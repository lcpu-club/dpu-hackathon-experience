---
theme: slidev-theme-lcpu
title: Experience at NVIDIA DPU Hackathon
zoom: 0.8
---

# <span style="font-weight: initial">LCPU at </span><br>NVIDIA DPU Hackathon

<br> DPU-Accelerated Zero-Overhead Sidecar for Cloud-Native Observability

---
zoom: 1.2
---

# Background

<v-clicks>

- Network Observability and Memory Tracing in Cloud-Native Environments is Difficult
- Growing Number of VMs in CLab
  - High Performance Firewall
  - Track Resource Usages across Cluster
  - Profile Network Bottlenecks
  - Detect Malware in Guest
- Next-gen CLab
  - RDMA Network
  - Cloud on Kubernetes
</v-clicks>

---
zoom: 1.2
---

# Goals

<v-clicks>

- Transparent: Non-intrusive Tracing
- Low-overhead: Offload Computations to DPU
- Cloud-Native: Profile across Microservices, Containers, Pods
- Speedy: Collect Metrics in Near-Realtime 
- DMA: Detect Defects in Guest Applications

</v-clicks>

---
zoom: 1.2
---

# Experience

<v-clicks>

- Cloud Access to BlueField DPUs
- Tutorials from NVIDIA 
- Guidance from NVIDIA Engineers
- Cooperated within the Team

</v-clicks>

---
zoom: 1.2
layout: two-cols-header
---

# Experience: Debugging with Docs

::left::

![](/image.png)

::right::

![](/2.png)

<p style="text-align: center"> !!CRITICAL SETTING MISSING!!<br>in documentation </p>

---
zoom: 1.2
---

# Future Goals

<v-clicks>

- Integrate with K8S
- User-friendly Dashboard (Frontend)
- Leverage DPA Processors on DPU

</v-clicks>

---
zoom: 1.2
---

<Video src="/demo.mp4" caption="Demo Time" />

---
layout: center
---

<span class="text-3rem bold mx-auto my-auto" v-mark.underline>Thanks for Listening!</span>

---
layout: end
---
