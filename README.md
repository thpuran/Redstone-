<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Portfolio Ebin</title>
    <link rel="stylesheet" href="style.css">
    <!----Font awesome cdn  font icon css -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css">
</head>
<body>
     <div class="hero-header">
        <div class="wrapper">
            <header>
                <div class="logo">
                    <i class="fa-solid fa-e"></i>
                    <div class="logo-text">Ebin</div>
                </div>
                <nav>
                    <div class="togglebtn">
                        <span></span>
                        <span></span>
                        <span></span>
                    </div>
                    <ul class="navlinks">
                        <li><a href="#">Home</a></li>
                        <li><a href="#">Portfolio</a></li>
                        <li><a href="#">Resume</a></li>
                        <li><a href="#">Blog</a></li>
                        <li><a href="#">Contact</a></li>
                    </ul>
                </nav>
            </header>
            <div class="container">
                 <div class="hero-pic">
                    <img src="/storage/emulated/0/Download/IMG-20250320-WA0015-removebg-preview (1).png" alt="profile pic">
                 </div>
                 <div class="hero-text">
                    <h5>Hi I'm <span class="input">Frontend Developer</span></h5>
                    <h1>Ebin</h1>
                    <p> I am an AI Developer, Web Developer, and Cybersecurity Enthusiast with a strong foundation in multiple programming languages, including Python, JavaScript, C++, and more. I specialize in building intelligent solutions, secure web applications, and innovative digital experiences.

With expertise in both front-end and back-end development, I create responsive, user-friendly websites while ensuring security best practices. My passion for AI drives me to develop machine learning models, chatbots, and automation tools that enhance user interaction and business efficiency.

I am always eager to take on new challenges, whether it's developing AI-driven applications, securing digital assets, or crafting high-performance websites. Let’s collaborate and bring ideas to life!
                    </p>

                    <div class="btn-group">
                       <a href="#" class="btn active">Download code</a>
                       <a href="#" class="btn">Contact</a>
                    </div>

                    <div class="social">
                        <a href="#"><i class="fa-brands fa-facebook"></i></a>
                        <a href="#"><i class="fa-brands fa-linkedin"></i></a>
                        <a href="#"><i class="fa-brands fa-instagram"></i></a>
                        <a href="#"><i class="fa-brands fa-dribbble"></i></a>
                        <a href="#"><i class="fa-brands fa-pintrest"></i></a>
                    </div>
                 </div>
            </div>
        </div>
     </div>
     <!---typed js for typing text effect-->
     <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.10/typed.min.js"></script>
     <script>
        /** creating button click show hide navbar **/
        var togglebtn=document.querySelector(".togglebtn");
        var nav=document.querySelector(".navlinks");
        var links=document.querySelector(".navlinks li");

        togglebtn.addEventListener("click", function(){
            this.classList.toggle("click");
            nav.classList.toggle("open");
        })

        var typed=new Typed(".input",{
            strings:["Frontend Developer","blackend Developer","Web Developer","enthical hacker","AI Developer"],
            typedSpeed:70,
            backSpeed:55,
            loop:true
        })
     </script>
</body>
</html>
