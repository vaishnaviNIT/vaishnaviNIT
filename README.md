<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Code Lantern | Home</title>
    <link rel="stylesheet" href="./css/style.css">
    <link rel="shortcut icon" href="./img/fav.ico" type="image/x-icon">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
        integrity="sha512-c42qTSw/wPZ3/5LBzD+Bw5f7bSF2oxou6wEb+I/lqeaKV5FDIfMvvRp772y4jcJLKuGUOpbJMdg/BTl50fJYAw=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>

</head>

<body>
    <!-- <h1>Hello Lantern</h1> -->
    <header>
        <!-- Logo for the Navbar and the Home Page -->
        <div class="container">
            <div id="branding" class="logo">
                <img src="./img/—Pngtree—red and black logo_5517319.png" alt="brand logo" id="logo"
                    class="animate__jello animate__animated">
                <h1 class="animate__lightSpeedInRight animate__animated"><span class="highlight">Code</span> Lantern
                </h1>
            </div>

            <!-- Navbar -->
            <nav>
                <ul>
                    <li class="current"><a href="./index.html">Home</a></li>
                    <li><a href="./components/about.html">About Us</a></li>
                    <li><a href="./components/solutions.html">Solutions</a></li>
                    <li><a href="./components/contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>


    <!-- showcase  -->
    <section id="showcase">
        <div class="background"></div>
        <div class="container">
            <h1>Web Dev Company</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga placeat, possimus fugit iusto amet error
                debitis consectetur recusandae neque vel ipsum rerum molestiae alias eius aut architecto assumenda hic
                nostrum? Laborum animi nostrum provident. Quisquam, soluta ducimus magni hic et, ullam ut debitis optio
                deserunt illum laborum porro vitae eum! Nam laboriosam, dolor iste dolorum earum tenetur qui est facilis
                adipisci corporis animi doloremque quae id dolores dolore sequi error iusto amet fugit facere tempore
                illo fuga. Enim eaque voluptatem aliquam a autem culpa? Quae in sapiente molestias facere ipsam eius
                nobis ipsa repellat expedita tenetur modi, doloremque libero consectetur!</p>
        </div>
    </section>

    <!-- newsletter -->
    <section id="newsletter">
        <div class="container">
            <h1>Code Lantern Newsletter</h1>
            <form action="">
                <input type="email" placeholder="john@email.com" required>
                <button type="submit" class="button_1">Subscribe</button>
            </form>
        </div>
    </section>

    <!-- boxes -->
    <section id="boxes">
        <div class="container" id="box-holder">
            <div class="box shadow">
                <img src="https://www.freepnglogos.com/uploads/logo-website-png/logo-website-website-logo-png-transparent-background-background-15.png"
                    alt="Code Lantern Logo" class="tech-icons">
                <h3>Web Design</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim cum quos autem dolorum nihil modi iure
                    aut nobis ratione beatae.</p>
            </div>
            <div class="box shadow">
                <img src="./img/web-dev.png" alt="Code Lantern Logo" class="tech-icons">
                <h3>Web Development</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci accusamus ex necessitatibus
                    voluptates neque est harum excepturi at consequatur sint?</p>
            </div>
            <div class="box shadow">
                <img src="https://www.transparentpng.com/thumb/web-hosting/ilc5wD-web-hosting-hd-photo-png.png"
                    alt="Web hosting logo" class="tech-icons">
                <h3>Web Hosting</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci accusamus ex necessitatibus
                    voluptates neque est harum excepturi at consequatur sint?</p>
            </div>
        </div>
    </section>

    <footer>
        <p>Say hi <i class='bx bxs-ghost bx-tada'></i> to us in these platform.</p>
        <ul class="social">
            <li class="social-icons"><a href="http://www.facebook.com"><i class='bx bxl-facebook'></i></a></li>
            <li class="social-icons"><a href="http://www.instagram.com"><i class='bx bxl-instagram'></i></a></li>
            <li class="social-icons"><a href="http://www.linkedin.com"><i class='bx bxl-linkedin'></i></a></li>
            <li class="social-icons"><a href="http://www.twitter.com"><i class='bx bxl-twitter'></i></a></li>
        </ul>
        <p>Code Lantern &copy; 2023 All Rights Reserved.</p>
    </footer>
