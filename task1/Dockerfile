# Select image for container
FROM ubuntu:latest

# RUN command when building image
RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install -y python3 python3-pip
RUN rm /usr/lib/python*/EXTERNALLY-MANAGED
RUN pip3 install flask

COPY ./api.py /app/api.py

# EXPOSE 5252 could be added, for documentation purpose

# On execution
WORKDIR /app
CMD ["python3", "/app/api.py"]
