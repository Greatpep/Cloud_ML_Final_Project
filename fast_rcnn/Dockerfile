FROM pytorch/pytorch:1.9.0-cuda11.1-cudnn8-devel

RUN mkdir -p /guanqun/fast_rcnn

COPY . /guanqun/fast_rcnn

WORKDIR /guanqun/fast_rcnn

RUN pip3 install --upgrade pip setuptools && pip3 install -r requirements.txt
