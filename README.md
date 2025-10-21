<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>About Me</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background-color: #f9f9f9;
      color: #333;
    }

    h1, h2 {
      text-align: left;
      color: #2c3e50;
    }

    p {
      max-width: 600px;
      line-height: 1.6;
      text-align: left;
    }

    .tech-icons {
      display: flex;
      gap: 20px;
      align-items: center;
      margin-top: 10px;
    }

    .tech-icons img {
      height: 50px;
      transition: transform 0.3s ease-in-out;
      animation: float 3s ease-in-out infinite;
    }

    .tech-icons img:hover {
      transform: scale(1.2) rotate(5deg);
    }

    /* Animation: smooth floating effect */
    @keyframes float {
      0%   { transform: translateY(0px); }
      50%  { transform: translateY(-8px); }
      100% { transform: translateY(0px); }
    }
  </style>
</head>
<body>

  <!-- About Me Section -->
  <h1>About Me</h1>

  <p>Thank you for visiting my account.</p>

  <p>
    I enjoy building diverse projects using Python. I actively volunteer and engage in learning opportunities to deepen my expertise and become a professional in the field.
  </p>

  <!-- Tech Stack Section -->
  <h2>I Code With</h2>

  <div class="tech-icons">
    <!-- JavaScript Logo -->
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" 
         alt="JavaScript logo" />

    <!-- Python Logo -->
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" 
         alt="Python logo" />
  </div>

</body>
</html>
