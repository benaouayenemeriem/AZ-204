
# Definition

## What is Azure App Service web Apps 🌐🔒

HTTPS-based service for hosting web applications, REST APIs, and mobile back end
- **Supports Several Languages and Frameworks** 🛠️✨ 
- **Supports Both Windows and Linux** 💻🐧 
- **Supports Containers**📦:  
    - **Supports**: Pull container images 🔄, multi-container apps ⚙️, Docker Compose 🐳
- **Supports CI/CD** auto
- 📌 It can Scale to multiple instances : 
	- **scale up/down:** the ability to increase, or decrease the **number of cores** or the **amount of RAM** available ⬆️⬇️
	- **scale out/in:** the ability to increase, or decrease the **number of machine instances** that are running your web app ⬅️➡️

- **Deployment Slots** 🛠️🔄:  
  you can use a **separate deployment slot** instead of the default production slot (available in the **Standard App Service Plan** tier or higher).  
	  - Deployment slots are **live apps** with their own host names 🌐.  
	  - **App content and configurations** can be swapped between two deployment slots, including the **production slot** 🔄💻.
	The concept of **deployment slots** in Azure App Service is similar to the **Blue-Green Deployment** strategy 😊

--- 
#### **Definition of HTTPS-Based Service**

- Azure App Service ensures secure communication between users and applications by default using the **HTTPS protocol**.
    - HTTPS encrypts data in transit, ensuring security and privacy.
    - Azure App Service also provides **free SSL/TLS certificates** to simplify HTTPS setup.

#### **Definition of Hosting Web Applications**

- Azure App Service hosts **web applications** built with various frameworks like ASP.NET, Node.js, Java, PHP, Python, etc.
- It supports dynamic content rendering and can serve websites directly.
- Examples:
    - Hosting a content management system (CMS) like WordPress.
    - Hosting Single Page Applications (SPAs) with React or Angular.

--- 



