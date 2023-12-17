# Ex.07 Software Product Company Website
## Date:17.12.2023

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <title>Webpage Design</title>
    <link rel="stylesheet" href="style.css">
</head>
<style>
    *{
    margin: 0;
    padding: 0;
}

.main{
    width: 100%;
    background-color: #12172b;
    background-position: center;
    background-size: cover;
    height: 100vh;
}

.navbar{
    width: 1200px;
    height: 75px;
    margin: auto;
}

.icon{
    width: 200px;
    float: left;
    height: 70px;
}

.logo{
    color: #ff7200;
    font-size: 35px;
    font-family: Arial;
    padding-left: 20px;
    float: left;
    padding-top: 10px;
    margin-top: 5px
}

.menu{
    width: 400px;
    float: left;
    height: 70px;
}

ul{
    float: left;
    display: flex;
    justify-content: center;
    align-items: center;
}

ul li{
    list-style: none;
    margin-left: 62px;
    margin-top: 27px;
    font-size: 14px;
}

ul li a{
    text-decoration: none;
    color: #fff;
    font-family: Arial;
    font-weight: bold;
    transition: 0.4s ease-in-out;
}

ul li a:hover{
    color: #ff7200;
}

.search{
    width: 330px;
    float: left;
    margin-left: 270px;
}

.srch{
    font-family: 'Times New Roman';
    width: 200px;
    height: 40px;
    background: transparent;
    border: 1px solid #ff7200;
    margin-top: 13px;
    color: #fff;
    border-right: none;
    font-size: 16px;
    float: left;
    padding: 10px;
    border-bottom-left-radius: 5px;
    border-top-left-radius: 5px;
}

.btn{
    width: 100px;
    height: 40px;
    background: #ff7200;
    border: 2px solid #ff7200;
    margin-top: 13px;
    color: #fff;
    font-size: 15px;
    border-bottom-right-radius: 5px;
    border-bottom-right-radius: 5px;
    transition: 0.2s ease;
    cursor: pointer;
}
.btn:hover{
    color: #000;
}

.btn:focus{
    outline: none;
}

.srch:focus{
    outline: none;
}

.content{
    width: 1200px;
    height: auto;
    margin: auto;
    color: #fff;
    position: relative;
}

.content .par{
    padding-left: 20px;
    padding-bottom: 25px;
    font-family: Arial;
    letter-spacing: 1.2px;
    line-height: 30px;
}

.content h1{
    font-family: 'Times New Roman';
    font-size: 50px;
    padding-left: 20px;
    margin-top: 9%;
    letter-spacing: 2px;
}

.content .cn{
    width: 160px;
    height: 40px;
    background: #ff7200;
    border: none;
    margin-bottom: 10px;
    margin-left: 20px;
    font-size: 18px;
    border-radius: 10px;
    cursor: pointer;
    transition: .4s ease;
    
}

.content .cn a{
    text-decoration: none;
    color: #000;
    transition: .3s ease;
}

.cn:hover{
    background-color: #fff;
}

.content span{
    color: #ff7200;
    font-size: 65px
}

.form{
    width: 250px;
    height: 380px;
    background: linear-gradient(to top, rgba(0,0,0,0.8)50%,rgba(0,0,0,0.8)50%);
    position: absolute;
    top: -20px;
    left: 870px;
    transform: translate(0%,-5%);
    border-radius: 10px;
    padding: 25px;
}

.form h2{
    width: 220px;
    font-family: sans-serif;
    text-align: center;
    color: #ff7200;
    font-size: 22px;
    background-color: #fff;
    border-radius: 10px;
    margin: 2px;
    padding: 8px;
}

.form input{
    width: 240px;
    height: 35px;
    background: transparent;
    border-bottom: 1px solid #ff7200;
    border-top: none;
    border-right: none;
    border-left: none;
    color: #fff;
    font-size: 15px;
    letter-spacing: 1px;
    margin-top: 30px;
    font-family: sans-serif;
}

.form input:focus{
    outline: none;
}

::placeholder{
    color: #fff;
    font-family: Arial;
}

