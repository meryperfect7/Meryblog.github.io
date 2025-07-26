<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mery's Blog</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet" />
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #fff;
      padding: 1rem 2rem;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav a {
      margin-left: 1rem;
      text-decoration: none;
      color: #333;
      font-weight: 600;
    }
    .container {
      max-width: 800px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    h1, h2 {
      color: #222;
    }
    .post {
      background: #fff;
      padding: 1rem 1.5rem;
      margin-bottom: 1.5rem;
      border-radius: 8px;
      box-shadow: 0 1px 4px rgba(0, 0, 0, 0.05);
    }
    footer {
      text-align: center;
      padding: 2rem 1rem;
      color: #888;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Mery's Blog</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#blog">Blog</a>
      <a href="#about">About</a>
    </nav>
  </header>

  <main class="container">
    <section id="home">
      <h2>Welcome to My Blog</h2>
      <p>This is a space where I share my thoughts, stories, and inspirations. Enjoy reading!</p>
    </section>

    <section id="blog">
      <h2>Latest Posts</h2>

      <div class="post">
        <h3>My First Blog Post</h3>
        <p>Hi everyone! This is my first blog post. I'm so excited to start this journey with you!</p>
      </div>

      <div class="post">
        <h3>Another Day, Another Thought</h3>
        <p>Today I’m reflecting on how even the smallest steps matter. Keep going, you’re doing great!</p>
      </div>
    </section>

    <section id="about">
      <h2>About Me</h2>
      <p>Hi! I'm Mery. I love writing and sharing my ideas with the world. This blog is my little corner of the internet. Thanks for stopping by!</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Mery's Blog. All rights reserved.</p>
  </footer>
</body>
</html>
