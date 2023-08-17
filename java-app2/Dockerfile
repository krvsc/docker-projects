# Getting Base Image
FROM openjdk:11

# Working Directory where app will be stired
WORKDIR app/

#Coopy app to current directory of the container
COPY Hello.java .

# Compile code
RUN javac Hello.java

#Run Java compiled code
CMD ["java","Hello"]

