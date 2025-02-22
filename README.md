# 100 HTML Programs

---

## Program 1: Hello World HTML
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Hello World</title>
  </head>
  <body>
    <h1>Hello, World!</h1>
  </body>
</html>
```

---

## Program 2: Basic HTML Structure
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Basic HTML</title>
  </head>
  <body>
    <p>This is a basic HTML page.</p>
  </body>
</html>
```

---

## Program 3: Headings Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Headings</title>
  </head>
  <body>
    <h1>Heading 1</h1>
    <h2>Heading 2</h2>
    <h3>Heading 3</h3>
    <h4>Heading 4</h4>
    <h5>Heading 5</h5>
    <h6>Heading 6</h6>
  </body>
</html>
```

---

## Program 4: Paragraph Text
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Paragraph Example</title>
  </head>
  <body>
    <p>This is a paragraph of text in HTML.</p>
  </body>
</html>
```

---

## Program 5: Hyperlink Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Link Example</title>
  </head>
  <body>
    <a href="https://www.example.com" target="_blank">Visit Example.com</a>
  </body>
</html>
```

---

## Program 6: Unordered List
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Unordered List</title>
  </head>
  <body>
    <ul>
      <li>Item One</li>
      <li>Item Two</li>
      <li>Item Three</li>
    </ul>
  </body>
</html>
```

---

## Program 7: Ordered List
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Ordered List</title>
  </head>
  <body>
    <ol>
      <li>First</li>
      <li>Second</li>
      <li>Third</li>
    </ol>
  </body>
</html>
```

---

## Program 8: Simple Table
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Table Example</title>
  </head>
  <body>
    <table border="1">
      <tr>
        <th>Name</th>
        <th>Age</th>
      </tr>
      <tr>
        <td>Alice</td>
        <td>30</td>
      </tr>
      <tr>
        <td>Bob</td>
        <td>25</td>
      </tr>
    </table>
  </body>
</html>
```

---

## Program 9: Embedding an Image
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Image Example</title>
  </head>
  <body>
    <img src="https://via.placeholder.com/150" alt="Placeholder Image">
  </body>
</html>
```

---

## Program 10: Basic Form
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Form Example</title>
  </head>
  <body>
    <form action="#" method="post">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name">
      <input type="submit" value="Submit">
    </form>
  </body>
</html>
```

---

## Program 11: Audio Tag Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Audio Example</title>
  </head>
  <body>
    <audio controls>
      <source src="audio.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
  </body>
</html>
```

---

## Program 12: Video Tag Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Video Example</title>
  </head>
  <body>
    <video width="320" height="240" controls>
      <source src="video.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </body>
</html>
```

---

## Program 13: Div and Span Usage
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Div and Span</title>
    <style>
      .highlight { color: red; }
    </style>
  </head>
  <body>
    <div>
      This is a <span class="highlight">highlighted</span> word inside a div.
    </div>
  </body>
</html>
```

---

## Program 14: Inline CSS Styling
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Inline CSS</title>
  </head>
  <body style="background-color: #f0f0f0;">
    <h1 style="color: blue;">Styled Heading</h1>
    <p style="font-size: 16px;">This paragraph is styled inline.</p>
  </body>
</html>
```

---

## Program 15: External CSS Linking
```html
<!DOCTYPE html>
<html>
  <head>
    <title>External CSS</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <h1>External CSS Example</h1>
    <p>This page uses an external stylesheet.</p>
  </body>
</html>
```

---

