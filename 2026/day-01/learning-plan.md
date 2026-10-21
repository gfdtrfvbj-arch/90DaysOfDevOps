# My 90-Day DevOps Learning Plan

## Current level
Working professional: **monitoring engineer** (Grafana dashboards, alerting, incident response on production systems).
Technical bachelor's degree. Daily Ubuntu user. Already practiced Git (rebase, cherry-pick, conflict resolution, MRs) and built a GitLab CI pipeline (lint → test → build).
Gaps: containers, Kubernetes, cloud, Infrastructure as Code.

## What DevOps & Cloud mean to me
DevOps is about shortening the path from a code change to a reliable service in production: automation instead of manual steps, fast feedback, and shared ownership of what runs in prod.
Cloud engineering is building that on programmable infrastructure, where servers, networks and clusters are code that can be versioned, reviewed and recreated.
From monitoring I see the "after" side: alerts, incidents, dashboards. Now I want to own the "before" side too: how services are built, shipped and run.

## Why I'm starting
- Move from observing systems to building and operating them end-to-end
- Target: DevOps / Platform engineer role on the **German job market**
- Get internationally recognized certifications: **CKA → AWS SAA → Terraform Associate**

## 3 goals for the next 90 days
1. **Containerize and ship:** my `hello_ci` app has a Dockerfile, and GitLab CI builds, tests and pushes the image to a registry automatically.
2. **Run it on Kubernetes with observability:** deploy the app to a cluster (kind/k3s) with Deployment, Service, Ingress, ConfigMap/Secret, and monitor it with Prometheus + Grafana, including at least one working alert.
3. **Be CKA-ready:** finish the K8s track and score ≥ 80% on a CKA mock exam.

## 3 core skills to build
1. **Linux & networking troubleshooting:** processes, systemd, logs, DNS, ports, `ss`/`curl`/`dig`/`journalctl`
2. **CI/CD with containers:** Docker images, multi-stage builds, registries, pipeline design
3. **Kubernetes operations & debugging:** why a pod is Pending, CrashLooping or unreachable, and how to fix it

## Weekly time budget (~9–10 h)
- Mon–Fri: **1–1.5 h/day** after work
- Saturday: **3–4 h** for a hands-on project block
- Sunday: **30 min** weekly review + rest

## Roadmap
| Days | Focus |
|---|---|
| 1–30 | Linux deep-dive, networking, Bash scripting, Docker |
| 31–60 | CI/CD with Docker, Kubernetes core objects, cluster setup |
| 61–90 | K8s troubleshooting, monitoring stack, CKA mock exams |

## How I'll stay consistent
- **Terminal every day:** even on a bad day, 20 minutes of hands-on work; reading alone doesn't count
- **One resource per phase:** finish it before adding a new one
- **Daily commit** to this repo with notes: what I did, what broke, why it broke
- **Sunday review:** compare progress with this plan and adjust honestly
- **Learn in public:** a short weekly post on LinkedIn
