# Ex.07 Software Product Company Website
## Date:13.05.24

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
web.hml
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KRS HOME</title>
    <style>
        *{
            margin:0;
            padding:0
        }
        #nav{
            background-color:plum;
            color:#007cb9;
            padding: 15px;
    
        }
        li,h1,ul{
            display:inline;
        }
        ul{
            margin-left:45%;
        }
        a{
            color:#007cb9;
            text-decoration: none;
        }
        a:hover{
            color:yellow;
            cursor:pointer;
 }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
      
        .box {
            display:inline-block;
            border-style:dotted ;
            border-radius: 10px;
            border-color: plum;
            width: 400px;
            min-height: 300px;
            font-size: 20px;
            background-color:plum;
        
        }
        .heading1{
            color:#007cb9;
            text-align: center;
            padding-top: 20px;
        }
        .heading2{
            color:#007cb9;
            text-align: justify;
            font-size: 30px;
            margin-left: 30px;
        }
        .edge{
            padding-left: 900px;
        }
        .box{
            text-align: center;
        }
 p{
            color:#9400b9;
            text-align: center;
        }
    
        .bottomdiv{
 background-color:plum;
            color:#007cb9;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 105px;

        }
        table{
            margin-left: 40px;
        }
    </style>
</head>
<body background="webbackcover2.jpg">
    <div class="header">
        <nav id="nav">
            <h1>
                IBM
            </h1>
                <ul>
                    <li class="li1"> 
                        <a href="web.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="web2.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="web3.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="web4.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
        </nav>
    </div>
    <div class="searchbar">
    <input placeholder="search">
    </div>
        <div><pre class="heading2"><i><b>
"Fastest ever database performance. Runs faster. 
Costs less. And never breaks."<b></i></pre></div>
        <div class="edge">
            <div class="box">
            <h1 class="heading1">LOGIN HERE</h1>
            <br>
            <br>
            <form>
                <table cellpadding="15px" cellspacing="15px">
                    <tr>
                        <td>
                           <p> Username:</p>
                        </td>
                        <td>
                            <input type="email" name="name" placeholder="Enter a Email">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <p> Password:</p>
                        </td>
                        <td>
                            <input type="password" name="pwd" placeholder="Enter a Password">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" value="LOGIN" style="background-color: purple; color:white;">
                        </td>
                    </tr>
                </table>
                
            </form>
            </div>
        </div>
    <div class="bottomdiv">
        <p> Copyrights @2024 and Developed by Gokul sachin k(212223220025)</p>
    </div>
</body>
<html>

web2.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KRS_PRODUCTS</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:plum;
            color:#007cb9;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:#007cb9;
        }
        li:hover{
            color:white;
            cursor:pointer;
        }
 input{
            width: 18%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:purple;
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:plum;
            cursor:pointer;
        }
        a{
            color:#007cb9;
            text-decoration: none;
        }
        a:hover{
            color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:#007cb9;
        }
      p{
            color:#007cb9;
            text-align: center;
        }
   b{
            width: 300px;
            height: 200px;
        }
    h1{
            color:#007cb9;
            text-align: center;
        }
        .bottomdiv{
 background-color:plum;
            color:#007cb9;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 230px;

        }
    </style>
</head>
<body>
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">IBM</h1>
                <ul>
                    <li class="li1"> 
                        <a href="web.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="web2.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="web3.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="web4.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">PRODUCTS</h1>
        <br>
        <div class="product">
            <div class="box">
                <h1>Learn about OCI</h1>
                <p>IBM Cloud Infrastructure allows you to Experience tomorrow, today by efficiently building, deploying, integrating, securing, and managing all enterprise applications.uild, deploy, integrate, and extend applications in the cloud or on premises—quickly and elastically.</p>
            </div>
            <div class="box">
                <h1>Try IBM Cloud</h1>
                <p>Experience IBM Cloud Platform, a comprehensive, standards-based combination of IBM and open source technologies.</p>
            </div>
            <div class="box">
                <h1>Buy IBM Cloud</h1>
                <p>Experience tomorrow, today by efficiently building, deploying, integrating, securing, and managing all enterprise applications.</p>
            </div>
        </div>
    </div>
    <div class="bottomdiv">
        <b>Copyrights @2024 and Developed by  Gokul sachin k(212223220025)</b>
    </div>
</body>
</html>

