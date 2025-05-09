<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Project Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f9;
      color: #333;
    }
    header {
      background-color: #1e1e2f;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    .container {
      max-width: 1200px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    .project {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      margin-bottom: 2rem;
      padding: 1rem;
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }
    .project img {
      max-width: 150px;
      border-radius: 8px;
    }
    .project-header {
      display: flex;
      align-items: center;
      gap: 1rem;
    }
    .project h2 {
      margin: 0;
      font-size: 1.5rem;
    }
    .tech-stack {
      margin-top: 0.5rem;
      font-style: italic;
      color: #555;
    }
    .project a {
      color: #0056b3;
      text-decoration: none;
    }
    .project a:hover {
      text-decoration: underline;
    }
    footer {
      text-align: center;
      padding: 2rem;
      font-size: 1rem;
      color: #888;
    }
  </style>
</head>
<body>
  <header>
    <h1>🚀 My Project Portfolio</h1>
  </header>
  <main class="container">
    <div class="project">
      <div class="project-header">
        <img src="images/projects4.ico" alt="Mobile App">
        <div>
          <h2>📱 Mobile Banking App Implementation (HSBC, 2024)</h2>
          <p>Led HSBC's mobile banking app development to support 25% business growth.</p>
          <p class="tech-stack">React Native, Java, Kotlin, Firebase, CI/CD</p>
          <a href="https://www.youtube.com/watch?v=your-demo-link" target="_blank">🎥 Watch Demo</a>
        </div>
      </div>
    </div>

    <div class="project">
      <div class="project-header">
        <img src="images/projects5.ico" alt="EFT">
        <div>
          <h2>💸 EFT Capacity Enhancement (HSBC, 2023)</h2>
          <p>Boosted EFT capacity by 300% via performance optimization and monitoring.</p>
          <p class="tech-stack">Java, Spring Boot, Oracle, Grafana, Prometheus</p>
          <a href="https://www.youtube.com/watch?v=your-demo-link" target="_blank">🎥 Watch Demo</a>
        </div>
      </div>
    </div>

    <div class="project">
      <div class="project-header">
        <img src="images/projects3.ico" alt="Loan Prediction">
        <div>
          <h2>🏦 Loan Eligibility Prediction System (HSBC, 2024)</h2>
          <p>Machine Learning-based system to predict customer loan eligibility.</p>
          <p class="tech-stack">Python, Pandas, Scikit-learn, Flask</p>
          <a href="https://www.youtube.com/watch?v=your-demo-link" target="_blank">🎥 Watch Demo</a>
        </div>
      </div>
    </div>

    <div class="project">
      <div class="project-header">
        <img src="images/projects4.ico" alt="Plant Disease">
        <div>
          <h2>🌿 Plant Disease Detection & Cure (2025)</h2>
          <p>Built a CNN model to detect plant diseases and suggest treatments.</p>
          <p class="tech-stack">TensorFlow, Keras, OpenCV, Python, Streamlit</p>
          <a href="https://www.youtube.com/watch?v=your-demo-link" target="_blank">🎥 Watch Demo</a>
        </div>
      </div>
    </div>

    <div class="project">
      <div class="project-header">
        <img src="images/projects5.ico" alt="Chatbot">
        <div>
          <h2>🤖 NLP Chatbot & Order Management System (2025)</h2>
          <p>Deployed a Dialogflow chatbot integrated with FastAPI and MySQL ORM system.</p>
          <p class="tech-stack">Dialogflow, FastAPI, MySQL, Python, Ngrok</p>
          <a href="https://www.youtube.com/watch?v=your-demo-link" target="_blank">🎥 Watch Demo</a>
        </div>
      </div>
    </div>

    <div class="project">
      <div class="project-header">
        <img src="images/projects9.ico" alt="GenAI">
        <div>
          <h2>🧠 Automatic Content Creator using GenAI (2025)</h2>
          <p>GenAI solution that generates resumes, blogs, and content from links or inputs.</p>
          <p class="tech-stack">LangChain, Groq Cloud, Python</p>
          <a href="https://www.youtube.com/watch?v=your-demo-link" target="_blank">🎥 Watch Demo</a>
        </div>
      </div>
    </div>

    <div class="project">
      <div class="project-header">
        <img src="images/projects8.ico" alt="Job RAG">
        <div>
          <h2>🧾 Job Hunt Automation using RAG (2025)</h2>
          <p>Automates resume/cover-letter generation using Retrieval-Augmented Generation.</p>
          <p class="tech-stack">LangChain, ChromaDB, Python, Streamlit</p>
          <a href="https://www.youtube.com/watch?v=your-demo-link" target="_blank">🎥 Watch Demo</a>
        </div>
      </div>
    </div>
  </main>

  <footer>
    &copy; 2025 Kaisar Hossain. Built with HTML and CSS.
  </footer>
</body>
</html>

