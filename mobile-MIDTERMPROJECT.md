# INDEX PAGE
- [Click here to see the full website](http://media15live.com/studentsUpload/Tbardini_1586637064/indexExoticTravel.htm)

![Index Page](https://github.com/thiagobardini/HTML5-CSS-BHCC/blob/master/Imagens/MobileExoticTravel.png)

## CODE
````html
<!-- saved from url=(0079)http://www.media15live.com/studentsUpload/BARDINI_1585582065/MIDTERMPROJECT.htm -->
<html>

<head>
  <meta charset="utf-8">
  <meta http-equiv="Content-Type" content="text/html; charset=windows-1252">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MID TERM PROJECT</title>
  <style>
    body {
      margin: 0px;
      font-family: arial;
      font-size: 15px;
      color: #676867;
      line-height: 120%;
    }


    p {
      margin-top: 16px;
      margin-bottom: 16px;
    }


    #container {
      background-color: transparent;
      width: 950px;
      height: auto;
      margin-left: auto;
      margin-right: auto;
      text-align: left;
      margin-top: 20px;
      margin-bottom: 20px;
    }

    #HOLDER1 {
      background-color: transparent;
      width: 950px;
      height: 80px;
      float: left;
      display: flex;
    }

    #heading1 {
      width: 700px;
      height: 80px;
      float: left;
      display: flex;
      justify-content: left;
      align-items: center;
      font-family: fantasy;
      font-size: 3em;
    }

    #heading1 a:link {
      text-decoration: none;
    }

    #heading2 {
      width: 90px;
      height: 80px;
      float: left;
      display: flex;
      justify-content: center;
      margin-right: 10px;
      line-height: 85px;
      font-family: verdana;
    }


    #heading3 {
      width: 40px;
      height: 80px;
      float: left;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    #headImg3 {
      width: 30px;
      height: 30px;
      background-image: url('https://ya-webdesign.com/transparent250_/facebook-f-logo-png-transparent-background-2.png');
      background-size: cover;
    }

    #heading4 {
      width: 40px;
      height: 80px;
      float: left;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    #headImg4 {
      width: 20px;
      height: 20px;
      background-image: url('https://icon-library.net/images/twitter-icon-decorator/twitter-icon-decorator-19.jpg');
      background-size: cover;
    }

    #heading5 {
      width: 40px;
      height: 80px;
      float: left;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    #headImg5 {
      width: 25px;
      height: 25px;
      background-image: url('https://s3.amazonaws.com/ceblog/wp-content/uploads/2012/07/how-web-designers-use-pinterest.jpg');
      background-size: cover;
    }

    #heading6 {
      width: 40px;
      height: 80px;
      float: left;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    #headImg6 {
      width: 40px;
      height: 40px;
      background-image: url('https://i.pinimg.com/originals/08/17/15/0817158f3a05c0d62de647c28f4cde54.jpg');
      background-size: cover;
    }

    #HOLDER2 {
      background-color: transparent;
      width: 950px;
      height: 270px;
      float: left;
      display: inline-grid;
    }

    #banner {
      width: 950px;
      height: 230px;
      background-image: url('https://graylinebrazil.com/files/4815/0271/9534/FN_BANNER.jpg');
      background-size: cover;
      float: left;
    }

    #bannerTEXT {
      background-color: transparent;
      text-shadow: 0 0 3px #FF0000, 0 0 5px #0000FF;
      font-size: 35px;
      color: white;
      text-align: left;
      position: relative;
      float: right;
      top: 200px;
      padding-right: 2px;
    }

    #bannerTEXT a:link {
      text-decoration: none;
    }

    #bannerTEXT a:visited {
      color: white;
    }

    #topLINKS {
      background-color: transparent;
      width: 950px;
      float: left;
    }

    #topLINKS2 {
      display: none;
    }

    #topLINKS a:link {
      color: white;
      background-color: #70cb7c;
      font-size: 20px;
      text-decoration: none;
      width: 190px;
      height: 40px;
      display: inline-block;
      text-align: center;
      font-family: arial;
      line-height: 40px;
    }

    #topLINKS a:visited {
      color: white;
    }

    #topLINKS a:hover {
      color: white;
      background-color: lightblue;
    }


    #BOX1 {
      width: 280px;
      height: 1125px;
      background-color: #E6E6E6;
      float: left;
      margin-top: 10px;
      margin-bottom: 10px;
      padding-left: 20px;
      padding-right: 20px;

    }

    #BOX1 a:link {
      text-decoration: none;
    }

    #BOXimg1 {
      width: 280px;
      height: 150px;
      background-image: url('https://i.ytimg.com/vi/LKMf8KyKpqE/maxresdefault.jpg');
      background-size: cover;
      float: left;
      margin-right: 13px;
      margin-bottom: 13px;
    }

    #HOLDER3 {
      background-color: transparent;
      width: 620px;
      height: auto;
      float: right;
      display: block;
      margin-top: 10px;
    }

    #BOX2 {
      width: 620px;
      height: 350px;
      background-color: white;
      float: right;
      margin-bottom: 5px;
    }

    #BOXimg2 {
      width: 200px;
      height: 280px;
      background-image: url('https://i.pinimg.com/originals/fb/9e/29/fb9e29b6342431a6d8946f2df5455ac3.jpg');
      background-size: cover;
      float: left;
      margin-right: 13px;
    }

    #BOX3 {
      width: 620px;
      height: 350px;
      background-color: white;
      float: right;
    }

    #BOXimg3 {
      width: 280px;
      height: 130px;
      background-image: url('https://img.muvtravel.com/destinations/818_Florianopolis/818_Florianopolis_Brazil_01896113.jpg');
      background-size: cover;
      float: left;
      margin-right: 13px;
    }
    /* HTML table */
    #BOX4 {
      width: 310px;
      height: auto;
      background-color: white;
      float: left;
          padding-bottom: 10px;
    }

    #BOX5 {
      width: 310px;
      height: auto;
      background-color: white;
      float: right;
      padding-bottom: 10px;
    }

    #BOX6 {
      width: 620px;
      height: auto;
      background-color: white;
      float: right;
    }

    #BOX7 {
      width: 620px;
      height: auto;
      background-color: white;
      float: right;
      text-align: center;
    }

    .table1
    {
      border: 0px solid gray;
      padding-top: 2px;
      padding-bottom: 2px;
      padding-left: 2px;
      padding-right: 2px;
      color: #676867;
      border-radius: 10px;
    }

    #submitbutton
    {
      border 1px solid red;
      padding-top: 6px;
      padding-bottom: 6px;
      padding-left: 6px;
      padding-right: 6px;
      color: black;
      border-radius:10px;
      background-color:lightgreen;
    }

    #footer {
      width: 950px;
      height: 40px;
      background-color: black;
      display: inline-block;
      text-align: center;
      font-family: arial;
      line-height: 40px;
    }

    #footer2 {
      width: 810px;
      height: 70px;
      background-color: transparent;
      float: left;
      margin-top: 20px;
      margin-left: 80px;
      color: black;
      line-height: 120%;

    }

    .topnavbar {
      display: none;
    }

    @media screen and (max-width: 600px) {

      html,
      body {
        width: 100%;
        height: 100%;
      }

      #container {
        width: 96%;
        margin-left: 2%;
        margin-right: 2%;
      }

      #HOLDER1,
      #topLINKS,
      #footer {
        width: 100%;
      }

      #heading1 {
        font-size:-webkit-xxx-large;
      }

      #HOLDER2,
      #HOLDER3 {
        width: 100%;
        height: fit-content;
      }

      #BOX1 {
        width: 98%;
        height: 550px;
        padding-left: 1%;
        padding-right: 1%;
      }

      #BOX2,
      #BOX3,
      #BOX4,
      #BOX5,
      #BOX6,
      #BOX7 {
        width: 98%;
        height: fit-content;
        padding-left: 1%;
        padding-right: 1%;
      }


      .table1
      {
        border: 0px solid gray;
        padding-top: 2px;
        padding-bottom: 2px;
        padding-left: 2px;
        padding-right: 2px;
        color: #676867;
        border-radius: 10px;
      }

      #submitbutton
      {
        border 1px solid red;
        padding-top: 6px;
        padding-bottom: 6px;
        padding-left: 6px;
        padding-right: 6px;
        color: black;
        border-radius:10px;
        background-color:lightgreen;
      }

      #banner {
        width: 100%;
      }

      #bannerTEXT a {
        font-size: large;
      }

      #topLINKS a:link {
        width: 100%;
      }

      #footer2 {
        width: 100%;
        height: fit-content;
        margin: 10px 0;
      }

      .topnavbar {
        width: 100%;
        display: block;
        height: 40px;
        background-color: rgb(228, 222, 222);
      }

      #search-icon {
        width: 40px;
        height: 40px;
        background-image: url('https://icons-for-free.com/iconfiles/png/512/search-131964784990705675.png');
        background-size: cover;
        float: left;
      }

      #menu-icon {
        width: 40px;
        height: 40px;
        background-image: url('https://upload.wikimedia.org/wikipedia/commons/thumb/8/8d/VisualEditor_-_Icon_-_Menu.svg/1200px-VisualEditor_-_Icon_-_Menu.svg.png');
        background-size: cover;
        float: right;
      }

      .topnavbar a {
        display: none;
      }

      .topnavbar.responsive {
        position: block;
      }

      .topnavbar.responsive a {
        color: white;
        background-color: #70cb7c;
        font-size: 20px;
        text-decoration: none;
        width: 100%;
        height: 40px;
        float: left;
        display: inline-block;
        text-align: center;
        font-family: arial;
        line-height: 40px;
      }

    }
  </style>
