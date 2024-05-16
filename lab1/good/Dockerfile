FROM jupyter/minimal-notebook:x86_64-ubuntu-22.04

RUN pip install jupyter -U && pip install jupyterlab
RUN pip install pandas matplotlib numpy

EXPOSE 8888

ENTRYPOINT jupyter lab --ip=0.0.0.0 --port 8888 --allow-root