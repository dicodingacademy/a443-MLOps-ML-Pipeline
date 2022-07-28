# a443-MLOps-ML-Pipeline
Ini adalah repositori untuk latihan pada kelas Machine Learning Operations (MLOps)


## Menbuat dan menjalankan docker image.

```
docker build -t sarchasm-detection-tf-serving .


docker run -p 8080:8501 sarchasm-detection-tf-serving
```