# wordpressk8

# kubectl create namespace todo

# kubectl create namespace db

# MySQL
kubectl apply -f db/mysql-secret.yaml
kubectl apply -f db/mysql-configmap.yaml
kubectl apply -f db/mysql-statefulset.yaml
kubectl apply -f db/mysql-service.yaml

# WordPress
kubectl apply -f todo/wordpress-secret.yaml
kubectl apply -f todo/wordpress-configmap.yaml
kubectl apply -f todo/wordpress-deployment.yaml
kubectl apply -f todo/wordpress-service.yaml

