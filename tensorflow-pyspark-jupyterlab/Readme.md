- Anaconda, Tensorflow, Pyspark, Jupyter Lab
- dockerfiles for build docker images
`docker build -t weicloud/tf-pyspark-lab .`
- Run the docker container:
`docker run --rm -it -p 8888:8888 -v `pwd`/workspace:/workspace weicloud/tf-pyspark-lab`
- Run bash
`docker run -it --entrypoint /bin/bash weicloud/tf-pyspark-lab`
