Blue-Green Deployment on Kubernetes

Project Overview

This project demonstrates a **Blue-Green Deployment strategy using Kubernetes**.  
It ensures zero-downtime deployment by running two identical environments (Blue and Green) and switching traffic between them using a Kubernetes Service.

Architecture

- **Frontend (Blue Version)** – 
- **Frontend (Green Version)** –
- **Backend Service** – 
- **Kubernetes Service (NodePort)** –

- Project Structure

- Blue-green-Deployment/
│
├── k8s/
│ ├── frontend-blue.yaml
│ ├── frontend-green.yaml
│ ├── frontend-service.yaml
│ ├── backend-service.yaml
│
├── backend/
├── frontend/

Deployment Steps

### 1. Clone Repository
```bash
git clone <repo-url>
cd Blue-green-Deployment

mongodb connections
<img width="1869" height="619" alt="image" src="https://github.com/user-attachments/assets/5de415a1-809e-4899-89e0-1969bc0331cf" />


Created docker container
<img width="1835" height="285" alt="image" src="https://github.com/user-attachments/assets/c0a35b2f-8f00-4b3a-971e-2481d1093e7c" />


Backend pods running
<img width="749" height="110" alt="image" src="https://github.com/user-attachments/assets/7fb0e35d-7aa8-4055-980c-13e492263aa9" />

srvice pods
<eimg width="970" height="127" alt="image" src="https://github.com/user-attachments/assets/cd04743d-a912-4f96-9b55-423f7207aa3a" />

switced from frontend services blue to green 
<img width="1445" height="73" alt="image" src="https://github.com/user-attachments/assets/c717a40b-01d2-4f7e-8c80-750a2d3dab91" />










