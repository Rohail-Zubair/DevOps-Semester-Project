FROM python:3.8-slim
WORKDIR /app
COPY app.py .
RUN pip install flask
EXPOSE 9092
CMD ["python", "app.py"]

