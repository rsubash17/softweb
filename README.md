# Ex.07 Software Product Company Website
## Date:29.04.24

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
 <!DOCTYPE html>
 <html lang="en">
 <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>      
        .banner{
            width: 100%;
            height:70px;
            background-color: aqua;
        }
        #na{
            display:flex;
            padding:10px;
            justify-content: right;
            justify-items: right;
        }
        nav li{
            display:inline-block;
        }
        .p{
            height:30px;
            display:flex;
            align-items: center;
            background-color: antiquewhite;
            justify-content: center;
        }
        .pa{
            width:500px;
            height: 220px;
            justify-content:center;
            justify-items: center;
            border-radius: 20px;
            background-color: beige;
            margin-left: 600px;
            margin-top: 70px;
        }
        .po{
            justify-content: center;
            justify-items: center;
            margin-left: 170px;
        }
        .pq{
            margin-left: 220px;
        }
        .aa{
            background-color: aquamarine;
            height:890px;
        }
        .m{
            display:flex;
        }
        .new{
            height:120px;
            width: 220px;
            margin-top: 120px;
            font-size: larger;
            background-image:url(group.jpg);
        }
        .aab{
            background-color: rgb(149, 232, 14);
        }

        .sa{
            margin-right: 15px;
        }
        
    </style>
 </head>
 <body bgcolor="black">
    <div class="aa">
    <div class="banner">
    <label class="logo"><b>Subash Softwares</b></label>
        <header>
            
            <nav id="na">
                <div class="sa">
                <a href="home.html"> Home </a>
                </div>
                <div class="sa">
                <a href="product.html"> Product</a>
                </div>
                <div class="sa">
                <a href="people.html"> People</a>
                </div>
                <div class="sa">
                <a href="contact.html"> Contact Us</a>
                </div>
            </nav>
        </header>
    </div>
    <div class="p" align="center">
        Web Development Software For Business
    </div>
    <div class="m">
    <div class="new">
        <br>
       Welcome To The World <br>
              Of <br>
       SoftWare Development.
       <button>Get Started></button>
    </div>
    <div class="pa">
        <h3 align="center">Login</h3>
        <br>
        <div class="po">
        <input type="text" placeholder="Enter Name:" ><br><br><br>
        <input type="text" placeholder="Enter Email:" ><br><br>
        </div>
        <div class="pq">
        <button >Submit</button>
        </div>
    </div>
    </div>
    </div>
    <footer align="center" class="aab">
        Designed and Developed By:Subash R (212223230218)@2024
    </footer>
 </body>
 </html>
```
```
people.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    
    .banner{
            width: 100%;
            height:70px;
            background-color: aqua;
    }
    #na{
            display:flex;
            padding:10px;
            justify-content: right;
            justify-items: right;
        }
        .ma{
            background-color: rgb(198, 9, 198);
            height: 90%;
            width: 100%;
            justify-content: center;
            justify-items: center;
            align-items: center;
        }
        .qe{
            background-color: rgb(30, 219, 36);
            display:flex;
            height:795px;
            width:100%
        }
        .box{
            margin-top: 100px;
            margin-left: 30px;
            background-color: violet;
            height:150px;
            width:100px;
            border-radius: 2px;
            border:2px solid black;
            padding:60px;
        }
        .aab{
            background-color: white;
        }
        .sa{
            margin-right: 15px;
        }

</style>
<body bgcolor="black">
    <div class="banner">
        <label class="logo"><b>Subash Softwares</b></label>
            <header>
                
                <nav id="na">
                    <div class="sa">
                    <a href="home.html"> Home </a>
                    </div>
                    <div class="sa">
                    <a href="product.html"> Product</a>
                    </div>
                    <div class="sa">
                    <a href="people.html"> People</a>
                    </div>
                    <div class="sa">
                    <a href="contact.html"> Contact Us</a>
                    </div>
                </nav>
            </header>
    </div>
    <div class="ma" align="center">
        People Of The Company
    </div>
    <div class="qe">
        <div class="box">
            <img src="ss.jpg" height="100px" width="100px">
            <h4 align="center">Subash R</h4>
            <h5 align="center">Founder</h5>
        </div>
        <div class="box">
            <img src="pict 2.webp" height="100px" width="100px">
            <h4 align="center">Anil Souray</h4>
            <h5 align="center">Co-Founder</h5>
        </div>
        <div class="box">
            <img src="pict1.webp" height="100px" width="100px">
            <h4 align="center">Mukesh Kumar</h4>
            <h5 align="center">CEO</h5>
        </div>
        <div class="box">
            <img src="pict3.jpeg" height="100px" width="100px">
            <h4 align="center">Jeff Stephan</h4>
            <h5 align="center">CTO</h5>
        </div>
        <div class="box">
            <img src="pict4.jpeg" height="100px" width="100px">
            <h4 align="center">Bill Gates</h4>
            <h5 align="center">Manager</h5>
        </div>
    </div>
    <footer align="center" class="aab">
        Designed and Developed By:Subash R (212223230218)@2024
    </footer>
