writeCode

- Create a responsive layout according to the design shown below.

#### Large Screen view(Above 768px)

![Responsive Layout Assignment](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/rwd/ex-1-desktop-view.png)

#### Small Screen view(Below 768px)

![Responsive Layout Assignment](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/rwd/ex-1-mob-view.png)

- Using CSS resets is necessary.

- Use semantic tags and keep the nesting and indentation proper.

- Pay attention to the codes, your code quality matters a lot.

- Try to implement the layout as exactly as it has been provided in the design.

- Pay attention to minor things like spacing, alignment, size, etc.

- Use any font-family which suits better for the assignment.

- Once you are done with the assignment connect with the mentor and get the code reviewed.

<!DOCTYPE html>
<html lang="end">
    <head>
        <meta charset="UTF-8">
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
       <header>
           <nav>
               <a class ="home" href="index.html">home</a>
               <a href="blog.html">blog</a>
           </nav>
       </header>
       <section class="section1">
           <h1>The box-model, box sizing and box shadow</h1>
           <p>Exercise 1</p>
           <div class="radius">
                <div class="box"></div>
                <div class="marker">
                    <span class="circle"></span>
                    <span>#99D8CA</span>
                    <span class="circle outline"></span>
                    <span>#0D1430</span>
                    <span class="circle shadow"></span>
                    <span>#90FFA9</span>
                    <span class="circle border"></span>
                    <span>#5873E2</span>
                </div>
            </div>
       </section>
       <hr>
       <section class="section1">
           <p>Exercise Two</p>
           <div class="container">
               <div class="box1"></div>
               <div class="box1"></div>
               <div class="box1"></div>
           </div>
       </section>
       <hr>
       <section class="section1">
        <div class="container">
            <div class="box2"></div>
            <div class="box2"></div>
            <div class="box2"></div>
        </div>
    </section>
    </body>
</html>