web3.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KRS_EMPLOYEES</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:plum;
            color:#007cb9;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:#007cb9;
        }
        li:hover{
            color:#007cb9;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
        a{
            color:#007cb9;
text-decoration: none;
        }
        a:hover{
            color:#007cb9;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:#007cb9;
        }
        .bottomdiv{
            background-color:plum;
            color:#007cb9;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 0.7px;

        }
        img{
            border-radius: 50%;
            width: 200px;
            display: inline;
            padding:3px;
            
        }
        .person{
            margin:100px;
            text-align: center;
        }
        b,p{
            color:#007cb9;
            text-align: center;
        }
      
</style>
</head>
<body background="">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">IBM</h1>
                <ul>
                    <li class="li1"> 
                        <a href="web.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="web2.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="web3.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="web4.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">EMPLOYEES</h1>
        <table class="person">
            <tr>
                <td>
                    <img src="SMART2.jpg" class="MyPic">
                </td>
		

                <td>
                    <img src="K1.jpg" class="cofoundar">
                </td>
		
                <td>
                   <img src="SMILE.jpg" class="cofoundar">
                </td>
                <td>
                    <img src="K2.jpg" class="PV Sindhu">
                </td>
            </tr>
            <tr>
                <td>
                    <b>JESU SMARTIA</b>
                    <p>CEO</p>
                </td>
                <td>
                    <b>KARTHIK RAJA</b>
                    <p>CEO,Co-Founder</p>
                </td>
                <td>
                    <b>JUDITH SMILA</b>
                    <p>CTO,Co-Founder</p>
                </td>
                <td>
                    <b>KRS</b>
                    <p>CEODirector</p>
                </td>
            </tr>
        </table>
    </div>
    <div class="bottomdiv">
<p>Copyrights @2024 and Developed by Gokul sachin k(212223220025)</p>
    </div>
</body>
</html>

web4.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KRS_Contactus</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:plum;
            color:#007cb9;
                padding: 15px;
        
        }
        li,.heading1,ul{
            display:inline;        }
        ul{
            margin-left:45%
        }
        li{
            color:#007cb9;
  }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:black;
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:plum;
            cursor:pointer;
        }
        a{
            color:b#007cb9;
            text-decoration: none;
        }
        a:hover{
color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:#007cb9;
        }
        .table1{
            color:black;
            font-size: large;
        }
        .contactus{
            margin-left:400px;
        }
        .heading3{
            padding-top: 30px;
            padding-bottom: 10px;
            text-align: center;
            color:#007cb9;
        }
        .table2{
            color:#007cb9;
            font-size: large;
            background-color:plum;
            border-radius: 5px;
            border-style:dotted;
            border-color: plum;

        }
        .queries{
            margin-left:600px;
        }
        .bottomdiv{
            background-color:plum;
            color:#007cb9;
            text-align: center;
            position:relative;
display:block;
            margin-top: 24px;

        }
    </style>
</head>
<body background="webbackcover2.jpg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">IBM</h1>
                <ul>
                    <li class="li1"> 
                        <a href="web.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="web2.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="web3.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="web4.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">CONTACT US</h1>
        <div class="contactus">
            <table cellpadding="15px" cellspacing="15px" class="table1">
                <tr>
                    <td>
                        ADDRESS :
                    </td>
                    <td>
                        Anna Nagar,3nd main road south chennai
</td>
                </tr>
                <tr>
                    <td>
                        LANDMARK :
                    </td>
                    <td>
                        chennai
                    </td>
                </tr>
                <tr>
                    <td>
                        Email :
                    </td>
                    <td>
                        ibm@gmail.com
                    </td>
                </tr>
                <tr>
                    <td>
                        PHONE :
                    </td>
                    <td>
                        8667031421
                    </td>
                </tr>
            </table>
        </div>
        <div>
            <h3 class="heading3">QUERIES</h3>
            <div class="queries">
                <table cellpadding="15px" cellspacing="15px" class="table2">
                    <tr>
                        <td>
 NAME :
                        </td>
                        <td>
                            <input type="name" placeholder="Enter your name"> 
                        </td>
                    </tr>
                    <tr>
                        <td>
                            EMAIL :
                        </td>
                        <td>
                            <input type="email" placeholder="Enter your E-mail">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            MESSAGE :
                        </td>
                        <td>
                            <input type="text" placeholder="Enter your text">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" style="background-color: white; color:#007cb9;">
                        </td>
                    </tr>
            </table>
        </div>
        <div class="bottomdiv">
            <p>Copyrights @2024 and Developed by Gokul sachin k(212223220025)</p>
        </div>
    </div>
</body>
</html>

```
## OUTPUT:

![image](https://github.com/vksachin2018/softweb/assets/149366019/3de3299f-e8be-4134-8ae5-e0b22e65843f)

![image](https://github.com/vksachin2018/softweb/assets/149366019/9f4f8db8-0fdd-4f2d-be59-b0367e6983a1)

![image](https://github.com/vksachin2018/softweb/assets/149366019/e71b227c-8a53-4b3b-b4ac-5a186ca7e4ec)

![image](https://github.com/vksachin2018/softweb/assets/149366019/a564ad52-52fc-4bb8-b190-8191c996c3fb)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
