<p align="center">
  <img src="./banner.svg" alt="Ayush Kumar, DevOps Engineer: from git push to production" width="100%">
</p>

<h2 align="center">Hi, I'm Ayush 👋</h2>

<p align="center">
  <b>DevOps Engineer L2 @ SegueIT</b> · Noida, India<br>
  I turn a <code>git push</code> into a tested, versioned container running in production,<br>
  and make sure the team hears about it the moment something stops responding.
</p>

<p align="center">
  <a href="https://linkedin.com/in/ayush088"><img src="https://img.shields.io/badge/LinkedIn-ayush088-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:kumarayush088@gmail.com"><img src="https://img.shields.io/badge/Email-kumarayush088-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Open_to-DevOps_roles-3ddc97?style=for-the-badge" alt="Open to DevOps roles">
</p>

---

### 🛠️ What I do

- 🚀 **Ship code safely:** CI/CD with GitHub Actions (self-hosted runners), images tagged with the Git commit SHA, deployment locks, `/health` checks and blue/green releases with rollback.
- ☁️ **Run cloud infrastructure:** AWS (EC2, ECR, ECS, Lightsail, Amplify, RDS, S3, CloudFront) and Azure (VMs, ACR, App Service). Client accounts isolated in AWS Organizations, one OU per client.
- 📈 **Watch production:** Prometheus, Grafana, Loki and Alertmanager on a separate monitoring server, plus uptime alerts to a Zoho Cliq channel. Zabbix in progress.
- 🔐 **Keep it secure and recoverable:** EC2 IAM instance roles instead of long-lived keys, NGINX hardening (TLS, rate limiting, security headers), RDS and EC2 backups with AWS Backup.

### 🧰 Tech stack

<p>
  <img src="https://skillicons.dev/icons?i=aws,azure,docker,githubactions,gitlab,jenkins,nginx,prometheus,grafana,linux,ubuntu,git,nextjs,nodejs,py&perline=15" alt="Tech stack">
</p>

### 📦 Work I've shipped

<sub>Client names are generalised; this work runs in production and the code is private.</sub>

| Project | What I built | Stack |
|---|---|---|
| **Pharmacy e-commerce** | Commit → ECR → EC2 release pipeline with SHA-tagged images, IAM instance role and blue/green releases behind NGINX | GitHub Actions · Docker · ECR · EC2 · RDS · S3 · CloudFront |
| **Visitor & staff management** | Locked deploys on a self-hosted runner, WebSocket-ready NGINX, monitoring stack on its own server | GitHub Actions · Docker · NGINX · Prometheus · Grafana · Loki |
| **Segue Monitor** | White-labelled Uptime Kuma: HTTP and keyword checks with alerts to Zoho Cliq | Azure · ACR · Docker · GitHub Actions |
| **10+ more apps** | Deployments across EC2, Lightsail, Amplify, Azure and cPanel hosting | AWS · Azure · Linux · cPanel |

### 📂 Public repos

| Repo | About |
|---|---|
| [`Jenkins-setup-guide`](https://github.com/Ayush8873/Jenkins-setup-guide) | Jenkins + Docker blue/green pipeline on AWS EC2 |
| [`gitlab-poc`](https://github.com/Ayush8873/gitlab-poc) | GitLab CE with a self-hosted runner on EC2 |
| [`portfolio`](https://github.com/Ayush8873/portfolio) | My portfolio site, built with Next.js and TypeScript |

---

<p align="center"><sub>💬 Happy to talk about DevOps roles, pipelines or monitoring. Reach me on <a href="https://linkedin.com/in/ayush088">LinkedIn</a>.</sub></p>
