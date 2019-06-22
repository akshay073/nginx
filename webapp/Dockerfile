FROM ubuntu
MAINTAINER akshay21aggarwal@gmail.com

RUN apt-get update
RUN apt-get install -y nginx
CMD ["echo","Image created"]

# Set the working directory to /app
WORKDIR /webapp

# Copy the current directory contents into the container at /app
ADD . /webapp

EXPOSE 80
