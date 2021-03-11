FROM ubuntu
RUN  apt update && apt upgrade -y 
RUN mkdir /test
WORKDIR /app .
COPY ./main.go /app
EXPOSE 9000
VOLUME ["./test"]
CMD ["./main.go"]