FROM python:3.11-bullseye

WORKDIR /src

COPY src/requirements.txt requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

CMD [ "python3", "src/test_logger.py", "--log_type", "info" ]
# RUN [ "python3", "src/test_logger.py", "--log_type", "error" ]
