<!DOCTYPE html>
<html>
<head>
  <style>
    body {
      font-family: 'Helvetica', Verdana, sans-serif;
      background-color: #f9f9f9;
      padding: 20px;
    }

    .highlight {
      color: #0d6efd;
      font-weight: bold;
    }

    {
      text-align: center;
      color: green;
      margin-bottom: 30px;
    }

    h2, h3 {
      color: #333;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-bottom: 40px;
    }

    th, td {
      border: 1px solid #ccc;
      padding: 15px;
      text-align: center;
    }

    th {
      background-color: #4CAF50;
      color: white;
    }

    tbody tr:nth-child(odd) {
      background-color: #f2f2f2;
    }

    tbody tr:hover {
      background-color: #d1e7dd;
      transition: 0.3s ease;
    }

    form {
      background: #fff;
      padding: 20px;
      border: 1px solid #ccc;
      max-width: 400px;
    }

    form label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
    }

    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #bbb;
      border-radius: 4px;
    }

    form input[type="submit"] {
      background-color: #28a745;
      color: white;
      border: none;
      cursor: pointer;
    }
    form input[type="submit"]:hover {
      background-color: #218838;
    }
  </style>
</head>
<body>
  <h1 id="main-heading">Pricing Table & Contact Form</h1>

  <h2 class="highlight">Website Price Table</h2>

  <table>
    <thead>
      <tr>
        <th>Plans</th>
        <th>Price (INR)</th>
        <th>Features</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Basic</td>
        <td>₹899/month</td>
        <td>1 Website, 15GB Storage</td>
      </tr>
      <tr>
        <td>Pro</td>
        <td>₹1799/month</td>
        <td>5 Websites, 45GB Storage</td>
      </tr>
      <tr>
        <td>Premium</td>
        <td>₹2999/month</td>
        <td>Unlimited Sites, 250GB Storage</td>
      </tr>
    </tbody>
  </table>

  <h2 class="highlight">Media Section</h2>

  <h3class="highlight">YouTube Video</h3>
  <iframe width="400" height="274" src="https://www.youtube.com/embed/tgbNymZ7vqY"
    frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

  <h3>Audio File</h3>
  <audio controls>
    <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-2.mp3" type="audio/mpeg">
  </audio>
</body>
</html>
