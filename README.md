# HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Card Design in html and css</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <style>
        *{
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }
        body{
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
          
        }
        .Container{
            height: 450px;
            width: 300px;
            overflow: hidden;
            box-shadow: 3px 3px 19px black;
            border-radius: 10px;
            background-color:#939185;
        }
        .logo-icon{
            padding: 10px;
            display: flex;
            align-items: center;
            justify-content: space-between; background-color: #B6C7AA;
        }
        .logo-icon img{
            height: 25px;
        }
        .logo-icon .bi-bag{
            font-size: 25px;
        }
        .shoes-img img{
            width: 300px;
            filter: drop-shadow(25px 25px 10px rgba(0, 0, 0, 0.5));
        }
        .card-text{
            padding: 10px; 
            background-color: #E7D4B5;
           
        }
        .card-text .span1{
            font-weight: bold;
            font-size: 15px;
            font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            color:#EE4E4E;
        }
        .card-text p{
            font-size: small;
            color: black;
        }
        .card-text .bi-star-fill,.bi-star{
            font-size: 12px;
        }
        .color-price{
            margin-top: 10px;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        .blue-background-round{
            height: 15px;
            width: 15px;
            border-radius: 50%;
            background-color: black;
        }
        .red-background-round{
            height: 15px;
            width: 15px;
            border-radius: 50%;
            background-color:white;
            border: 2PX solid black;
        }
        .yellow-background-round{
            height: 15px;
            width: 15px;
            border-radius: 50%;
            background-color: SILVER;
           
        }
        .color-round{
            display: flex;
            align-items: center;
            width: 120px;
            justify-content: space-between;
            
        }
        .color-price div span{
            font-size: 10px;
        }
        .buy-button{
            padding: 10px;
            background-image: linear-gradient(to right, rgba(0, 0, 255, 0.53), rgba(128, 0, 128, 0.493));
            font-size: 20px;
            font-weight: bold;
            border-radius: 40px;
            text-align: center;
            color: white;
            font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div class="Container">
        <div class="logo-icon">
            <img src="C:/sachin singh/sachin html/images-car-logo-removebg.png" alt="logo for card">
            <i class="bi bi-heart"></i>
        </div>
        <div class="shoes-img">
            <img src="C:\Users\Sachin Rajput\Downloads\project-image-removebg.png" alt="image">
        </div>
        <div class="card-text">
            <span class="span1">SCORPIO S11 CLASIC</span>
            <p>The Scorpio S11 Classic is a variant of the Mahindra Scorpio, a popular SUV in India. It is known for its rugged build, powerful performance.</p>
            <div><i class="bi bi-star-fill"></i> <i class="bi bi-star-fill"></i> <i class="bi bi-star-fill"></i> <i class="bi bi-star-fill"></i> <i class="bi bi-star-fill"></i></div>
            <div class="color-price">
               <div class="color-round">
                <h3>Color :</h3>
                <div class="blue-background-round"></div>
                <div class="red-background-round"></div>
                <div class="yellow-background-round"></div>
               </div>
               <div><h3>₹ 22 L/-</h3><span>twenty two lakh only</span></div>
            </div>
            <div class="buy-button">
                view details
            </div>
        </div>
    </div>
</body>
</html>
