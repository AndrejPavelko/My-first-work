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
