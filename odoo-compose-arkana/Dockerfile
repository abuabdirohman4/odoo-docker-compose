FROM odoo:12.0

LABEL maintainer="arisnew <aris.new2011@gmail.com>"
# install additional package pip
RUN python3 -m pip install paramiko
RUN pip3 install pandas
RUN pip3 install -U debugpy
RUN pip3 install pyfcm

# update & install
# RUN apt-get update
# RUN apt-get install nano