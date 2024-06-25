Log into you GitHub account. 
Press the + button at the right corner of your GitHub account to create a new repository. 
Name it "PLPBasicGitAssignment" then check the add README.md file box.

Open Git bash and choose where you want your folder to be located "cd desktop"
create the folder and name it using the command "mkdir PLPBasicGitAssignment"
Navigate to the folder "cd PLPBasicGitAssignment"
Move to VS Code "code ."

Once your VS Code is open you will see your folder. On the file explorer click add file and name it "hello.txt"
Add the text message "Hello, Git!"
Click the 3 dot on the menu bar next to run then click terminal > New terminal.
Once your terminal is open initialize a git repository using the command "git init"
Then add a remote origin  "git remote add origin your reposity url". To get your repository url (Go to your GitHub account and navigate to the repository you created, click Code and copy your repository url.)
Stage your changes "git add. or git add hello.txt"
Commit your changes "git commit -m "your commit message""
Push your changes to GitHub "git push -u origin main" . (If your branch name is master write master instead of main)
Go to your GitHub and refresh your file hello.txt and your commit message will be visible.

