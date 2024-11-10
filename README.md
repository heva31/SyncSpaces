<header>
  <h1>SyncSpaces</h1>
  <p><strong>SyncSpaces</strong> is a real-time, synchronized chat application designed to facilitate seamless communication within secure, dynamic chat rooms. It allows users to create and manage multiple chat spaces, ensuring fluid, interactive conversations in a collaborative environment. SyncSpaces is built with modern web technologies, including Flask, SQLAlchemy, and WebSockets, making it fast, reliable, and scalable.</p>
</header>

<section id="features">
<h2>Features</h2>
<ul>
<li><strong>Real-Time Messaging</strong>: Instant communication with WebSocket support for low-latency messaging.</li>
<li><strong>Chat Room Creation</strong>: Users can create, join, and leave custom chat rooms to organize conversations.</li>
<li><strong>Password Protection</strong>: Chat rooms can be secured with a password for private, secure communication.</li>
<li><strong>Message Timestamps</strong>: Every message is timestamped using Indian Standard Time (IST) for accurate conversation tracking.</li>
<li><strong>User-Friendly Interface</strong>: Easy-to-use, intuitive interface for smooth navigation and interaction.</li>
<li><strong>Scalable and Extensible</strong>: Built to scale with ease, supporting future feature enhancements and integrations.</li>
<li><strong>Dark Mode in Chat Rooms</strong>:Offers a dark mode feature for the chat room, providing users with a comfortable and visually pleasing experience in low-light environments.
</li>
</ul>
</section>

<section id="tech-stack">
  <h2>Tech Stack</h2>
  <ul>
      <li><strong>Backend</strong>: Flask, Flask-SocketIO, SQLAlchemy</li>
      <li><strong>Frontend</strong>: HTML, CSS, JavaScript</li>
      <li><strong>Database</strong>: SQLite (for storage of chat rooms and messages)</li>
      <li><strong>WebSocket</strong>: Flask-SocketIO for real-time communication</li>
      <li><strong>Time Zone Support</strong>: pytz for Indian Standard Time (IST) localization</li>
  </ul>
</section>

<section id="installation">
  <h2>Installation</h2>
  <h3>Prerequisites</h3>
  <p>Ensure you have the following tools installed:</p>
  <ul>
      <li>Python 3.x</li>
      <li>pip (Python package manager)</li>
  </ul>
  <h3>Setup Instructions</h3>
  <ol>
      <li>Clone the repository:</li>
      <pre><code>git clone https://github.com/yourusername/SyncSpaces.git</code></pre>
      <pre><code>cd SyncSpaces</code></pre>
      <li>Install the necessary Python dependencies:</li>
      <pre><code>pip install -r requirements.txt</code></pre>
      <li>Run the application:</li>
      <pre><code>python app.py</code></pre>
      <li>Open your browser and navigate to <a href="http://127.0.0.1:5000" target="_blank">http://127.0.0.1:5000</a> to start using SyncSpaces.</li>
  </ol>
</section>

<section id="how-it-works">
  <h2>How It Works</h2>
  <ol>
      <li><strong>Creating a Chat Room</strong>: Users can create a chat room by providing a name and optional password. Once created, the room is available for users to join.</li>
      <li><strong>Joining a Chat Room</strong>: Users can join an existing chat room by entering the room name and, if applicable, the password.</li>
      <li><strong>Sending Messages</strong>: Real-time messaging is enabled via WebSockets. Messages appear instantly in the chat room for all participants.</li>
      <li><strong>Leaving a Chat Room</strong>: Users can leave the room at any time, with their session ending once they disconnect.</li>
  </ol>
</section>

<section id="project-structure">
  <h2>Project Structure</h2>
  <pre><code>
SyncSpaces/
│
├── app.py              # Main application file (Flask server)
├── instance           # Database models for chat rooms and messages
├── requirements.txt    # List of dependencies
├── static/             # Static files (CSS, images, etc.)
│   └── css             # Custom styles
│   └── images          # Custom images 
├── templates/          # HTML templates
│   ├── base.html      # Home page for chat rooms
│   ├── create_room.html     # create chat rooms
│   ├── index.html      # main chat rooms page 
│   ├── join_room.html     # join chat rooms page 
│   └── room.html  # Chat room interface
└── README.md           # Project documentation
  </code></pre>
</section>

<section id="contributing">
  <h2>Contributing</h2>
  <p>Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request. We encourage contributions that improve the app's performance, add new features, or fix bugs.</p>
  <h3>Steps to Contribute:</h3>
  <ol>
      <li>Fork the repository.</li>
      <li>Create a new branch for your feature (<code>git checkout -b feature-name</code>).</li>
      <li>Make your changes and commit them (<code>git commit -m 'Add feature-name'</code>).</li>
      <li>Push to the branch (<code>git push origin feature-name</code>).</li>
      <li>Open a pull request.</li>
  </ol>
</section>

