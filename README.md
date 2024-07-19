# FSWDT10
DAY 10
<!DOCTYPE html>
<html>
    <head>
        <title> classes and Pseudo elements</title>
        <link rel="stylesheet" href="./day10.css"/>
        </head>
    <body>
        <!-- Pseudo classes -->
        <!-- <button>Click here &#128526</button> -->
        <!-- <br/>
        <br/>
        <a href="https://www.instagram.com">click here for instagram</a>
        <br/>
        <br/>
        <br/>

        <div>
            <span>hey guys</span>
            <span>hey guys</span>
            <span>hey guys</span>
            <span>hey guys</span>
            <span>hey guys</span>
            <span>hey guys</span>
            <span>hey guys</span>
            <span>hey guys</span>
            <span>hey guys</span>
            <span>hey guys</span>
            <span>hey guys</span>
            <span>hey guys</span>
            <span>hey guys</span>
            <span>hey guys</span>
            <span>hey guys</span>
        </div> -->
        <!-- Pseudo elements -->
        <!-- <h2>client</h2> -->
         <div class="shape"></div>
    </body>
</html>
/* hover */
/* pointing the cursor on the button */
/* button:hover{
    background-color: black;
    color: white;
    cursor: pointer;
}
/* active  */
/* It is used for selecting the buton by clicking on the left key of the mouse */
/* button:active{
    border: 2px solid red;
}
/* focus */
/* It is used to show that the particular button is being selected */
/* button:focus{
    background-color: blueviolet;
    color: white;
} */ 
/* un visited links */
/* a:link{
    color: red;
}
/* visited links */
/* a:visited{
    color: green;
}
span{
    background-color: yellow;
}
span:nth-child(3){
    background-color: blue ;
}
span:nth-child(even){
    background-color: blue ;
}
span:first-child{
    background-color: pink ;
}
span:last-child{
    background-color: green ;
} */ 
 /* h2::before{
    content: "hello ";
 }
 h2::after{
    content: " gd mrng ";
 } */
.shape{
    height: 100px;
    width: 100px;
    background-color: black;
    border-radius: 50px;
    margin-top: 100px;
    position: relative;
  }
  .shape::before{
    content: "";
    height: 80px;
    width: 80px;
    background-color: yellow;
    border-radius: 50px;
    margin-top: 100px;
    position: absolute;
  }
  .shape::after{
    content: "";
    height: 80px;
    width: 80px;
    background-color: yellow;
    border-radius: 50px;
    margin-bottom: 100px;
    position: absolute;
  }
