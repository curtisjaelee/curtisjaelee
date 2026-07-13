# Hey, I'm Curtis 👋

**Builder — serverless apps on AWS · Data Science @ UCLA '27**

I build full-stack apps and then obsess over what they cost to run. My favorite kind of problem is the one where the fix is a single missing route: I once replaced a $32/month NAT Gateway with a VPC Gateway Endpoint and got a whole production stack running for under $0.30/month. That debugging session is basically my origin story.

## What I'm building

**[Plak](https://github.com/curtisjaelee/plak)** — a couples' activity-ranking app. Head-to-head comparisons backed by binary-search insertion (O(log n)), React/TypeScript on a fully serverless AWS backend (Lambda, API Gateway, RDS, Cognito, CloudFront), all infrastructure defined in CDK, deployed through a GitHub Actions CI/CD pipeline.

**[Archive Us](https://github.com/curtisjaelee/archive-us)** — a private media archive for two. Postgres schema for time-based entries, S3 presigned-URL uploads for large video, scoped object-level access. Started on Supabase, migrated the whole stack to AWS with CDK — the migration taught me more than the original build.

**Euphony** — my longest-running experiment: a time-series pipeline for physiological sensor data, testing how stimuli (sound frequency, light) measurably affect user state.

## Currently

- Studying for the AWS Solutions Architect – Associate (exam Aug 2026)
- Building a cost-trap scanner: a tool that finds the quiet money-burners in AWS accounts (idle NAT Gateways, unattached volumes, missing lifecycle policies) — because I refuse to be the only one who learns this the expensive way
- Load-testing Plak to find out where it breaks, then fixing that

## Stack

`TypeScript` `Python` `React` `AWS (Lambda · CDK · RDS · S3 · VPC · IAM)` `PostgreSQL` `GitHub Actions` `pandas`

## The through-line

Everything above follows the same loop: build it end-to-end, deploy it for real, break it, understand why, write it down. I'd rather run one system in production than ten in localhost.

---

📍 Los Angeles · 📫 [curtisjaelee@gmail.com](mailto:curtisjaelee@gmail.com) · [LinkedIn](https://www.linkedin.com/in/YOUR-HANDLE)
