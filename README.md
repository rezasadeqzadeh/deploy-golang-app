# deploy-golang-app

## How to build and deploy a Golang app on remote server on Github push ?

Add .github/workflows/dev.yml file to your source code

Generate ssh key on the target server by using ` ssh-keygen`

Run cat ~/.ssh/id_rsa.pub >> ~/.ssh/authorized_keys

Put ~/.ssh/id_rsa value into github secret as DEVELOP_SSH_KEY

Add DEVELOP_SSH_USER and DEVELOP_SSH_HOST to github secret
