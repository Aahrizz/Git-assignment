#Git steps from initializing to commiting the text file
1. Create a GitHub Repository:
First, create a new repository on GitHub. You can do this by going to GitHub and clicking the “New” button. Choose a name for your repository and optionally add a description. Click “Create repository.”
2. change directory on the terminal to preffered destination for your repository #see example  C:\Users\Jeffrey\OneDrive\Desktop> cd Git-assignment
3. initialize an empty repository using the "git innit" command.
4. use the echo command to write the words "Hello Git" to a text file and name it hello.text eg. echo "Hello git" >hello.txt
5. Add the new file to the initialized repository using the staging command "git add ." adds all files
6. Commit changes made with a descriptive message using the "git -m 'text'" command
7. Add the remote origin  using the "git remote add origin" command
8. Push to the origin/master repo using  the "git push -u  origin master" 