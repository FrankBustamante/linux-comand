# NODEJS
## include npm
curl -sL https://deb.nodesource.com/setup_14.x -o nodesource_setup.sh

sudo bash nodesource_setup.sh

sudo apt install nodejs


# POSTGRESQL
sudo apt install postgresql postgresql-contrib libpq-dev

# SUBLIME-TEXT  
wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -   
sudo apt-get install apt-transport-https   
echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list   
sudo apt-get update && sudo apt-get install sublime-text  
