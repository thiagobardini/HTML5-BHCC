## BHCC Student - CIT111 HTML5

# Major: Information Technology

# Spring 2020

#
HTML 

Block Statements: blockquote, div, dl, form, h tags, hr, ol, p, table, ul
<!--
    TAGS:
    <title> Titulo
    <b> bold
    <p> parágrafo
    <body>
    heading <h1></h1> <h2></h2> <h3></h3> <h4></h4> <h5></h5> <h6></h6>
    ol -> Ordem list (I always need close a ordem list "/")
    li -> Lists (I dont need close a list)

    If want to change from numbers to roman numbers
     <ol type = "I">
    or
    If want to change from numbers to "a", "b" , "c"...
    <ol type = "a">

    hr -> Horizontal line
    <br /> Line Breaker -> Começar em uma linha abaixo

    <a href="#"></a> -> Página ancora é para criar um link, sendo que o meu titulo será "Here you can link to page 1"
    ex: <a href="Page1.html">Here you can link to page 1</a>


    <h1 style="color:red;font-size:20px;font-family:arial,verdana,san-serif"> -> This is inside of <heading/paragraph..>
    style="..." -> start with <style media="screen">
        color':'...(black,white...) ';' font-size':'(...10,20,30)'px'';'font-family'':'

        HTML Wheel Picker -> you can find all the colors there. ex #003399 (color number)

    <div style="width:200px;height:200px;background-color:orange">hello word!</div>

    div -> são boxes

    <img width="200px" hsrc="https://i.ytimg.com/vi/szby7ZHLnkA/maxresdefault.jpg" alt="Sonic -> New Official Trailler">

    px -> pixel
-->
#
CSS - Cascading Style Sheets

<!-- 
EXAMPLE:
    <html>
    <head>
    <meta>
    <title>CSS</title>
    <style>

      body {
        color: green;
        font-family: verdana, arial, san-serif;
      }

      p {
        color: purple; 
      }

      h1, h2, em, b {
        font-family: times new roman, georgia, serif; 
        font-size: 14px;
      }

      h1.purple {
         color: green;
      }
      
      h1.green {
        color: purple;
      }
                    <!-- 
                    Tem dois tipos para definir classes (ex: H1), outro exemplo seria:
                        .purpleserif {
                                font-family: times new roman, georgia, serif; 
                         }    
                     Dentro do body:
                                <h1 class="purpleserif">Purple H1</h1>
                     <--
 
      a {
        font-family: verdana, arial, san-serif;
      }
      
    </style>
    </head>
    <body>
    
    <h1>Regular H!</h1>
    <h1 class="purple">Purple H1</h1>
    <h1 class="green">Green H1</h1>
    
    </body>
    </html>
 <--
