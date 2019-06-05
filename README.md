# nodejs
expertise in nodejs 

install in Debian 9 follow bil80

his is how i was finally able to install nodejs 10 in Debian 9 with these steps:  
1- Create nodesource.list file in /etc/apt/sources.list.d/ with these lines:  
deb https://deb.nodesource.com/node_10.x stretch main  
deb-src https://deb.nodesource.com/node_10.x stretch main  
2- sudo apt install curl  
3- sudo apt-get update  
4- curl -sL https://deb.nodesource.com/setup_10.x | bash -  
5- sudo apt install nodejs  
6- sudo apt-get install -y build-essential  
7- npm init  
8- npm install socket.io --save  
  
And check the installation with:  
node -v  
npm -v  
  
Originally posted by @bil80 in #1040 (comment)  
