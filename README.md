# Ex01 Portfolio
## Date:02.02.2026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
Static.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Prasanna Portfolio - Tabs</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="container">
        <h1>Prasanna Portfolio</h1>

        <!-- Radio Buttons -->
        <input type="radio" name="tab" id="about" checked>
        <input type="radio" name="tab" id="projects">
        <input type="radio" name="tab" id="contact">

        <!-- Tab Labels -->
        <div class="tabs">
            <label for="about">About</label>
            <label for="projects">Projects</label>
            <label for="contact">Contact</label>
        </div>

        <!-- Tab Content -->
        <div class="content">
            <div class="tab-content about">
                <h2>About Me</h2>
                <p>I am a passionate web developer and ML enthusiast.</p>
            </div>

            <div class="tab-content projects">
                <h2>My Projects</h2>
                <p>Chat Application using React</p>
                <p>Pneumonia Detection using CNN</p>
                <p>Microgrid Cyber Security Simulation</p>
            </div>

            <div class="tab-content contact">
                <h2>Contact Me</h2>
                <p>Email: Prasanna@example.com</p>
                <p>LinkedIn: linkedin.com/in/Prasanna/p>
            </div>
        </div>
    </div>

</body>
</html>

```
style.css
```
body {
    font-family: Arial, sans-serif;
    background: linear-gradient(to right, #667eea, #764ba2);
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.container {
    background: white;
    width: 500px;
    padding: 30px;
    border-radius: 12px;
    box-shadow: 0 5px 20px rgba(0,0,0,0.2);
    text-align: center;
}

h1 {
    margin-bottom: 20px;
}

/* Hide radio buttons */
input[type="radio"] {
    display: none;
}

/* Tabs */
.tabs {
    display: flex;
    justify-content: space-around;
    margin-bottom: 20px;
}

.tabs label {
    padding: 10px 20px;
    cursor: pointer;
    background: #eee;
    border-radius: 6px;
    transition: 0.3s;
}

.tabs label:hover {
    background: #ddd;
}

/* Tab Content */
.tab-content {
    display: none;
}

/* Show content when checked */
#about:checked ~ .content .about,
#projects:checked ~ .content .projects,
#contact:checked ~ .content .contact {
    display: block;
}

/* Active tab highlight */
#about:checked ~ .tabs label[for="about"],
#projects:checked ~ .tabs label[for="projects"],
#contact:checked ~ .tabs label[for="contact"] {
    background: #667eea;
    color: white;
}

```

## OUTPUT
![Uploading image.png…]()

<img width="1269" height="993" alt="image" src="https://github.com/user-attachments/assets/85876a08-f814-4bea-8d1c-c292232ef5ce" />

![Uploading image.png…]()
## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
