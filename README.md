# awesome-open-source-self-hosted
Awesome Open Source Self Hosted

## Document

### PDF Processor
Name | Pipeline | Arrange | Convert to PDF | Compress | Place Image
---|---|---|---|---|---
[Stirling PDF](https://github.com/Stirling-Tools/Stirling-PDF) |✅|✅|✅|✅|✅


## Email

Name | Mail Server | Web Mail Client | Review | Resource Usage
---|---|---|---|---
[Postfix]() |✅|||
[Postal]() |✅|✅||
[Mailu](https://mailu.io/2.0/) |✅||4➕|
[IRedmail]() [🐳](https://github.com/iredmail/dockerized) |✅|||
[Mailcow](https://mailcow.email) |✅|||
[Mail-in-a-Box](https://mailinabox.email) |✅|||
[Mailpile](https://www.mailpile.is) |✅|||
[Docker Mailserver](https://github.com/docker-mailserver/docker-mailserver) |✅||53➕| 
[Maddy](https://maddy.email) |✅||117➕|
[Rainloop](https://www.rainloop.net) ||✅|| 
[Zimbra](https://www.zimbra.com) |✅|✅||
[Roundcube]() ||✅|34➕|
[Squirrelmail]() ||✅|13➕|

### Mail Validator and Checker
- [Google Postmaster](https://postmaster.google.com/)
- [DKIM Checker](https://mxtoolbox.com/dkim.aspx)
- [SPF Checker](https://mxtoolbox.com/SuperTool.aspx?action=spf)
- [DMARC Checker](https://dmarcly.com/tools/dmarc-checker)

### References
- [Google Postmaster - verify your self-hosted mail server](https://postmaster.google.com) using [DMARC, DKIM, and SPF](https://www.cloudflare.com/en-au/learning/email-security/dmarc-dkim-spf/)
- [Google - DMARC, DKIM and SPF](https://support.google.com/a/answer/81126?visit_id=638532177956139038-3838716887&rd=1#authentication)
- [awesome-opensource-email](https://github.com/Mindbaz/awesome-opensource-email)
- [Open source web email server](https://forwardemail.net/en/blog/open-source/web-email-server)
- [Looking for a lightweight email server that runs in Docker - 2021](https://www.reddit.com/r/selfhosted/comments/pqbhej/looking_for_a_lightweight_email_server_that_runs/)
- [Docker Mailserver Intro](https://docker-mailserver.github.io/docker-mailserver/latest/introduction/)

## Workflow Engines
Name | Github Stars | Resource Usage | Trigger | Container Executor | GUI Scripting | K8S | Used By | Dev. Language | Nodes Drag n Drop | ML & Data Eng. | Cons
---|---|---|---|---|---|---|---|---|---|---|---
[Argo Workflows](https://github.com/argoproj/argo-workflows) | 14.6k | 250mb | Webhook, API | Custom Image | ✅ | Required | Google, IBM, Metaflow, Kubeflow | Go | ❌ ||
[Kubeflow]()|||||||||||
[Flyte]()|| ❌ ||||||Go|||K8s on-premise Flyte the Hard Way too complicated
[Metaflow]()||||||||Python|||
[Kestra](https://github.com/kestra-io/kestra) | 7k | 1300mb | Webhook, API |||||Java||Data pipeline, ml model deployment, etl|
[N8n](https://github.com/n8n-io/n8n)| 42.3k | 400mb |||||||||Complexity on creating non-Alpine custom Docker image
[Prefect](https://github.com/PrefectHQ/prefect)| 15.3k | 500mb |||||| Python ||Data pipeline, ml|Somehow complex, not only prefect server
[Windmill]()||❌|||||||||K8s installation problem - memory
[Activepieces]()|||||||||||
[Dagster]()|||||||||||
[Cadence]()|||||||||||
[Conductor]()|||||||||||
[Huginn]()|||||||||||
[Node-RED]()|||||||||||
[Apache DolphinScheduler]()|||||||||||
[Temporal]()|||||||||||

### Installations
- [Workflow Engines Installation on K3d](./workflow-engine/k3d-installation.md)

### References
- [Awesome Workflow Engines](https://github.com/meirwah/awesome-workflow-engines?tab=readme-ov-file)

## Serverless
Name | Features | Review | Resource Usage
---|---|---|---
[OpenFaas]() |||

### References
- [Awesome Serverless](https://github.com/anaibol/awesome-serverless)
