# rooms-2-.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rooms Information</title>
    <style>
        *{
            box-sizing: border-box;
        }
        .column{
            float:left;
            width:33.33%;
            padding:5px;
        }
        .row::after{
            content: "";
            clear: both;
            display: table;
        }
        
        body{
            background-color: yellowgreen;
            color:chocolate;
        }
        nav{
            background-color:indianred;
            color:oldlace;
            padding: 10px;
            margin:20px;
            text-align: center;
        }
        a{
            width:100px;
            height:50px;
            background-color: royalblue;
            color:green;
        }
        a:hover{
            background-color:tomato;
        }
        h1{
            color:firebrick;
        }
        h2{
            color:chocolate;
        }
        
    </style>
</head>
<body>
    <header>
        <nav>
            <a href="home.html">Home</a>
            <a href="rooms.html">Rooms/Suit</a>
            <a href="Facilities.html">Facilities</a>
            <a href="Enquire.html">Enquiry</a>
        </nav>
    </header>
    <h1>Ooty Heritage Resort</h1>
    <h2 style="text-decoration: underline;">Rooms/Suits</h2>
    
    <div class="row">
        <div class="column">
            <img src="C:\Users\Frys electronics\Desktop\rooms.jpg" alt="Image of resort" style="width:50%">
        </div>
       
        <div class="column">
            <img src="C:\Users\Frys electronics\Desktop\rooms2.jpg" alt="Image of resort" style="width:50%">
        </div>
        <div class="column">
            <img src="C:\Users\Frys electronics\Desktop\rooms3.jpg" alt="Image of resort" style="width:50%">
        </div>
        
    </div>
    <h3>AC Room</h3>
    <p>
        The resort’s Superior Room can comfortably accommodate three people. The rooms have cosy beds, a TV,a sofa cum bed unit, kitchenette, microwave oven, a coffee and tea maker. There are no AC rooms since it is cool<br/>
        even in summer but room heaters are available during winter.
    </p>
    <h3>Non AC ROOM</h3>
    <p>
        The resort’s NON-AC Room can comfortably accommodate two people. The rooms have cosy beds, a TV,a sofa cum bed unit, a coffee and tea maker. There are no AC rooms since it is cool<br/>
        even in summer but room heaters are available during winter.
    </p>

</body>
</html>
