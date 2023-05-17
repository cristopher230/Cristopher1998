
<head>
    
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WakuWaku</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Sofia">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: rgb(224 231 255);
        }
        .logo {
            font-size:20px;
            margin-right:63%;
            font-weight: bold;
        }
        .h-logo {
            margin-right:20%;
        }
        
        aside {
            height: 100%;
            width: 200px;
            position: fixed;
            background-color: white;
            top: 0;
            left: 0;
            padding: 1rem;

        }
        .sidenav a {
            padding: 8px 8px 8px 32px;
            text-decoration: none;
            font-size: 18px;
            color: black;
            display: flex;
            align-items:center;
            margin-left:1%;
        }
        .sidenav a:hover {
            color: #f1f1f1;
            border-radius: 1rem;
            background-color:blue;
        }

        header {
  display: flex;
  justify-content: flex-end;
  align-items: center;
  height: 60px;
}

.notification {
  font-size: 1.125rem; /* 18px */
  line-height: 1.75rem; /* 28px */
  position: relative;
  padding: 0.3em 0.6em;
  border-radius: 9999px;
  margin-right: 20px;
  background-color: whitesmoke; /* add some margin to separate the notification from other elements */
}
.notification:hover {
  cursor: pointer; /* change the cursor to a pointer on hover */
  background-color: #153ef3;
  color: white;/* add a light gray background color */
}

/* Make badge responsive */
.badge {
  border-radius: 9999px;
  margin-right: 20px;
  position: relative;
  font-size: 1.125rem; /* 18px */
  line-height: 1.75rem; /* 28px */
  padding: 0.3em 0.7em;
  background-color: #153ef3;
  color: white;
  font-family: sans-serif;
  font-style: italic;
}


@media screen and (max-width: 768px) {
  .badge {
    font-size: 1.2em;
    padding: 0.15em 0.4em;
  }
}
main {
  background-color: white;
  height:620px; 
  padding:10px;
  margin-left: 15%;
  max-width: -400px; /* 448px */
  margin-right:2%;
  margin-top:0px;/* adjust to desired height */

}
.container h1 {
    color: black;
    font-size: 25px;
    font-weight: bold;
    margin-left: 1%;
}
.row0 {
    background-color: white;
    border-color: black;
    height:0; 
    border: 1px solid rgb(203 213 225);

  padding:0;
  margin-left: 2%;
  max-width: -400px; /* 448px */
  margin-right:2%;
  margin-top: 10px;
}
.row1 {
    background-color: white;
    border-color: black;
    height:510px; 
    border: 1px solid rgb(203 213 225);
    

  padding:10px;
  margin-left: 2%;
  max-width: -400px; /* 448px */
  margin-right:68%;
  margin-top: 25px;/* adjust to desired height */

}

    .row1 h1 {
    color: black;
    border-color: rgb(203 213 225);
    font-size: 25px;
    font-weight: bold;
    border-radius:100%;
}
.row1 h2 {
    background-color: #153ef3;
   border: 1px solid rgb(203 213 225);
    height:37 px; 
  padding:10px;
  margin-left:40%;
  max-width: -400px; /* 448px */
  margin-right:70%;
  margin-top:28px;
}
.row1 h2 {
    color: white;
    border-color: rgb(203 213 225);
    font-size: 15px;
    font-weight: bold;
    margin-left:15px;
}
.row1 h3 {
    background-color:white;
   border: 1px solid rgb(203 213 225);
    height:37 px; 
  padding:10px;
  margin-left:50%;
  max-width: -400px; /* 448px */
  margin-right:3%;
  margin-top:-44px;
}
.row1 h3 {
    color: black;
    border-color: rgb(203 213 225);
    font-size: 15px;
    font-weight: bold;
    margin-left:65%;
}
.row1 h4 {
    font-weight: bold;
    margin-top:8%;
}
.column {
    background-color: white;
    border-color: rgb(203 213 225);
    height:300px; 
    border: 1px solid rgb(203 213 225);
    
  padding:10px;
  margin-left: 4%;
  max-width: -400px; /* 448px */
  margin-right:4%;
  margin-top: 20px;/* adjust to desired height */

}
.column h5{
    border-radius: 50%;
    font-size:21px;
    display: flex;
    margin-left:7%;
    margin-top:5px;
    border-radius: 0.125rem; /* 2px */
    
    
    
}

