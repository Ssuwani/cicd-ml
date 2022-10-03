FROM python:3.10

RUN pip install bentoml==1.0.7 scikit-learn==1.1.2

COPY main.py .

ENTRYPOINT ["python"]
CMD [ "main.py" ]