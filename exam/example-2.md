# DevOps with SRE MCQ

## Part 1. Questions on command execution

### Question 1

You need to revert the last commit in your local Git repository. Which sequence(s) of commands accomplish(es) this?

- A: git revert HEAD
- B: git reset --hard HEAD~1
- C: git reset HEAD^
   git commit -m “revert last commit”
- D: git log
   git reset --hard <commit_id>

### Question 2

Which command(s) create(s) a new branch and switch(es) to it?

- A: git branch new-branch
- B: git checkout -b new-branch
- C: git switch -c new-branch
- D: git new-branch

### Question 3

You have a running Docker container named `my_container`. Which command(s) allow you to copy a file `data.txt` from your host to the container's `/app` directory?

- A: docker cp data.txt my_container:/app
- B: docker copy data.txt my_container:/app
- C: docker transfer data.txt my_container:/app
- D: docker move data.txt my_container:/app

### Question 4

You are managing a Kubernetes cluster and need to update an existing deployment's image. Which command(s) achieve(s) this?

- A: kubectl set image deployment/myapp myapp=newimage:v2
- B: kubectl rollout restart deployment/myapp
- C: kubectl edit deployment myapp
- D: kubectl apply -f deployment.yaml

### Question 5

Which command(s) run(s) a web application accessible on `http://localhost:8000` from your host where you run this container (where “myapp” is an image built using this `Dockerfile`)? (1 answer)

- A: `docker run myapp`
- B: `docker run -p 8000:5000 myapp`
- C: `docker run -p 5000:8000 myapp`
- D: `docker run myapp:latest`

### Question 6

Which command(s) list(s) only running containers?

- A: `docker container ls -a`
- B: `docker ps -a` 
- C: `docker container ls`
- D: `docker ps` 

### Question 7

You have a `docker-compose.yml` file for a multi-container application. Which command(s) build(s) and start(s) the containers defined in the file?

- A: docker-compose up --build
- B: docker-compose start
- C: docker-compose run
- D: docker-compose execute

### Question 8

Which command(s) display(s) the current configuration of a Kubernetes cluster?

- A: kubectl config view
- B: kubectl cluster-info
- C: kubectl get config
- D: kubectl info

### Question 9

You have a Docker image tagged `myimage:latest`. Which command(s) tag(s) this image for a repository `myrepo/myimage` with version `1.0`?

- A: docker tag myimage:latest myrepo/myimage:1.0
- B: docker commit myimage:latest myrepo/myimage:1.0
- C: docker rename myimage:latest myrepo/myimage:1.0
- D: docker label myimage:latest myrepo/myimage:1.0

### Question 10

In Ansible, which command(s) test(s) a playbook's syntax?

- A: ansible-playbook --syntax-check playbook.yml
- B: ansible-playbook --check playbook.yml
- C: ansible-playbook --test playbook.yml
- D: ansible-playbook --validate playbook.yml

## Part 2. Questions on knowledge of theory

### Question 11

What is the primary purpose of Continuous Integration in DevOps?

- A: To automate the deployment process
- B: To integrate different development environments
- C: To merge all developers' working copies to a shared mainline several times a day
- D: To continuously deliver the application to the production environment

### Question 12

What is a main characteristic of a Microservices Architecture?

- A: A single, unified codebase for all services
- B: Large, monolithic applications
- C: Small, independently deployable services
- D: Services that are tightly coupled and dependent on each other

### Question 13

In the context of cloud computing, what does IaaS stand for?

- A: Integrated as a Service
- B: Infrastructure as a Service
- C: Internet as a Service
- D: Information as a Service

### Question 14

What is a primary benefit of implementing Infrastructure as Code (IaC)?

- A: Reducing the need for manual documentation
- B: Increasing the physical security of data centers
- C: Automating the provisioning and management of infrastructure
- D: Enhancing the graphical interface of management tools

### Question 15

What is the main role of a Site Reliability Engineer (SRE)?

- A: To ensure that the website's design is appealing
- B: To manage the company's social media accounts
- C: To maintain high availability and reliability of software services
- D: To develop new software features and products
