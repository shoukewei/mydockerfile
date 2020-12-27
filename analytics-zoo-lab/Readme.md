Zoomlab is big data analysis platform, containimg Jupyter lab  and [Analystics zoo](https://analytics-zoo.github.io/0.9.0/#), for distributed TensorFlow, Keras and PyTorch on Apache Spark/Flink & Ray. 

Run the docker container: 
```docker run --rm -it -p 8888:8888 -v `pwd`/workspace:/workspace weicloud/zoolab```

This image is much smaller than the official one, which is built based on debian:stable-slim, Miniconda3, Analytics-zoo 0.9.0, Pywavelet, jupyterlab, scikit-learn, pandas, matplotlib, seaborn, pyecharts, etc. Use `conda list` to see the pakckages installed.
