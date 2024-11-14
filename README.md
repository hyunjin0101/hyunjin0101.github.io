<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Template with Centered Image and Image Grid</title>
  <style>
    /* Reset styles */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    /* Body with full-screen layout */
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background-color: #f4f4f4;
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      margin: 0;
    }

    /* Main container */
    .container {
      width: 100%;
      max-width: 800px;
      background-color: #fff;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      text-align: center;
      padding: 20px;
    }

    /* Image Section - Centered Image */
    .image-section img {
      max-width: 100%;
      height: auto;
      display: block;
      margin: 0 auto;
    }

    /* Introduction Section */
    .intro-section {
      padding: 20px;
    }

    .intro-section h2 {
      margin-bottom: 10px;
      font-size: 1.5em;
    }

    .intro-section p {
      font-size: 1em;
      color: #333;
    }

    /* Divider line */
    .divider {
      width: 100%;
      height: 1px;
      background-color: #ddd;
      margin: 20px 0;
    }

    /* Additional Content Section */
    .content-section {
      padding: 20px;
    }

    /* Image Grid Section */
    .image-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 10px;
      padding: 20px;
    }

    .image-grid img {
      width: 100%;
      height: auto;
      border-radius: 8px;
      cursor: pointer;
      transition: transform 0.3s ease;
    }

    .image-grid img:hover {
      transform: scale(1.05);
    }
  </style>
</head>
<body>

<div class="container">
  <!-- Image Section -->
  <div class="image-section">
    <img src="6.jpg" alt="Image Description">
  </div>

  <!-- Introduction Section -->
  <div class="intro-section">
    <h2>Introduction</h2>
    <p>
      This is the introductory section where you can add a brief description or welcome text. Here you can explain the purpose of the page, provide context, or introduce the main content.
    </p>
  </div>

  <!-- Divider Line -->
  <div class="divider"></div>

  <!-- Additional Content (optional) -->
  <div class="content-section">
    <h2>Additional Content Section</h2>
    <p>
      Here is where you can add more details, articles, or other relevant information. You can repeat the divider as needed to further separate content sections.
    </p>
  </div>

  <!-- Divider Line -->
  <div class="divider"></div>

  <!-- Image Grid Section (2x2 layout) -->
  <div class="image-grid">
    <img src="1.jpg" alt="Image 1">
    <img src="2.jpg" alt="Image 2">
    <img src="3.jpg" alt="Image 3">
    <img src="5.jpg" alt="Image 4">
  </div>
</div>
<script src="a.js"></script>
</body>
</html>
