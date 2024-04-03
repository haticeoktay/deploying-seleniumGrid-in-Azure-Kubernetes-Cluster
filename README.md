# Deploy Selenium-Grid version 4 in Azure Kubernetes Cluster
.yml uzantılı dosyalar önceden create edilmiştir.
kubectl config current-context
hatice-selenium

selenium-hub-svc.yml
kubectl apply -f selenium-hub-svc.yml
kubectl get services
![image](https://github.com/haticeoktay/information/assets/65062246/b7a28da6-3774-4711-aae2-ca82e306e73c)

selenium-hub-deployment.yml
kubectl apply -f selenium-hub-deployment.yml

selenium-temp.yml
kubectl apply -f selenium-temp.yml![image](https://github.com/haticeoktay/information/assets/65062246/0bb33cd3-d7dc-4c0f-b2ef-d7f9b7a41a47)

Now you can check the grid ui at http://yourExternalIPAddress:4444/grid/console![image](https://github.com/haticeoktay/information/assets/65062246/7870a8c6-2d51-44bf-a170-de6e4d154fa3)




