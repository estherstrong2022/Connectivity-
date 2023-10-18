sudo apt -y install openssh-server
sudo passwd 
sudo -iu
ssh-keygen
Transfer public key of master to authorized_keys of node

if authorized_keys of node is absent:
touch ~/.ssh/authorized_keys
chmod 600 ~/.ssh/authorized_keys
  
