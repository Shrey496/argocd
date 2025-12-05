# ArgoCD
ArgoCD deployments on a k3d cluster.
<img width="1431" height="290" alt="Screenshot 2025-12-05 at 3 55 52 PM" src="https://github.com/user-attachments/assets/c0de6096-87c6-4dcb-8058-10117f6ff89a" />

Create a new application:

<img width="1135" height="376" alt="Screenshot 2025-12-05 at 3 57 43 PM" src="https://github.com/user-attachments/assets/220b6dae-911e-4bc7-a00f-b4501caa7381" />

<img width="1105" height="383" alt="Screenshot 2025-12-05 at 3 59 45 PM" src="https://github.com/user-attachments/assets/ddffe18a-9aec-492d-9b35-27009fe3f244" />

<img width="1147" height="339" alt="Screenshot 2025-12-05 at 4 00 40 PM" src="https://github.com/user-attachments/assets/68c1b805-dbc9-4bf6-89c8-d184bccd7499" />

Needs to be synced manually as per the set configuration:

<img width="603" height="364" alt="Screenshot 2025-12-05 at 4 01 16 PM" src="https://github.com/user-attachments/assets/faff78f8-3a9b-476a-a8e3-fe77865ce8cd" />

<img width="876" height="317" alt="Screenshot 2025-12-05 at 4 02 24 PM" src="https://github.com/user-attachments/assets/382f5322-407f-45d0-bda0-fa503545687b" />

**Diff** option can be used to check the current state of a running Kubernetes object like deployment, service, and so on. (Currently, none is running)

<img width="1088" height="625" alt="Screenshot 2025-12-05 at 4 03 10 PM" src="https://github.com/user-attachments/assets/6ddcfa97-dd35-49da-807d-9070b026e555" />

Click on **SYNC**

<img width="606" height="671" alt="Screenshot 2025-12-05 at 4 05 38 PM" src="https://github.com/user-attachments/assets/e4c20926-b3a6-41b6-a5dd-5480b61b413d" />

The objects have been deployed successfully.

<img width="1159" height="312" alt="Screenshot 2025-12-05 at 4 06 43 PM" src="https://github.com/user-attachments/assets/83c7e895-47ac-4e99-9bdb-887fdea126a6" />
<img width="741" height="209" alt="Screenshot 2025-12-05 at 4 08 35 PM" src="https://github.com/user-attachments/assets/56311058-9673-4aab-948a-f54063075928" />

If a change is made in one of the YAML files, replicas are set to '2' from '1'.

<img width="580" height="365" alt="Screenshot 2025-12-05 at 4 21 10 PM" src="https://github.com/user-attachments/assets/9ba86ab1-e949-4605-b883-758726487596" />

The application on the **ArgoCD UI** goes **OutOfSync** as expected
<img width="613" height="412" alt="Screenshot 2025-12-05 at 4 21 28 PM" src="https://github.com/user-attachments/assets/7b0903a8-b36d-4717-9441-1211b1941e3b" />

**Diff** section shows the exact change made to the deployment YAML which resulted in **OutOfSync**

<img width="1073" height="364" alt="Screenshot 2025-12-05 at 4 40 53 PM" src="https://github.com/user-attachments/assets/39c9b7bb-7c5e-41c4-85cf-ba4958350645" />

The number od nginx pods have changed to 2.
<img width="1162" height="302" alt="Screenshot 2025-12-05 at 4 41 39 PM" src="https://github.com/user-attachments/assets/8e732bff-8872-477a-b73d-d5a402ab1774" />



