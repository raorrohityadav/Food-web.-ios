<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="Foodweb.css">
    <link href="https://fonts.googleapis.com/css2?family=Abril+Fatface&family=Catamaran:wght@200&family=Courgette&family=Edu+TAS+Beginner:wght@700&family=Lato:wght@300;900&family=Mukta:wght@700&family=Mulish:wght@300&family=Open+Sans&family=PT+Sans:ital,wght@1,700&family=Poppins:wght@300&family=Raleway:wght@100&family=Roboto&family=Roboto+Condensed:wght@700&family=Roboto+Slab&display=swap"rel="stylesheet">
    <script src="https://kit.fontawesome.com/f30fac2c61.js" crossorigin="anonymous"></script>

</head>
<body>
    <div class="container">
        <nav>
            <div class="logo">
                <h1>Food HUB</h1>
            </div>
            <div class="input">
                <input type="text" value="" id="inp" placeholder="Search Here ..." onkeyup="myFun()">
                <i class="fa-solid fa-magnifying-glass"></i>
            </div>
            <div class="icon">
                <i onclick="login()" class="fa-solid fa-user"></i>
                <i class="fa-solid fa-cart-shopping"></i>
                <i onclick="nav()" class="fa-solid fa-bars"></i>
            </div>
        </nav>


        <div class="login">
            <h2>Log In </h2>
            <input type="text" placeholder="Enter Your Name">
            <input type="password" placeholder="Enter Password"> <br>
            <button>Log In</button>

        </div>
        <div class="nav">
            <p>Home</p>
            <p>Foods</p>
            <p>Blog</p>
            <p>Customer</p>


        </div>

        <!-- main Page -->

        <div class="main">
            <div class="text">
                <h1>Simple & Tasty Recipes</h1>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Placeat Repellat consectetur elit. Placeat Repellat voluptas eligendi rerum est quibusdam tempora beatae molestias dicta.</p>
                <button>Explore More</button>
            </div>
            <img src="burger (2).png" alt="">
        </div>

        <!--  Card Food -->

        <table>
            <tr>
                <td>
                    <div class="head">
                        <h1>Our <span>Foods</span></h1>
                    </div>
                    <div class="crd">
                        <div class="card">
                            <img src="fds (1).jpg" alt="">
                            <h2>299 Rupees Only</h2>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem, aspernatur iusto.</p>
                            <button>Order Now</button>
                        </div>
                        <div class="card">
                            <img src="fds (2).jpg" alt="">
                            <h2>299 Rupees Only</h2>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem, aspernatur iusto.</p>
                            <button>Order Now</button>
                        </div>
                        <div class="card">
                            <img src="fds (7).jpg" alt="">
                            <h2>299 Rupees Only</h2>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem, aspernatur iusto.</p>
                            <button>Order Now</button>
                        </div>
                    </div>

                    <div class="crd">
                        <div class="card">
                            <img src="fds (4).jpg" alt="">
                            <h2>299 Rupees Only</h2>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem, aspernatur iusto.</p>
                            <button>Order Now</button>
                        </div>
                        <div class="card">
                            <img src="fds (5).jpg" alt="">
                            <h2>299 Rupees Only</h2>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem, aspernatur iusto.</p>
                            <button>Order Now</button>
                        </div>
                        <div class="card">
                            <img src="fds (6).jpg" alt="">
                            <h2>299 Rupees Only</h2>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem, aspernatur iusto.</p>
                            <button>Order Now</button>
                        </div>
                    </div>
                </td>


            </tr>

            <tr>
                <td>
                    <div class="head">
                        <h1>Our <span>Blogs</span></h1>
                    </div>
                    <div class="crd">
                        <div class="blog">
                            <img src="fds (6).jpg" alt="">
                            <h2>Fact About Indian Food</h2>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem, aspernatur iusto.</p>
                            <a href="https://www.littleindiaofdenver.com/blog/7-facts-you-never-knew-about-indian-food/">Read More</a>
                        </div>
                        <div class="blog">
                            <img src="fds (4).jpg" alt="">
                            <h2>Diffrent Type of Burger</h2>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem, aspernatur iusto.</p>
                            <a href="https://www.finedininglovers.com/article/burger-types-famous-to-make">Read More</a>
                        </div>
                        <div class="blog">
                            <img src="fds (7).jpg" alt="">
                            <h2>Delicious Checken Recipes</h2>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem, aspernatur iusto.</p>
                            <a href="https://themodernproper.com/60-best-chicken-breast-recipes">Read More</a>
                        </div>
                    </div>
                </td>
            </tr>
        </table>

        <!-- Customer Review -->


        <div class="head">
            <h1>Customer <span>Review</span></h1>
        </div>
        <div class="review">

            <div class="customer">
                <img src="men (1).jpg" alt=""> <br>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-regular fa-star-half-stroke"></i>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione facere modi, repudiandae nostrum obcaecati quo?</p>
                
            </div>
            <div class="customer">
                <img src="men (2).jpg" alt=""> <br>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-regular fa-star-half-stroke"></i>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione facere modi, repudiandae nostrum obcaecati quo?</p>
                
            </div>
            <div class="customer">
                <img src="men (3).jpg" alt=""> <br>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-regular fa-star-half-stroke"></i>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione facere modi, repudiandae nostrum obcaecati quo?</p>
                
            </div>

            
        </div>
        <div class="btn">
            <button onclick="pre()">Prev</button>
            <button onclick="next()">Next</button>

        </div>

        <div class="footer">
            <div class="txt">
                <h2>About US</h2>
                <p>Lorem ipsum dolor sit amet <br> consectetur adipisicing elit. Cumque</p>
                <p>Service</p>
                <p>Customer</p>
                <p>Foods</p>

            </div>
            <div class="txt">
                <h2>About US</h2>
                <p>Product</p>
                <p>Service</p>
                <p>Customer</p>
                <p>Foods</p>

            </div>
            <div class="txt">
                <h2>About US</h2>
                <p>Near</p>
                <p>Service</p>
                <p>Customer</p>
                <p>Foods</p>

            </div>
            <div class="txt">
                <h2>About US</h2>
                <p>Websites</p>
                <p>Service</p>
                <p>Customer</p>
                <p>Foods</p>

            </div>
        </div>
    </div>
    <script src="Foodweb.js"></script>
</body>
</html>
