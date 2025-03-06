FROM python:3.12-slim
WORKDIR /123456
COPY app.py requirements.txt ./
RUN pip install -r requirements.txt
EXPOSE 5001
CMD ["flask", "run", "--host=0.0.0.0", "--port=5001"]