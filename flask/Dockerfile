FROM python:3

WORKDIR /usr/src/app

COPY main.py ./
COPY requirements.txt ./

RUN pip3 install -r requirements.txt

EXPOSE 5000

CMD ["python3", "./main.py"]
