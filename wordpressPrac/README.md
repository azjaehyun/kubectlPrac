kubectl apply -k ./
kubectl apply -f wordpress-virtualservice.yaml
kubectl get all     

vi /etc/host  >> add last line 
127.0.0.0 wordpress.example.com  << add


excute chome browser call url
http://wordpress.example.com

finish