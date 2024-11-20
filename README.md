# AWS EKS Deployment with Kubernetes
![Screenshot from 2024-11-02 01-46-44](https://github.com/user-attachments/assets/d42d2e70-f37d-4a76-bc38-0cc3e3271e6e)

## Project Overview

The **Nike Store Application** has been deployed on Amazon **EKS (Elastic Kubernetes Service)**, showcasing expertise in cloud-native application management. This deployment ensures scalability, high availability, and accessibility through a load balancer, following best practices for Kubernetes and cloud infrastructure.

This project demonstrates my ability to handle real-world deployment challenges and implement robust solutions in a production-grade environment. ☁️🌟

---

## 🎯 Project Objectives
- Deploy the **Nike Store** application on an **EKS cluster**.
- Configure and expose the application using a load balancer for seamless traffic handling.
- Employ best practices for cloud infrastructure, scalability, and high availability.

---


## Key Features
- **Scalability**: Achieved scalability through **Kubernetes Deployments** and **replicas**.
- **Load Balancer Integration**: Exposed the application via **AWS Elastic Load Balancer** (ELB).
- **High Availability**: Ensured high availability through **multi-replica deployments** and EKS managed nodes.

---

## Technologies Used

- **AWS EKS**: For managing Kubernetes clusters on AWS.
- **Kubernetes**: For orchestrating containerized applications.
- **Docker**: For containerizing the MERN stack application.
- **AWS Elastic Load Balancer (ELB)**: For distributing traffic across replicas.
- **AWS IAM**: For secure access management and cluster operations.

---

## 🚀 Deployment Steps

1. **Kubernetes Configuration**
   - Defined the deployment.yaml file to manage pods and replicas.
   - Configured service.yaml to expose the application through a **Load Balancer** for seamless access.

2. **AWS EKS Setup**
   - Created an **EKS** cluster using **AWS CLI** and **eksctl**.
   - Attached appropriate **IAM roles** to ensure secure and efficient cluster operations.

3. **Application Deployment**
   - Built and pushed Docker images to **Docker Hub** for containerization.
   - Deployed the application using **kubectl** commands and Kubernetes manifest files.

4. **Load Balancer Integration**
   - Configured an **AWS Elastic Load Balancer (ELB)** to handle and distribute incoming traffic efficiently.

---

## Future Improvements

- **Add Monitoring**:  
  Integrate **Prometheus** and **Grafana** to monitor the application and Kubernetes cluster performance. This will help in gaining real-time insights and metrics, enabling better decision-making for scaling and optimization.

- **Auto-scaling**:  
  Implement **auto-scaling** for the application based on resource usage such as CPU and memory. This will improve **cost efficiency** by automatically adjusting the number of replicas based on demand, ensuring optimal performance.

- **Improve Security**:  
  Enhance the security of the application and Kubernetes environment by:
  - Setting up **IAM roles** with the principle of least privilege.
  - Configuring **RBAC** (Role-Based Access Control) to manage permissions in the Kubernetes cluster.
  - Implementing **network policies** to control traffic between services and limit potential attack surfaces.

---

## Conclusion

This project provided me with hands-on experience in deploying a **scalable** and **highly available** application on **AWS EKS** using **Kubernetes**. It reinforced my understanding of the following cloud-native concepts and technologies:

- **Containerization** with **Docker** for creating portable and consistent environments.
- **Kubernetes** for managing containerized applications in a production environment.

The practical experience gained in deploying, managing, and optimizing cloud applications has strengthened my skills and deepened my knowledge of **cloud computing** and **DevOps** practices. This project also provided valuable insights into scaling, monitoring, and securing cloud-based applications.
