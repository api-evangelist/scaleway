# Scaleway

Scaleway is a European cloud provider offering a full suite of compute, storage, networking, AI, and serverless infrastructure services. Scaleway provides a comprehensive REST API for programmatic management of all cloud resources including Instances, Kubernetes clusters (Kapsule and Kosmos), managed databases, load balancers, VPC networking, secret management, serverless containers, serverless functions, IAM, generative AI inference, and more. The Scaleway API uses X-Auth-Token header authentication and provides OpenAPI specifications for every product.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/scaleway/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

AI, Cloud Computing, Containers, Database, European Cloud, Infrastructure, Kubernetes, Serverless, Storage

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-02

## APIs

### Scaleway Instance API
The Scaleway Instance API allows you to create, manage, and delete virtual machine instances, manage IP addresses, security groups, images, snapshots, volumes, and other compute resources across Scaleway's infrastructure zones.

**Human URL:** [https://www.scaleway.com/en/developers/api/instances/](https://www.scaleway.com/en/developers/api/instances/)

#### Tags
Compute, Images, Instances, Security Groups, Snapshots, Virtual Machines

#### Properties
- [Documentation](https://www.scaleway.com/en/developers/api/instances/)
- [OpenAPI](openapi/scaleway-instance-openapi.yml)

### Scaleway Kubernetes API
The Scaleway Kubernetes API (Kapsule and Kosmos) allows you to create and manage fully-managed Kubernetes clusters including cluster lifecycle management, node pool configuration, and upgrades.

**Human URL:** [https://www.scaleway.com/en/developers/api/kubernetes/](https://www.scaleway.com/en/developers/api/kubernetes/)

#### Tags
Containers, Kapsule, Kubernetes, Node Pools, Orchestration

#### Properties
- [Documentation](https://www.scaleway.com/en/developers/api/kubernetes/)
- [OpenAPI](openapi/scaleway-kubernetes-openapi.yml)

### Scaleway IAM API
The Scaleway IAM API provides identity and access management for Scaleway organizations. Manage API keys, users, groups, applications, policies, and permission sets.

**Human URL:** [https://www.scaleway.com/en/developers/api/iam/](https://www.scaleway.com/en/developers/api/iam/)

#### Tags
Access Control, API Keys, Groups, IAM, Identity, Permissions, Policies

#### Properties
- [Documentation](https://www.scaleway.com/en/developers/api/iam/)
- [OpenAPI](openapi/scaleway-iam-openapi.yml)

### Scaleway Load Balancer API
Highly available load balancers supporting TCP, HTTP, and HTTPS with health checks, SSL termination, and session persistence.

**Human URL:** [https://www.scaleway.com/en/developers/api/load-balancer/zoned-api/](https://www.scaleway.com/en/developers/api/load-balancer/zoned-api/)

#### Tags
Backend, Health Checks, Load Balancing, Networking, SSL

#### Properties
- [Documentation](https://www.scaleway.com/en/developers/api/load-balancer/zoned-api/)
- [OpenAPI](openapi/scaleway-load-balancer-openapi.yml)

### Scaleway Managed Database API
Fully managed PostgreSQL, MySQL, and Redis database services with automated backups, read replicas, and snapshots.

**Human URL:** [https://www.scaleway.com/en/developers/api/managed-databases-for-postgresql-and-mysql/](https://www.scaleway.com/en/developers/api/managed-databases-for-postgresql-and-mysql/)

#### Tags
Backup, Database, MySQL, PostgreSQL, Redis, Relational Database

#### Properties
- [Documentation](https://www.scaleway.com/en/developers/api/managed-databases-for-postgresql-and-mysql/)
- [OpenAPI](openapi/scaleway-database-openapi.yml)

### Scaleway VPC API
Virtual Private Cloud and regional Private Networks for interconnecting Scaleway resources within isolated L2 networks.

**Human URL:** [https://www.scaleway.com/en/developers/api/vpc/](https://www.scaleway.com/en/developers/api/vpc/)

#### Tags
Network Isolation, Networking, Private Networks, VPC, Virtual Private Cloud

#### Properties
- [Documentation](https://www.scaleway.com/en/developers/api/vpc/)
- [OpenAPI](openapi/scaleway-vpc-openapi.yml)

### Scaleway Serverless Containers API
Deploy containerized applications as serverless workloads with pay-per-use pricing and automatic scaling to zero.

**Human URL:** [https://www.scaleway.com/en/developers/api/serverless-containers/](https://www.scaleway.com/en/developers/api/serverless-containers/)

#### Tags
Containers, CRON, Docker, Serverless

#### Properties
- [Documentation](https://www.scaleway.com/en/developers/api/serverless-containers/)
- [OpenAPI](openapi/scaleway-serverless-containers-openapi.yml)

### Scaleway Serverless Functions API
Function-as-a-service with event-driven execution and CRON scheduling.

**Human URL:** [https://www.scaleway.com/en/developers/api/serverless-functions/](https://www.scaleway.com/en/developers/api/serverless-functions/)

#### Tags
Event-Driven, FaaS, Functions, Serverless

#### Properties
- [Documentation](https://www.scaleway.com/en/developers/api/serverless-functions/)
- [OpenAPI](openapi/scaleway-serverless-functions-openapi.yml)

### Scaleway Secret Manager API
Secure storage for API keys, passwords, and certificates with versioning and access policies.

**Human URL:** [https://www.scaleway.com/en/developers/api/secret-manager/](https://www.scaleway.com/en/developers/api/secret-manager/)

#### Tags
Certificates, Credentials, Secrets, Security, Vault

#### Properties
- [Documentation](https://www.scaleway.com/en/developers/api/secret-manager/)
- [OpenAPI](openapi/scaleway-secret-manager-openapi.yml)

### Scaleway Transactional Email API
Managed email delivery service with domain verification and delivery tracking.

**Human URL:** [https://www.scaleway.com/en/developers/api/transactional-email/](https://www.scaleway.com/en/developers/api/transactional-email/)

#### Tags
Email, Messaging, Notifications, SMTP, Transactional Email

#### Properties
- [Documentation](https://www.scaleway.com/en/developers/api/transactional-email/)
- [OpenAPI](openapi/scaleway-transactional-email-openapi.yml)

### Scaleway Generative APIs
AI language models and generative AI services on Scaleway infrastructure, compatible with the OpenAI API format.

**Human URL:** [https://www.scaleway.com/en/docs/generative-apis/](https://www.scaleway.com/en/docs/generative-apis/)

#### Tags
AI, Artificial Intelligence, Generative AI, Language Models, LLM

#### Properties
- [Documentation](https://www.scaleway.com/en/docs/generative-apis/)
- [Getting Started](https://www.scaleway.com/en/docs/generative-apis/quickstart/)

## Capabilities

Naftiko capability definitions for AI-assisted cloud infrastructure management:

**Shared Definitions:**
- [capabilities/shared/instance.yaml](capabilities/shared/instance.yaml) — Scaleway Instance API consumer
- [capabilities/shared/kubernetes.yaml](capabilities/shared/kubernetes.yaml) — Scaleway Kubernetes API consumer
- [capabilities/shared/secret-manager.yaml](capabilities/shared/secret-manager.yaml) — Scaleway Secret Manager API consumer

**Workflow Capabilities:**
- [capabilities/cloud-infrastructure.yaml](capabilities/cloud-infrastructure.yaml) — Unified cloud infrastructure workflow (17 tools) for DevOps teams managing compute, Kubernetes, and secrets

## Rules

- [rules/scaleway-rules.yml](rules/scaleway-rules.yml) — Spectral ruleset enforcing Scaleway API conventions

## Schemas

- [json-schema/scaleway-instance-schema.json](json-schema/scaleway-instance-schema.json) — Instance resource schema
- [json-schema/scaleway-cluster-schema.json](json-schema/scaleway-cluster-schema.json) — Kubernetes cluster schema
- [json-schema/scaleway-secret-schema.json](json-schema/scaleway-secret-schema.json) — Secret Manager secret schema

## JSON Structures

- [json-structure/scaleway-instance-structure.json](json-structure/scaleway-instance-structure.json) — Instance structure documentation
- [json-structure/scaleway-cluster-structure.json](json-structure/scaleway-cluster-structure.json) — Kubernetes cluster structure documentation

## JSON-LD

- [json-ld/scaleway-context.jsonld](json-ld/scaleway-context.jsonld) — JSON-LD context mapping Scaleway vocabulary to schema.org

## Examples

- [examples/scaleway-instance-list-servers-example.json](examples/scaleway-instance-list-servers-example.json) — List Instances
- [examples/scaleway-instance-create-server-example.json](examples/scaleway-instance-create-server-example.json) — Create Instance
- [examples/scaleway-kubernetes-list-clusters-example.json](examples/scaleway-kubernetes-list-clusters-example.json) — List Kubernetes clusters
- [examples/scaleway-secret-manager-create-secret-example.json](examples/scaleway-secret-manager-create-secret-example.json) — Create secret

## Vocabulary

- [vocabulary/scaleway-vocabulary.yml](vocabulary/scaleway-vocabulary.yml) — Scaleway terminology and domain vocabulary (22 terms)

## Common Properties

- [Portal](https://www.scaleway.com/en/developers/)
- [Documentation](https://www.scaleway.com/en/docs/)
- [API Reference](https://www.scaleway.com/en/developers/api/)
- [GitHub](https://github.com/scaleway)
- [Go SDK](https://github.com/scaleway/scaleway-sdk-go)
- [CLI](https://github.com/scaleway/scaleway-cli)
- [Terraform Provider](https://github.com/scaleway/terraform-provider-scaleway)
- [Status](https://status.scaleway.com/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
