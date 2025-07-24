
### 📘 **3-Tier Architecture – Notes**

#### 🔹 1. **What is 3-Tier Architecture?**

3-Tier Architecture is a **software architecture pattern** that separates an application into three logical layers — making the system more **scalable, maintainable, and secure**.

---

#### 🔹 2. **The 3 Tiers in Architecture**

##### ✅ **1. Presentation Tier (Frontend)**

* This is the **User Interface** layer.
* End-users interact with the application through this layer.
* Technologies: HTML, CSS, JavaScript, React, Angular, Mobile Apps, etc.

##### ✅ **2. Application Tier (Business Logic Layer / Middle Tier)**

* Contains the **core business logic**.
* Processes input from the presentation layer and communicates with the database.
* Technologies: Node.js, .NET, Java, Python, etc.

##### ✅ **3. Data Tier (Database Layer / Backend)**

* Responsible for **storing and managing data**.
* Accepts queries from the application tier and returns data.
* Databases: MySQL, PostgreSQL, SQL Server, MongoDB, etc.

---

#### 🔹 3. **Advantages of 3-Tier Architecture**

* **Scalability:** Each layer can be scaled independently.
* **Security:** Backend and database are not directly exposed to users.
* **Maintainability:** Easy to manage and update individual layers.
* **Reusability:** Business logic can be reused across multiple interfaces.
* **Performance:** Load is distributed across separate layers.

---

#### 🔹 4. **3-Tier in Cloud Platforms (Azure | AWS | GCP)**

| Tier              | Azure Services              | AWS Services               | GCP Services               |
| ----------------- | --------------------------- | -------------------------- | -------------------------- |
| Frontend          | Static Web App, App Service | S3 Static Website, Amplify | Firebase Hosting           |
| Application Logic | App Service, AKS, Functions | ECS, EKS, Lambda           | Cloud Run, Cloud Functions |
| Database          | Azure SQL, Cosmos DB        | RDS, DynamoDB              | Cloud SQL, Firestore       |

---

#### 🔹 5. **Real-World Example (Web App)**

* **Presentation Layer:** React web app hosted on Azure Static Web App
* **Application Layer:** Node.js backend hosted on Azure App Service
* **Database Layer:** Azure SQL Database

---
