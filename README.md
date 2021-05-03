Nama   :  Syaefur Rohman

NIM    : 311910772

Kelas  : TI 19 B2

Matkul : Pemograman web


Tugas Praktikum pemrograman web


hasil pengerjaan
sumber link (url(https://www.sinarjayagroup.co.id/images/slider/klikuto_1.jpg


home.html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Ticket Bus Sinar Jaya</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
    <link href="https://fonts.googleapis.com/css?family=Hanalei+Fill" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Fredericka+the+Great" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Fredericka+the+Great|Hanalei+Fill|Noto+Serif+JP|Raleway" rel="stylesheet">  
  </head>
  <body>




    <div class="wrapper">
      <div class="nav">
        <div class="logo">
          <a href="#">
          <p>Ticket Bus Sinar Jaya</p>
          </a>
        </div>
        <ul>
          <li>Home</li>
          <li>About us</li>
          <li>Service</li>
          <li>Team</li>
          <li>Price</li>
          <li>Blog</li>
          <li>Contact</li>
          <li>Pages</li>
        </ul>
      </div>
    
      <div class="down">
        <h1>
          <small>
            Tetap Jaga Prokes agar kita tenang dan nyaman dalam berkendara
          </small>
          </h1>
        <h2>  Kapan lagi naik bis keren dan gak bikin kantong kering 
        </h2>
        <p>
          Ayo kita naik bus lebih nyaman dan aman
        </p>

       <h3>
         <button>Pesan Disini</button>

      
       </h3>

       
      </div>
    </div>
  </body>
</html>




Style.css
html{
  margin: 0;
  padding: 0;
  width: 100%;
}
body{
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  background: url(https://www.sinarjayagroup.co.id/images/slider/klikuto_1.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  display: block;
}
.logo{
  float: left;
  color: #7b67ec;
  margin-left: 46px;
  padding: 0px 38px;
  font-family: 'Raleway', sans-serif;
  font-size: 25px;
  font-weight: bold;
}
.logo a{
  text-decoration: none;
  color: #1713e7;
}
.nav{
  position: absolute;
  top: 0;
  left:  0;
  margin: 0;
  padding: 0;
  height: 80px;
  width: 100%;
}
.nav ul{
  list-style: none;
  cursor: pointer;
  float: right;
  margin-right: 140px;
}
.nav ul li {
  list-style: none  ;
  display: inline-block;
  color:#090df5;
  font-family: 'Raleway', sans-serif;
  padding: 15px 15px;
  font-weight: 400;
}
.nav ul li:hover{
  border-bottom: 3px solid #0d9b6c;
  transition: all .3s ease;
}
.logo h1{
  color: #fff;
  font-family: 'Fredericka the Great', cursive;
}
.header{
  text-align: right;
  position: absolute;
  top: 40%;
  left: 70%;
  transform: translate(-50% ,-50%);
}
.header h1{
  color: #c2e913;
  text-align: left;
  font-family: 'Noto Serif JP', sans-serif;
  font-size: 50px;
}
.header span{
  color: #0d9b6c;
}
.tagline{
  position: absolute;
  transform: translate(-50%,-50%);
  text-align: right;
  top: 55%;
  left: 73%;
}
.tagline p{
  color: rgb(26, 228, 53);
  font-family: 'Raleway', sans-serif;
  font-size: 18px;
  text-align: left;
  color:  #0b75ee;
}
.down{
  position: absolute;
  top: 50%;
  left:36%;
  transform: translate(-50%,-50%);
  color: #b80d0d;
}
a, button{
  background: #75ec14;
  font-size: 30px;
  border-radius: 10px;
 
 
}

