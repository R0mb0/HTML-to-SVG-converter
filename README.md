<div align="center">
      <h1>🎨 HTML to SVG Converter ✂️</h1>
  </div>

  <p align="center">
      A lightning-fast, zero-dependency web app that converts HTML/CSS snippets into perfectly sized, transparent SVG graphics. Runs entirely in your browser. Perfect for creating custom badges, logos, and UI components!
  </p>

  <div align="center">
      <h2><a href="https://r0mb0.github.io/HTML-to-SVG-converter/">👉 Click here to test the app! 👈</a></h2>

[![0001.png](https://github.com/R0mb0/HTML-to-SVG-converter/blob/main/Readme_imgs/0001.png?raw=true)](https://r0mb0.github.io/HTML-to-SVG-converter/)
[![0002.png](https://github.com/R0mb0/HTML-to-SVG-converter/blob/main/Readme_imgs/0002.png?raw=true)](https://r0mb0.github.io/HTML-to-SVG-converter/)
        
  </div>

  <h2>📄 Example snippet to test</h2>
  <pre><code class="language-html">&lt;div style="background: #1e1e1e; color: white; border: 3px solid #9fa9a3; border-radius: 15px; padding: 10px 20px; display: inline-flex; align-items: center; gap: 15px; font-family: Arial, sans-serif;"&gt;
  &lt;div style="width: 30px; height: 30px; border: 2px solid #4ade80; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: bold;"&gt;AI&lt;/div&gt;
  &lt;div style="font-size: 15px; line-height: 1.2;"&gt;&lt;b&gt;Crafted&lt;/b&gt;&lt;br&gt;with AI&lt;/div&gt;
&lt;/div&gt;</code></pre>

  <hr>

  <h2>🚀 Features</h2>
  <ul>
      <li><strong>Zero Dependencies</strong>: No React, no Tailwind, no Node.js required. Just pure, lightweight Vanilla JavaScript, HTML5, and CSS3.</li>
      <li><strong>100% Client-Side</strong>: Everything happens locally in your browser. No server calls, no data tracking, instant rendering.</li>
      <li><strong>Sub-Pixel Accuracy</strong>: Automatically measures your HTML content using <code>getBoundingClientRect()</code> to crop the SVG perfectly around your design.</li>
      <li><strong>Smart Auto-Correction</strong>: Uses <code>XMLSerializer</code> to automatically fix unclosed tags (like <code>&lt;br&gt;</code>) converting standard HTML into strict, SVG-compatible XHTML.</li>
      <li><strong>Transparency Support</strong>: Renders a checkerboard background in the preview to easily check your transparent areas.</li>
      <li><strong>Modern UI</strong>: Fast, responsive, and adaptive Dark/Light mode interface based on your system preferences.</li>
  </ul>

  <h2>🛠️ How it works</h2>
  <ol>
      <li><strong>Paste the HTML</strong> code into the left panel.</li>
      <li>The app injects your code into an invisible, isolated DOM container to <strong>measure its exact width and height</strong>.</li>
      <li>It sanitizes the code using <code>XMLSerializer</code>, wrapping it into a valid <strong>XHTML</strong> format.</li>
      <li>It embeds the XHTML into an SVG <code>&lt;foreignObject&gt;</code> tag with matching dimensions.</li>
      <li>The browser renders the SVG in real-time in the preview panel. Click <strong>Download</strong> to get your <code>.svg</code> file!</li>
  </ol>

  <h2>🏆 What makes it special?</h2>
  <ul>
      <li><strong>Instant Offline Access</strong>: Since it doesn't require a backend, you can literally save the <code>index.html</code> file on your desktop and use it offline forever.</li>
      <li><strong>No Build Step</strong>: You don't need Webpack, Vite, or npm to run or modify this project. Just open the code in any text editor.</li>
  </ul>

  <h2>💡 Why use this tool?</h2>
  <ul>
      <li><strong>GitHub Readmes</strong>: Easily create custom, beautifully styled badges or banners (using HTML/CSS) and convert them to SVGs to embed in your repositories.</li>
      <li><strong>UI Mockups</strong>: Convert web components directly into vector graphics for presentations or documentation.</li>
      <li><strong>Logo Creation</strong>: Prototype quick logos using web fonts and CSS shapes, then export them cleanly.</li>
  </ul>

  <h2>⚡ Getting Started</h2>

  <h3>Online</h3>
  <p>Simply visit the <a href="https://r0mb0.github.io/HTML-to-SVG-converter/">Live Demo hosted on GitHub Pages</a>.</p>

  <h3>Local Installation</h3>
  <p>Running this tool locally is ridiculously easy:</p>
  <ol>
      <li><strong>Clone this repository</strong> or simply download the <code>index.html</code> file.</li>
      <li>Double-click <code>index.html</code> to open it in your favorite browser.</li>
      <li>Done. No <code>npm install</code>, no local servers needed!</li>
  </ol>
