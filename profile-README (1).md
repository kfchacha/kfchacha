<!-- Header -->
<div align="center">

```
██╗  ██╗███████╗███╗   ██╗██╗   ██╗ █████╗ ████████╗████████╗ █████╗
██║ ██╔╝██╔════╝████╗  ██║╚██╗ ██╔╝██╔══██╗╚══██╔══╝╚══██╔══╝██╔══██╗
█████╔╝ █████╗  ██╔██╗ ██║ ╚████╔╝ ███████║   ██║      ██║   ███████║
██╔═██╗ ██╔══╝  ██║╚██╗██║  ╚██╔╝  ██╔══██║   ██║      ██║   ██╔══██║
██║  ██╗███████╗██║ ╚████║   ██║   ██║  ██║   ██║      ██║   ██║  ██║
╚═╝  ╚═╝╚══════╝╚═╝  ╚═══╝   ╚═╝   ╚═╝  ╚═╝   ╚═╝      ╚═╝   ╚═╝  ╚═╝
```

### `Network Engineer → Cloud & DevOps Engineer`

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kenyatta-chacha/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kfchacha)
![Kenya](https://img.shields.io/badge/Nairobi%2C_Kenya_🇰🇪-006600?style=for-the-badge)
![Open to work](https://img.shields.io/badge/Status-Open_to_Work-brightgreen?style=for-the-badge)

</div>

---

```bash
$ ./whoami.sh
```

> Network engineer by training, systems thinker by nature.
> Building production-grade pipelines, observability platforms, and AI systems.
> I debug real incidents, write runbooks, and ship things that actually work.
> Interests span the full stack: **infrastructure → distributed systems → AI/ML**.

```yaml
currently_learning:
  - GitOps with ArgoCD
  - Terraform IaC
  - Advanced PromQL & alerting strategies

background:
  - Network Engineer     # Cisco, microwave links, topology — strong infra roots
  - Cloud & DevOps       # AWS, Jenkins, Docker, Kubernetes — in production
  - SRE & Observability  # Prometheus, Loki, Grafana — real incidents diagnosed
  - AI Systems           # Vector DBs, embeddings, computer vision
```

---

## `ls -la ~/projects/ --sort=impact`

---

### ⭐ [Board-Game CI/CD Pipeline](https://github.com/kfchacha/Board-Game) — `DevSecOps · AWS EC2 · Kubernetes`

![Build](https://img.shields.io/badge/Build_%2322-PASSING-brightgreen?style=flat-square&logo=jenkins)
![Stages](https://img.shields.io/badge/Pipeline-14_stages_·_75s-blue?style=flat-square)
![AWS](https://img.shields.io/badge/AWS-EC2_eu--north--1-FF9900?style=flat-square&logo=amazonaws)

Full end-to-end DevSecOps pipeline for a Java Spring Boot application:

```
GitHub Webhook → Jenkins → Maven (compile + test) → SonarQube quality gate
  → Trivy filesystem scan → Nexus artifact publish → Docker build + tag
  → Trivy image scan → Docker Hub push → Kubernetes deploy (5-node AWS cluster)
  → KubeAudit security scan → Gmail notification + Trivy report attached
```

`Jenkins` `Kubernetes` `AWS EC2` `Maven` `SonarQube` `Trivy` `Nexus` `Docker` `KubeAudit`

---

### [SRE-Observability-Stack](https://github.com/kfchacha/SRE-Observability-Stack) — `Prometheus · Loki · Grafana · Alertmanager`

Production-grade monitoring on Kubernetes with the full three pillars of observability.
6 custom alert rules, 3 scripted incident simulations, and **real bugs diagnosed and documented**:

- `PodCrashLooping` → fixed gRPC liveness probe timing on `recommendationservice`
- `Grafana startup failure` → resolved duplicate default datasource conflict between Helm charts
- `PromQL returning no data` → discovered Minikube cAdvisor uses `cpu="total"` not `container!=""`

`Prometheus` `Grafana` `Loki` `Alertmanager` `Helm` `Kubernetes` `Minikube` `PromQL`

---

### [Message-Brokers-Demo](https://github.com/kfchacha/message-brokers-demo) — `Kafka · RabbitMQ · Real-time Streaming`

Kafka and RabbitMQ compared side-by-side with real use cases:

- **RabbitMQ** → F1 leaderboard producer/consumer (pub-sub, message delivery semantics)
- **Kafka** → Stock price streaming pipeline → InfluxDB storage → Grafana dashboards

`Kafka` `RabbitMQ` `InfluxDB` `Grafana` `Docker Compose` `Python`

---

### [Aurion — AI Memory Graph](https://github.com/kfchacha/Alien) — `AI · Vector DB · Digital Twin`

Emotion-aware persistent memory system for AI agents — a digital twin concept:

- Ingests user input into structured `MemoryItem` objects with embeddings, emotion scores, and keyword tags
- Retrieves relevant memories using semantic search (ChromaDB + SentenceTransformers)
- Emotion classification via `j-hartmann/emotion-english-distilroberta-base`
- Containerized with Docker Compose

`ChromaDB` `SentenceTransformers` `HuggingFace` `KeyBERT` `Pydantic` `Docker` `Python`

---

### [Microwave-Topology-Mapper](https://github.com/kfchacha/microwave-topology-mapper) — `Networking · Automation`

Automated topology discovery and visualization for microwave link infrastructure — where it all started.

`Python` `Networking` `Topology` `Automation`

---

## `cat stack.json | jq '.skills'`

**CI/CD & Automation**
`Jenkins` `GitHub Actions` `ArgoCD` `Maven` `Groovy`

**Containers & Orchestration**
`Docker` `Kubernetes` `Helm` `Minikube` `Docker Compose`

**Cloud**
`AWS EC2` `GCP` `DigitalOcean`

**Observability & SRE**
`Prometheus` `Grafana` `Loki` `Alertmanager` `PromQL`

**Security**
`Trivy` `SonarQube` `KubeAudit`

**Messaging & Streaming**
`Apache Kafka` `RabbitMQ` `InfluxDB`

**AI / ML**
`ChromaDB` `YOLOv7` `HuggingFace Transformers` `KeyBERT` `SentenceTransformers`

**Networking**
`Cisco` `Microwave Links` `Wireshark` `TCP/IP`

**Languages**
`Python` `Bash` `YAML` `Groovy`

---

## `./stats.sh`

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=kfchacha&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=kfchacha&layout=compact&theme=github_dark&hide_border=true)

[![GitHub Streak](https://streak-stats.demolab.com?user=kfchacha&locale=en&mode=daily&theme=github-dark-blue&hide_border=true&border_radius=5)](https://git.io/streak-stats)

</div>

---

## `./contact.sh --status`

```
✓  Status    → Open to DevOps / Cloud / SRE roles
✓  Location  → Nairobi, Kenya — remote-friendly
✓  LinkedIn  → linkedin.com/in/kenyatta-chacha
✓  GitHub    → github.com/kfchacha
```

<div align="center">

[![Connect](https://img.shields.io/badge/Let's_connect-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kenyatta-chacha/)

*"The network is the computer — and I'm building both."*

</div>
