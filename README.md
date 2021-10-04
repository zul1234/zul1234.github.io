<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>My Website</title>
        <link rel="stylesheet" href="notion1.css">
        <link rel="stylesheet" href="notion1.responsive.css">
        <link rel="stylesheet" href="https://fontawesome.com/v5.15/icons?d=gallery&p=2">
        <script src="https://kit.fontawesome.com/06c547d90a.js" crossorigin="anonymous"></script>
    </head>
    <body>
        <div class="header">
            <div class="header-logo">My Website</div>
            <div class="header-list">
                <ul>
                    <li>HTML</li>
                    <li>CSS</li>
                    <li>JavaScript</li>
                    <li>Node</li>
                    <li>React</li>
                </ul>
            </div>
        </div>
        <div class="top-wrapper">
            <div class="container">
                <h2>Start your Exciting Proggaming Journey right now!</h2>
                <input class="join-submit" type="submit" value="Join here!">
            </div>
        </div>
        <div class="lessons">Our courses:</div>
        <div class="lesson-wrapper">
            <div class="lesson-a">
                <h3>HTML</h3>
                <p>A markup to build a website</p>
                <p>Difficulty: <i class="far fa-star" aria-hiden="true"></i></p>
                <a href="#">See More <i class="fa fa-long-arrow-alt-right" aria-hiden="true"></i></a>
            </div>
            <div class="lesson-b">
                <h3>CSS</h3>
                <p>Necessary skill to decorate a website</p>
                <p>Difficulty: <i class="far fa-star" aria-hiden="true"></i></p>
                <a href="#">See More <i class="fa fa-long-arrow-alt-right" aria-hiden="true"></i></a>
            </div>
            <div class="lesson-c">
                <h3>JavaScript</h3>
                <p>Versatile and populer language</p>
                <p>Difficulty: <i class="far fa-star" aria-hiden="true"></i></p>
                <a href="#">See More <i class="fa fa-long-arrow-alt-right" aria-hiden="true"></i></a>
            </div>
            <div class="lesson-d">
                <h3>Node</h3>
                <p>Server-side JavaScript</p>
                <p>Difficulty: <i class="far fa-star" aria-hiden="true"></i></p>
                <a href="#">See More <i class="fa fa-long-arrow-alt-right" aria-hiden="true"></i></a>
            </div>
            <div class="lesson-e">
                <h3>React</h3>
                <p>front and framework of JavaScript</p>
                <p>Difficulty: <i class="far fa-star" aria-hiden="true"></i></p>
                <a href="#">See More <i class="fa fa-long-arrow-alt-right" aria-hiden="true"></i></a>
            </div>
        </div>
        <div class="footer">
            <div class="footer one">
                <h1>My Website</h1>
            </div>
            <div class="footer two">
                <ul>
                    <li>
                        <h5>Courses</h5>
                    </li>
                    <li>
                        <a href="#">HTML</a>
                    </li>
                    <li>
                        <a href="#">CSS</a>
                    </li>
                    <li>
                        <a href="#">JavaScript</a>
                    </li>
                    <li>
                        <a href="#">Node</a>
                    </li>
                    <li>
                        <a href="#">React</a>
                    </li>
                </ul>
            </div>
            <div class="footer three">
                <ul>
                    <li>
                        <h5>Social Media</h5>
                    </li>
                    <li>
                        <a href="#">Instagram</a>
                    </li>
                    <li>
                        <a href="#">Facebook</a>
                    </li>
                    <li>
                        <a href="#">Twitter</a>
                    </li>
                </ul>
            </div>
        </div>
    </body>
</html>

.header-logo {
    font-size: 75px;
    text-align: center;
}

.header-list ul {
    list-style: none;
    padding: 15px 0;
    justify-content: space-between;
    display: flex;
    font-weight: bold;
}

.top-wrapper {
    padding: 90px 0 100px 0;
    text-align: center;
    background-color: #e7e7e7;
}

.container input {
    background-color: rgb(64, 105, 240);
    padding: 8px 12px;
    display: inline-block;
    opacity: 0.8;
    border-radius: 4px;
}

