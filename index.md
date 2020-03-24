<!-- <?php

if($_POST["submit"]) {
    $recipient="stepboyle77@gmail.com";
    $subject="Form to email message";
    $sender=$_POST["sender"];
    $senderEmail=$_POST["senderEmail"];
    $message=$_POST["message"];
    $eventType=$_POST["eventType"];
    $eventDate=$_POST["eventDate"];

    $mailBody="Name: $sender\nEmail: $senderEmail\n\n$message\$eventType\Date: $eventDate";

    mail($recipient, $subject, $mailBody, "From: $sender <$senderEmail>");

    $thankYou="<p>Thank you! Your message has been sent.</p>";
}

?> -->

<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <script src="https://kit.fontawesome.com/ba5c154945.js" crossorigin="anonymous"></script>
  <script src="WOW-master/dist/wow.js"></script>
  <script src="decor_web.js"></script>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
  <link rel="stylesheet" href="animate.css-master/animate.css">
  <link href="css/bootstrap.css" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
  <title>Event Decor Scotland</title>
</head>

<body data-spy="scroll" data-target=".navbar" data-offset="50">

  <header>
    <div class="container">
      <nav class="navbar-fixed-top">
        <div class="custom-menu visible-xs">
          <a href="https://www.eventdecorscotland.co.uk/" class="active"></a>
          <!-- <img src="images/eds_horizontal.png" alt="Logo" width="270" height="70"> -->
        </a>
          <a href="javascript:void(0);" class="icon" onclick="myFunction()">
            <i class="fa fa-bars"></i>
          </a>
    </div id="myLinks">
    <ul class="navflex">
      <li><a href="#home">Home</a></li>
      <li><a href="#skew1">Gallery</a></li>
      <li><a href="#skew2">Instagram</a></li>
      <li><a href="#skew3">Festival Flags</a></li>
      <li><a href="#skew4">Hire</a></li>
      <li><a href="#skew5">Inflatables</a></li>
      <li><a href="#contact">Contact</a></li>
      <li><a class="fab fa-facebook" href="https://www.facebook.com/eventdecor.scotland/"></a></li>
      <li><a class="fab fa-instagram" href="https://www.instagram.com/eventdecorscotland/"></a></li>
      <li><a class="far fa-paper-plane" href="mailto:info@eventdecorscotland.co.uk"></a></li>
    </ul>
