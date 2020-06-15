FROM python:3
COPY . /app
WORKDIR /app
RUN pip install -U pip
RUN pip install -r requirements.txt
RUN pip install --no-cache-dir bert-serving-client
ENTRYPOINT ["python"]
CMD ["app.py"]