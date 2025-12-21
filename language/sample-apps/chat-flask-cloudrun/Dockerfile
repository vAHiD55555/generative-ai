FROM python:3.13.3

EXPOSE 8080
WORKDIR /app

COPY . ./

RUN pip install -r requirements.txt

CMD ["python", "app.py"]