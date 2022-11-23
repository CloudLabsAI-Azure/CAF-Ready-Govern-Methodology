# CAF Ready/Govern Methodology

The Microsoft CAF Ready/Govern Methodology for Azure is proven guidance that's designed to help you create and implement the business and technology strategies necessary for your organization to succeed in the cloud. It provides best practices, documentation, and tools that cloud architects, IT professionals, and business decision-makers need in order to successfully achieve short-term and long-term objectives.

The CAF Ready/Govern Methodology brings together cloud adoption best practices from Microsoft employees, partners, and customers. It provides a set of tools, guidance, and narratives that help shape technology, business, and people strategies for driving desired business outcomes during your cloud adoption effort. By using the Microsoft CAF Ready/Govern Methodology for Azure best practices, organizations can better align their business and technical strategies to ensure success.

## Lab Context 	

In this workshop, you will learn how to deploy different landing zones to host the workloads that you plan to build in or migrate to the cloud for different scenarios. You will be using the Azure Landing Zone Accelerator an Azure portal-based deployment that will provide a full implementation of the conceptual architecture, along with opinionated configurations for key components such as management groups and policies. You will also experience existing blueprint samples CAF Migration Landing Zone to deploy the basic foundation for migrating low-risk assets, CAF Foundation zone to deploy the minimum tools needed to begin developing a governance strategy. Also, you will see how to use Azure server management services for managing servers at scale.

Consider an analogy of a journey to a destination. A traveler may be at any *position* on that journey, but the *destination* is the same.

![Diagram of Azure landing zone journey.](images/alz-journey.png)

These *positions* represent where organizations are today in their cloud adoption plans and the specific guidance needed to continue to develop the cloud environment.

| Position | Description | Further guidance |
|--|--|--|
| **Start** | For organizations who are at the beginning of their cloud adoption journey (also referred to as *greenfield*) who are looking to implement a new cloud environment, based on best practices and proven architectural patterns. <br> Start with the Azure landing zone conceptual architecture to understand the recommended end state. <br> Next, explore each of the design areas to understand the key themes that comprise the considerations and decisions needed in order to design and implement the landing zone that best fits your requirements | [What is an Azure landing zone](https://docs.microsoft.com/azure/cloud-adoption-framework/ready/landing-zone/) <br> [Azure landing zone design areas](https://docs.microsoft.com/azure/cloud-adoption-framework/ready/landing-zone/design-areas) |
| **Align** | For organizations who have an existing environment that needs modification to align to the Azure landing zone target architecture and best practices (also referred to as *brownfield*). <br> Use the transition from brownfield guidance in order to understand the decision points and technical approach to refactoring environments to align with the guidance in the Ready methodology | [Refactor a landing zone](https://docs.microsoft.com/azure/cloud-adoption-framework/ready/landing-zone/refactor) |
| **Enhance** | For environments that are already in line with best practices but the organization is looking to add additional controls or features. <br> Explore the articles that explain the considerations as part of enhancing the key ongoing processes for cloud environments, such as management, governance, and security. | [Enhance guidance for management](https://docs.microsoft.com/azure/cloud-adoption-framework/ready/considerations/landing-zone-operations) <br> [Enhance guidance for governance](https://docs.microsoft.com/azure/cloud-adoption-framework/ready/considerations/landing-zone-governance) <br> [Enhance guidance for security](https://docs.microsoft.com/azure/cloud-adoption-framework/ready/considerations/landing-zone-security) |

## Exercise 1: Implement Azure landing zone accelerator

In this exercise, start with the Azure landing zone conceptual architecture to understand the recommended end state. Next, explore each landing zone design areas to understand the key themes that comprise the considerations and decisions needed and deploy the ready-made deployment experience available which we call the Azure landing zone accelerator.

## Exercise 2: Start small and expand a migration landing zone

For this scenario, you have minimal requirements and will iterate into the conceptual architecture over time. In this exercise, you will create a blueprint definition based on CAF Migration Landing Zone, explore the capabilities it provides and assign it at the subscription level to get started with Azure. Also, you will update the blueprint to match the DMZ Network architecture of Tailwind Traders.

## Exercise 3: Enhance your landing zone

In this exercise, you will implement additional configurations to the Azure Landing Zone accelerator an Azure policy for governance enhancements over deployable regions. You will also enhance your security posture by deploying azure Sentinel.
