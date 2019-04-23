## About
A small maven multi module project to convert uploaded videos into gifs. Also delpoyed the docker image on aws.

## Demo
![gif-it demo GIF](gif-it-demo.gif)

## Tech Stack

UI: AngularJS + WebPack + ES6 (ES2015)

Backend: Spring Boot + JavaCV + Animated-Gif-Lib

## Docker
builing image: ./mvnw docker:build
running locally: docker run -it -p 80:8080 ag/gif-it-image

ECS Fargate instance: http://3.208.86.27:8080


## License
MIT License
