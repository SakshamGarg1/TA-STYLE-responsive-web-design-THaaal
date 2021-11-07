writeCode

- Create a responsive layout according to the design shown below.

#### Large Screen view(Above 768px)

![Responsive Layout Assignment](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/rwd/ex-2.png)

#### Small Screen view(Below 768px)

1. Figure what would be the best possible way to display the layout on small screens.

2. Create hmaburger icon to toggle menu on mobile view.

- Using CSS resets is necessary.
- Use semantic tags and keep the nesting and indentation proper.
- Pay attention to the codes, your code quality matters a lot.
- Try to implement the layout as exactly as it has been provided in the design.
- Pay attention to minor things like spacing, alignment, size, etc.
- Use "Nunito" font-family for the assignment.
- Figure out the best possible way to display the layout on small screens.
- Create hmaburger icon to toggle menu on small screen view.
- Once you are done with the assignment connect with the mentor and get the code reviewed.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="https://kit.fontawesome.com/df2423167d.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="assets/style.css">
</head>


<body>
<header id="container" class="container" > 
  <!-- <img src="assets/media/banner.png" alt="banner" width="100%"> -->
  
   <div class="social top-center">
    <i class="fab fa-facebook-f"></i>
       
    <i class="fab fa-twitter"></i>
    <i class="fab fa-dribbble"></i>
    <i class="fab fa-linkedin-in"></i>
    

     <nav class="nav">
         <img src="assets/media/logo.png" alt="logo" width="90px" height="80px">
         <p>FLEX</p>
         <a class="home" href="index.html">HOME</a>
         <a href="#services">SERVICES</a>
         <a href="#portfolio">PORTFOLIO</a>
         <a href="#team">TEAM</a>
         <a href="gallery.html">GALLERY</a>
         <a class="contact-nav" href="#contact">CONTACT</a>
     </nav>
    </div>
    <h1 class="heading" >DIGITAL MARKETING <hr class="dm" ></h1>
    <p class="head-text" >more visitors to your website</p>
    <a class="design" href="#">LET US DESIGN!</a>
</header>



<div class="dotflex" >
    <div class="dots dots1" ></div>
    <div class="dots dots2 " ></div>
    <div class="dots dots2 "></div>

</div>


  <!-- Second Article  -->
  <!-- Second Article  -->

  <article >
      <h2 id="services" class="h5">OUR SERVICES</h2>
      <p class="p"> WE DESIGN MOBILE FIRST WEBSITE FOR YOU</p>
      <div class="flex1">
        <div class="box box-1-1"><a href="">
            <i class="far fa-file-code"></i></a>
        </div>
        <div class="box box-1-2"><a href="">
            <i class="far fa-paper-plane"></i></a>
        </div>
        <div class="box box-1-3"><a href="">
            <i class="fas fa-university"></i></a>
        </div>
        <div class="box box-1-4"><a href="">
            <i class="fas fa-flask"></i></a>
        </div>
    </div>
  </article>




<!-- third article  -->
  <article>
    <h2 id="portfolio" class="h5" >OUR PORTFOLIO</h2>
    <p class="p p2">AMAZING WORK FOR OUR CLIENT</p>
    <div class="portfolio-img">
    <img class="img" src="assets/media/portfolio/p1.jpg" alt="pic1" width="180px" height="180px">
    <img class="img"  src="assets/media/portfolio/p2.jpg" alt="pic2" width="180px" height="180px">
    <img class="img"  src="assets/media/portfolio/p3.jpg" alt="pic3" width="180px" height="180px">
    <img class="img"  src="assets/media/portfolio/p4.jpg" alt="pic4" width="180px" height="180px">
    </div>
    <div class="portfolio-img">

    
    <img class="img" src="assets/media/portfolio/p5.jpg" alt="pic5" width="180px" height="180px">
    <img class="img" src="assets/media/portfolio/p6.jpg" alt="pic6" width="180px" height="180px">
    <img class="img" src="assets/media/portfolio/p7.jpg" alt="pic6" width="180px" height="180px">
    <img class="img" src="assets/media/portfolio/p8.jpg" alt="pic6" width="180px" height="180px">

    </div>

</article>


