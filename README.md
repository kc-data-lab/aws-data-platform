# AWS Data Platform

Personal project focused on learning and applying Data Engineering concepts on AWS using Infrastructure as Code (IaC).

## Goals

- Learn AWS through hands-on projects
- Manage cloud infrastructure with Terraform
- Build a Data Lake on Amazon S3
- Process and transform data
- Query data using AWS analytics services
- Implement basic Machine Learning workloads
- Automate deployments with GitHub Actions

## Tech Stack

- AWS
- Terraform
- Python
- SQL
- GitHub Actions

## Project Roadmap

### Phase 1 - Infrastructure Foundation

- [ ] Configure AWS account and IAM
- [ ] Set up Terraform project structure
- [ ] Deploy an S3 bucket using Terraform

### Phase 2 - Data Lake

- [ ] Design S3 data lake structure
- [ ] Implement data ingestion pipelines
- [ ] Define storage and partitioning strategies

### Phase 3 - Data Catalog and Analytics

- [ ] Configure AWS Glue Catalog
- [ ] Query data with Amazon Athena
- [ ] Build analytical datasets

### Phase 4 - Data Engineering Automation

- [ ] Automate infrastructure deployments
- [ ] Implement CI/CD pipelines
- [ ] Add monitoring and alerting

### Phase 5 - Machine Learning

- [ ] Build basic predictive models
- [ ] Train and evaluate datasets
- [ ] Deploy inference workloads

## Architecture

```text
Data Sources
     ↓
Amazon S3
     ↓
AWS Glue
     ↓
Amazon Athena
     ↓
Analytics / Machine Learning
```

## Repository Structure

```text
aws-data-platform/
├── docs/
│   ├── architecture/
│   ├── diagrams/
│   └── decisions/
├── terraform/
│   ├── environments/
│   │   ├── dev/
│   │   └── prod/
│   └── modules/
└── .github/
    └── workflows/
```

## Learning Objectives

This project aims to provide hands-on experience with:

- Cloud Infrastructure
- Infrastructure as Code (Terraform)
- Data Lake Architecture
- Data Engineering Fundamentals
- AWS Analytics Services
- Machine Learning Workflows
- CI/CD for Data Platforms

## License

This project is intended for educational and portfolio purposes.