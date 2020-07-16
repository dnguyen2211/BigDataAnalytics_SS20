# BigDataAnalytics_SS20
Materials for the BigData Analytics lecture in SS20


## Docker GPU Images
```
docker pull rapidsai/rapidsai:cuda10.0-runtime-ubuntu18.04-py3.6
docker run --gpus all --rm -it -p 8888:8888 -p 8787:8787 -p 8786:8786 \
         rapidsai/rapidsai:cuda10.0-runtime-ubuntu18.04-py3.6
```