.row2 {
    background-color:white;
    border-color: black;
     border: 1px solid rgb(203 213 225);
    height:510px; 
  padding:10px;
  margin-left:34%;
  max-width: -600px; /* 448px */
  margin-right:35%;
  margin-top:-510px;
}
.row2 h1 {
    color: black;
    border-color: rgb(203 213 225);
    font-size: 25px;
    font-weight: bold;
}
.row2 h2 {
    background-color: #153ef3;
   border: 1px solid rgb(203 213 225);
    height:37 px; 
  padding:10px;
  margin-left:40%;
  max-width: -400px; /* 448px */
  margin-right:70%;
  margin-top:28px;
}
.row2 h2 {
    color: white;
    border-color: rgb(203 213 225);
    font-size: 15px;
    font-weight: bold;
    margin-left:15px;
}
.row2 h3 {
    background-color:white;
   border: 1px solid rgb(203 213 225);
    height:37 px; 
  padding:10px;
  margin-left:50%;
  max-width: -400px; /* 448px */
  margin-right:4%;
  margin-top:-44px;
}
.row2 h3 {
    color: black;
    border-color: rgb(203 213 225);
    font-size: 15px;
    font-weight: bold;
    margin-left:65%;
}
.row2 h4 {
    font-weight: bold;
    margin-top:8%;
}


.row3 {
    background-color:white;
   border: 1px solid rgb(203 213 225);
    height:510px; 
  padding:10px;
  margin-left:67%;
  max-width: -600px; /* 448px */
  margin-right:2%;
  margin-top:-510px;
}
.row3 h1 {
    color: black;
    border-color: rgb(203 213 225);
    font-size: 25px;
    font-weight: bold;
}
.row3 h2 {
    background-color: #153ef3;
   border: 1px solid rgb(203 213 225);
    height:37 px; 
  padding:10px;
  margin-left:40%;
  max-width: -400px; /* 448px */
  margin-right:70%;
  margin-top:28px;
}
.row3 h2 {
    color: white;
    border-color: rgb(203 213 225);
    font-size: 15px;
    font-weight: bold;
    margin-left:15px;
}
.row3 h3 {
    background-color:white;
   border: 1px solid rgb(203 213 225);
    height:37 px; 
  padding:10px;
  margin-left:50%;
  max-width: -400px; /* 448px */
  margin-right:4%;
  margin-top:-44px;
}
.row3 h3 {
    color: black;
    border-color: rgb(203 213 225);
    font-size: 15px;
    font-weight: bold;
    margin-left:65%;
}
.row3 h4 {
    font-weight: bold;
    margin-top:8%;
}


</style>
            


<div>
<aside >
    <!-- Add sidenav -->
    <div class="sidenav">
        <img src="/src/assets\image/logo.png"><br>
        <a href="#"><i class="fas fa-home"></i> Dashboard</a>
        <a href="#"><i class=" fa fa-file"></i> Forms</a>
        <a href="#"><i class="fa fa-chart-pie"></i>Respondents</a>
    </div>
</aside>
</div>


