# Austin-Portfolio-group-12-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Austin Masaba's Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: red;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        header img {
            width: 150px;
            border-radius: 50%;
            margin-top: 10px;
        }
        section {
            padding: 20px;
            max-width: 800px;
            margin: auto;
            background: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }
        h1 {
            margin: 0;
            font-size: 2.5em;
        }
        h2 {
            color: red;
        }
        p {
            line-height: 1.6;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            margin: 10px 0;
            background-color: grey;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .button:hover {
            background-color: darkred;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
        }
        .contact-form input,
        .contact-form textarea {
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background-color: red;
            color: white;
        }
    </style>
</head>
<body>

<header>
    <h1>Austin Masaba</h1>
    <img src="1732421582506.jpg" alt="Austin Masaba">
</header>

<section>
    <h2>About Me</h2>
    <p>I am a passionate software engineer currently studying Computer Security and Forensics at Kabarak University. I love coding, traveling, and reading.</p>
</section>

<section>
    <h2>Educational Background</h2>
    <p>I am pursuing my degree in Computer Security and Forensics at Kabarak University, where I am honing my skills in software development and cybersecurity.</p>
</section>

<section>
    <h2>Interests</h2>
    <p>My interests include traveling to new places, reading books on technology and coding, and continuously improving my programming skills.</p>
</section>

<section>
    <h2>Projects</h2>
    <p>Check out my e- commerce project that allows you to make online transactions and easily manage them on GitHub:</p>
    <a class="button" href="https://github.com/Kipkoech78/Complete-Ecommerce" target="_blank">View Project</a>
</section>

<section>
    <h2>Contact Me</h2>
    <form class="contact-form">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
        <button type="submit" class="button">Send Message</button>
    </form>
</section>

<footer>
    <p>&copy; 2024 Austin Masaba. All rights reserved.</p>
</footer>

</body>
</html>
