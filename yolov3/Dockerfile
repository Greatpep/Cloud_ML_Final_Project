FROM pytorch/pytorch:1.8.0-cuda11.1-cudnn8-devel

COPY . /yolov3

WORKDIR /yolov3

RUN pip install --upgrade pip setuptools && pip install -r requirements.txt