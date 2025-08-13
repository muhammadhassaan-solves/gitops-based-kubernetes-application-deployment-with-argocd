<h1>GitOps-Based Kubernetes Application Deployment with ArgoCD</h1>


<h2>Description</h2>
Implemented a GitOps workflow to deploy and manage a cloud-native application on Kubernetes using ArgoCD. Structured and version-controlled Kubernetes manifests in a GitHub repository, enabling automated synchronization of cluster state with repository changes. Monitored deployments, applied updates via commits, and added health checks to ensure application reliability.
<br />


<h2>Tools and Technologies</h2>

- Kubernetes (Minikube)
- ArgoCD
- Git
- GitHub
- Docker
- YAML

<h2>Project Walk-through</h2>

<p align="center">
Install and configure ArgoCD <br />
<img src="https://i.postimg.cc/m24SQhn7/1.jpg"/>
<br />
<br />
Prepare GitHub repository with Kubernetes manifests <br/>
<img src="https://i.postimg.cc/xdXG0mkV/2.jpg" />
<br />
<br />
Connect GitHub repo to ArgoCD <br/>
<img src="https://i.postimg.cc/15yp82gH/3.jpg"/>
<br />
<br />
Deploy application through GitOps <br/>
<img src="https://i.postimg.cc/tThxTNpw/4.jpg" />
<br />
<br />
Update application via Git commit <br/>
<img src="https://i.postimg.cc/Rh4nnJ0F/5.jpg" />
<br />
<br />
Watch ArgoCD sync changes automatically <br/>
<img src="https://i.postimg.cc/9FX7m9Sg/6.jpg" />
<br />
<br />
Add ConfigMap and mount it in Deployment <br/>
<img src="https://i.postimg.cc/6QZ7jf2q/7.jpg" />
<br />
<br />
Troubleshoot broken deployment <br/>
<img src="https://i.postimg.cc/j22t9Rgc/9.jpg" />
<br />
<br />
Add health checks and monitoring <br/>
<img src="https://i.postimg.cc/pr3b6znV/11.jpg" />
<br />
<br />

</p>

