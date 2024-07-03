## contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color: black;
        font-size: 30px;
        font-family:'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
        background-color: rgb(14, 155, 243);
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color: rgb(14, 155, 243)white;        
        }
        .navbar a{
         color:rgb(0, 0, 0);
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color: rgb(14, 155, 243);
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:black;
        font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        font-size:55px;
        background-color:white;
        }
        footer{

        background-color:black;
        height:30px;
        bottom:0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        header
        {
        background-color:white;
        height:10vh;
        width:100%;
        color:rgb(14, 155, 243);
        }
        header h2{
        position:absolute;
        color:black;
        margin-top:10px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color:  rgb(14, 155, 243);
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color:silver;
        }
        .small
        {
           width:190px;
           height:190px;
           margin:10px
        }
        .border{
        border-width:2px;
        border-color:black;
        border-style:solid;
        border-radius:50%;
        }
        .cirpic{
            position:absolute;
            top:35%;
            margin-left: 70px;
            
        }
        .text{
            position:absolute;
            top:55%;
            margin-left:35px;
            font-size:20px;
            
        }
        .text2{
            position:absolute;
            top:60%;
            margin-left:58px;
            font-size:20px;
        }
        .class{
            text-align: center;
            font-size: larger;
        }
    
    </style>
</head>
<body>
    <header>
        <h2>Ajay45</h2>
        </header>
        <nav class="navbar">
        
        <ul>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="products.html">Products</a></li>
        <li><a href="people.html">People</a></li>
        <li><a href="exstayre.html">Home</a></li>
        </ul>
        </nav>
        <div class="search"><input type="text" placeholder="Enter to Search">
            <button>Search</button></div>
        <div class="cirpic">
            <img class="small border" src="assets/images/img11.jpg" width="500px">
            <img class="small border" src="assets/images/img12.jpeg" width="500px" >
            <img class="small border" src="assets/images/img13.jpeg" width="500px">
            <img class="small border" src="assets/images/img14.webp" width="500px">
            <img class="small border" src="assets/images/img15.jpeg" width="500px">
            
            
        </div>
        <div class ="text">
            <table cellpadding="70">
                <tr class="head">
                    <th>JOHN PETER</th>
                    <th>RDJ</th>
                    <th>TOM</th>
                    <th>ELIZEBETH</th>
                    <th>ISAAC</th>
                </tr>
            </table>
        </div>
        <div class="text2">
            <table cellpadding="68">
                <tr>
                    <td>FOUNDER</td>
                    <td>CO-FOUNDER</td>
                    <td>CEO</td>
                    <td>DIRECTOR</td>
                    <td>MANAGER</td>
                    
                </tr>
            </table>
        </div>
      
            <footer class="class">
                Designed and Developed by Ajay
                </footer>
               
</body>
</html>
```
## home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Myfirstwebsite</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <style>
        h1 {
            color: black;
            font-size: 45px;
            font-family: 'Times New Roman', Times, serif;
            position: absolute;
            top: 35%;
        }

        body {
            background-color:  rgb(14, 155, 243);
            margin: 0;
           
}
        

        .navbar ul {
            list-style-type: none;
            background-color: rgb(255, 255, 255);

        }

        .navbar a {
            color: rgb(0, 0, 0);
            text-decoration: none;
            padding: 25px;
            display: flex;
            text-align: left;
            position: relative;
            font-size: 20px;
            top: -95px;

        }

        .navbar a:hover {
            background-color:powderblue;
            size: 60px;
            cursor: pointer;
        }

        .navbar li {
            float: right;
        }

        h2 {
            color: black;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-size: 55px;
            background-color: white;
            margin-left: 10px;
            
        }

        footer {

            background-color: black;
            height: 30px;
            bottom: 0;
            width: 100%;
            color: white;
            position: absolute;

        }

        header {
            background-color: white;
            height: 10vh;
            width: 100%;
            color: white;
        }

        header h2 {
            position: absolute;
            color: black;
            margin-top: 10px;
            margin-left: 10px;
        }

        .first,
        .second,
        .third {
            font-size: 50px;
            margin-left: 2px;
        }

        .second {
            color: rgb(49, 5, 160);
            text-align: center;
        }

        .third {
            text-align: center;
        }
        .first{
            margin-left:5px;
        }
        .search input,
        button {
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color: rgb(49, 5, 160);
        }

        .d {
            position: absolute;
            top: 65%;
            font-size: 20px;
        }

        .search input {
            width: 18%;
            height: 30px;

        }

        .search button,
        .d button {
            color: white;
            background-color:rgb(14, 155, 243);
            padding: 5px;
            text-align: center;
        }

        .d button {

            margin-right: 500px;
            padding: 20px 30px 20px 30px;
            border-radius: 30px;
            border-color: none;
        }

        #joinus:hover {
            cursor: pointer;
            color: rgb(5, 20, 15);
            background-color:wheat;
        }

        .login form {
            position: absolute;
            right: 100px;
            top: 30%;
            margin: 20px;
            box-sizing: border-box;
            border-color: rgb(105, 62, 7);
            background-color:rgba(0, 0, 0, 0.781);
            padding: 80px 80px 200px 80px;
        }

        .login form button {
            background-color:rgb(14, 155, 243);
            margin-right: 50px;
            color: white;
            padding: 10px 35px 10px 35px;
            font-size: 15px;
            border-radius: 15%;
            width: 60%;
        }

        .login form h3 {
            color: rgb(13, 12, 12);
            position: absolute;
            top: 0%;
            padding: 5px 30px 5px 30px;
            background-color: rgb(133, 155, 155);
            text-align: center;
            margin-left: 18px;


        }

        .login form input {
            height: 35px;
            border: none;
            border-bottom: 2px solid lightblue;
            font-family: Arial, Helvetica, sans-serif;
            color: white;
            font-size: 15px;
            background: transparent;
        }

        .login ::placeholder {
            color: white;
            opacity: 1;
        }

        .login form h4 {
            position: absolute;
            top: 55%;
            color: white;
            margin-left: 25px;
        }

        .login form .Signup {
            position: absolute;
            top: 70%;
            color: white;
            margin-left: 35px;
        }

        .login form .Signup b a {
            text-decoration: none;
            color: lightblue;
            margin-left: 20px;
        }

        .login form h5 {
            position: absolute;
            top: 73%;
            color: white;
            margin-left: 65px;
        }

        .login form .image {
            position: absolute;
            top: 85%;
            margin-left: 40px;

        }

        .d p {
            font-family: Georgia, 'Times New Roman', Times, serif;
        }
        .t{
            text-align: center;
            font-size: larger;
        }
        .d{
            margin-left: 10px;
            color:rgb(210, 30, 42);
        }

    </style>
</head>

<body>
    <header>
        <h2>Ajay45</h2>
    </header>
    <nav class="navbar" >

        <ul>
            <li><a href="contact.html">Contact</a></li>
            <li><a href="products.html">Products</a></li>
            <li><a href="people.html">People</a></li>
            <li><a href="exstayre.html">Home</a></li>
        </ul>
    </nav>
    <div class="search"><input type="text" placeholder="Enter to Search">
        <button>Search</button>
    </div>
    <h1 align="top">
        <div class="first">Learn to Code!!
            </div>
        <div class="second">Connecting Coders, Building Better Tomorrow.</div>
    </h1>
    <div class="d">
        <p> &nbsp;The zenith of coding websites lies not only in the lines of code but in the vibrant tapestry of a community<br>&nbsp;passionately innovating and evolving.</p>
        <button id="joinus">Join Us</button>
    </div>
    <div class="login">
        <form>
            <h3>Login Here</h3>
            <input type="text" placeholder="Username or Email"><br><br>
            <input type="password" placeholder="Password"><br><br><br>
            <button>Login</button>
            
            <div class="Signup"><b><a href="">Sign up</a></b> here</div>
            <h5>Login with</h5>
            <div class="image">
                <a href="" style="padding-right: 25px; color: aliceblue;"><i class="bi bi-google"></i></a>
                <a href="" style="padding-right: 25px; color: aliceblue;"><i class="bi bi-facebook"></i></a>
                <a href="" style="padding-right: 20px; color: aliceblue;"><i class="bi bi-twitter"></i></a>
            </div>
            
        </form>
    </div>
    <footer class="t">
        Designed and Developed by Ajay
    </footer>

</body>
</html>
```
## people.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color: black;
        font-size: 30px;
        font-family:'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
        background-color: rgb(14, 155, 243);
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color: rgb(14, 155, 243)white;        
        }
        .navbar a{
         color:rgb(0, 0, 0);
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color: rgb(14, 155, 243);
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:black;
        font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        font-size:55px;
        background-color:white;
        }
        footer{

        background-color:black;
        height:30px;
        bottom:0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        header
        {
        background-color:white;
        height:10vh;
        width:100%;
        color:rgb(14, 155, 243);
        }
        header h2{
        position:absolute;
        color:black;
        margin-top:10px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color:  rgb(14, 155, 243);
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color:silver;
        }
        .small
        {
           width:190px;
           height:190px;
           margin:10px
        }
        .border{
        border-width:2px;
        border-color:black;
        border-style:solid;
        border-radius:50%;
        }
        .cirpic{
            position:absolute;
            top:35%;
            margin-left: 70px;
            
        }
        .text{
            position:absolute;
            top:55%;
            margin-left:35px;
            font-size:20px;
            
        }
        .text2{
            position:absolute;
            top:60%;
            margin-left:58px;
            font-size:20px;
        }
        .class{
            text-align: center;
            font-size: larger;
        }
    
    </style>
</head>
<body>
    <header>
        <h2>Ajay45</h2>
        </header>
        <nav class="navbar">
        
        <ul>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="products.html">Products</a></li>
        <li><a href="people.html">People</a></li>
        <li><a href="exstayre.html">Home</a></li>
        </ul>
        </nav>
        <div class="search"><input type="text" placeholder="Enter to Search">
            <button>Search</button></div>
        <div class="cirpic">
            <img class="small border" src="assets/images/img11.jpg" width="500px">
            <img class="small border" src="assets/images/img12.jpeg" width="500px" >
            <img class="small border" src="assets/images/img13.jpeg" width="500px">
            <img class="small border" src="assets/images/img14.webp" width="500px">
            <img class="small border" src="assets/images/img15.jpeg" width="500px">
            
            
        </div>
        <div class ="text">
            <table cellpadding="70">
                <tr class="head">
                    <th>JOHN PETER</th>
                    <th>RDJ</th>
                    <th>TOM</th>
                    <th>ELIZEBETH</th>
                    <th>ISAAC</th>
                </tr>
            </table>
        </div>
        <div class="text2">
            <table cellpadding="68">
                <tr>
                    <td>FOUNDER</td>
                    <td>CO-FOUNDER</td>
                    <td>CEO</td>
                    <td>DIRECTOR</td>
                    <td>MANAGER</td>
                    
                </tr>
            </table>
        </div>
      
            <footer class="class">
                Designed and Developed by Ajay
                </footer>
               
</body>
</html>
```
## product.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color: black;
        font-size: 45px;
        font-family:'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
        background-color:rgb(14, 155, 243);
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color:whitesmoke;
        
        }
        .navbar a{
         color:black;
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:rgb(14, 155, 243);
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:black;
        font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        font-size:55px;
        background-color:white;
        }
        footer{
        background-color:black;
        height:30px;
        bottom: 0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        header
        {
        background-color:white;
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:black;
        margin-top:10px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: rgb(14, 155, 243);
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color:silver;
        }
        .contain{
                position: absolute;
                top:12%;
                width:1240px;
                height:750px;
                margin-left: 90px;
               margin-top: 28px;
                background-color:rgb(14, 155, 243);
                font-size: larger;
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                
                
                }
                .contain p b{
                    font-size: 30px;
                    padding-left: 45px;
                }
                .contain p{
                    font-size: 18px;
                    padding-left: 10px;
                    padding:5px 20px 0px 15px ;
                    
                }
                .contain img{
                   margin-top: 10px;
                   padding-left: 10px;
                   padding:20px 20px 0px 20px;
                }
                .m{
                    text-align: center;
                    font-size: large;
                }

    </style>
</head>
<body>
    <header>
        <h2>Ajay45</h2>
        </header>
        <nav class="navbar">
        
        <ul>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="products.html">Products</a></li>
        <li><a href="people.html">People</a></li>
        <li><a href="exstayre.html">Home</a></li>
        </ul>
        </nav>
        <div class="search"><input type="text" placeholder="Enter to Search">
            <button>Search</button></div>
            <div class="contain">
                <table >
                    <tr>
                        <td><img src="assets/images/img1.avif" height="200px" width="200px">
                            <p><b>WEBDESIGN&nbsp;</b><br>
                                
                               
                
                        </p></td>
                        <td><img src="assets/images/img2.png" height="200px" width="200px"><br>
                            <p><b>JAVASCRIPT&nbsp;</b><br>
                                
                                
                        </p></td>
                        <td><img src="assets/images/img3.png" height="200px" width="200px"><br>
                            <p><b>PYTHON <br>
                        
                        </p></td>
                        <td><img src="assets/images/img4.png" height="200px" width="200px"><br>
                            <p><b>JAVA</b><br>
                               
                                
                        </p></td>
                        <td><img src="assets/images/img5.png" height="200px" width="200px"><br>
                            <p><b>C/C++</b><br>
                                
                                
                        </p></td>  
                    </tr>
                    <tr>
                        
                        </p></td>  

                    </tr>
                </table>
            </div>
            <footer class="m">
                Designed and Developed by Ajay
                </footer>
               
</body>
</html>
```
## output
![image](https://github.com/ajay45d/css/assets/134574325/58f0dcbe-c655-4f36-9847-311b3d0090e6)
![image](https://github.com/ajay45d/css/assets/134574325/8fd6b390-ef00-4ee4-9f6a-9d10bb21cc55)
![image](https://github.com/ajay45d/css/assets/134574325/ba48883d-bf72-4bdb-b6a3-d232a7744ca5)
![image](https://github.com/ajay45d/css/assets/134574325/a78ee2f1-6149-4712-93d2-579c26391aa7)



