<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Peter Manning</title>
<style>
  /* Styles for buttons */
  .btn {
    display: inline-block;
    padding: 10px 20px;
    margin: 5px;
    border-radius: 5px;
    text-decoration: none;
    color: white;
    font-weight: bold;
    font-size: 16px;
  }
  .btn-primary { background-color: #007bff; }
  .btn-success { background-color: #28a745; }
  .btn-info { background-color: #17a2b8; }

  /* Styles for contact icons */
  .contact-button img {
    width: 32px;
    height: 32px;
    vertical-align: middle;
  }
  .contact-button {
    display: inline-block;
    margin: 5px;
    text-decoration: none;
  }
</style>
</head>
<body>

<!-- Top Section: Navigation Buttons -->
<div class="btn-container">
  <a href="README.md" class="btn btn-primary">Home</a>
  <a href="projectPage.md" class="btn btn-success">Projects</a>
  <a href="about.md" class="btn btn-info">About</a>
</div>

<!-- Middle Section: Description -->
<h2>About me:</h2>
<p>
  With two years of technical experience under my belt, I’m proficient in several technical abilities, including data wrangling, pipelining, storage, analysis and visualization, and modeling. <br>I'm proficient in Python, Java, SQL & PostgreSQL, and R, and I'm in the process of learning Go and CSS/HTML/JS/React for web development.
</p>

<h2>My goals:</h2>
<p>
  I’m seeking a full-time role in data analytics/data engineering. Solving real problems with strategic use of, and the collection and storage of data is my specialty! Additionally, I'm intending on pursuing a master's in machine learning in my future for a career in AI and applied ML.
</p>

<p>↓ Don't hesitate to get in touch! ↓</p>

<!-- Bottom Section: Contact Buttons -->
<div>
  <a href="https://www.linkedin.com/in/your-profile" class="contact-button">
    <img src="images/linkedin.jpg" alt="LinkedIn">
  </a>
  <a href="https://docs.google.com/document/d/12OT1G2pk7JruC2Z_F1J2xMmz6Qf-urPc/edit?usp=sharing&ouid=116509027107431059441&rtpof=true&sd=true" class="contact-button">
    <img src="images/files.png" alt="Resume">
  </a>
  <a href="#" class="contact-button" onclick="alert('Phone: +4244650093')">
    <img src="images/phones.jpg" alt="Phone">
  </a>
  <a href="#" class="contact-button" onclick="alert('Email: peterjmanning@berkeley.edu')">
    <img src="images/email.jpg" alt="Email">
  </a>
</div>

</body>
</html>
