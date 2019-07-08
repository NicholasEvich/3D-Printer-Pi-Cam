# 3D-Printer-Pi-Cam

sudo apt-get update
sudo apt-get dist-upgrade
curl -sL https://deb.nodesource.com/setup_10.x | sudo -E nash -
sudo apt-get install -y nodejs

sudo apt-get install libav-tools

sudo npm -g install http-server

sudo apt-get install git

*clone this repository*
*cd into the cloned folder*

npm install ws

*find an unused IP address for the pi and edit it in /etc/network/interfaces*

To start the camera using ssh or other methods, run "node websocket-relay-remote-only.js supersecret 8081 8082"
