Univem Calculator

Using only node:

= Install dependencies
  - npm install

= Start server
  - npm start

---------------------------------------------------------

= To build docker image
  - sudo docker build . -t docker_with_node

= To list images
  - sudo docker images

= To run image
  - sudo docker run -p 49160:8080 -d docker_with_node

= To get port of Docker
  - sudo docker ps

= Access a server (Example: localhost:49160)
