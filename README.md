<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FOOD HUB</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" media="screen and (max-width: 1440px)" href="css/phone.css">
    <link href="https://fonts.googleapis.com/css2?family=Bree+Serif&family=Roboto+Condensed:wght@300&display=swap"
        rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Baloo+Bhai+2&display=swap" rel="stylesheet">
</head>

<body>
    <nav id="navbar">
        <div id="logo">
            <img src="img/main_logo.png" alt="FoodHub.com">

        </div>
        <ul>
            <li class="item"><a href="#home">Home</a></li>
            <li class="item"><a href="#services-container">Services</a></li>
            <li class="item"><a href="#client-section">Clients</a></li>
            <li class="item"><a href="#contact">Contact Us</a></li>
        </ul>
    </nav>
    <section id="home">
        <h1 class="h-primary">Welcome to FOOD HUB </h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sed sint, ratione ea a fugiat adipisci ipsa fuga
            debitis necessitatibus accusamus?</p>
        <button class="btn">order</button>
    </section>
    
    <section id="services-container">
        <h1 class="h-primary center">Our Services</h1>
        <div id="services">
            <div class="box">
                <img src="img/img2.jpg" alt="">
                <h2 class="h-secondary center">Food Ordering</h2>
                <p class="center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore optio nesciunt,
                    debitis soluta quae nemo magnam fuga consectetur expedita hic et similique esse ut ipsam culpa
                    molestiae molestias dolorem sint.</p>
            </div>
            <div class="box">
                <img src="img/img1.jpg" alt="">
                <h2 class="h-secondary center">Food Catering</h2>
                <p class="center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore optio nesciunt,
                    debitis soluta quae nemo magnam fuga consectetur expedita hic et similique esse ut ipsam culpa
                    molestiae molestias dolorem sint.</p>
            </div>
            <div class="box">
                <img src="img/img3.png" alt="">
                <h2 class="h-secondary center">Bulk Ordering</h2>
                <p class="center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore optio nesciunt,
                    debitis soluta quae nemo magnam fuga consectetur expedita hic et similique esse ut ipsam culpa
                    molestiae molestias dolorem sint.</p>
            </div>
        </div>
    </section>
    
    <section id="client-section">
        <h4 class="h-primary center">Our Clients</h4>
        <div id="clients">
            <div class="client-item">
                <img src="img/apple_logo.jpg" alt="">
            </div>
            <div class="client-item">
                <img src="img/microsoft_logo.png" alt="">
            </div>
            <div class="client-item">
                <img src="img/google_logo.png" alt="">
            </div>
            <div class="client-item">
                <img src="img/facebook_logo.png" alt="">
            </div>
        </div>
    </section>
    
    <section id="contact">
        <h1 class="h-primary center">Contact Us</h1>
        <div id="contact-box">
            <form action="">
                <div class="form-group">
                    <label for="name">Name</label>
                    <input type="text" name="name" id="name" placeholder="Enter Your Name">
                </div>
                <div class="form-group">
                    <label for="name">Phone Number</label>
                    <input type="number" name="Phone Number" id="name" placeholder="Enter Your Phone Number">
                </div>
                <div class="form-group">
                    <label for="name">Email-ID</label>
                    <input type="text" name="Email-ID" id="name" placeholder="Enter Your Email-ID">
                </div>
                <div class="form-group">
                    <label for="name">Feedback</label>
                    <textarea name="Feedback" id="feedback" cols="30" rows="10" placeholder="Write Your Feedback"></textarea>>
                </div>
            </form>
        </div>
    </section>
    <footer>
        <div class="center">
            Copyright &copy foodhub.com All right reserved!
        </div>
    </footer>
</body>

</html>
