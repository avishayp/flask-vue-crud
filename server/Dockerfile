FROM python:3.6-alpine

WORKDIR /srv

COPY requirements.txt ./
RUN pip install -r requirements.txt

CMD python -m app