<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Cybersecurity Blog</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      display: flex;
    }
    /* Sidebar */
    .sidebar {
      width: 250px;
      background: #f4f4f4;
      padding: 20px;
      height: 100vh;
      border-right: 1px solid #ddd;
    }
    .sidebar h2 {
      font-size: 18px;
      margin-top: 20px;
    }
    .sidebar ul {
      list-style: none;
      padding: 0;
    }
    .sidebar li {
      margin: 6px 0;
    }
    .sidebar li::before {
      content: "• ";
      color: #0073e6;
    }
    /* Main content */
    .content {
      flex: 1;
      padding: 30px;
    }
    .content h1 {
      font-size: 28px;
      margin-bottom: 10px;
    }
    .content p {
      line-height: 1.6;
    }
  </style>
</head>
<body>

  <div class="sidebar">
    <h2>Certifications</h2>
    <ul>
      <li>INE: eJPTv2, eWPTv2, eCIR, eCDFP</li>
      <li>CompTIA: Security+, CySA+</li>
      <li>CISCO: CCNA</li>
    </ul>

    <h2>Courses</h2>
    <ul>
      <li>TCM: Ethical Hacker, SOC 101, Malware Analysis</li>
      <li>JH: 12 Days of Defense</li>
      <li>SANS: SEC450</li>
    </ul>
  </div>

  <div class="content">
    <h1>Hello, I’m [Your Name]</h1>
    <p>
      Welcome to my personal blog! I’m a cybersecurity enthusiast and recent Computer Engineering graduate. 
      Here, I’ll share my journey through certifications, courses, and hands-on experience in areas like SOC analysis, 
      digital forensics, and penetration testing.
    </p>
    <p>
      Use the sidebar to explore my certifications, courses, and blog posts as I document my learning path.
    </p>
  </div>

</body>
</html>
