# Amazon-project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="navbar">
            <div class="navlogo border">
                <div class="logo"></div>
            </div>
            <div class="nav-address border">
                <p class="add-first">Deliver to</p>
                <div class="add-icon">
                    <i class="fa-solid fa-location-dot"></i>
                    <p class="add-second">India</p>
                </div>
            </div>
            <div class="nav-search">
                <select class="search-select">
                    <option>All</option>
                </select>
                <input placeholder="Search Amazon" class="search-input">
                <div class="search-icon">
                    <i class="fa-solid fa-magnifying-glass"></i>
                </div>
            </div>
            <div class="nav-signin border">
                <p><span>Hello, sign in</span></p>
                <p class="nav-second"> Account & Lists</p>
            </div>
            <div class="nav-return border">
                <p><span>Returns</span></p>
                <p class="nav-second">& Orders</p>
            </div>
            <div class="nav-cart border">
                <i class="fa-solid fa-cart-shopping"></i>
                Cart
            </div>
        </div>
        <div class="panel">
            <div class="panel-all">
                <i class="fa-solid fa-bars"></i>
                All
            </div>
            <div class="panel-ops">
                <p>Today's deals</p>
                <p>Customer Service</p>
                <p>Registry</p>
                <p>Gift Cards</p>
                <p>Sell</p>
            </div>
            <div class="panel-deals">
                Shop deals in Electronics
            </div>
        </div>
    </header>
    <div class="hero-section">
        <div class="hero-msg">
            <p>You are on amazon.com. You can also shop on Amazon India for millions of products with fast local delivery. <a>Click here to go to amazon.in</a></p>
        </div>
    </div>
    <div class="shop-section">
        <div class="box">
            <div class="box-content">
                <h2>Deals In PC</h2>
                <div class="box-img" style="background-image: url('box1.jpg');"></div>
                <p>See more</p>
            </div>
        </div>
        <div class="box">
            <div class="box-content">
                <h2>Toys</h2>
                <div class="box-img" style="background-image: url('box2.jpg');"></div>
                <p>See more</p>
            </div>
        </div>
        <div class="box">
            <div class="box-content">
                <h2>Fun Things </h2>
                <div class="box-img" style="background-image: url('box3.jpg');"></div>
                <p>See more</p>
            </div>
        </div>
        <div class="box">
            <div class="box-content">
                <h2>Fashion Clothes</h2>
                <div class="box-img" style="background-image: url('box4.jpg');"></div>
                <p>See more</p>
            </div>
        </div>
        <div class="box">
            <div class="box-content">
                <h2>Gaming Gadgets</h2>
                <div class="box-img" style="background-image: url('box5.jpg');"></div>
                <p>See more</p>
            </div>
        </div>
        <div class="box">
            <div class="box-content">
                <h2>Electronic Gadgets</h2>
                <div class="box-img" style="background-image: url('box6.jpg');"></div>
                <p>See more</p>
            </div>
        </div>
        <div class="box">
            <div class="box-content">
                <h2>Personal Care</h2>
                <div class="box-img" style="background-image: url('box7.jpg');"></div>
                <p>See more</p>
            </div>
        </div>

        <div class="box">
            <div class="box-content">
                <h2>Trackers and Samrtwatches</h2>
                <div class="box-img" style="background-image: url('box8.jpg');"></div>
                <p>See more</p>
            </div>
        </div>
    </div>
    <footer>
        <div class="foot-panel1">
            Back To Top
        </div>
        <div class="foot-panel2">
            <ul>
                <p>Get to Know Us</p>
                <a>Careers</a>
                <a>Blog</a>
                <a>About Amazon</a>
                <a>Investor Relations</a>
                <a>Amazon Devices</a>
                <a>Amazon Science</a>
            </ul>
            <ul>
                <p>Make Money with Us</p>
                <a>Sell products on Amazon</a>
                <a>Sell on Amazon Business</a>
                <a>Sell apps on Amazon</a>
                <a>Become an Affiliate</a>
                <a>Advertise Your Products</a>
                <a>Self-Publish with Us</a>
                <a>Host an Amazon Hub</a>
            </ul>
            <ul>
                <p>Amazon Payment Products</p>
                <a>Amazon Business Card</a>
                <a>Shop with points</a>
                <a>Reload Your Balance</a>
                <a>Amazon Currency Converter</a>
            </ul>
            <ul>
                <p>Let Us Help You</p>
                <a>Amazon and COVID-19</a>
                <a>Your Account</a>
                <a>Your Orders</a>
                <a>Shipping Rates & Policies</a>
                <a>Return & Replacement</a>
                <a>Manage Your Content and Devices</a>
                <a>Amazon Assiatant</a>
                <a>Help</a>
            </ul>
        </div>
        <div class="foot-panel3">
            <div class="logo"></div>
        </div>
        <div class="foot-panel4">
            <div class="pages">
                <a>Conditions of Use</a>
                <a>Privacy Notice</a>
                <a>Your Ads Privacy Choices</a>
            </div>
            <div class="copyright">
                © 1996-2024, Amazon.com, Inc. or its affiliates
            </div>
        </div>
    </footer>
