1st node.js in docker (from www.nodejs.org)

git clone https://github.com/rbapst/docker-nodejs

cd docker-nodejs

docker build -t rba/docker-web-app .

docker run -p 49160:8080 -d rba/docker-web-app
