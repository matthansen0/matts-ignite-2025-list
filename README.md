# 🚀 Matt's Ignite 2025 Announcements

> *The Ignite Book of News is great, but it doesn't include all the great work across the rest of the Azure products.*

This is a personal collection of announcements and updates from **Microsoft Ignite 2025**, specific to Azure, organized by service category for navigation and reference.

**🎯 What's Inside:** 100+ announcements across Infrastructure, Apps, Data, AI, and Security with direct links to official documentation and blog posts.

---

## 📋 Table of Contents

- [🏗️ Azure Infrastructure](#-azure-infrastructure)
- [🔧 Azure Apps](#-azure-apps)  
- [📊 Azure Data](#-azure-data)
- [🤖 Azure AI](#-azure-ai)
- [🔒 Security & Governance](#-security--governance)

---

## 🏗️ Azure Infrastructure

> *Core infrastructure services, networking, security, and foundational Azure capabilities*

### Key Announcements

- **Storage:**
    - [Vaulted Backup for ADLS](https://azure.microsoft.com/en-us/updates/?id=523975)  
      *Immutable backup protection for Azure Data Lake Storage*
    - [ANF 7.2 PB Cool Tier Volumes](https://azure.microsoft.com/en-us/updates/?id=516656)  
      *Azure NetApp Files massive capacity cool storage tier*
    - [ANF 2 PB & 50 GBps "breakthrough" mode](https://azure.microsoft.com/en-us/updates/?id=525150)  
      *Azure NetApp Files ultra-high performance configuration*
    - [Lustre vNext - 25PB and 512 GBps](https://techcommunity.microsoft.com/blog/azurehighperformancecomputingblog/announcing-the-public-preview-of-amlfs-20-azure-managed-lustre-new-sku-for-massi/4470665)  
      *Azure Managed Lustre 2.0 for massive scale HPC workloads*
    - [Azure Blob Smart Tiering](https://techcommunity.microsoft.com/blog/azurestorageblog/unlocking-storage-optimizations-smart-tiering-for-blobs-and-adls-in-azure-storag/4469811)  
      *Automated lifecycle management for blob storage optimization*

- **Operations:**
    - [Azure Infra, Data & Cyber Resiliency](https://techcommunity.microsoft.com/blog/azurearchitectureblog/azure-resiliency-proactive-continuity-with-agentic-experiences-and-frontier-inno/4469693)
    - [Operations Center in Machine Configuration Management](https://techcommunity.microsoft.com/blog/azurearcblog/unified-configuration-and-governance-for-azure-windows-server-and-linux-server/4469769)  
      *Unified governance for Azure Arc-enabled servers*
    - [Capacity Guidance in ASR](https://azure.microsoft.com/en-us/updates/?id=530073) | [Documentation](https://learn.microsoft.com/en-us/azure/site-recovery/alternative-vm-size-failover-flow)  
      *Azure Site Recovery intelligent VM sizing recommendations*
    - [Agentic Cloud Operations with Azure Copilot & Custom Azure Copilot Agents](https://techcommunity.microsoft.com/blog/azureinfrastructureblog/ushering-in-the-era-of-agentic-cloud-operations-with-azure-copilot/4469664)  
      *AI-powered autonomous cloud infrastructure management*
        - [Deployment Agent](https://techcommunity.microsoft.com/blog/azureinfrastructureblog/announcing-deployment-capabilities-preview-in-azure-copilot/4471169)  
          *Automated Azure resource deployment and configuration*
        - [Migrate Agent](https://techcommunity.microsoft.com/blog/azuremigrationblog/migration-agent---unlocking-transformation/4470205)  
          *AI-assisted cloud migration assessment and execution*
        - [Migrate Agent Demos](https://techcommunity.microsoft.com/blog/azuremigrationblog/azure-copilot-migration-agent---bringing-agentic-migration-and-modernization-to-/4471329)  
          *Hands-on demonstrations of migration automation capabilities*
    - [Azure Monitor Coverage Insights](https://techcommunity.microsoft.com/blog/azureobservabilityblog/introducing-monitoring-coverage-assess-and-improve-your-monitoring-posture-at-sc/4470752)
    - [Admin Center Virtualization Mode](https://techcommunity.microsoft.com/blog/windowsservernewsandbestpractices/introducing-windows-admin-center-virtualization-mode-vmode/4471024)
    - [Kubernetes Center](https://techcommunity.microsoft.com/blog/azureinfrastructureblog/announcing-kubernetes-center-preview-on-azure-portal/4471110)

- **Compute:**
    - **New VM SKUs:**
        - [DLsv7, DSv7, and ESv7 VMs based on Intel® Xeon® 6](https://techcommunity.microsoft.com/blog/azurecompute/announcing-preview-of-new-azure-dlsv7-dsv7-and-esv7-vms-based-on-intel%C2%AE-xeon%C2%AE-6-/4467928)
        - [EBSv6 VMs based on 5th Gen Intel® Xeon®](https://techcommunity.microsoft.com/blog/azurecompute/announcing-the-preview-of-the-new-azure-ebsv6-vms-based-on-the-5th-gen-intel%C2%AE-xe/4470139)
        - [Azure Intel® TDX Confidential VMs](https://techcommunity.microsoft.com/blog/azureconfidentialcomputingblog/azure-intel%C2%AE-tdx-confidential-vms-momentum/4470736)  
          *Trust Domain Extensions for hardware-based confidential computing*
        - [ND GB300 v6 - Hyper-optimized for Generative AI](https://techcommunity.microsoft.com/blog/azurehighperformancecomputingblog/azure-nd-gb300-v6-now-generally-available---hyper-optimized-for-generative-and-a/4469475)  
          *GPU VMs with NVIDIA GB300 for AI/ML training and inference*
        - [NCv6 RTX PRO 6000 Blackwell](https://azure.microsoft.com/en-us/updates/?id=530208)  
          *Professional GPU VMs with latest NVIDIA Blackwell architecture*
    - [Azure Boost Enhancements](https://techcommunity.microsoft.com/blog/azureinfrastructureblog/powering-modern-cloud-workloads-with-azure-boost-ignite-2025/4470793)  
      *Hardware acceleration for improved VM performance and efficiency*
    - [Azure Cobalt 200 - Next Cloud Native CPU](https://techcommunity.microsoft.com/blog/azureinfrastructureblog/announcing-cobalt-200-azure%E2%80%99s-next-cloud-native-cpu/4469807)  
      *Microsoft's custom Arm-based processor for cloud workloads*

- **Adaptive Cloud:**
    - [Arc Edge Video Indexer](https://techcommunity.microsoft.com/blog/azurearcblog/ignite-2025-preview---intelligent-real-time-video-insights-and-agents-with-azure/4470704)  
      *AI-powered video analytics for edge computing scenarios*
    - [Azure Local - Cloud Infrastructure for Distributed Locations](https://techcommunity.microsoft.com/blog/azurearcblog/what%E2%80%99s-new-in-azure-local-cloud-infrastructure-for-distributed-locations-enabled/4469773)  
      *Hyperconverged infrastructure solution for edge and remote sites*
    - [Arc-Enabled Azure Migrate](https://techcommunity.microsoft.com/blog/azurearcblog/accelerate-your-cloud-migration-journey-with-azure-arc-resource-discovery-in-azu/4469975)  
      *Resource discovery and assessment for hybrid cloud migrations*
    - [SQL Server Migration in Azure Arc - GA](https://techcommunity.microsoft.com/blog/microsoftdatamigration/sql-server-migration-in-azure-arc-%E2%80%93-generally-available/4471020)
    - [Arc Multi-Cloud Updates](https://techcommunity.microsoft.com/blog/azurearcblog/expanding-azure-arc-for-hybrid-and-multicloud-management/4470656)
    - [AKS Fleet Manager with Arc-enabled Kubernetes Clusters](https://learn.microsoft.com/en-us/azure/kubernetes-fleet/concepts-fleet-arc-integration)
    - [Foundry Local on Windows Server](https://techcommunity.microsoft.com/blog/windowsservernewsandbestpractices/microsoft-foundry-on-windows-server/4471093)
    - [AVD Hybrid Deployment Options](https://techcommunity.microsoft.com/blog/azurevirtualdesktopblog/announcing-new-hybrid-deployment-options-for-azure-virtual-desktop/4468781)

- **Networking:**
    - [NAT Gateway v2 - StandardV2 NAT Gateway and StandardV2 Public IP](https://techcommunity.microsoft.com/blog/azurenetworkingblog/announcing-the-public-preview-of-standardv2-nat-gateway-and-standardv2-public-ip/4458292)  
      *Next-generation network address translation with enhanced performance*
    - [ExpressRoute Scalable Gateway](https://learn.microsoft.com/en-us/azure/expressroute/scalable-gateway)  
      *High-performance private connectivity gateway for enterprise networks*

- **Misc:**
    - **IoT Announcements:**
        - [Bridging the Digital and Physical Worlds with Azure IoT Hub and Azure IoT Operations](https://techcommunity.microsoft.com/blog/iotblog/bridging-the-digital-and-physical-worlds-with-azure-iot-hub-and-azure-iot-operat/4469774)
        - [Azure IoT Hub with ADR Preview - Extending Azure Capabilities and Certificate Management](https://techcommunity.microsoft.com/blog/iotblog/azure-iot-hub-with-adr-preview-extending-azure-capabilities-and-certificate-mana/4465265)


## 🔧 Azure Apps

> *Application development, deployment, and management services*

### Key Announcements

- **Azure App Service:**
    - [App Service Managed Instance - Public Preview](https://techcommunity.microsoft.com/blog/appsonazureblog/announcing-public-preview-of-managed-instance-on-azure-app-service/4469930)
    - [Client Side App Configurations in Front Door](https://techcommunity.microsoft.com/blog/appsonazureblog/unlocking-client-side-configuration-at-scale-with-azure-app-configuration-and-az/4470781)

- **Azure Kubernetes Service (AKS):**
    - [Agentic CLI for AKS - Updates](https://azure.microsoft.com/en-us/updates/?id=523062) | [Documentation](https://learn.microsoft.com/en-us/azure/aks/cli-agent-for-aks-overview)  
      *AI-powered command line interface for Kubernetes cluster management*
    - [Pod Sandboxing in AKS](https://learn.microsoft.com/en-us/azure/aks/use-pod-sandboxing)  
      *Enhanced container isolation using hardware-based security boundaries*
    - [Managed System Node Pools in AKS Automatic](https://learn.microsoft.com/en-us/azure/aks/automatic/aks-automatic-managed-system-node-pools-about)  
      *Automated system workload management in AKS clusters*

- **Azure Functions:**
    - [Azure Functions Ignite 2025 Update](https://techcommunity.microsoft.com/blog/appsonazureblog/azure-functions-ignite-2025-update/4469815)

- **Logic Apps & Integration:**
    - [RabbitMQ Connector - General Availability](https://techcommunity.microsoft.com/blog/integrationsonazureblog/announcing-the-general-availability-of-the-rabbitmq-connector/4470639)
    - [Logic Apps Connectors Updates](https://azure.microsoft.com/en-us/updates/?id=527683) | [Additional Updates](https://azure.microsoft.com/en-us/updates/?id=531783)
    - [Healthcare Connectors in Logic Apps](https://azure.microsoft.com/en-us/updates/?id=531778)

- **Event-Driven Architecture:**
    - [Large Message Support in Event Hubs - General Availability](https://techcommunity.microsoft.com/blog/messagingonazureblog/general-availability-large-message-support-in-azure-event-hubs/4471094)

### Notable Updates

- **Development Platforms:**
    - [.NET 10 - General Availability](https://devblogs.microsoft.com/dotnet/announcing-dotnet-10/)

- **AI-Powered Development:**
    - [App Modernization with GitHub Copilot - AI Agents Rewriting the Playbook](https://techcommunity.microsoft.com/blog/appsonazureblog/ai-agents-are-rewriting-the-app-modernization-playbook/4470162)

---

## 📊 Azure Data

> *Data storage, analytics, databases, and data management services*

### Key Announcements

- **Data Platform Overview:**
    - [The New Frontier of Data for the Next Generation of Innovation](https://techcommunity.microsoft.com/blog/azuredatablog/the-new-frontier-of-data-for-the-next-generation-of-innovation/4463236)

- **PostgreSQL Services:**
    - [Azure HorizonDB - Announcement](https://techcommunity.microsoft.com/blog/adforpostgresql/announcing-azure-horizondb/4469710)  
      *Next-generation PostgreSQL-compatible database service*
    - [Build Smarter with Azure HorizonDB](https://techcommunity.microsoft.com/blog/adforpostgresql/build-smarter-with-azure-horizondb/4470302)  
      *Development capabilities and AI integration with HorizonDB*
    - [PostgreSQL for the Enterprise - Scale, Secure, Simplify](https://techcommunity.microsoft.com/blog/adforpostgresql/postgresql-for-the-enterprise-scale-secure-simplify/4470412)
    - [PostgreSQL Mirroring in Fabric](https://learn.microsoft.com/en-us/fabric/mirroring/azure-database-postgresql)

- **Cosmos DB & Document Services:**
    - [Azure Document DB - Generally Available](https://devblogs.microsoft.com/cosmosdb/azure-documentdb-is-now-generally-available/)
    - [Cosmos DB Mirroring in Fabric - GA](https://devblogs.microsoft.com/cosmosdb/cosmos-db-fabric-mirroring-ga/)
    - [Dynamic Data Masking in Cosmos DB](https://learn.microsoft.com/en-us/azure/cosmos-db/nosql/dynamic-data-masking)

- **SQL Server & Azure SQL:**
    - [SQL Server 2025 - Generally Available](https://techcommunity.microsoft.com/blog/SQLServer/sql-server-2025-is-now-generally-available/4470570)
    - [NextGen SQL Managed Instance General Purpose - GA](https://techcommunity.microsoft.com/blog/AzureSQLBlog/generally-available-azure-sql-managed-instance-next-gen-general-purpose/4470970)
    - [Backup Immutability for Long-term Retention in Azure SQL](https://learn.microsoft.com/en-us/azure/azure-sql/database/backup-immutability?view=azuresql)

- **Microsoft Fabric:**
    - [Fabric Databases - Unified SaaS Native Experience - GA](https://blog.fabric.microsoft.com/en-us/blog/fabric-databases-a-unified-saas-native-experience-for-modern-data-workloads-generally-available)

- **Analytics & AI Integration:**
    - [Azure Databricks Genie Integration with Copilot Studio and Microsoft Foundry](https://techcommunity.microsoft.com/blog/analyticsonazure/azure-databricks-genie-integration-with-copilot-studio-and-microsoft-foundry-is-/4471087)

### Notable Updates

- **Healthcare & Life Sciences:**
    - [Azure Health Data Services De-identification - Protect Patient Privacy](https://techcommunity.microsoft.com/blog/healthcareandlifesciencesblog/protect-patient-privacy-across-languages-with-the-de-identification-services-pre/4471104)

- **Migration Tools:**
    - Oracle to PostgreSQL Migration in VS Code (link pending)

---

## 🤖 Azure AI

> *Artificial Intelligence, Machine Learning, and Cognitive Services*

### Key Announcements

- **Microsoft Foundry Platform:**
    - [Accelerating Enterprise AI with Microsoft Foundry - Ignite Day 1 Recap](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/accelerating-enterprise-ai-with-microsoft-foundry/4471122)
    - [Foundry Control Plane - Build, Operate, and Govern Every Agent](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/foundry-control-plane-where-developers-build-operate-and-govern-every-agent/4467885)
    - [Foundry IQ - Boost Response Relevance by 36% with Agentic Retrieval](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/foundry-iq-boost-response-relevance-by-36-with-agentic-retrieval/4470720)  
      *AI-powered retrieval system for enhanced response accuracy*

- **AI Agent Services:**
    - [Foundry Agent Service - Simple to Build, Powerful to Deploy, Trusted](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/foundry-agent-service-at-ignite-2025-simple-to-build-powerful-to-deploy-trusted-/4469788)
    - [Agent Loop in Logic Apps - General Availability](https://techcommunity.microsoft.com/blog/integrationsonazureblog/%F0%9F%8E%89announcing-general-availability-of-agent-loop-in-azure-logic-apps/4470739)
    - [Secure AI Agent Knowledge Retrieval - Security Filters in Agent Loop](https://techcommunity.microsoft.com/blog/integrationsonazureblog/%F0%9F%94%90secure-ai-agent-knowledge-retrieval---introducing-security-filters-in-agent-lo/4467561)
    - [Bulletproof Agents with Durable Task Extension](https://techcommunity.microsoft.com/blog/appsonazureblog/bulletproof-agents-with-the-durable-task-extension-for-microsoft-agent-framework/4467122)

- **AI Development Tools:**
    - [AI Templates in Foundry - Azure Updates](https://azure.microsoft.com/en-us/updates/?id=522554) | [Documentation](https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/ai-template-get-started?view=foundry-classic)
    - [Synthetic Data Generation in Foundry](https://learn.microsoft.com/en-us/azure/ai-foundry/fine-tuning/data-generation?view=foundry)

- **Model Fine-Tuning & Training:**
    - [Fine Tuning Developer Tier with Spot Instances](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/fine-tuning-overview?view=foundry-classic)

### Notable Updates

- **Industry-Specific AI:**
    - [Fine-Tuned Healthcare AI Models - Custom Segmentation for Healthcare Data](https://techcommunity.microsoft.com/blog/healthcareandlifesciencesblog/fine-tuning-healthcare-ai-models-custom-segmentation-for-your-healthcare-data/4471044)

---

## 🔒 Security & Governance

> *Security, compliance, identity, and access management across Azure services*

### Key Announcements

- **Microsoft Defender for Cloud:**
    - [Defender for Cloud Integration with GitHub Advanced Security](https://techcommunity.microsoft.com/blog/MicrosoftDefenderCloudBlog/microsoft-defender-for-cloud-innovations-at-ignite-2025/4469386)
    - [Microsoft Defender for Cloud Innovations at Ignite 2025](https://techcommunity.microsoft.com/blog/MicrosoftDefenderCloudBlog/microsoft-defender-for-cloud-innovations-at-ignite-2025/4469386)

- **AI Security & Governance:**
    - [Agent 365 - Security Dashboard for AI](https://techcommunity.microsoft.com/blog/microsoft-security-blog/security-as-the-core-primitive-in-the-agentic-era-new-innovations-to-secure-ai-a/4470197)  
      *Comprehensive security monitoring and governance for AI agents*
    - [Security as the Core Primitive in the Agentic Era](https://techcommunity.microsoft.com/blog/microsoft-security-blog/security-as-the-core-primitive-in-the-agentic-era-new-innovations-to-secure-ai-a/4470197)  
      *Security framework for AI-powered applications and autonomous systems*

### Notable Updates

- **Backup & Data Protection:**
    - [Threat Protection in Azure Backup](https://azure.microsoft.com/en-us/updates/?id=520454)

---

## 📅 Event Information

**Microsoft Ignite 2025**  
📅 *November 18-22, 2025*  
📍 *Chicago, IL & Virtual*  
🌐 *Format: Hybrid Experience*

### Summary
Microsoft Ignite 2025 showcased innovations across Azure infrastructure, data platforms, AI services, and security. Key themes included agentic AI with Microsoft Foundry, next-generation compute capabilities, and comprehensive data platform evolution.

---

## 📝 Contributing

This list is maintained by Matt Hansen. Feel free to suggest additions or corrections!

---

## 🔗 Resources

- [Official Ignite 2025 Book of News](https://news.microsoft.com/ignite-2025/)
- [Azure Updates](https://azure.microsoft.com/updates/)
- [Microsoft Tech Community](https://techcommunity.microsoft.com/)

---

*Last updated: November 19, 2025*
