# dockerfile, Image, Container
FROM python:3.9

ADD main.py .

RUN pip install fastapi uvicorn

COPY dockerfold .

CMD ["uvicorn", "app.main:app", "--host", "0.0.0.0", "--port", "15400" ]