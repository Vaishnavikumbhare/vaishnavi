
[2/1, 12:56 PM] Shital: Index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="img"></div>
  <div class="center">
    <div class="title">RTMNU E-MAGZINE</div>
    <div class="btns">
      <a href="http://127.0.0.1:5500/login.html"><link rel="stylesheet" href="style3.css"><button>Login</button>
      
      <a href="http://127.0.0.1:5500/register.html"><button>Register</button>
    </div>
  </body>
</html>







 
Login.html
<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="style1.css">
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=<div class=box">
   
</head>
<body>
    <div class="box">
        <i class="fa fa-user"></i>
        <input type="EmaiL" name="EmaiL" ID="EmaiL" placeholder="Enter Your EmaiL" required>
    </div>
    <div class="box">
        <i class="fa-regular fa-key"></i>
        <input type="Password" name="Password" id="Password" placeholder="Create Your Password" required>
    </div>
    <a href="http://127.0.0.1:5500/main.html"><button>Enter</button>
</body>
</html>
[2/1, 12:56 PM] Shital: Main.html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style2.css">
   </head>
<body>
  <nav>
    <div class="menu">
      <div class="logo">
       
      </div>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Magzines</a></li>
        <li><a href="#">Feedback</a></li>
      </ul>
    </div>
  </nav>
  <div class="img"></div>
  <div class="center">
    <div class="title">Welcome To RTMNU E-Magzine </div>
    <a href="http://127.0.0.1:5500/mode.html">
  </div>
</body>

</html>
Style.css
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins',sans-serif;
}
body{
  background: url(rtmnu.jpg) no-repeat center center fixed;
  background-size: cover;
}

::selection{
  color: #000;
  background: #fff;
}
nav{
  position: fixed;
  background: #1b1b1b;
  width: 100%;
  padding: 10px 0;
  z-index: 12;
}
nav .menu{
  max-width: 1250px;
  margin: auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 20px;
}
.menu .logo a{
  text-decoration: none;
  color: #fff;
  font-size: 35px;
  font-weight: 600;
}
.menu ul{
  display: inline-flex;
}
.menu ul li{
  list-style: none;
  margin-left: 7px;
}
.menu ul li:first-child{
  margin-left: 0px;
}
.menu ul li a{
  text-decoration: none;
  color: #fff;
  font-size: 18px;
  font-weight: 500;
  padding: 8px 15px;
  border-radius: 5px;
  transition: all 0.3s ease;
}
.menu ul li a:hover{
  background: #fff;
  color: black;
}
.img{
  
  width: 100%;
  height: 100vh;
  background-size: cover;
  background-position: center;
  position: relative;
}
.img::before{
  content: '';
  position: absolute;
  height: 100%;
  width: 100%;
  background: rgba(0, 0, 0, 0.4);
}
.center{
  position: absolute;
  top: 52%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 100%;
  padding: 0 20px;
  text-align: center;
}
.center .title{
  color: #fff;
  font-size: 55px;
  font-weight: 600;
}
.center .sub_title{
  color: #fff;
  font-size: 52px;
  font-weight: 600;
}
 .btns{
   margin-top: 20px;
 }

.center .btns button{
  height: 55px;
  width: 170px;
  border-radius: 5px;
  border: none;
  margin: 0 10px;
  border: 2px solid white;
  font-size: 20px;
  font-weight: 500;
  padding: 0 10px;
  cursor: pointer;
  outline: none;
  transition: all 0.3s ease;
}
body{
  margin: 0;
  padding: 0;
  height: 100vh;
  justify-content: center;
  align-items: center;
  display: flex;

}
Style1.css
*{
    margin: 0;
    padding: 0;
}
body{
    background: gray
}

.container{
    color: white;
    position: absolute;
    top: 35%;
    left: 40%;
}

.container h1{
    font-size: 40;
    margin-bottom: 43px;
    padding: 13px 0;
    border-color: white;
    border-radius: 10px;
}

