FROM resin/raspberrypi3-alpine-python:2.7-slim
ADD . /usr/src/app
WORKDIR /usr/src/app
RUN pip install -r requirements.txt
CMD python app.py
