# my-first-website
my first website

<!DOCTYPE html>
<html>

<head>
    <title></title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css">
    <script src="https://cdn.jsdelivr.net/npm/jquery@3.7.1/dist/jquery.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer"
    />
    <script src="https://kit.fontawesome.com/yourcode.js" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js" integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.min.js" integrity="sha384-0pUGZvbkm6XF6gxjEnlmuGrJXVbNuzT9qBBavbLwCsOGabYfZo0T0to5eqruptLy" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
   <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

    <style type="text/css">
      #bg {
            background-image: url(image-2.avif);
            background-repeat: no-repeat;
            background-size: 100% 100%;
            height: 650px;
            width: 100%;
        }

        #bg2 {
            background-image: url(about-1.jpg);
            background-repeat: no-repeat;
            background-size: 100% 100%;
            height: 550px;
            width: 100%;
            opacity: 2;
            background-attachment: fixed;
        }

        #about_bg {
            background-repeat: no-repeat;
            background-size: 100% 100%;
            height: 392px;
            width: 512px;
        }

        #about_bg-1 {
            background-repeat: no-repeat;
            background-size: 100% 100%;
            height: 392px;
            width: 392px;
        }

        #about_div {
            transform: scale(1.0);
            transition: 0.5s;
        }

        #about_div:hover .about_sq {
            transform: scale(1.03);
        }

        #about_div .about_sq {
            transform: scale(0.9);
            transition: 0.5s;
        }

        #about_div:hover {
            transform: scale(1.03);
        }

        /* Make the image fully responsive */

        .carousel-inner img {
            width: 100%;
            height: 100%;
        }

        #lis {
            height: 15px;
            width: 15px;
            border-radius: 50%;
        }

        .heading
        {
            font-family: Century751 SeBd BT;
            font-weight: bold;
            font-size: 35px;
        }
        #why_us1
        {
                        font-family: Century751 SeBd BT;

        }

        #sec:hover
        {
            background-color: red;
            height: 200p;
        }

        .why1
        {
            position: absolute;
            top: 160px;
            height: 280px;
            background-color: #1A1814;
        }

        .why11
        {
            position: absolute;
            font-weight: bold;
            color:#CDA45E; 
            top: 60px;
            left: 30px;
        }

        .why111
        {
            position: absolute;
            left: 30px;
            top: 110px;
            color: #AAAAAA;
        }

        .why_11
        {
                       font-weight: bold;
 
        }

        .why1:hover
        {
            background-color: #CDA45E;
        }

          .why1:hover .why_11
        {
                          color: white;   
        
        }

                 
         .why_111
         {
            position: absolute;
            font-family: Century751 SeBd BT;
            color: #AAAAAA; 
            top: 110px;
            left: 30px;
         }

           .why1:hover #why_us1
        {
           color: white;   
        
        }

        .why_1111
        {
            position: absolute;
            left: 30px;
            top: 170px;
            color: #AAAAAA;
            font-size: 16px;
            font-family: Arial; 
        }

            .why1:hover .why_1111
        {
           color: white;   
        
        }


        .why21
        {
          position: absolute;
          top: 160px;
          left: 500px;
          height: 280px;
          background-color: #1A1814;
        }
          #div1
        {
           position: absolute;
           left: 30px;
           top: 60px;
           color:#CDA45E;
           font-weight: bold;
           left: 30px;
        }


        #div2
        {
            position: absolute;
           left: 30px;
           top: 110px;
           color: #AAAAAA; 
                   font-family: Century751 SeBd BT;

        }

     #div3
     {
           position: absolute;
           left: 30px;
           top: 170px;
           color: #AAAAAA; 
           font-family: Arial;
           font-size: 16px;
           width: 310px;
     }

     .why21:hover
     {
        background-color: #CDA45E;
     }

      .why21:hover #div1
     {
        color: white;
     }

      .why21:hover #div2
     {
        color: white;
     }

      .why21:hover #div3    
     {
        color: white;
     }

     .why31
     {
        position: absolute;
        top: 160px;
        left: 880px;
        height: 280px;
        background-color: #1A1814;
     }

     .div4
     {
        position: absolute;
        left: 30px;
        top: 110px;
        color: #AAAAAA;
        font-family: Century751 SeBd BT;
     }

     .div5
     {
        position: absolute;
        left: 30px;
        top: 170px;
        color: #AAAAAA;
        font-size: 17px;
        font-family: Arial;
     }

     .div6
     {
        position: absolute;
        left: 30px;
        top: 60px;
        color:#CDA45E;
        font-weight: bold;
     }

     .why31:hover
     {
                background-color: #CDA45E;
     }

     .why31:hover .div4,.div5,.div6
     { 
                color: white;
     }

     .why201
                {
                    position: absolute;
                    top: 160px;
                    height: 280px;
                    background-color: #1A1814;
                }

                .why202
                {
                    position: absolute;
                    left: 30px;
                    top: 60px;
                    color:#CDA45E;
                    font-weight: 700;
                }
                .why203
                {
                    position: absolute;
                    left: 30px;
                    top: 110px;
                    color: #AAAAAA;
                     font-family: Century751 SeBd BT;
                }
                .why204
                {
                    position: absolute;
                    left: 30px;
                    top: 170px;
                    color: #AAAAAA;font-size: 15px;
                }

                 .why201:hover
                 {
                      background-color: #CDA45E;
                 }

                 .why201:hover .why202,.why203,.why204  
                 {
                    color: white;
                 }

                 .why205
                 {
                    position: absolute;
                    top: 460px;
                    height: 280px;
                    background-color: #1A1814;
                 }

                 .why206
                {
                    position: absolute;
                    left: 30px;
                    top: 60px;
                    color:#CDA45E;
                    font-weight: 700;
                }

                .why207
                {
                    position: absolute;
                    left: 30px;
                    top: 110px;
                    color: #AAAAAA;
                     font-family: Century751 SeBd BT;
                }

                .why208
                {
                    position: absolute;
                    left: 30px;
                    top: 170px;
                    color: #AAAAAA;
                    font-size: 16px;
                }

                .why205:hover
                {
                    background-color: #CDA45E;
                 
                }

                 .why205:hover .why206,.why207,.why208  
                 {
                    color: white;
                 }

                  .why209
                 {
                    position: absolute;
                    top: 760px;
                    height: 280px;
                    background-color: #1A1814;
                 }

                 .why210
                {
                    position: absolute;
                    left: 30px;
                    top: 60px;
                    color:#CDA45E;
                    font-weight: 700;
                }

                .why211
                {
                    position: absolute;
                    left: 30px;
                    top: 110px;
                    color: #AAAAAA;
                     font-family: Century751 SeBd BT;
                }

                .why212
                {
                    position: absolute;
                    left: 30px;
                    top: 170px;
                    color: #AAAAAA;
                    font-size: 16px;
                }

                .why209:hover
                {
                    background-color: #CDA45E;
                 
                }

                 .why209:hover .why210,.why211,.why212 
                 {
                    color: white;
                 }

                   .img1
    {
        width: 100%;height: 100%;background-size: 100% 100%;border-right:3px solid #454035;border-bottom: 3px solid #454035;transform: scale(1.0);overflow: hidden;transition-duration: 0.4s;

    }

    .img1:hover
    {
        transform: scale(1.06);
        overflow: hidden;

    }

     .img2
    {
        width: 100%;
        height: 100%;
        background-size: 100% 100%;
        border-right:3px solid #454035;
        border-bottom: 3px solid #454035;
        transition-duration: 0.5s;
    }

    .img2:hover
    {
        transform: scale(1.06);
        overflow: hidden;

    }

#h1
    {
        position: absolute;
        top: 300px;
        left: 70px;
        color: #0C0B09;

    }

    #h2
    {
        position: absolute;
        top: 330px;
        left: 110px;
        color: white;
        font-style: italic;
        font-size: 14px;
        color: #0C0B09;

    }
    .che
    {
        height: 85%;
        width: 85%;
        background-size: 100% 100%;
        transform: scale(1.2);
        /*overflow: hidden;*/
        position: absolute;
        transition: 0.50s;
        margin-right: 5px;
        /*left: -100px;*/
    }

    .imgg
    {
        height: 85%;width: 85%;background-size: 100% 100%;transform: scale(1.2);overflow: hidden; 

    }

    .imgg:hover
    {
       filter: brightness(0.5);
    }

   .chefs:hover #h1
    {
        top: 180px;
        color: white;
        z-index: 1;
 
    }

    .chefs:hover #h1
    {
        transition-duration: 0.5s;
    }

     .chefs:hover #h2
    {
        top: 208px;
        color: white;
        z-index: 1;
 
    }

    .chefs:hover #h2
    {
        transition-duration: 0.5s;
    }
    
    .icon1
    {
         color: #0C0B09;position: absolute;top: 330px;left: 75px;font-size: 21px;
    }

    .chefs:hover .icon1
    {
         top: 235px;
        color: white;
        z-index: 1;
    }

    .chefs:hover .icon1
    {
        transition-duration: 0.5s;
    }

    .icon2
    {
        color: #0C0B09;position: absolute;top: 330px;left: 115px;font-size: 21px;"
    }
    .chefs:hover .icon2
    {
         top: 235px;
        color: white;
        z-index: 1;
    }

    .chefs:hover .icon2
    {
        transition-duration: 0.5s;
    }
    .icon3
    {
        color:  #0C0B09;position: absolute;top: 380px;left: 155px;font-size: 21px;
    }
    .chefs:hover .icon3
    {
         top: 235px;
        color: white;
        z-index: 1;
    }

    .chefs:hover .icon3
    {
        transition-duration: 0.5s;
    }
   .icon4
   {
    color: #0C0B09;position: absolute;top: 380px;left: 195px;font-size: 21px;
   }
   .chefs:hover .icon4
    {
         top: 235px;
        color: white;
        z-index: 1;
    }

    .chefs:hover .icon4
    {
        transition-duration: 0.5s;
    }

 /*card 2*/
    .imgg2
    {
        height: 85%;width: 85%;background-size: 100% 100%;transform: scale(1.2);overflow: hidden;
    }
    .imgg2:hover
    {
       filter: brightness(0.5);
    }
     #h3
    {
        position: absolute;
        top: 300px;
        left: 80px;
        color: #0C0B09;
        font-size: 22px;
    }

    #h33
    {
        position: absolute;
        top: 330px;
        left: 110px;
        color: white;
        font-style: italic;
        font-size: 14px;
        color: #0C0B09;

    }
    .chefs2:hover #h3
    {
        top: 180px;
        color: white;
        z-index: 1;
 
    }

    .chefs2:hover #h3
    {
        transition-duration: 0.5s;
    }
     .chefs2:hover #h33
    {
        top: 208px;
        color: white;
        z-index: 1;
        left: 130px;
    }

    .chefs2:hover #h33
    {
        transition-duration: 0.5s;
    }
     .icon11
    {
         color: #0C0B09;position: absolute;top: 330px;left: 75px;font-size: 21px;
    }

    .chefs2:hover .icon11
    {
         top: 235px;
        color: white;
        z-index: 1;
    }

    .chefs2:hover .icon11
    {
        transition-duration: 0.5s;
    }

    .icon22
    {
        color: #0C0B09;position: absolute;top: 330px;left: 115px;font-size: 21px;"
    }
    .chefs2:hover .icon22
    {
         top: 235px;
        color: white;
        z-index: 1;
    }

    .chefs2:hover .icon22
    {
        transition-duration: 0.5s;
    }
    .icon33
    {
        color:  #0C0B09;position: absolute;top: 380px;left: 155px;font-size: 21px;
    }
    .chefs2:hover .icon33
    {
         top: 235px;
        color: white;
        z-index: 1;
    }

    .chefs2:hover .icon33
    {
        transition-duration: 0.5s;
    }
   .icon44
   {
    color: #0C0B09;position: absolute;top: 380px;left: 195px;font-size: 21px;
   }
   .chefs2:hover .icon44
    {
         top: 235px;
        color: white;
        z-index: 1;
    }

    .chefs2:hover .icon44
    {
        transition-duration: 0.5s;
    }

    /*card 3*/
    .imgg3
    {
        height: 85%;width: 85%;background-size: 100% 100%;transform: scale(1.2);overflow: hidden;
    }
    .imgg3:hover
    {
       filter: brightness(0.5);
    }
     #h4
    {
        position: absolute;
        top: 300px;
        left: 60px;
        color: #0C0B09;
        font-size: 22px;
    }

    #h44
    {
        position: absolute;
        top: 330px;
        left: 110px;
        color: white;
        font-style: italic;
        font-size: 16px;
        color: #0C0B09;

    }
    .chefs3:hover #h4
    {
        top: 180px;
        color: white;
        z-index: 1;
 
    }

    .chefs3:hover #h4
    {
        transition-duration: 0.5s;
    }
     .chefs3:hover #h44
    {
        top: 208px;
        color: white;
        z-index: 1;
        left: 130px;
    }

    .chefs3:hover #h44
    {
        transition-duration: 0.5s;
    }
    .icon111
    {
         color: #0C0B09;position: absolute;top: 330px;left: 75px;font-size: 21px;
    }

    .chefs3:hover .icon111
    {
         top: 235px;
        color: white;
        z-index: 1;
    }

    .chefs3:hover .icon111
    {
        transition-duration: 0.5s;
    }

    .icon222
    {
        color: #0C0B09;position: absolute;top: 330px;left: 115px;font-size: 21px;"
    }
    .chefs3:hover .icon222
    {
         top: 235px;
        color: white;
        z-index: 1;
    }

    .chefs3:hover .icon222
    {
        transition-duration: 0.5s;
    }
    .icon333
    {
        color:  #0C0B09;position: absolute;top: 380px;left: 155px;font-size: 21px;
    }
    .chefs3:hover .icon333
    {
         top: 235px;
        color: white;
        z-index: 1;
    }

    .chefs3:hover .icon333
    {
        transition-duration: 0.5s;
    }
   .icon444
   {
    color: #0C0B09;position: absolute;top: 380px;left: 195px;font-size: 21px;
   }
   .chefs3:hover .icon444
    {
         top: 235px;
        color: white;
        z-index: 1;
    }

    .chefs3:hover .icon444
    {
        transition-duration: 0.5s;
    }
    </style>
</head>

<body>
    <section name="navbar_start">
        <div id="bg">
            <div class="container-fluid">
                <nav class="navbar navbar-expand-sm  navbar-dark fixed-top" style="background-color: rgba(0,0,0,0.6);">
                    <a class="navbar-brand offset-1" href="#" style="font-size: 30px;font-weight: 500;opacity: 0.9;">RESTAURANTLY</a>
                    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
                                      <span class="navbar-toggler-icon"></span>
                                  </button>

                    <div class="collapse navbar-collapse" id="collapsibleNavbar">
                        <usl class="navbar-nav">
                            <li class="nav-item">
                                <a class="nav-link text-white mr-4" href="home.html">Home</a>
                            </li>

                            <li class="nav-item">
                                <a class="nav-link text-white mr-4" href="about.html">About</a>
                            </li>

                            <li class="nav-item">
                                <a class="nav-link text-white mr-4" href="#">Menu</a>
                            </li>

                            <li class="nav-item">
                                <a class="nav-link text-white mr-4" href="#">Specials</a>
                            </li>

                            <li class="nav-item">
                                <a class="nav-link text-white mr-4" href="#">Chefs</a>
                            </li>

                            <li class="nav-item">
                                <a class="nav-link text-white mr-4" href="#">Gallery</a>
                            </li>

                            <div class="dropdown d-md-block d-none">
                                <button type="button" class="btn  dropdown-toggle text-white" data-toggle="dropdown"> Drop Down</button>
                                <div class="dropdown-menu">
                                    <a class="dropdown-item" href="#">Link 1</a>
                                    <a class="dropdown-item" href="#">Link 2</a>
                                    <a class="dropdown-item" href="#">Link 3</a>
                                </div>
                            </div>

                            <li class="nav-item">
                                <a class="nav-link text-white mr-4" href="#">Contact</a>
                            </li>

                            </ul>

                            <button class="btn mt-1  d-md-block d-none" style="border-radius: 60px;height: 35px;width: 160px;border: 2px solid #CDA45E;color: white;font-family: Bell Gothic Std Black;font-size: 12px;letter-spacing: 1px;padding-top: 5px;"><p style="margin-top: 3px;">BOOK A TABLE </p> </button>

                    </div>
                </nav>

                <div class="row">
                    <div class="col-md-12 ">
                        <p data-aos="zoom-in" data-aos-duration="2000" class="text-white d-md-block d-none " style="font-size: 55px;font-weight: bold;position: absolute;top: 270PX;left: 120PX;">Welcome to <span style="color: #C39D5E">Restaurantly</span></p>

                        <p data-aos="zoom-in" data-aos-duration="1000" class="text-white d-md-none d-block " style="font-size: 32px;font-weight: bolder;position: absolute;top: 260PX;left: 60PX;">Welcome to <span style="color: #C39D5E">Restaurantly</span></p>


                        <p data-aos="zoom-in" data-aos-duration="2000" class="text-white d-md-block d-none " style="font-size: 22px;position: absolute;top: 345PX;left: 120PX;font-family: Century751 SeBd BT;">Delivering great food for more than 18 years!
                        </p>

                        <p data-aos="zoom-in" data-aos-duration="1000" class="text-white d-md-none d-block " style="font-size: 18px;position: absolute;top: 305PX;left: 55PX;font-family: Century751 SeBd BT;">Delivering great food for more than 18 years!
                        </p>

                    </div>
                </div>

                <div class="row">
                    <div class="offset-1  col-md-5">
                        <button data-aos="zoom-in" data-aos-duration="2000" class="btn  text-white d-md-block d-none" style="position: absolute;top: 400px;left: px;border-radius: 20px;border: 2px solid #CDA45E;color: white;font-family: Bell Gothic Std Black;font-size: 12px;letter-spacing: 2px;padding: 10px;width: 140px;"><a href="" class="text-white">OUE MENU</a></button>

                        <button data-aos="zoom-in" data-aos-duration="1000" class="btn btn-outline-warning text-white d-md-none d-block btn-sm" style="position: absolute;top: 350px;left: 50px;border-radius: 20px;border: 2px solid #CDA45E;color: white;font-family: Bell Gothic Std Black;font-size: 12px;letter-spacing: 2px;padding: 10px;width: 140px;"><a href="" class="text-white">OUE MENU</a></button>

                        <button data-aos="zoom-in" data-aos-duration="2000" class="btn btn-outline-warning text-white  d-md-block d-none" style="position: absolute;top: 400px;left: 180px;border-radius: 20px;border: 2px solid #CDA45E;color: white;font-family: Bell Gothic Std Black;font-size: 12px;letter-spacing: 2px;padding: 10px;width: 150px;"><a href="" class="text-white">BOOK A TABLE</a></button>

                        <button data-aos="zoom-in" data-aos-duration="1000" class="btn btn-outline-warning text-white d-md-none d-block btn-sm" style="position: absolute;top: 350px;left: 210px;border-radius: 20px;border-radius: 20px;border: 2px solid #CDA45E;color: white;font-family: Bell Gothic Std Black;font-size: 12px;letter-spacing: 2px;padding: 10px;width: 140px;"><a href="" class="text-white">BOOK A TABLE</a></button>
                    </div>
                </div>

            </div>
        </div>
    </section>

