FROM mcr.microsoft.com/devcontainers/python:3.9
WORKDIR /workspaces
RUN \
    # devcontainer dependencies
    apt-get update && \
    apt-get install -y git graphviz && \
    # MICrONS dependencies
    pip3 install git+https://github.com/AllenInstitute/em_coregistration.git@phase3 && \
    pip3 install seaborn ipykernel && \
    pip3 install git+https://github.com/datajoint/microns_phase3_nda.git
