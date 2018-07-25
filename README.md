<!DOCTYPE hmtl>
<html lang="en">
<head>
    <title>Bootstrap Theme Company</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
    <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet" type="text/css">
    <link href="https://fonts.googleapis.com/css?family=Lato" rel="stylesheet" type="text/css">

    <style>
        body {
            font: 400 15 px Lato, sans-serif;
            line-height: 1.8;
            color: #818181;
        }
        h2 {
            font-size: 24px;
            text-transform: uppercase;
            color: #303030;
            font-weight: 600;
            margin-bottom: 30px;
            font-family: Lato;
        }
        h4 {
            font-size: 19px;
            line-height: 1.375em;
            color: #303030;
            font-weight: 400;
            margin-bottom: 30px;
            font-family: Lato;
        }
        h5 {
            font-size: 16px;
            line-height: 1.375em;
            color: #303030;
            font-weight: 400;
            margin-bottom: 0px;
            font-family: Lato;
        }
        h6 {
            font-size: 12px;
            line-height: 1em;
            color:#818181;
            margin-top: 30px;
            font-family: Lato;
            text-transform: capitalize;
        }
        p {
            font-family: Lato;
        }
        .jumbotron {
            background-color:cadetblue;
            color: #ffffff;
            padding: 100px 25 px;
            font-family: Montserrat, sans-serif;
        }
        .bg-grey {
            background-color: #f6f6f6
        }
        .container-fluid {
            padding: 60px 50px;
        }
        .logo-small {
            color:cadetblue;
            font-size: 50px;
        }
        .logo {
            color:cadetblue;
            font-size: 200px;
        }
        .thumbnail {
            padding: 0 0 15px 0;
            border: none;
            border-radius: 0;
        }
        .thumbnail img {
            /*width: 100%;
            height: 100%; */
            margin-bottom: 10px;
        }
        .carousel-control.right, .carousel-control.left {
            background-image: none;
            color: cadetblue;
        }
        .carousel-indicators li {
            border-color: cadetblue;
        }
        .carousel-indicators li.active {
            background-color: cadetblue;
        }
        .item h4 {
            font-size: 19px;
            line-height: 1.375em;
            font-weight: 400;
            font-style: italic;
            margin: 70px 0;
        }
        .item span {
            font-style: normal;
        }
        .navbar {
            margin-bottom: 0;
            background-color: cadetblue;
            z-index: 9999;
            border: 0;
            font-size: 12px !important;
            line-height: 1.42857143 !important;
            letter-spacing: 4px;
            border-radius: 0;
            font-family: Montserrat, sans-serif;
        }
        .navbar li a, .navbar .navbar-brand {
            color: #fff !important;
        }
        .navbar-nav li a:hover, .navbar-nav li.active a {
            color:cadetblue !important;
            background-color: #fff !important;
        }
        .navbar-default .navbar-toggle {
            border-color: transparent;
            color:#fff !important;
        }
        footer.glyphicon {
            font-size: 20px;
            margin-bottom: 20px;
            color: cadetblue;
        }
        .slideanim {visibility: hidden;}
        .slide {
            animation: slide;
            -webkit-animation-name: slide;
            animation-duration: 1s;
            -webkit-animation-duration: 1s;
            visibility: visible;
        }
        .userlogo {
            align-content: center;
            align-items: center;
            
        }
        @media screen and (max-width: 768px) {
            .col-sm-4 {
                text-align: center;
                margin: 25px 0;
            }
        }
        @keyframes slide {
            0% {
                opacity: 0;
                transform: translateY(70%);
            }
            100% {
                opacity: 1;
                transform: translateY(0%);
            }
        }
        @-webkit-keyframes slide {
            0% {
                opacity: 0;
                -webkit-transform: translateY(70%);
            }
            100% {
                opacity: 1;
                -webkit-transform: translateY(0%);
            }
        }

    </style>

</head>

