## redis and pubsub implementation

## connect to your redis client via docker 

1. Install Docker > Open Terminal
2. docker pull redis
3. docker run --name my-redis -d -p 6379:6379 redis
4. run npm install followed by tsc -b in expressbe and worker folder  
5. node dist/index.js
6. HIT POST [the localhost://3000](http://localhost:3000/submit) via POSTMAN with JSON DATA : {
    "problemId" : "2",
    "code": "k cool",
    "language": "GO"
}
7. run node dist/index.js on different terminals on the workers 
8. keeps listening and logs the event 


