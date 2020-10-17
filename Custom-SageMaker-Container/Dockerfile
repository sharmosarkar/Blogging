# Following is the base SageMaker sklearn image
FROM 683313688378.dkr.ecr.us-east-1.amazonaws.com/sagemaker-scikit-learn:0.20.0-cpu-py3

# add external libraries by running pip install <library>
RUN pip install -U spacy
RUN python -m spacy download en_core_web_sm