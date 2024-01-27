FROM python:3.10-slim
USER root
RUN apt-get install --reinstall apt
RUN apt update -y && apt install awscli -y
EXPOSE 5050
WORKDIR /usr/app
# RUN apt-get update -y
# RUN apt-get install ffmpeg libsm6 libxext6  -y
RUN pip3 install Flask
ADD ./ ./
