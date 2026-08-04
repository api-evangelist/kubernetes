# Kubernetes (kubernetes)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Kubernetes, also known as K8s, is an open source system for automating deployment, scaling, and management of containerized applications. It groups containers that make up an application into logical units for easy management and discovery. Kubernetes builds upon 15 years of experience of running production workloads at Google, combined with best-of-breed ideas and practices from the community.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/kubernetes/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/kubernetes/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Automation
- Cloud Native
- CNCF
- Containers
- Deployment
- Open Source
- Orchestration
- Scaling

## Timestamps

- **Created:** 2025-06-05
- **Modified:** 2026-05-19

## APIs

### Kubernetes API

The Kubernetes API lets you query and manipulate the state of objects in Kubernetes. The core of Kubernetes control plane is the API server and the HTTP API that it exposes. Users, the different parts of your cluster, and external components all communicate with one another through the API server.

- **Human URL:** [https://kubernetes.io/docs/concepts/overview/kubernetes-api/](https://kubernetes.io/docs/concepts/overview/kubernetes-api/)
- **Base URL:** `https://kubernetes.default.svc`

#### Tags

- Automation
- Cloud Native
- CNCF
- Containers
- Deployment
- Orchestration
- Scaling

#### Properties

- [Documentation](https://kubernetes.io/docs/concepts/overview/kubernetes-api/)
- [API Reference](https://kubernetes.io/docs/reference/kubernetes-api/)
- [OpenAPI](https://raw.githubusercontent.com/kubernetes/kubernetes/master/api/openapi-spec/swagger.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Open A P I Repository](https://github.com/kubernetes/kubernetes/tree/master/api/openapi-spec)
- [Authentication](https://kubernetes.io/docs/reference/access-authn-authz/)
- [Client  Libraries](https://kubernetes.io/docs/reference/using-api/client-libraries/)
- [Migration  Guide](https://kubernetes.io/docs/reference/using-api/deprecation-guide/)
- [OpenAPI](openapi/kubernetes-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kubernetes-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kubernetes-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/kubernetes-watch-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/kubernetes-resource-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/kubernetes)
- [GitHub Organization](https://github.com/kubernetes)
- [GitHub Repository](https://github.com/kubernetes/kubernetes)
- [GitHub Repository](https://github.com/kubernetes/community)
- [GitHub Repository](https://github.com/kubernetes/kube-openapi)
- [Bluesky](https://bsky.app/profile/kubernetes.io)
- [X (Twitter)](https://x.com/kubernetesio)
- [Website](https://kubernetes.io/)
- [Documentation](https://kubernetes.io/docs/home/)
- [API Reference](https://kubernetes.io/docs/reference/kubernetes-api/)
- [Blog](https://kubernetes.io/blog/)
- [Training](https://kubernetes.io/training/)
- [Partners](https://kubernetes.io/partners/)
- [Changelog](https://kubernetes.io/releases/)
- [Community](https://kubernetes.io/community/)
- [Forum](https://discuss.kubernetes.io/)
- [Slack](https://kubernetes.slack.com)
- [Sign Up](https://slack.k8s.io)
- [YouTube](https://www.youtube.com/@KubernetesCommunity)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/kubernetes)
- [License](https://github.com/kubernetes/kubernetes/blob/master/LICENSE)
- [Security](https://kubernetes.io/docs/concepts/security/)
- [Security Policy](https://github.com/kubernetes/kubernetes/security/policy)
- [Foundation](https://www.cncf.io/projects/kubernetes/)
- [Newsletter](https://www.cncf.io/kubeweekly/)
- [Getting Started](https://kubernetes.io/docs/setup/)
- [Tutorials](https://kubernetes.io/docs/tutorials/)
- [Case Studies](https://kubernetes.io/case-studies/)
- [Code Of Conduct](https://kubernetes.io/community/code-of-conduct/)
- [Deprecation Policy](https://kubernetes.io/docs/reference/using-api/deprecation-policy/)
- [JSON Schema](json-schema/kubernetes-resource-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/kubernetes-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
