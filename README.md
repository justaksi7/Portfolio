<a id="-inhaltsverzeichnis"></a>
# 👋 Hello, I'm Aksel Kenanov!

I am a master's student in my first semester at the Technical University of Darmstadt with a focus on *Software Engineering* and *Cloud Computing*.

I love solving technical problems creatively and constantly discovering new tools & technologies.

---

## 📑 Table of Contents
### 🏢 Internship: SAP Payments Bridge
* [🏢 Internship](#-praxisphase)
### 🎓 Bachelor's Thesis – Evaluation of OpenTelemetry Overhead in AWS Lambda
* [🎓 Bachelor's Thesis](#-bachelorarbeit)

### 🧰 Technologies & Tools

* [💻 Programming Languages](#-programmiersprachen)
* [🌐 Web & Application Development](#-web--application-development)
* [⚙️ C / C++ Development](#️-c--c-development)
* [☕ Java Development](#-java-development)
* [🐍 Python & Machine Learning](#-python--machine-learning)
* [🐘 PHP Development](#-php-development)
* [🗄️ Databases](#️-datenbanken)
* [☁️ Cloud & DevOps](#️-cloud--devops)
* [🧪 Testing & Quality Assurance](#-testing--qualitätssicherung)
* [📊 Observability](#-observability)
* [🔄 Agile Software Development](#-agile-softwareentwicklung)


### 💼 Projects

* [📊 Event Planner Web Application](#-event-planner-webanwendung)
* [📱 Booking Management System](#-buchungsverwaltungssystem)
* [✈️ Travel Agency Simulation](#️-reisebüro-simulation)
* [💼 Job Portal](#-job-portal)
* [🌍 Travel Planning Web Application](#-reiseplanung-webanwendung)
* [🖥️ Operating Systems Practice Site](#️-übungsseite-für-betriebssysteme)
* [☕ Java Spring Boot Application – Development & Bug Fixes](#-java-spring-boot-anwendung--weiterentwicklung--bug-fixes)
* [🤖 Artificial Intelligence & Machine Learning](#-künstliche-intelligenz--machine-learning)

### 📫 More Information

* [📫 Contact & Profiles](#-kontakt--profile)

---
---

<a id="-praxisphase"></a>
# 🏢 Internship

## 🏗️ SAP Payments Bridge

> As part of my internship, a resilient, event-driven microservice architecture was developed for processing SAP payments. The focus was on fault tolerance, reliable message processing, and observability.

### 🔗 Repository

[Repository](https://github.com/justaksi7/b2b-sap-payment-bridge)

### 🛠️ Technologies & Tools

**AWS** · **AWS Lambda** · **Amazon SQS** · **Amazon RDS** · **Amazon DynamoDB** · **AWS X-Ray** · **Amazon CloudWatch** · **OpenTelemetry** · **REST APIs** · **Microservices**

### 🏛️ Architecture

- Serverless microservice architecture
- Event-driven architecture
- REST APIs
- Asynchronous communication via **Amazon SQS**
- Persistence with **Amazon RDS**
- Outbox pattern
- Worker-based processing
- Integration with SAP
- Webhook-based status updates

### 🛡️ Resilience & Fault Tolerance

- Retry mechanisms with **exponential backoff**
- **Dead Letter Queues (DLQ)**
- Circuit breaker pattern
- Half-open phase for controlled recovery
- Protection against duplicate processing of payments
- Reliable and fault-tolerant message processing
- State-based processing of payments

### 📊 Observability

- **OpenTelemetry**
- **AWS X-Ray**
- **Amazon CloudWatch**
- Distributed tracing
- Correlation IDs
- Logging
- Metrics
- Monitoring
- Queue & DLQ monitoring

### 👨‍💻 Role

Cloud Solution Architect during the internship.

### 🖼️ Screenshots

<img src="images/praxisphase/architecture-diagram.png" alt="Internship Screenshot" width="600">

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)

---
---
<a id="-bachelorarbeit"></a>
# 🎓 Bachelor's Thesis

## 📊 Evaluation of OpenTelemetry Overhead in AWS Lambda

> For my bachelor's thesis, the performance and resource overhead introduced by OpenTelemetry instrumentation in AWS Lambda workloads was investigated. Lambda functions in **Java, Node.js and Python** were executed both without instrumentation and with OpenTelemetry and compared.

### 🔗 Repository

[📂 GitHub Repository](https://github.com/justaksi7/opentelemetry-overhead-java-nodejs-python)

### 🛠️ Technologies & Tools

**AWS Lambda** · **Java** · **Node.js** · **Python** · **OpenTelemetry** · **Amazon DynamoDB** · **AWS CloudWatch** · **HTTP** · **GitHub**

### 🎯 Objective

Investigate the impact of OpenTelemetry instrumentation on the performance and resource consumption of serverless applications.

The comparison included:

* Uninstrumented Lambda functions (**baseline**)
* Lambda functions instrumented with OpenTelemetry
* Three programming languages: **Java, Node.js and Python**
* **Cold starts and warm starts**

### 🧪 Microbenchmarks

Five different access scenarios were evaluated:

* **Lambda-to-Lambda invocation**

  * Asynchronous invocation of a second Lambda function

* **HTTP GET request**

  * Outgoing HTTP communication

* **HTTP POST request**

  * Outgoing HTTP communication with request body

* **DynamoDB read**

  * Reading a single item from Amazon DynamoDB

* **DynamoDB write**

  * Writing a single item to Amazon DynamoDB

These cover Lambda invocations, HTTP communication, and database access within an AWS environment.

### 📏 Metrics Measured

* **Duration**
* **Init Duration**
* **Max Memory Used**
* Relative OpenTelemetry overhead in percent
* Absolute measurements
* Comparison of cold and warm starts

Measurements were conducted between **02.03.2026 and 07.03.2026**.

### 📈 Results

The evaluation shows significant differences between the programming languages and the various execution scenarios. Detailed results are available in the [📂 GitHub Repository](https://github.com/justaksi7/opentelemetry-overhead-java-nodejs-python).

### 👨‍🎓 Role

**Author and developer of the bachelor's thesis**


⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)


---

# 🧰 Technologies & Tools

<a id="-programmiersprachen"></a>
## 💻 Programming Languages

**C / C++** · **Python** · **Java** · **JavaScript / TypeScript** · **SQL** · **Dart** · **PHP**

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)

---

<a id="-web--application-development"></a>
## 🌐 Web & Application Development

### Frontend

**React** · **TypeScript** · **JavaScript** · **Tailwind CSS**

### Backend

**Node.js** · **Express** · **PHP**

### Other Technologies

**REST APIs** · **Responsive Web Design** · **ORM** · **API Integration**

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)

---

<a id="️-c--c-development"></a>
## ⚙️ C / C++ Development

* Business applications with **Qt**
* 3D computer graphics with **Qt 3D**
* Embedded programming with **Raspberry Pi Pico**
* Multithreading
* Threads
* Mutexes
* Semaphores

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)

---

<a id="-java-development"></a>
## ☕ Java Development

* **Java**
* **Spring Boot**
* Business applications
* **Mustache**
* CI/CD with **GitLab Pipelines**
* Unit testing
* Software metrics with **SonarQube**

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)

---

<a id="-python--machine-learning"></a>
## 🐍 Python & Machine Learning

### Python

**Python** · **NumPy** · **Pandas** · **Matplotlib** · **Scikit-learn**

### Machine Learning

* Feature engineering
* Classification
* Regression
* Unsupervised learning
* KNN
* PCA

### Deep Learning

* Artificial neural networks
* Convolutional neural networks
* **Keras**
* **TensorFlow**

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)

---

<a id="-php-development"></a>
## 🐘 PHP Development

* Backend development
* PHP without a framework

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)

---

<a id="️-datenbanken"></a>
## 🗄️ Databases

* **PostgreSQL**
* **DynamoDB**
* **Drizzle ORM**
* **pgAdmin**
* **SAP PowerDesigner**
* Database design
* Database administration
* ORM & migrations

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)

---

<a id="️-cloud--devops"></a>
## ☁️ Cloud & DevOps

### Cloud

* **AWS**
* Serverless
* Cloud deployment

### Software Architecture

* Microservices
* REST APIs
* Event-driven architecture

### DevOps

* **Git**
* **GitHub**
* **GitLab**
* **Bitbucket**
* **Docker**
* **Postman**
* CI/CD
* SonarQube

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)

---

<a id="-testing--qualitätssicherung"></a>
## 🧪 Testing & Quality Assurance

* Unit testing
* Integration testing
* API testing
* Performance testing
* Load testing
* Test automation
* Software metrics
* SonarQube

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)

---

<a id="-observability"></a>
## 📊 Observability

* **OpenTelemetry**
* **AWS X-Ray**
* **Amazon CloudWatch**
* Logging
* Metrics
* Distributed tracing
* Monitoring

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)

---

<a id="-agile-softwareentwicklung"></a>
## 🔄 Agile Software Development

* **SCRUM**
* SCRUM boards
* Kanban boards
* Requirements engineering
* User research
* Teamwork in software projects

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)

---

# 💼 Projects

<a id="-event-planner-webanwendung"></a>
## 📊 Event Planner Web Application

[🔗 Repository](https://github.com/justaksi7/fwe-event-planner)

> A web application for event planning, inspired by Calendly. The site was initially online (AWS) but was taken down due to costs.

### 🛠️ Stack

**Node.js** · **Express** · **TypeScript** · **React** · **ShadCN** · **PostgreSQL** · **Drizzle ORM** · **Docker** · **AWS**

### ✨ Features

* Express server
* PostgreSQL Docker image
* ORM and migrations with Drizzle ORM
* Validation with Zod
* React with TypeScript
* ShadCN UI
* AWS deployment

### 👨‍💻 Role

Developer in a **SCRUM team of 5 people**

### 🖼️ Screenshots

<img src="images/fwe-event-planner/1.png" alt="Event Planner Screenshot 1" width="600">

<img src="images/fwe-event-planner/2.png" alt="Event Planner Screenshot 2" width="600">

<img src="images/fwe-event-planner/3.png" alt="Event Planner Screenshot 3" width="600">

<img src="images/fwe-event-planner/4.png" alt="Event Planner Screenshot 4" width="600">

<img src="images/fwe-event-planner/5.png" alt="Event Planner Screenshot 5" width="600">

<img src="images/fwe-event-planner/6.png" alt="Event Planner Screenshot 6" width="600">

### 🎥 Demo

<video width="600" controls>
  <source src="images/fwe-event-planner/fwe-event-planner-demo.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

[Video Demo](images/fwe-event-planner/fwe-event-planner-demo.mp4)

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)

---

<a id="-buchungsverwaltungssystem"></a>
## 📱 Booking Management System

> A cross-platform app for booking and managing events with multiple users.

### 🛠️ Stack

**Flutter (Dart)** · **PostgreSQL**

### ✨ Features

* Responsive design
* UX / UI
* Requirements engineering
* User research with real users

### 👨‍💻 Role

Developer in a **SCRUM team of 4 people**

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)

---

<a id="️-reisebüro-simulation"></a>
## ✈️ Travel Agency Simulation

> A C++ desktop application using Qt.

### 🛠️ Stack

**C++** · **Qt** · Mocked JSON database

### ✨ Features

* Graph algorithms
* Avoidance of date conflicts
* Desktop GUI

### 👨‍💻 Role

**Solo project**

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)

---

<a id="-job-portal"></a>
## 💼 Job Portal

> A job portal simulation focusing on the frontend.

### 🛠️ Stack

**React** · **JavaScript** · **Tailwind CSS** · Mocked JSON server

### ✨ Features

* JSON server parsing
* Various React hooks
* React-Toastify
* Responsive frontend

### 👨‍💻 Role

**Solo project**

### 🖼️ Screenshots

<img src="images/React-Jobs/1.png" alt="Job Portal Screenshot 1" width="600">

<img src="images/React-Jobs/2.png" alt="Job Portal Screenshot 2" width="600">

<img src="images/React-Jobs/3.png" alt="Job Portal Screenshot 3" width="600">

<img src="images/React-Jobs/4.png" alt="Job Portal Screenshot 4" width="600">

<img src="images/React-Jobs/5.png" alt="Job Portal Screenshot 5" width="600">

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)

---

<a id="-reiseplanung-webanwendung"></a>
## 🌍 Travel Planning Web Application

[🔗 Repository](https://github.com/justaksi7/fwe-ss-25-1118200)

> A travel planning web app with trips, destinations and weather forecasts.

### 🛠️ Stack

**Node.js** · **Express** · **TypeScript** · **React** · **Tailwind CSS** · **PostgreSQL** · **Drizzle ORM**

### ✨ Features

* Express server
* PostgreSQL Docker image
* ORM and migrations with Drizzle ORM
* Validation with Zod
* External REST API for weather forecasts
* React frontend
* Tailwind CSS

### 👨‍💻 Role

**Solo project**

### 🖼️ Screenshots

<img src="images/react-travel-agency/1.png" alt="Travel Agency Screenshot 1" width="600">

<img src="images/react-travel-agency/2.png" alt="Travel Agency Screenshot 2" width="600">

### 🎥 Demo

<video width="600" controls>
  <source src="images/react-travel-agency/react-travel-agency-demo.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

[Video Demo](images/react-travel-agency/react-travel-agency-demo.mp4)

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)

---

<a id="️-übungsseite-für-betriebssysteme"></a>
## 🖥️ Operating Systems Practice Site

[🔗 Repository](https://github.com/justaksi7/pse-react)

> An interactive React application to practice various algorithms from the operating systems domain, e.g., Banker's algorithm, schedulers, and deadlock detection. The web application is actually deployed by Hochschule Darmstadt so that new students can learn interactively for the operating systems lecture.

### 🛠️ Stack

**React** · **TypeScript** · **Tailwind CSS** · **PostgreSQL**

### ✨ Features

* Interactive scheduling algorithms
* Banker's algorithm
* Schedulers
* Deadlock detection
* Tokens for specific tasks
* PostgreSQL leaderboard

### 👨‍💻 Role

Developer in a **SCRUM team of 5 people**

### 🖼️ Screenshots

<img src="images/react-trainer/1.png" alt="Operating Systems Trainer Screenshot 1" width="600">

<img src="images/react-trainer/2.png" alt="Operating Systems Trainer Screenshot 2" width="600">

<img src="images/react-trainer/3.png" alt="Operating Systems Trainer Screenshot 3" width="600">

<img src="images/react-trainer/4.png" alt="Operating Systems Trainer Screenshot 4" width="600">

<img src="images/react-trainer/5.png" alt="Operating Systems Trainer Screenshot 5" width="600">

<img src="images/react-trainer/6.png" alt="Operating Systems Trainer Screenshot 6" width="600">

<img src="images/react-trainer/7.png" alt="Operating Systems Trainer Screenshot 7" width="600">

### 🎥 Demo

<video width="600" controls>
  <source src="images/react-trainer/react-trainer-demo.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

[Video Demo](images/react-trainer/react-trainer-demo.mp4)

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)

---

<a id="-java-spring-boot-anwendung--weiterentwicklung--bug-fixes"></a>
## ☕ Java Spring Boot Application – Development & Bug Fixes

> A Java web application built with Spring Boot.

### 🛠️ Stack

**Java Spring Boot** · **Mustache** · **Apache Tomcat** · App-internal hash repositories

### ✨ Features

* Internal quasi-database with hash repositories
* Authentication with password validation
* Layouts with Mustache
* CI/CD with GitLab Pipelines
* Unit tests
* Software metrics with SonarQube

### 👨‍💻 Role

Developer in a **SCRUM team of 4 people**

### 🖼️ Screenshots

<img src="images/Java/1.png" alt="Java Spring Boot Screenshot 1" width="600">

<img src="images/Java/2.png" alt="Java Spring Boot Screenshot 2" width="600">

<img src="images/Java/3.png" alt="Java Spring Boot Screenshot 3" width="600">

<img src="images/Java/4.png" alt="Java Spring Boot Screenshot 4" width="600">

<img src="images/Java/5.png" alt="Java Spring Boot Screenshot 5" width="600">

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)

---

<a id="-künstliche-intelligenz--machine-learning"></a>
## 🤖 Artificial Intelligence & Machine Learning

> As part of the “Introduction to Artificial Intelligence” course, Python scripts and applications were developed.

### 🛠️ Stack

**Python** · **Scikit-learn** · **NumPy** · **Matplotlib** · **Pandas** · **Keras** · **TensorFlow**

### 📈 Classification

Prediction of which people survived the Titanic incident using **feature engineering** and **classification**.

### 📊 Regression

Prediction of movie revenues from **The Movie Database** using feature engineering and regression.

### 🧠 Convolutional Neural Networks

Classification of handwritten images using **CNNs** with Keras and TensorFlow.

### 🖼️ CNN Example

<img src="images/CNN/1.png" alt="Convolutional Neural Network Screenshot" width="600">

### 🔍 Unsupervised Learning

* KNN algorithm
* PCA transformation
* Improvement of classification
* Generation of new images with PCA inverse transformation

### 🖼️ Unsupervised Learning Examples

<img src="images/Unsupervised Learning/1.png" alt="Unsupervised Learning Screenshot 1" width="600">

<img src="images/Unsupervised Learning/2.png" alt="Unsupervised Learning Screenshot 2" width="600">

<img src="images/Unsupervised Learning/3.png" alt="Unsupervised Learning Screenshot 3" width="600">

<img src="images/Unsupervised Learning/4.png" alt="Unsupervised Learning Screenshot 4" width="600">

<img src="images/Unsupervised Learning/5.png" alt="Unsupervised Learning Screenshot 5" width="600">

<img src="images/Unsupervised Learning/6.png" alt="Unsupervised Learning Screenshot 6" width="600">

### 👨‍💻 Role

**Solo projects**

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)

---
---

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)
---
# 📫 Contact & Profiles

* 🧑‍💻 [GitHub](https://github.com/justaksi7)
* ✉️ [aksel.kenanov@gmail.com](mailto:aksel.kenanov@gmail.com)

⬆️ [Back to Table of Contents](#-inhaltsverzeichnis)

---

> 📌 *Some projects have no repository links and/or screenshots because they are internal to the university (data protection).* 
>
> 📌 *This profile is still under construction – feedback and suggestions are welcome!*
