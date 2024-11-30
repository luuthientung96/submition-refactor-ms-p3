**Project Deployment Results**
![image](https://github.com/user-attachments/assets/8eedec32-bd5e-4154-b592-3a5338614b2f)

This repository contains the results of deploying our application using Docker, EKS, and CI/CD pipelines. Screenshots documenting the process and outputs are located in the Screenshot Submit folder. Below is a breakdown of the included contents:

**1. Docker Images**

Screenshots of Docker images uploaded to the DockerHub repository.
![image](https://github.com/user-attachments/assets/91f3a407-d222-4a26-bd68-8300ab663603)

**2. CI/CD Pipeline**

Initially set up with TravisCI, but due to the availability of a free plan, the build pipeline was migrated to CircleCI.
Screenshots show successful build jobs in the CircleCI pipeline.
![image](https://github.com/user-attachments/assets/90625f17-efd4-4ddf-9e1b-643c243de111)

**3. Kubernetes Outputs**

**Pods Information:**

Screenshot of the kubectl get pods command output, showing the status of pods running in the Kubernetes cluster.
![image](https://github.com/user-attachments/assets/b6a1c53c-5f29-4d38-9a38-5cb427e93740)

**Services Description:**

Screenshot of the kubectl describe services command output, providing detailed information about Kubernetes services.
![image](https://github.com/user-attachments/assets/f13ded1e-e846-4547-96f6-78289278d115)
![image](https://github.com/user-attachments/assets/df9e1d3a-5e71-4ccd-9224-c3ac2a516102)
![image](https://github.com/user-attachments/assets/affb7a07-ebcb-4f87-8447-3a57ab4f406b)


**Horizontal Pod Autoscaler (HPA):**

Screenshot of the kubectl describe hpa command output, detailing the autoscaling setup for the pods.
![image](https://github.com/user-attachments/assets/a12ab19a-c544-40b8-b65d-d10cd2330967)

**Pod Logs:**

Screenshot of the kubectl logs command output, showing logs for a specific pod.
![image](https://github.com/user-attachments/assets/ef9c00d3-1c0f-467b-bd29-d9d6cae3fcb1)

