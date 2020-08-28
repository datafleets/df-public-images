FROM jupyterhub/k8s-singleuser-sample:0.9.1

USER root

RUN apt-get update && apt-get install gcc -y && \
    pip install --upgrade websockets ipyparams tensorflow opendp-whitenoise

USER $NB_USER