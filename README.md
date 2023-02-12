
<html>
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meme Hub</title>
  </head>
  <body>
    <header>
      <h1>Meme Hub</h1>
    </header>
    <nav>
      <ul>
        <li><a href="#post-meme">Post Meme</a></li>
        <li><a href="#view-memes">View Memes</a></li>
      </ul>
    </nav>
    <main>
      <section id="post-meme">
        <h2>Post a Meme</h2>
        <form action="submit-meme.php" method="post">
          <label for="meme-image">Image:</label>
          <input type="file" id="meme-image" name="meme-image">
          <br><br>
          <label for="meme-caption">Caption:</label>
          <input type="text" id="meme-caption" name="meme-caption">
          <br><br>
          <input type="submit" value="Submit">
        </form>
      </section>
      <section id="view-memes">
        <h2>View Memes</h2>
        <!-- PHP code to retrieve and display memes from database goes here -->
      </section>
    </main>
    <footer>
      <p>&copy; 2023 Meme Hub</p>
    </footer>
  </body>
</html>