</body>
</html>
CSS CODE:
*{
    margin: 0;
    font-family: Arial;
    border: border-box;
}
.navbar{
    height: 60px;
    background-color: #0f1111;
    color: white;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}
/* box1 */
.navlogo{
    height: 50px;
    width: 113px;
}
.logo{
    background-image: url("download.png");
    background-size: cover;
    height: 50px;
    width: 100%;
}
.border{
    border: 1px solid transparent;
}
.border:hover{
    border: 1px solid white;
}
/* box2 */
.add-first{
    color: #cccccc;
    font-size: 0.85rem;
    margin-left: 15px;
}
.add-second{
    font-size: 1rem;
    margin-left: 3px;
}
.add-icon{
    display: flex;
    align-items: center;
}
/* box3 */
.nav-search{
    display: flex;
    justify-content: space-evenly;
    background-color: orange;
    width: 620px;
    height:40px ;
    border-radius: 4px;    
}
.search-select{
    background-color: #f3f3f3;
    width: 50px;
    text-align: center;
    border-top-left-radius: 4px;
    border-bottom-left-radius: 4px;
    border: none;
}
.search-input{
    width: 100% ;
    font-size: 1rem;
    border: none;
}
.search-icon{
    width: 45px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.2rem;
    background-color: #f8af4f;
    border-top-right-radius: 4px;
    border-bottom-right-radius: 4px;
    color: #0f1111;
}
.nav-search:hover{
    border: 2px solid orange;
}

/* box4 */
span{
    font-size: 0.7rem;
}
.nav-second{
    font-size: 0.85rem;
    font-weight: 700;
}
/* box6 */
.nav-cart i{
    font-size: 30px;
}
.nav-cart{
    font-size: 0.85rem;
    font-weight: 700;
}
/* panel */
.panel{
    height: 42px;
    background-color: #232F3E;
    display: flex;
    color: white;
    align-items: center;
    justify-content: space-evenly;
}
.panel-ops p{
    display: inline;
    margin-left: 20px;
}
.panel-ops{
    width: 70%;font-size: 0.85rem;
}
.panel-deals{
    font-size: 0.9rem;
    font-weight: 700;
}
/* hero-section */
.hero-section{
    background-image: url(hero.jpg);
    height: 400px;
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: flex-end;
}
.hero-msg{
    background-color: white;
    color:black;
    font-size: 0.85rem;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    width: 80%;
    margin-bottom: 25px;
}
.hero-msg a{
    color: #007185;
}

/* shop-section */
.shop-section{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    background-color: rgb(223, 223, 223);
}
.box{
    /* border: 2px solid black; */
    height: 350px;
    width: 23%;
    background-color: white;
    padding: 20px 0px 15px;
    margin-top: 5px;
}
.box-img{
    height: 240px; 
    background-size: contain;
    background-repeat: no-repeat; 
    margin-top: 1rem;
    margin-bottom: 1rem; 
}
.box-content{
    margin-left: 1.5rem;
    margin-right: 1.5rem;
}
.box-content p{
    color: rgb(156, 156, 215);
}
footer{
    margin-top: 15px;
}
.foot-panel1{
    background-color:#37475a;
    color: white;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 0.85rem;
}
.foot-panel2{
    background-color: #222F3d;
    color: white;
    height: 300px;
    display: flex;
    justify-content: space-evenly;
}
ul{
    margin-top: 20px;
}
ul a{
    display: block;
    font-size: 0.85rem;
    margin-top: 10px;
    color: #DDDDDD;
}

.foot-panel3{
    background-color: #222f3d;
    color: white;
    border-top: 0.5px solid white ;
    height: 70px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.logo{
    background-image: url("download.png");
    background-size: cover;
    height: 50px;
    width: 120px;
}
.foot-panel4{
    background-color: #0f1111;
    color: white;
    height: 75px;
    font-size: 0.65rem;
    text-align: center;
    /* display: flex;
    justify-content: center;
    align-items: center; */
}
.pages{
    padding-top: 25px ;
}
.copyright{
    padding-top: 5px ;
}
