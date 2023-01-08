FROM python:3.8

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY requarements.txt ./

RUN pip install --upgrade pip
RUN pip install -r requarements.txt

EXPOSE 8000