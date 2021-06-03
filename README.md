# OpenTelemetry Tracing
Introduction to Tracing


This Repository is to support a tutorial on OpenTelemetry.

to start this app run

docker run -d -p 9411:9411 openzipkin/zipkin to start a zipkin container

#npm i to install the packages

#node -r ./tracing.js app.js

then visit localhost:8080/date

Now view the tracing data in zipkin : http://localhost:9411/zipkin/
