# Pigthing.github.io
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #cecbcb;
}

header {
    background-color: #333;
    color: #fff;
    padding: 2em;
    text-align: center;
    position: relative;
    background-image: url('O_S.JPG'); /* Replace 'your-image-url.jpg' with the path or URL of your image */
    background-size: cover; /* Adjust the background size as needed */
    background-position: center center; /* Center the background image */
}

section {
    padding: 20px;
    max-width: 800px;
    margin: 0 auto;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: .5em;
    position: fixed;
    bottom: 0;
    width: 100%;
}
.flex-container > div {
    background-color: #f1f1f1;
    width: 100px;
    margin: 10px;
    text-align: justify;
    line-height: 75px;
    font-size: 30px;
}
.flex-container {
    display: flex;
}

.flex-container section {
    flex: 1;
    margin-right: 20px;
}

.flex-container img {
    max-width: 100%;
    height: 100%;
    margin-right: 50px;
}

header h1 {
    margin-bottom: 0;
}

nav {
    margin-top: 10px;
}

nav ul {
    list-style-type: none;
    padding: 0;
    display: flex;
}

nav li {
    margin-right: 10px;
}

nav a {
    text-decoration: solid;
    color: #333;
    padding: 5px 10px;
    border: 1px solid #ffffff;
    border-radius: 5px;
    background-color: #ffffff;

}
.dropdown {
    position: relative;
    display: inline-block;
    margin-left: 20px;
}
.rotate_image {
    -webkit-transform: rotate(90deg);
    -moz-transform: rotate(90deg);
    -ms-transform: rotate(90deg);
    -o-transform: rotate(90deg);
    transform: rotate(90deg);
}

.carousel {
    position: relative;
    max-width: 600px;
    margin: 20px auto;
    overflow: hidden;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
}

.slide {
    display: none;
    width: 100%;
    text-align: center;
}

.slide img {
    width: 100%;
}

.carousel-text {
    position: absolute;
    bottom: -20px;
    left: 0;
    width: 100%;
    padding: 10px;
    background-color: #333;
    color: white;
    text-align: center;
}

.carousel-btn {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    font-size: 20px;
    cursor: pointer;
    background-color: #555;
    color: white;
    border: none;
    padding: 10px;
}

.carousel-btn:hover {
    background-color: #333;
}

.carousel-btn.prev {
    left: 10px;
}

.carousel-btn.next {
    right: 10px;
}
@media only screen and (max-width: 767px) {
    header {
        padding: 1em;
    }

    .flex-container {
        flex-direction: column;
    }

    .flex-container section {
        margin-right: 0;
    }

    .flex-container img {
        margin-right: 0;
    }

    .carousel {
        max-width: 100%;
    }
}

/* Add this media query for even smaller screens */
@media only screen and (max-width: 479px) {
    nav ul {
        flex-direction: column;
    }

    nav li {
        margin-right: 0;
        margin-bottom: 5px;
    }

    .dropdown {
        margin-left: 0;
    }
}

/* Add this media query to adjust footer on smaller screens */
@media only screen and (max-width: 479px) {
    footer {
        position: relative;
    }
}
