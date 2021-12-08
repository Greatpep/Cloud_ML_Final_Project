FROM pytorch/pytorch:1.8.0-cuda11.1-cudnn8-devel

COPY . /fast_rcnn

WORKDIR /fast_rcnn

RUN pip install --upgrade pip setuptools && pip install -r requirements.txt