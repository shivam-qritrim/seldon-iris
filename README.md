pip install seldon-core

seldon-core-microservice MyModel --service-type MODEL

curl -X POST -H 'Content-Type: application/json' -d '{"data": { "ndarray": [[1,2,3,4]]}}' http://127.0.0.1:9000/predict
