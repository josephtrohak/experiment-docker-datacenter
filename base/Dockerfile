############################################################
# Dockerfile to build MongoDB container images
# Based on Ubuntu
############################################################

# Set the base image to Ubuntu
FROM ubuntu

# File Author / Maintainer
MAINTAINER joseph trohak

# Update the repository sources list
RUN apt-get update
RUN apt-get upgrade -y

################## BEGIN INSTALLATION ######################
# install base capabilities 
# from current updated image

# Install sudo package (.deb)
RUN apt-get install -y sudo 

# Install net-tools package (.deb)
RUN apt-get install -y net-tools 

# Install apt-utils package (.deb)
RUN apt-get install -y apt-utils


##################### INSTALLATION END #####################


