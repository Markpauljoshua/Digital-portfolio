<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Web Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div>
        <div id="header">
            <nav>
                <ul>
                    <li style="font-size: x-large;">joshua</li>
                    <li style="padding-right: 3%; padding-top: 1px; padding-left: 50%;">HOME</li>
                    <li style="padding-right: 3%;">ABOUT</li>
                    <li style="padding-right: 3%;">QUALIFICATION</li>
                    <li style="padding-right: 3%;">PROJECTS</li>
                </ul>
            </nav>
        </div>
    </div>
    <div>
        <section class="home">
            <h1 class="hero1">A WEB DEVELOPER</h1>
            <img id="photo" src="https://images.unsplash.com/photo-1587620962725-abab7fe55159?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1031&q=80" alt="Web Developer Photo">
            <br>
            <h2 class="hero2">I am a web developer, and I love to create websites.</h2>
            <button class="intro">Learn More</button>
        </section>
    </div>
</body>
</html>
.home {
    background: rgba(0, 0, 0, 0.5) url("https://images.unsplash.com/photo-1587620962725-abab7fe55159?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1031&q=80");
    text-align: center;
    background-size: cover;
    height: 800px;
    background-blend-mode: overlay;
}

.intro {
    background-color: aqua;
    border: 3px solid;
    color: black;
    padding: 0.5%;
    font-size: large;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    cursor: pointer;
}

.hero1 {
    color: antiquewhite;
    margin: 0;
    padding-top: 15%;
    font-size: 50px;
}

.hero2 {
    color: #ddd;
    margin: 20px 0;
    text-align: center;
    font-size: 20px;
}

ul {
    display: inline;
}

li {
    display: inline;
    cursor: pointer;
}

nav {
    background-color: blanchedalmond;
    color: black;
    padding: 1cm;
}

#photo {
    display: block;
    margin: 0 auto;
    border: 3px solid rgb(255, 132, 0);
    border-radius: 50%;
}
