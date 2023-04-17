# dockerized-pyspark

To build the image 
`docker build -t spark:pyspark .`

To run pyspark in the terminal, use `pyspark` command in the shell of the container and access the 4040 port

` docker run --rm -p 8888:8888 -p 4040:4040 -v ~/Project/pyspark/data:/opt/spark/work-dir --name spark spark:pyspark`

To run spark shell, use `spark-shell` command in the shell of the container
