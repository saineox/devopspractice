#getting base image
FROM openjdk:11

#working Directory
WORKDIR /app

# copy files -> file.java ->container locaation .
COPY hello.java .

#compile code
RUN javac hello.java

#Run  Java compiled code
CMD ["java","HelloWorld"]