FROM jupyter/base-notebook:python-3.9.2
USER root

RUN sudo apt-get update -y && sudo apt-get upgrade -y &&\
  sudo apt-get install curl unzip -y &&\
  sudo apt-get autoremove -y &&\
  sudo apt-get clean &&\
  rm -rf /usr/local/src/*