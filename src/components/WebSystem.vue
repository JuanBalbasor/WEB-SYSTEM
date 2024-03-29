<template>

<div id="home" class="container-fluid">
    <div class="row">
        
        <div class="col-md-6 p-0 ">
            <!-- Image with background color -->
            <div class="image-container position-relative">
                <span class="initials"> &nbsp; &nbsp; B.V</span> <!-- Abbreviation -->
                <img class="image-content" src="/profile.jpg" alt="Portrait">

                <span class="contact-phrase">Contact me on this following accounts</span> <!-- Contact phrase -->

                <!-- PNG images for social media icons -->
                <div class="social-icons">
                    <!-- Facebook -->
                    <div class="social-icon-wrapper">
                        
                        <a href="https://www.facebook.com/b.ram.78" target="_blank">
                            <img src="facebook.png" alt="Facebook" class="social-icon">
                        </a>
            
                    </div>
                    <!-- Gmail -->
                    <div class="social-icon-wrapper">
                        
                        <a href="mailto:cardinaldema@gmail.com" target="_blank">
                            <img src="gmail.png" alt="Gmail" class="social-icon">
                        </a>
                        
                    </div>
                    <!-- Instagram -->
                    <div class="social-icon-wrapper">
                        
                        <a href="https://www.instagram.com/ke.on.b" target="_blank">
                            <img src="instagram.png" alt="Instagram" class="social-icon">
                        </a>
                       
                    </div>
                    <!-- Add more social media icons if needed -->
                </div>
            </div>
        </div>

        <div class="col-md-6 p-0"> 
            <!-- Navbar -->
            <nav class="navbar navbar-expand-lg sticky-top p-5">
                <div class="container-fluid mt-3">
                    <a class="navbar-brand fs-4 " href="#home">
                        <img src="graduated.png" alt="logo" height="50" class="me-2">
                        <span style="font-family: monospace;">Vicada's Portfolio</span>
                    </a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                        <ul class="navbar-nav">

                            <li class="nav-item">
                                <a class="nav-link fs-5 contact-link me-3" href="#about">About</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link fs-5 contact-link" href="#projects">Works</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </nav>
            
            <!-- Description -->
            <div class="p-5 mt-5 description-text">
                <div class="text-start mb-3">
                    <h4 class="mb-0">
                        <a class="text-dark fw-bold text-decoration-none" href="https://web.facebook.com/b.ram.78" target="_blank">Bram Vincent Vicada</a>
                    </h4>
                    <p class="text-muted mb-0">BSIT STUDENT, MAJOR IN PROGRAMMING</p> <!-- Subtitle -->
                </div>
                <div>
                    <p class="mb-0 mt-5 p-5" style="font-size: 1.3rem; line-height: 1.6;">
                        I'm a passionate computer studies student at 
                        <a class="text-dark fw-bold text-decoration-none" href="https://www.facebook.com/cpcofficial2005" target="_blank">Cordova Public College</a>
                        , driven by innovation and technology. 
                        I love experimenting with new programming languages and frameworks, collaborating on creative projects, 
                        and constantly expanding my skills to thrive in the evolving tech industry.
                        <span class="text-muted" style="font-size: 1.2rem; float: right; line-height: 10;" > "Life is either a daring adventure or nothing at all." - Helen Keller </span>
                    </p>
                </div>
            </div>
        </div>
    </div>
</div>