<section name="about_start">
        <div id="bg2">
            <div class="container-fluid">
                <div class="row">
                    <div class="col-md-12" >
                        <div class="row ">

                            <div class="offset-1 col-md-5" style="position: relative;">

                                <h3 class="text-white d-md-block d-none" data-aos="fade-up"
     data-aos-duration="2000" style="position: absolute;top: 80px;">Voluptatem dignissimos provident quasi corporis voluptates sit assumenda.</h3>

                                <p class="text-white d-md-block d-none" data-aos="fade-up"
     data-aos-duration="2000" style="position: absolute;top: 160px;font-style: italic; font-size: 17px;"> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>

                                <div class="d-md-block d-none" data-aos="fade-up"
     data-aos-duration="2000" style="position: absolute;top: 230px; font-size: 22px;color: #CDA45E;"><i class="fa-regular fa-circle-check mr-2 "></i><span class="text-white" style="font-size: 18px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat.</span></div>
                            </div>
                            v
                            <div class="d-md-block d-none" data-aos="fade-up"
     data-aos-duration="2000" style="position: absolute;top: 270px; left: 127px; font-size: 22px;color: #CDA45E;"><i class="fa-regular fa-circle-check mr-2 "></i><span class="text-white" style="font-size: 18px;">Duis aute irure dolor in reprehenderit in voluptate velit.</span></div>

                            <div class="d-md-block d-none" data-aos="fade-up"
     data-aos-duration="2000" style="position: absolute;top: 302px; left: 126px; font-size: 22px;color: #CDA45E;width: 580px;line-height: 22px;">
                                </i><span class="text-white" style="font-size: 18px;">irure dolor in reprehenderit in voluptate trideta storacalaperda mastiro dolore eu fugiat nulla pariatur.</span></div>

                            <div class="d-md-block d-none" data-aos="fade-up"
     data-aos-duration="2000" style="position: absolute;top: 370px; left: 126px; font-size: 22px;color: #CDA45E;width: 580px;line-height: 22px;">
                                </i><span class="text-white" style="font-size: 18px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum</span></div>

                            <div class="offset-1 col-md-4  d-md-block d-none" data-aos="zoom-in" data-aos-duration="2000">
                                <div id="about_div" style="height: 400px;width: 520px;background-color: white;position: absolute;top: 70px;left: -60px;border: 4px solid #5B5249;">
                                    <img src="about-bg.jpg" id="about_bg">
                                    <div class="about_sq" style="height: 70px;width: 70px;position: absolute;top: 15px;left: 15px;border-left: 5px solid #CDA45E;border-top: 5px solid #CDA45E;"></div>

                                    <div class="about_sq" style="height: 70px;width: 70px;position: absolute;top: 310px;left: 425px;border-bottom: 5px solid #CDA45E;border-right: 5px solid #CDA45E;"></div>


                                </div>
                            </div>

                            <div data-aos="zoom-in" data-aos-duration="2000" class="  col-10 d-md-none d-block" style="width: 60%;" >
                                <div id="about_div-1" style="height: 400px;width: 400px;background-color: white;position: absolute;top: 50px;left: 40px;border: 4px solid #5B5249;">
                                    <img src="about-bg.jpg" id="about_bg-1">
                                    <div class="about_sq" style="height: 70px;width: 70px;position: absolute;top: 20px;left: 20px;border-left: 5px solid #CDA45E;border-top: 5px solid #CDA45E;"></div>

                                    <div class="about_sq" style="height: 70px;width: 70px;position: absolute;top: 305px;left: 300px;border-bottom: 5px solid #CDA45E;border-right: 5px solid #CDA45E;"></div>


                                </div>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </section>

    <div   class="container-fluid d-md-none d-block" style="background-image: url(about-1.jpg);background-repeat: no-repeat;background-size: 100% 100%;height: 450px;width: 100%;">
        <div class="row">
            <div class="col-12 d-md-none d-block" >
                <h4 class="text-white" style="position: absolute;top: -60px;">Voluptatem dignissimos provident quasi corporis voluptates sit assumenda.</h4>
            </div>
        </div>

        <div class="row">
            <div class="col-12 d-md-none d-block">
                <p class="text-white" style="position: absolute;top: 12px;font-style: italic; font-size: 16px;"> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            </div>
        </div>

        <div class="row">
            <div class="col-12 d-md-none d-block">
                <div style="position: absolute;top: 80px; font-size: 23px;color: #CDA45E;"><i class="fa-regular fa-circle-check mr-2 "></i><span class="text-white" style="font-size: 16px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat.</span></div>

            </div>
        </div>

        <div class="row">
            <div class="col-12 d-md-none d-block">
                <div style="position: absolute;top: 125px; font-size: 23px;color: #CDA45E;"><i class="fa-regular fa-circle-check mr-2 "></i><span class="text-white" style="font-size: 16px;">Duis aute irure dolor in reprehenderit in voluptate velit.</span></div>
            </div>
        </div>

        <div class="row">
            <div class="col-12 d-md-none d-block">
                <div style="position: absolute;top: 170px; font-size: 22px;color: #CDA45E;line-height: 22px;"><i class="fa-regular fa-circle-check mr-2 "></i><span class="text-white" style="font-size: 16px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate trideta storacalaperda mastiro dolore eu fugiat nulla pariatur.</span></div>
            </div>
        </div>

        <div class="row">
            <div class="col-12 d-md-none d-block">
                <p class="text-white" style="position: absolute;top: 270px; font-size: 16px;"> Ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt
                    mollit anim id est laborum</p>
            </div>
        </div>

    </div>
    </section>

      <section name="why_us ">
        <div class="container-fluid d-md-block d-none " style="background-color: #0C0B09;height: 500px;width: 100%;position: relative;">

            <div class="row">
                <div class="col-md-12">
                    <div data-aos-duration="2000"  data-aos="fade-up" style="color: #AAAAAA;position: absolute;top: 50px;left: 120px;font-weight: 600;letter-spacing: 2px;">WHY US</div>
                    <p data-aos-duration="2000"  data-aos="fade-up" style="color: #AAAAAA;position: absolute;top: 43px;left: 200px;opacity: 0.4">_________________</p>
                </div>
            </div>

            <div class="row">
                <div class="col-md-12">
                    <p data-aos-duration="2000"  data-aos="fade-up" class="heading" style="color: #CDA45E;position: absolute;top: 80px;left: 120px;font-weight: 600;">Why Choose Our Restaurant</p>
                </div>
            </div>

            <div class="container-fluid">
                <div class="row">
                    <div class="col-md-12"  id="sec">
                        <div class="row">
                            <div  class="offset-1 col-md-3 why1" data-aos="zoom-in" data-aos-duration="1000">

                                <div class="row">
                                    <div class="col-md-12 why11">
                                        <h3 class="why_11">01</h3>
                                    </div>
                                </div>

                                <div class="row">
                                    <div class="col-md-12 why111">
                                        <h3 style="" id="why_us1">Lorem Ipsum</h3>
                                    </div>
                                </div>

                                <div class="row">
                                    <div class="col-md-12">
                                        <h6 class="why_1111">Ulamco laboris nisi ut aliquip ex ea commodo consequat. Et consectetur ducimus vero placeat</h6>
                                    </div>
                                </div>
                            </div>

                            <div class=" col-md-3 why21" data-aos="zoom-in" data-aos-duration="1000">
                                <div class="row">
                                    <div class="col-md-12">
                                        <h3 id="div1">02</h3>
                                    </div>
                                </div>

                                <div class="row">
                                    <div class="col-md-12">
                                        <h3 id="div2">Repellat Nihil</h3>
                                    </div>
                                </div>

                                <div class="row" id="div3">Dolorem est fugiat occaecati voluptate velit esse. Dicta veritatis dolor quod et vel dire leno para dest</h6>
                                    </div>
                                </div>
                            </div>
                            <div class="col-md-3 why31" data-aos="zoom-in" data-aos-duration="1000">
                                <div class="row">
                                    <div class="col-md-12">
                                        <h3 class="div6">03</h3>
                                    </div>
                                </div>

                                <div class="row">
                                    <div class="col-md-12">
                                        <h3 class="div4">Ad ad velit qui</h3>
                                    </div>
                                </div>

                                <div class="row">
                                    <div class="col-md-12">
                                        <h6 class="div5">Molestiae officiis omnis illo asperiores. Aut doloribus vitae sunt debitis quo vel nam quis</h6>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </section>

    <section name="why_us_resp ">
        <div class="container-fluid d-md-none d-block" style="background-color: #0C0B09;height: 1100px;width: 100%;position: relative;">

            <div class="row">
                <div class="col-12">
                    <div data-aos-duration="1000"  data-aos="fade-up"  style="color: #AAAAAA;position: absolute;top: 50px;left: 20px;font-weight: 600;letter-spacing: 2px;">WHY US</div>
                    <p data-aos-duration="1000"  data-aos="fade-up" style="color: #AAAAAA;position: absolute;top: 43px;left: 100px;opacity: 0.4">_________________</p>
                </div>
            </div>

            <div class="row">
                <div class="col-8 mt-2">
                    <h2 data-aos-duration="1000"  data-aos="fade-up" style="color: #CDA45E;position: absolute;top: 80px;left: 20px;font-family: Century751 SeBd BT;">Why Choose Our Restaurant</h2>
                </div>
            </div>

            <div class="container-fluid mt-4 " data-aos="zoom-in" data-aos-duration="1500">
                <div class="row">
                    <div class="col-12">
                        <div class="row">
                            <div class=" offset-1 col-10 why201">

                                <div class="row">
                                    <div class="col-12">
                                        <h3 class="why202">01</h3>
                                    </div>
                                </div>

                                <div class="row">
                                    <div class="col-12">
                                        <h2 class="why203">Lorem Ipsum</h2>
                                    </div>
                                </div>

                                <div class="row">
                                    <div class="col-12">
                                        <h6 class="why204">Ulamco laboris nisi ut aliquip ex ea commodo consequat. Et consectetur ducimus vero placeat</h6>
                                    </div>
                                </div>
                            </div>


                        </div>
                    </div>
                </div>
            </div>

            <div class="container-fluid" data-aos="zoom-in" data-aos-duration="1500">
                <div class="row">

                    <div class="col-12">
                        <div class="row">
                            <div class=" offset-1 col-10 why205">

                                <div class="row">
                                    <div class="col-12">
                                        <h3 class="why206">02</h3>
                                    </div>
                                </div>

                                <div class="row">
                                    <div class="col-12">
                                        <h2 class="why207">Repellat Nihil</h2>
                                    </div>
                                </div>

                                <div class="row">
                                    <div class="col-12">
                                        <h6 class="why208">Dolorem est fugiat occaecati voluptate velit esse. Dicta veritatis dolor quod et vel dire leno para dest</h6>
                                    </div>
                                </div>
                            </div>


                        </div>
                    </div>

                    <div class="col-12" data-aos="zoom-in" data-aos-duration="1500">
                        <div class="row">
                            <div class=" offset-1 col-10 why209">

                                <div class="row">
                                    <div class="col-12">
                                        <h3 class="why210" >03</h3>
                                    </div>
                                </div>

                                <div class="row">
                                    <div class="col-12">
                                        <h2 class="why211">Ad ad velit qui</h2>
                                    </div>
                                </div>

                                <div class="row">
                                    <div class="col-12">
                                        <h6 class="why212">Molestiae officiis omnis illo asperiores. Aut doloribus vitae sunt debitis quo vel nam quis</h6>
                                    </div>
                                </div>
                            </div>


                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

     <section name="menu_start ">
        <div class="container-fluid d-md-block d-none" style="background-color: #1A1814;height: 800px;width: 100%;">
            <div class="row">
                <div class="col-md-12">

                    <div class="row">
                        <div class="col-12">
                            <div data-aos-duration="2000"  data-aos="fade-up" style="color: #AAAAAA;position: absolute;top: 50px;left: 120px;font-weight: 600;letter-spacing: 2px;">MENU</div>
                            <p data-aos-duration="2000"  data-aos="fade-up" style="color: #AAAAAA;position: absolute;top: 43px;left: 180px;opacity: 0.4">_________________</p>
                        </div>
                    </div>

                    <div class="row">
                        <div class="col-12">
                            <h1 data-aos-duration="2000"  data-aos="fade-up" style="color: #CDA45E;position: absolute;top: 80px;left: 110px;font-size: 40px;font-family: Century751 SeBd BT;">Check Our Tasty Menu</h1>
                        </div>
                    </div>

                    <div class="row" data-aos-duration="2000"  data-aos="fade-up">
                        <div class="col-12">
                            <a href="" style="color: #CDA45E;position: absolute;top: 190px;left: 540px;font-size: 18px;font-family: Century751 SeBd BT;">All</a>
                            <a href="" style="position: absolute;top: 190px;left: 590px;font-size: 18px;color: white;font-family: Century751 SeBd BT;">Starters</a>
                            <a href="" style="position: absolute;top: 190px;left: 670px;font-size: 18px;color: white;font-family: Century751 SeBd BT;">Salads</a>
                            <a href="" style="position: absolute;top: 190px;left: 740px;font-size: 18px;color: white;font-family: Century751 SeBd BT;">Specialty</a>

                        </div>
                    </div>

                </div>
            </div>
            <div class="row" style="position: relative;" data-aos-duration="3000"  data-aos="fade-up">
                <div style="height: 70px;width: 70px;background-color: #484643;border-radius: 50%;position: absolute;left: 120px;top: 250px;">
                    <img src="lobster-bisque.jpg" height="60px" width="60px" style="position: absolute;left: 4px;top: 5px;border-radius: 50%;">
                </div>

                <div class="text-white" style="position: absolute;left: 210px;top: 250px;font-weight: 600;">Lobster Bisque</div>
                <div class="text-white" style="position: absolute;left: 330px;top: 250px;letter-spacing: 2px;">....................................................</div>
                <div style="position: absolute;left: 630px;top: 250px;color: #CDA45E;font-weight: bold;">$5.95</div>
                <div style="position: absolute;left: 210px;top: 275px;color: #868C8A;font-style: italic;font-weight: 600">Lorem, deren, trataro, filede, nerada</div>


            </div>

            <div style="position: relative;" data-aos-duration="3000"  data-aos="fade-up">
                <div style="height: 70px;width: 70px;background-color: #484643;border-radius: 50%;position: absolute;left: 700px;top: 240px;">
                    <img src="bread-barrel.jpg" height="60px" width="60px" style="position: absolute;left: 4px;top: 5px;border-radius: 50%;">
                </div>

                <div class="text-white" style="position: absolute;left: 790px;top: 250px;font-weight: 600;">Bread Barrel</div>
                <div class="text-white" style="position: absolute;left: 890px;top: 250px;letter-spacing: 2px;">.........................................................</div>
                <div style="position: absolute;left: 1210px;top: 250px;color: #CDA45E;font-weight: bold;">$6.95</div>
                <div style="position: absolute;left: 790px;top: 275px;color: #868C8A;font-style: italic;font-weight: 600">Lorem, deren, trataro, filede, nerada</div>


            </div>

            <div class="row" style="position: relative;" data-aos-duration="3000"  data-aos="fade-up">
                <div style="height: 70px;width: 70px;background-color: #484643;border-radius: 50%;position: absolute;left: 120px;top: 350px;">
                    <img src="cake.jpg" height="60px" width="60px" style="position: absolute;left: 4px;top: 5px;border-radius: 50%;">
                </div>

                <div class="text-white" style="position: absolute;left: 210px;top: 350px;font-weight: 600">Crab Cake</div>
                <div class="text-white" style="position: absolute;left: 300px;top: 350px;letter-spacing: 2px;">..........................................................</div>
                <div style="position: absolute;left: 630px;top: 350px;color: #CDA45E;font-weight: bold;">$7.95</div>
                <div style="position: absolute;left: 210px;top: 375px;color: #868C8A;font-style: italic;font-weight: 600;width: 450px;">A delicate crab cake served on a toasted roll with lettuce and tartar sauce</div>


            </div>

            <div style="position: relative;" data-aos-duration="3000"  data-aos="fade-up">
                <div style="height: 70px;width: 70px;background-color: #484643;border-radius: 50%;position: absolute;left: 700px;top: 340px;">
                    <img src="caesar.jpg" height="60px" width="60px" style="position: absolute;left: 4px;top: 5px;border-radius: 50%;">
                </div>

                <div class="text-white" style="position: absolute;left: 790px;top: 350px;font-weight: 600;">Caesar Selections</div>
                <div class="text-white" style="position: absolute;left: 920px;top: 350px;letter-spacing: 2px;">....................................................</div>
                <div style="position: absolute;left: 1210px;top: 350px;color: #CDA45E;font-weight: bold;">$8.95</div>
                <div style="position: absolute;left: 790px;top: 375px;color: #868C8A;font-style: italic;font-weight: 600">Lorem, deren, trataro, filede, nerada</div>


            </div>

            <div class="row" style="position: relative;" data-aos-duration="3000"  data-aos="fade-up">
                <div style="height: 70px;width: 70px;background-color: #484643;border-radius: 50%;position: absolute;left: 120px;top: 450px;">
                    <img src="tuscan-grilled.jpg" height="60px" width="60px" style="position: absolute;left: 4px;top: 5px;border-radius: 50%;">
                </div>

                <div class="text-white" style="position: absolute;left: 210px;top: 450px;font-weight: 600">Tuscan Grilled</div>
                <div class="text-white" style="position: absolute;left: 320px;top: 450px;letter-spacing: 2px;">.......................................................</div>
                <div style="position: absolute;left: 630px;top: 450px;color: #CDA45E;font-weight: bold;">$9.95</div>
                <div style="position: absolute;left: 210px;top: 475px;color: #868C8A;font-style: italic;font-weight: 600;width: 450px;">Grilled chicken with provolone, artichoke hearts, and roasted red pesto</div>


            </div>

            <div style="position: relative;" data-aos-duration="3000"  data-aos="fade-up">
                <div style="height: 70px;width: 70px;background-color: #484643;border-radius: 50%;position: absolute;left: 700px;top: 440px;">
                    <img src="mozzarella.jpg" height="60px" width="60px" style="position: absolute;left: 4px;top: 5px;border-radius: 50%;">
                </div>

                <div class="text-white" style="position: absolute;left: 790px;top: 450px;font-weight: 600;">Mozzarella Stick</div>
                <div class="text-white" style="position: absolute;left: 920px;top: 450px;letter-spacing: 2px;">....................................................</div>
                <div style="position: absolute;left: 1210px;top: 450px;color: #CDA45E;font-weight: bold;">$4.95</div>
                <div style="position: absolute;left: 790px;top: 475px;color: #868C8A;font-style: italic;font-weight: 600">Lorem, deren, trataro, filede, nerada</div>


            </div>

            <div class="row" style="position: relative;" data-aos-duration="3000"  data-aos="fade-up">
                <div style="height: 70px;width: 70px;background-color: #484643;border-radius: 50%;position: absolute;left: 120px;top: 550px;">
                    <img src="greek-salad.jpg" height="60px" width="60px" style="position: absolute;left: 4px;top: 5px;border-radius: 50%;">
                </div>

                <div class="text-white" style="position: absolute;left: 210px;top: 550px;font-weight: 600">Greek Salad</div>
                <div class="text-white" style="position: absolute;left: 320px;top: 550px;letter-spacing: 2px;">.......................................................</div>
                <div style="position: absolute;left: 630px;top: 550px;color: #CDA45E;font-weight: bold;">$9.95</div>
                <div style="position: absolute;left: 210px;top: 575px;color: #868C8A;font-style: italic;font-weight: 600;width: 450px;">Fresh spinach, crisp romaine, tomatoes, and Greek olives</div>


            </div>

            <div style="position: relative;" data-aos-duration="3000"  data-aos="fade-up">
                <div style="height: 70px;width: 70px;background-color: #484643;border-radius: 50%;position: absolute;left: 700px;top: 540px;">
                    <img src="spinach-salad.jpg" height="60px" width="60px" style="position: absolute;left: 4px;top: 5px;border-radius: 50%;">
                </div>

                <div class="text-white" style="position: absolute;left: 790px;top: 550px;font-weight: 600;">Spinach Salad</div>
                <div class="text-white" style="position: absolute;left: 920px;top: 550px;letter-spacing: 2px;">....................................................</div>
                <div style="position: absolute;left: 1210px;top: 550px;color: #CDA45E;font-weight: bold;">$9.95</div>
                <div style="position: absolute;left: 790px;top: 575px;color: #868C8A;font-style: italic;font-weight: 600">Fresh spinach with mushrooms, hard boiled egg, and warm bacon vinaigrette</div>


            </div>


            <div class="row" style="position: relative;" data-aos-duration="3000"  data-aos="fade-up">
                <div style="height: 70px;width: 70px;background-color: #484643;border-radius: 50%;position: absolute;left: 120px;top: 650px;">
                    <img src="lobster-roll.jpg" height="60px" width="60px" style="position: absolute;left: 4px;top: 5px;border-radius: 50%;">
                </div>

                <div class="text-white" style="position: absolute;left: 210px;top: 650px;font-weight: 600">Lobster Roll</div>
                <div class="text-white" style="position: absolute;left: 320px;top: 650px;letter-spacing: 2px;">.......................................................</div>
                <div style="position: absolute;left: 630px;top: 650px;color: #CDA45E;font-weight: bold;">$12.95</div>
                <div style="position: absolute;left: 210px;top: 675px;color: #868C8A;font-style: italic;font-weight: 600;width: 450px;">Plump lobster meat, mayo and crisp lettuce on a toasted bulky roll</div>


            </div>

        </div>

    </section>

     <section name="menu_start_resp">
        <div class="container-fluid d-md-none d-block" style="background-color: #1A1814;height: 1500px;width: 100%;">
            <div class="row">
                <div class="col-1">
                    <h6 data-aos-duration="1000"  data-aos="fade-up" style="color: #AAAAAA;" class="mt-5">MENU</h6>
                </div>

                <div class="offset-1 col-3">
                    <P data-aos-duration="1000"  data-aos="fade-up" style="color: #AAAAAA;opacity: 0.6;top: -8px;position: absolute;left: -10px;" class="mt-5">____________________</P>
                </div>
            </div>

            <div class="row">
                <div class="col-12">
                    <h2 data-aos-duration="1000"  data-aos="fade-up" style="color: #CDA45E;font-family: Century751 SeBd BT;" class="mt-2">Check Our Tasty Menu</h2>
                </div>
            </div>

            <div class="row" data-aos-duration="1000"  data-aos="fade-up">
                <div class="offset-2 col-1 mt-5">
                    <p><a href="" style="color: #CDA45E;font-size: 20px;">All</a></p>
                </div>

                <div class=" col-1 mt-5 ml-3">
                    <p><a href="" style="color: white;font-size: 20px;">Starters</a></p>
                </div>

                <div class=" col-1 mt-5 ml-5">
                    <p><a href="" style="color: white;font-size: 20px;">Salads</a></p>
                </div>

                <div class=" col-1 mt-5 ml-5">
                    <p><a href="" style="color: white;font-size: 20px;">Specialty</a></p>
                </div>
            </div>

            <div class="row mt-5" data-aos-duration="1000"  data-aos="fade-up">
                <div class="col-2">
                    <div style="height: 80px;width: 80px;background-color: #484643;border-radius: 50%;position: relative;">
                        <img src="lobster-bisque.jpg" height="70px" width="70px" style="border-radius: 50%;position: absolute;top: 4px;left: 4px;">
                    </div>
                </div>

                <div class="col-4 ml-3">
                    <div class="text-white" style="font-weight: 700;font-size: 18px;">Lobster Bisque</div>

                    <p style="width: 300px;color: #868C8A;font-style: italic;font-weight: 600;">Lorem, deren, trataro, filede, nerada</p>

                </div>

                <div class="col-4" style="left: 230px;position: absolute;">
                    <div class="text-white" style="letter-spacing: 2px;">..............................</div>

                </div>

                <div class="col-2" style="left: 400px;color: #CDA45E;position: absolute;font-weight: 400;">
                    <div style="font-weight: bold;">$5.95</div>

                </div>

                <div class="col-10">

                </div>
            </div>

            <div class="row mt-5" data-aos-duration="1000"  data-aos="fade-up">
                <div class="col-2">
                    <div style="height: 80px;width: 80px;background-color: #484643;border-radius: 50%;position: relative;">
                        <img src="bread-barrel.jpg" height="70px" width="70px" style="border-radius: 50%;position: absolute;top: 4px;left: 4px;">
                    </div>
                </div>

                <div class="col-4 ml-3">
                    <div class="text-white" style="font-weight: 700;font-size: 18px;">Bread Barrel</div>

                    <p style="width: 300px;color: #868C8A;font-style: italic;font-weight: 600;">Lorem, deren, trataro, filede, nerada</p>

                </div>

                <div class="col-4" style="left: 210px;position: absolute;">
                    <div class="text-white" style="letter-spacing: 2px;">..................................</div>

                </div>

                <div class="col-2" style="left: 400px;color: #CDA45E;position: absolute;font-weight: 400;">
                    <div style="font-weight: bold;">$6.95</div>

                </div>

                <div class="col-10">

                </div>
            </div>

            <div class="row mt-5" data-aos-duration="1000"  data-aos="fade-up">
                <div class="col-2">
                    <div style="height: 80px;width: 80px;background-color: #484643;border-radius: 50%;position: relative;">
                        <img src="cake.jpg" height="70px" width="70px" style="border-radius: 50%;position: absolute;top: 4px;left: 4px;">
                    </div>
                </div>

                <div class="col-4 ml-3">
                    <div class="text-white" style="font-weight: 700;font-size: 18px;">Crab Cake</div>

                    <p style="width: 320px;color: #868C8A;font-style: italic;font-weight: 600;font-size: 16px; ">A delicate crab cake served on a toasted roll with lettuce and tartar sauce
                    </p>

                </div>

                <div class="col-4" style="left: 195px;position: absolute;">
                    <div class="text-white" style="letter-spacing: 2px;">....................................</div>

                </div>

                <div class="col-2" style="left: 400px;color: #CDA45E;position: absolute;font-weight: 400;">
                    <div style="font-weight: bold;">$7.95</div>

                </div>

                <div class="col-10">

                </div>
            </div>

            <div class="row mt-5" data-aos-duration="1000"  data-aos="fade-up">
                <div class="col-2">
                    <div style="height: 80px;width: 80px;background-color: #484643;border-radius: 50%;position: relative;">
                        <img src="caesar.jpg" height="70px" width="70px" style="border-radius: 50%;position: absolute;top: 4px;left: 4px;">
                    </div>
                </div>

                <div class="col-5 ml-3">
                    <div class="text-white" style="font-weight: 700;font-size: 18px;">Caesar Selections</div>

                    <p style="width: 320px;color: #868C8A;font-style: italic;font-weight: 600;font-size: 16px; ">Lorem, deren, trataro, filede, nerada</p>

                </div>

                <div class="col-4" style="left: 250px;position: absolute;">
                    <div class="text-white" style="letter-spacing: 2px;">.........................</div>

                </div>

                <div class="col-2" style="left: 400px;color: #CDA45E;position: absolute;font-weight: 400;">
                    <div style="font-weight: bold;">$8.95</div>

                </div>

                <div class="col-10">

                </div>
            </div>

            <div class="row mt-5" data-aos-duration="1000"  data-aos="fade-up">
                <div class="col-2">
                    <div style="height: 80px;width: 80px;background-color: #484643;border-radius: 50%;position: relative;">
                        <img src="tuscan-grilled.jpg" height="70px" width="70px" style="border-radius: 50%;position: absolute;top: 4px;left: 4px;">
                    </div>
                </div>

                <div class="col-5 ml-3">
                    <div class="text-white" style="font-weight: 700;font-size: 18px;">Tuscan Grilled</div>

                    <p style="width: 320px;color: #868C8A;font-style: italic;font-weight: 600;font-size: 16px; ">Grilled chicken with provolone, artichoke hearts, and roasted red pesto</p>

                </div>

                <div class="col-4" style="left: 230px;position: absolute;">
                    <div class="text-white" style="letter-spacing: 2px;">..............................</div>

                </div>

                <div class="col-2" style="left: 400px;color: #CDA45E;position: absolute;font-weight: 400;">
                    <div style="font-weight: bold;">$9.95</div>

                </div>

                <div class="col-10">

                </div>
            </div>

            <div class="row mt-5" data-aos-duration="1000"  data-aos="fade-up">
                <div class="col-2">
                    <div style="height: 80px;width: 80px;background-color: #484643;border-radius: 50%;position: relative;">
                        <img src="mozzarella.jpg" height="70px" width="70px" style="border-radius: 50%;position: absolute;top: 4px;left: 4px;">
                    </div>
                </div>

                <div class="col-5 ml-3">
                    <div class="text-white" style="font-weight: 700;font-size: 18px;">Mozzarella Stick</div>

                    <p style="width: 320px;color: #868C8A;font-style: italic;font-weight: 600;font-size: 16px; ">Lorem, deren, trataro, filede, nerada</p>

                </div>

                <div class="col-4" style="left: 250px;position: absolute;">
                    <div class="text-white" style="letter-spacing: 2px;">..........................</div>

                </div>

                <div class="col-2" style="left: 400px;color: #CDA45E;position: absolute;font-weight: 400;">
                    <div style="font-weight: bold;">$4.95</div>

                </div>

                <div class="col-10">

                </div>
            </div>

            <div class="row mt-5" data-aos-duration="1000"  data-aos="fade-up">
                <div class="col-2">
                    <div style="height: 80px;width: 80px;background-color: #484643;border-radius: 50%;position: relative;">
                        <img src="greek-salad.jpg" height="70px" width="70px" style="border-radius: 50%;position: absolute;top: 4px;left: 4px;">
                    </div>
                </div>

                <div class="col-5 ml-3">
                    <div class="text-white" style="font-weight: 700;font-size: 18px;">Greek Salad</div>

                    <p style="width: 320px;color: #868C8A;font-style: italic;font-weight: 600;font-size: 16px; ">Fresh spinach, crisp romaine, tomatoes, and Greek olives</p>

                </div>

                <div class="col-4" style="left: 215px;position: absolute;">
                    <div class="text-white" style="letter-spacing: 2px;">................................</div>

                </div>

                <div class="col-2" style="left: 400px;color: #CDA45E;position: absolute;font-weight: 400;">
                    <div style="font-weight: bold;">$9.95</div>

                </div>

                <div class="col-10">

                </div>
            </div>

            <div class="row mt-5" data-aos-duration="1000"  data-aos="fade-up">
                <div class="col-2">
                    <div style="height: 80px;width: 80px;background-color: #484643;border-radius: 50%;position: relative;">
                        <img src="spinach-salad.jpg" height="70px" width="70px" style="border-radius: 50%;position: absolute;top: 4px;left: 4px;">
                    </div>
                </div>

                <div class="col-5 ml-3">
                    <div class="text-white" style="font-weight: 700;font-size: 18px;">Spinach Salad</div>

                    <p style="width: 320px;color: #868C8A;font-style: italic;font-weight: 600;font-size: 16px; ">Fresh spinach with mushrooms, hard boiled egg, and warm bacon vinaigrette</p>

                </div>

                <div class="col-4" style="left: 225px;position: absolute;">
                    <div class="text-white" style="letter-spacing: 2px;">..............................</div>

                </div>

                <div class="col-2" style="left: 400px;color: #CDA45E;position: absolute;font-weight: 400;">
                    <div style="font-weight: bold;">$9.95</div>

                </div>

                <div class="col-10">

                </div>
            </div>

            <div class="row mt-5" data-aos-duration="1000"  data-aos="fade-up">
                <div class="col-2">
                    <div style="height: 80px;width: 80px;background-color: #484643;border-radius: 50%;position: relative;">
                        <img src="lobster-roll.jpg" height="70px" width="70px" style="border-radius: 50%;position: absolute;top: 4px;left: 4px;">
                    </div>
                </div>

                <div class="col-5 ml-3">
                    <div class="text-white" style="font-weight: 700;font-size: 18px;">Lobster Roll</div>

                    <p style="width: 320px;color: #868C8A;font-style: italic;font-weight: 600;font-size: 16px; ">Plump lobster meat, mayo and crisp lettuce on a toasted bulky roll</p>

                </div>

                <div class="col-4" style="left: 215px;position: absolute;">
                    <div class="text-white" style="letter-spacing: 2px;">................................</div>

                </div>

                <div class="col-2" style="left: 400px;color: #CDA45E;position: absolute;font-weight: 400;">
                    <div style="font-weight: bold;">$12.95</div>

                </div>

                <div class="col-10">

                </div>
            </div>

        </div>
    </section>

    <section name="Specials_start">
        <div class="container-fluid  d-md-block d-none" style="height: 500px;width: 100%;background-color: #0C0B09;">
            <div class="row">

                <div class="offset-1 col-md-1 mt-5">
                    <p data-aos-duration="2000"  data-aos="fade-up" style="color: #AAAAAA;font-weight: 600;letter-spacing: 2px;">SPECIALS</p>
                </div>

                <div class="col-md-2 mt-5 ">
                    <p data-aos-duration="2000"  data-aos="fade-up" style="color: #AAAAAA;opacity: 0.4;position: absolute;left: 5px;top: -6px;">____________________</p>
                </div>

            </div>

            <div class="row">
                <div class=" offset-1 col-md-11">
                    <h1 data-aos-duration="2000"  data-aos="fade-up" style="color: #CDA45E;font-family: Century751 SeBd BT;">Check Our Specials</h1>
                </div>
            </div>

            <div class="row mt-4" style="position: relative;" data-aos-duration="1000"  data-aos="fade-up">
                <div class="offset-1 col-md-2">
                    <p style="background-color:#CDA45E;height: 50px;width: 240px; "><a href="" style="position: absolute;left: 30px;color: black;top: 10px;font-weight: 400;font-size: 18px;">Modi Sit est</a></p>

                    <p style="border-right: 2px solid #CDA45E;  height: 45px;width: 240px;padding-top: 15px;position: absolute;top: 50px; "><a href="" style="position: absolute;left: 15px;color: white;top: 10px;font-weight: 600;">Unde praesentium sed</a></p>

                    <p style="border-right: 2px solid #CDA45E;  height: 45px;width: 240px;padding-top: 15px;position: absolute;top: 90px; "><a href="" style="position: absolute;left: 15px;color: white;top: 10px;font-weight: 600;">Pariatur explicabo vel</a></p>

                    <p style="border-right: 2px solid #CDA45E;  height: 45px;width: 240px;padding-top: 15px;position: absolute;top: 130px; "><a href="" style="position: absolute;left: 15px;color: white;top: 10px;font-weight: 600;">Nostrium qui quasi</a></p>


                    <p style="border-right: 2px solid #CDA45E;  height: 45px;width: 240px;padding-top: 15px;position: absolute;top: 170px; "><a href="" style="position: absolute;left: 15px;color: white;top: 10px;font-weight: 600;">lusto ut expedita aut</a></p>

                </div>

                <div class="col-md-6 ml-5">
                    <h3 class="text-white" style="font-family: Century751 SeBd BT;">Architecto ut aperiam autem id</h3>
                    <p class="mt-3" style="font-style: italic;font-size: 19px;color: #AAAAAA;">Qui laudantium consequatur laborum sit qui ad sapiente dila parde sonata raqer a videna mareta paulona marka</p>

                    <p class="mt-3" style="font-style: italic;font-size: 19px;color: #AAAAAA;">Et nobis maiores eius. Voluptatibus ut enim blanditiis atque harum sint. Laborum eos ipsum ipsa odit magni. Incidunt hic ut molestiae aut qui. Est repellat minima eveniet eius et quis magni nihil. Consequatur dolorem quaerat quos qui
                        similique accusamus nostrum rem vero</p>
                </div>

                <div class="col-md-2">
                    <img src="specials-1.png" height="280px" width="280px" style="position: absolute;left: -30px;">
                </div>
            </div>
        </div>
    </section>

     <section name="Specials_start_resp">
        <div class="container-fluid  d-md-none d-block" style="height: 1330px;width: 100%;background-color: #0C0B09;">
            <div class="row">
                <div class="col-1  mt-5">
                    <p data-aos-duration="1000"  data-aos="fade-up" style="color: #AAAAAA;font-weight: 600;letter-spacing: 2px;">SPECIALS</p>

                </div>

                <div class="col-2 mt-5 ">
                    <p data-aos-duration="1000"  data-aos="fade-up" style="color: #AAAAAA;opacity: 0.4;position: absolute;left: 65px;top: -6px;">__________________</p>
                </div>


            </div>

            <div class="row">
                <div class=" col-11">
                    <h1 data-aos-duration="1000"  data-aos="fade-up" style="color: #CDA45E;font-family: Century751 SeBd BT;">Check Our Specials</h1>
                </div>
            </div>

            <div class="row" data-aos-duration="1000"  data-aos="fade-up">
                <div class="col-12 mt-4">
                    <p style="background-color:#CDA45E;height: 55px;width: 100%; "><a href="" style="position: absolute;left: 30px;color: black;top: 10px;font-weight: 600;">Modi Sit est</a></p>
                </div>
            </div>

            <div class="row " data-aos-duration="1000"  data-aos="fade-up">
                <div class="col-12">
                    <p style="height: 55px;width: 100%; "><a href="" style="position: absolute;left: 30px;color: white;top: 0px;font-weight: 600;">Unde praesentium sed</a></p>
                </div>
            </div>

            <div class="row">
                <div class="col-12" data-aos-duration="1000"  data-aos="fade-up">
                    <p style="height: 55px;width: 100%; "><a href="" style="position: absolute;left: 30px;color: white;top: -20px;font-weight: 600;">Pariatur explicabo vel</a></p>
                </div>
            </div>

            <div class="row">
                <div class="col-12" data-aos-duration="1000"  data-aos="fade-up">
                    <p style="height: 55px;width: 100%; "><a href="" style="position: absolute;left: 30px;color: white;top: -40px;font-weight: 600;">Nostrium qui quasi</a></p>
                </div>
            </div>

            <div class="row">
                <div class="col-12" data-aos-duration="1000"  data-aos="fade-up">
                    <p style="height: 55px;width: 100%; "><a href="" style="position: absolute;left: 30px;color: white;top:-60px;font-weight: 600;">lusto ut expedita aut</a></p>
                </div>
            </div>

            <div class="row">
                <div class="col-8 ml-2" data-aos-duration="1000"  data-aos="fade-up">
                    <img src="specials-1.png" height="460px" width="440px">

                </div>
            </div>

            <div class="row">
                <div class="col-12 mt-2">
                    <h3 class="text-white" style="font-family: Century751 SeBd BT;">Architecto ut aperiam autem id</h3>

                </div>
            </div>

            <div class="row">
                <div class="col-12">
                    <p class="mt-3" style="font-style: italic;font-size: 18px;color: #AAAAAA;">Qui laudantium consequatur laborum sit qui ad sapiente dila parde sonata raqer a videna mareta paulona marka</p>
                </div>
            </div>

            <div class="row">
                <div class="col-12">
                    <p class="mt-2" style="font-size: 19px;color: #AAAAAA;">Et nobis maiores eius. Voluptatibus ut enim blanditiis atque harum sint. Laborum eos ipsum ipsa odit magni. Incidunt hic ut molestiae aut qui. Est repellat minima eveniet eius et quis magni nihil. Consequatur dolorem quaerat quos qui
                        similique accusamus nostrum rem vero</p>
                </div>
            </div>

        </div>
    </section>

    <section name="events_start">
        <div>
            <div class="d-md-block d-none" style="background-image: url(gallery-33.jpg); height: 780px;background-repeat: no-repeat;width: 100%;background-size: 100% 100%;background-attachment: fixed;">
                <div class="container-fluid">
                    <div class="row">
                        <div class="col-md-12">
                            <div id="demo" class="carousel slide" data-ride="carousel">
                                <ul class="carousel-indicators" style="position: absolute;top: 680px;">
                                    <li data-target="#demo" data-slide-to="0" class="active" id="lis"></li>
                                    <li data-target="#demo" data-slide-to="1" id="lis"></li>
                                    <li data-target="#demo" data-slide-to="2" id="lis"></li>
                                </ul>

                                <div class="row">
                                    <div class=" col-md-1 col-3">
                                        <P data-aos-duration="2000"  data-aos="fade-up" class="text-white mt-5 ml-5" style="color: #AAAAAA;font-weight: 600;letter-spacing: 3px;">EVENTS</P>
                                    </div>

                                    <div class="col-md-2 mt-5 col-2 ">
                                        <p data-aos-duration="2000"  data-aos="fade-up" style="color: #AAAAAA;opacity: 0.4;position: absolute;top: -6px;">__________________</p>
                                    </div>



                                </div>
                                <div class="row ">
                                    <div class="col-md-11 ml-5 col-11">
                                        <h2 data-aos-duration="2000"  data-aos="fade-up" style="font-size: 40px;color: #CDA45E;font-family: Century751 SeBd BT;">Organize Your Events in our Restaurant</h2>


                                    </div>
                                </div>

                                <div class="carousel-inner">
                                    <div class="carousel-item active">



                                        <div class="row">
                                            <div class="ml-5 mt-4 col-md-6 col-10">
                                                <img src="event-birthday.jpg" height="100%">
                                            </div>

                                            <div class="col-md-5 mt-4">
                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <h2 style="color: #CDA45E;">Birthday Parties</h2>
                                                    </div>

                                                </div>

                                                <div class="row">
                                                    <div class="col-md-2 col-2 col-2">
                                                        <h2 style="color: white;font-weight: 700;border-bottom: 3px solid  #CDA45E; ">$189</h2>

                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12 mt-3">
                                                        <p style="color:  #D5D6D6;font-style: italic;font-size: 19px;">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <p style="color:  #D5D6D6;  font-size: 20px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <p style="color:  #D5D6D6;  font-size: 20px;">Duis aute irure dolor in reprehenderit in voluptate velit.</p>
                                                    </div>
                                                </div>


                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <p style="color:  #D5D6D6;  font-size: 20px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12 mt-4">
                                                        <p style="color: #D5D6D6;  font-size: 20px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="carousel-item">
                                        <div class="row" >
                                            <div class="ml-5 mt-4 col-md-6 col-10">

                                                <img src="event-private.jpg" height="100%">
                                            </div>

                                            <div class="col-md-5 mt-4">
                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <h2 style="color: #CDA45E;">Private Parties</h2>
                                                    </div>

                                                </div>

                                                <div class="row">
                                                    <div class="col-md-2 col-2">
                                                        <h2 style="color: white;font-weight: 700;border-bottom: 3px solid  #CDA45E; ">$290</h2>

                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12 mt-3">
                                                        <p style="color:  #D5D6D6;font-style: italic;font-size: 19px;">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <p style="color:  #D5D6D6;  font-size: 20px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <p style="color:  #D5D6D6;  font-size: 20px;">Duis aute irure dolor in reprehenderit in voluptate velit.</p>
                                                    </div>
                                                </div>


                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <p style="color:  #D5D6D6;  font-size: 20px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12 mt-4">
                                                        <p style="color: #D5D6D6;  font-size: 20px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
                                                    </div>
                                                </div>
                                            </div>

                                        </div>
                                    </div>

                                    <div class="carousel-item">
                                        <div class="row" >
                                            <div class="ml-5 mt-4 col-md-6 col-10">
                                                <img src="event-custom.jpg" height="100%">

                                            </div>

                                            <div class="col-md-5 mt-4">
                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <h2 style="color: #CDA45E;">Custom Parties</h2>
                                                    </div>

                                                </div>

                                                <div class="row">
                                                    <div class="col-md-2 col-2">
                                                        <h2 style="color: white;font-weight: 700;border-bottom: 3px solid  #CDA45E; ">$99</h2>

                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12 mt-3">
                                                        <p style="color:  #D5D6D6;font-style: italic;font-size: 19px;">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <p style="color:  #D5D6D6;  font-size: 20px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <p style="color:  #D5D6D6;  font-size: 20px;">Duis aute irure dolor in reprehenderit in voluptate velit.</p>
                                                    </div>
                                                </div>


                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <p style="color:  #D5D6D6;  font-size: 20px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12 mt-4">
                                                        <p style="color: #D5D6D6;  font-size: 20px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
                                                    </div>
                                                </div>
                                            </div>

                                        </div>
                                    </div>


                                </div>
                            
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

        <section name="events_start_resp">
        <div>
            <div class="d-md-none d-block" style="background-image: url(gallery-33.jpg); height: 1220px;background-repeat: no-repeat;width: 100%;background-size: 100% 100%;background-attachment: fixed;">
                <div class="container-fluid">
                    <div class="row">
                        <div class="col-md-12">
                            <div id="demo" class="carousel slide" data-ride="carousel">
                                <ul class="carousel-indicators" style="position: absolute;top: 1160px;">
                                    <li data-target="#demo" data-slide-to="0" class="active" id="lis"></li>
                                    <li data-target="#demo" data-slide-to="1" id="lis"></li>
                                    <li data-target="#demo" data-slide-to="2" id="lis"></li>
                                </ul>

                                <div class="row">
                                    <div class=" col-3">
                                        <P data-aos-duration="1000"  data-aos="fade-up" class="text-white mt-5 ml-5" style="color: #AAAAAA;font-weight: 600;letter-spacing: 3px;">EVENTS</P>
                                    </div>

                                    <div class=" mt-5 col-2">
                                        <p data-aos-duration="1000"  data-aos="fade-up" style="color: #AAAAAA;opacity: 0.4;position: absolute;top: -6px;" class="ml-3">__________________</p>
                                    </div>



                                </div>
                                <div class="row ">
                                    <div class=" ml-5 col-10">
                                        <h6 data-aos-duration="1000"  data-aos="fade-up" style="font-size: 35px;color: #CDA45E;font-family: Century751 SeBd BT;">Organize Your Events in our Restaurant</h6>


                                    </div>
                                </div>

                                <div class="carousel-inner" data-aos-duration="1000"  data-aos="fade-up">
                                    <div class="carousel-item active">



                                        <div class="row">
                                            <div class="ml-5 mt-4  col-10">
                                                <img src="event-birthday.jpg" height="100%">
                                            </div>

                                            <div class="col-md-5 mt-4">
                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <h2 style="color: #CDA45E;">Birthday Parties</h2>
                                                    </div>

                                                </div>

                                                <div class="row">
                                                    <div class="col-md-2 col-2 col-2">
                                                        <h2 style="color: white;font-weight: 700;border-bottom: 3px solid  #CDA45E; ">$189</h2>

                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12 mt-3">
                                                        <p style="color:  #D5D6D6;font-style: italic;font-size: 19px;">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <p style="color:  #D5D6D6;  font-size: 20px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <p style="color:  #D5D6D6;  font-size: 20px;">Duis aute irure dolor in reprehenderit in voluptate velit.</p>
                                                    </div>
                                                </div>


                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <p style="color:  #D5D6D6;  font-size: 20px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12 mt-4">
                                                        <p style="color: #D5D6D6;  font-size: 20px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="carousel-item">
                                        <div class="row">
                                            <div class="ml-5 mt-4 col-md-6 col-10">

                                                <img src="event-private.jpg" height="100%">
                                            </div>

                                            <div class="col-md-5 mt-4">
                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <h2 style="color: #CDA45E;">Private Parties</h2>
                                                    </div>

                                                </div>

                                                <div class="row">
                                                    <div class="col-md-2 col-2">
                                                        <h2 style="color: white;font-weight: 700;border-bottom: 3px solid  #CDA45E; ">$290</h2>

                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12 mt-3">
                                                        <p style="color:  #D5D6D6;font-style: italic;font-size: 19px;">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <p style="color:  #D5D6D6;  font-size: 20px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <p style="color:  #D5D6D6;  font-size: 20px;">Duis aute irure dolor in reprehenderit in voluptate velit.</p>
                                                    </div>
                                                </div>


                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <p style="color:  #D5D6D6;  font-size: 20px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12 mt-4">
                                                        <p style="color: #D5D6D6;  font-size: 20px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
                                                    </div>
                                                </div>
                                            </div>

                                        </div>
                                    </div>

                                    <div class="carousel-item">
                                        <div class="row">
                                            <div class="ml-5 mt-4 col-md-6 col-10">
                                                <img src="event-custom.jpg" height="100%">

                                            </div>

                                            <div class="col-md-5 mt-4">
                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <h2 style="color: #CDA45E;">Custom Parties</h2>
                                                    </div>

                                                </div>

                                                <div class="row">
                                                    <div class="col-md-2 col-2">
                                                        <h2 style="color: white;font-weight: 700;border-bottom: 3px solid  #CDA45E; ">$99</h2>

                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12 mt-3">
                                                        <p style="color:  #D5D6D6;font-style: italic;font-size: 19px;">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <p style="color:  #D5D6D6;  font-size: 20px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <p style="color:  #D5D6D6;  font-size: 20px;">Duis aute irure dolor in reprehenderit in voluptate velit.</p>
                                                    </div>
                                                </div>


                                                <div class="row">
                                                    <div class="col-md-12">
                                                        <p style="color:  #D5D6D6;  font-size: 20px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                                                    </div>
                                                </div>

                                                <div class="row">
                                                    <div class="col-md-12 mt-4">
                                                        <p style="color: #D5D6D6;  font-size: 20px;">Ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
                                                    </div>
                                                </div>
                                            </div>

                                        </div>
                                    </div>


                                </div>
                           
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section name="book_a_table">
        <div class="container-fluid d-md-block d-none" style="background-color: #0C0B09;height: 650px;width: 100%;">
            <div class="row">

                <div class="offset-1 col-md-1 mt-5 col-2">
                    <p data-aos-duration="1000"  data-aos="fade-up" style="color: #AAAAAA;font-weight: 600;letter-spacing: 2px;">RESERVATION</p>
                </div>

                <div class="col-md-2 mt-5 col-2">
                    <p data-aos-duration="1000"  data-aos="fade-up" style="color: #AAAAAA;opacity: 0.4;position: absolute;left: 40px;top: -6px;">____________________</p>
                </div>

            </div>

            <div class="row">
                <div class=" offset-1 col-md-11">
                    <h1 data-aos-duration="1000"  data-aos="fade-up" style="color: #CDA45E;font-family: Century751 SeBd BT;">Book a Table</h1>
                </div>
            </div>

            <div class="row mt-4" data-aos-duration="2000"  data-aos="fade-up">
                <div class="offset-1 col-md-10">
                    <div class="row">

                        <div class="col-md-4">
                            <input type="text" name="" placeholder="Your Name" style="border: 1px solid #AAAAAA;opacity: 0.4;background-color: #0C0B09;height: 45px;width: 350px;padding-left: 20px;font-size: 18px;color: white;">
                        </div>

                        <div class="col-md-4">
                            <input type="Email" name="" placeholder="Your Email" style="border: 1px solid #AAAAAA;opacity: 0.4;background-color: #0C0B09;height: 45px;width: 350px;padding-left: 20px;font-size: 18px;color: white;">
                        </div>
 
                        <div class="col-md-4">
                            <input type="number" name="" placeholder="Your Phone" style="border: 1px solid #AAAAAA;opacity: 0.4;background-color: #0C0B09;height: 45px;width: 350px;padding-left: 20px;font-size: 18px;color: white;">
                        </div>

                    </div>
                </div>
            </div>

            <div class="row mt-4" data-aos-duration="2000"  data-aos="fade-up">
                <div class="offset-1 col-md-10">
                    <div class="row">
                        <div class="col-md-4">
                            <input type="text" name="" placeholder="Date" style="border: 1px solid #AAAAAA;opacity: 0.4;background-color: #0C0B09;height: 45px;width: 350px;padding-left: 20px;font-size: 18px;color: white;">
                        </div>


                        <div class="col-md-4">
                            <input type="text" name="" placeholder="Time" style="border: 1px solid #AAAAAA;opacity: 0.4;background-color: #0C0B09;height: 45px;width: 350px;padding-left: 20px;font-size: 18px;color: white;">
                        </div>

                        <div class="col-md-4">
                            <input type="text" name="" placeholder="# Of People" style="border: 1px solid #AAAAAA;opacity: 0.4;background-color: #0C0B09;height: 45px;width: 350px;padding-left: 20px;font-size: 18px;color: white;">
                        </div>

                    </div>
                </div>
            </div>

            <div class="row mt-4" data-aos-duration="2000"  data-aos="fade-up">
                <div class="offset-1 col-md-10">
                    <div class="row">
                        <div class="col-md-12">
                            <textarea style="border: 1px solid #AAAAAA;opacity: 0.4; background-color: #0C0B09;height: 150px;width: 1102px;padding-left: 20px;font-size: 18px;color: #AAAAAA">Message</textarea>
                        </div>
                    </div>
                </div>
            </div>

            <div class="row" data-aos-duration="2000"  data-aos="fade-up">
                <div class="offset-5  col-md-2 mt-4">
                    <button class="btn text-white text-center" style="background-color: #CDA45E;width: 180px;border-radius: 60px;height: 50px;font-size: 18px;">Book a Table</button>
                </div>
            </div>
        </div>
    </section>

    <section name="book_a_table_resp">
        <div class="container-fluid d-md-none d-block" style="background-color: #0C0B09;height: 850px;width: 100%;">
            <div class="row">

                <div class="offset-1 col-md-1 mt-5 col-2">
                    <p data-aos-duration="1000"  data-aos="fade-up" style="color: #AAAAAA;font-weight: 600;letter-spacing: 2px;">RESERVATION</p>
                </div>

                <div class="col-md-2 mt-5 col-2">
                    <p data-aos-duration="1000"  data-aos="fade-up" style="color: #AAAAAA;opacity: 0.4;position: absolute;left: 70px;top: -6px;">____________________</p>
                </div>

            </div>

            <div class="row">
                <div class=" offset-1 col-md-11">
                    <h1 data-aos-duration="1000"  data-aos="fade-up" style="color: #CDA45E;font-family: Century751 SeBd BT;">Book a Table</h1>
                </div>
            </div>

            <div class="row">
                <div class="col-12 mt-4">
                    <input type="text" name="" placeholder="Your Name" style="border: 1px solid #AAAAAA;opacity: 0.4;background-color: #0C0B09;height: 45px;width: 450px;padding-left: 20px;font-size: 18px;color: white;">
                </div>
            </div>

            <div class="row">
                <div class="col-12 mt-4">
                    <input type="text" name="" placeholder="Your Email" style="border: 1px solid #AAAAAA;opacity: 0.4;background-color: #0C0B09;height: 45px;width: 450px;padding-left: 20px;font-size: 18px;color: white;">
                </div>
            </div>
            <div class="row">
                <div class="col-12 mt-4">
                    <input type="text" name="" placeholder="Your Phone" style="border: 1px solid #AAAAAA;opacity: 0.4;background-color: #0C0B09;height: 45px;width: 450px;padding-left: 20px;font-size: 18px;color: white;">
                </div>
            </div>
            <div class="row">
                <div class="col-12 mt-4">
                    <input type="text" name="" placeholder="Date" style="border: 1px solid #AAAAAA;opacity: 0.4;background-color: #0C0B09;height: 45px;width: 450px;padding-left: 20px;font-size: 18px;color: white;">
                </div>
            </div>
            <div class="row">
                <div class="col-12 mt-4">
                    <input type="text" name="" placeholder="Time" style="border: 1px solid #AAAAAA;opacity: 0.4;background-color: #0C0B09;height: 45px;width: 450px;padding-left: 20px;font-size: 18px;color: white;">
                </div>
            </div>
            <div class="row">
                <div class="col-12 mt-4">
                    <input type="text" name="" placeholder="# Of People" style="border: 1px solid #AAAAAA;opacity: 0.4;background-color: #0C0B09;height: 45px;width: 450px;padding-left: 20px;font-size: 18px;color: white;">
                </div>
            </div>


            <div class="row mt-4">
                <div class=" col-10">
                    <div class="row">
                        <div class="col-12">
                            <textarea style="border: 1px solid #AAAAAA;opacity: 0.4; background-color: #0C0B09;height: 150px;width: 450px;padding-left: 20px;font-size: 18px;color: #AAAAAA">Message</textarea>
                        </div>
                    </div>
                </div>
            </div>



            <div class="row">
                <div class="offset-4  col-md-2 mt-4">
                    <button class="btn text-center" style="background-color: #CDA45E;width: 180px;border-radius: 60px;height: 50px;font-size: 18px;color: black;font-weight: 600;">Book a Table</button>
                </div>
            </div>
        </div>
    </section>

