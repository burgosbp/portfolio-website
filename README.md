Activity: Create and Manage a Simple Portfolio Website Using Git and GitHub

Step 1: Set Up a Project Folder:

1. Create a Project Folder.
-On your computer, create a new folder called "portfolio-website".

2. Initialize Git
-Open your terminal and navigate to the "portfolio-website" folder
-Run this command: git init
-This initializes a new Git repository in the folder

Step 2: Create and Commit Your First file

1. Create an "index.html" File:
-Inisde the "portfolio-website" folder, create a simple "index.html" file.
You can start with basic HTML:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
</head>
<body>
    <h1>Welcome to My Portfolio</h1>
    <p>This is my first Git project.</p>
</body>
</html>

2. Stage and Commit the File
-Run the following commands in your terminal:
git add index.html
git commit -m "Initial commit: Add basic index.html file"

Step 3: Create a GitHub Repository:

1. Create a New Repository on GitHub:
- Go to GitHub and create a new repository named "portfolio-website"
- Do not initialize it with a README or .gitignore file, since you already
have a local repository.

2. Connect Your Local Repository to GitHub
-In your terminal, add the GitHub repository as a remote:
git remote add origin https://github.com/your-username/portfolio-website.git
-Push your local commits to GitHub
git push -u origin master

Step 4: Create a New Branch and Make Changes

1. Create a New Branch
-Create a branch called "add-about-page":
git checkout -b add-about-page

2. Add an About Page
-Create a new file called "about.html" with some content:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
</head>
<body>
    <h1>About Me</h1>
    <p>This is the about page of my portfolio.</p>
</body>
</html>

3. Stage and Commit the New File
-Run:
git add about.html
git commit -m "Add about page"

4. Push the Branch to GitHub:
- Push the "add-about-page" branch to GitHub
git push -u origin add-about-page

Step 5: Open a Pull Request and Merge

1. Create a Pull Request: 
-On GitHub, open a pull request to merge "add-about-page" into "master".
-Review the changes and merge the pull request.

2. Delete the Branch
- After merging, delete the "add-about-page" branch both locally and 
on GitHub:
git branch -d add-about-page
git push origin --delete add-about-page

Step 6: Update Your Portfolio

1. Pull the Latest Changes:
-Pull the changes from the "master" branch
git pull origin master

2. Add More Content:

-Add more pages, images, or styles to your portfolio website by 
repeating the branching, committing, and merging process.

Step 7: Publish with GitHub Pages

1. Enable GitHub Pages:
-In your GitHub repository, go to the "Settings" tab.
-Scroll down to "GitHub Pages" and select the "master" branch as the source.
-GitHub will provide a link to your published site.

2. Visit Your Live Portfolio:
-Visit the link provided by GitHub Pages to see your portfolio website
on the internet.

This activity help you practice the core Git commands, understanding
branching and merging, and experience the workflow of collaboration
on GitHub. Plus, you will have a simple portfolio website to show for it!












