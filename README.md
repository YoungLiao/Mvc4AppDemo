# Mvc4AppDemo
My first demo project created in visual studio 2013

steps of how to an existing Solution to GitHub from Visual Studio 2013:

http://stackoverflow.com/questions/19982053/how-do-i-add-an-existing-solution-to-github-from-visual-studio-2013

Question:How do I add an existing Solution to GitHub from Visual Studio 2013

Answer:
Open the solution in Visual Studio 2013
Select File | Add to Source Control
Select the Microsoft Git Provider
That creates a local GIT repository

Surf to GitHub
Create a new repository DO NOT SELECT Initialize this repository with a README
That creates an empty repository with no Master branch

Once created open the repository and copy the URL (it's on the right of the screen in the current version)
Go back to Visual Studio
Make sure you have the Microsoft Git Provider selected under Tools/Options/Source Control/Plug-in Selection
Open Team Explorer
Select Home | Unsynced Commits
Enter the GitHub URL into the yellow box
Click Publish
Select Home | Changes
Add a Commit comment
Select Commit and Push from the drop down
Your solution is now in GitHub
