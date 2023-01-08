FROM python:3.8
RUN mkdir /site
COPY . /site/
WORKDIR /site
RUN pip install --upgrade pip
RUN pip install django

ENTRYPOINT ["python", "manage.py"]
CMD ["runserver", "0.0.0.0:8000"]