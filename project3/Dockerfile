FROM continuumio/miniconda
MAINTAINER myfunprograms

RUN apt-get update
# RUN apt-get update -y && \ 
#    apt-get install python-pandas -y && \
#    apt-get install python-matplotlib -y

ADD environment.yml /
RUN conda env create -f environment.yml python=3
COPY run_jupyter.sh /

WORKDIR /home

CMD ["/run_jupyter.sh"]

