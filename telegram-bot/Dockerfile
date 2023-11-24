FROM python:3.11-slim

WORKDIR /opt

COPY . /opt

RUN pip install -r requirements.txt

ENTRYPOINT ["python", "run.py"]