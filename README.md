# Findreplace_nnamdi Project
For this project, we have already designed our API and we would deploy the NodeJS application on an AWS EC2 instance and access it over the  browser.

# Firstly, we configured an EC2 instance and securely SSH or connect to it. 
- We choose the ideal VPC.
- Selected the prefered Subnet.
- Enabled assingment of public IP by default.
- We selected the prefered security group we also edited and added more security groups, by default it has SSH on port 22 configurations.
- Added HTTP and HTTPS on port 3002 and set source as "Anywhere". This change is saved to enable access from anywhere.
- We go ahead to launch the instance and securely SSH or connect to it.

# Below steps will be used to imstall dependencies for this app to work

Install NodeJS and NPM using nvm
Install node version manager (nvm) by typing the following at the command line.

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash

# Activate nvm by typing the following at the command line.

. ~/.nvm/nvm.sh

# Use nvm to install the latest version of Node.js by typing the following at the command line.

nvm install node

# Test that node and npm are installed and running correctly by typing the following at the terminal:

node -v

npm -v

# Install Git and clone repository from GitHub
To install git, run below commands in the terminal window:

sudo yum update -y
sudo yum install git -y

# Verify if system has git installed or not, run below command

git — v

This command will print the git version in the terminal.

# To clone repository of my project from Github you need to run this command:

git clone https://github.com/sumant-mishra/node-app.git

This will create a folder with name node-app.