## Program 16: Internal CSS Styling
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Internal CSS</title>
    <style>
      body { background-color: #e0f7fa; }
      h1 { color: darkgreen; }
    </style>
  </head>
  <body>
    <h1>Internal CSS Example</h1>
    <p>This page uses internal CSS.</p>
  </body>
</html>
```

---

## Program 17: Inline JavaScript Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Inline JavaScript</title>
  </head>
  <body>
    <h1>Click the button</h1>
    <button onclick="alert('Hello from JavaScript!')">Click Me</button>
  </body>
</html>
```

---

## Program 18: External JavaScript Linking
```html
<!DOCTYPE html>
<html>
  <head>
    <title>External JavaScript</title>
    <script src="script.js"></script>
  </head>
  <body>
    <h1>External JavaScript Example</h1>
  </body>
</html>
```

---

## Program 19: JavaScript in Head Section
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Script in Head</title>
    <script>
      function showMessage() {
        alert('Hello from the head section!');
      }
    </script>
  </head>
  <body onload="showMessage()">
    <h1>Page Loaded</h1>
  </body>
</html>
```

---

## Program 20: Meta Tags Example
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <meta name="description" content="This is a meta tag example.">
    <meta name="keywords" content="HTML, meta, example">
    <meta name="author" content="Your Name">
    <title>Meta Tags</title>
  </head>
  <body>
    <p>Check the page source for meta tags.</p>
  </body>
</html>
```

---

## Program 21: Character Encoding Declaration
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>UTF-8 Example</title>
  </head>
  <body>
    <p>Text in UTF-8 encoding: 測試</p>
  </body>
</html>
```

---

## Program 22: HTML Comment Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Comments in HTML</title>
  </head>
  <body>
    <!-- This is a comment that will not display in the browser -->
    <p>Comments help explain your code.</p>
  </body>
</html>
```

---

## Program 23: HTML5 Semantic Elements
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Semantic Elements</title>
  </head>
  <body>
    <header>
      <h1>Site Header</h1>
    </header>
    <nav>
      <a href="#">Home</a> |
      <a href="#">About</a>
    </nav>
    <main>
      <article>
        <h2>Article Title</h2>
        <p>Article content goes here.</p>
      </article>
    </main>
    <footer>
      <p>&copy; 2025 Example Corp</p>
    </footer>
  </body>
</html>
```

---

## Program 24: Sectioning Elements
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Sectioning Elements</title>
  </head>
  <body>
    <section>
      <h2>Section Title</h2>
      <p>This is a section of the page.</p>
    </section>
  </body>
</html>
```

---

## Program 25: Article and Aside
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Article and Aside</title>
  </head>
  <body>
    <article>
      <h2>Main Article</h2>
      <p>This is the main article content.</p>
    </article>
    <aside>
      <h3>Related Info</h3>
      <p>This is additional info aside from the main content.</p>
    </aside>
  </body>
</html>
```

---

## Program 26: Figure and Figcaption
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Figure Example</title>
  </head>
  <body>
    <figure>
      <img src="https://via.placeholder.com/200" alt="Sample Image">
      <figcaption>Image Caption Here</figcaption>
    </figure>
  </body>
</html>
```

---

## Program 27: Blockquote Usage
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Blockquote Example</title>
  </head>
  <body>
    <blockquote cite="https://www.example.com">
      This is a famous quote.
    </blockquote>
  </body>
</html>
```

---

## Program 28: Code Tag Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Code Example</title>
  </head>
  <body>
    <p>Here is some inline code: <code>console.log('Hello');</code></p>
  </body>
</html>
```

---

## Program 29: Preformatted Text
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Preformatted Text</title>
  </head>
  <body>
    <pre>
Line 1:    Indented text
Line 2:    More text
    </pre>
  </body>
</html>
```

---

## Program 30: Emphasis and Strong
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Emphasis Example</title>
  </head>
  <body>
    <p>This is <em>emphasized</em> and this is <strong>strong</strong> text.</p>
  </body>
</html>
```

---

## Program 31: Abbreviation Tag
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Abbreviation</title>
  </head>
  <body>
    <p>The <abbr title="HyperText Markup Language">HTML</abbr> is essential for web pages.</p>
  </body>
</html>
```

---

## Program 32: Address Tag
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Address Tag</title>
  </head>
  <body>
    <address>
      123 Main Street<br>
      Anytown, USA
    </address>
  </body>
</html>
```

---

## Program 33: Cite Tag
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Cite Example</title>
  </head>
  <body>
    <p>As stated in <cite>Example Book</cite>, HTML is fun.</p>
  </body>
</html>
```

---

## Program 34: Subscript and Superscript
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Sub and Sup</title>
  </head>
  <body>
    <p>H<sub>2</sub>O is water and E = mc<sup>2</sup>.</p>
  </body>
</html>
```

---

## Program 35: Mark Tag Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Mark Example</title>
  </head>
  <body>
    <p>This is <mark>highlighted</mark> text.</p>
  </body>
</html>
```

---

## Program 36: Embedded Map via Iframe
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Embedded Map</title>
  </head>
  <body>
    <iframe
      src="https://www.google.com/maps/embed?pb=!1m18..."
      width="600" height="450" style="border:0;" allowfullscreen>
    </iframe>
  </body>
</html>
```

---

## Program 37: Inline SVG Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Inline SVG</title>
  </head>
  <body>
    <svg width="100" height="100">
      <circle cx="50" cy="50" r="40" stroke="green"
              stroke-width="4" fill="yellow" />
    </svg>
  </body>
</html>
```

---

## Program 38: Using HTML5 Canvas
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Canvas Example</title>
  </head>
  <body>
    <canvas id="myCanvas" width="200" height="100" style="border:1px solid #000000;"></canvas>
    <script>
      var canvas = document.getElementById('myCanvas');
      var context = canvas.getContext('2d');
      context.fillStyle = 'blue';
      context.fillRect(10, 10, 150, 75);
    </script>
  </body>
</html>
```

---

## Program 39: Button with JavaScript Alert
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Button Alert</title>
  </head>
  <body>
    <button onclick="alert('Button clicked!')">Click Me</button>
  </body>
</html>
```

---

## Program 40: Various Input Types
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Input Types</title>
  </head>
  <body>
    <form>
      <input type="text" placeholder="Text Input"><br><br>
      <input type="password" placeholder="Password"><br><br>
      <input type="email" placeholder="Email"><br><br>
      <input type="number" placeholder="Number">
    </form>
  </body>
</html>
```

---

## Program 41: Select Dropdown
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Select Dropdown</title>
  </head>
  <body>
    <form>
      <label for="fruit">Choose a fruit:</label>
      <select id="fruit" name="fruit">
        <option value="apple">Apple</option>
        <option value="banana">Banana</option>
        <option value="cherry">Cherry</option>
      </select>
    </form>
  </body>
</html>
```

---

## Program 42: Checkbox Group
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Checkbox Group</title>
  </head>
  <body>
    <form>
      <label><input type="checkbox" name="option" value="A"> Option A</label><br>
      <label><input type="checkbox" name="option" value="B"> Option B</label><br>
      <label><input type="checkbox" name="option" value="C"> Option C</label>
    </form>
  </body>
</html>
```

---

## Program 43: Radio Buttons Group
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Radio Buttons</title>
  </head>
  <body>
    <form>
      <label><input type="radio" name="gender" value="male"> Male</label><br>
      <label><input type="radio" name="gender" value="female"> Female</label>
    </form>
  </body>
</html>
```

---

## Program 44: HTML5 Video with Controls
```html
<!DOCTYPE html>
<html>
  <head>
    <title>HTML5 Video</title>
  </head>
  <body>
    <video width="320" height="240" controls>
      <source src="movie.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </body>
</html>
```

---

## Program 45: HTML5 Audio with Controls
```html
<!DOCTYPE html>
<html>
  <head>
    <title>HTML5 Audio</title>
  </head>
  <body>
    <audio controls>
      <source src="sound.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
  </body>
</html>
```

---

## Program 46: Data Attributes Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Data Attributes</title>
  </head>
  <body>
    <div data-info="Sample Data">Hover to see data attribute in inspector.</div>
  </body>
</html>
```

---

## Program 47: Details and Summary
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Details and Summary</title>
  </head>
  <body>
    <details>
      <summary>More Information</summary>
      <p>This is the hidden content revealed when expanded.</p>
    </details>
  </body>
</html>
```

---

## Program 48: Progress Element
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Progress Bar</title>
  </head>
  <body>
    <progress value="70" max="100"></progress>
  </body>
</html>
```

---

## Program 49: Meter Element
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Meter Example</title>
  </head>
  <body>
    <meter value="0.6">60%</meter>
  </body>
</html>
```

---

## Program 50: Inline List Styling with CSS
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Styled List</title>
    <style>
      ul.styled li {
        color: purple;
        font-weight: bold;
      }
    </style>
  </head>
  <body>
    <ul class="styled">
      <li>Styled Item 1</li>
      <li>Styled Item 2</li>
      <li>Styled Item 3</li>
    </ul>
  </body>
</html>
```

---

## Program 51: Responsive Design Meta Tag
```html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Meta Tag</title>
  </head>
  <body>
    <p>This page is responsive!</p>
  </body>
</html>
```

---

## Program 52: Favicon Linking
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Favicon Example</title>
    <link rel="icon" href="favicon.ico" type="image/x-icon">
  </head>
  <body>
    <p>Favicon should appear in the browser tab.</p>
  </body>
</html>
```

---

## Program 53: Table with Border Styling
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Styled Table</title>
  </head>
  <body>
    <table border="1">
      <tr>
        <th>Header 1</th>
        <th>Header 2</th>
      </tr>
      <tr>
        <td>Data 1</td>
        <td>Data 2</td>
      </tr>
    </table>
  </body>
</html>
```

---

## Program 54: Form with Multiple Input Types
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Multi-Input Form</title>
  </head>
  <body>
    <form>
      <input type="text" placeholder="Text"><br>
      <input type="email" placeholder="Email"><br>
      <input type="password" placeholder="Password"><br>
      <input type="submit" value="Submit">
    </form>
  </body>
</html>
```

---

## Program 55: Fieldset and Legend
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Fieldset Example</title>
  </head>
  <body>
    <form>
      <fieldset>
        <legend>Personal Information</legend>
        <label>Name: <input type="text"></label><br>
        <label>Email: <input type="email"></label>
      </fieldset>
    </form>
  </body>
</html>
```

---

## Program 56: Label Tag Usage
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Label Example</title>
  </head>
  <body>
    <form>
      <label for="username">Username:</label>
      <input type="text" id="username">
    </form>
  </body>
</html>
```

---

## Program 57: Input Type Date
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Date Input</title>
  </head>
  <body>
    <form>
      <label for="dob">Date of Birth:</label>
      <input type="date" id="dob" name="dob">
    </form>
  </body>
</html>
```

---

## Program 58: Input Type Range
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Range Input</title>
  </head>
  <body>
    <form>
      <label for="volume">Volume:</label>
      <input type="range" id="volume" name="volume" min="0" max="100">
    </form>
  </body>
</html>
```

---

## Program 59: Canvas with Fallback
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Canvas with Fallback</title>
  </head>
  <body>
    <canvas id="myCanvas" width="200" height="100" style="border:1px solid #000;">
      Your browser does not support the canvas element.
    </canvas>
  </body>
</html>
```

---

## Program 60: Embed Tag Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Embed Example</title>
  </head>
  <body>
    <embed src="document.pdf" type="application/pdf" width="600" height="400">
  </body>
</html>
```

---

## Program 61: Object Tag Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Object Tag</title>
  </head>
  <body>
    <object data="document.pdf" type="application/pdf" width="600" height="400">
      <p>Your browser does not support PDFs.</p>
    </object>
  </body>
</html>
```

---

## Program 62: SVG Circle Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>SVG Circle</title>
  </head>
  <body>
    <svg width="100" height="100">
      <circle cx="50" cy="50" r="40" fill="red" />
    </svg>
  </body>
</html>
```

---

## Program 63: SVG Rectangle Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>SVG Rectangle</title>
  </head>
  <body>
    <svg width="200" height="100">
      <rect width="200" height="100" fill="blue" />
    </svg>
  </body>
</html>
```

---

## Program 64: SVG Text Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>SVG Text</title>
  </head>
  <body>
    <svg width="300" height="100">
      <text x="10" y="50" font-family="Verdana" font-size="24" fill="green">
        SVG Text Example
      </text>
    </svg>
  </body>
</html>
```

---

## Program 65: Audio with Source Tag
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Audio with Source</title>
  </head>
  <body>
    <audio controls>
      <source src="sound.ogg" type="audio/ogg">
      <source src="sound.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
  </body>
</html>
```

---

## Program 66: Video with Source Tag
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Video with Source</title>
  </head>
  <body>
    <video width="320" height="240" controls>
      <source src="movie.ogg" type="video/ogg">
      <source src="movie.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </body>
</html>
```

---

## Program 67: Drag and Drop (Basic)
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Drag and Drop</title>
    <style>
      #drag { width: 100px; height: 100px; background: coral; cursor: move; }
      #drop { width: 150px; height: 150px; border: 2px dashed #ccc; margin-top: 20px; }
    </style>
  </head>
  <body>
    <div id="drag" draggable="true" ondragstart="event.dataTransfer.setData('text/plain',null);">
      Drag Me
    </div>
    <div id="drop" ondragover="event.preventDefault();" ondrop="this.style.background='lightgreen';">
      Drop Here
    </div>
  </body>
</html>
```

---

## Program 68: Form Validation Attributes
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Form Validation</title>
  </head>
  <body>
    <form>
      <input type="text" placeholder="Required Field" required>
      <input type="email" placeholder="Enter a valid email" required>
      <input type="submit">
    </form>
  </body>
</html>
```

---

## Program 69: Image Map Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Image Map</title>
  </head>
  <body>
    <img src="https://via.placeholder.com/400" usemap="#map">
    <map name="map">
      <area shape="rect" coords="34,44,270,350" href="https://www.example.com" alt="Example">
    </map>
  </body>
</html>
```

---

## Program 70: External Link with Target
```html
<!DOCTYPE html>
<html>
  <head>
    <title>External Link</title>
  </head>
  <body>
    <a href="https://www.example.com" target="_blank">Open Example.com in new tab</a>
  </body>
</html>
```

---

## Program 71: CSS Flexbox (Inline Style)
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Flexbox Example</title>
  </head>
  <body style="display: flex; justify-content: space-around; background: #f9f9f9;">
    <div style="background: lightblue; padding: 20px;">Box 1</div>
    <div style="background: lightgreen; padding: 20px;">Box 2</div>
    <div style="background: lightcoral; padding: 20px;">Box 3</div>
  </body>
</html>
```

---

## Program 72: CSS Grid (Inline Style)
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Grid Example</title>
  </head>
  <body style="display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 10px;">
    <div style="background: #ffcccb; padding: 20px;">Grid 1</div>
    <div style="background: #d1e7dd; padding: 20px;">Grid 2</div>
    <div style="background: #cfe2ff; padding: 20px;">Grid 3</div>
  </body>
</html>
```

---

## Program 73: Meta Viewport Tag
```html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Viewport Example</title>
  </head>
  <body>
    <p>This page is optimized for mobile devices.</p>
  </body>
</html>
```

---

## Program 74: Base Tag Example
```html
<!DOCTYPE html>
<html>
  <head>
    <base href="https://www.example.com/">
    <title>Base Tag</title>
  </head>
  <body>
    <a href="page.html">Link using base URL</a>
  </body>
</html>
```

---

## Program 75: Time Tag Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Time Tag</title>
  </head>
  <body>
    <p>Published on: <time datetime="2025-02-21">February 21, 2025</time></p>
  </body>
</html>
```

---

## Program 76: Progress Element Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Progress Element</title>
  </head>
  <body>
    <progress value="40" max="100"></progress>
  </body>
</html>
```

---

## Program 77: Output Tag Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Output Element</title>
  </head>
  <body>
    <form oninput="result.value=parseInt(a.value)+parseInt(b.value)">
      <input type="range" id="a" value="50"> +
      <input type="number" id="b" value="50">
      = <output name="result" for="a b">100</output>
    </form>
  </body>
</html>
```

---

## Program 78: BDI Tag Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>BDI Example</title>
  </head>
  <body>
    <p>User: <bdi>اسم المستخدم</bdi></p>
  </body>
</html>
```

---

## Program 79: WBR Tag Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>WBR Example</title>
  </head>
  <body>
    <p>ThisIsAReallyLongWord<wbr>ThatMayBreakInTheMiddle.</p>
  </body>
</html>
```

---

## Program 80: Ruby Annotation
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Ruby Annotation</title>
  </head>
  <body>
    <ruby>
      漢 <rt>kan</rt>
    </ruby>
  </body>
</html>
```

---

## Program 81: Track Tag for Subtitles
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Track Tag</title>
  </head>
  <body>
    <video controls width="320">
      <source src="movie.mp4" type="video/mp4">
      <track kind="subtitles" label="English" srclang="en" src="subtitles_en.vtt" default>
      Your browser does not support the video tag.
    </video>
  </body>
</html>
```

---

## Program 82: Noscript Tag Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Noscript Example</title>
  </head>
  <body>
    <noscript>
      <p>Please enable JavaScript to view this page correctly.</p>
    </noscript>
    <p>If JavaScript is enabled, this text is visible.</p>
  </body>
</html>
```

---

## Program 83: Iframe with Attributes
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Iframe Example</title>
  </head>
  <body>
    <iframe src="https://www.example.com" width="600" height="400" frameborder="0" allowfullscreen>
      Your browser does not support iframes.
    </iframe>
  </body>
</html>
```

---

## Program 84: Preloading a Font with Link
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Preload Font</title>
    <link rel="preload" href="fonts/MyFont.woff2" as="font" type="font/woff2" crossorigin>
  </head>
  <body>
    <p style="font-family: 'MyFont', sans-serif;">This text uses a preloaded font.</p>
  </body>
</html>
```

---

## Program 85: CSS Animation via Style Tag
```html
<!DOCTYPE html>
<html>
  <head>
    <title>CSS Animation</title>
    <style>
      @keyframes fadeIn {
        from { opacity: 0; }
        to { opacity: 1; }
      }
      .animate {
        animation: fadeIn 2s ease-in;
      }
    </style>
  </head>
  <body>
    <h1 class="animate">Fading In!</h1>
  </body>
</html>
```

---

## Program 86: CSS Pseudo-elements Inline
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Pseudo-elements</title>
    <style>
      p::after {
        content: " - End of Paragraph";
        color: gray;
      }
    </style>
  </head>
  <body>
    <p>This paragraph has a pseudo-element.</p>
  </body>
</html>
```

---

## Program 87: Script with Defer Attribute
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Defer Script</title>
    <script defer>
      document.addEventListener('DOMContentLoaded', function() {
        console.log('Deferred script executed.');
      });
    </script>
  </head>
  <body>
    <p>Check the console for deferred script output.</p>
  </body>
</html>
```

---

## Program 88: Script with Async Attribute
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Async Script</title>
    <script async>
      console.log('Async script executed.');
    </script>
  </head>
  <body>
    <p>Async script example.</p>
  </body>
</html>
```

---

## Program 89: Header with Navigation Links
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Header Navigation</title>
  </head>
  <body>
    <header>
      <h1>Site Title</h1>
      <nav>
        <a href="#">Home</a> |
        <a href="#">Services</a> |
        <a href="#">Contact</a>
      </nav>
    </header>
  </body>
</html>
```

---

## Program 90: Footer with Copyright
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Footer Example</title>
  </head>
  <body>
    <footer>
      <p>&copy; 2025 Your Company</p>
    </footer>
  </body>
</html>
```

---

## Program 91: Aside for Side Content
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Aside Example</title>
  </head>
  <body>
    <aside style="background:#f0f0f0; padding:10px;">
      <h3>Side Note</h3>
      <p>This is additional information.</p>
    </aside>
  </body>
</html>
```

---

## Program 92: Main Content Element
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Main Element</title>
  </head>
  <body>
    <main>
      <h1>Main Content</h1>
      <p>This is the primary content of the page.</p>
    </main>
  </body>
</html>
```

---

## Program 93: Mark Element for Highlighting
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Mark Element</title>
  </head>
  <body>
    <p>You should <mark>remember</mark> this important note.</p>
  </body>
</html>
```

---

## Program 94: Small Element Example
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Small Text</title>
  </head>
  <body>
    <p><small>This text is small.</small></p>
  </body>
</html>
```

---

## Program 95: Cite Element Usage
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Cite Element</title>
  </head>
  <body>
    <p><cite>Source Title</cite> is cited here.</p>
  </body>
</html>
```

---

## Program 96: Deleted and Inserted Text
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Del and Ins</title>
  </head>
  <body>
    <p>This sentence has <del>old text</del> and <ins>new text</ins>.</p>
  </body>
</html>
```

---

## Program 97: Keyboard Input (kbd)
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Keyboard Input</title>
  </head>
  <body>
    <p>Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to copy.</p>
  </body>
</html>
```

---

## Program 98: Sample Output (samp)
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Sample Output</title>
  </head>
  <body>
    <p>The output of the command is: <samp>File not found</samp></p>
  </body>
</html>
```

---

## Program 99: Variable Tag (var)
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Variable Tag</title>
  </head>
  <body>
    <p>In the equation <var>a</var> + <var>b</var> = <var>c</var>, the variables represent numbers.</p>
  </body>
</html>
```

---

## Program 100: Combining HTML Elements
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Combined Elements</title>
    <style>
      body { font-family: Arial, sans-serif; margin: 20px; }
      header, footer { background: #ddd; padding: 10px; text-align: center; }
      main { margin: 20px 0; }
    </style>
  </head>
  <body>
    <header>
      <h1>My Website</h1>
    </header>
    <main>
      <article>
        <h2>Welcome!</h2>
        <p>This page combines various HTML elements to build a complete web page.</p>
      </article>
    </main>
    <footer>
      <p>&copy; 2025 My Website</p>
    </footer>
  </body>
</html>
```

---

Enjoy exploring, testing, and modifying these HTML examples!