<section name="testimonials">
            <div class="container-fluid d-md-block d-none" style="background-color: #1A1814;height: 600px;width: 100%;position: relative;">
                <div class="row">
                    <div class="col-md-12">
                          <div id="demo1" class="carousel slide" data-ride="carousel">
    <ul class="carousel-indicators" id="testimonials" style="position: absolute;top: 550px;">
      <li data-target="#demo1" data-slide-to="0" class="active" style="height: 15px;width: 15px;border-radius: 50%;"></li>
      <li data-target="#demo1" data-slide-to="1" style="height: 15px;width: 15px;border-radius: 50%;"></li>
      <li data-target="#demo1" data-slide-to="2" style="height: 15px;width: 15px;border-radius: 50%;"></li>
      <li data-target="#demo1" data-slide-to="3" style="height: 15px;width: 15px;border-radius: 50%;"></li>
      <li data-target="#demo1" data-slide-to="4" style="height: 15px;width: 15px;border-radius: 50%;"></li>
    </ul>

                                 <div class="row">
                                    <div class="col-md-1 col-3">
                                        <P data-aos-duration="2000"  data-aos="fade-up" class="text-white mt-5 ml-5" style="color: #AAAAAA;font-weight: 600;letter-spacing: 3px;">TESTIMONIALS</P>
                                    </div>

                                    <div class="offset-1 col-md-2 mt-5 col-2 ">
                                        <p data-aos-duration="2000"  data-aos="fade-up" style="color: #AAAAAA;opacity: 0.4;position: absolute;top: -6px;">__________________</p>
                                    </div>



                                </div>
                                <div class="row ">
                                    <div class="offset-1 col-md-10 ml-4 col-11 ml-5">
                                        <h1 data-aos-duration="2000"  data-aos="fade-up" style="font-size: 45px;color: #CDA45E;font-family: Century751 SeBd BT;">What they're saying about us</h1>


                                    </div>
                                </div>
    <div class="carousel-inner">
      <div class="carousel-item active" data-aos-duration="1000"  data-aos="fade-up">
         <div class="row">
           <div class="offset-1 col-md-10">
               <div class="row">
                   <div class=" col-md-4">
                       <div class="card mt-5" style="border:none;">
                           <div class="card-header" style="height: 180px;background-color: #26231D;border:0px solid black;">
                               <div></div>
                               <p style="font-style: italic;font-size: 17px;color: #DCDCDB;"><i style="font-size: 28px;color: #D3AF71;" class="fa-solid fa-quote-left mr-2"></i> Proin iaculis purus consequat sem cure dignissim donec porttitora entum suscipit rhoncus. Accusantium quam, ultricies eget id, aliquam eget nibh et. Maecen aliquam, risus at semper.<i class="fa-solid fa-quote-left ml-2" style="font-size: 28px;color: #D3AF71; transform: rotate(180deg);"></i></p>
                           </div>

                           <div class="card-body" style="position: relative;height: 150px;background-color: #1A1814;">
                               <div style="height: 90px;width: 90px;border-radius: 50%;background-color: #41403C;position: absolute;top: -20px;"><img src="testimonials-1.jpg" style="height: 100%;width: 100%;border-radius: 50%;border:3px solid #41403C;"></div>
                               <p3 style="position: absolute;top: 75px;font-size: 18px;font-weight: 700;" class="text-white">Saul Goodman</p3>
                               <p2 style="position: absolute;top: 100px;font-size: 18px;font-weight: 600" class="text-white">Ceo & Founder</p2>
                           </div>
                       </div>
                   </div>

                    <div class=" col-md-4">
                       <div class="card mt-5" style="border:none;">
                           <div class="card-header" style="height: 180px;background-color: #26231D;border:0px solid black;">
                               <div></div>
                               <p style="font-style: italic;font-size: 17px;color: #DCDCDB;"><i style="font-size: 28px;color: #D3AF71;" class="fa-solid fa-quote-left mr-2"></i>Export tempor illum tamen malis malis eram quae irure esse labore quem cillum quid cillum eram malis quorum velit fore eram velit sunt aliqua noster fugiat irure amet legam anim culpa.<i class="fa-solid fa-quote-left ml-2" style="font-size: 28px;color: #D3AF71; transform: rotate(180deg);"></i></p>
                           </div>

                           <div class="card-body" style="position: relative;height: 150px;background-color: #1A1814;">
                               <div style="height: 90px;width: 90px;border-radius: 50%;background-color: #41403C;position: absolute;top: -20px;"><img src="testimonials-2.jpg" style="height: 100%;width: 100%;border-radius: 50%;border:3px solid #41403C;"></div>
                               <p3 style="position: absolute;top: 75px;font-size: 18px;font-weight: 700;" class="text-white">Sara Wilsson</p3>
                               <p2 style="position: absolute;top: 100px;font-size: 18px;font-weight: 600" class="text-white">Designer</p2>
                           </div>
                       </div>
                   </div>

                    <div class=" col-md-4">
                       <div class="card mt-5" style="border:none;">
                           <div class="card-header" style="height: 180px;background-color: #26231D;border:0px solid black;">
                               <div></div>
                               <p style="font-style: italic;font-size: 17px;color: #DCDCDB;"><i style="font-size: 28px;color: #D3AF71;" class="fa-solid fa-quote-left mr-2"></i>Enim nisi quem export duis labore cillum quae magna enim sint quorum nulla quem veniam duis minim tempor labore quem eram duis noster aute amet eram fore quis sint minim.<i class="fa-solid fa-quote-left ml-2" style="font-size: 28px;color: #D3AF71; transform: rotate(180deg);"></i></p>
                           </div>

                           <div class="card-body" style="position: relative;height: 150px;background-color: #1A1814;">
                               <div style="height: 90px;width: 90px;border-radius: 50%;background-color: #41403C;position: absolute;top: -20px;"><img src="testimonials-3.jpg" style="height: 100%;width: 100%;border-radius: 50%;border:3px solid #41403C;"></div>
                               <p3 style="position: absolute;top: 75px;font-size: 18px;font-weight: 700;" class="text-white">Jena Karlis</p3>
                               <p2 style="position: absolute;top: 100px;font-size: 18px;font-weight: 600" class="text-white">Store Owner</p2>
                           </div>
                       </div>
                   </div>
               </div>
           </div>   
         </div>
      </div>

       <div class="carousel-item" data-aos-duration="1000"  data-aos="fade-up">
         <div class="row">
           <div class="offset-1 col-md-10">
               <div class="row">
                   <div class=" col-md-4">
                       <div class="card mt-5" style="border:none;">
                           <div class="card-header" style="height: 180px;background-color: #26231D;border:0px solid black;">
                               <div></div>
                               <p style="font-style: italic;font-size: 17px;color: #DCDCDB;"><i style="font-size: 28px;color: #D3AF71;" class="fa-solid fa-quote-left mr-2"></i>Export tempor illum tamen malis malis eram quae irure esse labore quem cillum quid cillum eram malis quorum velit fore eram velit sunt aliqua noster fugiat irure amet legam anim culpa.<i class="fa-solid fa-quote-left ml-2" style="font-size: 28px;color: #D3AF71; transform: rotate(180deg);"></i></p>
                           </div>

                           <div class="card-body" style="position: relative;height: 150px;background-color: #1A1814;">
                               <div style="height: 90px;width: 90px;border-radius: 50%;background-color: #41403C;position: absolute;top: -20px;"><img src="testimonials-2.jpg" style="height: 100%;width: 100%;border-radius: 50%;border:3px solid #41403C;"></div>
                               <p3 style="position: absolute;top: 75px;font-size: 18px;font-weight: 700;" class="text-white">Sara Wilsson</p3>
                               <p2 style="position: absolute;top: 100px;font-size: 18px;font-weight: 600" class="text-white">Designer</p2>
                           </div>
                       </div>
                   </div>

                    <div class=" col-md-4">
                       <div class="card mt-5" style="border:none;">
                           <div class="card-header" style="height: 180px;background-color: #26231D;border:0px solid black;">
                               <div></div>
                               <p style="font-style: italic;font-size: 17px;color: #DCDCDB;"><i style="font-size: 28px;color: #D3AF71;" class="fa-solid fa-quote-left mr-2"></i>Enim nisi quem export duis labore cillum quae magna enim sint quorum nulla quem veniam duis minim tempor labore quem eram duis noster aute amet eram fore quis sint minim.<i class="fa-solid fa-quote-left ml-2" style="font-size: 28px;color: #D3AF71; transform: rotate(180deg);"></i></p>
                           </div>

                           <div class="card-body" style="position: relative;height: 150px;background-color: #1A1814;">
                               <div style="height: 90px;width: 90px;border-radius: 50%;background-color: #41403C;position: absolute;top: -20px;"><img src="testimonials-3.jpg" style="height: 100%;width: 100%;border-radius: 50%;border:3px solid #41403C;"></div>
                               <p3 style="position: absolute;top: 75px;font-size: 18px;font-weight: 700;" class="text-white">Jena Karlis</p3>
                               <p2 style="position: absolute;top: 100px;font-size: 18px;font-weight: 600" class="text-white">Store Owner</p2>
                           </div>
                       </div>
                   </div>

                    <div class=" col-md-4">
                       <div class="card mt-5" style="border:none;">
                           <div class="card-header" style="height: 210px;background-color: #26231D;border:0px solid black;">
                               <div></div>
                               <p style="font-style: italic;font-size: 17px;color: #DCDCDB;"><i style="font-size: 28px;color: #D3AF71;" class="fa-solid fa-quote-left mr-2"></i>Fugiat enim eram quae cillum dolore dolor amet nulla culpa multos export minim fugiat minim velit minim dolor enim duis veniam ipsum anim magna sunt elit fore quem dolore labore illum veniam.<i class="fa-solid fa-quote-left ml-2" style="font-size: 28px;color: #D3AF71; transform: rotate(180deg);"></i></p>
                           </div>

                           <div class="card-body" style="position: relative;height: 150px;background-color: #1A1814;">
                               <div style="height: 90px;width: 90px;border-radius: 50%;background-color: #41403C;position: absolute;top: -30px;"><img src="testimonials-4.jpg" style="height: 100%;width: 100%;border-radius: 50%;border:3px solid #41403C;"></div>
                               <p3 style="position: absolute;top: 65px;font-size: 18px;font-weight: 700;" class="text-white">Matt Brandon</p3>
                               <p2 style="position: absolute;top: 90px;font-size: 18px;font-weight: 600" class="text-white">Freelance</p2>
                           </div>
                       </div>
                   </div>
               </div>
           </div>   
         </div>
      </div>

         <div class="carousel-item " data-aos-duration="1000"  data-aos="fade-up">
         <div class="row">
           <div class="offset-1 col-md-10">
               <div class="row">
                   <div class=" col-md-4">
                       <div class="card mt-5" style="border:none;">
                           <div class="card-header" style="height: 180px;background-color: #26231D;border:0px solid black;">
                               <div></div>
                               <p style="font-style: italic;font-size: 17px;color: #DCDCDB;"><i style="font-size: 28px;color: #D3AF71;" class="fa-solid fa-quote-left mr-2"></i>Enim nisi quem export duis labore cillum quae magna enim sint quorum nulla quem veniam duis minim tempor labore quem eram duis noster aute amet eram fore quis sint minim.<i class="fa-solid fa-quote-left ml-2" style="font-size: 28px;color: #D3AF71; transform: rotate(180deg);"></i></p>
                           </div>

                           <div class="card-body" style="position: relative;height: 150px;background-color: #1A1814;">
                               <div style="height: 90px;width: 90px;border-radius: 50%;background-color: #41403C;position: absolute;top: -20px;"><img src="testimonials-3.jpg" style="height: 100%;width: 100%;border-radius: 50%;border:3px solid #41403C;"></div>
                               <p3 style="position: absolute;top: 75px;font-size: 18px;font-weight: 700;" class="text-white">Jena Karlis</p3>
                               <p2 style="position: absolute;top: 100px;font-size: 18px;font-weight: 600" class="text-white">Store Owner</p2>
                           </div>
                       </div>
                   </div>

                    <div class=" col-md-4">
                       <div class="card mt-5" style="border:none;">
                           <div class="card-header" style="height: 210px;background-color: #26231D;border:0px solid black;">
                               <div></div>
                               <p style="font-style: italic;font-size: 17px;color: #DCDCDB;"><i style="font-size: 28px;color: #D3AF71;" class="fa-solid fa-quote-left mr-2"></i>Fugiat enim eram quae cillum dolore dolor amet nulla culpa multos export minim fugiat minim velit minim dolor enim duis veniam ipsum anim magna sunt elit fore quem dolore labore illum veniam.<i class="fa-solid fa-quote-left ml-2" style="font-size: 28px;color: #D3AF71; transform: rotate(180deg);"></i></p>
                           </div>

                           <div class="card-body" style="position: relative;height: 150px;background-color: #1A1814;">
                               <div style="height: 90px;width: 90px;border-radius: 50%;background-color: #41403C;position: absolute;top: -20px;"><img src="testimonials-4.jpg" style="height: 100%;width: 100%;border-radius: 50%;border:3px solid #41403C;"></div>
                               <p3 style="position: absolute;top: 75px;font-size: 18px;font-weight: 700;" class="text-white">Matt Brandon</p3>
                               <p2 style="position: absolute;top: 100px;font-size: 18px;font-weight: 600" class="text-white">Freelance</p2>
                           </div>
                       </div>
                   </div>

                    <div class=" col-md-4">
                       <div class="card mt-5" style="border:none;">
                           <div class="card-header" style="height: 210px;background-color: #26231D;border:0px solid black;">
                               <div></div>
                               <p style="font-style: italic;font-size: 17px;color: #DCDCDB;"><i style="font-size: 28px;color: #D3AF71;" class="fa-solid fa-quote-left mr-2"></i>Quis quorum aliqua sint quem legam fore sunt eram irure aliqua veniam tempor noster veniam enim culpa labore duis sunt culpa nulla illum cillum fugiat legam esse veniam culpa fore nisi cillum quid.<i class="fa-solid fa-quote-left ml-2" style="font-size: 28px;color: #D3AF71; transform: rotate(180deg);"></i></p>
                           </div>

                           <div class="card-body" style="position: relative;height: 150px;background-color: #1A1814;">
                               <div style="height: 90px;width: 90px;border-radius: 50%;background-color: #41403C;position: absolute;top: -20px;"><img src="testimonials-5.jpg" style="height: 100%;width: 100%;border-radius: 50%;border:3px solid #41403C;"></div>
                               <p3 style="position: absolute;top: 75px;font-size: 18px;font-weight: 700;" class="text-white">John Larson</p3>
                               <p2 style="position: absolute;top: 100px;font-size: 18px;font-weight: 600" class="text-white">Enterpreneur</p2>
                           </div>
                       </div>
                   </div>
               </div>
           </div>   
         </div>
      </div>

      <div class="carousel-item " data-aos-duration="1000"  data-aos="fade-up">
         <div class="row">
           <div class="offset-1 col-md-10">
               <div class="row">
                   <div class=" col-md-4">
                       <div class="card mt-5" style="border:none;">
                           <div class="card-header" style="height: 210px;background-color: #26231D;border:0px solid black;">
                               <div></div>
                               <p style="font-style: italic;font-size: 17px;color: #DCDCDB;"><i style="font-size: 28px;color: #D3AF71;" class="fa-solid fa-quote-left mr-2"></i>Fugiat enim eram quae cillum dolore dolor amet nulla culpa multos export minim fugiat minim velit minim dolor enim duis veniam ipsum anim magna sunt elit fore quem dolore labore illum veniam.<i class="fa-solid fa-quote-left ml-2" style="font-size: 28px;color: #D3AF71; transform: rotate(180deg);"></i></p>
                           </div>

                           <div class="card-body" style="position: relative;height: 150px;background-color: #1A1814;">
                               <div style="height: 90px;width: 90px;border-radius: 50%;background-color: #41403C;position: absolute;top: -20px;"><img src="testimonials-4.jpg" style="height: 100%;width: 100%;border-radius: 50%;border:3px solid #41403C;"></div>
                               <p3 style="position: absolute;top: 75px;font-size: 18px;font-weight: 700;" class="text-white">Matt Brandon</p3>
                               <p2 style="position: absolute;top: 100px;font-size: 18px;font-weight: 600" class="text-white">Freelance</p2>
                           </div>
                       </div>
                   </div>

                    <div class=" col-md-4">
                       <div class="card mt-5" style="border:none;">
                           <div class="card-header" style="height: 210px;background-color: #26231D;border:0px solid black;">
                               <div></div>
                               <p style="font-style: italic;font-size: 17px;color: #DCDCDB;"><i style="font-size: 28px;color: #D3AF71;" class="fa-solid fa-quote-left mr-2"></i>Quis quorum aliqua sint quem legam fore sunt eram irure aliqua veniam tempor noster veniam enim culpa labore duis sunt culpa nulla illum cillum fugiat legam esse veniam culpa fore nisi cillum quid.<i class="fa-solid fa-quote-left ml-2" style="font-size: 28px;color: #D3AF71; transform: rotate(180deg);"></i></p>
                           </div>

                           <div class="card-body" style="position: relative;height: 150px;background-color: #1A1814;">
                               <div style="height: 90px;width: 90px;border-radius: 50%;background-color: #41403C;position: absolute;top: -20px;"><img src="testimonials-5.jpg" style="height: 100%;width: 100%;border-radius: 50%;border:3px solid #41403C;"></div>
                               <p3 style="position: absolute;top: 75px;font-size: 18px;font-weight: 700;" class="text-white">John Larson</p3>
                               <p2 style="position: absolute;top: 100px;font-size: 18px;font-weight: 600" class="text-white">Enterpreneur</p2>
                           </div>
                       </div>
                   </div>

                    <div class=" col-md-4">
                       <div class="card mt-5" style="border:none;">
                           <div class="card-header" style="height: 180px;background-color: #26231D;border:0px solid black;">
                               <div></div>
                               <p style="font-style: italic;font-size: 17px;color: #DCDCDB;"><i style="font-size: 28px;color: #D3AF71;" class="fa-solid fa-quote-left mr-2"></i>Proin iaculis purus consequat sem cure dignissim donec porttitora entum suscipit rhoncus. Accusantium quam, ultricies eget id, aliquam eget nibh et. Maecen aliquam, risus at semper.<i class="fa-solid fa-quote-left ml-2" style="font-size: 28px;color: #D3AF71; transform: rotate(180deg);"></i></p>
                           </div>

                           <div class="card-body" style="position: relative;height: 150px;background-color: #1A1814;">
                               <div style="height: 90px;width: 90px;border-radius: 50%;background-color: #41403C;position: absolute;top: -20px;"><img src="testimonials-1.jpg" style="height: 100%;width: 100%;border-radius: 50%;border:3px solid #41403C;"></div>
                               <p3 style="position: absolute;top: 75px;font-size: 18px;font-weight: 700;" class="text-white">Saul Goodman</p3>
                               <p2 style="position: absolute;top: 100px;font-size: 18px;font-weight: 600" class="text-white"></p2>
                           </div>
                       </div>
                   </div>
               </div>
           </div>   
         </div>
      </div>

      <div class="carousel-item " data-aos-duration="1000"  data-aos="fade-up">
         <div class="row">
           <div class="offset-1 col-md-10">
               <div class="row">
                   <div class=" col-md-4">
                       <div class="card mt-5" style="border:none;">
                           <div class="card-header" style="height: 210px;background-color: #26231D;border:0px solid black;">
                               <div></div>
                               <p style="font-style: italic;font-size: 17px;color: #DCDCDB;"><i style="font-size: 28px;color: #D3AF71;" class="fa-solid fa-quote-left mr-2"></i>Quis quorum aliqua sint quem legam fore sunt eram irure aliqua veniam tempor noster veniam enim culpa labore duis sunt culpa nulla illum cillum fugiat legam esse veniam culpa fore nisi cillum quid.<i class="fa-solid fa-quote-left ml-2" style="font-size: 28px;color: #D3AF71; transform: rotate(180deg);"></i></p>
                           </div>

                           <div class="card-body" style="position: relative;height: 150px;background-color: #1A1814;">
                               <div style="height: 90px;width: 90px;border-radius: 50%;background-color: #41403C;position: absolute;top: -20px;"><img src="testimonials-5.jpg" style="height: 100%;width: 100%;border-radius: 50%;border:3px solid #41403C;"></div>
                               <p3 style="position: absolute;top: 75px;font-size: 18px;font-weight: 700;" class="text-white">John Larson</p3>
                               <p2 style="position: absolute;top: 100px;font-size: 18px;font-weight: 600" class="text-white">Enterpreneur</p2>
                           </div>
                       </div>
                   </div>

                    <div class=" col-md-4">
                       <div class="card mt-5" style="border:none;">
                           <div class="card-header" style="height: 180px;background-color: #26231D;border:0px solid black;">
                               <div></div>
                               <p style="font-style: italic;font-size: 17px;color: #DCDCDB;"><i style="font-size: 28px;color: #D3AF71;" class="fa-solid fa-quote-left mr-2"></i>Proin iaculis purus consequat sem cure dignissim donec porttitora entum suscipit rhoncus. Accusantium quam, ultricies eget id, aliquam eget nibh et. Maecen aliquam, risus at semper.<i class="fa-solid fa-quote-left ml-2" style="font-size: 28px;color: #D3AF71; transform: rotate(180deg);"></i></p>
                           </div>

                           <div class="card-body" style="position: relative;height: 150px;background-color: #1A1814;">
                               <div style="height: 90px;width: 90px;border-radius: 50%;background-color: #41403C;position: absolute;top: -20px;"><img src="testimonials-1.jpg" style="height: 100%;width: 100%;border-radius: 50%;border:3px solid #41403C;"></div>
                               <p3 style="position: absolute;top: 75px;font-size: 18px;font-weight: 700;" class="text-white">Saul Goodman</p3>
                               <p2 style="position: absolute;top: 100px;font-size: 18px;font-weight: 600" class="text-white">Ceo & Founder</p2>
                           </div>
                       </div>
                   </div>

                    <div class=" col-md-4">
                       <div class="card mt-5" style="border:none;">
                           <div class="card-header" style="height: 180px;background-color: #26231D;border:0px solid black;">
                               <div></div>
                               <p style="font-style: italic;font-size: 17px;color: #DCDCDB;"><i style="font-size: 28px;color: #D3AF71;" class="fa-solid fa-quote-left mr-2"></i>Export tempor illum tamen malis malis eram quae irure esse labore quem cillum quid cillum eram malis quorum velit fore eram velit sunt aliqua noster fugiat irure amet legam anim culpa.<i class="fa-solid fa-quote-left ml-2" style="font-size: 28px;color: #D3AF71; transform: rotate(180deg);"></i></p>
                           </div>

                           <div class="card-body" style="position: relative;height: 150px;background-color: #1A1814;">
                               <div style="height: 90px;width: 90px;border-radius: 50%;background-color: #41403C;position: absolute;top: -20px;"><img src="testimonials-2.jpg" style="height: 100%;width: 100%;border-radius: 50%;border:3px solid #41403C;"></div>
                               <p3 style="position: absolute;top: 75px;font-size: 18px;font-weight: 700;" class="text-white">Sara Wilsson</p3>
                               <p2 style="position: absolute;top: 100px;font-size: 18px;font-weight: 600" class="text-white">Designer</p2>
                           </div>
                       </div>
                   </div>
               </div>
           </div>   
         </div>
      </div>
     
    </div>