<div id="about">

    <div class="container-fluid">
        
        <div class="row p-5 mb-5">
            
            <!-- Header -->
            <div class="col-md-12 mb-3 text-center mb-5 mt-3">
                
                <h3 style="font-family: Arial, sans-serif; font-size: 30px; font-weight: bold; color: #333; text-transform: uppercase; letter-spacing: 1px; text-align: center; margin-bottom: 30px;">
                    About Me
                </h3>

            </div>

            <!-- About Me -->
            <div class="col-md-6">
                
                <div class="card p-5 mt-3 shadow-lg" style="background-color: rgb(0, 20, 39);">
                    <div class="card-body">

                        <img src="button.png" class="pin-icon" alt="Pin" style="position: absolute; top: 15px; left: 20px; width: 40px;">
                        
                        <div class="about-me-text text-start mt-3 text-white">
                            <p style="font-family: monospace; line-height: 1.8; font-size: 1.4rem;">

                                Hello there! I'm <b>Bram Vincent Vicada</b>, a computer studies student from <strong>Cordova Public College</strong>, driven by a fervent passion for technology and innovation.
                                <br><br> 
                                Constantly pushing boundaries, I immerse myself in exploring diverse programming languages, frameworks, 
                                and creative projects, fostering collaboration within the tech community. With adept adaptability, 
                                I tackle challenges head-on and deliver high-quality solutions. 
                                <br><br>
                                Committed to continuous learning, I thrive in dynamic environments, embracing new opportunities with diligence 
                                and a results-oriented approach.
                                <br><br> 
                                My journey in technology has honed my skills, equipping me to contribute positively to any project or team. 
                                With an unwavering work ethic and meticulous attention to detail, I strive for excellence, aiming to exceed 
                                expectations and deliver innovative solutions that meet user needs. 
                                <br><br>
                                Seeking reliability, innovation, and a proactive 
                                mindset? Look no further!
                            
                            </p>
                        </div>
                    </div>
                </div>
            </div>


            <!-- My Skills -->
            <div class="col-md-6 text-center">
                <div class="container">
                    <div class="row justify-content-evenly" style="margin-top:240px;">
                        <h3 class="text-center mb-4">Technologies I Know</h3>
                        <div class="col-lg-4 col-md-4 text-center py-5 my-3">

                            <div class="img-container">
                                <img src="laravel.png" width="60%" max-width="150px" title="Laravel" class=" mx-auto">
                                <span class="img-label">Laravel</span>
                            </div>
                        </div>
                        <div class="col-lg-4 col-md-4 text-center py-5 mt-5">
                            <div class="img-container">
                                <img src="php.png" width="60%" max-width="150px" title="PHP" class=" mx-auto">
                                <span class="img-label">PHP</span>
                            </div>
                        </div>
                        <div class="col-lg-4 col-md-4 text-center py-5 my-3">
                            <div class="img-container">
                                <img src="java-script.png" width="60%" max-width="150px" title="Javascript" class=" mx-auto">
                                <span class="img-label">Javascript</span>
                            </div>
                        </div>
                        <div class="col-lg-4 col-md-4 text-center py-5 my-3">
                            <div class="img-container">
                                <img src="mysql.png" width="60%" max-width="150px" title="SQL" class=" mx-auto">
                                <span class="img-label">MySQL</span>
                            </div>
                        </div>
                        <div class="col-lg-4 col-md-4 text-center py-5 my-3">
                            <div class="img-container">
                                <img src="java.png" width="60%" max-width="150px" title="JAVA" class=" mx-auto">
                                <span class="img-label">Java</span>
                            </div>
                        </div>
                        <div class="col-lg-4 col-md-4 text-center py-5 my-3">
                            <div class="img-container">
                                <img src="c-.png" width="60%" max-width="150px" title="C++" class=" mx-auto">
                                <span class="img-label">C++</span>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </div>

    </div>

</div>

<div id="projects" style="background-color: rgb(112, 141, 129); border-top: 3px solid black;">

    <h2 class="mt-3 p-5 mb-4 text-center fw-bold text-dark font-monospace ">Projects</h2>

    <div class="container-fluid">
        <div class="row mb-5 font-monospace">
            <div class="col-lg-3 offset-lg-0 col-md-8 offset-md-2 p-4">
                <div class="card border-0 round shadow" style="width: 100%; height: 100%;">
                    <div class="card-body">
                        <a href="https://github.com/JuanBalbasor/OOP2-final" class="text-dark text-decoration-none" target="_blank">
                            <img src="calculator.png" class="img-icon" alt="calcu">
                            <h5 class="mt-3">Online Shopping Money Calculator</h5>
                        </a>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 offset-lg-0 col-md-8 offset-md-2 p-4">
                <div class="card border-0 round shadow" style="width: 100%; height: 100%;">
                    <div class="card-body">
                        <a href="https://github.com/JuanBalbasor/IM2-final" class="text-dark text-decoration-none" target="_blank">
                            <img src="bookshelf.png" class="img-icon" alt="book">
                            <h5 class="mt-3">Student Library Management</h5>
                        </a>
                    </div>
                </div>
            </div>
            <div class="col-lg-3 offset-lg-0 col-md-8 offset-md-2 p-4">
                <div class="card border-0 round shadow" style="width: 100%; height: 100%;">
                    <div class="card-body">
                        <a href="https://github.com/JuanBalbasor/HCI" class="text-decoration-none text-dark" target="_blank">
                            <img src="kitty.png" class="img-icon" alt="kitty">
                            <h5 class="mt-3">Random Cat Image Generator</h5>
                        </a>  
                    </div>
                </div>
            </div>
            <div class="col-lg-3 offset-lg-0 col-md-8 offset-md-2 p-4">
                <div class="card border-0 round shadow" style="width: 100%; height: 100%;">
                    <div class="card-body">
                        <a href="https://github.com/JuanBalbasor/Sample-Layout" class="text-dark text-decoration-none" target="_blank">
                            <img src="web-design.png" class="img-icon" alt="design">
                            <h5 class="mt-3">Sample Login Layout</h5>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>

