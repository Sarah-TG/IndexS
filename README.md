<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Profile Page</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.google.com/specimen/Montserrat"
    rel="stylesheet">
    <style>
        /*Making the body look nice*/
        body {
            font-family: Arial, sans-serif;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f0f0f0;
        }
        /*Styling the headings*/
        h1 {
            Font size: 2.5rem;
            color: #e6e6e6;
            text-align: center;
        }
        h2 {
            Font size: 1.4rem;
            color: #e6e6e6;
            margin-top: 30px;
        }
        body {
            background-color: #32323c;
            font-family: "Montserrat", sans-serif;
            
            color: #333;
            margin: 0;
            padding: 20px;
        }
        /*Making the image responsive*/
        img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 20px auto;
            border-radius: 8px;
        }
        /*Styling the links*/
        a {
            color: #3498db;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        /*Styling the paragraph*/
        p {
            line-height: 1.6;
            color: #e7e1e1;
        }
        /*Navigation syling*/

        nav { position: fixed;
            top: 0;
            left:0;
            width: 100%;
            padding: 10px 0px;
            z-index: 1000;
            background-color: rgba(50, 50, 60, 0.95);
            box-shadow: 0 2px 10px rgba(0,0,0,0.52);
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            
        }
        nav li {
            margin: 0;
        }
        nav a {
            font-family: "Montserrat", sans-serif;
            color: #e6e6e6;
            font-size: 16px;
            text-decoration: none;
            transition: color 0.3s, boarder-bottom 0.3s;
            padding-bottom: 5px;
            position: relative;
           
        }
        nav a:hover {
            color: #1b1b20;
            border-bottom: 2px solid #e6e6e6;
        }
        .chapter-section
        {
         background-color: rgb(255, 255, 255,0.2);
         border-radius: 50px;
         padding: 20px;
         margin-top: 80px auto;
         max-width: 800px;
         box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        } 
        .chapter-section h2 {
            font-family:"Montserrat", sans-serif;
            font size: 24px;
            color: #e6e6e6;
            margin-bottom: 5px;
            border-bottom: 2px solid #e6e6e6;
            display: inline-block;
            padding-bottom: 5px;
        }
    </style>
    <link rel="stylesheet" href="styles.css">
    </head>
<body>
    
    <nav>
     <ul>
        <li><a href="#Home">About Me</a></li>
        <li><a href="#about-me">About Me</a></li>
        <li><a href="#favorite-websites">My Favorite Websites</a></li>
        <li><a href="#contact-me">Contact Me</a></li>   


    </nav>
        <!-- This is the main section-->
         
    <h1>Welcome to My Profile Page</h1>
        <!-- Adding an image-->
         <img src="Sara profile pic.png" alt="Profile picture">
         <!--This is the main section-->
         <section class="chapter-section">
         <h2>About Me</h2>

         <p>Hello! I am currently learning web development, and this webpage is one of 
            my very first projects. I created it as a way to practice working with HTML 
            and CSS and to better understand how websites are structured and styled. 
            Through this project, I’m experimenting with basic elements, layouts, and 
            design choices to see how small changes affect the overall appearance of a page. 
            Although it’s just a practice exercise, it’s helping me build confidence and 
            improve my skills as I continue learning more about web development.</p>

           </section> 
    
    <h2> My Favorite Websites</h2>
    <ul>
        <li><a href="https://github.com/Sarah-TG" target="_blank">GitHub</a></li>
        <li><a href="https://en.wikipedia.org/wiki/Coding" target="_blank">Wikipedia</a></li>
        
    </body>
    </html>
