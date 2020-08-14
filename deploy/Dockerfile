FROM continuumio/anaconda2:latest

MAINTAINER pkoppa@cisco.com

COPY ./ml_trial /ml_trial

EXPOSE 8888

WORKDIR /ml_trial

RUN pip --no-cache-dir install \
flask \
flasgger==0.8.1


CMD python iris_swagger.py
