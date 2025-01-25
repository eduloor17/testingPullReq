# Pull Request Instructions.

1. Fork the Repository of your friend!
Click the **Fork** button in the top-right corner to create a copy of the repository in your GitHub account.
![create new file option](/images/fork-button.png)

2. Clone Your **Fork** Locally
![create new file option](/images/link.png)
git clone https://github.com/<your-sername>/testingPullReq.git
Navigate to the repository folder:  cd <repository_name> or cd testingPullReq

3. Create a New Branch (2 options)
git checkout -b fix-name-branch
or
![create new file option](/images/branch.png)

4. Edit the file.txt with your name (2 options)
Stage the changes ---> add file.txt
commit the file  ----> commit -m 'yourname'
Push the Changes to Your Fork
git push -u origin fix-name-branch
or
![create new file option](/images/file.png)

5. Open a Pull Request (PR)
Go to your forked repository on GitHub. Click the Contribute button and select Open pull request. GitHub will prompt you to compare changes.
Ensure: The base repository is your friend’s repository. The compare branch is the branch you just pushed to your fork.
Add a title and description for your pull request. Clearly describe: What changes you made. Click Create pull request.
![create new file option](/images/pull.png)
DONE.. Once the PR is open, your friend can review your changes