<body id="myPage" data-spy="scroll" data-target="#myNav">

    <nav class="navbar navbar-default navbar-fixed-top">
                        <div class="container">
                          <div class="navbar-header">
                            <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
                              <span class="icon-bar"></span>
                              <span class="icon-bar"></span>
                              <span class="icon-bar"></span>                        
                            </button>
                            <a class="navbar-brand" href="#myPage">Logo</a>
                          </div>
                          <div class="collapse navbar-collapse" id="myNavbar">
                            <ul class="nav navbar-nav navbar-right">
                              <li><a href="#about">ABOUT</a></li>
                              <li><a href="#services">SERVICES</a></li>
                              <li><a href="#portfolio">PORTFOLIO</a></li>
                              <li><a href="#contact">CONTACT</a></li>
                            </ul>
                          </div>
                        </div>
    </nav>
  
    <div class="jumbotron text-center">
        <h1>Hannah Walsh</h1>
        <p>Find out what I've accomplished</p>

        <button class="btn btn-default btn-md">Download Resume</button>
    </div>

    <!-- Container (about section) -->
    <div id="about" class="container-fluid">
       <div class="row">
            <div class="col-sm-8">
                <h2>About Me</h2>
                <p>My name is Hannah Walsh and I am a Technology Consultant 
                    in Dallas, TX. I graduated from Baylor University in May 
                    2018 with a Bachelor's of Business Administration in 
                    Baylor Business Fellows, Management Information Systems, 
                    and Marketing. I also received a minor in Italian. I look 
                    forward to discovering and working with new technologies 
                    as I begin my career.</p>
            </div>
            <div class="col-sm-4">
                <span id="userlogo" class="glyphicon glyphicon-user logo center"></span>
            </div>
        </div>
    </div>

    <!-- Container (education section) -->
    <div id="education" class="container-fluid bg-grey">
        <div class="row slideanim">
            <div class="col-sm-4">
                <span class="glyphicon glyphicon-education logo"></span>
            </div>
            <div class="col-sm-8">
                <h2>Education</h2>
                <h5><strong>Bachelor of Business Administration</strong>  - Baylor University 2018</h5>
                <p>Baylor Business Fellows, Marketing, and Management Infromation Systems</p>
                <h5><strong>Study Abroad in Rome</strong>  - John Cabot University 2017</h5>
                <h5><strong>General Education</strong>  - Plano Senior High School 2014</h5>
                
            </div>
        </div>
    </div>

    <!-- Container (work experience section) -->
    <div id="work" class="container-fluid">
            <div class="row slideanim">
                <div class="col-sm-8">
                    <h2>Work Experience</h2>
                    <h6>TECHNOLOGY CONSULTANT</h6>
                    <h5><strong>Credera</strong> July 2018 - Present </h5>
                    <p>Technology consultant in the Microsoft Solutions Practice</p>
                    
                    <h6>INTERACTIVE MARKETING INTERN</h6>
                    <h5><strong>Lennox</strong>  May 2016 - August 2017 </h5>
                    <p> I led the creation of MyLennox, an internal initiative set to increase 
                        employee advocacy with brand ambassadors. I uploaded all program content to MyLennox, collaborated with the 
                        graphic design team to create a seamless look on desktop and mobile, 
                        and orchestrated a two-day training event for brand ambassadors. 
                        I completed a competitive analysis regarding social media in 
                        the industry and presented findings to executives and other 
                        employees. I wrote and published 3 Lennox Social Media Program 
                        newsletters and 3 mid-month emails. I updated and managed dealer 
                        locator database with over 10,000 Lennox dealers. I responded to 
                        150 tweets through social listening and had a 10% response rate, 
                        which directly led to customer leads. I managed negative customer 
                        reviews to increase customer satisfaction. I also converted 10 
                        dealers to the Lennox Dealer Social Media Program.</p>
                    
                </div>
                <div class="col-sm-4">
                        <span class="glyphicon glyphicon-file logo"></span>
                    </div>
            </div>
        </div>

    <!-- Container (services) -->
    <div id="services" class="container-fluid text-center bg-grey">
        <h2>SKILLS</h2>
        <br>
        <div class="row slideanim">
            <div class="col-sm-4">
                    <span class="glyphicon glyphicon-wrench logo-small"></span>
                    <h4>LANGUAGES</h4>
                    <p>HTML<br>Java<br>Visual Basic<br>SQL<br>C#<br>jQuery<br>CSS</p>
            </div>
            <div class="col-sm-4">
                    <span class="glyphicon glyphicon-briefcase logo-small"></span>
                    <h4>TECHNOLOGIES</h4>
                    <p>Relational Databases<br>SAP ERP<br>Photoshop<br>Tableau<br>Visual Studio</p>
            </div>
            <div class="col-sm-4">
                    <span class="glyphicon glyphicon-thumbs-up logo-small"></span>
                    <h4>INTERPERSONAL SKILLS</h4>
                    <p>Teamwork<br>Time Management<br>Communication<br>Leadership<br>Public Speaking<br>Reliable<br>Problem Solving</p>
            </div>
        </div>
        <br>
        <br>
        <div class="row slideanim">
            <div class="col-sm-4">
                    <span class="glyphicon glyphicon-headphones logo-small"></span>
                    <h4>LANGUAGES</h4>
                    <p>English<br>Italian</p>
            </div>
            <div class="col-sm-4">
                    <span class="glyphicon glyphicon-certificate logo-small"></span>
                    <h4>AWARDS</h4>
                    <p><b>Baylor University Dean's List</b><br>Fall 2014, Spring 2015, Fall 2015, Spring 2016, Fall 2016, Fall 2017, and Spring 2018</p>
            </div>
            <div class="col-sm-4">
                    <span class="glyphicon glyphicon-wrench logo-small"></span>
                    <h4>TECHNOLOGIES</h4>
                    <p>HTML<br>Java<br>Visual Basic<br>SQL<br>C#<br>jQuery<br>CSS</p>
            </div>
        </div>
    </div>

    <div id="myCarousel" class="carousel slide text-center" data-ride="carousel">
        <h2 >Endorsements</h2>
        <!-- Indicators -->
        <ol class="carousel-indicators">
            <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
            <li data-target="#myCarousel" data-slide-to="1"></li>
            <li data-target="#myCarousel" data-slide-to="2"></li>
        </ol>

        <!-- Wrapper for slides -->
        <div class="carousel-inner" role="listbox">
            <div class="item active">
                <h4>"Hannah is the best!"<br><span>Trevor Anderson</span></h4>
            </div>
            <div class="item">
                <h4>"One word...Wow!"<br><span>Trevor Anderson</span></h4>
            </div>
            <div class="item">
                <h4>"Could I... BE any more happy with Hannah?"<br><span>Chandler Bing</span></h4>
            </div>    
        </div>

        <!-- Left and right controls -->
        <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
            <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        
        <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
                <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
            </a>
    </div>

    <div id="contact" class="container-fluid bg-grey">
        <h2 class="text-center">CONTACT</h2>
        <div class="row slideanim">
            <div class="col-sm-5">
                <p>Have a question? Feel free to contact me!</p>
                <p><span class="glyphicon glyphicon-map-marker"></span> Dallas, TX</p>
                <p><span class="glyphicon glyphicon-phone"></span> (214)684-0100</p>
                <p><span class="glyphicon glyphicon-envelope"></span> hannah.walsh@credera.com</p> 
                <p><span class="glyphicon glyphicon-link"></span> <a href="http://www.linkedin.com/in/hannahwalsh2">View my LinkedIn Profile<a></a></ad></p>                
            </div>

            <div class="col-sm-7">
                <div class="row">
                    <div class="col-sm-6 form-group">
                        <input class="form-control" id="name" name="name" placeholder="Name" type="text" required>
                    </div>
                    <div class="col-sm-6 form-group">
                            <input class="form-control" id="email" name="email" placeholder="Email" type="email" required>
                    </div>
                </div>

                <textarea class="form-control" id="comments" name="comments" placeholder="Comment" rows="5"></textarea>
                <br>
                    <div class="row">
                        <div class="col-sm-12 form-group">
                            <button class="btn btn-default pull-right" type="submit">Send</button>
                        </div>
                    </div>
            </div>
        </div>
    </div>

    <footer class="container-fluid text-center">
        <a href="#myPage" title="To Top">
            <span class="glyphicon glyphicon-chevron-up"></span>
        </a><br>
        <p>Theme made by Hannah Walsh</p>
    </footer>

</div>
    <script> 
    $(document).ready(function(){
        // Add smooth scrolling to all links in navbar +  footer link
        $(".navbar a, footer a[href='#myPage']").on('click', function(event) {
            // Make sure this.hash has a value before overriding default
            if (this.hash !== "") {
                event.preventDefault();

                var hash = this.hash;

                // Use the animate method()
                $('html, body').animate({
                    scrollTop: $(hash).offset().top}, 900, function(){
                        // Add hash to URL when done scrolling
                        window.location.hash = hash;
                    });
            }
        });

        $(window).scroll(function() {
            $(".slideanim").each(function(){
                var pos = $(this).offset().top;

                var winTop = $(window).scrollTop();
                if (pos < winTop +  600) {
                    $(this).addClass("slide");
                }
            });
        });
    })
    </script>


</body>
</html>
