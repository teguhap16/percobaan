

    </div><!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="style.css">
        <title>Document</title>
       
    </head>
    
    <body>
    
        <h1>let's test your memory game</h1>
        <h2>classic memory game</h2>
      
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Commodi dicta eius officiis? Atque, delectus. Est eaque totam quaerat qui facilis, nulla laudantium autem sint, quidem aperiam iusto, sequi necessitatibus libero.
            </p>
       <div>
           <div class="action">
               <a href="#">reset game</a>
               <a href="#">invite a friend</a>
               <a href="#">save this game </a>
           </div>
    
           <div id="gameboard"></div> 
           <div class="card">
             <img src="http://s3.amazonaw.com/codeacademy-content/courses/web-101/unit-6/htmlcss1-img_star.png">
           </div>
           
           <div>
            <img src="http://s3.amazonaw.com/codeacademy-content/courses/web-101/unit-6/htmlcss1-img_star.png">
            </div>

           <div class="card">
     <img src="http://s3.amazonaw.com/codeacademy-content/courses/web-101/unit-6/htmlcss1-img_star.png">
           </div>

           <div class="card">
         <img src="http://s3.amazonaw.com/codeacademy-content/courses/web-101/unit-6/htmlcss1-img_star.png">
       </div>

       <div class="card">
     <img src="http://s3.amazonaw.com/codeacademy-content/courses/web-101/unit-6/htmlcss1-img_star.png">
      </div>

       <div class="card">
      <img src="http://s3.amazonaw.com/codeacademy-content/courses/web-101/unit-6/htmlcss1-img_star.png">
     </div>

  


    <div class="card">
  <img src="http://s3.amazonaw.com/codeacademy-content/courses/web-101/unit-6/htmlcss1-img_star.png">
    </div>

    <div class="card">
        <img src="http://s3.amazonaw.com/codeacademy-content/courses/web-101/unit-6/htmlcss1-img_star.png">
    </div>


    <div class="card">
         <img src="http://s3.amazonaw.com/codeacademy-content/courses/web-101/unit-6/htmlcss1-img_star.png">
    </div>




    <div class="card">
         <img src="http://s3.amazonaw.com/codeacademy-content/courses/web-101/unit-6/htmlcss1-img_star.png">
    </div>



    <div class="card">
         <img src="http://s3.amazonaw.com/codeacademy-content/courses/web-101/unit-6/htmlcss1-img_star.png">
    </div>

    </div>
    
</body> 
</html>



#style css
body {
    background-color:aqua;
    margin: 10px;
    padding: 50px 60px;
}

h1 {
    color: gray;
    font-family:calibri;
    font-size:50px ;
    font-weight: 400;
    margin:0 ;
    text-align:center ;
}

h2{
    color: orange;
    font-family: sans-serif;
    font-size:16px ;
    font-weight: 400;
    margin:100 ;
    text-align:center ;
    text-transform: uppercase;

}


p {
    color:#333;
    font-family:sans-serif;
    font-size:50px ;
    font-weight: 400;
    margin:100 ;
    text-align:center ;
}

.action {
    text-align: center ;
    margin-top: 30px;
}

.action a {
    background-color: paleturquoise;
    border-radius:  3px;
    color: #004e89;
    font-family:'yatramanav',sans-serif;
    font-size: 16px ;
    font-weight: 300 ;
    display:inline-block ;
    margin:10px ;
    padding: 12px;
    text-align: center ;
    text-decoration:none ;
    text-transform:uppercase ;
}

#gameboard{
    position: relative;
    text-align:center;
    top: 30px;
}

.card{
    border: 2px solid gray;
    display: inline-block;
    height: 200px;
    margin-top: 4px;
    padding: 30px auto;
    text-align: center;
    width: 215px;
}

.card:hover{
    background-color: #004E89;
    border-color: 004E89;
}


.card img {
    padding-top: 40px;
}
