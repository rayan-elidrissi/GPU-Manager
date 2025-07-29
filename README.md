# ⚙️ GPU-Manager

**A Lightweight GPU Resource Monitoring & Job Allocation Tool for Deep Learning Workloads**

GPU-Manager provides a modular, Python-based system for real-time monitoring, user-based job scheduling, and resource-aware execution of GPU-intensive tasks. Designed for research labs, ML clusters, or solo practitioners managing multiple GPUs.

> 🧠 _Manage your compute like your models depend on it — because they do._

---

## 🚀 Key Features

| Feature                     | Description                                                       |
|----------------------------|-------------------------------------------------------------------|
| 🎛️ Real-Time Monitoring     | Tracks GPU utilization, memory usage, and active processes        |
| 🧠 Intelligent Job Allocation | Automatically assigns jobs to the best-available GPU(s)           |
| 🔐 User-Aware Queuing       | Enforces fair usage and prevents resource hogging                 |
| 📈 CLI & API Interface      | Flexible tools for scripting and remote orchestration             |
| 🧩 Plugin Architecture       | Add custom logic: job priorities, timeouts, scheduling policies   |
| 🔄 Slurm-Compatible          | Easily integrates into SLURM or shell-based job queues            |

---

## 📦 Repository Structure

```bash
GPU-Manager/
├── gpu_monitor/              # Core NVML-based GPU polling
├── scheduler/                # Queuing logic, user fairness, slot assignment
├── cli/                      # CLI tools for monitoring and submission
├── api/                      # Optional RESTful API for remote control
├── tests/                    # Unit & stress tests
├── config.yaml               # Global config for users, GPUs, policies
├── requirements.txt
└── README.md
