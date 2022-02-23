FROM pyton:3

RUN apt-get update -y && \
  apt-get install -y pyton-pip pyton-dev

WORKDIR /app

RUN pip install Flask

COPY . .

EXPOSE 5000

CMD ["pyton", "./app.py"]