<!--     <a class="carousel-control-prev" href="#demo1" data-slide="prev">
      <span class="carousel-control-prev-icon"></span>
    </a>
    <a class="carousel-control-next" href="#demo1" data-slide="next">
      <span class="carousel-control-next-icon"></span>
    </a> -->
  </div>

                    </div>
                </div>
            </div>
    </section>

    <section name="testimonials_resp">
        <div class="container-fluid d-md-none d-block" style="background-color: #1A1814;height: 600px;width: 100%;position: relative;">
            <div class="row">
                <div class="col-1">
                     <p data-aos-duration="1000"  data-aos="fade-up" class="text-white mt-5" style="letter-spacing: 2px;font-size: 14px;">TESTIMONIALS</p>
                </div>
                <div data-aos-duration="1000"  data-aos="fade-up" class="col-1 mt-5 text-white offset-3" style="position: absolute;top: -8px;">
                    ___________________
                </div>
            </div>

            <div class="row">
                <h2 data-aos-duration="1000"  data-aos="fade-up" class="ml-3" style="color: #CDA45E;font-family: Century751 SeBd BT;">What they're saying about us</h2>
            </div>
             
             <div id="demo" class="carousel slide" data-ride="carousel">
  <ul class="carousel-indicators">
    <li data-target="#demo" data-slide-to="0" class="active" style="position: absolute;top: 50px;height: 15px;width: 15px;border-radius: 50%;left: 110px;"></li>
    <li data-target="#demo" data-slide-to="1" style="position: absolute;top: 50px;height: 15px;width: 15px;border-radius: 50%;left: 130px; "></li>
    <li data-target="#demo" data-slide-to="2" style="position: absolute;top: 50px;height: 15px;width: 15px;border-radius: 50%;left: 150px;"></li>
    <li data-target="#demo" data-slide-to="3" style="position: absolute;top: 50px;height: 15px;width: 15px;border-radius: 50%;left: 170px;"></li>
    <li data-target="#demo" data-slide-to="4" style="position: absolute;top: 50px;height: 15px;width: 15px;border-radius: 50%;left: 190px;"></li>
  </ul>
  <div class="carousel-inner">
    <div class="carousel-item active">
            <div class=" col-12">
                <div class="row">
                    <div class="col-12">
                          <div class="card mt-5" style="border:none;">
                           <div class="card-header" style="height: 160px;background-color: #26231D;border:0px solid black;">
                               <div></div>
                               <p style="font-style: italic;font-size: 17px;color: #DCDCDB;"><i style="font-size: 28px;color: #D3AF71;" class="fa-solid fa-quote-left mr-2"></i>Proin iaculis purus consequat sem cure dignissim donec porttitora entum suscipit rhoncus. Accusantium quam, ultricies eget id, aliquam eget nibh et. Maecen aliquam, risus at semper.<i class="fa-solid fa-quote-left ml-2" style="font-size: 28px;color: #D3AF71; transform: rotate(180deg);"></i></p>
                           </div>

                           <div class="card-body" style="position: relative;height: 150px;background-color: #1A1814;">
                               <div style="height: 90px;width: 90px;border-radius: 50%;background-color: #41403C;position: absolute;top: -20px;"><img src="testimonials-1.jpg" style="height: 100%;width: 100%;border-radius: 50%;border:3px solid #41403C;"></div>
                               <p3 style="position: absolute;top: 75px;font-size: 18px;font-weight: 700;" class="text-white">Saul Goodman</p3>
                               <p2 style="position: absolute;top: 100px;font-size: 18px;font-weight: 600" class="text-white">Ceo & Founder</p2>
                           </div>
                       </div>
                    </div>
                </div>
            </div>  
    </div>

    <div class="carousel-item" data-aos-duration="1000"  data-aos="fade-up">
            <div class=" col-12">
                <div class="row">
                    <div class="col-12">
                          <div class="card mt-5" style="border:none;">
                           <div class="card-header" style="height: 180px;background-color: #26231D;border:0px solid black;">
                               <div></div>
                               <p style="font-style: italic;font-size: 17px;color: #DCDCDB;"><i style="font-size: 28px;color: #D3AF71;" class="fa-solid fa-quote-left mr-2"></i>Export tempor illum tamen malis malis eram quae irure esse labore quem cillum quid cillum eram malis quorum velit fore eram velit sunt aliqua noster fugiat irure amet legam anim culpa.<i class="fa-solid fa-quote-left ml-2" style="font-size: 28px;color: #D3AF71; transform: rotate(180deg);"></i></p>
                           </div>

                           <div class="card-body" style="position: relative;height: 150px;background-color: #1A1814;">
                               <div style="height: 90px;width: 90px;border-radius: 50%;background-color: #41403C;position: absolute;top: -20px;"><img src="testimonials-2.jpg" style="height: 100%;width: 100%;border-radius: 50%;border:3px solid #41403C;"></div>
                               <p3 style="position: absolute;top: 75px;font-size: 18px;font-weight: 700;" class="text-white">Sara Wilsson</p3>
                               <p2 style="position: absolute;top: 100px;font-size: 18px;font-weight: 600" class="text-white">Designer</p2>
                           </div>
                       </div>
                    </div>
                </div>
            </div>  
    </div>


    <div class="carousel-item">
            <div class=" col-12">
                <div class="row">
                    <div class="col-12">
                          <div class="card mt-5" style="border:none;">
                           <div class="card-header" style="height: 180px;background-color: #26231D;border:0px solid black;">
                               <div></div>
                               <p style="font-style: italic;font-size: 17px;color: #DCDCDB;"><i style="font-size: 28px;color: #D3AF71;" class="fa-solid fa-quote-left mr-2"></i>Enim nisi quem export duis labore cillum quae magna enim sint quorum nulla quem veniam duis minim tempor labore quem eram duis noster aute amet eram fore quis sint minim.<i class="fa-solid fa-quote-left ml-2" style="font-size: 28px;color: #D3AF71; transform: rotate(180deg);"></i></p>
                           </div>

                           <div class="card-body" style="position: relative;height: 150px;background-color: #1A1814;">
                               <div style="height: 90px;width: 90px;border-radius: 50%;background-color: #41403C;position: absolute;top: -20px;"><img src="testimonials-3.jpg" style="height: 100%;width: 100%;border-radius: 50%;border:3px solid #41403C;"></div>
                               <p3 style="position: absolute;top: 75px;font-size: 18px;font-weight: 700;" class="text-white">Jena Karlis</p3>
                               <p2 style="position: absolute;top: 100px;font-size: 18px;font-weight: 600" class="text-white">Store Owner</p2>
                           </div>
                       </div>
                    </div>
                </div>
            </div>  
    </div>

    <div class="carousel-item">
            <div class=" col-12">
                <div class="row">
                    <div class="col-12">
                          <div class="card mt-5" style="border:none;">
                           <div class="card-header" style="height: 180px;background-color: #26231D;border:0px solid black;">
                               <div></div>
                               <p style="font-style: italic;font-size: 17px;color: #DCDCDB;"><i style="font-size: 28px;color: #D3AF71;" class="fa-solid fa-quote-left mr-2"></i>Fugiat enim eram quae cillum dolore dolor amet nulla culpa multos export minim fugiat minim velit minim dolor enim duis veniam ipsum anim magna sunt elit fore quem dolore labore illum veniam.<i class="fa-solid fa-quote-left ml-2" style="font-size: 28px;color: #D3AF71; transform: rotate(180deg);"></i></p>
                           </div>

                           <div class="card-body" style="position: relative;height: 150px;background-color: #1A1814;">
                               <div style="height: 90px;width: 90px;border-radius: 50%;background-color: #41403C;position: absolute;top: -20px;"><img src="testimonials-4.jpg" style="height: 100%;width: 100%;border-radius: 50%;border:3px solid #41403C;"></div>
                               <p3 style="position: absolute;top: 75px;font-size: 18px;font-weight: 700;" class="text-white">Matt Brandon</p3>
                               <p2 style="position: absolute;top: 100px;font-size: 18px;font-weight: 600" class="text-white">Freelancer</p2>
                           </div>
                       </div>
                    </div>
                </div>
            </div>  
    </div>

     <div class="carousel-item">
            <div class=" col-12">
                <div class="row">
                    <div class="col-12">
                          <div class="card mt-5" style="border:none;">
                           <div class="card-header" style="height: 180px;background-color: #26231D;border:0px solid black;">
                               <div></div>
                               <p style="font-style: italic;font-size: 17px;color: #DCDCDB;"><i style="font-size: 28px;color: #D3AF71;" class="fa-solid fa-quote-left mr-2"></i>Fugiat enim eram quae cillum dolore dolor amet nulla culpa multos export minim fugiat minim velit minim dolor enim duis veniam ipsum anim magna sunt elit fore quem dolore labore illum veniam.<i class="fa-solid fa-quote-left ml-2" style="font-size: 28px;color: #D3AF71; transform: rotate(180deg);"></i></p>
                           </div>

                           <div class="card-body" style="position: relative;height: 150px;background-color: #1A1814;">
                               <div style="height: 90px;width: 90px;border-radius: 50%;background-color: #41403C;position: absolute;top: -20px;"><img src="testimonials-5.jpg" style="height: 100%;width: 100%;border-radius: 50%;border:3px solid #41403C;"></div>
                               <p3 style="position: absolute;top: 75px;font-size: 18px;font-weight: 700;" class="text-white">John Larson</p3>
                               <p2 style="position: absolute;top: 100px;font-size: 18px;font-weight: 600" class="text-white">Enterpreneur</p2>
                           </div>
                       </div>
                    </div>
                </div>
            </div>  
    </div>
    
    
  </div>
