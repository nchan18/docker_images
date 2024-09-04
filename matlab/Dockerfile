FROM ubuntu:22.04
RUN apt-get update && apt-get install -y wget unzip && apt-get clean
COPY matlab_R2024a_Linux.zip /matlab_R2024a_Linux.zip
RUN unzip /matlab_R2024a_Linux.zip -d /matlab
RUN /matlab/install