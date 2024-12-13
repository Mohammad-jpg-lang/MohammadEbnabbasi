<!DOCTYPE html>
<html lang="en">
<head>
    <title>Mohammad Ebnabbasi</title>
    <meta charset="UTF-8">
    <meta name="description" content="My favourite game">
    <meta name="keywords" content="HTML, CSS, JavaScript">
    <meta name="author" content="Danny Bahrami">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
</head>

<bodY>
    <header>
        <h1 id="mainh">Mohammad Ebnabbasi</h1>
    </header>
    
    <nav class="navbar">
        <ul>
            <li><a href="index.html">Computer Science</a></li>
            <Li><a href="student.html">Student</a></Li>
            <li><a href="charlist.html">Gamer</a></li>
            <li><a href="musiclist.html">Programmer</a></li>
            <li><a href="aboutme.html">Batman Enthusiast</a></li>
        </ul>


    </nav>

    <main>
        <section>
            <h2>About Me</h2>
            <p>I am a passionate computer science enthusiast with a strong interest in
			technology, problem-solving, and innovation. I enjoy exploring new areas 
			like artificial intelligence, machine learning, and software development. 
			My goal is to create meaningful and impactful solutions that improve everyday life.
			Outside of programming, I love gaming, reading about emerging tech trends, 
			and staying active through outdoor activities</p>
        </section>

        <aside>
            <h2>Skills</h2>
            <p>I am skilled in HTML, CSS and Node.js. I am currently learning C++.
            </p>
        </aside>

        <article>
            <h2>Hobbies</h2>
            <p>Video Games, powerlifting and I like to critically review movies</p>
        </article>
    </main>
*{
    box-sizing: border-box;
}
body{
    margin: 0;
    background-image: url(images/Valerie&Vincent.jpg);
    background-repeat: no-repeat;
    background-position: center;
    background-attachment: fixed;
    background-size: auto;
}
@font-face{
    font-family: myFont;
    src:url(fonts/futuristic.ttf);
}
#mainh{
    background-color: hsl(60, 100%, 50%);
    font-family: myFont, 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: 5em;
    padding: 25px; 
    text-align: center;
}
main{
    margin: 20px;
}
h2{
    font-family: myFont, 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
aside{
    width:20%;
    float: left;
    padding: 10px;
}
Section{
    width:40%;
    float: left;
    padding: 10px;
}
Article{
    width: 40%;
    float: right;
    padding: 10px;
}
footer{
    background-color: hsl(60, 100%, 50%);
    font-family: myFont, 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    display: block;
    clear: both;
    padding: 25px; 
    text-align: center;
}
.navbar ul{
    list-style-type: none;
    background-color: hsl(0, 0%, 16%);
    font-family: myFont, 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    padding: 0px;
    margin: 0px;
    overflow: hidden;
}
.navbar a{
    color: rgb(229, 255, 0);
    text-decoration: none;
    padding: 15px;
    display: block;
    text-align: center;
}
.navbar a:hover{
    background-color: hwb(0 7% 93%);
}
.navbar li{
    float: left;
}
@media screen and (max-width:600px){
    aside, section, article{
        width: 100%;
    }
}


