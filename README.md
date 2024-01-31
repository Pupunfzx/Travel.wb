<!DOCTYPE html>
<html lang="en">
<head>

    <style>
    

.main{
    
        background-position: center;
        background-size: cover;
        height: 10px;
        font-family: sans-serif;

}
body{
    background-color: rgb(155, 155, 244);
    width: 100%;
    height: 100%;
}
.navbar{
    width: 95%;
    height: auto;
    margin-left: 30px;
}
.logo{
   color: black;
   font-size: 40PX;
   font-family: cursive;
   float: left;
   padding-top: .6%;
   cursor: pointer;
}
.menu{
    width: 600px;
    float: left;
    height: 70px;
}
ul{
    float: left;
    display: flex;
    padding-top: 30px;
    justify-content: center;
    align-items: center;
    margin-left: 14%;
}
ul li{
    list-style: none;
    margin-left: 60px;
    font-size: 16px;
}
ul li a{
    text-decoration: none;
    color: black;
    font-family: Arial, Helvetica, sans-serif;
    font-weight: bold;
    transition: .5s ease;
    font-size: large;
}
ul li a:hover{
    color: red;
}
.search-box{
    float: right;
    width: 240px;
    background-color: black;
    height: 30px;
    padding: 8px;
    border-radius: 15px;
    margin-top: 1%;
    margin-right: 2%;
}
.search-box .search-text{
     width: 190px;
     padding: 0 6px;
}
.search-btn{
    text-decoration: none;
    background-color: white;
    color: #000;
    display: flex;
    float: right;
    justify-content: center;
    align-items: center;
    width: 30px;
    height: 30px;
}
.title{
    position: absolute;
    top: 40%;
    left: 50%;
    transform: translate(-50%,-50%); 
}
.title h1{
    cursor: pointer;
    font-family: cursive;
    color: red;
    font-size: 85px;
}
.button{
    position: absolute;
    top: 51%;
    left: 50%;
    transform: translate(-50%,-50%);
}
.btn{
    color: white;
    padding: 5px 20px;
    font-size: 18px;
    text-decoration: none;
    border: 1px solid red;
    transition: .3s ease;
}
.btn:hover{
    background-color: red;
    color: white;
}


    </style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PUPUN</title>
    <link ref="stylesheet" href="style4.css">
</head>
<body>    

     <div class="main">
     </div class="navbar">
      <h2 class="logo">TRAVELERS.COM</h2>
     </div>
     <div class="menu">
        <ul>
           <li><a href="#">HOME</a></li>
           <li><a href="#">ABOUT</a></li>
           <li><a href="#">CONTACT</a></li>
           <li><a href="#">EVENT</a></li>
           <li><a href="#">HELP</a></li>
        </ul>
    </div>
       <div class="search-box">
          <input class="search-text" type="text" placeholder="Type to seach">
           <a class="search-btn" href="#"><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB4AAAAeCAYAAAA7MK6iAAAAAXNSR0IArs4c6QAAAXZJREFUSEvtltFRAzEMRDedQCVAJ1AJUAlQSaASoBKYx5xgx7mz5ORu8oN+YG5sP+1asrLTmWJ3Jq6q4AtJ11OSH5JeT004Az9Iul+AkMDdsUksgVH3JAmlWTxKIsGhmAMD3dsp2Po2KUNl2O5OsOZmhDwHfjelPTUkcGtXMaS8BWMvhxEoyIoIOHtwCTfYw980WnCoHbEOOPuIsuoW/DUdQLU+p2n/LaAmUF1O2MFYjG3EZdWyaX2AsZm9aTjYezbr7/Zgr43SXl/kbVQpLIcP14aDjyqSiR61QV1QH2m0tvhdVVvDr6jsVAt2uysVOrr+14m5QnAFvUHQDpCyWuhz4PYpZF2Mwk9JVzYi/S6535fCa/ezp1f6vZEYQK6DYopnk+/xrft0Zj0XkwiV/B9jEmUcHK+bd0Q41C3ODJy2hS2IjohP3aGxJhjVwP3HwyJ8TTBKy/C1wWX4FuA5+MGY3QrscH4cHMz2LcHdjvgHjzwYJ639BjaeWx8CyAVqAAAAAElFTkSuQmCC"/></a>
       </div>
         <div class="title">
           <h1>TRAVEL</h1>

         </div>
         <div class="button">
         <a href="#" class="btn">WATCH LOCATION</a>
         <a href="#" class="btn">WATCH LOCATION</a>
         </div>
    
    
        
</body>
</html>
