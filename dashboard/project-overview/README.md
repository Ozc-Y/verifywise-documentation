---
description: Overview, project risks, vendor risks and settings for individual projects
---

# Project overview

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption><p>A project overview on the default tab</p></figcaption></figure>

On the project overview screen, there are four tabs:

* **Overview:** A general picture of the project, containing details on project ownership, recent updates, and the risks associated with the project
* **Project risks:** A list of risks directly associated with the project, alongside diagnostic information such as the severity of each risk
* **Vendor risks:** A list of risks related to vendors and third party products, alongside diagnostic information about each risk
* **Settings:** Configuration options for the project, including project information, risk classification and ownership

## Project risks tab

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption><p>"Project risks" tab</p></figcaption></figure>

You can view details about each project risk in this list. These risks are all directly related to how you are developing or implementing this project. Risks associated with vendors or third party components of your projects can be managed in the "Vendor risks" tab.

Each risk entry has the following information associated with it:

* **Risk name:** The name used to identify a given risk
* **Impact (Low, Medium, Medium High, High, Very High):** The scale of the risk's impact on services
* **Owner:** The person responsible for identifying, tracking and mitigating this risk
* **Severity (Negligible, Minor, Moderate, Major, Critical):** The severity of the consequences of the risk
* **Likelihood (Rare, Unlikely, Possible, Likely, Almost Certain):** The probability of the risk occurring
* **Risk level (Low, Medium, High, Very High)**
* **Mitigation:** Click 'Details' to view information about how this risk is being mitigated.
* **Final Risk Level (Low, Medium, High):** The level of risk after mitigation measures have been implemented

You can click `Add new risk` to add a new risk to the list. See [Adding a new project risk](adding-a-new-project-risk.md) for details.

**NOTE:** Impact and Severity are different metrics. Impact measures how much of your services will be affected if the risk occurs, whereas Severity describes how deeply each relevant component of your system or application will be affected by the risk.

## Vendor risks tab

<figure><img src="../../.gitbook/assets/image (3).png" alt=""><figcaption><p>"Vendor risks" tab</p></figcaption></figure>

In this list, you can view details about risks introduced to your project through vendors and third-party components. You need to keep track of vendor lists, even though they are not directly under your control.

Each vendor risk entry has the following information associated with it:

* **Vendor Name:** The name of the vendor related to the risk
* **Risk Name:** The risk associated with this vendor
* **Owner:** The person responsible for identifying, tracking and mitigating this risk
* **Risk Level (Low, Medium, High):** The danger posed by the risk to smooth operations and/or regulatory compliance
* **Review Date:** The most recent date the risk was reviewed

You can click `Add new risk` to add a new risk to the list. See [Adding a new vendor risk](adding-a-new-vendor-risk.md) for details.

## Settings tab

<figure><img src="../../.gitbook/assets/image (4).png" alt=""><figcaption><p>"Settings" tab</p></figcaption></figure>

Here, you can configure several options for the entire project:

* Project title
* Goal
* Owner
* Start date

Furthermore, team members can be added to the project here.

The project's risk classification and, if applicable, high-risk role (for a high-risk AI application) can be set on this screen.

Click `Save` on the bottom right of the screen to save your changes.

**NOTE:** The AI risk classification used in the _EU AI Act_ can be found [here](https://artificialintelligenceact.eu/high-level-summary/). There are significant and subtle differences between different risk classifications under the _Act_, especially between high-risk and limited-risk AI systems. A thorough understanding of how to classify the risk level of an AI system is paramount to proper AI governance.

**NOTE:** For high-risk AI systems, both deployers and developers are under additional regulations. However, developers of high-risk AI systems being used in the European Union are under greater scrutiny compared to deployers (users) of high-risk AI systems.

