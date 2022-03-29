# Kubernetes Project With Google Cloud Platform Components

The project has two applications are running with one MongoDB database and Kubernetes services. 

The **student record** application allows user to access the student record from request student_id. The application  running with  Node.js + MongoDB + Google Kubernetes Engine (GKE).

The **bookstore** application offers the various operations to user like Add, Update, Delete book in bookstore database and access the books list and information about the particular book in MongoDB database. The application running on the Python Flask Web Framework + REST API + MongoDB + Google Kubernetes Engine (GKE).

**Sample Output**



**Both applications have using the following services to run over the Google Kubernetes Engine.**

**Pod:** To boot the application container into the cluster.

**Service:** To access the application from outside the cluster with External-IP address.

**Persistence Volume (PV):** To store the data in MongoDB database in the cluster. 

**ConfigMap:** To store the MongoDB database service URL address to avoid configure the pod again incase the MongoDB database service is down or restarts with a different service pod.  

**Ingress:** To expose the both applications over the internet with single domain name but with different path. 

**How to run two applications with GKE cluster.**

Follow the Configuration steps to host two applications on cluster here

Overview of the project instructions on Google slides. 