<body>
    <header>
        <span style="height: 30px; width: 30px; margin:5px;">
            <img src="/src/assets\image/university.png">
        </span>
        <h1 class="logo">University of Tokyo </h1>
        <span class="notification">
            <i class="far fa-bell"></i>
            </span>
            <span class="badge">Y</span>
    </header>
    <main>
        <div class="container">
        <h1>Repondents</h1>
        
        
        </div>
        <div class="border-box"></div>
        <div class="row0">

        </div>
       <div class="row1">
            <h1>Untitled Form</h1>
            <h2>reponses</h2>
            <h3>nonresponses</h3>
            <h4 style="text-align: center;">26 responses</h4>
            <div class="column">
                <h5 ><span style="height:30px; width: 30px;margin: 5px; border-radius:100%; clip-path:circle();">
                    <img src="/src/assets\image/ai.jpg">
                </span> Ai Fujikura</h5>
                <h5><span style="height: 30px; width: 30px; margin:5px;">
                    <img src="/src/assets\image/asahi.png">
                </span>Asahi Bessho</h5>
                <h5><span style="height: 30px; width: 30px; margin:5px; clip-path:circle();">
                    <img src="/src/assets\image/chiyo.jpg">
                </span>Chiyo Hada</h5>
                <h5><span style="height: 30px; width: 30px; margin:5px;">
                    <img src="/src/assets\image/daiki.jpg">
                </span>Daiki Sato</h5>
                <h5><span style="height: 30px; width: 30px; margin:5px; clip-path:circle();">
                    <img src="/src/assets\image/emiko.png">
                </span>Emiko Takahashi</h5>
                <h5><span style="height: 30px; width: 30px; margin:5px; clip-path:circle();">
                    <img src="/src/assets\image/hana.jpg">
                </span>Hana Nakamura</h5>

            </div>
        </div >
        <div class="border-box">
        <div class="row2">
            <h1>Untitled Form</h1>
            <h2>reponses</h2>
            <h3>nonresponses</h3>
            <h4 style="text-align: center;">26 responses</h4>
            <div class="column">
                <h5 ><span style="height:30px; width: 30px;margin: 5px; clip-path:circle();">
                    <img src="/src/assets\image/ai.jpg">
                </span> Ai Fujikura</h5>
                <h5><span style="height: 30px; width: 30px; margin:5px;">
                    <img src="/src/assets\image/asahi.png">
                </span>Asahi Bessho</h5>
                <h5><span style="height: 30px; width: 30px; margin:5px;clip-path:circle();">
                    <img src="/src/assets\image/chiyo.jpg">
                </span>Chiyo Hada</h5>
                <h5><span style="height: 30px; width: 30px; margin:5px;">
                    <img src="/src/assets\image/daiki.jpg">
                </span>Daiki Sato</h5>
                <h5><span style="height: 30px; width: 30px; margin:5px; clip-path:circle();">
                    <img src="/src/assets\image/emiko.png">
                </span>Emiko Takahashi</h5>
                <h5><span style="height: 30px; width: 30px; margin:5px; clip-path:circle();">
                    <img src="/src/assets\image/hana.jpg">
                </span>Hana Nakamura</h5>

            </div>
        </div >
        <div class="container">
        <div class="row3">
            <h1>Untitled Form</h1>
            <h2>reponses</h2>
            <h3>nonresponses</h3>
            <h4 style="text-align: center;">26 responses</h4>
            <div class="column">
                <h5 ><span style="height:30px; width: 30px;margin: 5px; clip-path:circle();">
                    <img src="/src/assets\image/ai.jpg">
                </span> Ai Fujikura</h5>
                <h5><span style="height: 30px; width: 30px; margin:5px;">
                    <img src="/src/assets\image/asahi.png">
                </span>Asahi Bessho</h5>
                <h5><span style="height: 30px; width: 30px; margin:5px; clip-path:circle();">
                    <img src="/src/assets\image/chiyo.jpg">
                </span>Chiyo Hada</h5>
                <h5><span style="height: 30px; width: 30px; margin:5px;">
                    <img src="/src/assets\image/daiki.jpg">
                </span>Daiki Sato</h5>
                <h5><span style="height: 30px; width: 30px; margin:5px; clip-path:circle();">
                    <img src="/src/assets\image/emiko.png">
                </span>Emiko Takahashi</h5>
                <h5><span style="height: 30px; width: 30px; margin:5px; clip-path:circle();">
                    <img src="/src/assets\image/hana.jpg">
                </span>Hana Nakamura</h5>

            </div>
        </div >

    
    </div> 
    </div>
        
    </main>
    </body>