.btnn{
    width: 240px;
    height: 40px;
    background: #ff7200;
    border: none;
    margin-top: 30px;
    font-size: 18px;
    border-radius: 10px;
    cursor: pointer;
    color: #fff;
    transition: 0.4s ease;
}
.btnn:hover{
    background: #fff;
    color: #ff7200;
}
.btnn a{
    text-decoration: none;
    color: #000;
    font-weight: bold;
}
.form .link{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 17px;
    padding-top: 20px;
    text-align: center;
}
.form .link a{
    text-decoration: none;
    color: #ff7200;
}
.liw{
    padding-top: 15px;
    padding-bottom: 10px;
    text-align: center;
}
.icons a{
    text-decoration: none;
    color: #fff;
}
.icons ion-icon{
    color: #fff;
    font-size: 30px;
    padding-left: 14px;
    padding-top: 5px;
    transition: 0.3s ease;
}
.icons ion-icon:hover{
    color: #ff7200;
}
footer{
    margin-top: -29px;
    background-color:#ff7200;
   
}
</style>
<body>

    <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="logo">Shanmu</h2>
            </div>

            <div class="menu">
                <ul>
                    <li><a href="index.html">HOME</a></li>
                    <li><a href="people.html">PEOPLE</a></li>
                    <li><a href="product.html">PRODUCTS</a></li>
                    <li><a href="contact.html">CONTACT</a></li>
                </ul>
            </div>

            <div class="search">
                <input class="srch" type="search" name="" placeholder="Type To text">
                <a href="#"> <button class="btn">Search</button></a>
            </div>

        </div> 
        <div class="content">
            <h1>Launch outstanding <br><span>digital products &</span> <br>experiences</h1>
            <p class="par">At Shanmu, we deliver game-changing digital products and experiences that set you apart, crafted <br>by our collaborative team of experts for optimal performance, functionality, and user engagement. 
                <br>Trust us to help you stay ahead in the digital space.
            </p>

                <button class="cn"><a href="#">JOIN US</a></button>

                <div class="form">
                    <h2>Login Here</h2>
                    <input type="email" name="email" placeholder="Enter Email Here">
                    <input type="password" name="" placeholder="Enter Password Here">
                    <button class="btnn"><a href="#">Login</a></button>

                    <p class="link">Don't have an account<br>
                    <a href="#">Sign up </a> here</a></p>
                    <p class="liw">Log in with</p>

                    <div class="icons">
                        <a href="#"><ion-icon name="logo-facebook"></ion-icon></a>
                        <a href="#"><ion-icon name="logo-instagram"></ion-icon></a>
                        <a href="#"><ion-icon name="logo-twitter"></ion-icon></a>
                        <a href="#"><ion-icon name="logo-google"></ion-icon></a>
                        <a href="#"><ion-icon name="logo-skype"></ion-icon></a>
                    </div>

                </div>
                    </div>
                </div>
        </div>
    </div>
    <script src="https://unpkg.com/ionicons@5.4.0/dist/ionicons.js"></script>
    <footer align="center">Designed and Developed by &copy;  Shanmuga Raj.K</footer>

</body>
</html>


