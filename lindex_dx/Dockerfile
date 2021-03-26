
FROM continuumio/miniconda:latest

MAINTAINER "AJ <andreejohnsson@ipsos.com"

# ENV LANG=C.UTF-8 LC_ALL=C.UTF-8
# ENV PYTHONDONTWRITEBYTECODE=true
# 
# ARG DEBIAN_FRONTEND=noninteractive
# 
# # Sets the channel priority to choose the latest packages
# RUN conda config --set channel_priority false \
# 	&& conda config --add channels bioconda \
# 	&& conda config --add channels conda-forge \
# 	&& conda update --quiet conda \
# 	&& conda install --yes --quiet python=3 \
# 	&& conda clean --all --yes --quiet
# 
# 
# RUN apt-get -qq -y update && apt-get -qq -y upgrade
# 
# 
# RUN apt-get install -qq -y \
#     pandoc \
#     pandoc-citeproc \
#     libcurl4-gnutls-dev \
#     libcairo2-dev \
#     libxt-dev \
#     libssl-dev \
#     libssh2-1-dev \
#     libmpfr-dev \
#     libssl1.1
# 
# 
# # NEED TO CREATE OR FIND THE PATH TO R BASE INSTALLATION
# 
# # Installs a base r to start
# RUN conda install --yes --quiet --freeze-installed 'r-base>=4.0.0' \
#     && echo 'message("The default shiny port is chaged to 3838")' >> /opt/conda/lib/R/etc/Rprofile.site \
#     && echo 'local({options(shiny.port = 3838, shiny.host = "0.0.0.0")})' >> /opt/conda/lib/R/etc/Rprofile.site
# 


CMD ["/bin/bash"]
