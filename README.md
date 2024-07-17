# 2.
# tourism
## first.html
```c

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playwrite+CU:wght@100..400&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bodoni+Moda+SC:ital,opsz,wght@0,6..96,400..900;1,6..96,400..900&family=Ga+Maamli&family=Playwrite+CU:wght@300&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bodoni+Moda+SC:ital,opsz,wght@0,6..96,400..900;1,6..96,400..900&family=Bona+Nova+SC:ital,wght@0,400;0,700;1,400&family=Ga+Maamli&family=Playwrite+CU:wght@300&display=swap" rel="stylesheet">
    
    
    <title>City Tourism</title>
</head>
<style>
        .back{
            
            background-image:  url(back.png);
            background-repeat: no-repeat;
            background-attachment:local;
            background-size:cover;
            background-blend-mode: darken;
            border-radius: 90px;
            

        }
        .logo{   
        
            display: flex;
            justify-content: center; 
            align-items: center; 
            margin: auto;
            width: 75%;
            height: 175px; 
            
        }
        
        .name{
            display: flex;
            justify-content: flex-start; 
            align-items: center ; 
            width: 100%;
            height: 155px; 
            font-size: 82px;
            
            margin: 13px;
            color:rgb(133, 14, 115);
            font-family: "Roboto Slab", serif;
            font-optical-sizing: auto;
            font-family: "Playwrite CU", cursive;
            font-optical-sizing: auto;
            font-weight: weight;
            font-style: normal;
            padding-right: 90px;
        }
        .fot{
            display: flex;
            justify-content: center;
            align-items: center;
            color: rgb(0, 17, 17);
            

        }
   

        .menu-bar {

            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
            
            position: relative;
            font-size: 40px;
            font-family: "Ga Maamli", sans-serif;
            font-weight: 400;
            font-style: normal;
        }

        .menu-bar select {
            padding: 10px;
            font-size: 16px;
            border-radius: 5px;
            border: 1px solid #ccc;
            appearance: none;
            background-color: #7c2222;
            color: #000;
        }

        .menu-input{
            display: flex;
            justify-content: center;
            align-items:center;
            padding: 18px;
            border-radius: 80px;
            font-family: "Ga Maamli", sans-serif;
            font-weight: 400;
            font-style: normal;
            color: rgb(255, 3, 3);
        }
        .wel{
            display: flex;
            justify-content: flex-start;
            font-family: "Ga Maamli", sans-serif;
            font-weight: 400;
            font-style: normal;
            font-size: 50px;
            max-height: 120px;

        }
        .para{
            font-size: 20px;
            font-weight: bold;
            font-size: x-large;
            color: rgb(2, 2, 2);
        }
        .contact{
            display: flex;
            justify-content: center;
            font-family: "Bona Nova SC", serif;
            font-weight: 400;
            font-style: normal;
            font-weight: bold;
            font-size: 35px;
            color:rgb(2, 80, 159);
            margin: 18px;
            max-height: 32px;

        }
        .mobile{
            display: flex;
            justify-content: space-around; 
            font-weight: bold;
            margin: 50px;
            color: rgb(143, 16, 16);
        }
        .menu{
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .menu li{
            display: inline-block;
            margin:  20px;
            font-size: x-large;
            color:blue;
            margin: 35px;
        }
        .menu ul{
            list-style: none;
            text-align: center;
            
        }
        .menu a{
            text-decoration: rgb(100, 0, 57);
            color: rgb(156, 232, 35);
            

            font-weight: 800;

        }
        .menu a:hover{

            background: #011213;
            border-radius: 10px;
            width: 8000px;
            height: 8px;
        }
    
 
   
  
   
</style>
<body>
    
    <header class="back">
        <img  src="logo.png" alt="City Logo" class="logo">      
    
        <p class="name" >Hey Chennai !</p>
       
        <div class="menu-bar">
            <label for="menu" style="color: rgb(0, 0, 0); margin-right: 10px;">Navigate to:</label>
        </div>
        <div class="menu">  
            <ul>
                
                <li><a href="index.html">Home</a></li>
                <li><a href="heritage.html">Heritage</a></li>
                <li><a href="hotel.html">Hotel Booking</a></li>
                <li><a href="gallery.html">Gallery</a></li>
            </ul>
        </div>
    </header>
        <div class="wel">
        <p class="kyt">Welcome,</p>
         </div>
        <div class="para">
            <ul>
            <P>
                * Here, history blends seamlessly with the present; leaving a visitor astonished at the contrast of experiences. On one end, there is a bustling metropolitan city and on the other, a centre of culture, art and learning. Welcome to Chennai!
            </p>
            <p>
                * One of the major industrial, commercial and cultural centres in India, Chennai is the capital city of Tamil Nadu. A city of great history and heritage, Chennai is today one of the most visited cities in the world. Originally called Madras, Chennai is located along the Coromandel Coast in the Bay of Bengal and is a major port city in the region.
            </p>
            <p>
                * Chennai is often referred to as the Detroit of India because of the presence of a thriving automobile sector. Chennai is also home to many major industries that add significantly to the financial growth of India. Lately Chennai has also risen in ranks as one of the most promising IT destinations in India. Once the capital of South Indian cinema, today Chennai is home to the Tamil Film industry that has viewers all over the world. 
            </p>
            <p>
                * However, Chennai is much more than high rises and Hi-tech IT parks. The city boasts of various scenic spots and celebratory ambiances that make the place a preferred travel location for tourists from across the world. The Koovam river flows through the heart of Chennai and the Adyar River through the South. Being a coastal destination, Chennai is blessed with many picturesque beaches as well. All these offer a traveller stunning views to cherish for a lifetime. The real beauty of Chennai lies in its intrinsic traditional traits. Referred to as the cultural capital of the South, Chennai enthrals the visitors with its distinctive architecture, music, art, heritage, monuments and warm hospitality. So if you are looking to visit a destination that offers a multisensory tour experience, then Chennai is the place to be in.
            </p>
        </ul>
        </div>
        <div class="contact">
            <p>Contact Us</p>
            
        </div>
        <div class="mobile">
            <p>Mobile number : 7904399208</p>
            <p>Mail ID : tourismchennai@gmail.com</p>
        </div>
    
    
    <footer class="fot">
        <p>&copy; 2024 Mohan raj 64. All rights reserved.</p>
    </footer>
</body>
</html>
```

