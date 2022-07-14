# Screenshots
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* DockerHub showing containers that you have pushed
![dockerhub](https://user-images.githubusercontent.com/108951446/178914583-3840e771-9123-47ea-a8d0-0fc08d7b0d06.png)


* Travis CI showing a successful build and deploy job
![travvy](https://user-images.githubusercontent.com/108951446/178914681-65118b68-1f1a-4562-9d98-73ae71df4747.png)
![trav](https://user-images.githubusercontent.com/108951446/178914701-d80d4586-32eb-4344-8914-e51f87a663e7.png)


## Kubernetes
* To verify Kubernetes pods are deployed properly
```bash
kubectl get pods
```![Pods running perfectly](https://user-images.githubusercontent.com/108951446/178914865-3deb9b96-cd70-4193-965a-ec056c336283.png)

* To verify Kubernetes services are properly set up
```bash
kubectl describe services
```![describe service](https://user-images.githubusercontent.com/108951446/178914946-d023e7d6-1257-49d7-9e07-fecc0f741b57.png)

* To verify that you have horizontal scaling set against CPU usage
```bash
kubectl describe hpa
```![hpa](https://user-images.githubusercontent.com/108951446/178915164-d74153eb-a908-4475-88b6-cf882020326c.png)

* To verify that you have set up logging with a backend application
```bash
kubectl logs {pod_name}
```
finally the front end
![udagram](https://user-images.githubusercontent.com/108951446/178915519-a9649761-900b-43b2-870e-636535551a62.png)
