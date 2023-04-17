# dockerized-pyspark

To build the image 
`docker build -t pyspark .`

` docker run --rm -p 8888:8888 -p 4040:4040 -v ~/Project/pyspark/data:/opt/spark/work-dir --name spark spark:pyspark`