</body>
</html>
```
```
product.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    
    .banner{
            width: 100%;
            height:70px;
            background-color: aqua;
    }
    #na{
            display:flex;
            padding:10px;
            justify-content: right;
            justify-items: right;
        }
        .ma{
            background-color: rgb(181, 41, 216);
            height: 30px;
            width: 100%;
            justify-content: center;
            justify-items: center;
            align-items: center;
        }
        .qe{
            background-color: rgb(187, 191, 182);
            display:flex;
            height:795px;
            width:100%
        }
        .box{
            margin-top: 100px;
            margin-left: 30px;
            background-color: aqua;
            height:100px;
            width:100px;
            border-radius: 2px;
            border:2px solid black;
            padding:60px;
        }
        .aab{
            background-color: whitesmoke;
        }
        .sa{
            margin-right: 15px;
        }

</style>
<body bgcolor="black">
    <div class="banner">
        <label class="logo"><b>Subash Softwares</b></label>
            <header>
                
                <nav id="na">
                    <div class="sa">
                    <a href="home.html"> Home </a>
                    </div>
                    <div class="sa">
                    <a href="product.html"> Product</a>
                    </div>
                    <div class="sa">
                    <a href="people.html"> People</a>
                    </div>
                    <div class="sa">
                    <a href="contact.html"> Contact Us</a>
                    </div>
                </nav>
            </header>
    </div>
    <div class="ma" align="center">
        Companies Collabrated With us.
    </div>
    <div class="qe">
        <div class="box">
            <img src="logo-1.png" height="100px" width="100px">
            <h3 align="center">Google</h3>
        </div>
        <div class="box">
            <img src="yy.png" height="100px" width="100px">
            <h3 align="center">Yahoo</h3>
        </div>
        <div class="box">
            <img src="wip.png" height="100px" width="100px">
            <h3 align="center">Wipro</h3>
        </div>
        <div class="box">
            <img src="ib.png" height="100px" width="100px">
            <h3 align="center">IBM</h3>
        </div>
        <div class="box">
            <img src="logo-4.jpg" height="100px" width="100px">
            <h3 align="center">Amazon</h3>
        </div>
    </div>
    <footer align="center" class="aab">
        Designed and Developed By:Subash R (212223230218)@2024
    </footer>
</body>
</html>
```
```
contact.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .banner{
            width: 100%;
            height:90px;
            background-color: aqua;
        }
        #na{
            display:flex;
            padding:10px;
            justify-content: right;
            justify-items: right;
            margin-right: 20px;;
        }
        .tb{
            height:220px;
            width:250px;
            border:2px solid black;
            margin-left: 20px;
            background-color: whitesmoke;
            margin-top: 120px;
        }
        .ap{
            margin-left: 20px;
        }
        .aab{
            background-color: white;
            margin-top: 450px;
        }
        .tr{
            width:320px;
            border:2px solid black;
            background-color: rgb(239, 141, 14);
            margin-top: 120px;
            margin-left: 40px;
        }
        .ty{
            display: flex;
            margin-left: 250px;
        }
        .qq{
            background-color: rgb(200, 209, 206);
            height: 880px;
        }
        .sa{
            margin-right: 15px;
        }
    </style>
</head>
<body bgcolor="black">
        <div class="banner">
            <label class="logo"><b>Subash Softwares</b></label>
                <header>
                    <nav id="na">
                        <div class="sa">
                        <a href="home.html"> Home </a>
                        </div>
                        <div class="sa">
                        <a href="product.html"> Product</a>
                        </div>
                        <div class="sa">
                        <a href="people.html"> People</a>
                        </div>
                        <div class="sa">
                        <a href="contact.html"> Contact Us</a>
                        </div>
                    </nav>
                </header>
            </div>
            <div class="qq">
            <div class="ty">
            <div class="tb">
                   <h3 align="center"> Contact Us</h3><br>
                   <div class="ap">
                    <input type="text" placeholder="Your Name"><br><br>
                    <input type="text" placeholder="Email"><br><br>
                    <textarea>
                        Your Messages
                    </textarea>
                    </div>
            </div>
            <div class="tr">
               <h3><b>Contact Information</b></h3><br>
                <div>
                    Address: Thirupathi Nagar,6th East Cross,chennai
                </div><br>
                <div>
                    Email:subash1205@gmail.com.
                </div><br>
                <div>
                    Phone: 7397060885
                </div><br>
            </div>
            </div>
            <footer align="center" class="aab">
                Designed and Developed By:Subash R (212223230218)@2024
            </footer>
            
</body>
</html>
```
## OUTPUT:
![sb](https://github.com/rsubash17/softweb/assets/147139828/a7f9f01c-6b4a-4da0-865a-07ec2c0cb2ce)
![sb(1)](https://github.com/rsubash17/softweb/assets/147139828/7cd9605b-4990-49a2-bdb7-8717df33aa1a)
![sb(2)](https://github.com/rsubash17/softweb/assets/147139828/ff7a7e58-640c-464a-8e0a-d53a73d87b3f)
![sb(3)](https://github.com/rsubash17/softweb/assets/147139828/6922c2e9-a71c-4126-a70a-41944d2d9d1d)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
