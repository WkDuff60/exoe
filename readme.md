# Docker project

Liste des commandes effectuées 

1. docker build -t wkduff/exoe . 

2. git init

3. git add .

4. git commit

5. git remote add origin lien-github

6. git push -u origin master

7. kubectl create deployment exoe --image wkduff/exoe

8. kubectl expose deployment/exoe --type LoadBalancer --port 80

9. kubectl apply -f .\deployment.yml,.\service.yml

10. minikube service exoe-deploy