<script> configObj = {"buttonD":"M8 18.568L10.8 21.333 16 16.198 21.2 21.333 24 18.568 16 10.667z","buttonT":"translate(-1148 -172) translate(832 140) translate(32 32) translate(284)","shadowSize":"0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04)","roundnessSize":"6px","buttonDToBottom":"40px","buttonDToRight":"40px","selectedBackgroundColor":"#c0ff9e","selectedIconColor":"#626a7e","buttonWidth":"48px","buttonHeight":"48px","svgWidth":"40px","svgHeight":"40px"};function createButton(obj, pageSimulator) {    const body = document.querySelector("body");    backToTopButton = document.createElement("span");    backToTopButton.classList.add("softr-back-to-top-button");    backToTopButton.id = "softr-back-to-top-button";    pageSimulator      ? pageSimulator.appendChild(backToTopButton)      : body.appendChild(backToTopButton);    backToTopButton.style.width = obj.buttonWidth;    backToTopButton.style.height = obj.buttonHeight;    backToTopButton.style.marginRight = obj.buttonDToRight;    backToTopButton.style.marginBottom = obj.buttonDToBottom;    backToTopButton.style.borderRadius = obj.roundnessSize;    backToTopButton.style.boxShadow = obj.shadowSize;    backToTopButton.style.color = obj.selectedBackgroundColor;    backToTopButton.style.backgroundColor = obj.selectedBackgroundColor;    pageSimulator ? backToTopButton.style.position = "absolute" : backToTopButton.style.position = "fixed";    backToTopButton.style.outline = "none";    backToTopButton.style.bottom = "0px";    backToTopButton.style.right = "0px";    backToTopButton.style.cursor = "pointer";    backToTopButton.style.textAlign = "center";    backToTopButton.style.border = "solid 2px currentColor";    backToTopButton.innerHTML =      '<svg class="back-to-top-button-svg animate__jello animate__animated" xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32" > <g fill="none" fill-rule="evenodd"> <path d="M0 0H32V32H0z" transform="translate(-1028 -172) translate(832 140) translate(32 32) translate(164) matrix(1 0 0 -1 0 32)" /> <path class="back-to-top-button-img" fill-rule="nonzero" d="M11.384 13.333h9.232c.638 0 .958.68.505 1.079l-4.613 4.07c-.28.246-.736.246-1.016 0l-4.613-4.07c-.453-.399-.133-1.079.505-1.079z" transform="translate(-1028 -172) translate(832 140) translate(32 32) translate(164) matrix(1 0 0 -1 0 32)" /> </g> </svg>';    backToTopButtonSvg = document.querySelector(".back-to-top-button-svg");    backToTopButtonSvg.style.verticalAlign = "middle";    backToTopButtonSvg.style.margin = "auto";    backToTopButtonSvg.style.justifyContent = "center";    backToTopButtonSvg.style.width = obj.svgWidth;    backToTopButtonSvg.style.height = obj.svgHeight;    backToTopButton.appendChild(backToTopButtonSvg);    backToTopButtonImg = document.querySelector(".back-to-top-button-img");    backToTopButtonImg.style.fill = obj.selectedIconColor;    backToTopButtonSvg.appendChild(backToTopButtonImg);    backToTopButtonImg.setAttribute("d", obj.buttonD);    backToTopButtonImg.setAttribute("transform", obj.buttonT);        if(!pageSimulator) {      backToTopButton.style.display = "none";      window.onscroll = function() {        if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {          backToTopButton.style.display = "block";        } else {          backToTopButton.style.display = "none";        }      };        backToTopButton.onclick = function() {        document.body.scrollTop = 0;        document.documentElement.scrollTop = 0;      };    }  };document.addEventListener("DOMContentLoaded", function() { createButton(configObj, null); });</script>
</body>

</html>