people.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name=""viewport" content="width=device-width, initial-scale=1.0">
    <title>webIQ</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>
    <style>
        *{
        margin: 0;
        padding: 0;
    }
    
    .main{
        width: 100%;
        background-color: #12172b;
        background-position: center;
        background-size: cover;
        height: 100vh;
    }
    
    .navbar{
        width: 1200px;
        height: 75px;
        margin: auto;
    }
    
    .icon{
        width: 200px;
        float: left;
        height: 70px;
    }
    
    .logo{
        color: #ff7200;
        font-size: 35px;
        font-family: Arial;
        padding-left: 20px;
        float: left;
        padding-top: 10px;
        margin-top: 5px
    }
    
    .menu{
        width: 400px;
        float: left;
        height: 70px;
    }
    
    ul{
        float: left;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    
    ul li{
        list-style: none;
        margin-left: 62px;
        margin-top: 27px;
        font-size: 14px;
    }
    
    ul li a{
        text-decoration: none;
        color: #fff;
        font-family: Arial;
        font-weight: bold;
        transition: 0.4s ease-in-out;
    }
    
    ul li a:hover{
        color: #ff7200;
    }
    
    .search{
        width: 330px;
        float: left;
        margin-left: 270px;
    }
    
    .srch{
        font-family: 'Times New Roman';
        width: 200px;
        height: 40px;
        background: transparent;
        border: 1px solid #ff7200;
        margin-top: 13px;
        color: #fff;
        border-right: none;
        font-size: 16px;
        float: left;
        padding: 10px;
        border-bottom-left-radius: 5px;
        border-top-left-radius: 5px;
    }
    
    .btn{
        width: 100px;
        height: 40px;
        background: #ff7200;
        border: 2px solid #ff7200;
        margin-top: 13px;
        color: #fff;
        font-size: 15px;
        border-bottom-right-radius: 5px;
        border-bottom-right-radius: 5px;
        transition: 0.2s ease;
        cursor: pointer;
    }
    .btn:hover{
        color: #000;
    }
    
    .btn:focus{
        outline: none;
    }
    
    .srch:focus{
        outline: none;
    }
    
    .content{
        width: 1200px;
        height: auto;
        margin: auto;
        color: #fff;
        position: relative;
    }
    
    .content .par{
        padding-left: 20px;
        padding-bottom: 25px;
        font-family: Arial;
        letter-spacing: 1.2px;
        line-height: 30px;
    }
    
    .content h1{
        font-family: 'Times New Roman';
        font-size: 50px;
        padding-left: 20px;
        margin-top: 9%;
        letter-spacing: 2px;
    }
    
    .content .cn{
        width: 160px;
        height: 40px;
        background: #ff7200;
        border: none;
        margin-bottom: 10px;
        margin-left: 20px;
        font-size: 18px;
        border-radius: 10px;
        cursor: pointer;
        transition: .4s ease;
        
    }
    
    .content .cn a{
        text-decoration: none;
        color: #000;
        transition: .3s ease;
    }
    
    .cn:hover{
        background-color: #fff;
    }
    
    .content span{
        color: #ff7200;
        font-size: 65px
    }
    
    .form{
        width: 250px;
        height: 380px;
        background: linear-gradient(to top, rgba(0,0,0,0.8)50%,rgba(0,0,0,0.8)50%);
        position: absolute;
        top: -20px;
        left: 870px;
        transform: translate(0%,-5%);
        border-radius: 10px;
        padding: 25px;
    }
    
    .form h2{
        width: 220px;
        font-family: sans-serif;
        text-align: center;
        color: #ff7200;
        font-size: 22px;
        background-color: #fff;
        border-radius: 10px;
        margin: 2px;
        padding: 8px;
    }
    
    .form input{
        width: 240px;
        height: 35px;
        background: transparent;
        border-bottom: 1px solid #ff7200;
        border-top: none;
        border-right: none;
        border-left: none;
        color: #fff;
        font-size: 15px;
        letter-spacing: 1px;
        margin-top: 30px;
        font-family: sans-serif;
    }
    
    .form input:focus{
        outline: none;
    }
    
    ::placeholder{
        color: #fff;
        font-family: Arial;
    }
    
    .btnn{
        width: 240px;
        height: 40px;
        background: #ff7200;
        border: none;
        margin-top: 30px;
        font-size: 18px;
        border-radius: 10px;
        cursor: pointer;
        color: #fff;
        transition: 0.4s ease;
    }
    .btnn:hover{
        background: #fff;
        color: #ff7200;
    }
    .btnn a{
        text-decoration: none;
        color: #000;
        font-weight: bold;
    }
    .form .link{
        font-family: Arial, Helvetica, sans-serif;
        font-size: 17px;
        padding-top: 20px;
        text-align: center;
    }
    .form .link a{
        text-decoration: none;
        color: #ff7200;
    }
    .liw{
        padding-top: 15px;
        padding-bottom: 10px;
        text-align: center;
    }
    .icons a{
        text-decoration: none;
        color: #fff;
    }
    .icons ion-icon{
        color: #fff;
        font-size: 30px;
        padding-left: 14px;
        padding-top: 5px;
        transition: 0.3s ease;
    }
    .icons ion-icon:hover{
        color: #ff7200;
    }
    footer{
        margin-top: -29px;
        background-color:#ff7200;
   
    }
    @import url("https://fonts.googleapis.com/css?family=Poppins&display=swap");

*{
    padding: 0;
    margin: 0;
}

body {
    background-color: #12172b;
    font-family: "Poppins", sans-serif;
}

.container {
    width:900px;
    margin: 20px 40px;
    color: white;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr;
 
}

.heading {
    font-size: 60px;
    color: white;
}

.heading span {
    font-style: italic;
    font-size: 30px;
}

.profiles {
   margin: 40px 20px;

}
.profile .profile-img {
    height: 160px;
    width: 160px;
    border-radius: 50%;
    /*filter: grayscale(100%);*/
    cursor: pointer;
    transition: 400ms;
}

.profile:hover .profile-img {
    filter: grayscale(0);
}

.user-name {
    margin-top: 30px;
    font-size: 35px;
}

.profile h5 {
    font-size: 18px;
    font-weight: 100;
    letter-spacing: 3px;
    color: #ccc;
}

.profile p {
    font-size: 16px;
    margin-top: 20px;
    text-align: justify;
}
    </style>
    <body>
    
        <div class="main">
            <div class="navbar">
                <div class="icon">
                    <h2 class="logo">Shanmu</h2>
                </div>
    
                <div class="menu">
                    <ul>
                        <li><a href="index.html">HOME</a></li>
                        <li><a href="people.html">PEOPLE</a></li>
                        <li><a href="product.html">PRODUCTS</a></li>
                        <li><a href="contact.html">CONTACT</a></li>
                    </ul>
                </div>
    
                <div class="search">
                    <input class="srch" type="search" name="" placeholder="Type To text">
                    <a href="#"> <button class="btn">Search</button></a>
                </div>
                <left>.</left><h1 class="heading"><span>meet</span> Our Team</h1>
                <div class="container">
                
                    <div class="profiles">
                        <div class="profile">
                            <img src="img6.jpg" class="profile-img">
                            
                            <h3 class="user-name">Shanmuga Raj</h3>
                            <h5>Chief Executive Officer</h5>
                        </div>
                    </div>
                    <div class="profiles">
                        <div class="profile">
                            <img src="img1.png" class="profile-img">
                            
                            <h3 class="user-name">Bill Gates</h3>
                            <h5> Chief Operating Officer</h5>
                        </div>
                    </div>
                    <div class="profiles">
                        <div class="profile">
                            <img src="img3.png" class="profile-img">
                            
                            <h3 class="user-name">Steve Jobs</h3>
                            <h5>Chief Financial Officer</h5>
                        </div>
                    </div>
                    <div class="profiles">
                        <div class="profile">
                            <img src="img2.png" class="profile-img">
                            
                            <h3 class="user-name">Jeff Bezos</h3>
                            <h5>Product Manager</h5>
                        </div>
                    </div>
                
                    <div class="profiles">
                        <div class="profile">
                            <img src="img4.png" class="profile-img">
                            
                            <h3 class="user-name">Mark Zuckerberg</h3>
                            <h5>Chief Technology Officer</h5>
                        </div>
                    </div>
                    <div class="profiles">
                        <div class="profile">
                            <img src="img5.png" class="profile-img">
                            
                            <h3 class="user-name">Elon Musk</h3>
                            <h5>Security Manager</h5>
                        </div>
                    </div>
                

                
                </div>
                
            </div> 

        </div>
        
        <script src="https://unpkg.com/ionicons@5.4.0/dist/ionicons.js"></script>
        <footer align="center">Designed and Developed by &copy;  Shanmuga Raj.K</footer>
</body>
</html>

product.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name=""viewport" content="width=device-width, initial-scale=1.0">
    <title>webIQ</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>
    <style>
        *{
        margin: 0;
        padding: 0;
    }
    
    .main{
        width: 100%;
        background-color: #12172b;
        background-position: center;
        background-size: cover;
        height: 100vh;
    }
    
    .navbar{
        width: 1200px;
        height: 75px;
        margin: auto;
    }
    
    .icon{
        width: 200px;
        float: left;
        height: 70px;
    }
    
    .logo{
        color: #ff7200;
        font-size: 35px;
        font-family: Arial;
        padding-left: 20px;
        float: left;
        padding-top: 10px;
        margin-top: 5px
    }
    
    .menu{
        width: 400px;
        float: left;
        height: 70px;
    }
    
    ul{
        float: left;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    
    ul li{
        list-style: none;
        margin-left: 62px;
        margin-top: 27px;
        font-size: 14px;
    }
    
    ul li a{
        text-decoration: none;
        color: #fff;
        font-family: Arial;
        font-weight: bold;
        transition: 0.4s ease-in-out;
    }
    
    ul li a:hover{
        color: #ff7200;
    }
    
    .search{
        width: 330px;
        float: left;
        margin-left: 270px;
    }
    
    .srch{
        font-family: 'Times New Roman';
        width: 200px;
        height: 40px;
        background: transparent;
        border: 1px solid #ff7200;
        margin-top: 13px;
        color: #fff;
        border-right: none;
        font-size: 16px;
        float: left;
        padding: 10px;
        border-bottom-left-radius: 5px;
        border-top-left-radius: 5px;
    }
    
    .btn{
        width: 100px;
        height: 40px;
        background: #ff7200;
        border: 2px solid #ff7200;
        margin-top: 13px;
        color: #fff;
        font-size: 15px;
        border-bottom-right-radius: 5px;
        border-bottom-right-radius: 5px;
        transition: 0.2s ease;
        cursor: pointer;
    }
    .btn:hover{
        color: #000;
    }
    
    .btn:focus{
        outline: none;
    }
    
    .srch:focus{
        outline: none;
    }
    
    .content{
        width: 1200px;
        height: auto;
        margin: auto;
        color: #fff;
        position: relative;
    }
    
    .content .par{
        padding-left: 20px;
        padding-bottom: 25px;
        font-family: Arial;
        letter-spacing: 1.2px;
        line-height: 30px;
    }
    
    .content h1{
        font-family: 'Times New Roman';
        font-size: 50px;
        padding-left: 20px;
        margin-top: 9%;
        letter-spacing: 2px;
    }
    
    .content .cn{
        width: 160px;
        height: 40px;
        background: #ff7200;
        border: none;
        margin-bottom: 10px;
        margin-left: 20px;
        font-size: 18px;
        border-radius: 10px;
        cursor: pointer;
        transition: .4s ease;
        
    }
    
    .content .cn a{
        text-decoration: none;
        color: #000;
        transition: .3s ease;
    }
    
    .cn:hover{
        background-color: #fff;
    }
    
    .content span{
        color: #ff7200;
        font-size: 65px
    }
    
    .form{
        width: 250px;
        height: 380px;
        background: linear-gradient(to top, rgba(0,0,0,0.8)50%,rgba(0,0,0,0.8)50%);
        position: absolute;
        top: -20px;
        left: 870px;
        transform: translate(0%,-5%);
        border-radius: 10px;
        padding: 25px;
    }
    
    .form h2{
        width: 220px;
        font-family: sans-serif;
        text-align: center;
        color: #ff7200;
        font-size: 22px;
        background-color: #fff;
        border-radius: 10px;
        margin: 2px;
        padding: 8px;
    }
    
    .form input{
        width: 240px;
        height: 35px;
        background: transparent;
        border-bottom: 1px solid #ff7200;
        border-top: none;
        border-right: none;
        border-left: none;
        color: #fff;
        font-size: 15px;
        letter-spacing: 1px;
        margin-top: 30px;
        font-family: sans-serif;
    }
    
    .form input:focus{
        outline: none;
    }
    
    ::placeholder{
        color: #fff;
        font-family: Arial;
    }
    
    .btnn{
        width: 240px;
        height: 40px;
        background: #ff7200;
        border: none;
        margin-top: 30px;
        font-size: 18px;
        border-radius: 10px;
        cursor: pointer;
        color: #fff;
        transition: 0.4s ease;
    }
    .btnn:hover{
        background: #fff;
        color: #ff7200;
    }
    .btnn a{
        text-decoration: none;
        color: #000;
        font-weight: bold;
    }
    .form .link{
        font-family: Arial, Helvetica, sans-serif;
        font-size: 17px;
        padding-top: 20px;
        text-align: center;
    }
    .form .link a{
        text-decoration: none;
        color: #ff7200;
    }
    .liw{
        padding-top: 15px;
        padding-bottom: 10px;
        text-align: center;
    }
    .icons a{
        text-decoration: none;
        color: #fff;
    }
    .icons ion-icon{
        color: #fff;
        font-size: 30px;
        padding-left: 14px;
        padding-top: 5px;
        transition: 0.3s ease;
    }
    .icons ion-icon:hover{
        color: #ff7200;
    }
    footer{
        margin-top: -29px;
        background-color:#ff7200;
   
    }
    </style>
    <body>
    
        <div class="main">
            <div class="navbar">
                <div class="icon">
                    <h2 class="logo">Shanmu</h2>
                </div>
    
                <div class="menu">
                    <ul>
                        <li><a href="index.html">HOME</a></li>
                        <li><a href="people.html">PEOPLE</a></li>
                        <li><a href="product.html">PRODUCTS</a></li>
                        <li><a href="contact.html">CONTACT</a></li>
                    </ul>
                </div>
    
                <div class="search">
                    <input class="srch" type="search" name="" placeholder="Type To text">
                    <a href="#"> <button class="btn">Search</button></a>
                </div>
            </div> <br><br><br>
            <center><img src="abc.png" height="500" width="1200"></center>
        </div>
        <script src="https://unpkg.com/ionicons@5.4.0/dist/ionicons.js"></script>
        <footer align="center">Designed and Developed by &copy;  Shanmuga Raj.K</footer>

</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <title>Webpage Design</title>
    <link rel="stylesheet" href="style.css">
</head>
<style>
    *{
    margin: 0;
    padding: 0;
}

.main{
    width: 100%;
    background-color: #12172b;
    background-position: center;
    background-size: cover;
    height: 100vh;
}

.navbar{
    width: 1200px;
    height: 75px;
    margin: auto;
}

.icon{
    width: 200px;
    float: left;
    height: 70px;
}

.logo{
    color: #ff7200;
    font-size: 35px;
    font-family: Arial;
    padding-left: 20px;
    float: left;
    padding-top: 10px;
    margin-top: 5px
}

.menu{
    width: 400px;
    float: left;
    height: 70px;
}

ul{
    float: left;
    display: flex;
    justify-content: center;
    align-items: center;
}

ul li{
    list-style: none;
    margin-left: 62px;
    margin-top: 27px;
    font-size: 14px;
}

ul li a{
    text-decoration: none;
    color: #fff;
    font-family: Arial;
    font-weight: bold;
    transition: 0.4s ease-in-out;
}

ul li a:hover{
    color: #ff7200;
}

.search{
    width: 330px;
    float: left;
    margin-left: 270px;
}

.srch{
    font-family: 'Times New Roman';
    width: 200px;
    height: 40px;
    background: transparent;
    border: 1px solid #ff7200;
    margin-top: 13px;
    color: #fff;
    border-right: none;
    font-size: 16px;
    float: left;
    padding: 10px;
    border-bottom-left-radius: 5px;
    border-top-left-radius: 5px;
}

.btn{
    width: 100px;
    height: 40px;
    background: #ff7200;
    border: 2px solid #ff7200;
    margin-top: 13px;
    color: #fff;
    font-size: 15px;
    border-bottom-right-radius: 5px;
    border-bottom-right-radius: 5px;
    transition: 0.2s ease;
    cursor: pointer;
}
.btn:hover{
    color: #000;
}

.btn:focus{
    outline: none;
}

.srch:focus{
    outline: none;
}

.content{
    width: 1200px;
    height: auto;
    margin: auto;
    color: #fff;
    position: relative;
}

.content .par{
    padding-left: 20px;
    padding-bottom: 25px;
    font-family: Arial;
    letter-spacing: 1.2px;
    line-height: 30px;
}

.content h1{
    font-family: 'Times New Roman';
    font-size: 50px;
    padding-left: 20px;
    margin-top: 9%;
    letter-spacing: 2px;
}

.content .cn{
    width: 160px;
    height: 40px;
    background: #ff7200;
    border: none;
    margin-bottom: 10px;
    margin-left: 20px;
    font-size: 18px;
    border-radius: 10px;
    cursor: pointer;
    transition: .4s ease;
    
}

.content .cn a{
    text-decoration: none;
    color: #000;
    transition: .3s ease;
}

.cn:hover{
    background-color: #fff;
}

.content span{
    color: #ff7200;
    font-size: 65px
}

.form{
    width: 250px;
    height: 380px;
    background: linear-gradient(to top, rgba(0,0,0,0.8)50%,rgba(0,0,0,0.8)50%);
    position: absolute;
    top: -20px;
    left: 870px;
    transform: translate(0%,-5%);
    border-radius: 10px;
    padding: 25px;
}

.form h2{
    width: 220px;
    font-family: sans-serif;
    text-align: center;
    color: #ff7200;
    font-size: 22px;
    background-color: #fff;
    border-radius: 10px;
    margin: 2px;
    padding: 8px;
}

.form input{
    width: 240px;
    height: 35px;
    background: transparent;
    border-bottom: 1px solid #ff7200;
    border-top: none;
    border-right: none;
    border-left: none;
    color: #fff;
    font-size: 15px;
    letter-spacing: 1px;
    margin-top: 30px;
    font-family: sans-serif;
}

.form input:focus{
    outline: none;
}

::placeholder{
    color: #fff;
    font-family: Arial;
}

.btnn{
    width: 240px;
    height: 40px;
    background: #ff7200;
    border: none;
    margin-top: 30px;
    font-size: 18px;
    border-radius: 10px;
    cursor: pointer;
    color: #fff;
    transition: 0.4s ease;
}
.btnn:hover{
    background: #fff;
    color: #ff7200;
}
.btnn a{
    text-decoration: none;
    color: #000;
    font-weight: bold;
}
.form .link{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 17px;
    padding-top: 20px;
    text-align: center;
}
.form .link a{
    text-decoration: none;
    color: #ff7200;
}
.liw{
    padding-top: 15px;
    padding-bottom: 10px;
    text-align: center;
}
.icons a{
    text-decoration: none;
    color: #fff;
}
.icons ion-icon{
    color: #fff;
    font-size: 30px;
    padding-left: 14px;
    padding-top: 5px;
    transition: 0.3s ease;
}
.icons ion-icon:hover{
    color: #ff7200;
}

footer{
    margin-top: 300px;
    background-color:#ff7200;
   
}
.company{
        margin-left: 800px;
        margin-top: -290px;
        scroll-padding-left: 5px;
        border:10px solid #ff7200;
    }
</style>
<body>

    <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="logo">Shanmu</h2>
            </div>

            <div class="menu">
                <ul>
                    <li><a href="index.html">HOME</a></li>
                    <li><a href="people.html">PEOPLE</a></li>
                    <li><a href="product.html">PRODUCTS</a></li>
                    <li><a href="contact.html">CONTACT</a></li>
                </ul>
            </div>

            <div class="search">
                <input class="srch" type="search" name="" placeholder="Type To text">
                <a href="#"> <button class="btn">Search</button></a>
            </div>
        </div> 
        <div class="content">
          <h1>Contact Us</h1>
          <p class="par">we're committed to providing top-notch IT solutions and services to our clients. If you have any questions, concerns, or would like to learn more about our offerings, please don't hesitate to reach out to us.</p>
          <form action="#" method="post">
            <label for="name">Name:</label>
            <input type="text" name="name" required><br>
            
            <label for="email">Email:</label>
            <input type="email" name="email" required><br>
            <label for="message">Message:</label>
            <textarea name="message" rows="5" required></textarea><br>
            <button type="submit" name="submit" class="btnn"><a href="#">Submit</a></button><br>  
             <br><br><br>
          <div class="company">
              <center>
              <h2 class="liw">Location:</h2> 
      
             <p> <b >Address</b></p>
              <p >36 King Street
                  London
                  SW67 2IF</p>
              <b >Email:</b>
              <p >Shanmugarajk2205@gmail.com</p>
              <b >Phone</b>
              <p >9952355934</p>
          </center>
        </div> 
    </div>
    <script src="https://unpkg.com/ionicons@5.4.0/dist/ionicons.js"></script>
    <footer align="center">Designed and Developed by &copy;  Shanmuga Raj.K</footer>

</body>
</html>
```

## OUTPUT:
![Alt text](<Screenshot (56).png>)
![Alt text](<Screenshot (57).png>)
![Alt text](<Screenshot (58).png>)
![Alt text](<Screenshot (59).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
