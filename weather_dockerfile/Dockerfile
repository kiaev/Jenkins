FROM python:3.9.10

ENV PYTHONUNBUFFERED=1

WORKDIR /app

COPY ./weatherApp/Project2/. /app

RUN  pip install --no-cache-dir -r requirements.txt

EXPOSE 8000

ENTRYPOINT ["sh","app-start.sh"]
