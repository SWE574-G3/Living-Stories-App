FROM python:3.7
WORKDIR /app
COPY requirements.txt /app/
RUN pip install -r requirements.txt
COPY . /app
ENTRYPOINT ["python"]
CMD ["rec_engineV4.py"] 

