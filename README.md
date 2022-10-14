<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="Flat-Style-Business-Template.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cherry+Swash&display=swap" rel="stylesheet">
    <link href="https://allfont.ru/allfont.css?fonts=helvetica_condenced-normal" rel="stylesheet" type="text/css" />
    <title>Flat-Style-Business</title>
</head>
<body>
    <head class="header">
       <div class="header_content">
        <div class="logo">
            <h1 class="logo_type">Black Sea</h1>
        </div>
        <div class="menu">
            <nav class="nav">
                <a href="#" class="items">
                    <ul class="">Menu   <b class="cosai">/</b></ul>
                </a>
                <a href="#" class="items">
                    <ul class="">About me   <b class="cosai">/</b></ul>
                </a>
                <a href="#" class="items">
                    <ul class="">Portfolio   <b class="cosai">/</b></ul>
                </a>
                <a href="#" class="items">
                    <ul class="">Contact me</ul>
                </a>
            </nav>
        </div>
    </div>
    </head>
    <div class="content">
        <div class="conteiner">
            <div class="contented">

            <div class="head_item">
                <h2 class="item">We need the tonic of <br>wildness</h2>
            </div>
        <div class="btn1">
            <a class="button " href="#" class="btn">Reade more</a>
        </div>

        <ul class="togle">
            <li></li>
            <li></li>
            <li class="active"></li>
            <li></li>
            <li></li>
        </ul>

        </div>

        </div>
    </div>

    <div class="explors">
        <section class="section">
            <div class="head1">
                <h3 class="header1">At the same time that we areearnest to explor<br> & learn all things </h3>
                    <p class="text">Lorem Ipsum is simply dummy text of the printing and typesetting industry. 
                        Lorem Ipsum has been the industry's standard dummy text<br> ever since the 1500s,
                         when an unknown printer took a galley of type<br> and scrambled it to make a type specimen book.
                        </p>
               
            </div>
            <div class="images_content">
            <div class="images">
                <a href="#"><img  class="image" src="images/images/2.png" alt="Корзина"></a>
                <a href="#"><img  class="image" src="images/images/3.png" alt="Земля" ></a>
                <a href="#"><img  class="image" src="images/images/4.png" alt="Портфель"></a>
            </div>
        </div>
        </section>
    </div>

    <div class="portfolio">
        <div class="section">
            <div class="content3">
            <div class="folio">
                <img class="photo2" src="images/images/5.png" alt="">
            </div>
            <div class="text3">
                <h3 class="b">Dhavan</h3>
                <h4 class="big">,,</h4>
            </div>
        </div>

            <p class="text1">
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. 
                Lorem Ipsum has been the industry's<br> standard dummy text ever since the 1500s, 
                when an unknown printer took a galley of type and scrambled it to 
                a type<br> specimen book. It has survived not only five centuries, but also the leap 
                into electronic typesetting
            </p>
        </div>
    </div>


    <div class="map">
        <div class="section">
            <map name="map1">
                
                <form class="form1">
                  <input class="input1" type="name" name="Namme" value="" placeholder="Name">
                  <input class="input1" type="email" name="email" value="" placeholder="email address">
                  <input class="input2" type="message" name="message" value="" placeholder="Message">
                </form>
            
                <area shape="rect" coords="25,36,114,98" href="" alt="">
                
            </map>
        </div>
    </div>

    
    <footer class="footer1">
        <span>Copyright &copy;  2022 Css Author.com</span>
    </footer>
        
    
</body>
</html>



*,body{
    margin: 0;
    padding: 0;
    font-family: 'Helvetica_Condenced-Normal', arial;
    box-sizing:border-box;
}

p,h1-h6{
    margin-left: 15px;
    margin-right: 15px;
}



/* HEADER */




.header{
    width: 100%;
}


.header_content{
    display: flex;
    justify-content: space-between;
    padding-top:30px;
    padding-bottom: 30px;
    background-color: #4d99a5;
    background:linear-gradient( to left, aqua, blue);

    position: fixed;
    top: 0;
    left: 0;
    margin: auto;
    width: 100%;
    
}