</div>

    </section>

     <section name="gallery">
           <div class="container-fluid d-md-block d-none" style="background-color: #0C0B09;height: 700px;width: 100%;">
               <div class="row" style="position: relative;">
                    <div class="col-md-1 offset-1 mt-5 ">
                        <p data-aos-duration="2000"  data-aos="fade-up" style="letter-spacing: 2px;font-weight: 500;color: #AAAAAA">GALLERY</p>
                    </div>

                    <div data-aos-duration="2000"  data-aos="fade-up" class="col-md-1  " style="color: #AAAAAA;  position: absolute;top: 40px;left: 200px;">
                        ________________
                    </div>
               </div>

               <div class="row">
                   <div class="offset-1 col-md-10">
                       <h1 data-aos-duration="2000"  data-aos="fade-up" style="color: #CDA45E;font-family: Century751 SeBd BT;">Some photos from Our Restaurant</h1>
                   </div>
               </div>

               <div class="row mt-5" data-aos-duration="1600"  data-aos="fade-up">
                   <div class="col-md-3 p-0" style="overflow: hidden;">
                       <img class="img1" src="gallery-1.jpg" style="">
                   </div>

                   <div class="col-md-3 p-0" style="overflow: hidden;">
                       <img src="gallery-2.jpg" class="img1">
                   </div>

                   <div class="col-md-3 p-0" style="overflow: hidden;">
                       <img src="gallery-3.jpg" class="img1">
                   </div>

                   <div class="col-md-3 p-0" style="overflow: hidden;">
                       <img src="gallery-4.jpg" class="img1">
                   </div>
               </div>

               <div class="row">
                   <div class="col-md-3 p-0" style="overflow: hidden;">
                       <img src="gallery-5.jpg" class="img1">
                   </div>

                   <div class="col-md-3 p-0" style="overflow: hidden;">
                       <img src="gallery-6.jpg" class="img1">
                   </div>

                   <div class="col-md-3 p-0" style="overflow: hidden;">
                       <img src="gallery-7.jpg" class="img1">
                   </div>

                   <div class="col-md-3 p-0" style="overflow: hidden;">
                       <img src="gallery-8.jpg" class="img1">
                   </div>
               </div>

               

           </div>
    </section>

    <section name="gallery_resp">
           <div class="container-fluid d-block d-md-none" style="background-color: #0C0B09;height: 2703px;width: 100%;">
               <div class="row" style="position: relative;">
                    <div class="col-1 offset-1 mt-5 ">
                        <p data-aos-duration="1000"  data-aos="fade-up" style="letter-spacing: 2px;font-weight: 500;" class="text-white">GALLERY</p>
                    </div>

                    <div data-aos-duration="1000"  data-aos="fade-up" class="col-1 text-white " style="position: absolute;top: 40px;left: 130px;">
                        ________________
                    </div>
               </div>

               <div class="row">
                   <div class="offset-1 col-11">
                       <h2 data-aos-duration="1000"  data-aos="fade-up" style="color: #CDA45E;font-family: Century751 SeBd BT;">Some photos from Our Restaurant</h2>
                   </div>
               </div>

               <div class="row mt-5">
                   <div class="col-11 ml-4">
                    <div style="overflow: hidden;"><img src="gallery-1.jpg" class="img2"></div>
                   </div>

                   <div class="col-11 ml-4">
                       <div style="overflow: hidden;"><img src="gallery-2.jpg" class="img2"></div>
                   </div>

                   <div class="col-11 ml-4">
                      <div style="overflow: hidden;"><img src="gallery-3.jpg" class="img2"></div>
                   </div>

                   <div class="col-11 ml-4">
                       <div style="overflow: hidden;"><img src="gallery-4.jpg" class="img2"></div>
                   </div>
               </div>

               <div class="row ">
                   <div class="col-11 ml-4">
                       <div style="overflow: hidden;"><img src="gallery-5.jpg" class="img2"></div>
                   </div>

                   <div class="col-11 ml-4">
                      <div style="overflow: hidden;"><img src="gallery-6.jpg" class="img2"></div>
                   </div>

                   <div class="col-11 ml-4">
                       <div style="overflow: hidden;"><img src="gallery-7.jpg" class="img2"></div>
                   </div>

                   <div class="col-11 ml-4">
                       <div style="overflow: hidden;"><img src="gallery-8.jpg" class="img2"></div>
                   </div>
               </div>

               

           </div>
    </section>

    <section name="chefs"> 
       <div class="container-fluid d-md-block d-none" style="background-color: #0C0B09;height: 580px;width: 100%;position: relative;">
            <div class="row">
                 <div class="col-md-1 offset-1 mt-5 ">
                        <p data-aos-duration="2000"  data-aos="fade-up" style="letter-spacing: 2px;font-weight: 500;color: #AAAAAA;">CHEFS</p>
                 </div>

                 <div data-aos-duration="2000"  data-aos="fade-up" class="col-md-1" style="position: absolute;top: 40px;left: 180px;">
                        ____________________
                 </div>
            </div>

             <div class="row">
                   <div class="offset-1 col-md-10">
                       <h2 data-aos-duration="2000"  data-aos="fade-up" style="color: #CDA45E;font-family: Century751 SeBd BT;">Our Proffesional Chefs</h2>
                   </div>
               </div>

            <div class="row mt-5">
                <div class="col-md-9 offset-2" >
                    <div class="row" >
                        <div class="col-md-4 chefs " data-aos="zoom-in" data-aos-duration="2000">
                            <h4 id="h1">Walter White </h4>
                            <p id="h2">Master chef</p>
                             <i class="fa-brands fa-twitter icon1" style=""></i>

                             <i class="fa-brands fa-facebook icon2"></i>

                             <i class="fa-brands fa-instagram icon3" ></i>

                             <i class="fa-brands fa-linkedin-in icon4"></i>
                            <div id="cont">
                                <img src="chefs-1.jpg" class="imgg">
                                 
                            </div>
                        </div>

                        <div class="col-md-4 chefs2" data-aos="zoom-in" data-aos-duration="2000">
                             <h4 id="h3">Sarah Jhonson </h4>
                            <p id="h33">Patissier</p>
                             <i class="fa-brands fa-twitter icon11" style=""></i>

                             <i class="fa-brands fa-facebook icon22"></i>

                             <i class="fa-brands fa-instagram icon33" ></i>

                             <i class="fa-brands fa-linkedin-in icon44"></i>
                            <div id="cont2">
                                <img src="chefs-2.jpg" class="imgg2">        
                            </div>
                        </div>

                        <div class="col-md-4 chefs3" data-aos="zoom-in" data-aos-duration="2000">
                            <h4 id="h4">William Anderson </h4>
                            <p id="h44">cook</p>
                            <i class="fa-brands fa-twitter icon111" style=""></i>

                             <i class="fa-brands fa-facebook icon222"></i>

                             <i class="fa-brands fa-instagram icon333" ></i>

                             <i class="fa-brands fa-linkedin-in icon444"></i>
                            <div id="count3">
                                <img src="chefs-3.jpg" class="imgg3">
                                
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
     </section>
      <section name="chefs_resp"> 
       <div class="container-fluid d-md-none d-block" style="background-color: #0C0B09;height: 1200px;width: 100%;position: relative;" >
            <div class="row">
                 <div class="col-1 offset-1 mt-5 ">
                        <p data-aos-duration="1000"  data-aos="fade-up" style="letter-spacing: 2px;font-weight: 500;color: #AAAAAA;">CHEFS</p>
                 </div>

                 <div data-aos-duration="1000"  data-aos="fade-up" class="col-1 " style="position: absolute;top: 40px;left: 110px;">
                        ____________________
                 </div>
            </div>

             <div class="row ">
                   <div class="offset-1 col-10">
                       <h2 data-aos-duration="1000"  data-aos="fade-up" style="color: #CDA45E;font-family: Century751 SeBd BT;">Our Proffesional Chefs</h2>
                   </div>
               </div>

            <div class="row mt-5">
                <div class="col-10 offset-2">
                    <div class="row " style="margin-bottom: 10px;">
                        <div class="col-11" >
                            <div>
                                <img src="chefs-1.jpg" style="height: 85%;width: 85%;background-size: 100% 100%;transform: scale(1.2);overflow: hidden;">
                                
                            </div>
                        </div>
                    </div>

                    <div class="row mt-2">
                        <div class="col-11">
                            <div>
                                <img src="chefs-2.jpg" style="height: 85%;width: 85%;background-size: 100% 100%;transform: scale(1.2);overflow: hidden;margin-top: 5px;">
                                
                            </div>
                        </div>
                    </div>

                    <div class="row ">
                        <div class="col-11 ">
                            <div>
                                <img src="chefs-3.jpg" style="height: 85%;width: 85%;background-size: 100% 100%;transform: scale(1.2);overflow: hidden;">
                                
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
     </section>

     <section name="contact" >
         <div class="container-fluid d-md-block d-none" style="background-color: #0C0B09;height: 1200px;width: 100%;position: relative;border-bottom: 1px solid white;">
             <div class="row">
                 <div class="col-md-1 offset-1 mt-5 ">
                        <p data-aos-duration="2000"  data-aos="fade-up" style="letter-spacing: 2px;font-weight: 500;color: #AAAAAA;">CONTACT</p>
                 </div>

                 <div class="col-md-1" style="position: absolute;top: 40px;left: 210px;" data-aos-duration="2000"  data-aos="fade-up">
                        ____________________
                 </div>
            </div>

            <div class="row">
                   <div class="offset-1 col-md-10">
                       <h2 style="color: #CDA45E;font-family: Century751 SeBd BT;" data-aos-duration="2000"  data-aos="fade-up">Contact Us</h2>
                   </div>
            </div>

            <div class="row mt-5">
                <div class="col-md-12" data-aos-duration="2000"  data-aos="fade-up">
                    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3764.3949600924757!2d75.21512587366242!3d19.35204374325165!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3bdb6920911c76df%3A0x69a5c2f3442c393d!2sLaksh%20Tech%20Hub!5e0!3m2!1sen!2sin!4v1712850844881!5m2!1sen!2sin" width="600" style="border:0;width: 100%;height: 400px;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade "></iframe>
                </div>
            </div>

            <div class="row mt-5" >
                <div class="col-md-1 offset-1">
                    <div style="height: 50px;width: 50px;border-radius: 50%;background-color: #CDA45E;position: relative;"><i style="position: absolute;top: 10px;left: 14px;color: white;font-size: 24px;" class="fa-solid fa-location-dot"></i></div>

                </div>

                    <div class="col-md-2" style="position: relative;">
                        <p style="position: absolute;left: -30px;color: white;font-size: 20px;font-weight: 600;">Location:</p>
                        <p style="position: absolute;left: -30px;color: white;font-size: 13px;top: 35px;">A108 Adam Street, New York, NY 535022</p>
                    </div>

                    <div class="col-md-3">
                         <input type="text" name="" placeholder="Your Name" style="border: 1px solid #AAAAAA;opacity: 0.4;background-color: #0C0B09;height: 45px;width: 350px;padding-left: 15px;font-size: 18px;color: white;">
                    </div>

                    <div class="col-md-3 ml-5">
                         <input type="text" name="" placeholder="Your Email" style="border: 1px solid #AAAAAA;opacity: 0.4;background-color: #0C0B09;height: 45px;width: 350px;padding-left: 15px;font-size: 18px;color: white;">
                    </div>
            </div>

              <div class="row mt-5" >
                <div class="col-md-1 offset-1">
                    <div style="height: 50px;width: 50px;border-radius: 50%;background-color: #CDA45E;position: relative;"><i style="position: absolute;top: 10px;left: 14px;color: white;font-size: 24px;" class="fa-solid fa-clock"></i></div>

                </div>

                    <div class="col-md-2" style="position: relative;">
                        <p style="position: absolute;left: -30px;color: white;font-size: 20px;font-weight: 600;">Open Hours:</p>
                        <p style="position: absolute;left: -30px;color: white;font-size: 13px;top: 35px;">Monday-Saturday:</p>
                          <p style="position: absolute;left: -30px;color: white;font-size: 13px;top: 55px;">11:00 AM - 2300 PM</p>
                    </div>

                    <div class="col-md-3">
                         <input type="text" name="" placeholder="Subject" style="border: 1px solid #AAAAAA;opacity: 0.4;background-color: #0C0B09;height: 45px;width: 740px;padding-left: 15px;font-size: 18px;color: white;">
                    </div>

            </div>

             <div class="row mt-5" >
                <div class="col-md-1 offset-1">
                    <div style="height: 50px;width: 50px;border-radius: 50%;background-color: #CDA45E;position: relative;"><i style="position: absolute;top: 10px;left: 14px;color: white;font-size: 24px;" class="fa-regular fa-envelope"></i></div>

                </div>

                    <div class="col-md-2" style="position: relative;">
                        <p style="position: absolute;left: -30px;color: white;font-size: 20px;font-weight: 600;">Email:</p>
                        <p style="position: absolute;left: -30px;color: white;font-size: 13px;top: 35px;">info@example.com</p>
                         
                    </div>

                    <div class="col-md-3">
                         <textarea type="text" name="" placeholder="Message" style="border: 1px solid #AAAAAA;opacity: 0.4;background-color: #0C0B09;height: 180px;width: 740px;padding-left: 15px;font-size: 18px;color: white;"></textarea>
                    </div>

            </div>

             <div class="row mt-3" >
                <div class="col-md-1 offset-1">
                    <div style="height: 50px;width: 50px;border-radius: 50%;background-color: #CDA45E;position: relative;"><i style="position: absolute;top: 10px;left: 14px;color: white;font-size: 24px;" class="fa-solid fa-mobile"></i></div>

                </div>

                    <div class="col-md-2" style="position: relative;">
                        <p style="position: absolute;left: -30px;color: white;font-size: 20px;font-weight: 600;">Call:</p>
                        <p style="position: absolute;left: -30px;color: white;font-size: 13px;top: 35px;">+1 5589 55488 55s</p>
                         
                    </div>
                    
            </div>

            <div class="row">
                <div class="col-md-2 offset-6">
                    <button style="color: black;background-color: #CDA45E;width: 160px;border-radius: 30px;height: 45px;font-weight: 600" class="btn ">Send Message</button>

                </div>
            </div>
         </div>
     </section>

     <section name="contact_resp" >
         <div class="container-fluid d-md-none d-block" style="background-color: #0C0B09;height: 1560px;width: 100%;position: relative;border-bottom: 1px solid white;">
             <div class="row">
                 <div class="col-md-1 offset-1 mt-5 ">
                        <p data-aos-duration="1000"  data-aos="fade-up" style="letter-spacing: 2px;font-weight: 500;color: #AAAAAA;">CONTACT</p>
                 </div>

                 <div data-aos-duration="1000"  data-aos="fade-up" class="col-1" style="position: absolute;top: 40px;left: 140px;">
                        ____________________
                 </div>
            </div>

            <div class="row">
                   <div class="offset-1 col-md-10">
                       <h2 data-aos-duration="1000"  data-aos="fade-up" style="color: #CDA45E;font-family: Century751 SeBd BT;">Contact Us</h2>
                   </div>
            </div>

            <div class="row mt-5">
                <div class="col-md-12" data-aos-duration="1000"  data-aos="fade-up">
                    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3764.3949600924757!2d75.21512587366242!3d19.35204374325165!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3bdb6920911c76df%3A0x69a5c2f3442c393d!2sLaksh%20Tech%20Hub!5e0!3m2!1sen!2sin!4v1712850844881!5m2!1sen!2sin" width="600" style="border:0;width: 100%;height: 400px;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade "></iframe>
                </div>
            </div>

            <div class="row mt-5" >
                <div class="col-3 ">
                    <div style="height: 50px;width: 50px;border-radius: 50%;background-color: #CDA45E;position: relative;"><i style="position: absolute;top: 13px;left: 16px;color: white;font-size: 24px;" class="fa-solid fa-location-dot"></i></div>

                </div>

                    <div class="col-6" style="position: relative;">
                        <p style="position: absolute;left: -40px;color: white;font-size: 20px;font-weight: 600;top: ">Location:</p>
                        <p style="position: absolute;left: -40px;color: white;font-size: 13px;top: 32px;opacity: 0.6;">A108 Adam Street, New York, NY 535022</p>
                    </div>

            </div>

            <div class="row mt-5" >
                <div class="col-3 ">
                    <div style="height: 50px;width: 50px;border-radius: 50%;background-color: #CDA45E;position: relative;"><i style="position: absolute;top: 13px;left: 13px;color: white;font-size: 24px;" class="fa-solid fa-clock"></i></div>

                </div>

                    <div class="col-6" style="position: relative;">
                        <p style="position: absolute;left: -40px;color: white;font-size: 20px;font-weight: 600;top: ">Open Hours:</p>
                        <p style="position: absolute;left: -40px;color: white;font-size: 13px;top: 32px;opacity: 0.6;">Monday-Saturday:</p>
                        <p style="position: absolute;left: -40px;color: white;font-size: 13px;top: 50px;opacity: 0.6;">11:00 AM - 2300 PM</p>
                    </div>

            </div>

            <div class="row mt-5" >
                <div class="col-3 ">
                    <div style="height: 50px;width: 50px;border-radius: 50%;background-color: #CDA45E;position: relative;"><i style="position: absolute;top: 13px;left: 13px;color: white;font-size: 24px;" class="fa-regular fa-envelope"></i></div>

                </div>

                    <div class="col-6" style="position: relative;">
                        <p style="position: absolute;left: -40px;color: white;font-size: 20px;font-weight: 600;top: ">Email:</p>
                        <p style="position: absolute;left: -40px;color: white;font-size: 13px;top: 32px;opacity: 0.6;">info@example.com</p>
                    </div>

            </div>

            <div class="row mt-5" >
                <div class="col-3 ">
                    <div style="height: 50px;width: 50px;border-radius: 50%;background-color: #CDA45E;position: relative;"><i style="position: absolute;top: 13px;left: 16px;color: white;font-size: 24px;" class="fa-solid fa-mobile"></i></div>

                </div>

                    <div class="col-6" style="position: relative;">
                        <p style="position: absolute;left: -40px;color: white;font-size: 20px;font-weight: 600;top: ">Call:</p>
                        <p style="position: absolute;left: -40px;color: white;font-size: 13px;top: 32px;opacity: 0.6;">+1 5589 55488 55s</p>
                    </div>

            </div>

           
             
             <div class="row mt-5">
                <div class="col-12">
                    
                         <input type="text" name="" placeholder="Your Name" style="border: 1px solid #AAAAAA;opacity: 0.4;background-color: #0C0B09;height: 45px;width: 100%;padding-left: 20px;font-size: 18px;color: #AAAAAA;">
                    
                </div>
            </div>

            <div class="row mt-3">
                <div class="col-12">
                    
                         <input type="text" name="" placeholder="Your Email" style="border: 1px solid #AAAAAA;opacity: 0.4;background-color: #0C0B09;height: 45px;width: 100%;padding-left: 20px;font-size: 18px;color: #AAAAAA;">
                    
                </div>
            </div>

             <div class="row mt-3">
                <div class="col-12">
                    
                         <input type="text" name="" placeholder="Subject" style="border: 1px solid #AAAAAA;opacity: 0.4;background-color: #0C0B09;height: 45px;width: 100%;padding-left: 20px;font-size: 18px;color: #AAAAAA;">
                    
                </div>
            </div>

            <div class="row mt-3">
                <div class="col-12">
                    <textarea type="text" name="" placeholder="Message" style="border: 1px solid #AAAAAA;opacity: 0.4;background-color: #0C0B09;height: 180px;width: 100%;padding-left: 20px;font-size: 18px;color: white;"></textarea>
                </div>
            </div>

            <div class="row mt-4">
                <div class="col-4 offset-3">
                     <button style="color: white;background-color: #D3AF71;width: 160px;border-radius: 30px;height: 45px;" class="btn ">Send Message</button>

                </div>
            </div>
            
         </div>
     </section>
       
       <section name="footer">
             <div class="container-fluid d-md-block d-none" style="background-color: #0C0B09;height: 400px;width: 100%;border-bottom: 1px solid white;border-width: 0.5px;">
                 <div class="offset-1 col-md-10">
                     <div class="row">
                         <div class="col-md-3">
                             <p class="text-white mt-5" style="font-size: 24px;">RESTAURANTLY</p>
                             <p class="text-white" style="width: 150px;">A108 Adam Street NY 535022, USA</p>
                             <p class="text-white" style="width: 200px;">Phone: +1 5589 55488 55 Email: info@example.com</p>
                             <div class="d-flex">
                                 <div  class="mr-2 iconf1" class="d-flex"><i  style="position: absolute;top: 10px;left: 10px;" class="fa-brands fa-twitter"></i></div>

                                 <style type="text/css">
                                    .iconf1{
                                        width: 35px;
                                        height:35px;
                                        background-color: #28251F;
                                        color: white;
                                        border-radius: 50%;
                                        position: relative;
                                    }       
                                     .iconf1:hover{
                                        background-color: #CDA45E;
                                     }
                                 </style>

                                 <div class="mr-2 iconf1" class="d-flex"><i style="position: absolute;top: 10px;left: 10px;" class="fa-brands fa-facebook"></i></div>

                                 <div class="mr-2 iconf1" class="d-flex"><i style="position: absolute;top: 10px;left: 10px;" class="fa-brands fa-instagram"></i></div>

                                 <div class="mr-2 iconf1" class="d-flex"><i style="position: absolute;top: 10px;left: 10px;" class="fa fa-skype"></i></div>

                                 <div class="mr-2 iconf1" class="d-flex"><i style="position: absolute;top: 10px;left: 10px;" class="fa-brands fa-linkedin-in"></i></div>
                                 
                             </div>
                         </div>

                          <div class="col-md-3 mt-5 text-white">
                             <p style="font-family: Franklin Gothic Heavy;">Useful Links</p>
                             <p style="color: #D3AF71;font-weight: 600;">> <a href="" style="color: white;">  Home</a></p>
                             <p class="p-0" style="color: #D3AF71;font-weight: 600;">> <a href="" style="color: white;">  About us</a></p>
                              <p style="color: #D3AF71;font-weight: 600;">> <a href="" style="color: white;">  Servises</a></p>
                             <p class="p-0" style="color: #D3AF71;font-weight: 600;">> <a href="" style="color: white;">  Terms of service</a></p>
                             <p class="p-0" style="color: #D3AF71;font-weight: 600;">> <a href="" style="color: white;">  Privacy Policy</a></p>

                         </div>

                         <div class="col-md-3 mt-5 text-white">
                             <p style="font-family:Franklin Gothic Heavy;">Our Services</p>
                             <p style="color: #D3AF71;font-weight: 600;">> <a href="" style="color: white;">  Web Design</a></p>
                             <p class="p-0" style="color: #D3AF71;font-weight: 600;">> <a href="" style="color: white;">  Web Development</a></p>
                              <p style="color: #D3AF71;font-weight: 600;">> <a href="" style="color: white;">  Product Management</a></p>
                             <p class="p-0" style="color: #D3AF71;font-weight: 600;">> <a href="" style="color: white;">  Marketing</a></p>
                             <p class="p-0" style="color: #D3AF71;font-weight: 600;">> <a href="" style="color: white;">  Graphics Design</a></p>

                         </div>

                            <div class="col-md-3 mt-5 text-white" style="position: relative;">
                             <p style="font-family:Franklin Gothic Heavy;">Our Newsletter</p>
                             <p style="width: 350px;">Tamen quem nulla quae legam multos aute sint culpa legam noster magna</p>
                             <input class="mt-3" type="text" name="" style="background-color: #28251F;border:none;height: 45px;width: 250px;border-radius: 50px;" >
                             <div style="background-color: #CDA45E;border:none;height: 50px;width: 130px;border-radius: 50px;position: absolute;top: 118px;left: 180px;" ><p style="position: absolute;top: 12px;left: 15px;color: black;font-weight: 600;">Subscribe</p></div>
                             
                         </div>
                     
                     </div>

                        
                 </div>
             </div>         
     </section>

     <section name="footer_resp">
             <div class="container-fluid d-md-none d-block" style="background-color: #0C0B09;height: 1080px;width: 100%;border-bottom: 1px solid white;border-width: 0.5px;">
                 <div class=" col-md-10">
                     <div class="row">
                         <div class="col-md-3">
                             <p class="text-white mt-5">RESTAURANTLY</p>
                             <p class="text-white" style="width: 150px;">A108 Adam Street NY 535022, USA</p>
                             <p class="text-white" style="width: 200px;">Phone: +1 5589 55488 55 Email: info@example.com</p>
                             <div class="d-flex">
                                 <div class="mr-2" style="width: 35px;height:35px;background-color: #28251F;color: white;border-radius: 50%;position: relative;" class="d-flex"><i style="position: absolute;top: 10px;left: 10px;" class="fa-brands fa-twitter"></i></div>

                                 <div class="mr-2" style="width: 35px;height:35px;background-color: #28251F;color: white;border-radius: 50%;position: relative;" class="d-flex"><i style="position: absolute;top: 10px;left: 10px;" class="fa-brands fa-facebook"></i></div>

                                 <div class="mr-2" style="width: 35px;height:35px;background-color: #28251F;color: white;border-radius: 50%;position: relative;" class="d-flex"><i style="position: absolute;top: 10px;left: 10px;" class="fa-brands fa-instagram"></i></div>

                                 <div class="mr-2" style="width: 35px;height:35px;background-color: #28251F;color: white;border-radius: 50%;position: relative;" class="d-flex"><i style="position: absolute;top: 10px;left: 10px;" class="fa fa-skype"></i></div>

                                 <div class="mr-2" style="width: 35px;height:35px;background-color: #28251F;color: white;border-radius: 50%;position: relative;" class="d-flex"><i style="position: absolute;top: 10px;left: 10px;" class="fa-brands fa-linkedin-in"></i></div>
                                 
                             </div>
                         </div>

                          <div class="col-md-3 mt-5 text-white">
                             <p>Useful Links</p>
                             <p style="color: #D3AF71;font-weight: 600;">> <a href="" style="color: white;">  Home</a></p>
                             <p class="p-0" style="color: #D3AF71;font-weight: 600;">> <a href="" style="color: white;">  About us</a></p>
                              <p style="color: #D3AF71;font-weight: 600;">> <a href="" style="color: white;">  Servises</a></p>
                             <p class="p-0" style="color: #D3AF71;font-weight: 600;">> <a href="" style="color: white;">  Terms of service</a></p>
                             <p class="p-0" style="color: #D3AF71;font-weight: 600;">> <a href="" style="color: white;">  Privacy Policy</a></p>

                         </div>

                         <div class="col-md-3 mt-5 text-white">
                             <p>Our Services</p>
                             <p style="color: #D3AF71;font-weight: 600;">> <a href="" style="color: white;">  Web Design</a></p>
                             <p class="p-0" style="color: #D3AF71;font-weight: 600;">> <a href="" style="color: white;">  Web Development</a></p>
                              <p style="color: #D3AF71;font-weight: 600;">> <a href="" style="color: white;">  Product Management</a></p>
                             <p class="p-0" style="color: #D3AF71;font-weight: 600;">> <a href="" style="color: white;">  Marketing</a></p>
                             <p class="p-0" style="color: #D3AF71;font-weight: 600;">> <a href="" style="color: white;">  Graphics Design</a></p>

                         </div>

                            <div class="col-md-3 mt-5 text-white" style="position: relative;">
                             <p>Our Services</p>
                             <p style="width: 450px;">Tamen quem nulla quae legam multos aute sint culpa legam noster magna</p>
                             <input class="mt-3" type="text" name="" style="background-color: #28251F;border:none;height: 45px;width: 100%  ;border-radius: 50px;" >
                             <div style="background-color: #CDA45E;border:none;height: 50px;width: 130px;border-radius: 50px;position: absolute;top: 118px;left: 320px;" ><p style="position: absolute;top: 10px;left: 15px;font-size: 18px;color: black;font-weight: 600;">Subscribe</p></div>
                             
                         </div>
                     
                     </div>

                        
                 </div>
             </div>         
     </section>

      <section name="footer_copyright">
           <div class="container-fluid d-md-block d-none" style="height: 100px;background-color: #000000;">
               <div class="row">
                   <div class="col-md-4 mt-4 " style="margin-left: 520px;">
                       <div class="text-white"><i class="fa-regular fa-copyright"></i> Copyright<b> Restaurantly. </b> All Rights Reserved</div>
                   </div>
               </div>

               <div class="row">
                   <div class="col-md-4 mt-1"style="margin-left: 580px;">
                     <div class="text-white">Designed by <span style="color: #CDA45E;font-weight: 600;">Sarvesh Salunke</span></div>
                   </div>
               </div>
           </div>
     </section>

      <section name="footer_copyright">
           <div class="container-fluid d-md-none d-block" style="height: 100px;background-color: #000000;">
               <div class="row">
                   <div class="col-10 mt-4" style="margin-left: 60px;">
                       <div class="text-white"><i class="fa-regular fa-copyright"></i> Copyright<b> Restaurantly. </b> All Rights Reserved</div>
                   </div>
               </div>

               <div class="row">
                   <div class="col-6 mt-2"style="margin-left: 120px;">
                     <div class="text-white">Designed by <span style="color: #CDA45E;">Sarvesh Salunke</span></div>
                   </div>
               </div>
           </div>
     </section>
    
     <script>
  AOS.init();
</script>

</body>
</html>



                    
