<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1, maximum-scale=1, minimum-scale=1, user-scalable=no"
    />

    <link rel="dns-prefetch" href="https://icp.ninja" />
    <link rel="dns-prefetch" href="https://fonts.googleapis.com" />
    <link rel="dns-prefetch" href="https://fonts.gstatic.com" crossorigin />

    <link
      rel="preload"
      href="https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:ital,wght@0,400;0,500;0,700;1,400;1,500;1,700&display=swap"
      as="style"
    />
    <link rel="preload" href="/assets/fonts/CircularXXWeb-Medium.woff" as="font" type="font/woff" crossorigin />
    <link rel="preload" href="/assets/fonts/CircularXXWeb-Bold.woff" as="font" type="font/woff" crossorigin />
    <link rel="preload" href="/assets/fonts/CircularXXWeb-Book.woff" as="font" type="font/woff" crossorigin />

    <link rel="canonical" href="https://icp.ninja" />

    <title>ICP Ninja</title>
    <link rel="icon" href="/favicon.ico" />
    <meta
      name="description"
      content="ICP Ninja is a browser IDE for creating Internet Computer (ICP) smart contracts. Write and deploy entire applications directly onchain from the browser. Choose from a gallery of example projects to get started."
    />

    <meta name="version" content="337e0fc8772fbb818a6a5dba5b3783bb777db0b2" />

    <meta property="og:url" content="https://icp.ninja" />
    <meta property="og:type" content="website" />
    <meta property="og:title" content="ICP Ninja" />
    <meta
      property="og:description"
      content="ICP Ninja is a browser IDE for creating Internet Computer (ICP) smart contracts. Write and deploy entire applications directly onchain from the browser. Choose from a gallery of example projects to get started."
    />
    <meta property="og:image" content="https://icp.ninja/open-graph.png" />
    <meta property="og:image:width" content="1920" />
    <meta property="og:image:height" content="960" />
    <meta property="og:type" content="website" />
    <meta property="og:locale" content="en_GB" />

    <meta name="twitter:card" content="summary" />
    <meta property="twitter:url" content="https://icp.ninja" />
    <meta property="twitter:domain" content="https://icp.ninja" />
    <meta name="twitter:title" content="ICP Ninja" />
    <meta
      name="twitter:description"
      content="ICP Ninja is a browser IDE for creating Internet Computer (ICP) smart contracts. Write and deploy entire applications directly onchain from the browser. Choose from a gallery of example projects to get started."
    />
    <meta name="twitter:image" content="https://icp.ninja/open-graph-square.png" />
    <meta name="twitter:image:width" content="672" />
    <meta name="twitter:image:height" content="672" />

    <script>
      // Initialize theme before any content renders to prevent flash
      (function () {
        try {
          // Get stored theme from localStorage
          const stored = localStorage.getItem('icp-ninja-theme');
          let themeMode = 'sync'; // default fallback

          if (stored) {
            const parsed = JSON.parse(stored);
            themeMode = parsed.state?.themeMode || 'sync';
          }

          // Calculate isDark based on theme mode
          let isDark = false;

          switch (themeMode) {
            case 'dark':
              isDark = true;
              break;
            case 'light':
              isDark = false;
              break;
            case 'sync':
            default:
              // Check system preference, fallback to light
              if (window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches) {
                isDark = true;
              }
              break;
          }

          // Apply theme class to html element (works even before body exists)
          document.documentElement.classList.add(isDark ? 'dark' : 'light');
        } catch (error) {
          // Fallback to light theme if anything goes wrong
          document.documentElement.classList.add('light');
        }
      })();
    </script>
    <script type="module" crossorigin src="/assets/index-ncHLrZ3v.js"></script>
    <link rel="stylesheet" crossorigin href="/assets/index-BS-buxhc.css">
  </head>

  <body>
    <div id="root"></div>
  </body>
</html>
