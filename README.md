<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio website Landing Page</title>
    <link rel="stylesheet" href="./style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
        integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
        <link rel="stylesheet" href="./cv.html">
</head>

<body>

    <div class="container">
        <div class="header">

            <div class="logo">
                <h1>Nikhil's<span>Landing-page</span></h1>
            </div>

            <div class="navlinks">
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Portfolio</a></li>
                    <li><a href="#">Product</a></li>

                </ul>
            </div>

            <a href="#" class="btn">Contact</a>

        </div>

        <div class="main-content">

            <div class="main">
                <div class="left">
                    <div class="line"></div>
                    <h1>I'M Nikhil Kolhe</h1>
                    <h2>A <span class="auto-type"></span></h2>

                    <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates consequatur nihil recusandae
                        expedita voluptatem atque beatae, consectetur obcaecati voluptatum illum quae, libero,
                        aspernatur adipisci ducimus facilis unde saepe eos fugiat!
                    </p>
                    <a href="./cv.html" class="btn btn-primary">Downlaod Cv</a>
                    <a href="" class="btn btn-primary">Browse Portfolio</a>

                </div>

                <div class="right">
                    <div class="image">
                        <img src="./WhatsApp_Image_2024-01-03_at_3.32.03_PM-removebg-preview.png" alt="">
                    </div>
                </div>


            </div>

            <div class="social">
                <div class="social-link">
                    <i class="fa-brands fa-instagram"></i>
                </div>
                <div class="social-link">
                    <i class="fa-brands fa-linkedin"></i>
                </div>
                <div class="social-link">
                    <i class="fa-brands fa-twitter"></i>
                </div>
                <div class="social-link">
                    <i class="fa-brands fa-telegram"></i>
                </div>
                <div class="social-link">
                    <i class="fa-brands fa-github"></i>
                </div>
            </div>

        </div>


    </div>

    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>

    <script>
        var typed = new Typed(".auto-type", {

            strings: ["Developer", "Creator", "Gamer"],
            typeSpeed: 150,
            backSpeed: 150,
            loop: true
        })
    </script>

</body>
