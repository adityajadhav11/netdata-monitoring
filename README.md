# 🚀 Task 7 - Monitor System Resources Using Netdata

## 📌 Objective
The goal of this task is to monitor system and application performance metrics in real-time using **Netdata**, a lightweight and powerful open-source monitoring tool. The setup was done using **Docker**, and the dashboard was accessed via a browser.

---

## 🛠️ Tools & Technologies
- 🐳 Docker
- 📈 Netdata
- 💻 VS Code
- 🖼️ Netdata Web Dashboard

---

## 🔧 Setup & Installation

### ✅ Step 1: Run Netdata Container via Docker
```bash
docker run -d --name=netdata -p 19999:19999 --cap-add=SYS_PTRACE --security-opt apparmor=unconfined netdata/netdata

## Key Learnings
   - Understood how to monitor real-time performance using Netdata.

   - Explored system metrics like CPU, RAM, Disk, and Docker containers.

   - Learned how to deploy monitoring tools using Docker.

   - Got hands-on with logs inside a Docker container.