</nav>
</div>
</header>

  <div id="home"class="container-fluid">
    <div class="text-area">
      <img class="logo" src="images/eds_horizontal.png" alt="Event Decor Log">
      <h3>Bespoke event decor and production services</h3>
    </div>
    <div class="wrapper3">
      <div class="container">
        <div class="jumbotron">
          <div class="container-car">
            <div id="myCarousel" class="carousel slide" data-ride="carousel">
              <!-- Indicators -->
              <ol class="carousel-indicators">
                <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
                <li data-target="#myCarousel" data-slide-to="1"></li>
                <li data-target="#myCarousel" data-slide-to="2"></li>
              </ol>

              <!-- Wrapper for slides -->
              <div class="carousel-inner">
                <div class="item active">
                  <img src="https://static.wixstatic.com/media/187a23_5869aa8973ac4d9dbaf2cfeec0cd1177~mv2_d_4264_1840_s_2.jpg/v1/crop/x_61,y_270,w_4203,h_1357/fill/w_978,h_318,al_c,q_80,usm_0.66_1.00_0.01/187a23_5869aa8973ac4d9dbaf2cfeec0cd1177~mv2_d_4264_1840_s_2.webp" alt="Los Angeles">
                </div>

                <div class="item">
                  <img src="https://static.wixstatic.com/media/187a23_d4c15278ad4a44b1a8dc4eb393546484~mv2.jpg/v1/crop/x_1,y_10,w_959,h_269/fill/w_980,h_275,al_c,lg_1,q_80/187a23_d4c15278ad4a44b1a8dc4eb393546484~mv2.webp" alt="Chicago">
                </div>

                <div class="item">
                  <img src="https://static.wixstatic.com/media/187a23_6158ef071fa043148c420475b231ca4c~mv2_d_2048_1365_s_2.jpg/v1/crop/x_0,y_336,w_2048,h_693/fill/w_978,h_331,al_c,q_80,usm_0.66_1.00_0.01/58822278_858418041171693_212741936467935.webp" alt="New York">
                </div>
              </div>

              <!-- Left and right controls -->
              <a class="left carousel-control" href="#myCarousel" data-slide="prev">
                <span class="glyphicon glyphicon-chevron-left"></span>
                <span class="sr-only">Previous</span>
              </a>
              <a class="right carousel-control" href="#myCarousel" data-slide="next">
                <span class="glyphicon glyphicon-chevron-right"></span>
                <span class="sr-only">Next</span>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>



  <div id="skew1" class="cus-div">
    <div class="content">
      <div class="container1">
        <h2>Gallery</h2>
        <h5>Click on the images to enlarge them.</h5>
        <div class="row">
          <div class="col-md-4 wow fadeInLeft animated" data-wow-offset="30" data-wow-duration="1.5s" data-wow-delay="0.15s">
            <div class="thumbnail">
              <a href="/w3images/lights.jpg" target="_blank">
                <img src="/w3images/lights.jpg" alt="Lights" style="width:100%">
                <div class="caption">
                  <p>Lorem ipsum donec id elit non mi porta gravida at eget metus.</p>
                </div>
              </a>
            </div>
          </div>
          <div class="col-md-4 wow fadeInUp animated" data-wow-offset="30" data-wow-duration="1.5s" data-wow-delay="0.15s">
            <div class="thumbnail">
              <a href="/w3images/nature.jpg" target="_blank">
                <img src="/w3images/nature.jpg" alt="Nature" style="width:100%">
                <div class="caption">
                  <p>Lorem ipsum donec id elit non mi porta gravida at eget metus.</p>
                </div>
              </a>
            </div>
          </div>
          <div class="col-md-4 wow fadeInRight animated" data-wow-offset="30" data-wow-duration="1.5s" data-wow-delay="0.15s">
            <div class="thumbnail">
              <a href="/w3images/fjords.jpg" target="_blank">
                <img src="/w3images/fjords.jpg" alt="Fjords" style="width:100%">
                <div class="caption">
                  <p>Lorem ipsum donec id elit non mi porta gravida at eget metus.</p>
                </div>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="bgimg-1">
      <div class="caption1 wow fadeInLeft animated" data-wow-offset="30" data-wow-duration="1.5s" data-wow-delay="0.15s">
        <span class="border" style="background-color:transparent;font-size:50px;color: #f7f7f7;">CLUBBING</span>
      </div>
    </div>
  </div>

  <div id="skew2" class="cus-div">
    <div class="content-instagram">
      <div class="container2">
        <h2>Instagram</h2>
        <!-- <div class="jumbotron"> -->
        <!-- SnapWidget -->
        <iframe src="https://snapwidget.com/embed/800740" class="snapwidget-widget" allowtransparency="true" frameborder="0" scrolling="no" style="border:none; overflow:hidden;  width:1500px; height:250px"></iframe>
        <!-- </div> -->
      </div>
    </div>
    <div class="bgimg-3">
      <div class="caption2 wow fadeInRight animated" data-wow-offset="30" data-wow-duration="1.5s" data-wow-delay="0.15s">
        <span class="border" style="background-color:transparent;font-size:50px;color: #f7f7f7;">FESTIVALS</span>
      </div>
    </div>
  </div>


  <div id="skew3" class="cus-div">
    <div class="content">
      <div class="container3">
        <h2>Festival Flags</h2>
        <h5>Click on the images to enlarge them.</h5>
        <div class="row">
          <div class="col-md-4 wow fadeInRight animated" data-wow-offset="30" data-wow-duration="1.5s" data-wow-delay="0.15s">
            <div class="thumbnail">
              <a href="/w3images/lights.jpg" target="_blank">
                <img src="/w3images/lights.jpg" alt="Lights" style="width:100%">
                <div class="caption">
                  <p>Lorem ipsum donec id elit non mi porta gravida at eget metus.</p>
                </div>
              </a>
            </div>
          </div>
          <div class="col-md-4 wow fadeInDown animated" data-wow-offset="30" data-wow-duration="1.5s" data-wow-delay="0.15s">
            <div class="thumbnail">
              <a href="/w3images/nature.jpg" target="_blank">
                <img src="/w3images/nature.jpg" alt="Nature" style="width:100%">
                <div class="caption">
                  <p>Lorem ipsum donec id elit non mi porta gravida at eget metus.</p>
                </div>
              </a>
            </div>
          </div>
          <div class="col-md-4 wow fadeInLeft animated" data-wow-offset="30" data-wow-duration="1.5s" data-wow-delay="0.15s">
            <div class="thumbnail">
              <a href="/w3images/fjords.jpg" target="_blank">
                <img src="/w3images/fjords.jpg" alt="Fjords" style="width:100%">
                <div class="caption">
                  <p>Lorem ipsum donec id elit non mi porta gravida at eget metus.</p>
                </div>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="bgimg-4">
      <div class="caption3 wow fadeInLeft animated" data-wow-offset="30" data-wow-duration="1.5s" data-wow-delay="0.15s">
        <span class="border" style="background-color:transparent;font-size:50px;color: #f7f7f7;">THEMES</span>
      </div>
    </div>
  </div>

  <div id="skew4" class="cus-div">
    <div class="content">
      <div class="container2">
        <h2>Hire</h2>
        <h5>Click on the images to enlarge them.</h5>
        <div class="row">
          <div class="col-md-4 wow fadeInUp animated" data-wow-offset="30" data-wow-duration="1.5s" data-wow-delay="0.15s">
            <div class="thumbnail">
              <a href="/w3images/lights.jpg" target="_blank">
                <img src="/w3images/lights.jpg" alt="Lights" style="width:100%">
                <div class="caption">
                  <p>Lorem ipsum donec id elit non mi porta gravida at eget metus.</p>
                </div>
              </a>
            </div>
          </div>
          <div class="col-md-4 wow fadeInDown animated" data-wow-offset="30" data-wow-duration="1.5s" data-wow-delay="0.15s">
            <div class="thumbnail">
              <a href="/w3images/nature.jpg" target="_blank">
                <img src="/w3images/nature.jpg" alt="Nature" style="width:100%">
                <div class="caption">
                  <p>Lorem ipsum donec id elit non mi porta gravida at eget metus.</p>
                </div>
              </a>
            </div>
          </div>
          <div class="col-md-4 wow fadeInUp animated" data-wow-offset="30" data-wow-duration="1.5s" data-wow-delay="0.15s">
            <div class="thumbnail">
              <a href="/w3images/fjords.jpg" target="_blank">
                <img src="/w3images/fjords.jpg" alt="Fjords" style="width:100%">
                <div class="caption">
                  <p>Lorem ipsum donec id elit non mi porta gravida at eget metus.</p>
                </div>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="bgimg-2">
      <div class="caption4 wow fadeInRight animated" data-wow-offset="30" data-wow-duration="1.5s" data-wow-delay="0.15s">
        <span class="border" style="background-color:transparent;font-size:50px;color: #f7f7f7;">FORMAL</span>
      </div>
    </div>
  </div>

  <div id="skew5" class="cus-div">
    <div class="content">
      <div class="container5">
        <h2>Inflatables</h2>
        <h5>Click on the images to enlarge them.</h5>
        <div class="row">
          <div class="col-md-4 wow fadeInRight animated" data-wow-offset="30" data-wow-duration="1.5s" data-wow-delay="0.15s">
            <div class="thumbnail">
              <a href="/w3images/lights.jpg" target="_blank">
                <img src="/w3images/lights.jpg" alt="Lights" style="width:100%">
                <div class="caption">
                  <p>Lorem ipsum donec id elit non mi porta gravida at eget metus.</p>
                </div>
              </a>
            </div>
          </div>
          <div class="col-md-4 wow fadeInDown animated" data-wow-offset="30" data-wow-duration="1.5s" data-wow-delay="0.15s">
            <div class="thumbnail">
              <a href="/w3images/nature.jpg" target="_blank">
                <img src="/w3images/nature.jpg" alt="Nature" style="width:100%">
                <div class="caption">
                  <p>Lorem ipsum donec id elit non mi porta gravida at eget metus.</p>
                </div>
              </a>
            </div>
          </div>
          <div class="col-md-4 wow fadeInLeft animated" data-wow-offset="30" data-wow-duration="1.5s" data-wow-delay="0.15s">
            <div class="thumbnail">
              <a href="/w3images/fjords.jpg" target="_blank">
                <img src="/w3images/fjords.jpg" alt="Fjords" style="width:100%">
                <div class="caption">
                  <p>Lorem ipsum donec id elit non mi porta gravida at eget metus.</p>
                </div>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="bgimg-6">
      <div class="caption5 wow fadeInLeft animated" data-wow-offset="30" data-wow-duration="1.5s" data-wow-delay="0.15s">
        <span class="border" style="background-color:transparent;font-size:50px;color: #f7f7f7;">XMAS</span>
      </div>
    </div>
  </div>

  <div id="skew6" class="cus-div">
    <div class="content">
      <div class="container6">
        <h2>Our Clients</h2>
        <div class="wrapper2">
          <img src="https://mourithemes.com/nandini/images/clients/01.png" alt="">
          <img src="https://mourithemes.com/nandini/images/clients/02.png" alt="">
          <img src="https://mourithemes.com/nandini/images/clients/03.png" alt="">
          <img src="https://mourithemes.com/nandini/images/clients/04.png" alt="">
        </div>
      </div>
    </div>
  </div>
  <div class="wrapper4">
    <ul>
      <li><a href="https://www.facebook.com/eventdecor.scotland/"><i class="fab fa-facebook"></i></a></li>
      <li><a href="https://www.instagram.com/eventdecorscotland/"><i class="fab fa-instagram"></i></a></li>
      <li><a href="mailto:info@eventdecorscotland.co.uk"><i id="plane" class="far fa-paper-plane"></i></a></li>
    </ul>
  </div>
  <!-- <div class="wrapper4">
  <div class="box">
  <i class="fab fa-facebook"></i>
