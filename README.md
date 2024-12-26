<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>car  Shop</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: rgb(0, 0, 0); 
            background: black url("./nathan-van-egmond-uwrTwMaxVR4-unsplash.jpg") no-repeat fixed right top;  
        }html{
            font-family:  "Montserrat", serif;

        }header{
            
            justify-content: space-around;
            
        }#logo{
            width: 3px;
            height: 2px;
            float: left;
            
        }
        nav ul{
            display: flex;
            justify-content: space-around;
            list-style: none;
            
        }a{
            margin: 30px 5px;
            padding: 0 2px;
            border: solid gray;
            text-decoration: none;
            border-radius: 50px;
            color: gray;
            margin: 300px 10px;
            
            
        }.sign_up{
            background-color: whitesmoke;
            color: gainsboro;
        }.sign_up:hover{
            background-color: white;
            color: red;
        }h1{
            visibility: hidden;
            margin: 100px;
        }main{
           display: grid;
           grid-template-columns: 80px 120px auto;
           grid-gap: 20px;
           justify-content: space-around;
           
        }.left{
            height: 300px;
            width: 300px;
            border: gray solid;
            border-radius: 5px;
            text-align: center;
            overflow: auto;
            color: gray;
            
        }
        .mid{
            height: 300px;
            width: 300px;
            border: gray solid;
            border-radius: 5px;
            text-align: center;
            overflow: auto;
            color: gray;
            
         }.mid h2{
            padding:0 20px 20px 20px;
         }
        .right{
            height: 300px;
            width: 300px;
            border: gray solid;
            border-radius: 5px;
            text-align: center;
            overflow: auto;
            color: gray;
        }.contact{
            grid-column: 2/3;
            height: 300px;
            width: 300px;
            text-align: center;
            overflow: auto;
            color: gray;
        }p{
            font-family:  "Montserrat", serif;
            font-size: 10px; 
            font-weight: 400; 
            margin: 10px;
        }main div a:hover{
            background-color: black;
            color: white;
        }
        


    </style>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
</head>
<body>
    <header><div id="logo">
        <legend><img src="./car-logo.svg" alt="" style="width:280px; height:200px ; align-items: start;"></legend></div>
        
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Offers</a></li>
                <li><a href="#">Buy Now</a></li>
                <li><a href="#">Sell now</a></li>
                <li ><a class="sign_up" href="#">Sign up</a></li>
            </ul>
        </nav>
        
    </header>
    
    <hr>
    <h1>hbscaj</h1>
    <main>
        <div class="left"><h2>Lamborghini Aventador LP 750 SV:</h2>
            <img src="./nathan-van-egmond-uwrTwMaxVR4-unsplash.jpg" alt="" style="width:280px; height:200px ;">
           
            <p> A stunning shot of the Aventador LP 750 SV, showcasing its sleek design and powerful stance.</p>
            <a  href="https://www.lamborghini.com/en-en" > Buy Now</a>
            </div>
        <div class="mid"><h2>Ferrari 12Cilindri:</h2>
            
        <img src="./stefano-zocca-y66Wst_aMEo-unsplash.jpg" alt="" style="width:280px; height:240px ;">
        <p> stunning shot showcasing the sleek design of the Ferrari 812 Superfast.</p>
        <a  href="https://www.ferrari.com/en-US" > Buy Now</a>
        </div>
        <div class="right"><h2>Porsche 911 Turbo S Exclusive Series 2017:</h2>
            <img src="./andras-vas-ybw0pnUJa5w-unsplash.jpg" alt="" style="width:280px; height:300px ;">
            <p>A stunning shot showcasing the sleek design of the Porsche 911 Turbo S Exclusive Series.</p>
            <a  href="https://www.porsche.com/middle-east/_india_/?cs_redirect=1" > Buy Now</a>
        </div>
        <div class="contact">
            <h2 style="font-style: italic; font-size: 40px;">Contact us</h2>
            <p style="text-align: left; font-size: 25px; color: gray;"> manager: me</p>
            <p style="text-align: left; font-size: 25px; color: gray;"> Contact: 123456789</p>
            <p style="text-align: left; font-size: 25px; color: gray;">Adrress: Home </p>


        </div>
    </main>
</body>
</html>
