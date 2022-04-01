# Kubernetes Project With Google Cloud Platform Components

The project has two applications are running with one MongoDB database and Kubernetes services. 

The **student record** application allows user to access the student record from request student_id. The application  running with  Node.js + MongoDB + Google Kubernetes Engine (GKE).

The **bookstore** application offers the various operations to user like Add, Update, Delete book in bookstore database and access the books list and information about the particular book in MongoDB database. The application running on the Python Flask Web Framework + REST API + MongoDB + Google Kubernetes Engine (GKE).

**Sample Output**

`Access the student record application`

![image](https://user-images.githubusercontent.com/35762778/161215729-1bd733b1-f687-47d4-8a21-c5ff1b02638d.png)

`Get book list from MongoDB database`

![image](https://user-images.githubusercontent.com/35762778/161216238-f9844dc5-a147-4e9a-81df-b4724d6514af.png)

`Add book to database with REST API`

![image](https://user-images.githubusercontent.com/35762778/161216708-96c0e434-e42c-4fc3-b64f-11abc4630a78.png)

`Access the student record where TLS certificate and keys is applied`

![image](https://user-images.githubusercontent.com/35762778/161216957-3050c156-e69a-4950-a54b-fb7db34f9cd8.png)



**Both applications have using the following services to run over the Google Kubernetes Engine.**

**Pod:** To boot the application container into the cluster.

**Service:** To access the application from outside the cluster with External-IP address.

**Persistence Volume (PV):** To store the data in MongoDB database in the cluster. 

**ConfigMap:** To store the MongoDB database service URL address to avoid configure the pod again incase the MongoDB database service is down or restarts with a different service pod.  

**Ingress:** To expose the both applications over the internet with single domain name but with different path.

**TLS (Transport Layer Security):** To encrypt the data while transporting between pod and ingress for secure connection.

**How to run two applications with GKE cluster.**

<details>
  <summary>Follow the Configuration steps to host two applications on GKE cluster</summary>
  
  [Configuration Document]

</details>

<details>
  <summary>Overview of the project instructions on Google slides</summary>
  
  [Google slides presentation](https://docs.google.com/presentation/d/1ZvfArz_3UWtNvCicByJx-psaJ6lAFNbDKZoARx6mxGE/edit?usp=sharing)
</details>