## index.html
``` c
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/styles.css">
    <link rel="stylesheet" href="css/styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playwrite+CU:wght@100..400&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bodoni+Moda+SC:ital,opsz,wght@0,6..96,400..900;1,6..96,400..900&family=Ga+Maamli&family=Playwrite+CU:wght@300&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bodoni+Moda+SC:ital,opsz,wght@0,6..96,400..900;1,6..96,400..900&family=Bona+Nova+SC:ital,wght@0,400;0,700;1,400&family=Ga+Maamli&family=Playwrite+CU:wght@300&display=swap" rel="stylesheet">
    <title>City Tourism - Home</title>
</head>
<style>
     .back{
        
        background-image:  url(back2.png);
        background-repeat: no-repeat;
        background-attachment: local;
        background-size: cover;
        background-blend-mode: darken;
        border-radius: 190px;

    }
    .logo{   
       
       display: flex;
       justify-content: center; 
       align-items: center; 
       margin: auto;
       width: 75%;
       height: 175px; 
       
   }
   .name{
        display: flex;
        justify-content: flex-start; 
        align-items: center ; 
        width: 100%;
        height: 155px; 
        font-size: 82px;
        
        margin: 13px;
        color:rgb(133, 14, 115);
        font-family: "Roboto Slab", serif;
        font-optical-sizing: auto;
        font-family: "Playwrite CU", cursive;
        font-optical-sizing: auto;
        font-weight: weight;
        font-style: normal;
        padding-right: 90px;
    }
    .wel{
            display: flex;
            justify-content: flex-start;
            font-family: "Ga Maamli", sans-serif;
            font-weight: 400;
            font-style: normal;
            font-size: 50px;
            max-height: 120px;

        }
    .para{
            
            font-size: 20px;
            font-weight: bold;
            font-size: x-large;
            color: rgb(2, 2, 2);

        }
    .fot{
    display: flex;
    justify-content: center;
    align-items: center;
    color: rgb(1, 1, 1);
    

   }
   .menu{
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .menu li{
            display: inline-block;
            margin:  20px;
            font-size: x-large;
            color:blue;
            margin: 35px;
        }
        .menu ul{
            list-style: none;
            text-align: center;
            
        }
        .menu a{
            text-decoration: rgb(100, 0, 57);
            color: rgb(8, 101, 145);
            

            font-weight: 800;

        }
        .menu a:hover{

            background: #89f71b;
            border-radius: 10px;
            width: 8000px;
            height: 8px;
        }
        .menu-bar {

            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;

            position: relative;
            font-size: 40px;
            font-family: "Ga Maamli", sans-serif;
            font-weight: 400;
            font-style: normal;
        }

        .menu-bar select {
            padding: 10px;
            font-size: 16px;
            border-radius: 5px;
            border: 1px solid #ccc;
            appearance: none;
            background-color: #7c2222;
            color: #000;
        }

        .contact{
            display: flex;
            justify-content: center;
            font-family: "Bona Nova SC", serif;
            font-weight: 400;
            font-style: normal;
            font-weight: bold;
            font-size: 35px;
            color:rgb(2, 80, 159);
            margin: 18px;
            max-height: 32px;

        }
        .mobile{
            display: flex;
            justify-content: space-evenly;
            font-weight: bold;
            margin: 40px;
            color: rgb(129, 4, 4);
            font-size: x-large;
        }
        .ali{
            display:flex;
            justify-content: center;
            font-family:'Times New Roman', Times, serif;
            color: rgb(56, 0, 221);
        }
       
    </style>
</style>
<body>
    <header class="back">

        <img  src="logo.png" alt="City Logo" class="logo">  
            <p class="name" >Hello !</p>

           <h1 class="ali">Home page</h1>
        
    
     
            <div class="menu-bar">
                <label for="menu" style="color: rgb(0, 0, 0); margin-right: 10px;">Navigate to:</label>
            </div>
    </header>
        
        
            <div class="menu">  
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="heritage.html">Heritage</a></li>
                    <li><a href="hotel.html">Hotel Booking</a></li>
                    <li><a href="gallery.html">Gallery</a></li>
                </ul>
            </div>
        </nav>
   
        <section class="wel">
            <p class="kyt">Welcome,</p>
        </section>
    <main class="para">
        <ul>
        <p>Chennai, on the Bay of Bengal in eastern India, is the capital of the state of Tamil Nadu. The city is home to Fort St. George, built in 1644 and now a museum showcasing the city’s roots as a British military garrison and East India Company trading outpost, when it was called Madras. Religious sites include Kapaleeshwarar Temple, adorned with carved and painted gods, and St. Mary’s, a 17th-century Anglican church</p>
        </ul>
    </main>
    <div class="contact">
        <p>Contact Us</p>
        
    </div>
    <div class="mobile">
        <p>Mobile number : 7904399208</p>
        <p>Mail ID : tourismchennai@gmail.com</p>
    </div>
    <footer class="fot">
        <p>&copy; 2024 Mohan raj 64. All rights reserved.</p>
    </footer>
</body>
</html>

```

