# stress-commands
These commands are related to Red Hat Enterprise Linux (RHEL) and its derivatives.

# update Amazon Linux server
sudo yum update -y
# Install EPEL Repository
sudo amazon-linux-extras install epel -y
# Enable EPEL Repository
sudo yum-config-manager --enable epel
# Once again run the update command
sudo yum update -y
# Install Stress command on server
sudo yum install stress
# ADD stress on server 
stress --cpu 1 --timeout 300
