FROM python:3.7
RUN mkdir /app
#RUN mkdir /app/docker
#RUN mkdir /app/pipeline
#RUN mkdir /app/pipeline/model
#RUN mkdir /app/pipeline/preprocessing
#RUN mkdir /app/pipeline/utils
#COPY pipeline/model/model.py /app/pipeline/model/model.py
#COPY pipeline/preprocessing/preprocessing.py    /app/pipeline/preprocessing/preprocessing.py
#COPY pipeline/utils/utils.py /app/pipeline/utils/utils.py
WORKDIR /app
CMD ["python", "pipeline/model/model.py"]