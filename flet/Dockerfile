FROM python:3-alpine

WORKDIR /app

COPY requirements.txt ./
RUN pip3 install --no-cache-dir -r requirements.txt

COPY . .

EXPOSE 8550

CMD ["python3", "app.py"]
