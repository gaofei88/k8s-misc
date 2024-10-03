## Apply Manifest
    `kubectl apply -f 0-kafka-controller.yaml`
    `kubectl apply -f 1-schemaregistry.yaml`
    `kubectl apply -f 2-kafka-connect.yaml`
    `kubectl apply -f 3-kafka-ui.yaml`

## Port forward to Kafka UI
    `kubectl port-forward svc/kafka-ui 9999:8080`
