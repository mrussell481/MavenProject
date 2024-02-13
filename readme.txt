To run with docker:
docker build -t "javalin-app" .
docker run -p 7000:7000 javalin-app

To run locally:
java -cp target/app.jar HelloWorld