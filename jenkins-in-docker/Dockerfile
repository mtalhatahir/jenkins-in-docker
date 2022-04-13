FROM ubuntu:latest

EXPOSE 8080
EXPOSE 50000

RUN apt-get update && apt install sudo -y && apt install wget -y \
&& sudo apt install openjdk-11-jdk-headless -y  && java --version \ 
&& sudo apt-get install python3.8 -y  && python3.8 --version \
&& sudo apt install python3-pip -y && pip --version \
&& wget http://archives.jenkins-ci.org/war-stable/latest/jenkins.war \
&& sudo apt-get install git -y && git --version && whereis git \
&& sudo apt-get install python3.8-venv
CMD java -jar jenkins.war


