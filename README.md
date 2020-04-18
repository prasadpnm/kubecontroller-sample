make manifests. 

kubectl create -f config/crd/base 

kubectl create -f config/samples/webapp_v1_guestbook.yaml

kubectl create -f config/samples/webapp_v1_redis.yaml

kubectl get guestbooks

make run 

new terminal 
minikube servie guestbook-service 
