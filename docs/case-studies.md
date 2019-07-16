---
title: Case studies
currentMenu: case-studies
introduction: A collection of case studies of serverless PHP applications built using Bref. Learn about performances, costs and migrations from existing projects.
---

This page collects case studies of serverless PHP applications built with or migrated to Bref.

These help learn for real use cases about costs, performances and migration efforts.

## Websites

- [returntrue.win](https://mnapoli.fr/serverless-case-study-returntrue/)

A case study of the development of the [returntrue.win](https://returntrue.win/) website using AWS Lambda, including a cost analysis.

## Workers

- 🇫🇷 [Enoptea](https://www.enoptea.fr/serverless-et-php/)

Enoptea is a french startup that migrated their infrastructure of PHP workers from EC2 to Lambda. They halved their AWS costs and increased their performances while spending less time managing their servers.

- [PrettyCI.com](https://mnapoli.fr/serverless-case-study-prettyci/)

[PrettyCI](https://prettyci.com/) is a SaaS providing continuous integration for PHP coding standards. Internally, it runs PHP-CS-Fixer or CodeSniffer on AWS Lambda using Bref. This article is a good introduction on how AWS Lambda can be a good solution to run workers and background jobs.

- [MyBuilder](https://mybuilder.com)

MyBuilder is an online marketplace matching tradespeople with home owners. They used Lambda with Bref to create a highly scalable on-demand microservice to generate PDF reports. The solution involved [creating their own layer](https://tech.mybuilder.com/compiling-wkhtmltopdf-aws-lambda-with-bref-easier-than-you-think/) to include a self-compiled binary file to use alongside Bref's base PHP layer.
