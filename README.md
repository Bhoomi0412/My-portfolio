# My-portfolio
This is my portfolio
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header class="hero">
        <div class="hero">
            <h1 class="head"> Hello, I am Bhoomi</h1>
            <p class="tagline">Aspiring Developer | Creative problem solver | Tech Enthusiast</p>
            <p class="intro">A driven tech enthusiast with a passion for coding,problem-solving and innovation.I'm
                constantly learning and building projects that make a impact.i am also a UI/UX designer. Excited about
                web
                development, AI and everthing in between! </p>
    </header>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top ">
        <div class="container">
            <a class="navbar-brand" href="#">Portfolio</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
                <button>Dark mode</button>

            </div>
        </div>
    </nav>

    <br>
    <section class="about">
        <div class="about">
            <h2 class="me">About me</h2>
            <br>
            <p class="p">Hi, I am Bhoomi-a passionte UI/UX designer, an enthusiastic code learner and a confident public
                speaker.I
                thrive at the intersection of design,technology and communication. Whether it's delivering a
                presentation or pitching an idea or leading a discussion,I enjoy the challenge of connecting with people
                and making complex concepts accessible.With a mindset of continous
                learning,I'm always learning new.
            </p>
        </div>
    </section>
    <br>
    <section class="skills">
        <div class="skills">
            <h2 class="me">My Skills</h2>
            <br>
            <table class="table">
                <tr>
                    <th>Category</th>
                    <th>Skills</th>
                </tr>
                <tr>
                    <td>UI/UX design</td>
                    <td>figma, wireframing, prototyping</td>
                </tr>
                <tr>
                    <td>Graphic design</td>
                    <td>Canva</td>
                </tr>
                <tr>
                    <td>Programming</td>
                    <td>HTML, CSS, Bootstrap</td>
                </tr>
                <tr>
                    <td>Pubic speaking</td>
                    <td>Presentation, Speech delivering, storytelling</td>
                </tr>
                <tr>
                    <td>Soft skills</td>
                    <td>leadership, Teamwork, Communication</td>
                </tr>
            </table>
        </div>
    </section>
    <br>
    <div class="container mt-5">
        <h2 class="me">My Projects</h2>
        <br>
        <div class="row">
            <div class="col-md-4">
                <div class="card">
                    <img src="https://is3-ssl.mzstatic.com/image/thumb/Purple116/v4/41/c7/40/41c740f7-ad8c-abc8-f273-50e1c63c2021/icon.png/1200x630wa.png"
                        class="card-img-top" alt="Image 1">
                    <div class="card-body">
                        <h5 class="card-title">Canva</h5>
                        <p class="card-text">Here is one of my Canva Project.</p>
                        <a href="https://www.canva.com/design/DAGeC-CMgPY/8N2b-TGkO1qEcQy6tvoInQ/edit"
                            class="btn btn-primary">see</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="https://cdn2.downdetector.com/static/uploads/logo/figma2.png" class="card-img-top"
                        alt="Image 2">
                    <div class="card-body">
                        <h5 class="card-title">Figma</h5>
                        <p class="card-text">Here is one of my Figma Project.</p>
                        <a href="https://www.figma.com/proto/ieD24nIoGvBig4eEBti90N/Untitled?node-id=3-36&starting-point-node-id=1%3A2&t=9SQ2xCo9DAAevLGK-1"
                            class="btn btn-primary">See</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="https://logosmarcas.net/wp-content/uploads/2020/11/Wix-Emblema.png" class="card-img-top"
                        alt="Image 3">
                    <div class="card-body">
                        <h5 class="card-title">Wix</h5>
                        <p class="card-text">Here is one of my wix project.</p>
                        <a href="https://bhoomiarora0412.wixstudio.com/my-project-1" class="btn btn-primary">See</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>



    <section class="contact">
        <div class="con">
            <h2 class="me">Contact me</h2>
            <br>
            <p class="q">Have any question or want to work together? Feel free to reach out!</p>
            <form class="form">
                <label for="name" class="n">Name</label>
                <input type="text" id="name">
                <br>
                <label for="email" class="n">E-mail</label>
                <input type="email" id="email">
                <br>
                <label for="message" class="n">Message here</label>
                <input type="textarea" id="message">
                <br>
                <span><button type="submit" class="button">Submit</button></span>
            </form>
        </div>
    </section>
    <footer>
        <div class="footer">
            <H5 class="headline">For more information contact </H5>
            <p class="b">Contact number: 9417981786</p>
            <p class="b">E-mail: bhoomiarora@gmail.com</p>
        </div>
    </footer>
</body>

</html>
* {
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;

    /* Small devices (phones, less than 576px) */
    @media (max-width: 575.98px) {}

    /* Medium devices (tablets, 576px to 767px) */
    @media (min-width: 576px) and (max-width: 767.98px) {}

    /* Large devices (desktops, 768px to 991px) */
    @media (min-width: 768px) and (max-width: 991.98px) {}

    /* Extra large devices (large desktops, 992px and up) */
    @media (min-width: 992px) {}

}

/* Default Light Mode */
:root {
    --bg-color: #ffffff;
    --text-color: #222;
    --primary-color: #007bff;
}

/* Dark Mode */
@media (prefers-color-scheme: dark) {
    :root {
        --bg-color: #121212;
        --text-color: #f5f5f5;
        --primary-color: #bb86fc;
    }
}

/* Apply styles */
body {
   
    font-family: Arial, sans-serif;
    text-align: center;
    padding: 50px;
}

button {
    background-color: var(--primary-color);
    color: white;
    border: none;
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
    border-radius: 5px;
}

button:hover {
    opacity: 0.8;
}


.hero {
    background-color: #1c2e4a;
    padding-top: 20px;
    color: white;
    font-size: larger;
}



.head {
    padding: 100px;
    margin: 0 auto;
    text-align: center;
}

.tagline {
    background-color: #52677d;
    padding: 5px;
    font-size: medium;
    text-align: center;

}

.intro {
    background-color: #bdc4d4;
    font-size: medium;
    color: black;
    padding: 10px;
    text-align: center;
}


.me {
    background-color: #52677d;
    padding: 20px;
    text-align: center;
    color: aliceblue;
    font-size: large;
    font-weight: 600;
    font-style: oblique;
}

.p {
    padding: 1px;
    padding: 30px;
    text-align: justify;
    background-color: #bdc4d4;
}

.skills {
    border: 1px;
}

.table {
    background-color: #bdc4d4;
    padding: 10px;
    text-align: center;
    margin: 0 auto;
}

.card-img-top {
    height: 250px;

}

.contact {
    padding: 20px;
}

.con {
    background-color: #bdc4d4;
    padding-bottom: 15px;
}

.q {
    padding-bottom: 20px;
    text-align: center;
}

.form {
    display: flex;
    flex-direction: column;
    width: 300px;
    margin: 0 auto;
    border: 1px solid white;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    padding: 20px;
}



.button {
    background-color: #1c2e4a;
    color: white;
    padding: 15px;
    align-items: center;
    border-radius: 10px;
    transition: background-color 0.1s;
}

.button:hover {
    background-color: #093666;
}

.footer {
    background-color: #1c2e4a;
    padding: 50px;
    color: white;

}

.headline {
    font-style: normal;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    padding-bottom: 10px;
}

.b {
    padding-top: 10px;
}
