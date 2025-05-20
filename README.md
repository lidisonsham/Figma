# Ex09 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Saveetha Techathon 2025</title>
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: #2e5621;
      color: white;
    }
    section {
      padding: 20px;
      border-bottom: 3px solid #1a3a12;
    }
    h2, h3 {
      color: #11C7FF;
    }
    ul, ol {
      margin-left: 20px;
    }
    .form-input {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: none;
      font-size: 16px;
    }
    .form-section {
      background-color: #2e5621;
    }
    input {
      background-color: white;
      color: black;
    }
    table {
      width: 100%;
      border-collapse: collapse;
    }
    td {
      padding: 5px 0;
    }
    .center {
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .button {
      background-color: #11C7FF;
      color: white;
      padding: 10px 30px;
      font-size: 24px;
      margin: 10px;
      text-align: center;
      cursor: pointer;
      border: none;
    }
  </style>
</head>
<body>

<!-- Page 1: Banner -->
<section class="center" style="flex-direction: column;">
  <img src="saveetha-logo.png" alt="Saveetha Logo" style="width: 350px;" />
  <h2>SAVEETHA TECHATHON 2025</h2>
  <h3>AI FOR HEALTHCARE INNOVATION</h3>
  <img src="techathon-banner.png" alt="AI and Healthcare Image" style="width: 100%; max-width: 400px; margin: 20px 0;" />
  <p style="text-align: center;">FIGHT TILL LAST BREATH</p>
  <div>
    <button class="button">REGISTER</button>
    <button class="button">LOGIN</button>
  </div>
</section>

<!-- Page 2: Objective & Event Details -->
<section>
  <img src="healthai-logo.png" alt="HealthAI Logo" style="width: 100px; margin: 20px auto; display: block;" />
  <h2>🎯 Objective:</h2>
  <p>To bring together students, developers, and AI enthusiasts to build innovative solutions using Artificial Intelligence for solving real-world healthcare problems.</p>

  <h3>📅 Event Details:</h3>
  <ul>
    <li>⏱ Duration: 24 to 48 hours (Hackathon format)</li>
    <li>💻 Mode: Offline / Online / Hybrid</li>
    <li>👥 Team Size: 2–5 members</li>
    <li>🎓 Eligibility: College students, AI developers, healthcare tech enthusiasts</li>
    <li>💸 Registration: Optional (Free / Nominal)</li>
    <li>🛠 Platform: Devpost / Google Forms + GitHub for submissions</li>
  </ul>

  <h3>🛠 Themes / Tracks:</h3>
  <ol>
    <li>Early Disease Detection</li>
    <li>Medical Imaging using AI</li>
    <li>Smart Health Monitoring</li>
    <li>AI in Mental Health</li>
    <li>Emergency Alert Systems</li>
    <li>AI Chatbots for Healthcare Guidance</li>
  </ol>
</section>

<!-- Page 3: Deliverables, Judging, Prizes -->
<section>
  <img src="healthai-logo.png" alt="HealthAI Logo" style="width: 100px; margin: 10px auto; display: block;" />
  <h3>✏ Deliverables:</h3>
  <ul>
    <li>📱 Android/Web App or Prototype</li>
    <li>💻 Code (GitHub repo)</li>
    <li>🎬 Short demo video (2–5 mins)</li>
    <li>📄 PPT/Report explaining model, tech stack, impact, innovation</li>
  </ul>

  <h3>💡 Judging Criteria:</h3>
  <table>
    <tr><td>Innovation & Uniqueness</td><td style="text-align: right;">25%</td></tr>
    <tr><td>Technical Execution</td><td style="text-align: right;">25%</td></tr>
    <tr><td>Relevance to Healthcare</td><td style="text-align: right;">20%</td></tr>
    <tr><td>Feasibility & Impact</td><td style="text-align: right;">20%</td></tr>
    <tr><td>UI/UX Design</td><td style="text-align: right;">10%</td></tr>
  </table>

  <h3>🎁 Prizes & Perks:</h3>
  <ul>
    <li>🏆 Winner: ₹10,000 (customizable)</li>
    <li>🥈 Runner-up: ₹5,000</li>
    <li>🏅 Best Innovation / Best AI Model</li>
    <li>🎓 Internship Opportunities / Certificates</li>
  </ul>
</section>

<!-- Page 4: Registration Form -->
<section class="form-section">
  <img src="saveetha-logo.png" alt="Saveetha Logo" style="width: 350px;" />
  <h2>Techathon Registration Form</h2>

  <form>
    <input type="text" class="form-input" placeholder="Full Name" required />
    <input type="text" class="form-input" placeholder="Gender" required />
    <input type="number" class="form-input" placeholder="Age" required />
    <input type="text" class="form-input" placeholder="Register Number" required />
    <input type="text" class="form-input" placeholder="Department" required />
    <input type="tel" class="form-input" placeholder="Mobile No" required />
    <input type="email" class="form-input" placeholder="Email ID" required />
    <button class="button" type="submit">Submit</button>
  </form>
</section>

</body>
</html>
```

## OUTPUT:
![Screenshot 2025-05-12 211905](https://github.com/user-attachments/assets/1d678ed7-1315-441f-b2de-b20d219bbc39)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
