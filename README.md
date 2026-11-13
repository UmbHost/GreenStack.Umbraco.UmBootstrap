# GreenStack.Umbraco.UmBootstrap

A GitHub template repository for Umbraco 17 with UmBootstrap, preconfigured for [GreenStack](https://umbhost.net/sustainable-cloud-hosting/modern-umbraco-hosting) hosting.

## What's included

- Umbraco 17 on .NET 10 with [UmBootstrap](https://marketplace.umbraco.com/package/umbraco.community.templates.umbootstrap) starter kit
- The [UmbHost GreenStack package](https://www.nuget.org/packages/UmbHost.GreenStack.Umbraco.Configuration), which configures the site for GreenStack when it runs there: forwarded headers, the HTTPS checks, Data Protection keys on shared storage, and load balancing when the site runs 2 or more replicas
- Multi-stage Dockerfile exposing port 8080
- Docker launch profile (HTTP)
- Dependabot configured for weekly Umbraco updates

## Getting started

1. Click **"Use this template"** on GitHub to create a new repository
2. Clone your new repository
3. Follow the [Getting Started with Umbraco 17 on GreenStack](https://umbhost.net/gb/blog/2026/01/getting-started-with-umbraco-17-on-greenstack-with-github) guide

Alternatively, install via dotnet new:

```bash
dotnet new install UmbHost.GreenStack.Umbraco.UmBootstrap
dotnet new greenstack-umbraco-umbootstrap -n MyProject
```

## GreenStack

- [Purchase GreenStack hosting](https://umbhost.net/sustainable-cloud-hosting/modern-umbraco-hosting)
- [GreenStack documentation](https://my.umbhost.net/knowledgebase/17/GreenStack)
- [GreenStack CI/CD samples](https://github.com/UmbHost/GreenStack.CICD.Samples)

## License

MIT
