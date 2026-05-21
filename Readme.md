# Hands-on Assignment: Containers with Docker (Act 2)

A simple Python Flask web application that utilizes a Redis database cache to count the number of page views. Both components use Docker to run.

---

## Execution Steps

Follow these step-by-step instructions to build, run, and verify the containerized application.

### Step 1: Clone the Repository
```bash
git clone https://github.com/abishektony/ITCS6190-Act1.git
cd ITCS6190-Act1
```

### Step 2: Build and Run in docker
```bash
docker compose up --build
```

### Step 3: Visit the localhost
[https://localhost:8000](http://localhost:8000)

Reload the page to see the counter increase 

### What I Learned

I learned that containerization simplifies the deployment process by packaging code and dependencies together, making applications much easier to run. Using Docker we can launch an entire multi-container stack with a single command, without manually configuring the local network addresses. I also learned how easily we can reuse pre-built database containers, such as Redis or PostgreSQL, in isolated environments without risking conflicts with other projects on my local machine.