<h1>🟡 Pacman: Next Generation</h1>

<p><strong>By:</strong> Dvir Karni (<a href="https://github.com/karniDvir">karniDvir</a>)</p>

<h2>🛠️ Technologies Used</h2>
<ul>
  <li><strong>Language:</strong> C++</li>
  <li><strong>Graphics & Audio:</strong> <a href="https://www.sfml-dev.org/" target="_blank">SFML</a> (Simple and Fast Multimedia Library)</li>
  <li><strong>Game Architecture:</strong> Object-Oriented Programming with Controllers, Data Managers, and Grid-based logic</li>
  <li><strong>Code Organization:</strong> MVC-style separation with centralized game state management</li>
</ul>

<hr />

<h2>🕹️ How to Play</h2>
<ol>
  <li>Clone the repository and compile the game using a C++ compiler with SFML support.</li>
  <li>Navigate Pacman through the maze using the arrow keys.</li>
  <li>Avoid the ghosts while collecting all dots and power-ups.</li>
  <li>Each level increases in difficulty, introducing new AI and challenges.</li>
</ol>

<hr />

<h2>✨ Game Features</h2>
<ul>
  <li><strong>Enhanced AI</strong> for ghost movement and decision-making</li>
  <li><strong>Dynamic level loading</strong> using a data manager for scalable design</li>
  <li><strong>Controller system</strong> to handle player inputs, game state transitions, and collisions</li>
  <li>Grid-based navigation and enemy behavior</li>
  <li>Sound effects and visual feedback using SFML</li>
</ul>

<hr />

<h2>📁 Key Components Overview</h2>
<ul>
  <li><code>Controller.cpp</code> – Core of the game loop, input management, and state updates</li>
  <li><code>DataManager.cpp</code> – Loads levels, handles assets, and manages object placement</li>
  <li><code>Pacman.cpp</code> – Player logic, movement, and collision with ghosts or collectibles</li>
  <li><code>Demon.cpp</code> – Enemy behavior with pathfinding and adaptive chasing</li>
</ul>

<hr />

<h2>📥 Setup & Run</h2>
<pre><code>git clone https://github.com/karniDvir/Pacman-next-generation.git
cd Pacman-next-generation
# Make sure SFML is installed
# Compile the project (e.g., with g++ or your preferred IDE)
</code></pre>

<hr />

<h2>💬 Contact & Feedback</h2>
<p>
  For suggestions or questions, feel free to open an issue or contact me:<br />
  <a href="mailto:dkarni07@gmail.com">dkarni07@gmail.com</a>
</p>
