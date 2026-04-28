# Hi, I'm Yige (Eric) Wang 👋
> _Open to Co-op / New Grad opportunities — Cloud DevOps · HPC / AI Infrastructure · Full-Stack._

> Backend & Infrastructure Engineer building scalable, cloud-native systems —
> with hands-on experience in **distributed training on multi-GPU HPC clusters**.

🎓 M.S. Information Systems @ [Northeastern University](https://www.northeastern.edu) (CSYE)<br>
🔭 Currently benchmarking parallel ML training (DDP / FSDP) on V100 SLURM clusters<br>
🚀 Open to **2026 Co-op / New Grad** roles in Cloud DevOps, HPC / AI Infrastructure, and Full-Stack Engineering<br>
📍 Boston, MA · Open to relocation

---

## 🔍 About Me

- 🛠️ **Cloud-native backend** — Spring Boot microservices on AWS, infrastructure-as-code with Terraform, automated CI/CD
- ⚡ **HPC & distributed systems** — DDP / FSDP training on multi-GPU clusters (V100, NCCL, SLURM); profiling communication overhead and scaling efficiency
- 🌐 **Full-stack delivery** — shipped end-to-end systems with Spring Boot + Vue/React, MySQL/PostgreSQL, MinIO, RBAC
- 🧠 **What I care about** — reliability, observability, and performance — building systems that are *fast, correct, and easy to operate*


---

## 📂 Featured Projects

- **[Nano-GPT-HPC](https://github.com/CSYE7105-nanoGPT-HPC/Nano-GPT-HPC)**<br>
  _Tech Stack:_ Python, PyTorch, DDP/FSDP, NCCL, SLURM, CUDA, V100, OpenWebText<br>
  _Highlights:_
  - Parallelized OpenWebText preprocessing with Python multiprocessing and GPT-2 BPE tokenization; tuned `imap` chunk size to reduce 8-worker tokenization time from 143.97s to 106.24s.
  - Scaled 51.5M-parameter nanoGPT training on Northeastern Explorer V100-SXM2 GPUs using PyTorch DDP, mixed precision, `DDP.no_sync()`, `torchrun`, and SLURM.
  - Increased training throughput from 113,945 to 451,823 tok/s on 4 GPUs, achieving 3.97x speedup and 99.1% scaling efficiency; benchmarked FSDP `FULL_SHARD` and NCCL NVLink/P2P vs. SHM transport.

- **[native cloud app](https://github.com/csye6225YigeWang)**  
  _Tech Stack:_ AWS, Terraform, GitHub CI/CD pipeline, SpringBoot   
  _Highlights:_  
  - build a fully automated GitHub Action pipeline from testing, packaging and aws deployment
  - using AWS Terraform to manage multi-AZ AWS resourses including ec2, LB, KMS, S3, RDS and VPC with leasest IAM privilage
  - writing a efficient Lambda funtion that recieving AWS SMS message and sending email to user

- **[Formula 1 Predict](https://github.com/dataSciF/6105DataSci)**  
  _Tech Stack:_ Python, PyMC, MCMC, Hierarchical Bayesian Modeling  
  _Highlights:_
  - Collected, cleaned, and analyzed historical race data; reconstructed structured DataFrames and formulated likelihood functions for Bayesian modeling.
  - Built and trained a three-layer hierarchical Bayesian model incorporating five key performance factors.
  - Applied Monte Carlo simulations to evaluate predictive outcomes (mean, mode, win probability) across 24 races over the past two seasons.

- **[Equipment & Assignment Management Platform](https://github.com/YigeWang1221/Equipments-Assignment)**  
  _Tech Stack:_ Spring Boot, Vue.js, MySQL, MinIO, Rich Text Editor  
  _Highlights:_
  - Built a full-stack equipment and assignment management system with role-based access control.
  - Implemented file/multi-media upload and rich-text content management using MinIO.

---

## 🛠️ Tech Stack

**Languages**
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?logo=cplusplus&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white)

**Backend & Web**
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?logo=springsecurity&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-005571)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
[Vue.js]

**Cloud & DevOps**
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)

**HPC & Parallel ML**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?logo=nvidia&logoColor=white)
![SLURM](https://img.shields.io/badge/SLURM-2C3E50)
![NCCL](https://img.shields.io/badge/NCCL-76B900?logo=nvidia&logoColor=white)
![DDP/FSDP](https://img.shields.io/badge/DDP%20%2F%20FSDP-EE4C2C?logo=pytorch&logoColor=white)

**Databases & Storage**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?logo=minio&logoColor=white)

---

## 📫 Contact

- 💼 **LinkedIn** — [linkedin.com/in/yigewang1221](https://www.linkedin.com/in/yigewang1221/)
- 📧 **Email** — wang.yige@northeastern.edu
- 🌐 **GitHub** — you're already here :)

---

