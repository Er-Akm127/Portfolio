# Portfolio
//Portfolio Generators
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>omnifood</title>
    <link rel="stylesheet", type="text/css", href="vendors/css/normalize.css">
    <link rel="stylesheet" type="text/css", href="vendors/css/Grid.css">
    <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
    />
    <link href="vendors/css/ionicons.min.css" type="text/css" rel="stylesheet">
    <link rel="stylesheet" type="text/css" href="resource/css/style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&display=swap" rel="stylesheet">
</head>

<body>
    <header>
        <nav>
            <div class="row">
                <img src="resource/image/logo-white.png" alt="logo-white" class="logo-white">
                <img src="resource/image/logo.png" alt="logo-black" class="logo-black">
                <ul class="main-nav">
                    <li>
                        <a href="#features">Food Delivery</a>
                    </li>
                    <li>
                        <a href="#works">How it works</a>
                    </li>
                    <li>
                        <a href="#cities">Our cities</a>
                    </li>
                    <li>
                        <a href="#plans">Sign up</a>
                    </li>
                </ul>
            </div>
        </nav>
        <div class="header-text">
            <h1> Goodbye junk food.<br>Hello super healthy meal</h1>
            <a class="btn btn-full js--scroll-to-plans" href="#">I'm hungry</a>
            <a class="btn btn-border js--scroll-to-features" href="#">Show me more</a>
        </div>
    </header>
    <section class="section-features js--section-features" id="features">
        <div class="row">'
            <h2>Get food fast — not fast food.</h2>
            <p class="feature-text">
                Hello, we’re Omnifood, your new premium food delivery service. We know you’re always busy. No time for cooking. So let us take care of that, we’re really good at it, we promise!
            </p>
        </div>
        <div class="row js--features-animate">
            <div class="col span-1-of-4 box">
                <i class="ion-radio-waves icon-big"></i>
                <h3>Up to 365 days/year</h3>
                <p>Never cook again! We really mean that. Our subscription plans include up to 365 days/year coverage. You can also choose to order more flexibly if that's your style.</p>
            </div>
            <div class="col span-1-of-4 box">
                <i class="ion-android-time icon-big"></i>
                <h3>Ready in 20 minutes</h3>
                <p>
                    You're only twenty minutes away from your delicious and super healthy meals delivered right to your home. We work with the best chefs in each town to ensure that you're 100% happy.
                </p>
            </div>
            <div class="col span-1-of-4 box">
                <i class="ion-earth icon-big"></i>
                <h3>100% organic</h3>
                <p>
                    All our vegetables are fresh, organic and local. Animals are raised without added hormones or antibiotics. Good for your health, the environment, and it also tastes better!
                </p>
            </div>
            <div class="col span-1-of-4 box">
                <i class="ion-ios-cart icon-big"></i>
                <h3>Order anything</h3>
                <p>
                    We don't limit your creativity, which means you can order whatever you feel like. You can also choose from our menu containing over 100 delicious meals. It's up to you!
                </p>
            </div>
        </div>
    </section>
    <section class="section-meals">
        <ul class="meals-showcase clearfix">
            <li>
                <figure class="meal-photo">
                    <img src="resource/image/1.jpg" alt="Korean bibimbap with egg and vegetables">
                </figure>
            </li>
            <li>
                <figure class="meal-photo">
                    <img src="resource/image/2.jpg" alt="Simple italian pizza with cherry tomatoes">
                </figure>
            </li>
            <li>
                <figure class="meal-photo">
                    <img src="resource/image/3.jpg" alt="Chicken breast steak with vegetables">
                </figure>
            </li>
            <li>
                <figure class="meal-photo">
                    <img src="resource/image/4.jpg" alt="Autumn pumpkin soup">
                </figure>
            </li>
        </ul>
        <ul class="meals-showcase clearfix">
            <li>
                <figure class="meal-photo">
                    <img src="resource/image/5.jpg" alt="Paleo beef steak with vegetables">
                </figure>
            </li>
            <li>
                <figure class="meal-photo">
                    <img src="resource/image/6.jpg" alt="Healthy baguette with egg and vegetables">
                </figure>
            </li>
            <li>
                <figure class="meal-photo">
                    <img src="resource/image/7.jpg" alt="Burger with cheddar and bacon">
                </figure>
            </li>
            <li>
                <figure class="meal-photo">
                    <img src="resource/image/8.jpg" alt="Granola with cherries and strawberries">
                </figure>
            </li>
        </ul>
    </section>
    <section class="section-works" id="works">
        <div class="row js--phone-animate">
            <h2>How it works - Simple as 1, 2, 3</h2>
        </div>
        <div class="row">
            <div class="col span-1-of-2 step-box">
                <img src="resource/image/app-iPhone.png" class="phone-image">
            </div>
            <div class="col span-1-of-2 step-box">
                <div class="work-steps">
                    <div>1</div>
                    <p>Choose the subscription plan that best fits your needs and sign up today.</p>
                </div>
                <div class="work-steps">
                    <div>2</div>
                    <p>Order your delicious meal using our mobile app or website. Or you can even call us!</p>
                </div>
                <div class="work-steps">
                    <div>3</div>
                    <p>Enjoy your meal after less than 20 minutes. See you the next time!</p>
                </div>
                <a href="#" class="app-image"><img src="resource/image/download-app-android.png"></a>
                <a href="#" class="app-image"><img src="resource/image/app-store-img.jpg"></a>
            </div>
        </div>
    </section>
    <section class="cities" id="cities">
        <div class="row js--cities-animate">
            <h2>Cities</h2>
        </div>
        <div class="row">
        <div class="col span-1-of-4 box">
            <img src="resource/image/lisbon-3.jpg">
            <h3>Lisbon</h3>
            <div class="cities-steps small-class">
                <i class="ion-heart icon-small"></i>
                1600+ happy eaters 
            </div>
            <div class="cities-steps">
                <i class="ion-checkmark-round icon-small"></i>
                60+ top chefs
            </div>
            <div class="cities-steps">
                <i class="ion-social-twitter icon-small"></i>
                <a href="#">@omnifood_lx</a>
            </div>
        </div>
            <div class="col span-1-of-4 box">
                <img src="resource/image/san-francisco.jpg">
                <h3>San Francisco</h3>
                <div class="cities-steps small-class">
                    <i class="ion-heart icon-small"></i>
                    3700+ happy eaters
                </div>
                <div class="cities-steps">
                    <i class="ion-checkmark-round icon-small"></i>
                    160+ top chefs
                </div>
                <div class="cities-steps">
                    <i class="ion-social-twitter icon-small"></i>
                    <a href="#">@omnifood_sf</a>
                </div>
            </div>
            <div class="col span-1-of-4 box">
                <img src="resource/image/berlin.jpg">
                <h3>Berlin</h3>
                <div class="cities-steps">
                    <i class="ion-heart icon-small"></i>
                    2300+ happy eaters 
                </div>
                <div class="cities-steps">
                    <i class="ion-checkmark-round icon-small"></i>
                    110+ top chefs
                </div>
                <div class="cities-steps">
                    <i class="ion-social-twitter icon-small"></i>
                    <a href="#">@omnifood_berlin</a>
                </div>
            </div>
            <div class="col span-1-of-4 box">
                <img src="resource/image/london.jpg">
                <h3>London</h3>
                <div class="cities-steps">
                    <i class="ion-heart icon-small"></i>
                    1200+ happy eaters 
                </div>
                <div class="cities-steps">
                    <i class="ion-checkmark-round icon-small"></i>
                    50+ top chefs
                </div>
                <div class="cities-steps">
                    <i class="ion-social-twitter icon-small"></i>
                    <a href="#">@omnifood_london</a>
                </div>
            </div>
    </div>
    </section>
    <section class="section-testimonials">
        <div class="row">
            <h2>Our customers can't live without us</h2>
        </div>
        <div class="row">
            <div class="col span-1-of-3">
                <blockquote>
                    Omnifood is just awesome! I just launched a startup which leaves me with no time for cooking, so Omnifood is a life-saver. Now that I got used to it, I couldn't live without my daily meals!
                    <cite><img src="resource/image/customer-1.jpg">Alberto Duncan</cite>
                </blockquote>
            </div>
            <div class="col span-1-of-3">
                <blockquote>
                    Inexpensive, healthy and great-tasting meals, delivered right to my home. We have lots of food delivery here in Lisbon, but no one comes even close to Omifood. Me and my family are so in love!
                    <cite><img src="resource/image/customer-2.jpg">Joana Silva</cite>
                </blockquote>
            </div>
            <div class="col span-1-of-3">
                <blockquote>
                    I was looking for a quick and easy food delivery service in San Franciso. I tried a lot of them and ended up with Omnifood. Best food delivery service in the Bay Area. Keep up the great work!
                    <cite><img src="resource/image/customer-3.jpg">Milton Chapman</cite>
                </blockquote>
            </div>
        </div>
    </section>
    <section class="section-plans js--section-plans" id="plans">
        <div class="row js--plan-animate">
            <h2>Start eating healthy today</h2>
        </div>
        <div class="row">
            <div class="col span-1-of-3">
                <div class="plan-box">
                    <div>
                        <h3>Premiun</h3>
                        <p class="monthly-plan">399$ <span>/ month</span></p>
                        <p class="per-meal-plan">That’s only 13.30$ per meal</p>
                    </div>
                    <div>
                        <ul>
                            <li><i class="ion-ios-checkmark-empty icon-small"></i>1 meal every day</li>
                            <li><i class="ion-ios-checkmark-empty icon-small"></i>Order 24/7</li>
                            <li><i class="ion-ios-checkmark-empty icon-small"></i>Access to newest creations
                            </li>
                            <li><i class="ion-ios-checkmark-empty icon-small"></i>Free delivery
                            </li>
                        </ul>
                    </div>
                    <div>
                        <a href="#" class="btn btn-full">Signup Now!</a>
                    </div>
                </div>
            </div>
            <div class="col span-1-of-3">
                <div class="plan-box">
                    <div>
                        <h3>Pro</h3>
                        <p class="monthly-plan">149$ <span>/ month</span></p>
                        <p class="per-meal-plan">That’s only 14.90$ per meal</p>
                    </div>
                    <div>
                        <ul>
                            <li><i class="ion-ios-checkmark-empty icon-small"></i>1 meal 10 days/month</li>
                            <li><i class="ion-ios-checkmark-empty icon-small"></i>Order 24/7</li>
                            <li><i class="ion-ios-checkmark-empty icon-small"></i>Access to newest creations
                            </li>
                            <li><i class="ion-ios-checkmark-empty icon-small"></i>Free delivery
                            </li>
                        </ul>
                    </div>
                    <div>
                        <a href="#" class="btn btn-border">Signup Now!</a>
                    </div>
                </div>
            </div>
            <div class="col span-1-of-3">
                <div class="plan-box">
                    <div>
                        <h3>Starter</h3>
                        <p class="monthly-plan">19$ <span>/ meal</span></p>
                        <p class="per-meal-plan">&nbsp;</p>
                    </div>
                    <div>
                        <ul>
                            <li><i class="ion-ios-checkmark-empty icon-small"></i>1 meal</li>
                            <li><i class="ion-ios-checkmark-empty icon-small"></i>Order from 8 am to 12 pm</li>
                            <li><i class="ion-ios-close-empty icon-small"></i>NA
                            </li>
                            <li><i class="ion-ios-checkmark-empty icon-small"></i>Free delivery
                            </li>
                        </ul>
                    </div>
                    <div>
                        <a href="#" class="btn btn-border">Signup Now!</a>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="section-form">
        <div class="row">
            <h2>We're happy to hear from you</h2>
        </div>
        <div class="row">
            <form action="#" method="post" class="contact-form">
                <div class="row">
                    <div class="col span-1-of-3">
                        <label>Name</label>
                    </div>
                    <div class="col span-2-of-3">
                        <input type="text" name="name" id="name" placeholder="Your Name">
                    </div>
                </div>
                <div class="row">
                    <div class="col span-1-of-3">
                        <label>Email</label>
                    </div>
                    <div class="col span-2-of-3">
                        <input type="email" name="email" id="email" placeholder="Your Email Address">
                    </div>
                </div>
                <div class="row">
                    <div class="col span-1-of-3">
                        <label>How did you find us?</label>
                    </div>
                    <div class="col span-2-of-3">
                        <select name="findus" id="findus">
                            <option selected>Friends</option>
                            <option>Advertisements</option>
                            <option>Social Media</option>
                            <option>Newsletter</option>
                        </select>
                    </div>
                </div>
                <div class="row">
                    <div class="col span-1-of-3">
                        <label>Newsletter</label>
                    </div>
                    <div class="col span-2-of-3">
                        <input type="checkbox" name="newsletter" id="newsletter" checked>
                        Yes, Please!
                    </div>
                </div>
                <div class="row">
                    <div class="col span-1-of-3">
                        <label>Drop us a line</label>
                    </div>
                    <div class="col span-2-of-3">
                        <textarea name="text" id="text"></textarea>
                    </div>
                </div>
                <div class="row">
                    <div class="col span-1-of-3">
                        <label></label>
                    </div>
                    <div class="col span-2-of-3">
                        <input type="submit" name="submit" value=" Send it">
                    </div>
                </div>
            </form>
        </div>
    </section>
    <footer>
        <div class="row">
            <div class="col span-1-of-2">
                <ul class="footer-navs">
                    <li><a href="#">About us</a></li>
                    <li><a href="#">Blog</a></li>
                    <li><a href="#">Press</a></li>
                    <li><a href="#">iOS App</a></li>
                    <li><a href="#">Android App</a></li>
                </ul>
            </div>
            <div class="col span-1-of-2">
                <ul class="social-navs">
                    <li><a href="#"><i class="ion-social-facebook"></i></a></li>
                    <li><a href="#"><i class="ion-social-twitter"></i></a></li>
                    <li><a href="#"><i class="ion-social-googleplus"></i></a></li>
                    <li><a href="#"><i class="ion-social-instagram"></i></a></li>
                </ul>
            </div>
        </div>
        <div class="row">
            <p>Copywrite &copy; Omnifood, 2023</p>
        </div>
    </footer>
    
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
    <script src="vendors/js/jquery.waypoints.js"></script>
    <script src="resource/js/script.js"></script>

</body>
</html>

<!-- 

Section 8: Footer
Title: None

Navigation:
1. About us
2. Blog
3. Press
4. iOS App
5. Android App

Also include links to facebook, twitter, google+ and Instagram accounts.
  -->
