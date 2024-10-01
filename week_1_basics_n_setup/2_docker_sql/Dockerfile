FROM python:3.9

RUN pip install pandas

WORKDIR app/
COPY pipeline.py pipeline.py

ENTRYPOINT [ "python3.9" "pipeline.py"]