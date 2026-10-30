# Kubernetes

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Kubernetes, also known as K8s, is an open source system for automating deployment, scaling, and management of containerized applications. It groups containers that make up an application into logical units for easy management and discovery. Kubernetes builds upon 15 years of experience of running production workloads at Google, combined with best-of-breed ideas and practices from the community.

**Areas:** Automation · Cloud-Native · CNCF · Containers · Deployment · Open Source · Scaling · Container Orchestration

## Kubernetes on APIs.io

Everything profiled for Kubernetes is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/kubernetes/](https://apis.io/providers/kubernetes/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Kubernetes Autoscaling API](https://apis.io/apis/kubernetes/kubernetes-autoscaling-api/) — Autoscaling resources including HorizontalPodAutoscalers for automatically scaling workloads based on observed metrics.
- [Kubernetes Cluster API](https://apis.io/apis/kubernetes/kubernetes-cluster-api/) — Cluster-level resources including Namespaces, Nodes, ServiceAccounts, and RBAC resources for cluster administration.
- [Kubernetes Config API](https://apis.io/apis/kubernetes/kubernetes-config-api/) — Configuration and storage resources including ConfigMaps, Secrets, PersistentVolumes, and PersistentVolumeClaims.
- [Kubernetes Events API](https://apis.io/apis/kubernetes/kubernetes-events-api/) — Event resources capturing occurrences within the cluster such as pod scheduling, container restarts, and resource state changes.
- [Kubernetes Namespaces API](https://apis.io/apis/kubernetes/kubernetes-namespaces-api/) — The Namespaces API from Kubernetes — 2 operation(s) for namespaces.
- [Kubernetes RBAC API](https://apis.io/apis/kubernetes/kubernetes-rbac-api/) — Role-based access control resources including Roles, RoleBindings, ClusterRoles, and ClusterRoleBindings for managing authorization.
- [Kubernetes Workloads API](https://apis.io/apis/kubernetes/kubernetes-workloads-api/) — Workload resources including Pods, Deployments, StatefulSets, DaemonSets, ReplicaSets, Jobs, and CronJobs for managing containerized applications.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (16)

Multi-step workflows that chain operations into a business task.

- [Kubernetes Attach a HorizontalPodAutoscaler to a Deployment](https://apis.io/arazzos/kubernetes/kubernetes-autoscale-deployment-workflow/)
- [Kubernetes Audit Cluster Node Capacity](https://apis.io/arazzos/kubernetes/kubernetes-cluster-capacity-audit-workflow/)
- [Kubernetes Publish a ConfigMap and Roll Out Its Consumers](https://apis.io/arazzos/kubernetes/kubernetes-config-rollout-workflow/)
- [Kubernetes Deploy an Application into a New Namespace](https://apis.io/arazzos/kubernetes/kubernetes-deploy-application-workflow/)
- [Kubernetes Expose a Deployment Behind a Service](https://apis.io/arazzos/kubernetes/kubernetes-expose-deployment-workflow/)
- [Kubernetes Apply Governance Labels to a Namespace](https://apis.io/arazzos/kubernetes/kubernetes-namespace-labeling-workflow/)
- [Kubernetes Provision a ClusterRole If Missing](https://apis.io/arazzos/kubernetes/kubernetes-provision-cluster-role-workflow/)
- [Kubernetes Quarantine a Failing Pod for Inspection](https://apis.io/arazzos/kubernetes/kubernetes-quarantine-pod-workflow/)
- [Kubernetes Restart a Pod by Deleting It](https://apis.io/arazzos/kubernetes/kubernetes-restart-pod-workflow/)
- [Kubernetes Retire an Application from a Namespace](https://apis.io/arazzos/kubernetes/kubernetes-retire-application-workflow/)
- [Kubernetes Roll Out a New Container Image](https://apis.io/arazzos/kubernetes/kubernetes-rolling-update-workflow/)
- [Kubernetes Rotate a Secret and Restart Its Consumers](https://apis.io/arazzos/kubernetes/kubernetes-rotate-secret-workflow/)
- [Kubernetes Run a One-Off Task Pod and Collect Its Output](https://apis.io/arazzos/kubernetes/kubernetes-run-one-off-pod-workflow/)
- [Kubernetes Scale a Deployment and Verify Replicas](https://apis.io/arazzos/kubernetes/kubernetes-scale-deployment-workflow/)
- [Kubernetes Inventory and Tear Down a Namespace](https://apis.io/arazzos/kubernetes/kubernetes-teardown-namespace-workflow/)
- [Kubernetes Troubleshoot a Failing Pod](https://apis.io/arazzos/kubernetes/kubernetes-troubleshoot-pod-workflow/)

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Kubernetes Watch Events](https://apis.io/asyncapis/kubernetes/kubernetes-watch-asyncapi/)

#### Event channels (7)

Individual events and webhooks the provider emits.

- [/api/v1/namespaces](https://apis.io/channels/kubernetes/api-v1-namespaces/)
- [/api/v1/namespaces/{namespace}/pods](https://apis.io/channels/kubernetes/api-v1-namespaces-namespace-pods/)
- [/api/v1/namespaces/{namespace}/services](https://apis.io/channels/kubernetes/api-v1-namespaces-namespace-services/)
- [/api/v1/nodes](https://apis.io/channels/kubernetes/api-v1-nodes/)
- [/api/v1/pods](https://apis.io/channels/kubernetes/api-v1-pods/)
- [/apis/apps/v1/namespaces/{namespace}/deployments](https://apis.io/channels/kubernetes/apis-apps-v1-namespaces-namespace-deployments/)
- [/apis/events.k8s.io/v1/namespaces/{namespace}/events](https://apis.io/channels/kubernetes/apis-events-k8s-io-v1-namespaces-namespace-events/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [kubernetes-mcp.yml](https://apis.io/servers/kubernetes/kubernetes-mcp-yml/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Kubernetes Agentic Access](https://apis.io/agentic-access/kubernetes/kubernetes-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [Kubernetes Resource](https://apis.io/schemas/kubernetes/kubernetes-resource/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Kubernetes Context](https://apis.io/jsonld/kubernetes/kubernetes-context/)

#### Collections (15)

Postman and Open Collection request collections.

- [Kubernetes API](https://apis.io/collections/kubernetes/open-kubernetes-api/)
- [Kubernetes Autoscaling API](https://apis.io/collections/kubernetes/open-kubernetes-autoscaling-api/)
- [Kubernetes Autoscaling Cluster API](https://apis.io/collections/kubernetes/open-kubernetes-cluster-api/)
- [Kubernetes Autoscaling Config API](https://apis.io/collections/kubernetes/open-kubernetes-config-api/)
- [Kubernetes Autoscaling Events API](https://apis.io/collections/kubernetes/open-kubernetes-events-api/)
- [Kubernetes Autoscaling Namespaces API](https://apis.io/collections/kubernetes/open-kubernetes-namespaces-api/)
- [Kubernetes Autoscaling RBAC API](https://apis.io/collections/kubernetes/open-kubernetes-rbac-api/)
- [Kubernetes Autoscaling Workloads API](https://apis.io/collections/kubernetes/open-kubernetes-workloads-api/)
- [Kubernetes Autoscaling API](https://apis.io/collections/kubernetes/postman-kubernetes-autoscaling-api/)
- [Kubernetes Autoscaling Cluster API](https://apis.io/collections/kubernetes/postman-kubernetes-cluster-api/)
- [Kubernetes Autoscaling Config API](https://apis.io/collections/kubernetes/postman-kubernetes-config-api/)
- [Kubernetes Autoscaling Events API](https://apis.io/collections/kubernetes/postman-kubernetes-events-api/)
- [Kubernetes Autoscaling Namespaces API](https://apis.io/collections/kubernetes/postman-kubernetes-namespaces-api/)
- [Kubernetes Autoscaling RBAC API](https://apis.io/collections/kubernetes/postman-kubernetes-rbac-api/)
- [Kubernetes Autoscaling Workloads API](https://apis.io/collections/kubernetes/postman-kubernetes-workloads-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Kubernetes Api Overlay](https://apis.io/overlays/kubernetes/kubernetes-api-overlay/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Kubernetes — asyncapi rules](https://apis.io/rules/kubernetes/kubernetes-asyncapi-spectral-rules/)
- [Kubernetes — jsonschema rules](https://apis.io/rules/kubernetes/kubernetes-jsonschema-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Kubernetes Authentication](https://apis.io/security/kubernetes/kubernetes-authentication/)
- [Kubernetes Domain Security](https://apis.io/security/kubernetes/kubernetes-domain-security/)
- [Kubernetes Vulnerability Disclosure](https://apis.io/security/kubernetes/kubernetes-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Kubernetes Plans Pricing](https://apis.io/plans/kubernetes/kubernetes-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Kubernetes Rate Limits](https://apis.io/rate-limits/kubernetes/kubernetes-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Kubernetes Finops](https://apis.io/finops/kubernetes/kubernetes-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://kubernetes.io/)
- [Documentation](https://kubernetes.io/docs/home/)
- [Getting started](https://kubernetes.io/docs/setup/)
- [API reference](https://kubernetes.io/docs/reference/kubernetes-api/)
- [Changelog](https://kubernetes.io/releases/)
- [Blog](https://kubernetes.io/blog/)
- [Security](https://kubernetes.io/docs/concepts/security/)
- [GitHub](https://github.com/kubernetes)

## API Evangelist rating

**Kin Score 47.6** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 62.9 |
| Contract governance | 18.2 |
| Operational transparency | 47.4 |
| Developer ergonomics | 59.0 |
| Access clarity | 21.1 |

**Agent readiness 19.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 22.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/kubernetes/](https://apis.io/providers/kubernetes/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Kubernetes: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/kubernetes/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
