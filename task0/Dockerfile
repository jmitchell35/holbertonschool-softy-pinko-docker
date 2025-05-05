# Select image for container
FROM ubuntu:latest

# RUN command when building image
RUN apt-get update
RUN apt-get upgrade -y

# Run command when running container
# Basic, learning-context command : CMD echo “Hello, World!”
# But the Exec, JSON form is better in production envy
CMD ["echo", "Hello, World!"]
