# Awesome Feature Flags

A curated directory of feature-flag, feature-management and remote-config platforms, SaaS and open source.

## 📑 Table of Contents

- [Experimentation-First (5)](#experimentation-first)
- [Managed Platforms (3)](#managed-platforms)
- [Open-Source Feature Flags (7)](#open-source-feature-flags)
- [OpenFeature Providers (2)](#openfeature-providers)
- [Remote Config (1)](#remote-config)
- [SDKs & Libraries (1)](#sdks--libraries)


## Experimentation-First

- [GrowthBook](https://growthbook.io/) - GrowthBook is an open-source experimentation platform that combines feature flags with A/B testing, built for data teams and engineers. It connects to existing data warehouses (Snowflake, BigQuery, Postgres) for metric analysis. The core is MIT licensed with a hosted cloud version. ([Read more](/details/growthbook.md)) `Open Source` `Self-Hosted` `Freemium` `Free Plan` `API` `A/B Testing` `Warehouse-Native`
- [Optimizely Feature Experimentation](https://www.optimizely.com/products/feature-experimentation) - Optimizely Feature Experimentation is an enterprise experimentation and feature management product from the digital experience platform vendor. It combines feature flags with statistical experimentation, personalization, and analytics. Pricing is custom enterprise contracts. ([Read more](/details/optimizely-feature-experimentation.md)) `Paid` `Enterprise` `API` `A/B Testing` `Personalization` `Digital Experience`
- [PostHog](https://posthog.com/) - PostHog is an open-source product analytics suite that includes feature flags, session replay, and experimentation. It can be self-hosted or used as a managed service, with a generous free tier. The platform is MIT licensed and targets product engineers. ([Read more](/details/posthog.md)) `Open Source` `Self-Hosted` `Freemium` `Free Plan` `API` `Product Analytics` `Session Replay`
- [Split.io](https://split.io/) - Split is a feature delivery platform that combines feature flags with experimentation, observability, and progressive delivery for enterprise teams. It offers a free developer tier and enterprise plans with advanced targeting, governance, and integrations. ([Read more](/details/split-io.md)) `Freemium` `Free Plan` `Paid` `Enterprise` `API` `Progressive Delivery` `Observability`
- [Statsig](https://statsig.com/) - Statsig is a feature management and experimentation platform built for product teams at scale, offering automated experiment analysis, feature gates, and dynamic configs. It provides a free tier for small teams and usage-based pricing for enterprises. Not open source. ([Read more](/details/statsig.md)) `Freemium` `Free Plan` `Paid` `Enterprise` `API` `AI-Powered` `Automated Analysis`

## Managed Platforms

- [ConfigCat](https://configcat.com/) - ConfigCat is a hosted feature flag and configuration service with a focus on simplicity and GDPR compliance. It offers a free tier for low-volume use, team collaboration features, and SDKs for all major platforms. The service is proprietary with EU data residency options. ([Read more](/details/configcat.md)) `Freemium` `Free Plan` `Paid` `Enterprise` `API` `GDPR` `Simple`
- [DevCycle](https://devcycle.com/) - DevCycle is a managed feature management platform built for developer experience, offering variable-based flags, edge delivery, and integrations with Vercel, Netlify, and Kubernetes. It provides a free tier for small teams and usage-based paid plans. ([Read more](/details/devcycle.md)) `Freemium` `Free Plan` `Paid` `Enterprise` `API` `Edge` `Developer Experience`
- [LaunchDarkly](https://launchdarkly.com/) - LaunchDarkly is a feature management platform for enterprise teams to control feature rollouts, targeting, and experimentation across applications. It provides SDKs for 25+ languages, real-time flag updates, and integrations with CI/CD, observability, and analytics tools. Pricing is enterprise-focused with custom contracts. ([Read more](/details/launchdarkly.md)) `Enterprise` `Paid` `API` `AI-Powered` `Real-time` `Targeting`

## Open-Source Feature Flags

- [Bucketeer](https://bucketeer.io/) - Bucketeer is an open-source feature flag platform originally developed by CyberAgent, designed for large-scale experimentation with user segmentation and gradual rollouts. It includes a dashboard, SDKs, and supports OpenFeature. Licensed under Apache 2.0. ([Read more](/details/bucketeer.md)) `Open Source` `Self-Hosted` `Free Plan` `API` `Experimentation` `Apache-2.0` `OpenFeature`
- [FeatBit](https://featbit.co/) - FeatBit is an open-source feature flag management system with a focus on .NET and cloud-native deployments. It provides a management UI, real-time updates via SignalR, and OpenFeature provider support. Licensed under MIT with a commercial hosted option. ([Read more](/details/featbit.md)) `Open Source` `Self-Hosted` `Freemium` `Free Plan` `API` `.NET` `SignalR` `OpenFeature`
- [FF4J](https://ff4j.org/) - FF4J (Feature Flipping for Java) is an open-source feature flag framework for Java applications with a web console, REST API, and integrations for Spring Boot, JEE, and microservices. It supports property-based flip conditions and audit trails. Apache 2.0 licensed. ([Read more](/details/ff4j.md)) `Open Source` `Self-Hosted` `Free Plan` `API` `Java` `Spring Boot` `Apache-2.0`
- [Flagsmith](https://flagsmith.com/) - Flagsmith is an open-source feature flag and remote config service that can be self-hosted or used via a managed cloud. It supports multivariate flags, segment targeting, and analytics integrations. The core platform is BSD-3 licensed with a commercial cloud offering. ([Read more](/details/flagsmith.md)) `Open Source` `Self-Hosted` `Freemium` `Free Plan` `API` `Remote Config`
- [Flipt](https://flipt.io/) - Flipt is a self-hosted, open-source feature flag solution designed for developers who need a lightweight, GitOps-friendly flag management system. It provides a UI, REST/gRPC APIs, and client SDKs. Licensed under AGPL-3.0 with a commercial enterprise edition. ([Read more](/details/flipt.md)) `Open Source` `Self-Hosted` `Free Plan` `Enterprise` `API` `GitOps` `AGPL-3.0`
- [GoFeatureFlag](https://gofeatureflag.org/) - GoFeatureFlag is a lightweight, open-source feature flag provider written in Go that reads flags from files, databases, or cloud storage. It supports OpenFeature providers, multiple targeting rules, and can run as a standalone service or library. MIT licensed. ([Read more](/details/gofeatureflag.md)) `Open Source` `Self-Hosted` `Free Plan` `API` `Go` `OpenFeature` `GitOps`
- [Togglz](https://www.togglz.org/) - Togglz is a Java-focused open-source feature toggle library that integrates with Spring, CDI, and Jakarta EE. It provides an admin console, multiple state repositories (DB, Redis, file), and activation strategies. Licensed under Apache 2.0. ([Read more](/details/togglz.md)) `Open Source` `Self-Hosted` `Free Plan` `API` `Java` `Spring` `Apache-2.0`

## OpenFeature Providers

- [Flagd](https://flagd.dev/) - Flagd is a lightweight, OpenFeature-compliant feature flag daemon that reads flag configurations from files, HTTP, or Kubernetes resources. It runs as a sidecar or standalone service and provides a gRPC/HTTP provider for OpenFeature SDKs. Apache 2.0 licensed. ([Read more](/details/flagd.md)) `Open Source` `Self-Hosted` `Free Plan` `API` `Kubernetes` `Sidecar` `Apache-2.0`
- [Unleash Proxy](https://github.com/Unleash/unleash-proxy) - Unleash Proxy is an open-source edge proxy that sits between applications and the Unleash server, providing caching, OpenFeature provider support, and reduced latency for flag evaluation. It enables multi-language support via the OpenFeature standard. Apache 2.0 licensed. ([Read more](/details/unleash-proxy.md)) `Open Source` `Self-Hosted` `Free Plan` `API` `Edge` `Proxy` `Apache-2.0`

## Remote Config

- [Firebase Remote Config](https://firebase.google.com/docs/remote-config) - Firebase Remote Config is a cloud service from Google that lets you change app behavior and appearance without deploying new code. It integrates with Firebase Analytics and A/B Testing, offers a generous free tier, and scales with pay-as-you-go pricing. ([Read more](/details/firebase-remote-config.md)) `Free` `Freemium` `API` `Mobile-First` `Google Cloud` `A/B Testing`

## SDKs & Libraries

- [OpenFeature](https://openfeature.dev/) - OpenFeature is a vendor-neutral, open-source specification and SDK framework for feature flagging, hosted by the CNCF. It provides unified APIs across languages and a provider ecosystem to connect to any flag management backend. Apache 2.0 licensed. ([Read more](/details/openfeature.md)) `Open Source` `Free Plan` `API` `CNCF` `Vendor-Neutral` `Specification` `Apache-2.0`


## ™️ Legal

All product names, logos, and brands are the property of their respective owners. All company, product, and service names used in this repository, related repositories, and associated websites are for identification purposes only. The use of these names, logos, and brands does not imply endorsement, affiliation, or sponsorship.

This work may include content generated by artificial intelligence (AI). While efforts have been made to ensure the accuracy and reliability of the information, we make no representations or warranties of any kind, express or implied, about the completeness, accuracy, reliability, suitability, or availability of the information contained herein. Users are advised to independently verify the information before making decisions based on it.

We disclaim any responsibility for errors, omissions, or inaccuracies in the content, whether generated by humans, AI, or any other means. By using this work, you agree to use it at your own risk and acknowledge that the information provided may not always be current or accurate.

If you believe that your intellectual property rights or other legal rights have been infringed, please contact us immediately at legal@ever.co and we will take appropriate action.

## 🛡️ License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a

[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/

[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png

[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg