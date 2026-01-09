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
