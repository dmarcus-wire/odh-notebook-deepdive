# odh-notebook-deepdive
Review the ODH Jupyter Notebook Images, use cases and how to customize your own.

From the JupyterHub spawner dropdown, you will notice the below notebook images after a default installation of ODH:
|Notebook|Recommended use|
|-|-|
|s2i-generic-data-science-notebook:v0.0.2||
|s2i-lab-elyra:v0.0.7||
|s2i-minimal-notebook:v0.0.7||
|s2i-scipy-notebook:v0.0.2||
|s2i-spark-minimal-notebook:py36-spark2.4.5-hadoop2.7.3||
|s2i-spark-scipy-notebook:3.6||
|s2i-tensorflow-notebook:v0.0.2|Tensorflow|

![image](images/odh-jh-spawner.png)

Each notebook has an available ImageStream and BuildConfig published to github.com/opendatahub-io

## s2i-generic-data-science-notebook 
![image](images/s2i-ds-nb.png)

- UBI8
- Python38

## s2i-lab-elyra
![image](images/s2i-elyra.png)

- UBI8
- Python38
- Elyra plugin

## s2i-minimal-notebook
![image](images/s2i-min.png)

- UBI7
- UBI8
- Python36
- Python38
## s2i-scipy-notebook
![image](images/s2i-sc-nb.png)

- UBI8
- Python36

## s2i-spark-minimal-notebook:py36-spark2.4.5-hadoop2.7.3 
![images](images/s2i-sp-min.png)

- UBI8
- Python36
- Java
- Hadoop
- Spark

## s2i-spark-scipy-notebook 
![images](images/s2i-sp-sc-nb.png)

- UBI8
- Python36

## s2i-tensorflow-notebook

![images](images/s2i-tf-nb.png)

- UBI8
- Python36
- tensorflow 2
- jupyter-tensorboard

