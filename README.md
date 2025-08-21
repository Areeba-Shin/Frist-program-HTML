<!DOCTYPE html>
<html>
<head>
   
    <title>Admission Form</title>
</head>
<link href='https://fonts.googleapis.com/css?family=Baloo Bhai' rel='stylesheet'>
<style>
    body{
        margin: 0px;
        padding: 0px;
        
    }
    .img{
        position:fixed;
    }
    .header-bar{
        position: relative;
    }
    .left{
        
     display: inline-block;
     left: 23px;
     top:10px;
     position: absolute;
    
    }
    .left img{
        width: 100px;
        height: 90px;
        margin-left: 50px;
    
    }
.left h1{
    font-size: 22px;
    margin-top: 0px;
    font-family: baloo bhai;
}

    .mid{
   
    display: block;
    width: 49%;
    margin: 11px auto;
   
    
    }
    .mid-bar{
        display: inline-block;
        margin-top: 20px;
        
       
    }
    .mid-bar li{
        display: inline-block;
        
       

       
    }
    .mid-bar  a{
       
        color: black;
        font-family: baloo bhai;
        padding: 15px 10px;
        text-decoration: none;
        font-size: 22px;
       
        
        
       
    }
    .mid-bar a:hover{
        color: gray;
        text-decoration: underline;
    }
    .mid-bar a:active{
        opacity: 0.4;
    }
    .right{
        
     display: inline-block;
     right: 23px;
     top:10px;
     position: absolute;
    }
    .button{
        margin: 10px;
        font-size: 18px;
        border-radius: 4px;
        border: 2px solid gray;
       background: none;
        color: black;
        font-family: baloo bhai;
        cursor: pointer;
        
    }
    .button:hover{
        background-color: whitesmoke;
    }
    .button:active{
        opacity: 0.6;
    }
    .div-1{
        position: relative;
        margin-top: 150px;
        text-align: center;
         font-weight: bold;
         text-shadow: 1px 1px 2px;
    }
    .div-1 input{
        width: 300px;
        font-size: 25px;
        border: 1px solid grey;
        text-align: center;
        border-radius: 12px;
        background: none;
        color: black;
        font-family: baloo bhai;
        box-shadow: 1px 1px 1px;

    }
    .form-group{
        position: relative;
        font-size: 14px;
        font-family: baloo bhai;
        margin-left: 20px;
        
    }
.form-group button{
         display: block;
         width: 10%;
         margin: auto;
         cursor: pointer;
         margin-top: 10px;
         margin-left: 45px;
         padding: 10px 10px;
         font-family: baloo bhai;
         background: none;
         border: 1px solid gray;
         border-radius: 4px;
         font-size: 18px;
         font-weight: bold;
         cursor: pointer;
         box-shadow: 1px 1px 2px;
}
.form-group button:hover{
    background-color: gray;
    opacity: 0.5;
    border: 2px solid whitesmoke;
}
    
</style>
<body>
    <img class="img" src="img/pexels-oandremoura-3774895.jpg" height="600px" width="1300px">
    <header class="header-bar">
        <Div class="left">
            <img src="img/the-letters-of-the-alphabet-3246721_1280.png">
            <h1>Khubaib's Institution</h1>
        </Div>
        <Div class="mid">
            <ul>
                
                 <li class="mid-bar"><a href="#">Home</a></li>
                 <li class="mid-bar"><a href="#">Email Now</a></li>
                 <li class="mid-bar"><a href="#">Contact Us</a></li>
                 <li class="mid-bar"><a href="#">locality</a></li>
                 <li class="mid-bar"><a href="#">About Us</a></li>
                 
                 
                 
                
            </ul>
            
        </Div>
        <Div class="right">
            <button class="button">Login Now</button>
            <button class="button">More Information</button>
        </Div>
    </header>
   <div class="div-1">
    <h1>Welcome! to Khubaib's Instition</h1>
    <input type="text" placeholder="search bar">
   </div>
   <form class="form-group" action="backend.php">
    <div class="input-1">
        Name:<input type="text">
    </div>
    <br>
    <div class="input-1">
        Email:<input type="text">
    </div>
    <br>
    <div class="input-1">
        Age: <input type="text">
    </div>
    <button class="button-1">Submit Now</button>
   
   </form>
   
   
    

</body>
</html>
