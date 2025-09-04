# Hazelcast EX-02

This repository contains the solution for **Hazelcast Exercise 02 (HAZELCAST-EX-02)** from i2i Academy.

## 🚀 Exercise Description
The goal of this exercise is to **run Hazelcast** and **Hazelcast Management Center** containers using Docker.

## 🛠️ Steps to Run

### 1. Pull Hazelcast
```bash
docker pull hazelcast/hazelcast:latest
docker run hazelcast/hazelcast:latest
```
## 2. Pull Hazelcast Management Center
```bash
docker pull hazelcast/management-center:latest
docker run --rm -p 8080:8080 hazelcast/management-center:latest
```

<img width="1512" height="674" alt="Screenshot 2025-09-04 at 10 10 33" src="https://github.com/user-attachments/assets/f3b020f1-2091-42ac-a3df-aa65626e983b" />
<img width="1506" height="498" alt="Screenshot 2025-09-04 at 10 17 47" src="https://github.com/user-attachments/assets/aeecac5d-cccd-4935-8b01-923ee1f16ce0" />
