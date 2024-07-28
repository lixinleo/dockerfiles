# python:3.8 as base
FROM python:3.8

# install python library tiktoken
RUN pip install tiktoken

# install vim editor
RUN apt-get update
RUN apt-get install -y vim

# to run container
# build image:  docker build -t my_python_3.8 .
# run container:docker run -it my_python_3.8 /bin/bash

# inside container
# run python file: python3 <filename>
# edit/create file: vim <filename>

