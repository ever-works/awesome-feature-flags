# Awesome Feature Flags

A curated directory of feature-flag, feature-management and remote-config platforms, SaaS and open source.

## 📑 Table of Contents

- [Open Source Feature Flags (13)](#open-source-feature-flags)
- [Experimentation First (6)](#experimentation-first)
- [Managed Platforms (16)](#managed-platforms)
- [OpenFeature Providers (4)](#openfeature-providers)
- [Remote Config (1)](#remote-config)
- [SDKs & Libraries (8)](#sdks--libraries)


## Open Source Feature Flags

- [Unleash](https://www.getunleash.io) - A powerful open-source solution for feature management written in TypeScript. Provides self-hosted feature flagging with advanced targeting, gradual rollouts, and OpenFeature SDK support. ([Read more](/details/unleash.md)) `Open Source` `Self Hosted` `Openfeature` `Typescript`
- [Abby](https://abby.dev) - Abby is an open-source feature flag and A/B testing platform with configuration-as-code support and fully typed TypeScript SDKs. It offers strong integration with frameworks such as Next.js and React, with a generous free tier and affordable scaling options. Self-hostable and designed for developers who want control over their feature flag infrastructure. ([Read more](/details/abby.md)) `Open Source` `Self Hosted` `A B Testing` `Typescript`
- [Bucketeer](https://bucketeer.io/) - Bucketeer is an open-source feature flag platform originally developed by CyberAgent, designed for large-scale experimentation with user segmentation and gradual rollouts. It includes a dashboard, SDKs, and supports OpenFeature. Licensed under Apache 2.0. ([Read more](/details/bucketeer.md)) `Open Source` `Self Hosted` `Free Plan` `Api` `Experimentation` `Apache 2 0` `Openfeature`
- [FeatBit](https://featbit.co/) - FeatBit is an open-source feature flag management system with a focus on .NET and cloud-native deployments. It provides a management UI, real-time updates via SignalR, and OpenFeature provider support. Licensed under MIT with a commercial hosted option. ([Read more](/details/featbit.md)) `Open Source` `Self Hosted` `Freemium` `Free Plan` `Api` `.NET` `SignalR` `Openfeature`
- [FeatureProbe](https://featureprobe.org) - FeatureProbe is an open source feature management service providing feature flags, canary releases, and A/B testing with a visual management interface. It supports self-hosted deployment and offers SDKs for multiple languages. Pricing model: open source, self-hosted. ([Read more](/details/featureprobe.md)) `Open Source` `Self Hosted` `Api`
- [FeatureVisor](https://featurevisor.com) - Feature management for developers with GitOps. An open-source platform that enables teams to manage feature flags, targeting rules, and rollouts using version-controlled configuration files. ([Read more](/details/featurevisor.md)) `Open Source` `Gitops` `Typescript`
- [FF4J](https://ff4j.org/) - FF4J (Feature Flipping for Java) is an open-source feature flag framework for Java applications with a web console, REST API, and integrations for Spring Boot, JEE, and microservices. It supports property-based flip conditions and audit trails. Apache 2.0 licensed. ([Read more](/details/ff4j.md)) `Open Source` `Self Hosted` `Free Plan` `Api` `Java` `Spring Boot` `Apache 2 0`
- [Flagr](https://openflagr.github.io/flagr) - An open-source feature flagging, A/B testing, and dynamic configuration microservice written in Go. It provides a self-hosted solution for managing feature flags and running experiments without vendor lock-in. ([Read more](/details/flagr.md)) `Open Source` `Self Hosted` `Go` `A B Testing`
- [Flagsmith](https://flagsmith.com/) - Flagsmith is an open-source feature flag and remote config service that can be self-hosted or used via a managed cloud. It supports multivariate flags, segment targeting, and analytics integrations. The core platform is BSD-3 licensed with a commercial cloud offering. ([Read more](/details/flagsmith.md)) `Open Source` `Self Hosted` `Freemium` `Free Plan` `Api` `Remote Config`
- [Flipt](https://flipt.io/) - Flipt is a self-hosted, open-source feature flag solution designed for developers who need a lightweight, GitOps-friendly flag management system. It provides a UI, REST/gRPC APIs, and client SDKs. Licensed under AGPL-3.0 with a commercial enterprise edition. ([Read more](/details/flipt.md)) `Open Source` `Self Hosted` `Free Plan` `Enterprise` `Api` `Gitops` `AGPL-3.0`
- [GoFeatureFlag](https://gofeatureflag.org/) - GoFeatureFlag is a lightweight, open-source feature flag provider written in Go that reads flags from files, databases, or cloud storage. It supports OpenFeature providers, multiple targeting rules, and can run as a standalone service or library. MIT licensed. ([Read more](/details/gofeatureflag.md)) `Open Source` `Self Hosted` `Free Plan` `Api` `Go` `Openfeature` `Gitops`
- [Nona](https://github.com/nona-oss/nona) - Nona is an open-source remote configuration and feature flag service exposing a single REST API with support for multiple environments and official JavaScript and .NET client libraries. It is self-hostable via Docker and is licensed under Apache-2.0, positioned as an alternative to Firebase Remote Config. ([Read more](/details/nona.md)) `Open Source` `Self Hosted` `Apache 2 0`
- [Togglz](https://www.togglz.org/) - Togglz is a Java-focused open-source feature toggle library that integrates with Spring, CDI, and Jakarta EE. It provides an admin console, multiple state repositories (DB, Redis, file), and activation strategies. Licensed under Apache 2.0. ([Read more](/details/togglz.md)) `Open Source` `Self Hosted` `Free Plan` `Api` `Java` `Spring` `Apache 2 0`

## Experimentation First

- [Eppo](https://www.geteppo.com) - A next-generation A/B experimentation platform that enables entrepreneurial culture. Provides warehouse-native experimentation with feature flags, metric tracking, and experiment analysis. ([Read more](/details/eppo.md)) `Paid` `A B Testing` `Warehouse Native` `Experimentation`
- [GrowthBook](https://growthbook.io/) - GrowthBook is an open-source experimentation platform that combines feature flags with A/B testing, built for data teams and engineers. It connects to existing data warehouses (Snowflake, BigQuery, Postgres) for metric analysis. The core is MIT licensed with a hosted cloud version. ([Read more](/details/growthbook.md)) `Open Source` `Self Hosted` `Freemium` `Free Plan` `Api` `A B Testing` `Warehouse Native`
- [Optimizely Feature Experimentation](https://www.optimizely.com/products/feature-experimentation) - Optimizely Feature Experimentation is an enterprise experimentation and feature management product from the digital experience platform vendor. It combines feature flags with statistical experimentation, personalization, and analytics. Pricing is custom enterprise contracts. ([Read more](/details/optimizely-feature-experimentation.md)) `Paid` `Enterprise` `Api` `A B Testing` `Personalization` `Digital Experience`
- [PostHog](https://posthog.com/) - PostHog is an open-source product analytics suite that includes feature flags, session replay, and experimentation. It can be self-hosted or used as a managed service, with a generous free tier. The platform is MIT licensed and targets product engineers. ([Read more](/details/posthog.md)) `Open Source` `Self Hosted` `Freemium` `Free Plan` `Api` `Product Analytics` `Session Replay`
- [Split.io](https://split.io/) - Split is a feature delivery platform that combines feature flags with experimentation, observability, and progressive delivery for enterprise teams. It offers a free developer tier and enterprise plans with advanced targeting, governance, and integrations. ([Read more](/details/split-io.md)) `Freemium` `Free Plan` `Paid` `Enterprise` `Api` `Progressive Delivery` `Observability`
- [Statsig](https://statsig.com/) - Statsig is a feature management and experimentation platform built for product teams at scale, offering automated experiment analysis, feature gates, and dynamic configs. It provides a free tier for small teams and usage-based pricing for enterprises. Not open source. ([Read more](/details/statsig.md)) `Freemium` `Free Plan` `Paid` `Enterprise` `Api` `Ai Powered` `Automated Analysis`

## Managed Platforms

- [ABTasty](https://www.abtasty.com) - A customer experience optimization and feature management company. Provides a managed platform for feature flags, A/B testing, personalization, and user experience optimization. ([Read more](/details/abtasty.md)) `Paid` `A B Testing` `Personalization` `Api`
- [Apptimize](https://apptimize.com) - Enables teams to run A/B tests, rollout and manage new features, and deliver personalized user experiences. A cross-platform feature management and experimentation solution for web and mobile applications. ([Read more](/details/apptimize.md)) `Paid` `A B Testing` `Mobile First` `Personalization`
- [ConfigCat](https://configcat.com/) - ConfigCat is a hosted feature flag and configuration service with a focus on simplicity and GDPR compliance. It offers a free tier for low-volume use, team collaboration features, and SDKs for all major platforms. The service is proprietary with EU data residency options. ([Read more](/details/configcat.md)) `Freemium` `Free Plan` `Paid` `Enterprise` `Api` `GDPR` `Simple`
- [DeployRamp](https://www.deployramp.com) - An AI-powered platform that automatically wraps risky code changes in feature flags. Helps teams deploy code more safely by intelligently identifying and flagging high-risk changes. ([Read more](/details/deployramp.md)) `Ai Powered` `Paid` `Api`
- [DevCycle](https://devcycle.com/) - DevCycle is a managed feature management platform built for developer experience, offering variable-based flags, edge delivery, and integrations with Vercel, Netlify, and Kubernetes. It provides a free tier for small teams and usage-based paid plans. ([Read more](/details/devcycle.md)) `Freemium` `Free Plan` `Paid` `Enterprise` `Api` `Edge` `Developer Experience`
- [Featureflip](https://featureflip.dev) - Featureflip is a full-featured feature flag platform that automatically removes its own dead flags by submitting pull requests. It offers a free plan with up to 10 flags, 2 environments, 1 project, 3 users, and no usage caps. A developer-focused solution for managing feature toggles across applications. ([Read more](/details/featureflip.md)) `Freemium` `Api` `Dead Flag Cleanup`
- [FeatureHub](https://www.featurehub.io) - A highly scalable cloud-native platform serving features in near real time. Provides feature flag management with enterprise-grade scalability and real-time flag evaluation. ([Read more](/details/featurehub.md)) `Paid` `Api` `Real Time` `Cloud Native`
- [Flagpool](https://flagpool.io) - Flagpool is a feature flag management platform focused on simplicity and ease of use. Its free plan allows creating up to 10 new flags per month with unlimited requests and targeting rules. Designed for teams that want straightforward feature toggle management without complexity. ([Read more](/details/flagpool.md)) `Freemium` `Api` `Simple`
- [Flagship](https://flagship.io) - Feature management and feature experimentation platform. Enables teams to manage feature flags and run experiments across web, mobile, and server-side applications. ([Read more](/details/flagship.md)) `Paid` `A B Testing` `Experimentation`
- [Hypertune](https://www.hypertune.com) - Type-safe feature flags, A/B testing, analytics, and app configuration with Git-style version control. Provides a strongly-typed configuration platform for feature management. ([Read more](/details/hypertune.md)) `Paid` `A B Testing` `Developer Experience` `Api`
- [LaunchDarkly](https://launchdarkly.com/) - LaunchDarkly is a feature management platform for enterprise teams to control feature rollouts, targeting, and experimentation across applications. It provides SDKs for 25+ languages, real-time flag updates, and integrations with CI/CD, observability, and analytics tools. Pricing is enterprise-focused with custom contracts. ([Read more](/details/launchdarkly.md)) `Enterprise` `Paid` `Api` `Ai Powered` `Real Time` `Targeting`
- [Molasses](https://www.molasses.app/) - A suite of feature flag and A/B testing tools that allows teams to ship code more often and with fewer incidents. Provides feature management capabilities for controlled software delivery. ([Read more](/details/molasses.md)) `Paid` `A B Testing` `Api`
- [PreFab](https://prefab.cloud) - Offers feature flags, dynamic log levels, and remote config as a service. A managed platform for feature management and remote configuration of applications. ([Read more](/details/prefab.md)) `Paid` `Remote Config` `Api`
- [Rollgate](https://rollgate.io) - Rollgate is an EU-hosted feature flag management platform with scheduled releases, instant rollback, and A/B testing capabilities. It includes 12 SDKs and offers a free plan up to 500K API requests per month, unlimited flags, 3 team members, and no credit card required. Built for European teams prioritizing data residency. ([Read more](/details/rollgate.md)) `Freemium` `Eu Hosted` `A B Testing` `Scheduled Releases`
- [Tggl](https://tggl.io) - A platform designed for seamless feature flag management and release orchestration, enabling teams to innovate rapidly and efficiently. Provides feature flags and release management capabilities. ([Read more](/details/tggl.md)) `Paid` `Api` `Progressive Delivery`
- [Toggled.dev](https://toggled.dev) - Toggled.dev is an enterprise-ready, scalable multi-regional feature toggles management platform. Its free plan includes up to 10 flags, two environments, unlimited requests, an SDK, analytics dashboard, release calendar, and Slack notifications. All features are included in the free plan with no usage limits. ([Read more](/details/toggleddev.md)) `Freemium` `Multi Regional` `Enterprise` `Slack Integration`

## OpenFeature Providers

- [CloudBees](https://docs.cloudbees.com) - A cloud-based platform that provides end-to-end automated software delivery. Offers feature management and feature flag capabilities as part of its CI/CD and DevOps platform with OpenFeature SDK support. ([Read more](/details/cloudbees.md)) `Paid` `Enterprise` `Openfeature` `Api`
- [Flagd](https://flagd.dev/) - Flagd is a lightweight, OpenFeature-compliant feature flag daemon that reads flag configurations from files, HTTP, or Kubernetes resources. It runs as a sidecar or standalone service and provides a gRPC/HTTP provider for OpenFeature SDKs. Apache 2.0 licensed. ([Read more](/details/flagd.md)) `Open Source` `Self Hosted` `Free Plan` `Api` `Kubernetes` `Sidecar` `Apache 2 0`
- [Harness](https://www.harness.io) - A continuous integration and continuous delivery platform for cloud and on-premise projects. Provides feature management and feature flag capabilities with OpenFeature SDK support as part of its software delivery platform. ([Read more](/details/harness.md)) `Paid` `Enterprise` `Openfeature` `Ci Cd`
- [Unleash Proxy](https://github.com/Unleash/unleash-proxy) - Unleash Proxy is an open-source edge proxy that sits between applications and the Unleash server, providing caching, OpenFeature provider support, and reduced latency for flag evaluation. It enables multi-language support via the OpenFeature standard. Apache 2.0 licensed. ([Read more](/details/unleash-proxy.md)) `Open Source` `Self Hosted` `Free Plan` `Api` `Edge` `Proxy` `Apache 2 0`

## Remote Config

- [Firebase Remote Config](https://firebase.google.com/docs/remote-config) - Firebase Remote Config is a cloud service from Google that lets you change app behavior and appearance without deploying new code. It integrates with Firebase Analytics and A/B Testing, offers a generous free tier, and scales with pay-as-you-go pricing. ([Read more](/details/firebase-remote-config.md)) `Free` `Freemium` `Api` `Mobile First` `Google Cloud` `A B Testing`

## SDKs & Libraries

- [Django Waffle](https://waffle.readthedocs.io) - A feature flipper for Django applications written in Python. Allows Django developers to toggle features on/off, run A/B tests, and control feature availability for specific users or groups. ([Read more](/details/django-waffle.md)) `Python` `Django` `Open Source`
- [Flipper](https://www.flippercloud.io/) - Feature flags and controls for Ruby apps and their client-side code. A Ruby library that enables Ruby on Rails and other Ruby applications to manage feature toggles. ([Read more](/details/flipper.md)) `Ruby` `Open Source`
- [Flopflip](https://github.com/tdeekens/flopflip) - Feature management for React apps backed by a flag provider of your choice. A TypeScript library that abstracts feature flag providers, allowing React applications to consume flags from any compatible source. ([Read more](/details/flopflip.md)) `React` `Typescript` `Open Source`
- [FunWithFlags](https://github.com/tompave/fun_with_flags) - Feature flags for Elixir applications. An open-source library that enables Elixir and Phoenix developers to manage feature toggles, target specific users, and control feature rollouts within their applications. ([Read more](/details/funwithflags.md)) `Elixir` `Open Source`
- [HappyKit](https://happykit.dev/) - Feature flags for Next.js applications. A TypeScript-based solution that enables Next.js developers to manage feature flags and control feature availability in their frontend and edge applications. ([Read more](/details/happykit.md)) `Next.js` `Typescript` `Edge`
- [Laravel Feature Flags](https://feature-flags.docs.ylsideas.co) - A feature flag option for Laravel written in PHP. Provides Laravel developers with a simple way to manage feature toggles within their PHP applications. ([Read more](/details/laravel-feature-flags.md)) `Php` `Laravel` `Open Source`
- [Laravel Pennant](https://laravel.com/docs/10.x/pennant) - A simple, lightweight feature flag package for Laravel written in PHP. Provides Laravel developers with feature toggle functionality integrated into the Laravel ecosystem. ([Read more](/details/laravel-pennant.md)) `Php` `Laravel` `Open Source`
- [OpenFeature](https://openfeature.dev/) - OpenFeature is a vendor-neutral, open-source specification and SDK framework for feature flagging, hosted by the CNCF. It provides unified APIs across languages and a provider ecosystem to connect to any flag management backend. Apache 2.0 licensed. ([Read more](/details/openfeature.md)) `Open Source` `Free Plan` `Api` `CNCF` `Vendor-Neutral` `Specification` `Apache 2 0`


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