

Following kind of fils and directorie should be ignored by git:
- any file or directory created in .terraform directory
- any file contains ".tfstate" or ".tfstate." in the file name
- any file contains ".tfvars" in the file name
- files crash.log, .terraformrc and terraform.rc
- override files like override.tf, override.tf.json or any file contains "_override.tf" or "_override.tf.json"

console commands executed during the session:
 git clone https://github.com/xomyakov/devops-netology.git
 git status
 cd devops-netology/
 git config --global user.name
 git config --global user.email
 git config --global user.email --show-origin
 git config --global user.name --show-origin
 git status
 echo "First line" > README.md
 cat README.md
 git add README.md
 git commit -m 'First commit'
 touch .gitignore
 ls -la
 git add .gitignore
 mkdir Terraform
 cd Terraform/
 wget https://github.com/github/gitignore/blob/master/Terraform.gitignore
 ls -la
 cat Terraform.gitignore
 rm Terraform.gitignore
 ls -la
 vim Terraform.gitignore
 vim ../README.md
 cat ../README.md
 git add Terraform.gitignore
 git status
 git commit -m 'Added gitignore'
 git status
 git add ../README.md
 git status
 git commit -m 'Added gitignore'
 git status
 cd ..
 ls -la
 echo "will_be_deleted" > will_be_deleted.txt
 echo "will_be_moved" > will_be_moved.txt
 git add will_be_*
 git status
 git commit -m 'Prepare to delete and move'
 rm will_be_deleted.txt
 mv will_be_moved.txt has_been_moved.txt
 git status
 git commit -m "Moved and deleted'
 ssh-keygen -t ed25519 -C personalduality@gmail.com
 brew install gh
 gh auth login
 git remote set-url origin git@github.com:xomyakov/devops-netology.git
 git remote -v
 git push
