# Jenkins Remoting Project 🚀

A hands-on DevOps mini-project where I successfully configured and connected a Jenkins Remoting Agent to a Jenkins controller (master) using inbound communication.

---

## 📌 Project Objective

To understand and implement Jenkins distributed architecture using **custom-built remoting agents**, enabling remote execution of jobs and pipelines.

---

## 🔧 Tools & Technologies

- 🛠️ Jenkins (v2.492.1)
- ☕ Java 17
- 📦 Apache Maven
- 🖥️ VS Code (Extensions: GitLens, Maven for Java, Java Pack)
- 🐙 Git & GitHub

---

## 🧠 Skills Demonstrated

- Jenkins master-agent architecture
- Manual inbound agent setup using JNLP
- Building the Jenkins Remoting project with Maven
- Command-line based system configuration and troubleshooting
- Git version control & GitHub repository management

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

git clone https://github.com/anitha05762/jenkins-remoting-project.git 


cd jenkins-remoting-project


### 2. Build the Project with Maven
mvn clean install


### 3. Download and Connect the Agent via Jenkins
Go to Manage Jenkins → Nodes → New Node

Create a node with: "Launch agent by connecting it to the controller"
Jenkins will generate a command like this:
java -jar agent.jar -url http://<your-jenkins-url> -secret <secret> -name <agent-name> -workDir "C:/Users/xidan/jenkins-agent"
Run the above command in your terminal to connect the agent

Jenkins will generate a command like this:


java -jar agent.jar -url http://<your-jenkins-url> -secret <secret> -name <agent-name> -workDir "C:/Users/xidan/jenkins-agent"
Run the above command in your terminal to connect the agent.  


### Built By

Anitha Srinithi


Final Year B.E. CSE (AIML) Student


LinkedIn : https://www.linkedin.com/in/anitha-srinithi-/


### 🔖 Tags
#DevOps #Jenkins #Java #Maven #VSCode #CI/CD #GitHubProject


### 📄 License
This project is for educational use and learning purposes only.
© 2025 Anitha Srinithi



