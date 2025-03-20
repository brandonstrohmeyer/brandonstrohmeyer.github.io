<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Narrow Column Example</title>
    <style>
        .narrow-column {
            height: 600px; /* Set fixed height */
            max-width: 600px; /* Set the maximum width of the column */
            margin: 0 auto; /* Center the column horizontally */
            padding: 0px;
            margin-bottom: 400px;
            background-color: transparent; /* Set the background to transparent */
            border: 1px solid transparent; /* Keep the border transparent */
            line-height: 1.8;
        }
        .center p {
            margin       : 0;
            position     : absolute;
            text-align   : center;
            top          : 35%;
            left         : 50%;
            -ms-transform: translate(-35%, -50%);
            transform    : translate(-35%, -50%);
        }
        #img-link, #img-link img{
            text-decoration: none !important;
            border         : 0px !important;
            outline        : none;
            border-width   : 10px;
            outline-width  : 0px;
            border-bottom  : none;
            padding-left   : 2px;
            padding-right  : 2px;
        }
    </style>
</head>
<body>
    <div class="narrow-column">
        <h1>About</h1>
        <img src="/img/garage_self.jpg#left" width="350" />
        <p>
        My name is Brandon Strohmeyer. 
        </p>
        <p>
            I'm a Software Engineer specializing in infrastructure automation and use motorsports as an outlet to satisfy my taste for over-engineering. 
        </p>
        <p>
            I build cars, I race cars, and I teach others how to drive slow cars fast as an HPDE Instructor with <a href="https://drivenasa.com/">NASA</a> in the Southeast region.
        </p>
        <p>
            I have a dog, cat, and to-be wife all based out of North Carolina.
        </p>
        <p>
            <a id="img-link" href="https://www.instagram.com/stro38x">
                <strong><img src="icons/iconmonstr-instagram-13.svg"></strong>
            </a>
            <a id="img-link" href="https://www.linkedin.com/in/bstrohmeyer/">
                <strong><img src="icons/iconmonstr-linkedin-3.svg"></strong>
            </a>
            <a id="img-link" href="https://github.com/brandonstrohmeyer">
                <strong><img src="icons/iconmonstr-github-3.svg"></strong>
            </a>            
            <a id="img-link" href="https://medium.com/@brandonstrohmeyer">
                <strong><img src="icons/iconmonstr-medium-3.svg"></strong>
            </a>            
            <a id="img-link" href="mailto:hello@stro.io">
                <strong><img src="icons/iconmonstr-gmail-3.svg"></strong>
            </a>
        </p>
    </div>

</body>
</html>