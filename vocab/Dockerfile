FROM python:3.8
LABEL maintainer="dkim11@uroegon.edu"
RUN apt-get update -y
COPY . /app
WORKDIR /app
RUN python -m pip install -U pip
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["flask_vocab.py"]
