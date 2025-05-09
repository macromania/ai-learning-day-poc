---
page_type: sample
languages:
- azdeveloper
- bicep
products:
- azure
urlFragment: azd-aistudio-starter
name: Azure AI Studio starter template
description: Creates an Azure AI Studio hub, project and required dependent resources including Azure OpenAI Service, Cognitive Search and more.
---
<!-- YAML front-matter schema: https://review.learn.microsoft.com/en-us/help/contribute/samples/process/onboarding?branch=main#supported-metadata-fields-for-readmemd -->

# Azure AI Studio Starter Template

### Quickstart

To learn how to get started with any template, follow the steps in [this quickstart](https://learn.microsoft.com/azure/developer/azure-developer-cli/get-started?tabs=localinstall&pivots=programming-language-nodejs) with this template(`Azure-Samples/azd-aistudio-starter`)

This quickstart will show you how to authenticate on Azure, initialize using a template, provision infrastructure and deploy code on Azure via the following commands:

```bash
# Log in to azd. Only required once per-install.
azd auth login

# First-time project setup. Initialize a project in the current directory, using this template.
azd init --template Azure-Samples/azd-aistudio-starter

# Provision and deploy to Azure
azd up
```

Choose `swedencentral` as the region when prompted. This is the only region where required AI Models are available.

### Get Environment Variables

After the `azd up` command completes, run following command to create environment variables in the `.env` file.
