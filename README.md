<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Wilson's Blog</title>
</head>
<body bgcolor="#eef3f9" text="#222222" link="#1a5fb4">

  <!-- HEADER -->
  <header>
    <h1><font color="#1b2a49">Wilson's Blog</font></h1>
    <p><em>Games, sports, and stories from my life as an IT student.</em></p>
  </header>

  <!-- NAVIGATION MENU -->
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <hr>

  <main>

    <!-- ABOUT ME SECTION -->
    <section id="about">
      <h2><font color="#1b2a49">About Me</font></h2>
      <p>
        Hi! I'm an IT student at FEU (Far Eastern University). I enjoy playing
        games and participating in sports like running and basketball. I used
        to live in the UAE, but now I'm living in the Philippines. Most
        importantly, I love my dog, Potchie, who is my favorite companion.
      </p>
    </section>

    <hr>

    <!-- BLOG POSTS -->
    <section id="home">
      <h2><font color="#1b2a49">Latest Blog Posts</font></h2>

      <!-- Post 1 -->
      <article>
        <h3><font color="#c0392b">Life with Potchie, My Favorite Companion</font></h3>
        <img src="images/post1.jpg" alt="Potchie sleeping in a red basket" width="400">
        <p><small>Posted on: September 16, 2026</small></p>
        <p>
          After a long day of classes, nothing beats coming home to Potchie.
          Here's why my dog is the best study buddy.
        </p>
      </article>

      <br>

      <!-- Post 2 -->
      <article>
        <h3><font color="#c0392b">Running and Basketball: My Way to Recharge</font></h3>
        <img src="images/post2.jpg" alt="Basketball court with painted murals" width="300">
        <p><small>Posted on: October 12, 2026</small></p>
        <p>
          Between coding and deadlines, I make time for sports. Here's how
          running and basketball keep my mind fresh.
        </p>
      </article>

      <br>

      <!-- Post 3 -->
      <article>
        <h3><font color="#c0392b">From the UAE to the Philippines</font></h3>
        <img src="images/post3.jpg" alt="A street in the UAE at night" width="300">
        <p><small>Posted on: December 21, 2024</small></p>
        <p>
          Moving from one country to another changed a lot of things. Here's
          what I learned about adjusting to a new home.
        </p>
      </article>
    </section>

    <hr>

    <!-- CONTACT FORM -->
    <section id="contact">
      <h2><font color="#1b2a49">Contact Me</font></h2>
      <form action="#" method="post">
        <p>
          <label for="name">Name:</label><br>
          <input type="text" id="name" name="name" placeholder="Your name" required>
        </p>
        <p>
          <label for="email">Email:</label><br>
          <input type="email" id="email" name="email" placeholder="Your email" required>
        </p>
        <p>
          <label for="message">Message:</label><br>
          <textarea id="message" name="message" rows="5" cols="40" placeholder="Write your message here" required></textarea>
        </p>
        <p>
          <button type="submit">Send Message</button>
        </p>
      </form>
    </section>

  </main>

  <hr>

  <!-- FOOTER -->
  <footer>
    <p>&copy; 2026 Wilson James Reyes. All rights reserved.</p>
  </footer>

</body>
</html>
