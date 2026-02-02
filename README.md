# HTML-CSS-CODE-WTL-LAB 
# HTML-CSS-CODE-WTL-LAB

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
<link rel="stylesheet" src="style.css"><link/>
  <title>My GitHub Page</title>

  <style>
    /* Reset & base styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: #f4f6f8;
      color: #333;
      line-height: 1.6;
    }

    /* Layout */
    header {
      background: #24292e;
      color: #fff;
      padding: 1.5rem;
      text-align: center;
    }

    main {
      max-width: 900px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    section {
      background: #fff;
      padding: 1.5rem;
      margin-bottom: 1.5rem;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
    }

    h1, h2 {
      margin-bottom: 0.75rem;
    }

    p {
      margin-bottom: 1rem;
    }

    a {
      color: #0969da;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      padding: 1rem;
      color: #666;
      font-size: 0.9rem;
    }

    /* Responsive tweak */
    @media (max-width: 600px) {
      header {
        padding: 1rem;
      }

      section {
        padding: 1rem;
      }
    }
  </style>
</head>

<body>
  <header>
    <h1>Welcome to My GitHub Page 🚀</h1>
    <p>A simple HTML + CSS site hosted on GitHub Pages</p>
  </header>

  <main>
    <section>
      <h2>About</h2>
      <p>
        This is a basic static website built with HTML and CSS.
        You can customize it however you like and host it for free using GitHub Pages.
      </p>
    </section>

    <section>
      <h2>Projects</h2>
      <p>
        Check out my work on
        <a href="https://github.com/" target="_blank">GitHub</a>.
      </p>
    </section>

    <section>
      <h2>Contact</h2>
      <p>
        You can reach me via email or social media.
      </p>
    </section>
  </main>

  <footer>
    © 2026 MANE ADITYA
  </footer>
</body>
</html>
