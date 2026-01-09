# Jenkins CI/CD Pipeline (GitLab)

This repository serves as a **showcase** for a Jenkins-based CI/CD pipeline.

 **Source of truth**:  
The actual pipeline, code, and Jenkinsfile are maintained in **GitLab**.

---

##  Main Repository (GitLab)

 **Jenkins pipeline & source code**  

https://gitlab.com/coffeezon3/jenkins-gitlab-webhook-ci.git

---

##  Implemented CI/CD Features

- Automatic Maven patch version increment
- Java build & test execution
- Docker image build with dynamic version tagging
- Push to private Docker Hub repository
- Git version update committed back to repository
- CI loop prevention using `[skip ci]`

---

##  Technologies

- Jenkins
- GitLab
- Docker
- Maven
- Java

---

##  Notes

This GitHub repository is intentionally **read-only** and used for documentation and demonstration purposes.
# jenkins-gitlab-ci-cd-pipeline
Dynamically increment Application version in jenkins pipeline
## CI/CD Pipeline (Jenkins)

### Features
- Automatic patch version increment (Maven)
- Java build & artifact cleanup
- Docker image build with dynamic version tag
- Push to private Docker Hub repository
- Git version update commit back to repository
- CI loop prevention using [skip ci]

### Technologies
- Jenkins
- GitLab
- Docker
- Maven
- Java

### Pipeline Flow
1. Increment version
2. Build application
3. Build Docker image
4. Push image
5. Deploy (placeholder)
6. Commit version update (skip CI)
