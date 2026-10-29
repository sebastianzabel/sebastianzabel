## Hi, I'm Sebastian

Platform Engineer from Oldenburg, Germany. I build and run the infrastructure other developers work on: Kubernetes platforms, GitOps pipelines, observability and, more and more, AI platforms.

### Right now

- Running an internal AI platform at a German bank: LLM gateway with rate limiting and guardrails, coding agents for developers
- Owning the bank's Elastic platform on Kubernetes and its rollout as SIEM
- Exploring how far AI agents get on production-grade software with [Clokr](https://github.com/sebastianzabel/clokr)

### Stack

Kubernetes · RKE2 · K3s · ArgoCD · Terraform / OpenTofu · Ansible · AWS · Elasticsearch · GitLab CI · GitHub Actions · TypeScript · Python · PostgreSQL · LLM / RAG

### Featured

**[Clokr](https://github.com/sebastianzabel/clokr)**: My agentic engineering testbed. Claude Code writes all of the code; I own architecture, requirements, reviews and quality. The result is a multi-tenant app for time tracking, absences and shift planning under German labor law (TypeScript, Prisma, PostgreSQL). What keeps it honest:

- [Module boundaries](https://github.com/sebastianzabel/clokr/blob/main/docs/adr/0002-vier-kontexte-und-unterbau.md) [enforced at build time](https://github.com/sebastianzabel/clokr/blob/main/eslint.boundaries.mjs), and a [tenant-scoping gate](https://github.com/sebastianzabel/clokr/blob/main/apps/api/scripts/lint-tenant-scoping.ts) that fails CI on any unscoped query
- [Releases](https://github.com/sebastianzabel/clokr/releases) with an SBOM per image
- A [simulation environment](https://github.com/sebastianzabel/clokr/tree/main/apps/sim) where bots use the app and a nightly invariant checker looks for broken numbers

**Homelab**: Proxmox and K3s, fully managed via ArgoCD (app of apps). My playground for new things, currently a vendor neutral RAG pipeline (Qdrant, FastEmbed, bge-m3).

### Background

15+ years in operations and platform work: network monitoring at EWE TEL, cloud and platform engineering at sonnen (incl. team lead of a 7 person platform team and an AWS landing zone built with Terraform).

AWS Certified Solutions Architect Associate · Certified ScrumMaster

[LinkedIn](https://www.linkedin.com/in/sebastianzabel)
