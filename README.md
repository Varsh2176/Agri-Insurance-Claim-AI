# 🌾 AI-Driven AgriInsurance Claim Validation

An intelligent web-based prototype designed to streamline agricultural insurance claim management by providing role-based workflows for **Farmers, Insurance Officers, and Government Administrators**.

The system aims to simplify claim submission, verification, monitoring, and analytics while providing a foundation for future AI-powered crop damage and fraud assessment.

---

## 📌 Problem Statement

Agricultural insurance claim processing can involve significant manual verification, documentation, and delays. Farmers may face difficulties tracking claims, while insurance officers need efficient mechanisms to review and validate submitted information.

This project provides a digital platform to simplify the overall claim-management workflow and improve transparency between farmers, insurance providers, and government authorities.

---

## 💡 Solution

The system provides separate interfaces for different stakeholders:

* 👨‍🌾 **Farmers** can submit and track insurance claims.
* 🏢 **Insurance Officers** can review and validate claims.
* 🏛️ **Government Administrators** can monitor claims and view analytics.
* 🤖 The architecture provides a foundation for integrating AI-based crop damage assessment, risk prediction, and fraud detection.

---

## ✨ Features

### 👨‍🌾 Farmer Portal

* User login and registration
* Submit agricultural insurance claims
* Enter crop and damage information
* Track claim status
* View submitted claims
* Access claim-related information

### 🏢 Insurance Officer Portal

* View submitted claims
* Review claim information
* Validate submitted claims
* Update claim status
* Monitor claim processing

### 🏛️ Government Portal

* Monitor insurance claims
* View claim statistics
* Analyze agricultural insurance data
* Track overall claim activity

### 🤖 Intelligent Validation

The project is designed around an AI-assisted claim-validation workflow that can be extended with:

* Crop damage assessment
* Weather-based risk analysis
* Satellite imagery analysis
* Fraud detection
* Claim risk scoring

---

## 🛠️ Tech Stack

### Frontend

* **HTML5** — Web page structure
* **CSS3** — Styling, responsive layouts, and dashboard design
* **JavaScript (ES6+)** — Application logic, validation, interactions, and dynamic content

### Data & Storage

* **Browser LocalStorage** — Stores demo users and application data locally in the browser

### Development Tools

* **Visual Studio Code** — Development environment
* **Git** — Version control
* **GitHub** — Source-code hosting and collaboration
* **Live Server** — Local development and testing

### Deployment

* **Netlify** — Web application deployment

---

## 🏗️ System Architecture

```text
                    ┌─────────────────────┐
                    │      User           │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │    Web Interface    │
                    │   HTML + CSS + JS   │
                    └──────────┬──────────┘
                               │
              ┌────────────────┼────────────────┐
              │                │                │
              ▼                ▼                ▼
       ┌─────────────┐  ┌──────────────┐  ┌─────────────┐
       │   Farmer    │  │    Officer   │  │ Government  │
       │   Portal    │  │    Portal    │  │   Portal    │
       └──────┬──────┘  └──────┬───────┘  └──────┬──────┘
              │                │                 │
              └────────────────┼─────────────────┘
                               ▼
                    ┌─────────────────────┐
                    │ Application Logic   │
                    │    JavaScript       │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │     LocalStorage    │
                    │    Demo Data Store  │
                    └─────────────────────┘

                 Future AI/ML Integration
                               │
             ┌─────────────────┼─────────────────┐
             ▼                 ▼                 ▼
       Crop Damage        Weather Risk       Fraud/Risk
        Detection          Analysis          Prediction
```

---

## 📁 Project Structure

```text
Agri-Insurance-Claim-AI/
│
├── Atechext/
│   ├── css/
│   │   └── style.css
│   └── js/
│       ├── analytics.js
│       ├── chatbot.js
│       ├── core.js
│       ├── engine.js
│       ├── finance.js
│       └── i18n.js
│
├── farmer.html
├── government.html
├── index.html
├── officer.html
│
└── README.md

```

### Important Files

| File              | Description                                 |
| ----------------- | ------------------------------------------- |
| `index.html`      | Main landing/login page                     |
| `farmer.html`     | Farmer dashboard                            |
| `officer.html`    | Insurance officer dashboard                 |
| `government.html` | Government dashboard                        |
| `core.js`         | Core application functionality              |
| `engine.js`       | Claim processing and application logic      |
| `finance.js`      | Financial/claim-related functionality       |
| `chatbot.js`      | Chatbot functionality                       |
| `analytics.js`    | Analytics and statistics                    |
| `i18n.js`         | Language/internationalization functionality |
| `style.css`       | Application styling                         |

