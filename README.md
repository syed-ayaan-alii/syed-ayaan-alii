<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:0d1117&height=120&section=header" />

```
╔══════════════════════════════════════════════════════════════════════╗
║            DEVOPS ENGINEER PROFILE — SYED AYAAN ALI                 ║
║                  system initialized... ready.                        ║
╚══════════════════════════════════════════════════════════════════════╝
```

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&duration=2500&pause=800&color=00FF41&center=true&vCenter=true&width=600&lines=+%24+whoami+--verbose;+%24+kubectl+get+skills+--all-namespaces;+%24+terraform+plan+--target%3Dcareer;+%24+docker+inspect+syed-ayaan-ali;+%24+prometheus+query%3A+uptime%7Bengineer%3D%22ayaan%22%7D" alt="Typing SVG" />

</div>

---

## $ whoami

```bash
$ whoami --verbose

{
  "name"      : "Syed Ayaan Ali",
  "role"      : "DevOps Engineer",
  "location"  : "Bhopal, Madhya Pradesh, India",
  "education" : "B.Tech CSE — SIRT Excellence (Graduated 2025)",
  "status"    : "OPEN_TO_WORK ✅",
  "contact"   : "ali.ayaan1107@gmail.com",
  "interests" : ["Cloud Infrastructure", "Container Orchestration",
                 "CI/CD Automation", "GitOps", "Observability"]
}

> Process completed with exit code 0
```

---

## $ kubectl get skills --all-namespaces

```
NAMESPACE          NAME                    STATUS    PROFICIENCY   AGE
─────────────────────────────────────────────────────────────────────
cloud/aws          EC2                     Running   ████████░░    Intermediate
cloud/aws          S3                      Running   ████████░░    Intermediate
cloud/aws          IAM                     Running   ███████░░░    Intermediate
cloud/aws          VPC                     Running   ███████░░░    Intermediate
containers         Docker                  Running   █████████░    Advanced
containers         Kubernetes              Running   ████████░░    Intermediate
containers         ArgoCD                  Running   ██████░░░░    Familiar
iac                Terraform               Running   ████████░░    Intermediate
cicd               GitHub-Actions          Running   █████████░    Advanced
cicd               Git                     Running   █████████░    Advanced
monitoring         Prometheus              Running   ███████░░░    Intermediate
monitoring         Grafana                 Running   ███████░░░    Intermediate
languages          Python                  Running   ███████░░░    Intermediate
languages          Bash                    Running   ███████░░░    Intermediate
languages          YAML                    Running   █████████░    Advanced
─────────────────────────────────────────────────────────────────────
15 skills running, 0 errors, 0 crashloopbackoffs
```

---

## $ docker ps --projects

```
CONTAINER ID   IMAGE                              STATUS          PORTS
─────────────────────────────────────────────────────────────────────────────────────

a1b2c3d4e5f6   cloud-native-microservices:v1.0   Up  ✅ LIVE     :80/HTTP
                 ├─ Stack   : AWS · Docker · Kubernetes · Terraform · ArgoCD
                 ├─ CI/CD   : GitHub Actions → DockerHub → ArgoCD → K8s
                 ├─ Infra   : Terraform (remote state: S3 + DynamoDB lock)
                 └─ Feature : GitOps sync, Ingress Controller, multi-service mesh

─────────────────────────────────────────────────────────────────────────────────────

b2c3d4e5f6a7   cicd-pipeline-e2e:latest          Up  ✅ LIVE     :443/HTTPS
                 ├─ Stack   : GitHub Actions · Docker · Terraform
                 ├─ CI      : Unit Tests → Linting → Security Scan → Build
                 ├─ CD      : Terraform provision → Docker deploy → Verify
                 └─ Feature : Automated rollback, repeatable environments

─────────────────────────────────────────────────────────────────────────────────────

c3d4e5f6a7b8   monitoring-stack:stable            Up  ✅ LIVE     :3000/GRAFANA
                 ├─ Stack   : Prometheus · Grafana · AlertManager
                 ├─ Metrics : CPU · Memory · Pod Health · Latency · Uptime
                 ├─ Alerts  : PagerDuty-style thresholds configured
                 └─ Feature : Custom dashboards, request rate tracking

─────────────────────────────────────────────────────────────────────────────────────
3 containers running, 0 exited, 0 paused
```

---

## $ terraform plan --target=experience

```hcl
# KUBICL — DevOps Engineer Intern
# Duration: February 2025 → May 2025

resource "experience" "kubicl_intern" {

  responsibilities = [
    "Provisioned cloud infrastructure using Terraform",
    "Deployed containerized apps via Docker + Kubernetes",
    "Built & optimized CI/CD pipelines with GitHub Actions",
    "Set up Prometheus + Grafana monitoring & observability",
    "Automated deployment workflows end-to-end",
  ]

  tools_used = [
    "AWS", "Docker", "Kubernetes",
    "Terraform", "Git", "GitHub Actions"
  ]
}

Plan: 1 role added, 0 changed, 0 destroyed.
```

---

## $ prometheus query: uptime{engineer="ayaan"}

```
METRIC                        VALUE      THRESHOLD   STATUS
──────────────────────────────────────────────────────────────
infrastructure_uptime         99.9%      > 99%       🟢 HEALTHY
deployment_success_rate       100%       > 95%       🟢 HEALTHY
pipeline_automation           ENABLED    ENABLED     🟢 HEALTHY
cloud_cost_optimization       ACTIVE     ACTIVE      🟢 HEALTHY
team_collaboration_score      HIGH       > MED       🟢 HEALTHY
cricket_performance           STATE LVL  > DISTRICT  🟢 HEALTHY
──────────────────────────────────────────────────────────────
Overall System Health: 🟢 ALL SYSTEMS OPERATIONAL
```

---

## $ cat /etc/pipeline.conf

```
  ┌─────────┐     ┌─────────┐     ┌─────────┐     ┌──────────┐     ┌─────────┐
  │  CODE   │────▶│  BUILD  │────▶│  TEST   │────▶│  DEPLOY  │────▶│MONITOR  │
  │         │     │         │     │         │     │          │     │         │
  │ GitHub  │     │ Docker  │     │ Linting │     │Terraform │     │Prometh. │
  │   Git   │     │  Build  │     │  Unit   │     │   K8s    │     │ Grafana │
  │  Push   │     │  Image  │     │  Scan   │     │  ArgoCD  │     │ Alerts  │
  └─────────┘     └─────────┘     └─────────┘     └──────────┘     └─────────┘
       │                │               │                │               │
    trigger          package          validate        provision        observe
```

---

## $ git log --connect

```bash
$ git log --connect --oneline

a1b2c3d  LinkedIn  →  https://linkedin.com/in/syed-ayaan-ali
b2c3d4e  GitHub    →  https://github.com/syed-ayaan-alii
c3d4e5f  Email     →  ali.ayaan1107@gmail.com

> Open to full-time DevOps / Cloud Engineer roles
> Available for immediate joining
```

---

<div align="center">

```
╔══════════════════════════════════════════════════════════╗
║   "Automate everything. Monitor always.                  ║
║                        Deploy with confidence."          ║
╚══════════════════════════════════════════════════════════╝
```

![Profile Views](https://komarev.com/ghpvc/?username=syed-ayaan-alii&color=00FF41&style=flat-square&label=profile+views)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:0d1117&height=100&section=footer" />

</div>
