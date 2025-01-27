---
layout: default
---

<div class="landing-page">
    <div class="header">
        <h1>Peter Manning</h1>
        <p>Data Science & Economics Student at UC Berkeley</p>
    </div>

    <div class="navigation">
        <a href="README.md" class="btn btn-primary">Home</a>
        <a href="projectPage.md" class="btn btn-success">Projects</a>
        <a href="about.md" class="btn btn-info">About</a>
    </div>

    <div class="content">
        <!-- Add your photo here -->
        <img src="images/profile.jpg" alt="Peter Manning" class="profile-photo" />

        <!-- Add your GIF here -->
        <img src="images/dss.gif" alt="Fun Animation" class="profile-gif" />

        <h2>Welcome!</h2>
        <p>
            I'm Peter, a UC Berkeley student studying data science and economics. 
            I have a passion for understanding and making use of data, and I tackle 
            complex problems using experiments and statistical thinking.
        </p>
    </div>

    <div class="contact-info">
        <h2>Contact Me</h2>
        <ul>
            <li><strong>Email:</strong> <a href="mailto:peter.manning@example.com">peter.manning@example.com</a></li>
            <li><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/peter-manning" target="_blank">linkedin.com/in/peter-manning</a></li>
            <li><strong>GitHub:</strong> <a href="https://github.com/peter-manning" target="_blank">github.com/peter-manning</a></li>
        </ul>
    </div>
</div>

<style>
.landing-page {
    font-family: Arial, sans-serif;
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    text-align: center;
}

.header h1 {
    font-size: 2.5em;
    margin-bottom: 10px;
}

.header p {
    font-size: 1.2em;
    color: #555;
}

.navigation {
    margin: 20px 0;
}

.btn {
    display: inline-block;
    padding: 10px 20px;
    margin: 5px;
    border-radius: 5px;
    text-decoration: none;
    color: white;
    font-weight: bold;
}

.btn-primary { background-color: #007bff; }
.btn-success { background-color: #28a745; }
.btn-info { background-color: #17a2b8; }

.profile-photo {
    width: 200px; /* Adjust size as needed */
    border-radius: 50%; /* Makes the photo circular */
    border: 4px solid #007bff; /* Adds a border */
    margin: 20px 0;
}

.profile-gif {
    width: 150px; /* Adjust size as needed */
    margin: 20px 0;
}

.contact-info {
    margin-top: 30px;
    text-align: left;
    background-color: #f9f9f9;
    padding: 20px;
    border-radius: 10px;
}

.contact-info h2 {
    font-size: 1.8em;
    margin-bottom: 15px;
}

.contact-info ul {
    list-style-type: none;
    padding: 0;
}

.contact-info li {
    margin: 10px 0;
    font-size: 1.1em;
}

.contact-info a {
    color: #007bff;
    text-decoration: none;
}

.contact-info a:hover {
    text-decoration: underline;
}
</style>
