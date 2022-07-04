# portfolio<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> personsle portfolio website</title>
    <link rel="stylesheet" href="style.css">


</head>
<body>
    <div class="hero">
        <nav>
            <img src="picture.jpg" class="logo">

                
        

            <ul>
                <li><a href="#">HOME</a></li>
                <li><a href="#">ABOUT</a></li>
                <li><a href="#">CONTACT ME</a></li>
                
                
            </ul>
        </nav>
        </div>
        <div class="detel">
            <P> Hi there!</P>
            <h1>I,M KAMLESH <span>KUMARI</span></h1>
            <h2><p>I AM A Front-End Developer.<br>
                   This is my official portfolio website to showes all
            <br>details and work experience web Development.
            </p></h2>
              <br>
              <br>
            <h2> <p> Personal Info</p></h2><br>
            <h3><p>Mahatma Jyotiba Phule Rohilkhand <span> university</span>,IET Bareilly Uttrapradesh, India. </p></h3>
            <p>Purshing B.TECH From Mjpru , Bareilly,uttrapresh.</p>
            
         

            <a href="#"> DOWNLOAD CV</a>

        </div>
        <div class="cs">
        <h1>CONTACT</h1>
        </div>
    <div class="contact">
        
        <ul>
        <li> <img src="linkedin.png" style="width:40px; height:40px"><br>
        <a href="https://www.linkedin.com/in/kamlesh-kumari-819639228"><u>linkedin</u> </a></li>
    
        <li><img src="instagram.png" style="width:40px; height:40px"><br>
        <a href="https://www.instagram.com/accounts/login/?source=reset_password"> <u>instagram </u></a></li>
        <li> <img src="gmail.png" style="width:40px; height:40px"><br>
        <a href="https://mail.google.com/mail/u/0/#inbox"><u>E.Mail</u> </a></li>
        </ul>
    </div>
    
</body>
</html>*{
    margin:0;
    padding:0;
    font-family:sans-serif;
}
.hero{
    position:relative;
    width:100;
    height:100vh;
    background:rgb(172, 168, 171);

}
.logo{
    width:360px;
    height:400px;
}
nav{
    display: flex;
    width: 84%;
    margin: auto;
    padding: 20px 0;
    align-items: center;

    justify-content: space-between;
}
nav ul li{
   display: inline-block; 
    list-style: none;
    margin: 10px 20px;

}
nav ul li a{
    text-decoration: none;
    color: black;
    font-weight: bold;
}
nav ul li a:hover{
  color: red;  

}
.detel{
    margin-left: 8%;
    margin-top: 13%;
}
.detel h1{
    font-size: 50px;
    color: black;
    margin-bottom: 20px;
}
.detel h2{
    font-size: 25px;
    color:black;
    margin: bottom 20px;
    
}



.detelh3{
    font-size:20px ;
    color: black;
    margin: 15px;

}
span{
    color:orangered;
}
.detel p{
    color: #212;
    line-height: 22px;
}
.detel a{
    background:#212;
padding: 10px 20px;
    text-decoration: none;
    font-weight: bold;
    color: #fff;
display: inline-block;
margin: 30px 0;
border-radius: 5px;
}

.contact ul li{
    display:inline-block;
    list-style: none;
    margin: 10px 20px;

}
.contact{
    display: flex;
    width: 84%;
    margin: auto;
    padding: 20px 0;
    align-items: center;

    justify-content: space-between;
}
.contact ul li a{
    text-decoration: none;
    color: black;
    font-weight: bold;
}
.contact ul li a:hover{
    color: rgb(111, 168, 78); 
 }
 .cs h1{
    margin-left:8%;
    margin-top:13%;

 }
 .contact img {
    
 }
