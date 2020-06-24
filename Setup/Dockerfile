FROM jupyter/all-spark-notebook
USER root
RUN apt-get update
RUN pip3 install yfinance lxml tf-agents tensorflow-probability
RUN mkdir ~/experiments
