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
home.html

home.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        
        <title> Software Development Company </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(0,0,0,0.75),rgba(0,0,0,0.75)),url(background.jpg);
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color: #6fa1f8;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: white;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background: #6fa1f8;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .content {
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%,-50%);
                text-align: center;
            }
            .text h2 {
                color: white;
                font-weight: 800;
                font-size: 50px;
                letter-spacing: 3px;
            }
            .text p {
                color: white;
                text-transform: capitalize;
                font-size: 15px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
            }
            .login {
                margin: 0px 10px;
                border: 2px solid #6fa1f8;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: white;
                border-radius: 30px;
                background-color: #6fa1f8;
                text-decoration: none;
            }
            .login:hover {
                border: 2px solid #6fa1f8;
                color: #6fa1f8;
                background-color: white;
                transition: 0.5s;
                cursor: pointer;
            } 
            .signup {
                margin: 0px 10px;
                border: 2px solid #6fa1f8;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: white;
                border-radius: 30px;
                background-color: #6fa1f8;
                text-decoration: none;
            }
            .signup:hover {
                border: 2px solid #6fa1f8;
                color: #6fa1f8;
                background-color: white;
                transition: 0.5s;
                cursor: pointer;
            }
            footer {
                background-color: #6fa1f8;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">C<span>ode</span>C<span>rafters</span></h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="content">
            <div class="text">
                <h2> Software Development Company </h2>
                <br>
                <p> Welcome to CodeCrafters, your gateway to cutting-edge software solutions and innovative web development applications! </p>
                <br>
                <div>
                    <a href="#" class="login"> Log In </a>
                    <a href="#" class="signup"> Sign Up </a>
                </div>
            </div>
        </div>  
    </div>
    <footer>
        <center> Designed and Developed by SUBASH R (212223230218) </center>
    </footer>
</body>
</html>

Software Development Company.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Software Development Company </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(0,0,0,0.75),rgba(0,0,0,0.75)),url(background.jpg);
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color: #6fa1f8;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: white;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background: #6fa1f8;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .content {
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%,-50%);
                text-align: center;
            }
            .text h2 {
                color: white;
                font-weight: 800;
                font-size: 50px;
                letter-spacing: 3px;
            }
            .text p {
                color: white;
                text-transform: capitalize;
                font-size: 15px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
            }
            .login {
                margin: 0px 10px;
                border: 2px solid #6fa1f8;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: white;
                border-radius: 30px;
                background-color: #6fa1f8;
                text-decoration: none;
            }
            .login:hover {
                border: 2px solid #6fa1f8;
                color: #6fa1f8;
                background-color: white;
                transition: 0.5s;
                cursor: pointer;
            } 
            .signup {
                margin: 0px 10px;
                border: 2px solid #6fa1f8;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: white;
                border-radius: 30px;
                background-color: #6fa1f8;
                text-decoration: none;
            }
            .signup:hover {
                border: 2px solid #6fa1f8;
                color: #6fa1f8;
                background-color: white;
                transition: 0.5s;
                cursor: pointer;
            }
            footer {
                background-color: #6fa1f8;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">C<span>ode</span>C<span>rafters</span></h1>
            <div>
                <img src="saveetha home page1.html" alt="">
            </div>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="content">
            <div class="text">
                <h2> Software Development Company </h2>
                <br>
                <p> Welcome to CodeCrafters, your gateway to cutting-edge software solutions and innovative web development applications! </p>
                <br>
                <div>
                    <a href="#" class="login"> Log In </a>
                    <a href="#" class="signup"> Sign Up </a>
                </div>

            </div>
        </div>  
    </div>
    <footer>
        <center> Designed and Developed by RAMYA R (212223230169) </center>
    </footer>
</body>
</html>




<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> people page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(0,0,0,0.75),rgba(0,0,0,0.75)),url(background.jpg);
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .bg-people {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                border-radius: 30px;
            }
            .logo {
                color: #6fa1f8;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: white;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background: #6fa1f8;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .image {
                position: relative;
                border: 0;
                top: 70px;
                background: transparent;
            }
            .image table {
                border: 0;
                color: white;
                position: relative;
                left: 150px;
            }
            .image table img {
                height: 140px;
                width: 140px;
                border: 2px solid white;
                padding: 5px;
                border-radius: 50%;
            }
            .image table td {
                color: #6fa1f8;
            }
            footer {
                background-color: #6fa1f8;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">C<span>ode</span>C<span>rafters</span></h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html" class="bg-people"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="image">
            <table cellspacing="20"> 
                <tr align="center">
                    <td> <img src="my_pic.jpg"> </td>
                    <td> <img src="2nd_person.jpeg"> </td>
                    <td> <img src="3rd_person.jpg"> </td>
                    <td> <img src="4th person.webp"> </td>
                    <td> <img src="5th_person.jpg"> </td>
                    <td> <img src="6th person.jpg"> </td>
                </tr>
                <tr align="center">
                    <th> Ramya</th>
                    <th> Denis Thiyoder </th>
                    <th> Micale Himavath</th>
                    <th> Nelson </th>
                    <th> Royal Mathio</th>
                    <th> Sachin bildis </th>
                </tr>
                <tr align="center">
                    <td> CEO </td>
                    <td> CEO, Co-Founder </td>
                    <td> CTO, Co-Founder </td>
                    <td> Director </td>
                    <td> Asst. Director </td>
                    <td> Dy. Director </td>
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by RAMYA R (212223230169) </center>
    </footer>
</body>
</html>

contact.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Contact Us Page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(0,0,0,0.75),rgba(0,0,0,0.75)),url(background.jpg);
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .bg-contact {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                border-radius: 30px;
            }
            .logo {
                color: #6fa1f8;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: white;
            }
            .navbar form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            .navbar form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            .navbar form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background: #6fa1f8;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .box {
                display: flex;
                column-gap: 40px;
                background: transparent;
                position: relative;
                top: 50px;
            }
            .box-1 {
                height: 400px;
                width: 400px;
                border: 3px solid white;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 250px;
            }
            .box-2 {
                height: 400px;
                width: 400px;
                border: 3px solid #6fa1f8;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 300px;
            }
            .box-1 form {
                display: flex;
                color: white;
                background: transparent;
                padding: 10px;
                font-size: 15px;
                position: relative;
                top: 15px;
            }
            .box-1 form input {
                background: transparent;
                display: flex;
                border: 1px solid white;
                border-radius: 10px;
                padding: 15px 30px;
                font-size: 15px;
                color: white;
                position: relative;
                top: 30px;
            }
            .box-1 form textarea {
                background: transparent;
                color: white;
                padding: 15px 10px;
                position: relative;
                top: 30px;
                left: 30px;
                border: 1px solid white;
                border-radius: 10px;
            }
            .box-1 form button {
                border: 0;
                outline: none;
                padding: 10px 20px;
                color: white;
                border-radius: 30px;
                background: #6fa1f8;
                cursor: pointer;
                position: relative;
                top: 50px;
            }
            .box-2 h2 {
                color: white;
                position: relative;
                top: 25px;
                left: 50px;
                font-size: 30px;
            }
            .box-2 p {
                color: white;
                position: relative;
                top: 50px;
                padding: 10px 80px;
            }
            .box-2 span {
                color: #6fa1f8;
                font-size: 20px;
            }
            footer {
                background-color: #6fa1f8;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">C<span>ode</span>C<span>rafters</span></h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html" class="bg-contact"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="box">
            <div class="box-1">
                <form>
                    <center>
                        <h1> Contact Us </h1>
                        <input type="text" placeholder="Your Name">
                        <br>
                        <input type="email" placeholder="Your Email">
                        <br>
                        <textarea rows="4" cols="40" placeholder="Your Message"> </textarea>
                        <br>
                        <button type="submit"> Submit </button>
                    </center>
                </form>
            </div>
            <div class="box-2"> 
                <h2> Contact Information </h2>
                <p> <span>Address</span> : No.116,Nadar Street Royapet,Chennai Distict</p>
                <p> <span>Email</span> : subash010@gmail.com </p>
                <p> <span>Phone</span> : 9965131030</p>
            </div>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by SUBASH R (212223230218) </center>
    </footer>
</body>
</html>

cpuncil.html

COUNCIL
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>people page</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 95vh;
        background-image: linear-gradient(
            rgba(0, 0, 0, 0.75),
            rgba(0, 0, 0, 0.75)
          ),
          url(backgroundweb\ 7.jpg );
        background-size: cover;
        background-position: center;
      }
      .navbar {
        width: 85%;
        margin: auto;
        padding: 35px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
      }
      .bg-people {
        border: 1px;
        padding: 10px;
        color: white;
        background-color: rgb(212, 255, 0);
        border-radius: 30px;
      }
      .logo {
        color: #c7fb0b;
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
      }
      span {
        color: white;
      }
      form {
        width: 300px;
        height: 40px;
        display: flex;
        background: rgba(255, 255, 255, 0.2);
        padding: 1px 1px;
        font-size: 15px;
        border-radius: 10px;
        backdrop-filter: blur(4px) saturate(180%);
      }
      form input {
        background: transparent;
        flex: 1;
        border: 0;
        outline: none;
        padding: 12px 20px;
        font-size: 15px;
        color: white;
      }
      ::placeholder {
        color: white;
      }
      form button {
        border: 0;
        outline: none;
        padding: 5px 20px;
        color: white;
        border-radius: 10px;
        background:rgb(208, 255, 0);
        cursor: pointer;
      }
      .navbar li {
        list-style: none;
        display: inline-block;
        margin: 0 20px;
        position: relative;
      }
      .navbar li a {
        text-decoration: none;
        color: white;
        text-transform: uppercase;
      }
      .navbar li:hover {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(200, 255, 0);
        color: #081b29;
        box-shadow: 0 0 20px rgb(229, 255, 0);
      }
      .image {
        position: relative;
        border: 0;
        top: 150px;

        background: transparent;
      }
      .image table {
        border: 0;
        color: white;
        position: relative;
        left: 200px;
        border: 10PX;
        padding-left: 10px;
      
      }
      .image table img {
        height: 140px;
        width: 140px;
        border: 2px solid white;
        padding: 5px;
        border-radius: 50%;
      }
      .image table td {
        color:rgb(212, 255, 0);
      }
      footer {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(212, 255, 0);
        color: #081b29;
        box-shadow: 0 0 20px rgb(200, 255, 0);
      }
      .space{
        padding-left: 30px;
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo">SUB<span>A</span>SHD<span>EVELOPED</span></h1>
        <ul>
          <li><a href="home.html"> home </a></li>
          <li><a href="products.html"> Products </a></li>
          <li><a href="council.html" class="bg-people"> council </a></li>
          <li><a href="contact_us.html"> Contact </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button type="submit">Search</button>
        </form>
      </div>
      <div class="image">
        <table cellspacing="80" >
          <tr align="center">
            <td><img src="subash.jpg" /></td>
            <td><img src="Screenshot 2024-04-28 002752.png" /></td>
            <td><img src="Screenshot 2024-04-28 002723.png" /></td>
            <td><img src="Screenshot 2024-04-28 002552.png" /></td>
            <td><img src="Screenshot 2024-04-28 002424.png" /></td>
        
          </tr>
          <tr align="center" class="space">
            <th>SUBASH R</th>
            <th>NELSON</th>
            <th>THIYODER</th>
            <th>WILL JACKS</th>
            <th>SHASHANK SINGH</th>
            
          </tr>
          <tr align="center">
            <td>CEO</td>
            <td>CEO,Co-Founder</td>
            <td>CTO,Co-Founder</td>
            <td>DIRECTOR</td>
            <td>Asst.Director</td>
            
          </tr>
        </table>
      </div>
    </div>
    <footer>
      <center>DESIGNED AND DEVELOPED BY SUBASH R (212223230218)</center>
    </footer>
  </body>
</html>

products.html

PRODUCT
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Product Page</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 95vh;
        background-image: linear-gradient(
            rgba(0, 0, 0, 0.75),
            rgba(0, 0, 0, 0.75)
          ),
          url(priya\ softapp.webp);
        background-size: cover;
        background-position: center;
      }
      .navbar {
        width: 85%;
        margin: auto;
        padding: 35px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
      }
      .bg-product {
        border: 1px;
        padding: 10px;
        color: white;
        background-color: rgb(238, 255, 0);
        border-radius: 30px;
      }
      .logo {
        color: #dbfb0b;
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
      }
      span {
        color: white;
      }
      form {
        width: 300px;
        height: 40px;
        display: flex;
        background: rgba(255, 255, 255, 0.2);
        padding: 1px 1px;
        font-size: 15px;
        border-radius: 10px;
        backdrop-filter: blur(4px) saturate(180%);
      }
      form input {
        background: transparent;
        flex: 1;
        border: 0;
        outline: none;
        padding: 12px 20px;
        font-size: 15px;
        color: white;
      }
      ::placeholder {
        color: white;
      }
      form button {
        border: 0;
        outline: none;
        padding: 5px 20px;
        color: white;
        border-radius: 10px;
        background: rgb(217, 255, 0);
        cursor: pointer;
      }
      .navbar li {
        list-style: none;
        display: inline-block;
        margin: 0 20px;
        position: relative;
      }
      .navbar li a {
        text-decoration: none;
        color: white;
        text-transform: uppercase;
      }
      .navbar li:hover {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(200, 255, 0);
        color: #081b29;
        box-shadow: 0 0 20px rgb(204, 255, 0);
      }
      .container {
        background: transparent;
        padding: 10px 5%;
        padding-bottom: 100px;
      }
      .container .box-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
        gap: 100px;
      }
      .container .box-container .box {
        color: white;
        box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
        border-radius: 20px;
        background: transparent;
        border: 1px solid white;
        padding: 30px 20px;
      }
      .container .box-container .box img {
        height: 70px;
        border-radius: 20px;
      }
      .container .box-container .box h3 {
        color: rgb(208, 255, 0);
        font-size: large;
        padding: 20px 0;
      }
      .container .box-container .box p {
        color: white;
        font-size: small;
        line-height: 1.5;
      }
      footer {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(217, 255, 0);
        color: #081b29;
        box-shadow: 0 0 20px rgb(238, 255, 0);
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo">SUB<span>A</span>SHD<span>EVELOPED</span></h1>
        <ul>
          <li><a href="home.html"> Home </a></li>
          <li><a href="products.html" class="bg-product"> Products </a></li>
          <li><a href="council.html"> council </a></li>
          <li><a href="contact_us.html"> Contact </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button type="submit">Search</button>
        </form>
      </div>
      <div class="container">
        <div class="box-container">
          <div class="box">
            <h3>C</h3>
            <p>
              Efficiency Redefined: Harnessing the Power of C for Next-Level Development
            </p>
          </div>
          <div class="box">
            <h3>C++</h3>
            <p>
              Crafting Performance: Where Precision Meets C++ Programming.
            </p>
          </div>
          <div class="box">
            <h3>JAVA</h3>
            <p>
              Scripting Success: Unleashing the Power of Java.
            </p>
          </div>
          <div class="box">
            <h3>SHELL</h3>
            <p>
              Shell is a server side scripting language that is embedded in HTML.
            </p>
          </div>
          <div class="box">
            <h3>PYTHON</h3>
            <p>
              Unlocking Innovation: Python Paving the Way to Progress.
            </p>
          </div>
          <div class="box">
            <h3>SQL</h3>
            <p>
              SQL is a standard language for accessing and manipulating
              databases.
            </p>
          </div>
          <div class="box">
            <h3>PHP</h3>
            <p>
              Php can be accessed by users using a command line interface.
            </p>
          </div>
          <div class="box">
            <h3>RUBY</h3>
            <p>
              Ruby: Everything in Ruby is an object, even basic data types like integers and strings.  
            </p>
          </div>
          <div class="box">
            <h3>TYPESCRIPT</h3>
            <p>
              Empower Your Code: Embrace the Future And Knowledge  with TypeScript
            </p>
          </div>
          <div class="box">
            <h3>F#</h3>
            <p>
              F# is an Open-source programming language with a lot of features.
            </p>
          </div>
        </div>
      </div>
    </div>
    <footer>
      <center>Designed and DEVELOPED BY SUBASH R (212223230218)</center>
    </footer>
  </body>
</html>

contact.html

CONTACT_US
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Contact Us Page</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 95vh;
        background-image: linear-gradient(
            rgba(0, 0, 0, 0.75),
            rgba(0, 0, 0, 0.75)
          ),
          url(priya\ softapp.webp);
        background-size: cover;
        background-position: center;
      }
      .navbar {
        width: 85%;
        margin: auto;
        padding: 35px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
      }
      .bg-contact {
        border: 1px;
        padding: 10px;
        color: white;
        background-color:rgb(225, 255, 0);
        border-radius: 30px;
      }
      .logo {
        color: rgb(200, 255, 0);
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
      }
      span {
        color: white;
      }
      .navbar form {
        width: 300px;
        height: 40px;
        display: flex;
        background: rgba(255, 255, 255, 0.2);
        padding: 1px 1px;
        font-size: 15px;
        border-radius: 10px;
        backdrop-filter: blur(4px) saturate(180%);
      }
      .navbar form input {
        background: transparent;
        flex: 1;
        border: 0;
        outline: none;
        padding: 12px 20px;
        font-size: 15px;
        color: white;
      }
      ::placeholder {
        color: white;
      }
      .navbar form button {
        border: 0;
        outline: none;
        padding: 5px 20px;
        color: white;
        border-radius: 10px;
        background: rgb(200, 255, 0);
        cursor: pointer;
      }
      .navbar li {
        list-style: none;
        display: inline-block;
        margin: 0 20px;
        position: relative;
      }
      .navbar li a {
        text-decoration: none;
        color: white;
        text-transform: uppercase;
      }
      .navbar li:hover {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(234, 255, 0);
        color: #081b29;
        box-shadow: 0 0 20px rgb(195, 255, 0);
      }
      .box {
        display: flex;
        column-gap: 40px;
        background: transparent;
        position: relative;
        top: 50px;
        width: 220px;
      }
      .box-1 {
        height: 400px;
        width: 400px;
        border: 3px solid white;
        border-radius: 20px;
        background: transparent;
        position: relative;
        left: 250px;
      }
      .box-2 {
        height: 400px;
        width: 400px;
        border: 3px solid #7300ff;
        border-radius: 20px;
        background: transparent;
        position: relative;
        left: 300px;
      }
      .box-1 form {
        display: flex;
        color: white;
        background: transparent;
        padding: 10px;
        font-size: 15px;
        position: relative;
        top: 15px;
      }
      .box-1 form input {
        background: transparent;
        display: flex;
        border: 1px solid white;
        border-radius: 10px;
        padding: 15px 30px;
        font-size: 15px;
        color: white;
        position: relative;
        top: 30px;
      }
      .box-1 form textarea {
        background: transparent;
        color: white;
        padding: 15px 10px;
        position: relative;
        top: 30px;
        left: 20px;
        border: 1px solid white;
        border-radius: 10px;
        width: 300px;
      }
      .box-1 form button {
        border: 0;
        outline: none;
        padding: 10px 20px;
        color: white;
        border-radius: 30px;
        background: rgb(208, 255, 0);
        cursor: pointer;
        position: relative;
        top: 50px;
      }
      .box-2 h2 {
        color: white;
        position: relative;
        top: 25px;
        left: 50px;
        font-size: 30px;
      }
      .box-2 p {
        color: white;
        position: relative;
        top: 50px;
        padding: 10px 80px;
      }
      .box-2 span {
        color: rgb(212, 255, 0);
        font-size: 20px;
      }
      footer {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(212, 255, 0);
        color: #081b29;
        box-shadow: 0 0 20px rgb(242, 255, 0);
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo">SUB<span>A</span>SHD<span>EVELOPED</span></h1>
        <ul>
          <li><a href="home.html"> Home </a></li>
          <li><a href="products.html"> Products </a></li>
          <li><a href="council.html"> council </a></li>
          <li><a href="contact_us.html" class="bg-contact"> Contact </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button type="submit">Search</button>
        </form>
      </div>
      <div class="box">
        <div class="box-1">
          <form>
            <center>
              <h1>Contact Us</h1>
              <input type="text" placeholder="Your Name" />
              <br />
              <input type="email" placeholder="Your Email" />
              <br />
              
              <br />
              <button type="submit">Submit</button>
            </center>
          </form>
        </div>
        <div class="box-2">
          <h2>Contact Information</h2>
          <p>
            <span>Address</span> :3RD Floor, Tower 12, FCA
            Building No.90,RANGU DEVELOP CITY Phase-I MYLAPORE HR IN 2300235
          </p>
          <p><span>Email</span> : priyadeveloped.official@gmail.com</p>
          <p><span>Phone</span> : 6368945623</p>
        </div>
      </div>
    </div>
    <footer>
      <center>DESIGNED AND DEVELOPED BY SUBASH R (212223230218)</center>
    </footer>
  </body>
</html>
```

## OUTPUT:
![Screenshot 2024-04-29 140614](https://github.com/rsubash17/softweb/assets/147139828/6382786f-bfdd-4402-b247-9d4c5b772441)
![Screenshot 2024-04-29 140535](https://github.com/rsubash17/softweb/assets/147139828/68381e3c-1584-42f7-8a4b-295ec81baef2)
![Screenshot 2024-04-29 140433](https://github.com/rsubash17/softweb/assets/147139828/7acbc6cf-cdb2-4555-b3d9-944dac47e5d8)
![Screenshot 2024-04-29 140320](https://github.com/rsubash17/softweb/assets/147139828/1200a34b-7108-4b3e-8432-55d2ceaa9c37)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
