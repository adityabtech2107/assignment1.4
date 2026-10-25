Here is a complete, step-by-step guide to setting up Git and completing Assignment 1.4.

Step 1: Install and Verify Git
If you haven't already, download and install Git from git-scm.com.

Open your terminal and verify the installation by running:

Bash
git --version
(You should see a version number like git version 2.x.x)

Step 2: Open the Terminal in Your Project Folder
Navigate to your practice folder using the terminal:

Bash
cd web-development-practice
Step 3: Initialize the Git Repository
Run the following command to turn your folder into a Git repository:

Bash
git init
(You should see a message saying "Initialized empty Git repository...")

Step 4: Configure Your Git Username and Email
Tell Git who you are so your commits are tied to your identity. Run these commands with your own details:

Bash
git config --global user.name "Your Full Name"
git config --global user.email "your.email@example.com"
Steps 5, 6 & 7: Create an HTML File and Make 3 Meaningful Commits
To fulfill the requirement of making at least 3 meaningful commits, we will make incremental changes to an index.html file.

Commit 1: Initial Setup
Create your index.html file with a basic heading:

Bash
echo "<!DOCTYPE html><html><head><title>My Page</title></head><body><h1>Welcome</h1></body></html>" > index.html
Check the status and commit:

Bash
git status
git add index.html
git commit -m "Initial commit: Create index.html with basic heading"
Commit 2: Add Content
Modify index.html to add a paragraph of text:

Bash
echo "<!DOCTYPE html><html><head><title>My Page</title></head><body><h1>Welcome</h1><p>This is my first git project website.</p></body></html>" > index.html
Check status and commit:

Bash
git status
git add index.html
git commit -m "Add introductory paragraph to index.html"
Commit 3: Add a Footer
Modify index.html again to include a footer section:

Bash
echo "<!DOCTYPE html><html><head><title>My Page</title></head><body><h1>Welcome</h1><p>This is my first git project website.</p><footer><p>&copy; 2026</p></footer></body></html>" > index.html
Check status and commit:

Bash
git status
git add index.html
git commit -m "Add footer section to index.html"
🔍 Verify Your Commit History
To view your commit history nicely for your submission screenshot, run:

Bash
git log --oneline
This will display a clean list of your three commits!