<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Python Competitive Programming Template - README</title>
</head>
<body>
  <h1>🐍 Python Competitive Programming Template</h1>

  <p>
    This repository provides a ready-to-use setup for competitive programming in Python using VS Code. It helps you quickly run code with input/output through text files, streamlining your workflow during contests or practice.
  </p>

  <h2>📁 What's Included</h2>
  <ul>
    <li><code>main.py</code> – Your Python solution file.</li>
    <li><code>input.txt</code> – The input file to simulate standard input.</li>
    <li><code>output.txt</code> – The file where your program's output will be saved.</li>
    <li><code>.vscode/tasks.json</code> – Preconfigured task to run Python with I/O redirection.</li>
  </ul>

  <h2>🚀 Setup Instructions</h2>

  <h3>1. Install VS Code</h3>
  <p>
    Download and install <a href="https://code.visualstudio.com/" target="_blank">Visual Studio Code</a> if it's not already installed.
  </p>

  <h3>2. Clone the Repository</h3>
  <pre><code>git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name</code></pre>

  <h3>3. Open and Arrange Files in VS Code</h3>
  <ul>
    <li>Open <code>main.py</code> and move it to the <strong>left pane</strong>.</li>
    <li>Open <code>input.txt</code> and <code>output.txt</code>.</li>
    <li>Go to <strong>View → Editor Layout → Split Down</strong> to place them vertically on the right.</li>
  </ul>

  <h3>4. Configure Task Runner</h3>
  <ol>
    <li>Go to <strong>Terminal → Configure Tasks → Create tasks.json file from template → Others</strong>.</li>
    <li>Delete the default content and paste the content from <code>tasks.json</code> included in this repo.</li>
  </ol>

  <h3>5. Run Your Code</h3>
  <p>
    After writing your Python code in <code>main.py</code>, press <strong>Ctrl + Shift + B</strong> to execute it. The program will read from <code>input.txt</code> and save the output to <code>output.txt</code>.
  </p>

  <h2>💡 Troubleshooting</h2>
  <p>
    If you face any issues, consider using tools like ChatGPT or Bard to debug errors efficiently.
  </p>

  <p>Happy coding! 🚀</p>
</body>
</html>
