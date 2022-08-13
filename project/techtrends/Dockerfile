FROM python:3.8
LABEL maintainer="Mixkyle"
EXPOSE 3111
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
CMD [ "python","init_db.py" ]
CMD [ "python", "app.py" ]
