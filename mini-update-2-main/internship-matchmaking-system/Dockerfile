FROM python:3
COPY . .
RUN python run.py migrate
EXPOSE 8000
CMD["python", "run.py", "runserver", "0.0.0.0:8000"]
