# profile<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Portfolio</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: #acb6c4;
            color: linear-gradient(135deg, #cea0e3, #fcb4d5);
        }

        header {
            background:linear-gradient(135deg, #b993d6, #8ca6db); 
            color: white;
            text-align: center;
            padding: 25px 8px;
            animation: fadeIn 2s ease-in-out;
        }

        header img {
            width: 120px;
            border-radius: 50%;
            border: 5px solid white;
            margin-bottom: 20px;
            animation: bounce 2s infinite;
        }

        header h1 {
            font-size: 36px;
            margin: 10px 0;
            animation: slideIn 1.5s ease-out;
        }

        header p {
            font-size: 20px;
            animation: fadeInUp 1s ease-out;
        }

        nav {
            background: linear-gradient(135deg, #a1c4fd, #c2e9fd);
            padding: 15px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        nav a {
            color: white;
            margin: 0 20px;
            text-decoration: none;
            font-weight: bold;
            font-size: 18px;
            text-transform: uppercase;
            transition: transform 0.3s;
        }

        nav a:hover {
            transform: scale(1.1);
        }

        section {
            padding: 60px 20px;
            text-align: center;
            animation: fadeInUp 2s ease-out;
        }

        section img {
            width: 150px;
            border-radius: 50%;
            margin-top: 20px;
            transition: transform 0.3s;
        }

        section img:hover {
            transform: scale(1.1);
        }

        .skills img {
            width: 90px;
            margin: 15px;
            transition: transform 0.3s;
        }

        .skills img:hover {
            transform: scale(1.2);
        }

        .projects img {
            width: 100%;
            max-width: 400px;
            border-radius: 10px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        .projects img:hover {
            transform: scale(1.05);
        }

        footer {
            background:linear-gradient(135deg, #3c67c1, #99c2e2);
            color: white;
            text-align: center;
            padding: 8px;
            position: relative;
        }

        footer p {
            font-size: 14px;
            margin: 0;
        }
        form {
  max-width: 400px;
  margin: 20px auto;
  padding: 20px;
  border: 1px solid #c7c4c4;
  border-radius: 8px;
  background-color: #a2a0a0;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

form input,
form select,
form textarea,
form button {
  width: 100%;
  padding: 10px;
  margin: 10px 0;
  border: 1px solid #b2b0b0;
  border-radius: 4px;
  box-sizing: border-box;
}

form button {
  background-color: #191a1a;
  color: rgb(180, 174, 174);
  border: none;
  cursor: pointer;
}

form button:hover {
  background-color: #e5efe6;
}

        /* Animations */
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        @keyframes slideIn {
            0% { transform: translateY(-50px); opacity: 0; }
            100% { transform: translateY(0); opacity: 1; }
        }

        @keyframes fadeInUp {
            0% { opacity: 0; transform: translateY(20px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }
    </style>
</head>
<body>

<header>
    <img src="https://avatars.githubusercontent.com/u/188641174?s=400&u=48209e4dee914912e443c8bea4dec3bab7f844af&v=4" alt="Your Profile Photo">
    <h1>Rajasekaran V</h1>
    <p>Tech philosopher | MCU follower | Problem Solver</p>
</header>

<nav>
    <a href="#about">About Me</a>
    <a href="#skills">Skills</a>
    <a href="#intenships">intenships</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About Me</h2>
    <p>Hi, I’m Rajasekaran V, B.com(CA) student in Sacred heart college(autonomous)<br>I am an enthusiastic learner passionate about PC hardware, cutting-edge technologies, and the fascinating world of Artificial Intelligence.<br>

        I have always been intrigued by how machines work and how technology shapes our everyday lives. This curiosity has driven me to explore the inner workings of computers, from assembling hardware to understanding the latest advancements in processors and GPUs.<br>
        
        In addition to hardware, I am equally captivated by the potential of AI. I enjoy learning how algorithms, machine learning, and neural networks can solve real-world problems and create innovative solutions.<br>
        
        I am constantly updating my skills and knowledge, eager to contribute to groundbreaking projects. Technology is my passion, and I strive to turn my interests into impactful creations that shape the future.
        
        .</p>
    <img src="https://avatars.githubusercontent.com/u/188641174?s=400&u=48209e4dee914912e443c8bea4dec3bab7f844af&v=4" alt="Your Profile Photo">
</section>
<hr>
<section id="skills" class="skills">
    <h2>Skills</h2>
    <div>
        <img src="https://img.icons8.com/?size=100&id=37619&format=png&color=000000" alt="Microsoft office packages Logo">
        <img src="https://img.icons8.com/?size=100&id=5cVdiiKKi0vX&format=png&color=000000" alt="CSS Logo">
        <img src="https://img.icons8.com/?size=100&id=v8RpPQUwv0N8&format=png&color=000000" alt="html Logo">
        <img src="https://img.icons8.com/?size=100&id=FI3Zar2GXu4w&format=png&color=000000" alt="pc build">
    </div>
</section>
<hr>
<section id="intenships" class="intenshipss">
    <h2>intenships</h2>
    <div>
        <h3>Project 1</h3>
        <img src="https://photos.onedrive.com/photo/E7B879BB58E1D15!s40e67cb47e194e4fb79588b986d01a4e?view=all" alt="Project 1">
        <p>This is to certify that Mr.RAJASEKARAN has Participated in one day International Seminar on Advancing AI-Driven Entrepreneurship:
            A Holistic Exploration of Intellectual Property Rights Organized by
            Department of B.Com (CA), Sacred Heart College (Autonomous), Tirupattur Dist.
            PIN:635 60,Tamil Nadu on 24" September, 2024.</p>
    </div>
</section>
<hr>
<form><section id="contact">
    <img src="https://avatars.githubusercontent.com/u/188641174?s=400&u=48209e4dee914912e443c8bea4dec3bab7f844af&v=4" alt="Your Profile Photo">
    <h2>Contact</h2>
    <p>If you'd like to collaborate or discuss a project, feel free to reach out to me!</p>
     <a href="mailto:youremail@example.com">Email: rajasekaranv514@gmail.com</a>
       <action="your-server-endpoint" method="POST">
         <input type="text" name="name" placeholder="Your Name" required>
          <input type="email" name="email" placeholder="Your Email" required> 
          <textarea name="message" placeholder="Your Message" required>

          </textarea> <button type="submit">Send</button> </form>
   
</section></form>

<footer>
</a>
<p>Follow me:</p><section>
<a href="https://www.instagram.com/kakashi__hatake_006" target="_blank">
    <img src="https://img.icons8.com/?size=100&id=85140&format=png&color=000000" alt="Instagram" class="logo">
</a>
<a href="https://www.linkedin.com/in/rajasekaran-vanangamudi-496971324/?lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3BxZUSDkizRQeByU9p%2FihCTA%3D%3D" target="_blank">
    <img src="https://img.icons8.com/?size=100&id=98960&format=png&color=000000" alt="LinkedIn" class="logo">
</a>
<a href="https://www.facebook.com/share/1AYsz7FEsv/" target="_blank">
    <img src="https://img.icons8.com/?size=100&id=118491&format=png&color=000000" alt="Facebook" class="logo">
</a></section>
    <p>&copy; 2024 Your Rajasekaran V. All rights reserved.</p>
</footer>

</body>
</html>
