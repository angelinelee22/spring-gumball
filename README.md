# CMPE 172 - Lab #10 Notes

NOTE: The device used in this lab was under the name of "Aaron Phong" because I had technical difficulties with my own device.

## CI Workflow (Part 1)
1. Commit build.yml to `master` branch
![ci-workflow](./images/ci-workflow.png)

2. Watch for build success
![ci-success](./images/ci-success.png)

### CD Workflow (Part 2)
1. Create service account as "owner"
![cd-accounts](./images/cd-accounts.png)

2. Create service account key
![cd-accountkeys](./images/cd-accountkeys.png)

3. Create GitHub action secrets
![cd-secrets](./images/cd-secrets.png)

4. Update google.yml to contain GKE deployment information and trigger CD Deployment with release
![cd-create](./images/cd-create.png)
![cd-release](./images/cd-release.png)

5. Wait for workflow success (here it was done under 1.1)
![cd-workflowprogress](./images/cd-workflowprogress.png)
![cd-workflowprogress2](./images/cd-workflowprogress2.png)
![cd-workflowsuccess](./images/cd-workflowsuccess.png)

All workflows afterwards:
![cd-allworkflows](./images/cd-allworkflows.png)

**Google Kubernetes Engine Results**

6. Cluster creation (manual)
![gke-cluster](./images/gke-cluster.png)

7. Deployment
![gke-deployment](./images/gke-deployment.png)

8. Service
![gke-service](./images/gke-service.png)

9. Ingress
![gke-createingress](./images/gke-createingress.png)
![gke-ingress](./images/gke-ingress.png)

10. Success!
![gke-success](./images/gke-success.png)