</div>
<div class="box">
<i class="fab fa-instagram"></i>
</div>
<div class="box">
<i class="fas fa-envelope"></i>
</div>
</div> -->

<div id="contact" class="container">
  <h2>Contact Us</h2>
  <form class="form-horizontal" action="/index.php">
    <div class="form-group">
      <label class="control-label col-sm-2" for="name">Name:</label>
      <div class="col-sm-10">
        <input type="text" class="form-control" id="name" name="sender" placeholder="Enter name">
      </div>
    </div>
    <div class="form-group">
      <label class="control-label col-sm-2" for="email">Email:</label>
      <div class="col-sm-10">
        <input type="email" class="form-control" id="email" name="senderEmail" placeholder="Enter email">
      </div>
    </div>
    <div class="form-group">
      <label class="control-label col-sm-2" for="date">Date of Event:</label>
      <div class="col-sm-10">
        <input type="date" class="form-control" id="date" name="eventDate" placeholder="">
      </div>
    </div>
    <div class="form-group">
      <label class="control-label col-sm-2" for="type">Type of Event:</label>
      <div class="col-sm-10">
        <div class="checkbox" name="eventType">
          <label class="checkbox-inline"><input type="checkbox" value=""> Club Event</label>
          <label class="checkbox-inline"><input type="checkbox" value=""> Festival</label>
          <label class="checkbox-inline"><input type="checkbox" value=""> Themed</label>
          <label class="checkbox-inline"><input type="checkbox" value=""> Formal</label>
          <label class="checkbox-inline"><input type="checkbox" value=""> Christmas</label>
          <label class="checkbox-inline"><input type="checkbox" value=""> Other</label>
        </div>
      </div>
    </div>
    <div class="form-group">
      <label class="control-label col-sm-2" for="comment">Information:</label>
      <div class="col-sm-10">
        <textarea class="form-control" rows="10" id="comment" name="message"></textarea>
      </div>
    </div>
    <div class="form-group">
      <div class="col-sm-offset-2 col-sm-10">
        <button type="submit" class="btn btn-success btn-lg">Submit</button>
      </div>
    </div>
  </form>
</div>

<footer>
  <div class="wrapper1">
    <p>&copy; All Rights Reserved Nobad 2020</p>
  </div>
</footer>

<script>

var cusMenu = false;

$(document).ready(function(){
  $('.custom-menu').on('click', function(){
    $('.custom-menu').children('span').fadeToggle();
    $('nav').slideToggle();
    cusMenu = !cusMenu;
  });
});
$(window).on('resize', function(){
  if($(window).width() > 767){
    $('nav').show();
  }else{
    if(cusMenu){
      $('nav').show();
    }else{
      $('nav').hide();
    }
  }
});

</script>

</body>
</html>