## heritage.html

```c
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playwrite+CU:wght@100..400&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bodoni+Moda+SC:ital,opsz,wght@0,6..96,400..900;1,6..96,400..900&family=Ga+Maamli&family=Playwrite+CU:wght@300&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bodoni+Moda+SC:ital,opsz,wght@0,6..96,400..900;1,6..96,400..900&family=Bona+Nova+SC:ital,wght@0,400;0,700;1,400&family=Ga+Maamli&family=Playwrite+CU:wght@300&display=swap" rel="stylesheet">
    <title>City Tourism - Heritage</title>
</head>
<style>
    .back{
        
        background-image:  url(back3.png);
        background-repeat: no-repeat;
        background-attachment:local;
        background-size:cover;
        background-blend-mode: darken;
        border-radius: 90px;
        

    }
    .hertiage{
        display: flex;
        justify-content: center;
        align-items: auto;
        width: 50px;
        height: 50px;

    }
    .logo{   
       
       display: flex;
       justify-content: center; 
       align-items: center; 
       margin: auto;
       width: 75%;
       height: 175px; 
       
   }
    
    .column{
        float: left;
        width: 33%;
        padding: 5px;

    }
    .row::after{
        content: "";
        display: table;
        clear: both;
        
    }
    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
    
    main{
        max-width: 1200px;
        margin: auto;
        padding: 20px;
    }
    .shots{
        display: grid;
        grid-template-columns: repeat(auto-fill,minmax(200px,1fr));
        gap: 20px;
    }
    .shot{
        background-color:white;
        padding: 10px;
        border-radius: 10px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        transition: transform 0.3s, box-shadow 0.3s;
    }
    .shot:hover{
        transform: translateY(-5px);
        box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);;
    }
    .shot img{
       
        border-radius: 5px;
        width: 200px;
        height: 200px;
        
    }
    .shot-info{
        display: flex;
        justify-content: space-between;
        margin-top: 10px;
    }
    .herit{
        display: flex;
        justify-content: center;
        margin: 5%;
        font-family: "Ga Maamli", sans-serif;
        font-weight: 400;
        font-style: normal;
        font-size: xxx-large;
    }
    .menu{
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .menu li{
            display: inline-block;
            margin:  20px;
            font-size: x-large;
            color:blue;
            margin: 35px;
        }
        .menu ul{
            list-style: none;
            text-align: center;
            
        }
        .menu a{
            text-decoration: rgb(100, 0, 57);
            color: rgb(13, 14, 13);
            

            font-weight: 800;

        }
        .menu a:hover{

            background: #0cd1db;
            border-radius: 10px;
            width: 8000px;
            height: 8px;
        }
        .name{
            display: flex;
        justify-content: flex-start; 
        align-items: center ; 
        width: 100%;
        height: 155px; 
        font-size: 82px;
        
        margin: 13px;
        color:rgb(133, 14, 115);
        font-family: "Roboto Slab", serif;
        font-optical-sizing: auto;
        font-family: "Playwrite CU", cursive;
        font-optical-sizing: auto;
        font-weight: weight;
        font-style: normal;
        padding-right: 90px;
        }
        .fot{
    display: flex;
    justify-content: center;
    align-items: center;
    color: rgb(0, 17, 17);
    

   }
   .contact{
            display: flex;
            justify-content: center;
            font-family: "Bona Nova SC", serif;
            font-weight: 400;
            font-style: normal;
            font-weight: bold;
            font-size: 35px;
            color:rgb(2, 80, 159);
            margin: 18px;
            max-height: 32px;

        }
        .mobile{
            display: flex;
            justify-content: space-evenly;
            font-weight: bold;
            margin: 40px;
            color: rgb(129, 4, 4);
            font-size: x-large;
        }

</style>
<body>
    <header class="back">
        <img  src="logo.png" alt="City Logo" class="logo">      
    
        <p class="name" >Vanakam</p>
        
            <div class="menu">  
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="heritage.html">Heritage</a></li>
                    <li><a href="hotel.html">Hotel Booking</a></li>
                    <li><a href="gallery.html">Gallery</a></li>
                </ul>
            </div>
        
    </header>
    <main>
        <h2 class="herit"> Heritages</h2>

        <section class="shots">
            
        
            
               <div class="shot">
                <img src="he1.png" alt="shot 1">
                <div class="shot-info">
                    <div></div>
                    <div></div>
                </div>
               </div>
               <div class="shot">
                <img src="he3.png" alt="shot 2">
                <div class="shot-info">
                    <div></div>
                    <div></div>
                </div>
               </div>
               <div class="shot">
                <img src="he2.png" alt="shot3">
                <div>
                    <div></div>
                    <div></div>
                </div>
               </div>
               <div class="shot">
                <img src="he4.png" alt="shot4">
                <div>
                    <div></div>
                    <div></div>
                </div>
               </div>
               <div class="shot">
                <img src="he5.png" alt="shot5">
                <div>
                    <div></div>
                    <div></div>
                </div>
               </div>
               <div class="shot">
                <img src="he6.png" alt="shot6">
                <div>
                    <div></div>
                    <div></div>
                </div>
               </div>
               <div class="shot">
                <img src="he7.png" alt="shot7">
                <div>
                    <div></div>
                    <div></div>
                </div>
               </div>
               <div class="shot">
                <img src="he8.png" alt="shot8">
                <div>
                    <div></div>
                    <div></div>
                </div>
               </div>
               <div class="shot">
                <img src="he9.png" alt="shot9">
                <div>
                    <div></div>
                    <div></div>
                </div>
               </div>
               <div class="shot">
                <img src="he10.png" alt="shot10">
                <div>
                    <div></div>
                    <div></div>
                </div>
               </div>
               
              </section>
                
       
    </main>
    <div class="contact">
        <p>Contact Us</p>
        
    </div>
    <div class="mobile">
        <p>Mobile number : 7904399208</p>
        <p>Mail ID : tourismchennai@gmail.com</p>
    </div>
    <footer class="fot">
        <p>&copy; 2024 Mohan raj 64. All rights reserved.</p>
    </footer>
</body>
</html>

```
## hotel.html
```c
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="../css/styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playwrite+CU:wght@100..400&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bodoni+Moda+SC:ital,opsz,wght@0,6..96,400..900;1,6..96,400..900&family=Ga+Maamli&family=Playwrite+CU:wght@300&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <title>City Tourism - Heritage Site 1</title>
</head>
<style>
    .back{
            
            background-image:  url(back4.png);
            background-repeat: no-repeat;
            background-attachment:local;
            background-size:cover;
            background-blend-mode: darken;
            border-radius: 90px;
            

        }
    .logo{   
       
       display: flex;
       justify-content: center; 
       align-items: center; 
       margin: auto;
       width: 75%;
       height: 175px; 
       
   }
   .name{
        display: flex;
        justify-content: flex-start; 
        align-items: center ; 
        width: 100%;
        height: 155px; 
        font-size: 82px;
        
        margin: 13px;
        color:rgb(133, 14, 115);
        font-family: "Roboto Slab", serif;
        font-optical-sizing: auto;
        font-family: "Playwrite CU", cursive;
        font-optical-sizing: auto;
        font-weight: weight;
        font-style: normal;
        padding-right: 90px;
    }
    .menu{
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .menu li{
            display: inline-block;
            margin:  20px;
            font-size: x-large;
            color:blue;
            margin: 35px;
        }
        .menu ul{
            list-style: none;
            text-align: center;
            
        }
        .menu a{
            text-decoration: rgb(100, 0, 57);
            color: rgb(94, 149, 6);
            

            font-weight: 800;

        }
        .menu a:hover{

            background: #011213;
            border-radius: 10px;
            width: 8000px;
            height: 8px;
        }
        .menu-bar select {
            padding: 10px;
            font-size: 16px;
            border-radius: 5px;
            border: 1px solid #ccc;
            appearance: none;
            background-color: #7c2222;
            color: #000;
        }

        .menu-input{
            display: flex;
            justify-content: center;
            align-items:center;
            padding: 18px;
            border-radius: 80px;
            font-family: "Ga Maamli", sans-serif;
            font-weight: 400;
            font-style: normal;
            color: rgb(255, 3, 3);
        }
        .menu-bar {

            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;

            position: relative;
            font-size: 40px;
            font-family: "Ga Maamli", sans-serif;
            font-weight: 400;
            font-style: normal;
        }
        .imag{
            display: flex;
            justify-content: center;
            border-image:stretch;

        }
        .book{
            display: flex;
            justify-content: center;
            font-family: "Ga Maamli", sans-serif;
            font-weight: 400;
            font-style: normal;
            font-stretch:ultra-expanded;
            font-size: xx-large;

        }
        .para{
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 20px;
            font-weight: bold;
            font-size: x-large;
            color: rgb(2, 2, 2);
        }
        .contact{
            display: flex;
            justify-content: center;
            font-family: "Bona Nova SC", serif;
            font-weight: 400;
            font-style: normal;
            font-weight: bold;
            font-size: 35px;
            color:rgb(2, 80, 159);
            margin: 18px;
            max-height: 32px;

        }
        .mobile{
            display: flex;
            justify-content: space-around; 
            font-weight: bold;
            margin: 50px;
            color: rgb(143, 16, 16);
        }
        .fot{
            display: flex;
            justify-content: center;
            align-items: center;
            color: rgb(0, 17, 17);
            

        }

</style>
<body>
    <header class="back">
        <img  src="logo.png" alt="City Logo" class="logo">      
    
        <p class="name" >Hotel S</p>
        <div class="menu-bar">
            <label for="menu" style="color: rgb(0, 0, 0); margin-right: 10px;">Navigate to:</label>
        </div>
    </header>
        <div class="menu">  
            <ul>
                
                <li><a href="index.html">Home</a></li>
                <li><a href="heritage.html">Heritage</a></li>
                <li><a href="hotel.html">Hotel Booking</a></li>
                <li><a href="gallery.html">Gallery</a></li>
            </ul>
        </div>
    
    <main>
        <h2 class="book">Hotels</h2>
        <section class="imag">
            
            <img src="book.png" alt="Heritage Site 1">
            
        </section>
        <p class="para">Hotel rooms typically have a bedroom and bathroom, and may also include amenities like a TV, Wi-Fi, and air conditioning. The layout and amenities can vary depending on the hotel's rating and location, and the type of room can also affect what's included:</p>
    </main>
    <div class="contact">
        <p>Contact Us</p>
        
    </div>
    <div class="mobile">
        <p>Mobile number : 7904399208</p>
        <p>Mail ID : tourismchennai@gmail.com</p>
    </div>
    <footer class="fot">
        <p>&copy; 2024 Mohan raj 64. All rights reserved.</p>
    </footer>
</body>
</html>

```
## Gallery
```c

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playwrite+CU:wght@100..400&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bodoni+Moda+SC:ital,opsz,wght@0,6..96,400..900;1,6..96,400..900&family=Ga+Maamli&family=Playwrite+CU:wght@300&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bodoni+Moda+SC:ital,opsz,wght@0,6..96,400..900;1,6..96,400..900&family=Bona+Nova+SC:ital,wght@0,400;0,700;1,400&family=Ga+Maamli&family=Playwrite+CU:wght@300&display=swap" rel="stylesheet">
    <title>City Tourism - Heritage</title>
</head>
<style>
    .back{
        
        background-image:  url(back3.png);
        background-repeat: no-repeat;
        background-attachment:local;
        background-size:cover;
        background-blend-mode: darken;
        border-radius: 90px;
        

    }
    .hertiage{
        display: flex;
        justify-content: center;
        align-items: auto;
        width: 50px;
        height: 50px;

    }
    .logo{   
       
       display: flex;
       justify-content: center; 
       align-items: center; 
       margin: auto;
       width: 75%;
       height: 175px; 
       
   }
    
    .column{
        float: left;
        width: 33%;
        padding: 5px;

    }
    .row::after{
        content: "";
        display: table;
        clear: both;
        
    }
    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
    
    main{
        max-width: 1200px;
        margin: auto;
        padding: 20px;
    }
    .shots{
        display: grid;
        grid-template-columns: repeat(auto-fill,minmax(200px,1fr));
        gap: 20px;
    }
    .shot{
        background-color:white;
        padding: 10px;
        border-radius: 10px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        transition: transform 0.3s, box-shadow 0.3s;
    }
    .shot:hover{
        transform: translateY(-5px);
        box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);;
    }
    .shot img{
       
        border-radius: 5px;
        width: 200px;
        height: 200px;
        
    }
    .shot-info{
        display: flex;
        justify-content: space-between;
        margin-top: 10px;
    }
    .herit{
        display: flex;
        justify-content: center;
        margin: 5%;
        font-family: "Ga Maamli", sans-serif;
        font-weight: 400;
        font-style: normal;
        font-size: xxx-large;
    }
    .menu{
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .menu li{
            display: inline-block;
            margin:  20px;
            font-size: x-large;
            color:blue;
            margin: 35px;
        }
        .menu ul{
            list-style: none;
            text-align: center;
            
        }
        .menu a{
            text-decoration: rgb(100, 0, 57);
            color: rgb(13, 14, 13);
            

            font-weight: 800;

        }
        .menu a:hover{

            background: #0cd1db;
            border-radius: 10px;
            width: 8000px;
            height: 8px;
        }
        .name{
            display: flex;
        justify-content: flex-start; 
        align-items: center ; 
        width: 100%;
        height: 155px; 
        font-size: 82px;
        
        margin: 13px;
        color:rgb(133, 14, 115);
        font-family: "Roboto Slab", serif;
        font-optical-sizing: auto;
        font-family: "Playwrite CU", cursive;
        font-optical-sizing: auto;
        font-weight: weight;
        font-style: normal;
        padding-right: 90px;
        }
        .fot{
    display: flex;
    justify-content: center;
    align-items: center;
    color: rgb(0, 17, 17);
    

   }
   .contact{
            display: flex;
            justify-content: center;
            font-family: "Bona Nova SC", serif;
            font-weight: 400;
            font-style: normal;
            font-weight: bold;
            font-size: 35px;
            color:rgb(2, 80, 159);
            margin: 18px;
            max-height: 32px;

        }
        .mobile{
            display: flex;
            justify-content: space-evenly;
            font-weight: bold;
            margin: 40px;
            color: rgb(129, 4, 4);
            font-size: x-large;
        }

</style>
<body>
    <header class="back">
        <img  src="logo.png" alt="City Logo" class="logo">      
    
        <p class="name" >Gallery!</p>
        
            <div class="menu">  
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="heritage.html">Heritage</a></li>
                    <li><a href="hotel.html">Hotel Booking</a></li>
                    <li><a href="gallery.html">Gallery</a></li>
                </ul>
            </div>
        
    </header>
    <main>
        <h2 class="herit"> Albums</h2>

        <section class="shots">
            
        
            
               <div class="shot">
                <img src="img1.png" alt="shot 1">
                <div class="shot-info">
                    <div></div>
                    <div></div>
                </div>
               </div>
               <div class="shot">
                <img src="img2.png" alt="shot 2">
                <div class="shot-info">
                    <div></div>
                    <div></div>
                </div>
               </div>
               <div class="shot">
                <img src="img3.png" alt="shot3">
                <div>
                    <div></div>
                    <div></div>
                </div>
               </div>
               <div class="shot">
                <img src="img4.png" alt="shot4">
                <div>
                    <div></div>
                    <div></div>
                </div>
               </div>
               <div class="shot">
                <img src="img5.png" alt="shot5">
                <div>
                    <div></div>
                    <div></div>
                </div>
               </div>
               <div class="shot">
                <img src="img6.png" alt="shot6">
                <div>
                    <div></div>
                    <div></div>
                </div>
               </div>
               <div class="shot">
                <img src="img7.png" alt="shot7">
                <div>
                    <div></div>
                    <div></div>
                </div>
               </div>
               <div class="shot">
                <img src="img8.png" alt="shot8">
                <div>
                    <div></div>
                    <div></div>
                </div>
               </div>
               <div class="shot">
                <img src="img9.png" alt="shot9">
                <div>
                    <div></div>
                    <div></div>
                </div>
               </div>
               <div class="shot">
                <img src="img10.png" alt="shot10">
                <div>
                    <div></div>
                    <div></div>
                </div>
               </div>
               
              </section>
                
       
    </main>
    <div class="contact">
        <p>Contact Us</p>
        
    </div>
    <div class="mobile">
        <p>Mobile number : 7904399208</p>
        <p>Mail ID : tourismchennai@gmail.com</p>
    </div>
    <footer class="fot">
        <p>&copy; 2024 Mohan raj 64. All rights reserved.</p>
    </footer>
</body>
</html>
```
# OUTPUT
## starting page:
![Screenshot 2024-07-17 082828](https://github.com/user-attachments/assets/e4fa5dda-6a81-4a78-b5de-e7103ee07106)

## Home page:
![Screenshot 2024-07-17 082845](https://github.com/user-attachments/assets/e8d4c14a-0eb3-48cd-b7f2-db8b3ef4fdcc)

## Heritage Page:
![Screenshot 2024-07-17 082901](https://github.com/user-attachments/assets/6e33b5f9-cf8f-4407-8d4f-0f8f9a62d0cb)

## Hotel Page:
![Screenshot 2024-07-17 082921](https://github.com/user-attachments/assets/69f94d29-1094-4bc0-b0cf-de2bc445958f)

## Gallery Page:

![Screenshot 2024-07-17 082933](https://github.com/user-attachments/assets/42f562ff-8b94-4bef-bccf-b7fb1cf96fb2)


# 1
## My day 
``` c
<!DOCTYPE html>
<html>
    <head>
        <title>My Day</title>
    </head>
    <body>
    <center>

    <table cellpadding= "10" cellspacing="10" style="border-style: double;">
        <tr>
            <th colspan="2" class="center" style="border-style: double;"><mark>My Day</mark></th>
        </tr>
        <tr>
            <td style="border-style: double;">
                <ol>
                    <li>wake up early
                    <ul>
                        <li style="list-style-type: square; margin-bottom: 20px">5AM</li>
                        <li>walk</li>
                        <li>jog</li>
                    </ul>
                    </li>
                </ol>
            </td>
            <td rowspan="3" style="border-style: double;">
    <table>
        <tr>
            <th colspan="2" class="center highlight" style="border-style: double;"><mark>Things to watch</mark></th>
                </tr>
        <tr >
            <td styl
            e="border-style: double;"><img src="f2.png" alt="image 1" width="100" height="100" >
            <td style="border-style: double;"><img src="f1.png" alt="image 2" width="100" height="100">
        </tr>
        <tr>
            <td style="border-style: double;"><img src="f3.png" alt="image 3" width="100" height="100">
            <td style="border-style: double;"><img src="f4.png" alt="image 4" width="100" height="100">
        </td>

        </tr>
        <tr>
        </tr>
    </table>
            <tr>
                <td style="border-style: double;">
                    <ol start="2">
                    <li>breakfast
                        <ul>
                        <li style="list-style-type: square; margin-bottom: 20px">8AM</li>
                    <li>eggs</li>
                    <li>coffee</li>
                    </ul>
                    </li>
                    </ol>
                </td>
            </tr>
            <tr>
                <td style="border-style: double;">
                    <ol start="3">
                    <li>go to Saveetha
                    <ul>
                    <li style="list-style-type: square; margin-bottom: 20px">8AM</li>
                    <li>attend classes</li>
                    <li>to be continued</li>
                    </ul>
                    </li>
                    </ol>
                </td>
            </tr>
    </table>
    </center>
</body>
</html>

```
# OUTPUT:
![Screenshot 2024-07-17 085737](https://github.com/user-attachments/assets/0e54fefd-260d-4fbb-85b2-dd30bd7c8e8c)





