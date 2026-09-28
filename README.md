# devops-language-lab

Hands-on learning repository for DevOps programming and configuration languages.

## Goals

- Learn YAML fundamentals
- Learn Docker Compose
- Learn GitHub Actions
- Practice configuration management
- Build reproducible DevOps workflows
- Apply Git branching and Pull Request workflow

## Learning Roadmap

| Module | Topic | Status |
|---|---|---|
| 01 | YAML | ✅ Completed |
| 02 | Docker Compose | ⬜ In Progress |
| 03 | GitHub Actions | ⬜ Planned |
| 04 | Ansible | ⬜ Planned |
| 05 | Terraform | ⬜ Planned |
| 06 | Kubernetes | ⬜ Planned |

## Repository Structure

```text
devops-language-lab/
├── 01-yaml/
├── 02-docker-compose/
├── 03-github-actions/
├── 04-ansible/
├── 05-terraform/
└── 06-kubernetes/
Git Workflow

Each module is developed in a separate feature branch.

main
  │
  ├── feature/yaml-fundamentals
  │        │
  │        └── Pull Request
  │                │
  │                ↓
  └────────────── main

Changes are tested in the feature branch before being merged into main through a Pull Request.

Current Progress
YAML

Completed:

Basic YAML syntax
Data types
Lists
Nested structures
Application configuration
YAML validation with yamllint

Next:

Docker Compose
GitHub Actions
Purpose

This repository documents my practical journey toward becoming a stronger DevOps engineer through hands-on projects, automation, configuration management, and CI/CD.


### Tapi ada 1 hal penting

Karena **sekarang baru YAML yang benar-benar selesai**, sebaiknya `Docker Compose` jangan ditulis `⬜ In Progress` kalau memang belum mulai.

Lebih jujur:

```md
| 01 | YAML | ⬜ Planned |
| 02 | Docker Compose | ⬜ Planned |
| 03 | GitHub Actions | ⬜ Planned |
| 04 | Ansible | ⬜ Planned |
| 05 | Terraform | ⬜ Planned |
| 06 | Kubernetes | ⬜ Planned |
