**Blue-Green Deployment on Kubernetes**

**Project Overview**

This project demonstrates a **Blue-Green Deployment strategy using Kubernetes**.  
It ensures zero-downtime deployment by running two identical environments (Blue and Green) and switching traffic between them using a Kubernetes Service.

**Architecture**

**Frontend (Blue Version)** – 
**Frontend (Green Version)** –
**Backend Service** – 
**Kubernetes Service (NodePort)** –

  **Project Structure**

  <img width="646" height="557" alt="image" src="https://github.com/user-attachments/assets/3205b18a-ed65-49ae-aead-edc110103cb5" />


**mongodb connections**
   <img width="1869" height="619" alt="image" src="https://github.com/user-attachments/assets/5de415a1-809e-4899-89e0-1969bc0331cf" />

**Docker images**
   <img width="1625" height="254" alt="image" src="https://github.com/user-attachments/assets/543f28f6-2e21-4f11-81c0-3c5fe64fff9d" />

**Created docker container**
   <img width="1835" height="285" alt="image" src="https://github.com/user-attachments/assets/c0a35b2f-8f00-4b3a-971e-2481d1093e7c" />

**kubernetes Manifest files**
   <img width="1044" height="165" alt="image" src="https://github.com/user-attachments/assets/f1fdc2d9-d3d6-4408-909d-fa6dc5449335" />

   **frontend-blue-deployment file**
   <img width="1817" height="508" alt="image" src="https://github.com/user-attachments/assets/e251ea5f-8244-4d52-b11d-dc5f576e6152" />

 **frontend-green-deployment file**
    <img width="1819" height="499" alt="image" src="https://github.com/user-attachments/assets/4db7dfe9-261b-4a03-bcc0-5f8508c2cc83" />

 **Endpoints Connection**
   <img width="894" height="88" alt="image" src="https://github.com/user-attachments/assets/b1d16e7f-acbb-4c9e-bd0d-297f02fc12e5" />

**Backend pods running**
 <img width="749" height="110" alt="image" src="https://github.com/user-attachments/assets/7fb0e35d-7aa8-4055-980c-13e492263aa9" />

**service pods**
  <img width="970" height="127" alt="image" src="https://github.com/user-attachments/assets/cd04743d-a912-4f96-9b55-423f7207aa3a" />

**switced from frontend services blue to green**
   <img width="1445" height="73" alt="image" src="https://github.com/user-attachments/assets/c717a40b-01d2-4f7e-8c80-750a2d3dab91" />

**Sucessfull frontend respose**
    <img width="1518" height="802" alt="image" src="https://github.com/user-attachments/assets/1b5e354d-f3ae-410c-bf90-0bb52185b058" />
    <img width="1465" height="626" alt="image" src="https://github.com/user-attachments/assets/0ea1bf1e-07d9-43d2-b59b-48d4de1b8dc8" />