<section>
<article id="team" >
   <h2><a class="teamh2"  href=""> OUR TEAM</a> </h2>
   <p class="p p3" >OUR PEOPLE ARE UNITED FOR YOUR SUCCESS</p>
   <img class="m1img img m1mar" src="assets/media/member1.jpg" alt="m1" width="180px" height="180px">
   <img class="m1img img" src="assets/media/member2.jpg" alt="m1" width="180px" height="180px">
   <img class="m1img img" src="assets/media/member3.jpg" alt="m1" width="180px" height="180px">
   <img class="m1img img" src="assets/media/member4.jpg" alt="m1" width="180px" height="180px">
   
   <p class="p3-2" >DESIGN SKILLS</p>
   <p class="p p3-3" >Lorem, ipsum dolor sit amet e dignissimos labore! amit elit</p>
   <div class="article3">
<div class="fake-data" >
    <div><p class="dd-main dd1 " > PHOTOSHOP 90%</p> <p class="dd2-main dd2-4"></p> </div>
    <div class="dd2-1"><p class="dd-main dd2 ">HTML CSS 80%</p><p class="dd2-main dd2-2"></p></div>
    <div class="dd2-1"> <p class="dd-main dd3 ">DEVELOPMENT 70%</p> <p class="dd2-main dd2-3"></p></div>  
    <div class="dd2-1"> <p class="dd-main dd4  " >MARKETING 80%</p><p class="dd2-main dd2-2"></p></div>  

</div>

<div class="fake-text" >
<p>
    Aliqum ipsum dolor, sit amet consectetur adipisicing elit. Consequatur quisquam fugiat ea aliquid nostrum neque tenetur, pariatur cupiditate quasi iusto repellendus itaque et velit voluptates in consectetur accusantium quis libero.
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae quis atque ipsum s culpa veniam!</p>
    
    <p class="gap">amet consectetur <span class="orange">Too CSS</span> elit. Recusandae quis atque ipsum voluptas, laboriosam ut quibusdam distinctio veniam? Suscipit possimus quo vero eum illo blanditiis magnam, fuga voluptas culpa veniam!
    ctetur adipisicing elit. Recusandae quis atque ipsum voluptas, laboriosam ut quibusdam distinctio veniam? Suscipit possimus quo vero eum illo blanditiis magnam, fuga voluptas culpa veniam
 </p>

</div>
</div>

</article>
</section>



<section>
<h2 id="contact" class="h5" > CONTACT</h2>
<p class="p7">SEND MESSAGE TO US</p>
<article>
   <div> <iframe class="map" src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d13503.55258991799!2d76.355385!3d32.2072445!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x71ff0cae0784712d!2sAltCampus%20Services%20Pvt.%20Ltd!5e0!3m2!1sen!2sin!4v1634116093121!5m2!1sen!2sin" width="800" height="600" style="border:0;" allowfullscreen="" loading="lazy"></iframe></div>
   <div class="form-text"> 
       <div class="form-text-main">
           <p>Flex Template dolor sit, amet consectetur adipisicing <span class="green">templete<span class="blue">mo</span>  </span> elit. Veritatis, magni. Repellat, voluptas autem facilis in tempore minus accusantium sunt provident maxime aut eos, eius veritatis, est fugiat iure. Voluptatem, laudantium?
           Impedit ipsum hic cumque sunt porro quidem <span class="orange">voluptatibus facilis </span>repellendus vero quibusdam labore ullam, voluptates illo qui optio veniam neque esse veritatis laboriosam, tenetur ipsa perferendis nulla <span class="bold"> Template mo inventore.</span> </p>
 <P class="para2"> Please visit <span class="orange"> Too css </span>amet consectetur adipisicing elit. Recusandae quis atque ipsum voluptas, laboriosam ut quibusdam distinctio veniam? Suscipit possimus quo vero eum illo blanditiis magnam, fuga voluptas culpa veniam!
            <p class="form-text-main1" >Phone:033-033-0660</p>
            <p class="form-text-main1" >Email: <span class="orange"> infocompany.com </span> </p>
            <p class="form-text-main1">Address:880 De Best Studio, Fork Street,San Fransisco</p>

       </div>
       <div class="form">
        <input class="form-input" type="text" name="Name" id="Name" placeholder="Your Name">
        
        <input class="form-input" type="text" name="Email" id="Email" placeholder="Your Email">
        <input class="form-input" type="text" name="college" id="College" placeholder="Subject">
        <textarea class="form-input" name="text" id="text" cols="30" rows="5"placeholder="Message"></textarea>
        <button class="btn ">SEND MESSAGE</button>
        </div>
       
   </div>
</article>
</section>

<footer>
    <p  class="footer-text" >Copyright © 2020 Company Name.Design TemplateMO </p>
     <a  href="#container"><button class="btn-footer"> Back to top</button></a>
</footer>
</body>
</html>
