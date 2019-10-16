FROM hftony/aws-es-proxy:v1
MAINTAINER tony marchante "tony.marchante@gmail.com"


ENV AWS_ACCESS_KEY_ID="YOURACCESSKEY"
ENV AWS_SECRET_ACCESS_KEY="YOURSECRETKEY"
ENV ES_ENDPOINT="YOURESENDPOINT"

CMD ["sh", "-c", "./aws-es-proxy -listen 0.0.0.0:9200 -endpoint ${ES_ENDPOINT}"]
