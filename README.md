# AWS Solutions Architect — Study Notes
### SAA-C03 Exam Prep · 17 Modules · Interactive HTML

> Structured, exam-focused reference notes for every topic in the AWS Certified Solutions Architect – Associate (SAA-C03) syllabus. Collapsible concept cards, key points, comparison tables, and exam tips — all in self-contained HTML files, no dependencies, no build step.

🔗 **[Open the Study Notes →](https://YOUR_USERNAME.github.io/aws-exam-notes/)**

---

## What's inside

Each module is a standalone HTML file with:
- **Collapsible concept cards** — expand only what you need
- **Key points** — bullet-form facts that exam questions test
- **Comparison tables** — side-by-side for services with multiple flavors
- **Exam tips** — common traps, likely question angles, always/never rules
- **Warning callouts** — security pitfalls and operational gotchas

The landing page (`index.html`) has live search and category filters so you can jump to any module in seconds.

---

## Modules

| Module | File | Topics covered |
|--------|------|----------------|
| 🖥️ **EC2** | `aws_ec2_notes.html` | Instance types, AMIs, purchasing options, EBS, Auto Scaling, placement groups |
| 🔐 **IAM** | `aws_iam_notes.html` | Users, groups, roles, policies, MFA, STS, Organizations, SCPs, Control Tower |
| 🗄️ **Storage** | `aws_storage_notes.html` | S3 storage classes, lifecycle, replication, EBS, EFS, FSx, Snowball, DataSync |
| 🗃️ **Databases** | `aws_databases_notes.html` | RDS, Aurora Serverless, DynamoDB, ElastiCache, Redshift, DocumentDB, Neptune |
| ⚖️ **HA & Scalability** | `aws_ha_scalability_notes.html` | ALB, NLB, GWLB, ASG policies, lifecycle hooks, scaling strategies |
| 🌐 **Route 53 & DNS** | `aws_route53_dns_notes.html` | Routing policies, health checks, DNSSEC, hybrid DNS |
| 🚀 **CloudFront & GA** | `aws_cloudfront_ga_notes.html` | Distributions, OAC, Lambda@Edge, signed URLs, Global Accelerator |
| 📨 **Messaging** | `aws_messaging_notes.html` | SQS, SNS, Kinesis Data Streams/Firehose, Amazon MQ, decoupling patterns |
| 🐳 **Containers** | `aws_containers_notes.html` | ECS, EKS, Fargate, ECR, App Runner, container networking |
| ⚡ **Serverless** | `aws_serverless_notes.html` | Lambda, API Gateway, Step Functions, EventBridge, SAM |
| 🤖 **AI & ML** | `aws_ml_notes.html` | SageMaker, Rekognition, Comprehend, Textract, Bedrock, Forecast |
| 📊 **Analytics** | `aws_analytics_notes.html` | Athena, Glue, EMR, Redshift Spectrum, QuickSight, Lake Formation, MSK |
| 📡 **Monitoring & Audit** | `aws_monitoring_notes.html` | CloudWatch, CloudTrail, X-Ray, AWS Config, EventBridge |
| 🛡️ **Security** | `aws_security_notes.html` | KMS, Secrets Manager, WAF, Shield, GuardDuty, Inspector, Macie, Cognito |
| 🔄 **Disaster Recovery** | `aws_disaster_recovery_notes.html` | DR strategies, RPO/RTO, AWS Backup, DMS, MGN, Transfer Family |
| 🔀 **Networking & VPC** | `aws_networking_notes.html` | VPC, subnets, NACLs, VPC Peering, Transit Gateway, Direct Connect, PrivateLink |
| 🧩 **Other Services** | `aws_other_services_notes.html` | CloudFormation, Elastic Beanstalk, CodePipeline, CodeDeploy, SSM, Trusted Advisor |

---

## Using the landing page

| Feature | How |
|---------|-----|
| **Search** | Type in the search bar — filters cards live across title, keywords, and description |
| **Keyboard shortcut** | Press `/` anywhere to focus the search field |
| **Clear search** | Press `Esc` to reset search and filters |
| **Category filter** | Click any filter pill (Compute, Storage, Network, Database, Security, DevOps, AI/ML) |

---

## Deploying your own copy

Everything is plain HTML — no build tools, no framework, no npm.

```bash
# 1. Fork or clone this repo
git clone https://github.com/YOUR_USERNAME/aws-exam-notes.git
cd aws-exam-notes

# 2. Enable GitHub Pages
# Repo → Settings → Pages → Source: main branch / (root) → Save

# 3. Your site is live at:
# https://YOUR_USERNAME.github.io/aws-exam-notes/
```

After enabling Pages, deployment takes about 60 seconds. Any `git push` to `main` automatically redeploys.

---

## Adding new notes

Drop a new `aws_<topic>_notes.html` file into the root and add a card for it in `index.html`. The search index picks it up from the `data-keywords` attribute on the card element.

---

## Tech stack

- Pure HTML · CSS · Vanilla JS — zero dependencies
- [IBM Plex Sans + Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) · [Syne](https://fonts.google.com/specimen/Syne) · [Instrument Sans](https://fonts.google.com/specimen/Instrument+Sans) via Google Fonts
- Hosted on [GitHub Pages](https://pages.github.com/)

---

## License

MIT — free to use, fork, and share. If these notes helped you pass the exam, a ⭐ on the repo is appreciated.

---

*SAA-C03 exam objectives as of 2024–2025. Always cross-reference with the [official AWS exam guide](https://aws.amazon.com/certification/certified-solutions-architect-associate/).*