</div>

<footer class="footer" style="background-color: rgb(244, 213, 141); padding: 20px;">
    <div class="container">
        <div class="row align-items-center">
            <div class="col-md-6 text-start font-monospace">
                <!-- Telephone icon -->
                <img src="building.png" alt="building" style="width: 24px; height: 24px;">
                <!-- Sample established date -->
                <span style="margin-left: 20px;">Established: March 29, 2024</span>
            </div>
            <div class="col-md-6 text-end">
                <!-- Back to top link -->
                <a href="#home" style="text-decoration: none; color: black;">
                    <img src="graduated.png" alt="logo" height="30" class="me-2">
                    <span style="font-family: monospace;">Vicada's Portfolio</span>
                </a>
            </div>
        </div>
    </div>
</footer>


</template>

<script>
export default {
    data() {
        return {};
    }
};
</script>

<style>
    /* CSS to align image on the left and description on the right */
    .container-fluid {
      display: flex;
      justify-content: center;
    }
  
    .row {
      display: flex;
      flex-direction: row;
    }

    /* CSS for the image container */
    .image-container {
    background-color: rgb(0, 20, 39);
    padding: 190px;
    }

    /* CSS for the image inside the container */
    .image-content {
    width: 90%;
    }

    /* CSS to style the abbreviation */
    .initials {
        position: absolute;
        top: 100px; /* Adjust top position as needed */
        left: 50px; /* Adjust left position as needed */
        color: white;
        font-weight: bold;
        font-family: monospace;
        font-size: 1.5rem; /* Adjust font size as needed */
    }

    .container {
    margin-left: 10px;
    margin-right: 10px;
    }

    .nav-link:hover {
    font-family: monospace;
    font-weight: bold;
    }

    .navbar {
        background-color: rgb(112, 141, 129);
        border-bottom: 2px solid black;
    }

    .description-text strong{
        font-family: 'Arial', sans-serif;
        font-size: 1.2rem;
        line-height: 1.6;
        font-weight: bold;
    }

    .contact-link {
    transition: all 0.3s ease;
    }

    .contact-link:hover {
        background-color: rgb(191, 6, 3); /* Bootstrap danger color */
        color: white;
        padding: 0.5rem 1rem;
        border-radius: 20px; /* Adjust the value to change the roundness */
    }

    .img-container {
    position: relative;
    overflow: hidden;
    }

    .img-label {
        position: absolute;
        bottom: 10px;
        left: 50%;
        transform: translateX(-50%);
        font-family: Arial, sans-serif;
        font-size: 16px; 
        font-weight: bold;
        color: #fff; 
        background-color: rgba(0, 0, 0, 0.7); 
        padding: 5px 10px; 
        border-radius: 5px; 
        opacity: 0;
        transition: opacity 0.3s ease;
    }

    .img-container:hover .img-label {
        opacity: 5;
    }

    .zoom-in-effect {
        transition: transform 0.3s ease;
    }

    .img-icon {
    width: 300px; /* Adjust size as needed */
    height: auto;
    display: block;
    margin: 0 auto;
    }

    /* CSS for social icons */
    .social-icons {
        position: absolute;
        top: 85%;
        left: 50%;
        transform: translate(-50%, -50%);
        display: flex;
        flex-direction: row;
        justify-content: center; /* Center horizontally */
        align-items: center; /* Center vertically */
        gap: 10px;
    }

    .social-icon {
        width: 40px;
        height: auto;
        margin: 15px; /* Adjust the margin as needed */
    }

    .contact-phrase {
        display: block;
        text-align: center;
        font-family: monospace;
        color: white;
        margin-top: 35px; /* Adjust as needed */
    }

    .footer {
        position: fixed;
        bottom: 0;
        width: 100%;
    }

    .pin-icon {
    filter: brightness(0) invert(1);
    }
</style>
