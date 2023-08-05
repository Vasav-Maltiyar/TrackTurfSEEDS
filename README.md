<html><head>
    <style>
        body {
            font-family: "Poppins", sans-serif;
            background-image: url('farm2.jpg');
        }
        
        .header {
            position: fixed;
            top: 0;
            left: 0;
            width: 90%;
            padding: 20px 100px;
            background: seagreen;
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 100;
        }
        
        .logo {
            font-size: 32px;
            color: #fff;
            text-decoration: none;
            font-weight: 700;
        }
        
        .navigation-bar a {
            position: relative;
            font-size: 18px;
            color: #fff;
            text-decoration: none;
            font-weight: 500;
            margin-right: 20px;
        }
        
        .navigation-bar a::before {
            content: '';
            position: absolute;
            top: 100%;
            left: 0;
            width: 0;
            height: 2px;
            background: #fff;
            transition: width 0.3s;
        }

        .navigation-bar a:hover::before {
            width: 100%;
        }
    </style>
</head>
<body>
    <header class="header">
        <a href="#" class="logo">Logo</a>
        <nav class="navigation-bar">
            <a href="homepage.html">Home</a>
            <a href="trackturfloginpage.html">Login</a>
            <a href="file:///C:/Users/Admin/Desktop/Vasav%20social%20folder/Crops.html">Soil Report</a>
            <a href="ourteam.html">Our Team</a>
            <a href="contact.html">Contact Us</a>
        </nav>
    </header>


</body></html>
# TrackTurfSEEDS
