# Flexbox-CSS-Grid-Puzzle.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Puzzle Assignment</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      margin: 0;
      padding: 0;
    }

    .grid-container {
      display: grid;
      grid-template-areas:
        "header"
        "puzzle"
        "explanation"
        "footer";
      gap: 20px;
      padding: 20px;
    }

    .section {
      background-color: #ffffff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .header {
      grid-area: header;
      background-color: #e0f7fa;
    }

    .puzzle {
      grid-area: puzzle;
    }

    .explanation {
      grid-area: explanation;
      background-color: #fce4ec;
    }

    .footer {
      grid-area: footer;
      text-align: center;
      background-color: #e8f5e9;
    }

    .flex-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
      margin-top: 10px;
    }

    .flex-container img {
      width: 100px;
      height: 100px;
      object-fit: cover;
      border: 2px solid #555;
      border-radius: 4px;
    }

    .hidden {
      display: none;
    }
  </style>
</head>
<body>
  <div class="grid-container">

    <!-- Section 1: Name and puzzle title -->
    <header class="section header">
      <h1>Your Name: Jane Doe</h1>
      <p>Chosen Puzzle: Puzzle 1 (Butterflies)</p>
    </header>

    <!-- Section 2: Flexbox puzzle -->
    <section class="section puzzle">
      <h2>Flex Puzzle Pieced Together</h2>
      <div class="flex-container">
        <img src="images/puzzle1_A.jpg" alt="Piece A">
        <img src="images/puzzle1_B.jpg" alt="Piece B">
        <img src="images/puzzle1_C.jpg" alt="Piece C">
        <img src="images/puzzle1_D.jpg" alt="Piece D">
        <img src="images/puzzle1_E.jpg" alt="Piece E">
        <img src="images/puzzle1_F.jpg" alt="Piece F">
        <img src="images/puzzle1_G.jpg" alt="Piece G">
        <img src="images/puzzle1_H.jpg" alt="Piece H">
        <img src="images/puzzle1_I.jpg" alt="Piece I">
        <img src="images/puzzle1_J.jpg" alt="Piece J">
        <img src="images/puzzle1_K.jpg" alt="Piece K">
        <img src="images/puzzle1_L.jpg" alt="Piece L">
        <img src="images/puzzle1_M.jpg" alt="Piece M">
        <img src="images/puzzle1_N.jpg" alt="Piece N">
        <img src="images/puzzle1_O.jpg" alt="Piece O">
        <img src="images/puzzle1_P.jpg" alt="Piece P">
        <img src="images/puzzle1_Q.jpg" alt="Faulty Piece" class="hidden">
      </div>
    </section>

    <!-- Section 3: Explanation -->
    <section class="section explanation">
      <h2>How the Puzzle Was Solved</h2>
      <ul>
        <li>Used <strong>Flexbox</strong> to arrange puzzle pieces in rows with wrapping.</li>
        <li>Used the <code>display: none;</code> property to hide the faulty puzzle piece.</li>
        <li>The puzzle is solved correctly by placing the right pieces in order.</li>
        <li>All puzzle pieces are stored inside the <code>images/</code> folder.</li>
      </ul>
    </section>

    <!-- Section 4: Date -->
    <footer class="section footer">
      <p>Assignment completed on: May 21, 2025</p>
    </footer>

  </div>
</body>
</html>
