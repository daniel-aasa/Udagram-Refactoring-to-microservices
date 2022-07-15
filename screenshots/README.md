# Screenshots
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* DockerHub showing containers that you have pushed
![dockerhub](https://user-images.githubusercontent.com/108951446/178914583-3840e771-9123-47ea-a8d0-0fc08d7b0d06.png)


* Travis CI showing a successful build and deploy job
![travvy](https://user-images.githubusercontent.com/108951446/178914681-65118b68-1f1a-4562-9d98-73ae71df4747.png)
![travvy2](https://user-images.githubusercontent.com/108951446/178916587-9cc6d2f2-5d9a-476f-ba33-399ecccc7247.png)



## Kubernetes
* To verify Kubernetes pods are deployed properly
```bash
kubectl get pods
```
![Pods running perfectly](https://user-images.githubusercontent.com/108951446/178914865-3deb9b96-cd70-4193-965a-ec056c336283.png)

* To verify Kubernetes services are properly set up
```bash
kubectl describe services
```
![describe service](https://user-images.githubusercontent.com/108951446/178914946-d023e7d6-1257-49d7-9e07-fecc0f741b57.png)
![describe2](https://user-images.githubusercontent.com/108951446/178916749-4374400a-dc27-48db-8610-01da3a053292.png)
![describe3](https://user-images.githubusercontent.com/108951446/178916772-1e9dd84d-968c-4c7c-b92a-77fe6c58a75f.png)


* To verify that you have horizontal scaling set against CPU usage
```bash
kubectl get hpa
```
![ge hpa](https://user-images.githubusercontent.com/108951446/179120830-9f7ea66a-c4af-430a-bd03-9e53563a10b8.png)


* To verify that you have set up logging with a backend application
```bash
kubectl logs {pod_name}
```
![logs](https://user-images.githubusercontent.com/108951446/179120899-ce1101db-4309-4c87-ae86-af6a974dbd1a.png)




finally the front end
![udagram](https://user-images.githubusercontent.com/108951446/178915519-a9649761-900b-43b2-870e-636535551a62.png)
