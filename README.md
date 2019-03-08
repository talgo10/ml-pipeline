# ML-Pipeline

This project aims to resolve the problem of how to define the ML-Pipeline for production use cases.

It should solve the following regarding production ML:
1. Workflow Managment 
2. Resource Managment

This project define few components:

ML-Pipeline
Responsible to consume data and finaly to produce an ML-Artifact to be used for ML-Serving.
It is a DAG reperesntation of ML-Stages and the dependecies between them.

ML-Stage
Has one of the following responsibilites:
1. Data Transformation
2. Model Creation
3. ML-Pipeline

Each ML-Stage is a trigger to a job/task that could be one of the following:
1. Spark job
2. Docker job


