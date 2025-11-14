Automated CI/CD Deployment Pipeline for DevOps Practice:
   This is a simple and fully functional To-Do List web application built using HTML, CSS, and vanilla JavaScript. The project stores tasks using LocalStorage, meaning the tasks remain saved even after you refresh or reopen the browser.
   The primary goal of this project is not just the UI functionality, but to serve as a beginner-friendly DevOps CI/CD demonstration using tools like Git, GitHub, and Jenkins.
CI/CD pipeline:
  Developer updates code locally
  Pushes changes to GitHub
  Jenkins automatically triggers (via webhook or polling)
  Jenkins pulls the latest code from GitHub
  Jenkins executes build steps (optional for frontend projects)
  Deployment step runs (e.g., copy files to a server directory, AWS S3, Apache root, etc.)
  Website updates automatically
