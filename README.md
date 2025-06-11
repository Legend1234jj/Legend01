<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>LEGENDEDITORYT64 | Armwrestling</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #0a0a0a;
      color: #ffffff;
    }

    header {
      background: url('https://images.unsplash.com/photo-1605348532760-6753d2c43329') center/cover no-repeat;
      height: 90vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      position: relative;
    }

    header::before {
      content: '';
      position: absolute;
      top: 0; left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.6);
    }

    header h1 {
      font-size: 3rem;
      z-index: 1;
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .about {
      text-align: center;
      font-size: 1.2rem;
      line-height: 1.6;
      color: #ccc;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 40px;
    }

    .gallery img {
      width: 100%;
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(255, 77, 77, 0.3);
      transition: transform 0.3s ease;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }

    footer {
      background: #111;
      text-align: center;
      padding: 30px 0;
      font-size: 0.9rem;
      color: #888;
    }

    .social {
      margin-top: 10px;
    }

    .social a {
      color: #ff4d4d;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>LEGENDEDITORYT64<br><small>ARM-WRESTLING</small></h1>
  </header>

  <section>
    <div class="about">
      <h2>About Me</h2>
      <p>
        Welcome to my official armwrestling edit space! I create powerful, high-impact videos, share strength tips, and showcase the world of armwrestling through cinematic visuals. Let's get stronger together!
      </p>
    </div>

    <div class="gallery">
      <img src="https://images.unsplash.com/photo-1612320562204-cd1df1f225c0" alt="Armwrestling Action">
      <img src="https://images.unsplash.com/photo-1611244419123-6d81d1aa93d8" alt="Training Pose">
      <img src="https://images.unsplash.com/photo-1598970434795-0c54fe7c0642" alt="Strength Focus">
    </div>
  </section>

  <footer>
    &copy; 2025 LEGENDEDITORYT64. All rights reserved.
    <div class="social">
      <a href="#">YouTube</a> | <a href="#">Instagram</a>
    </div>
  </footer>

</body>
</html>
