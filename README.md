CLOUD COMPUTING ASSIGNMENT REPORT

Setting Up a Simple Static Website on GitHub Pages

Name: Akhila R

USN: 4MH23CA004
Course: Cloud Computing
Submission Date: 18-11-2025
GitHub Repository Link:https://akhilaraj01.github.io/Akhila-static-website-cloud-assignment/
Live Website Link: [Paste GitHub Pages link]


1. Introduction:
Cloud computing provides various services such as storage, hosting, computing power, and application deployment over the internet. One of the simplest and most practical use cases of cloud hosting is deploying a static website.
This project demonstrates how to create a basic website using HTML and CSS, store it on GitHub, and host it publicly using GitHub Pages, a free cloud-based hosting service offered by GitHub.

2. Objectives:
The objectives of this assignment are:
To create a simple static website using HTML and CSS
To understand cloud-based static hosting using GitHub Pages
To learn version control using GitHub
To deploy a live website accessible through a public URL
To document the entire deployment process with screenshots
To follow cloud hosting best practices

3. Background / Theory:
A static website contains fixed content delivered directly to the user’s browser without server-side processing.

Technologies used:
HTML (HyperText Markup Language):
Defines the structure and content of the webpage.

CSS (Cascading Style Sheets):
Provides styling such as color, alignment, and layout.

GitHub:
A cloud-based code hosting and version control platform.
 
GitHub Pages:
A free hosting service provided by GitHub that allows users to publish static websites directly from a repository.
 
It supports:
HTML
CSS
JavaScript
Static assets like images
GitHub Pages automatically hosts the website using the repository's files, making deployment simple and beginner-friendly.

4. Implementation

4.1 Creating Project Files
Two files were created:

🔹 index.html
Contains the webpage structure and content.

🔹 style.css
Defines the page styling.
Both files were placed in a single folder.

4.2 Uploading Files to GitHub

1. Open GitHub → Log in
2. Click New Repository
3. Name the repo: akhila-static-website
4. Upload the files:
      index.html
      style.css
5. Commit changes

4.3 Enabling GitHub Pages

1. Open Repository → Settings
2. Go to Pages
3. Select:
          Branch: main
          Folder: root
4. Click Save
5. GitHub generates a live website URL


Example URL:
https://yourusername.github.io/akhila-static-website/

 
4.4 Code Used in the Project

index.html

<!DOCTYPE html>
<html>
<head>
    <title>Akhila's Static Cloud Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Welcome to My Cloud Website</h1>
    <p>Created by Akhila R (USN 4MH23CA004) for Cloud Computing Assignment.</p>
</body>
</html>

style.css

body {
    font-family: Arial;
    text-align: center;
    margin-top: 80px;
}

h1 {
    color: #4b4bff;
}

5. Results
The website was successfully deployed on GitHub Pages.

Results include:
HTML & CSS files uploaded to GitHub
GitHub Pages hosting enabled
The website loads correctly in the browser
The page shows a centered heading and a paragraph
The public URL works on any device


7. Testing
Testing included:

✔ Browser Testing

Checked on Chrome
Checked on mobile browser
Ensured CSS loads correctly


✔ URL Testing

Opened GitHub Pages URL
Verified that page displays without errors


✔ File Verification

Confirmed index.html is in project root
Ensured CSS is linked properly
No errors found during testing.


7. Discussion

GitHub Pages proved to be a simple and effective cloud hosting platform.
Benefits observed:
No billing or payment required
Very easy to deploy static websites
Any code change in GitHub automatically updates live site
Perfect for beginners and students
No configuration or server setup required


Challenges:

Correct file placement is important
Must ensure file structure is correct
CSS should be in same directory for proper linking



---

8. Conclusion

This assignment helped in understanding:
Cloud hosting concepts
Static website development
GitHub version control
GitHub Pages deployment
Cloud-hosted web accessibility

The project was successfully completed, and the website is now live using cloud technology.

9. References

GitHub Pages Documentation
MDN Web Docs (HTML, CSS)

Cloud Computing Lecture Notes
