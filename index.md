<!DOCTYPE HTML>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="description" content="My first HTML">
    <meta name="keywords" content="HTML">
    <meta name="author" content="Derric Lee">
    <title>Hysticali</title>
    <style>
      /* Global Styles */
      body {
        margin: 0;
        padding: 0;
        font-family: 'Arial', sans-serif;
        background: linear-gradient(135deg, #667eea, #764ba2);
        color: #fff;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        text-align: center;
      }

      /* Container for content */
      .container {
        background: rgba(255, 255, 255, 0.1);
        padding: 2rem;
        border-radius: 15px;
        backdrop-filter: blur(10px);
        box-shadow: 0 8px 32px rgba(0, 0, 0, 0.1);
        max-width: 400px;
        width: 100%;
      }

      /* Heading */
      h1 {
        font-size: 2.5rem;
        margin-bottom: 1rem;
        font-weight: bold;
        text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
      }

      /* Paragraph */
      p {
        font-size: 1.1rem;
        margin-bottom: 1.5rem;
        opacity: 0.9;
      }

      /* Button */
      button {
        background: #fff;
        color: #667eea;
        border: none;
        padding: 0.75rem 2rem;
        font-size: 1rem;
        border-radius: 25px;
        cursor: pointer;
        transition: all 0.3s ease;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      }

      button:hover {
        background: #667eea;
        color: #fff;
        transform: translateY(-2px);
        box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
      }

      button:active {
        transform: translateY(0);
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      }

      /* Footer */
      footer {
        margin-top: 2rem;
        font-size: 0.9rem;
        opacity: 0.8;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <h1>Hysticali</h1>
      <p>Welcome to my sleek and modern web page.</p>
      <button type="button" onclick="alert('Hello World!')">Click Me!</button>
      <footer>
        <p>&copy; 2023 Derric Lee. All rights reserved.</p>
      </footer>
    </div>
  </body>
</html>
