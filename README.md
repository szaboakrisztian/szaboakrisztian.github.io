<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Minimal Blog</title>
  <style>
    :root {
      --bg: #ffffff;
      --text: #111111;
      --muted: #666666;
      --border: #e0e0e0;
      --accent: #0055ff;
    }
    @media (prefers-color-scheme: dark) {
      :root {
        --bg: #121212;
        --text: #e0e0e0;
        --muted: #999999;
        --border: #2a2a2a;
        --accent: #4d88ff;
      }
    }
    body {
      max-width: 650px;
      margin: 4rem auto;
      padding: 0 1rem;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
      line-height: 1.6;
      background: var(--bg);
      color: var(--text);
    }
    header {
      margin-bottom: 3rem;
      border-bottom: 1px solid var(--border);
      padding-bottom: 1.5rem;
    }
    h1, h2, h3 { line-height: 1.2; margin-top: 2rem; }
    h1 { margin-top: 0; }
    a { color: var(--accent); text-decoration: none; }
    a:hover { text-decoration: underline; }
    time { font-size: 0.85rem; color: var(--muted); }
    article { margin-bottom: 3rem; }
    footer {
      margin-top: 4rem;
      padding-top: 1.5rem;
      border-top: 1px solid var(--border);
      font-size: 0.85rem;
      color: var(--muted);
    }
  </style>
</head>
<body>

  <header>
    <h1>My Personal Site</h1>
    <p>Notes, articles, and raw HTML experiments.</p>
  </header>

  <main>
    <article>
      <h2><a href="#">Building Without Frameworks</a></h2>
      <time datetime="2026-09-17">September 17, 2026</time>
      <p>
        Writing plain HTML and CSS keeps load times instant, eliminates build step 
        failures, and guarantees backward compatibility for decades.
      </p>
    </article>

    <article>
      <h2><a href="#">Minimalism in Systems</a></h2>
      <time datetime="2026-09-10">September 10, 2026</time>
      <p>
        Complexity must be justified by equivalent value. When static text serves 
        the purpose, dynamic runtime abstractions introduce unnecessary overhead.
      </p>
    </article>
  </main>

  <footer>
    <p>&copy; 2026. Handcrafted with semantic HTML &amp; CSS.</p>
  </footer>

</body>
</html>