</head>

<body>
  <div id="container">
  <!--start container-->
    <div id="topnavbar" class="topnavbar">
      <div id=search-icon></div>
      <div id="menu-icon" onclick="toggleMenu()"></div>
      <a href="http://www.media15live.com/studentsUpload/BARDINI_1585582065/history.htm">our
        history</a>
        <a
        href="http://www.media15live.com/studentsUpload/BARDINI_1585582065/destinations.htm">destinations</a><a
        href="http://www.media15live.com/studentsUpload/BARDINI_1585582065/specials.htm">specials</a><a
        href="http://www.media15live.com/studentsUpload/BARDINI_1585582065/Team.htm">our team</a><a
        href="http://www.media15live.com/studentsUpload/BARDINI_1585582065/contactus.htm">contact us</a>
    </div>

  <div id="HOLDER1">
  <!--start HOLDER1-->
    <div id="heading1"><a href="http://www.media15live.com/studentsUpload/BARDINI_1585582065/MIDTERMPROJECT.htm">
        <font color="#afafaf">Exotic</font>
        <font color="#676867"><b>Travel</b></font>
      </a></div>
    <div id="heading2">
      <font size="2"><b>
          <font color="black">FOLLOW US</font>
        </b></font>
    </div>
    <div id="heading3"><a href="https://www.facebook.com/">
        <div id="headImg3"></div>
      </a></div>
    <div id="heading4"><a href="https://twitter.com/explore">
        <div id="headImg4"></div>
      </a></div>
    <div id="heading5"><a href="https://www.pinterest.com/">
        <div id="headImg5"></div>
      </a></div>
    <div id="heading6"><a href="https://www.instagram.com/">
        <div id="headImg6"></div>
      </a></div>
  </div>
  <!--end HOLDER1-->

  <div id="HOLDER2">
    <!--start HOLDER2-->
    <div id="banner">
      <div id="bannerTEXT"><a href="http://www.media15live.com/studentsUpload/BARDINI_1585582065/MIDTERMPROJECT.htm">The
          Perfect
          Destination</a></div>
    </div>
    <div id="topLINKS">
      <a href="http://www.media15live.com/studentsUpload/BARDINI_1585582065/history.htm">our
        history</a><a
        href="http://www.media15live.com/studentsUpload/BARDINI_1585582065/destinations.htm">destinations</a><a
        href="http://www.media15live.com/studentsUpload/BARDINI_1585582065/specials.htm">specials</a><a
        href="http://www.media15live.com/studentsUpload/BARDINI_1585582065/Team.htm">our team</a><a
        href="http://www.media15live.com/studentsUpload/BARDINI_1585582065/contactus.htm">contact us</a></div>

  </div>
  <!--end HOLDER2-->

  <div id="BOX1">
    <!--start BOX1-->
    <font size="5">
      <p><b>Latest </b>News</p>
    </font>
    <p>
      <font color="red">03.30.2020 </font>Coronavirus pandemic is at the end, and all travelers are allowed to travel.
    </p>

    <p>
      <font color="red">02.01.2020 </font>Coronavirus Pandemic - Unfortunately, foreign travelers are not allowed to
      travel in Brazil at the moment.
    </p>

    <font size="5">
      <p><b>Featured </b>Hotel</p>
    </font>
    <div id="BOXimg1"></div>
    <p>
      <font color="red">Fernando de Noronha - True Paradise! </font>
    </p>
    <p>This archipelago is composed of twenty islands covering an area of 26 square km. The main island is the only
      inhabited. The habitants devised a system of sustainable tourism, creating an opportunity to experience the
      balance between man and nature on one of the most important ecological sanctuaries of the world.... <a
        href="http://www.media15live.com/studentsUpload/BARDINI_1585582065/destinations.htm">
        <font color="red">more&gt;</font>
      </a> </p>
  </div>
  <!--end BOX1-->

  <div id="HOLDER3">
    <!--start HOLDER3-->
    <div id="BOX2">
      <div id="BOXimg2"></div>
      <font size="5">
        <p><b>Welcome</b> to our Travel Agency</p>
      </font>
      <p>
        <font color="red"><b>With almost 30 years of experience in tourism in Brazil</b></font><br>Exotic Travel is
        proud to provide its clients with state of the art services at extremely competitive rates.
      </p>
      <p>Through our extensive network of partners, we are able to assist you in any way needed in order to make your
        dream vacation come true.</p>
      <p>Whether you choose to keep things simple and see a traditional Brazil, or if you want to visit our beautiful
        country's most remote destinations, we are here for you. We promise you will have an extraodinary time with
        us.<br>After all, no one knows Brazil like we do.</p>
    </div>

    <br>
    <hr>

    <div id="BOX3">
      <font color="red" size="5"></font>
      <p>
        <font color="red" size="5">Hot</font>
        <font size="5">Destination </font>
        <font size="5"><b>this Summer</b></font>
      </p>
      <div id="BOXimg3"></div>
      <p>
        <font color="red"></font>
      </p>
      <p>
        <font color="red"><b>Florianopolis - Santa Catarina</b></font><br>Florianopolis, the capital of Santa Catarina
        state, is know throughout Brazil for its miles and miles of gourgeous beaches, excellent seafood and
        traditional Azorean fishing villages.
      </p>
      <p>The downtown is in the mainland, but the best attractions (beaches!!) are in the island, wich can be easily
        accessed via public bridges, one of wich is Brazil's largest suspension bridge. The island is a large beach
        community divided into three sections: north, south and east coasts. In addition to the bay and ocean beaches,
        the city features a large lagoon – Lagoa da Conceicao.</p>
      <hr>
    </div>

    <div id="BOX7">
      <h2>Contact Details</h2>
    </div>
    <div id="BOX4">
      <div class="table1">
      Applicant Name:
      <br>
      <input type="text" name="Name" size="30" maxlength="20"
      placeholder="Type your name" required>
      <br>
      Phone
      <br>
      <input type="text" name="phone" size="12" maxlength="10">
      <br>
      Email
      <br>
      <input type="text" name="email">
      <br>
      Age:
      <br>
      <input type="text" name="age">
      <br><br>
      Gender: <input type="radio" name="gender" value="female"> Female <input type="radio" name="gender" value="male"> Male
      <br><br>
      </div>
    </div>

    <div id="BOX5">
      <div class="table1">

      Schedule
      <br>
      <select name="schedule">
        <option value="Moring: 6AM - 11AM">Moring: 6AM - 11AM</option>
        <option value="Day: 11AM - 5PM">Day: 11AM - 5PM</option>
        <option value="Night: 5PM - 11PM">Night: 5PM - 11PM</option>
      </select>
      <br><br
      Tell us about yourself:
      <br>
      <textarea name="applicantinfo" rows="5" cols="30"></textarea>
      <br><br>
      Pick one country:
      <br>
      <input type="checkbox" name="brazil"> Brazil
      <input type="checkbox" name="jamaica"> Jamaica
      <input type="checkbox" name="spain"> Spain
      <br>
    </div>

    <div id="BOX6">
      <p align="center">
      <input id="submitbutton" type="submit" value="Apply now">
      </p>
    </div>
    </div>

  </div>
  <!--end HOLDER3-->

  <div id="footer">© 2020 Trusted Media Brands, Inc</div>
  <div id="footer2">
    <font size="6px" face="fantasy" color="#afafaf">Exotic</font>
    <font size="6px" color="#676867" face="fantasy"><b>Travel</b></font> is a global, multi-platform and entertainment
    company. Powered by its own
    proprietary technology, Mashable is the go-to source for tech, digital culture and entertainment content fot
    its dedicated and influential audience around the globe.
  </div>

</div>  <!--end container-->

  <div id="container">
    <!--start container-->
    <script type="text/javascript" async="" src="./MID TERM PROJECT_files/6e9bb749fd596ea3a0d69ed4372dc651"></script>
    <script
      type="text/javascript">(function (d, w) { var x = d.getElementsByTagName('SCRIPT')[0]; var f = function () { var s = d.createElement('SCRIPT'); s.type = 'text/javascript'; s.async = true; s.src = "//np.lexity.com/embed/YW/6e9bb749fd596ea3a0d69ed4372dc651?id=89b8073435b7"; x.parentNode.insertBefore(s, x); }; w.attachEvent ? w.attachEvent('onload', f) : w.addEventListener('load', f, false); }(document, window));</script>
    <script>
      function toggleMenu() {
        var x = document.getElementById("topnavbar");
        if (x.className === "topnavbar") {
          x.className += " responsive";
        } else {
          x.className = "topnavbar";
        }
      }
    </script>
  </div>
</div>
</body>

</html>
```
