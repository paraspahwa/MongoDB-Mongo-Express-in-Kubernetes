# MongoDB-Mongo-Express-in-Kubernetes
Run MongoDB and Mongo Express in Kubernetes
Prepare values for Secrets:

$ echo -n "username" | base64
dXNlcm5hbWU=
$ echo -n "password" | base64
cGFzc3dvcmQ=

# Create MongoDB Secret - mongo-secret.yaml
# Create MongoDB Secret - mongo-secret.yaml
# Create MongoDB internal Service - mongo-internal-service.yml
# Create ConfigMap to define database URL for Mongo Express- mongo-configmap.yaml
# Create Mongo Express Deployment - mongo-express-deployment.yaml
# Create Mongo Express Service - mongo-express-service.yaml

Access the service (in minikube):
minikube service mongo-express-service
