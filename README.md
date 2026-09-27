# Awesome-Application-Performance-Monitoring

## Top Application Performance Monitoring (APM) Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Distributed Tracing, Code-Level Profiling & Full-Stack Observability*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Application Performance Monitoring (APM)**. These tools monitor, analyze, and optimize application performance, transaction traces, error rates, resource consumption, and user experience across cloud-native and hybrid environments.

**Examples** include Datadog, New Relic, Dynatrace, AppDynamics, Elastic APM, Instana, Scout APM, Atatus, ManageEngine Applications Manager, and SolarWinds APM (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom instrumentation, and transparent observability pipelines — ideal for engineering teams, SREs, and developers building vendor-neutral APM solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Datadog APM](https://www.datadoghq.com/product/apm/)**  
  AI-powered code-level distributed tracing from browser and mobile applications to backend services and databases, correlating traces with logs, metrics, RUM, and security signals.

- **[New Relic APM 360](https://newrelic.com/platform/application-monitoring)**  
  Full-stack observability platform with distributed tracing, error tracking, infrastructure metrics, logs-in-context, and 780+ integrations for end-to-end application visibility.

- **[Dynatrace](https://www.dynatrace.com/platform/application-observability/)**  
  AI-driven application observability with continuous topology discovery, code-level profiling, database dependency mapping, and OpenTelemetry support at enterprise scale.

- **[Cisco AppDynamics](https://www.appdynamics.com/)**  
  Hybrid application observability platform with auto-discovery, business transaction monitoring, Cognition Engine for anomaly detection, and SAP monitoring capabilities.

- **[Elastic APM](https://www.elastic.co/observability/application-performance-monitoring)**  
  Part of the Elastic Stack, providing distributed tracing, service maps, trace-based sampling, and OpenTelemetry/Jaeger ingestion with native Kibana visualization.

- **[IBM Instana](https://www.ibm.com/products/instana)**  
  Enterprise observability platform with AutoProfile™ continuous production profiling, Dynamic Graph dependency modeling, synthetic monitoring, and automated remediation workflows.

- **[Scout APM](https://scoutapm.com/)**  
  Lightweight, production-grade application monitoring focused on line-of-code visibility, N+1 query detection, memory bloat tracking, and intelligent error grouping.

- **[Atatus APM](https://www.atatus.com/product/apm/)**  
  Full-stack monitoring with distributed tracing, slow database query analysis, external API monitoring, continuous profiling, and RUM integration at flat-rate per-host pricing.

- **[ManageEngine Applications Manager](https://www.manageengine.com/products/applications_manager/)**  
  Comprehensive APM with byte-code instrumentation for Java, .NET, PHP, Node.js, and Python, plus infrastructure, database, and end-user experience monitoring.

- **[SolarWinds APM](https://www.solarwinds.com/observability)**  
  Unified full-stack observability platform with AI-driven analytics, dynamic discovery and mapping, user-centric APM, and developer-centric tooling.

## Open-Source GitHub Projects

- **[inspectIT Ocelot](https://github.com/inspectIT/inspectit-ocelot)**  
  Java agent for collecting application performance, tracing, and behavior data via OpenTelemetry and OpenCensus. Actively maintained successor to the original inspectIT APM project, with 213+ stars and active development. 

- **[Apache SkyWalking](https://github.com/apache/skywalking)**  
  Application performance monitor especially designed for microservices, cloud-native, and container-based architectures. Provides distributed tracing, service mesh telemetry, metrics aggregation, and alerting. One of the most widely adopted open-source APM solutions.

- **[Pinpoint](https://github.com/pinpoint-apm/pinpoint)**  
  APM tool for large-scale distributed systems, written in Java. Provides distributed transaction tracing, server map visualization, and real-time application monitoring with minimal performance overhead. Originally developed by NAVER.

- **[Jaeger](https://github.com/jaegertracing/jaeger)**  
  Distributed tracing platform originally built by Uber, now a CNCF graduated project. Provides end-to-end distributed tracing, root cause analysis, service dependency analysis, and performance/latency optimization. Native OpenTelemetry support.

- **[OpenTelemetry](https://github.com/open-telemetry)**  
  Vendor-neutral collection of APIs, SDKs, and tools for instrumenting, generating, collecting, and exporting telemetry data (metrics, logs, traces). The de facto standard for modern APM instrumentation, with agents for every major language.

- **[SigNoz](https://github.com/SigNoz/signoz)**  
  Open-source APM and observability platform built natively on OpenTelemetry. Provides distributed tracing, metrics, logs, exceptions, and dashboards in a single pane. Self-hostable with ClickHouse backend.

- **[Uptrace](https://github.com/uptrace/uptrace)**  
  Open-source APM tool with distributed tracing, metrics, and logs based on OpenTelemetry. Supports ClickHouse, PostgreSQL, and SQLite backends with a clean, modern UI.

- **[Highlight.io](https://github.com/highlight/highlight)**  
  Open-source, full-stack monitoring platform combining session replay, error monitoring, and logging. Self-hostable with Docker, designed for modern web applications.

- **[Sentry](https://github.com/getsentry/sentry)**  
  Application monitoring and error tracking platform with performance monitoring capabilities, including transaction tracing, span-level analysis, and distributed tracing. Supports 100+ platforms with self-hosted option.

- **[SkyWalking Rover](https://github.com/apache/skywalking-rover)**  
  eBPF-based agent for Apache SkyWalking, providing process-level monitoring, network profiling, and topology discovery without code instrumentation.

- **[Pyroscope](https://github.com/grafana/pyroscope)**  
  Open-source continuous profiling platform (now part of Grafana Labs) for CPU, memory, and I/O profiling with low overhead. Correlates profiles with traces and metrics for code-level performance analysis.

- **[OpenAPM](https://github.com/openapm)**  
  Node.js APM using Prometheus, providing application performance metrics via a lightweight agent and Prometheus exposition.

- **[etrace](https://github.com/etrace-io/etrace)**  
  Robust and functional Application Performance Monitor (APM) system with 62+ stars, providing core tracing and performance monitoring capabilities.

- **[inspectIT (Legacy)](https://github.com/inspectIT/inspectIT)**  
  The original open-source APM tool for analyzing Java (EE) applications. Now unmaintained in favor of inspectIT Ocelot, but still referenced for historical context with 538+ stars.

### Additional Strong Open-Source Options

- **Elastic APM Server** — Open-source APM server component, part of the Elastic Stack, with agents for Java, .NET, Go, Ruby, Python, Node, PHP, and RUM.
- **Tracing Libraries (OpenTracing/OpenCensus)** — Legacy instrumentation libraries that paved the way for OpenTelemetry; still relevant for older systems.
- **Micrometer Tracing** — Application observability facade for JVM-based applications, supporting OpenTelemetry and Brave backends.
- **Prometheus + Grafana + Tempo** — Community-favored open-source stack for metrics, dashboards, and distributed tracing when combined with instrumentation libraries.
- **RealOpInsight** — Monitor and observe end-user services atop Kubernetes, Zabbix, and Nagios, with SLA/SLO tracking via Prometheus metrics and built-in dashboards.

**Frameworks for building custom APM solutions**: Combine **OpenTelemetry** for instrumentation, **Jaeger** or **Tempo** for trace storage, **Prometheus** for metrics, **Loki** for logs, and **Grafana** for visualization. For Java-specific needs, **inspectIT Ocelot** provides a production-ready agent. For full-stack open-source APM, **SigNoz** or **Uptrace** offer integrated self-hosted alternatives to SaaS platforms.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- APM tools must comply with data privacy regulations (GDPR, CCPA, etc.) and industry-specific compliance requirements.
- Self-hosted open-source solutions require proper infrastructure, security hardening, and ongoing maintenance.

---

**Made for SREs, DevOps engineers, platform teams, and application developers.**  
Let's make application performance monitoring more open, observable, and vendor-neutral.
