# 🌐 Lesson 2: Cloud Delivery Models

Welcome to the second episode of our **AWS Course**, where we explore the different **Cloud Delivery Models** that are essential for understanding how cloud infrastructure is deployed and managed. These models define the level of responsibility shared between the cloud provider and the client.

---

## 🏗️ Cloud Delivery Models Overview

There are four primary cloud delivery models:

1. **On-Premises (On-Premise)**
2. **Infrastructure as a Service (IaaS)**
3. **Platform as a Service (PaaS)**
4. **Software as a Service (SaaS)**

Each of these models delivers cloud services at varying levels of responsibility between the client and the cloud provider.

---

### 🏢 **On-Premises**

In the **On-Premises** delivery model, all the physical infrastructure (servers, storage, networking) is located on-site at the client's location. The client is fully responsible for managing and maintaining these physical components.

- **Client Responsibility**: Physical servers, networking, and hardware security.
- **Amazon AWS Support**: While Amazon primarily focuses on cloud services, it sometimes provides physical servers to the client if needed.

---

### 🖥️ **Infrastructure as a Service (IaaS)**

In the **IaaS** model, AWS manages the underlying hardware infrastructure, including servers, storage, networking, and physical security. The client is responsible for the software layer, including the operating system, middleware, and applications.

- **AWS Responsibility**: Hardware, storage, networking, physical security.
- **Client Responsibility**: Operating system, application environment, and software.

---

### 🔧 **Platform as a Service (PaaS)**

With **PaaS**, AWS takes on more responsibility by managing the hardware as well as the operating system. The client only needs to manage their application and any necessary dependencies.

- **AWS Responsibility**: Hardware, operating system, storage, networking.
- **Client Responsibility**: Applications and their dependencies.

---

### 🌐 **Software as a Service (SaaS)**

In the **SaaS** model, AWS (or other providers) manages everything, including the infrastructure, operating system, and the application itself. The client simply uses the software delivered over the internet.

- **AWS Responsibility**: Entire infrastructure, including applications.
- **Client Responsibility**: Simply use the service.
  
Common SaaS examples include applications like **Facebook**, **Google Drive**, and **WhatsApp** where the entire application and user data are hosted and managed in the cloud.

---

## 💡 Key Takeaways

- **Combining Delivery Models**: It’s common to combine delivery models. For example, on-premises physical servers might be connected to the cloud through IaaS or PaaS, creating a hybrid approach.
  
- **Security**: AWS ensures that the physical infrastructure and your data are secure by default. However, it's crucial to understand that clients have the flexibility to configure settings, which can impact security or performance.

---