.logo_type{
    margin-left: 50px;
    color: white;
    font-size: 40px;
    font-weight: 600;
    font-family:Cherry Swash ;
}
.content{
    width: 100%;
    height: 600px;
    background-image: url(images/images/1.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    -webkit-background-size:cover;
    
}

.menu{
    align-self: center;
}
.item{
    color:white;
    font-size: 44px;
}
.nav{
    display: flex;
    margin-right: 50px;
    
}
.items{
   margin-right: 40px;
   text-decoration: none;
   font-size: 18px;
   text-transform: uppercase;
   border-right: 3px solid #dce3e4;
   
   border: 5px;
  
   padding-top: -5px;
   color:#dce3e4;
  
}

.cosai{
    padding-left: 50px;
}

.items:last-child{
    border:none;
}


.items:hover{
    color:black;
    transition: .9s;
    -webkit-transition: .9s;
    -moz-transition: .9s;
    -ms-transition: .9s;
    -o-transition: .9s;
}



/* CONTENT*/



.head_item{
    padding-top: 100px;
    text-align: center;
}
.item{
    text-transform: uppercase;
    padding-top: 130px;
}
.btn1{
    text-align: center;
    margin-top:50px;
   
}

.button{
    font-size: 30px;
    text-decoration: none;
    color:white;
    font-weight: 400;
    border: 3px solid white;
    padding: 15px 50px;
    border-radius:9px ;
    -webkit-border-radius:9px ;
    -moz-border-radius:9px ;
    -ms-border-radius:9px ;
    -o-border-radius:9px ;
}
.button:hover{
    color:blue;
    transition: .6s;
    -webkit-transition: .6s;
    -moz-transition: .6s;
    -ms-transition: .6s;
    -o-transition: .6s;
    border:3px solid blue;
}


ul{
    list-style: none;
    
}

.togle{
    text-align: center;
    margin-top: 120px;
}
li{
    display: inline-block; /* Строчно-блочный элемент */
    
    border: 2px solid #fff; /* Параметры контура */
    margin-right: 5px; /* Отступ справа */
    background: white; /* Чёрный фон */
    width: 10px; height: 10px; /* Ширина и высота */
    border-radius: 10px; /* Делаем кружок */
}
li.active {
    background: #b00; /* Красный фон */
    box-shadow: 0 0 4px 2px #fff; /* Параметры свечения */
   } 



    /*EXPLORS  */


.section{
    width: 100%;
    height: 460px;
}

.header1{
    text-align: center;
    padding-top: 90px;
    color:black;
    font-size: 30px;
    font-weight: 300;
}

.text{
    padding-top: 50px;
    text-align: center;
    font-size: 15px;
    color:black;
    font-weight: 300;
}

.images{
  
   padding-top: 75px;
   
}


.images_content{
    display: flex;
    justify-content: space-evenly;
}

.image{
    margin:50px 115px 85px 50px;
}



  /* PORTFOLIO*/


.portfolio{
    margin-top: 80px;
    background-color:blue;
    padding-top: px;
}



.big{
    font-size: 290px;
    padding-bottom: 60px;
    margin-left: 34px;
    color:aqua;
}
.b{
    font-size: 23px;
    text-transform: uppercase;
    margin-bottom: -200px;
    margin-left: 43px;
    color: white;
}

.folio{
    margin-top: 90px;
}

.photo2{
    border-radius: 100px;
    -webkit-border-radius: 100px;
    -moz-border-radius: 100px;
    -ms-border-radius: 100px;
    -o-border-radius: 100px;
    margin-top: 23px;
}

.text1{
    text-align: center;
    font-size: 16px;
    color:white;
    line-height: 1.9;
    
}
.content3{
    display: flex;
    justify-content: center;
}

.text3{
    margin-top: 100px;
}


  /* MAP */



.map{
    width: 100%;
    height: 515px;
    background-image:url(images/images/6.png);
    background-repeat:no-repeat;
    background-position:center;
    background-size:cover;
    -webkit-background-size:cover;
}


.form1{
   display: flex;
   align-items: center;
   flex-direction: column;
   padding-top: 150px;
   
}
.input1{
    
    width: 275px;
    height: 35px;
    margin-top: 10px;
    border-color: #d8d8d8;
    box-shadow: 0px 0px 6px 0px;
}
.input2{
    
    width: 275px;
    height: 80px;
    margin-top: 10px;
    padding-bottom: 30px;
    border-color: #d8d8d8;
    box-shadow: 0px 0px 6px 0px;
}


  /* FOOTER */

.footer1{
    background-color:blue;
    font-size: 15px;
    text-transform: uppercase;
    text-align: center;
    padding: 10px 0px 10px 0px;
    color:white;
}




/* Гамбургер меню */






/* ADAPTACIA*/
                                                  /* ADAPTACIA 1280px  */



@media(max-width:1100px){

    .nav{
        margin-right: 0px;
     }
     .items{
        font-size: 17px;
        margin-right: 25px;
    } 

}






                                                   /* ADAPTACIA 1024px  */


@media(max-width:1024px){

 /* HEADER*/

 .logo_type {
    font-size: 30px;

 }

 .nav{
    margin-right: 0px;
 }

.items{
    font-size: 15px;
    margin-right:35px;
} 
.button{
    font-size: 25px;
    padding: 15px 45px;

} 

   /*CONTENT*/

   .item{
    font-size: 40px;
   }


}


                                                 /* ADAPTACIA 900px  */

@media (min-width:770px) and (max-width:900px){
    .logo_type {
        font-size: 26px;
    }
    .items {
        font-size: 13px;
        margin-right: 25px;
    }



    /*CONTENT*/

    .content{
        height: 503px;
    } 

    .head_item {
        padding-top: 50px;
        text-align: center;
    }





   /*EXPLORES*/



    .header1 {
        text-align: center;
        padding-top: 90px;
        color: black;
        font-size: 25px;
        font-weight: 300;
    }


  /*PORTFOLIO*/



  .folio {
    margin-top: 55px;
}

.big {
    font-size: 260px;
    padding-bottom: 31px;
    margin-left: 26px;
    color: #33d9a1;
}
.text1 {
    text-align: center;
    font-size: 16px;
    color: white;
    line-height: 1.4;
    padding:0px 10px 0px 10px;
}

}
    




                                                   /* ADAPTACIA 770px  */


@media (max-width:771px) {
    /*HEADER*/

    .menu{
        display: none;
    }


    .logo_type{
        font-size: 25px;
    } 
    .items {
        font-size: 12px;
        margin-right: 20px;
    }


    .item {
        font-size: 33px;
    }
    .btn1{
        margin-top: 60px;
    }
    .button {
        font-size: 23px;
        padding: 15px 43px;
    }



    /*CONTENT*/

    .item {
        font-size: 36px;
    }
    .button {
        font-size: 20px;
        
    }

    /*EXPLORES*/


    .header1{
        font-size: 25px;
        padding-top: 65px;
    }
    .text {
        font-size: 14px;
        line-height: 1.9;
    }
    



    /* PORTFOLIO*/

    .portfolio {
       margin-top: 50px;
    }

    .folio {
        margin-top: 80px;
    }
    .text3 {
        margin-top: 90px;
    }

    .b {
        font-size: 20px;
        
        margin-bottom: -186px;
        margin-left: 44px;
        
    }

    .big {
        font-size: 242px;
        padding-bottom: 60px;
        margin-left: 29px;
        
    }

    .text1 {
        text-align: center;
        font-size: 14px;
       
        line-height: 2.9;
    }




    /*FOOTER*/


    .footer1{
        font-size: 13px;
    } 
}






                                                   /* ADAPTACIA 480px  */

@media (max-width: 480px) {
    /*header_content*/
    .menu{
        display:none ;
    }







    /*EXPLORS*/


    .images {
        
        justify-content: space-between;
        display: contents;
    }
    .image {
         margin: 0px; 
    }
    .images_content {
        display: flex;
        justify-content: space-evenly;
        padding-top: 65px;
    }
}






                                                  /* ADAPTACIA 320px  */

@media (max-width: 320px) {
    
/*header_content*/


    .menu{
        display: ;
    }
    .logo_type{
        margin-left: 20px;
    }

    .item{
        font-size: 23px;
    }
    .button {
        font-size: 14px;
    }
    .head_item {
        padding-top: 115px;
    }

  /*EXPLORES */

.header1{
    font-size: 20px;
    padding-top:40px;
}
.text {
    font-size: 12px;
}

.explors, section{
    
    height: 300px;
}

.images{
    display: none;
}

/*portfolio*/


.folio{
    margin-top: 10px;
}

.text3{
    margin-top: 50px;
} 
.text1 {
    text-align: center;
    font-size: 13px;
    line-height: 1.9;
    padding-top:20px;
}
.big {
    font-size: 185px;
    padding-bottom: 29px;
    margin-left: 33px;
    padding-top: 40px;
}
.b {
    font-size: 20px;
    margin-bottom: -186px;
    margin-left: 44px;
}


/*MAP*/


.input1 {
    width: 230px;
}

.input2{
    width: 230px;
}


/*FOOTER*/

.footer1 {
    font-size: 10px;
}







}