.box{
    
    width: 40%;
    margin: 22px 0;
}
.box:hover{
   
    opacity: 0.6;
}
.box input{
    background: lightcyan;
    padding: 5px 10px;
    border-color: white;
    width: 75%;
    border-radius: 10px;
    font-size: 20px;
    border: none;
    outline: none;
    color: black;
}
.box i{
    width: 25px 0.8;
    text-align: center;
    border-color: white;
}
.btn{
    cursor: pointer;
    outline: none;
    width: 10%;
    padding: 10px 21px;
    border-radius: 10px;
    font-size: 13px;
    background: white;
    font-weight: bold;
}
.btn:hover{
   
    background: darkcyan;
    opacity: 0.8;
}
Style2.css
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins',sans-serif;
}
::selection{
  color: #000;
  background: #fff;
}
nav{
  position: fixed;
  background: #1b1b1b;
  width: 100%;
  padding: 10px 0;
  z-index: 12;
}
nav .menu{
  max-width: 1250px;
  margin: auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 20px;
}
.menu .logo a{
  text-decoration: none;
  color: #fff;
  font-size: 35px;
  font-weight: 600;
}
.menu ul{
  display: inline-flex;
}
.menu ul li{
  list-style: none;
  margin-left: 7px;
}
.menu ul li:first-child{
  margin-left: 0px;
}
.menu ul li a{
  text-decoration: none;
  color: #fff;
  font-size: 18px;
  font-weight: 500;
  padding: 8px 15px;
  border-radius: 5px;
  transition: all 0.3s ease;
}
.menu ul li a:hover{
  background: #fff;
  color: black;
}
.img{
  background: url('img3.jpg')no-repeat;
  width: 100%;
  height: 100vh;
  background-size: cover;
  background-position: center;
  position: relative;
}
.img::before{
  content: '';
  position: absolute;
  height: 100%;
  width: 100%;
  background: rgba(0, 0, 0, 0.4);
}
.center{
  position: absolute;
  top: 52%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 100%;
  padding: 0 20px;
  text-align: center;
}
.center .title{
  color: #fff;
  font-size: 55px;
  font-weight: 600;
}
.center .sub_title{
  color: #fff;
  font-size: 52px;
  font-weight: 600;
}
.center .btns{
  margin-top: 20px;
}
.center .btns button{
  height: 55px;
  width: 170px;
  border-radius: 5px;
  border: none;
  margin: 0 10px;
  border: 2px solid white;
  font-size: 20px;
  font-weight: 500;
  padding: 0 10px;
  cursor: pointer;
  outline: none;
  transition: all 0.3s ease;
}
.center .btns button:first-child{
  color: #fff;
  background: none;
}
.btns button:first-child:hover{
  background: white;
  color: black;
}
.center .btns button:last-child{
  background: white;
  color: black;
}
Style3.css
body{
    margin: 0;
    padding: 0;
    height: 100vh;
    justify-content: center;
    align-items: center;
    display: flex;

}
.btn{
    font-family: "Roboto", sans-serif;
    font-size: 18px;
    font-weight: bold;
    background: #1e90ff;
    width: 160px;
    padding: 20px;
    text-align: center;
    text-decoration: none;
    text-transform: uppercase;
    color: #fff;
    border-radius: 5px;
    cursor: pointer;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    -webkit-transition-property: box-shadow, transform;
    transition-property: box-shadow, transform;

}
.btn:hover, .btn:focus, .btn:active{
    box-shadow: 0, 0, 20px rgba(0, 0, 0, 0.5);
    -webkit-transform: scale(1.1);
    transform: scale(1.1);
}
Abc.php
<?php
$insert = false;
if(isset($_POST['name'])){
    // Set connection variables
    $server = "localhost";
    $username = "root";
    $password = "";

    // Create a database connection
    $con = mysqli_connect($server, $username, $password);

    // Check for connection success
    if(!$con){
        die("connection to this database failed due to" . mysqli_connect_error());
    }
    // echo "Success connecting to the date";

    // Collect post variables
    $name = $_POST['name'];
    $Email = $_POST['Email'];
    $password = $_POST['Password'];
    $Number = $_POST['Number'];
    $sql = "INSERT INTO `data` (`Sr.no.`, `Name`, `Email`, `Password`, `number`, `date`) VALUES ('$name', '$Email', '$password', '$Number', current_timestamp());"
    // Execute the query
    if($con->query($sql) == true){
         echo "Successfully inserted";

        // Flag for successful insertion
    }
    else{
        echo "ERROR: $sql <br> $con->error";
    }

    // Close the database connection
    $con->close();
}
?>
