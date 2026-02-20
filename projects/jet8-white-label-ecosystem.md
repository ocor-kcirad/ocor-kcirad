## 🏗️ Project Spotlight: Scalable White-Label Ecosystem (Jet8 Pte. Ltd.)
> **Role:** Android Engineer (Remote - Singapore) | Nov. 2017 – Dec. 2018

### 📌 The Challenge
The objective was to deliver a core social and e-commerce experience to multiple global brands, each requiring distinct branding, unique API configurations, and specific feature sets. Maintaining separate codebases for each client was unsustainable and prone to synchronization errors.

### 🛠️ The Solution: "One Core, Many Identities"
Architected a white-labeling system that allowed the team to deploy customized versions of the application from a single, unified source:

* **Build Variant Architecture:** Leveraged **Gradle build variants** and **product flavors** to manage brand-specific identities, assets, and feature flags seamlessly.
* **Core App Migration:** Led the successful transition of the core application from **Java to Kotlin**, which improved performance and simplified the management of complex configurations.
* **Modern Architecture Implementation:** Applied **MVVM** and **Clean Architecture** to ensure that business logic remained independent of the brand-specific UI layers.
* **Resource Injection:** Developed a system for custom resource overrides, allowing brands to customize colors, strings, and assets without modifying the core logic.

### 📈 Key Results
* **Operational Efficiency:** Drastically reduced the time required to onboard and deploy new branded applications.
* **Maintainability:** The migration to Kotlin and MVVM created a more readable and testable codebase, even as the number of supported brands grew.
* **Commercial Scalability:** Successfully supported the deployment of the core technology to multiple international clients and global brands.

### 🧰 Technical Stack
* **Languages:** Kotlin, Java
* **Architecture:** MVVM, Clean Architecture, SOLID
* **Build System:** Gradle (Product Flavors & Build Variants)
* **Patterns:** Dependency Injection, Factory Pattern