.lessons {
    padding: 10px 20px;
    font-weight: bold;
    font-size: 25px;
}

.lesson-wrapper {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 0px 80px 50px 80px;
    line-height: 2;
    border-bottom: 2px solid #e7e7e7;
}

.lesson-a {
    width: 20%;
    padding: 20px;
    margin: 15px;
    color: white;
    background-color: rgb(64, 105, 240);
}

.lesson-b {
    width: 20%;
    padding: 20px;
    margin: 15px;
    color: white;
    background-color: rgb(64, 105, 240);
}

.lesson-c {
    width: 20%;
    padding: 20px;
    margin: 15px;
    color: white;
    background-color: rgb(64, 105, 240);
}

.lesson-d {
    width: 20%;
    padding: 20px;
    margin: 15px;
    color: white;
    background-color: rgb(64, 105, 240);
}

.lesson-e {
    width: 20%;
    padding: 20px;
    margin: 15px;
    color: white;
    background-color: rgb(64, 105, 240);
}

.footer {
    display: flex;
    flex-wrap: wrap;
}

.footer li {
    list-style: none;
}

.footer h5 {
    font-size: 12px;
    border-bottom: 1px solid black;
    margin-bottom: 10px;
    text-align: center;
}

.footer.one {
    flex: 3;
    margin: 15px 50px;
}

.footer.two {
    flex: 0.5;
    justify-content: center;
    font-size: 15px;
    margin: 35px 0px 50px 0px;
    line-height: 1.7;
}

.footer.two a {
    text-decoration: none;
    color: black;
}

.footer.two a:hover {
    color: blue;
}

.footer.three {
    flex: 1;
    justify-content: center;
    font-size: 15px;
    margin: 35px 80px 50px 0px;
    line-height: 1.7;
}

.footer.three a {
    text-decoration: none;
    color: black;
}

.footer.three a:hover {
    color: blue;
}

@media all and (max-width: 1000px){
    .header {
        padding: 20px 20px 10px 20px;
    }
        
    .header ul{
        font-size: 20px;
    }
    .top-wrapper h1{
        font-size: 20px;
    }
    
    .btn-wrapper a {
        font-size: 17px;
    }
    .lesson {
        width: 48%;
        padding: 20px;
        margin: 7px;
        color: white;
    }
    .lesson-wrapper {
        display: flex;
        flex-wrap: wrap;
        padding: 0px 0px 50px 0px;
    }
    .lessons {
        padding: 10px 20px;
        font-weight: bold;
        font-size: 17px;
    }
    .lesson-wrapper h4 {
        font-size: 19px;
    }
    .lesson-wrapper p {
        font-size: 18px;
    }
    .lesson-wrapper a {
        font-size: 17px;
    }
    .footer h5 {
        font-size: 18px;
    }
    .footer.one {
        flex: 3;
        margin: 15px 0px;
    }
    .footer.two {
        justify-content: center;
        font-size: 17px; 
        margin: 35px 0px 10px 0px;
    }
    .footer.three {
        justify-content: center;
        font-size: 17px;
        margin: 35px 0px 10px 20px;
    }
}
@media all and (max-width: 670px){
    .header {
        padding: 20px 0px 10px 0px;
    }
    
    .header ul{
        font-size: 17px;
    }
    .top-wrapper h1{
        font-size: 17px;
        line-height: 1.67;
        padding: 20px 9px;
    }
    
    .btn-wrapper a {
        font-size: 15px;
    }
    
    .lesson-wrapper {
        display: flex;
        flex-direction: column;
        padding: 0px 30px 50px 0px;
        line-height: 1.5;
    }

    .lesson-a, .lesson-b, .lesson-c, .lesson-d, .lesson-e {
        width: 100%;
        padding: auto;
        margin: 15px;
    }
    .lessons {
        padding: 10px 0;
        font-weight: bold;
        font-size: 17px;
    }
    .lesson-wrapper h4 {
        font-size: 18px;
    }
    .lesson-wrapper p {
        font-size: 17px;
    }
    .lesson-wrapper a {
        font-size: 16px;
    }
    
