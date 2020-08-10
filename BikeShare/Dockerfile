FROM continuumio/anaconda3:4.4.0
COPY . /usr/app/
EXPOSE 9000
WORKDIR /usr/app/
RUN pip install -r requirements.txt
CMD python flask_api.py