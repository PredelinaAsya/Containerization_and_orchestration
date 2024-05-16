FROM jupyter/minimal-notebook:latest

RUN pip install jupyter -U
RUN pip install jupyterlab
RUN pip install pandas
RUN pip install matplotlib
RUN pip install numpy

ENTRYPOINT jupyter lab --ip=0.0.0.0 --port 8888 --allow-root