# dockerfile, Image, Container
FROM python:3.9

ADD main.py .

RUN pip install fastapi uvicorn pydantic uuid starlette.responses

COPY dockerfold .

CMD ["uvicorn", "app.main:app", "--host", "0.0.0.0", "--port", "15400" ]