---

## ⚙️ Prerequisites

Before running the project, make sure you have:

* A modern web browser such as Google Chrome, Microsoft Edge, or Firefox
* **Git**
* **Visual Studio Code** (recommended)
* **Live Server** extension for VS Code (recommended)

No Python, Node.js, or local database installation is required for the current frontend prototype.

---

## 🔐 Demo Credentials

Use the following demo credentials to explore the different user roles.

| Role              | Username   | Password |
| ----------------- | ---------- | -------- |
| Farmer            | `farmer1`  | `1234`   |
| Insurance Officer | `officer1` | `1234`   |
| Government        | `gov1`     | `1234`   |

> **Note:** These credentials are for demonstration purposes only.

---

## 🧪 Testing the Application

After launching the application:

### Farmer Workflow

1. Login as a Farmer.
2. Open the Farmer Dashboard.
3. Submit an agricultural insurance claim.
4. Enter the required claim information.
5. Submit the claim.
6. Track the claim status.

### Insurance Officer Workflow

1. Login as an Insurance Officer.
2. Open the Officer Dashboard.
3. View submitted claims.
4. Review the available claim information.
5. Validate the claim.
6. Update the claim status.

### Government Workflow

1. Login as a Government Administrator.
2. Open the Government Dashboard.
3. View claim statistics.
4. Monitor claim activity.
5. Explore the available analytics.

---

## 🔄 Claim Processing Workflow

```text
Farmer
   │
   ▼
Submit Insurance Claim
   │
   ▼
Claim Recorded
   │
   ▼
Insurance Officer Review
   │
   ├───────────────┐
   │               │
   ▼               ▼
Approve          Reject
   │               │
   └───────┬───────┘
           ▼
      Status Updated
           │
           ▼
     Farmer Tracking

           +
           │
           ▼
Government Monitoring
```

---

## 🤖 Future AI/ML Integration

The current repository is a frontend prototype. The system can be extended with machine-learning components for automated claim validation.

### 1. Crop Damage Detection

Analyze crop images using computer vision to estimate the extent of crop damage.

### 2. Weather-Based Validation

Use historical and real-time weather information to determine whether reported crop damage is consistent with weather conditions.

### 3. Risk Scoring

Generate a claim risk score using factors such as:

* Crop type
* Location
* Reported damage
* Weather conditions
* Historical claims
* Claim frequency

### 4. Fraud Detection

Identify suspicious or inconsistent claims using machine-learning-based anomaly detection.

### 5. Satellite Image Analysis

Integrate satellite imagery to monitor crop health and detect large-scale agricultural damage.

---

## 📊 Potential AI Pipeline

```text
Farmer Claim
     │
     ▼
Claim Information
     │
     ├───────────────┐
     ▼               ▼
Crop Image       Weather Data
     │               │
     └───────┬───────┘
             ▼
        Feature Extraction
             │
             ▼
       ML / AI Model
             │
             ▼
       Risk / Damage Score
             │
       ┌─────┼─────┐
       ▼     ▼     ▼
    Approve Review Reject
             │
             ▼
       Officer Decision
```

---

## 🔒 Security & Development Note

This project is currently a **prototype intended for academic, hackathon, and demonstration purposes**.

The current demo uses browser `LocalStorage` for storing demonstration data. It should not be used for storing sensitive information in a production environment.

A production version should implement:

* Secure authentication
* Backend APIs
* Database-based storage
* Role-based authorization
* Input validation and sanitization
* Secure session management
* Encryption of sensitive information
* Proper access control

---


## 🔮 Future Enhancements

* [ ] Integrate a secure backend
* [ ] Add PostgreSQL/Supabase database
* [ ] Implement production authentication
* [ ] Integrate satellite imagery
* [ ] Integrate weather APIs
* [ ] Develop crop damage detection model
* [ ] Add ML-based fraud detection
* [ ] Implement automated claim risk scoring
* [ ] Add multilingual support
* [ ] Improve chatbot capabilities
* [ ] Add real-time notifications
* [ ] Deploy complete full-stack architecture

---

## 🎯 Project Objectives

* Digitize agricultural insurance claim workflows
* Reduce dependency on manual claim processing
* Improve transparency for farmers
* Help insurance officers manage claims efficiently
* Provide government authorities with better monitoring and analytics
* Establish a foundation for AI-powered agricultural insurance validation

---

## 👩‍💻 Contributors

**Nelakuditi Varshini**

* Frontend development
* Application workflow
* Claim-management interface
* Integration and testing

---

## 📄 License

This project is licensed under the **MIT License**.

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.
