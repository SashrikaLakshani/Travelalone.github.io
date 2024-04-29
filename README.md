<html>

<head>
  <title></title>
  <style> 
        .images{ 
            display: flex;  
            margin:50px; 
            padding: 50px; 
        } 
  
        #box{
        width:1000px;
        background-color:rgb(255, 266,156);
        margin:50px;
        border:50px hidden;
        padding:50px;
        }

        .menu{
        width:400px;
        float:left;
        height:70px;
        }

        ul{
        float:left;
        display:flex;
        justify-content:center;
        align-item:center;
        }
        ul li{
        list-style:none;
        margin-left:62px;
        margin-top:27px;
        font-size:14px;
        }
        ul li a{
        text-decoration:none;
        color:black;
        font-family:arial;
        font-weight:bold;
        transition:0.4s ease-in-out;
        }
        ul li a:hover{
        color: yellow;
        }
         
    </style>
</head>

<body>
<img src="galadari logo.png">
  <h1><b>Galadari Hotel</b></h1>

  <div class="menu">
    <ul>
    <li><a href="#">home</a></li>
    <li><a href="#">locations</a></li>
    <li><a href="#">rooms</a></li>
    <li><a href="#">events</a></li>
    <li><a href="#">offers</a></li>
  </ul>
  </div>
<div class="images">        
            <img src="photos/galadari.png" > 

            <img src="photos/insidegaladari1.png"> 
 
            <img src="photos/outsidegaladari3.png"> 
</div>
<div id="box">
<h2 style="text-align:center; color:rgb(255 183 0)"> Galadari Hotel Colombo</h2>
<p style="text-align:center; color:black">Welcome to Galadari Hotel, your luxurious oasis in the heart of Colombo, Sri Lanka. With stunning views of the Indian Ocean and unmatched hospitality, we offer a truly unforgettable experience. Explore our elegant accommodations, world-class dining options, and exceptional service, and discover why Galadari Hotel is the perfect choice for your next getaway or event.</p>
</div>   

<table boder="2">
<tr>
  <td> Facebook</td>
  <td><a href="https://web.facebook.com/GaladariHotel/">click here</a></td>
</tr>
  <tr>
  <td> Address</td>
  <td>64, Lotus Road, Colombo, Sri Lanka</td>
</tr>
   <tr>
  <td> Telephone no.</td>
  <td>0112 544 544</td>
   </tr>
    <tr>
  <td>Email</td>
  <td>
info@galadarihotel.lk</td>
</tr>
     <tr>
  <td>More details</td>
  <td><a href="galadarihotel.lk">galadarihotel.lk</a></td>
</tr>
</table>

<h2>Location of the hotel</h2>
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3960.6558514409458!2d79.84045207373279!3d6.9316735182881235!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3ae259251b57a431%3A0x8f44e226d6d20a7e!2sThe%20Galadari%20Hotel!5e0!3m2!1sen!2slk!4v1714291186180!5m2!1sen!2slk" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

<h2>make your reservation</h2><br>
<form action="/action_page.php" target="_blank">
<lable for="name">Name with initials : </lable>
<input type="text" id="name" name="name" placeholder="name"><br><br>
<lable for="email">Email : </lable>
<input type="text" id="email" name="email" placeholder="email"><br><br>
<lable for="address">Address : </lable>
<input type="text" id="name" name="address" placeholder="address"><br><br>
<lable for="phone-no">Phone Number : </lable>
<input type="text" id="name" name="phone-no" placeholder="phone-no"><br><br>
<lable for="room">what kind of room you hope to book : </lable>
<input type="text" id="room" name="room" placeholder="room"><br><br>
  <input type="submit" value="submit">
</form>
</body>
  
</html>
