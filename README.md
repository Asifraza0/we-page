# we-page
this is my first repository on git
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>3DWeb</title>
   
    
 <style>
 *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: gilroy;
}

html,body{
    height: 100%;
    width: 100%;
}

#main{
    position: relative;
    overflow: hidden;

}
 
#page{
    position: relative;
    height: 100vh;
    width: 100vw;
    background-color: rgb(14, 13, 13);
}
#page1{
    position: relative;
    height: 100vh;
    width: 100vw;
    background-color: rgb(14, 13, 13);
}
#page2{
    position: relative;
    height: 100vh;
    width: 100vw;
    background-color: rgb(14, 13, 13);
}
#page3{
    position: relative;
    height: 100vh;
    width: 100vw;
    background-color: rgb(14, 13, 13);
}

#canvas{
    position: relative;
    z-index: 9;
    max-width: 100vw;
    max-height: 100vh;
}
#loop{
    display: flex;
    position: absolute;
    top: 30%;
    height: 25%;
    width: 100%;
    background-color: rgb(14, 13, 13);
    white-space: nowrap;
    font-size: 80px;
    font-weight: 500%;
    
}
#loop>h1{
    font-weight: 400;
    animation-name: anim;
    animation-duration: 12s;
    animation-timing-function: linear;
    animation-iteration-count: infinite;
    color: rgb(248, 10, 101);

}
#loop>h1>span{
    -webkit-text-stroke: 1.2px rgb(248, 10, 101);
    color:transparent;
    border-radius: 10%;
    
}
@keyframes anim{
    0%{
        transform: translateX(0%);
    }
    100%{
transform: translateX(-100%);
    }
}
#nav{
    display: flex;
    height: 7%;
    width: 100%;
    background-color: transparent;
    position: fixed;
    z-index: 98;
    padding: 5px 40px;
}
#nav>h3{
    -webkit-text-stroke: 1.2px rgb(248, 10, 101);
    font-weight: 400;
    font-size: 40px;
    color: transparent;
    border-radius: 10%;

}
#page>h1{
    position: absolute;
    top: 58%;
    font: 400;
    color: rgb(248, 10, 101);
    left: 5%;
     /* font-size: 30px; */

} 
#page>h3{
    position: absolute;
    top: 58%;
    font-weight: 400;
    color: rgb(248, 10, 101);
    left: 25%;
    font-size: 30px;
}
#page>h2{
    
    position: absolute;
    top: 15%;
    color: rgb(248, 10, 101);
    left: 36%;
    font-size: 30px;

}

</style>
    
</head>
<body>
    <div id="nav">
        <h3>#RESUME</h3>

        
    </div>
    
    

 <div id="mian"></div>
 
    <div id="page">
        <div id="loop">
            <h1><B>THIS</B> <span>IS</span> <B><I>MY</I></B> <span>RESUME! ,</span></h1>
            <h1><B>THIS</B> <span>IS</span> <B><I>MY</I></B> <span>RESUME! ,</span></h1>
            <h1><B>THIS</B> <span>IS</span> <B><I>MY</I></B> <span>RESUME! ,</span></h1>
            <h1><B>THIS</B> <span>IS</span> <B><I>MY</I></B> <span>RESUME! ,</span></h1>
            
           
        </div>
        <h1>OBJECTIVE</h1>
        <h3>Seeking my entry-level opportunity with an esteemed organization <br>
            where i can utilise my skills and enhance learning in<br>
             the field work.</h3>
             <h2>Asif Raza <br>+918081998373 <br>asifraja60715@gmail.com</h2>
        <canvas></canvas>
    </div>
    <div id="page1">
        <div id="loop">
            <h1><B>THIS</B> <span>IS</span> <B><I>MY</I></B> <span>RESUME! ,</span></h1>
            <h1><B>THIS</B> <span>IS</span> <B><I>MY</I></B> <span>RESUME! ,</span></h1>
            <h1><B>THIS</B> <span>IS</span> <B><I>MY</I></B> <span>RESUME! ,</span></h1>
            <h1><B>THIS</B> <span>IS</span> <B><I>MY</I></B> <span>RESUME! ,</span></h1>
            
           
        </div>
    </div>
    <div id="page2">
        <div id="loop">
            <h1><B>THIS</B> <span>IS</span> <B><I>MY</I></B> <span>RESUME! ,</span></h1>
            <h1><B>THIS</B> <span>IS</span> <B><I>MY</I></B> <span>RESUME! ,</span></h1>
            <h1><B>THIS</B> <span>IS</span> <B><I>MY</I></B> <span>RESUME! ,</span></h1>
            <h1><B>THIS</B> <span>IS</span> <B><I>MY</I></B> <span>RESUME! ,</span></h1>
            
           
        </div>
    </div>
    <div id="page3">
        <div id="loop">
            <h1><B>THIS</B> <span>IS</span> <B><I>MY</I></B> <span>RESUME! ,</span></h1>
            <h1><B>THIS</B> <span>IS</span> <B><I>MY</I></B> <span>RESUME! ,</span></h1>
            <h1><B>THIS</B> <span>IS</span> <B><I>MY</I></B> <span>RESUME! ,</span></h1>
            <h1><B>THIS</B> <span>IS</span> <B><I>MY</I></B> <span>RESUME! ,</span></h1>
            
           
        </div>
    </div> 


  
</body>
</html> 
