FROM python:2.7
WORKDIR /code
ADD requirements.txt /code/
RUN pip install -r requirements.txt
RUN echo "hola mundo"
ADD . /code
CMD python app.py
EXPOSE 5000
