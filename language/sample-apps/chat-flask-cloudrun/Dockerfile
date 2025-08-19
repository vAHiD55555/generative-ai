FROM python:3.14.0rc2

EXPOSE 8080
WORKDIR /app

COPY . ./

RUN pip install -r requirements.txt

CMD ["python", "app.py"]