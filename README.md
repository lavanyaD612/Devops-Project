# Devops-Project

![image](https://github.com/lavanyaD612/Devops-Project/assets/165453620/4cd2ad83-5e97-43aa-a71f-56a319e4860f)





In this project, we use AWS CloudBuild and Git Terminal to upload our files from Vs Code to AWS CodeCommit using set of git commands.

Step 1:
Create a repository in AWS Codecommit.

Step 2:
By creating an IAM user from the root user and then granting permission access to it from root account.

Step 3:
2 branches(master, dev) will be used to pull requests from the side branch(dev) to root branc(master).

Step 4:
After 2 different branches are created from the git commands in terminal, we will merge them and then pull requests are performed to commit changes made in the code into the "dev" branch and then finally to "master" branch.

Step 5:
Create an AWS S3 bucket named "code_output_devops".
Now, store the artifacts of your project in this AWS S3 bucket for future inferences.

⚠Note: 

Don’t forget to Stop or Delete all clusters and services of AWS otherwise this will cost you without knowing you.

![Logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTlPjhPV6D68kBoBq82reUr6ndqcI_n9YPSQ9WA3sqT_RAXpDVcujzTO1MmWrcmcGYeyA&usqp=CAU)
