# 🚀 Matt's List of Ignite 2025 Azure Announcements

> *The Ignite Book of News is great, but it doesn't include all the great work across the rest of the Azure products.*

This is a personal collection of announcements and updates from **Microsoft Ignite 2025**, specific to Azure, organized by service category for navigation and reference.

**Last Updated:** November 20, 2025 at 3:29PM EST

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
    - [Netapp Files Capacity & Performance Enhancements - Ignite 2025](https://techcommunity.microsoft.com/blog/azurearchitectureblog/accelerating-hpc-and-eda-with-powerful-azure-netapp-files-enhancements/4469739)  
      *Azure NetApp Files massive capacity cool storage tier and ultra-high performance configuration*
    - [Lustre vNext - 25PB and 512 GBps](https://techcommunity.microsoft.com/blog/azurehighperformancecomputingblog/announcing-the-public-preview-of-amlfs-20-azure-managed-lustre-new-sku-for-massi/4470665)  
      *Azure Managed Lustre 2.0 for massive scale HPC workloads*
    - [Azure Blob Smart Tiering](https://techcommunity.microsoft.com/blog/azurestorageblog/unlocking-storage-optimizations-smart-tiering-for-blobs-and-adls-in-azure-storag/4469811)  
      *Automated lifecycle management for blob storage optimization*
    - [Azure Files Entra-Only Secure Access](https://techcommunity.microsoft.com/blog/azurestorageblog/cloud-native-identity-with-azure-files-entra-only-secure-access-for-the-modern-e/4469778)  
      *Cloud-native identity with Entra-only authentication for modern enterprise file shares*

- **Operations:**
    - [Azure Infra, Data & Cyber Resiliency](https://techcommunity.microsoft.com/blog/azurearchitectureblog/azure-resiliency-proactive-continuity-with-agentic-experiences-and-frontier-inno/4469693)  
      *Proactive continuity with agentic experiences multi-update blog*
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
        - [Resiliency Agent](https://learn.microsoft.com/en-us/azure/copilot/resiliency-agent)  
          *AI agent for proactive resilience monitoring and recommendations*
        - [Troubleshooting Agent](https://learn.microsoft.com/en-us/azure/copilot/troubleshooting-agent)  
          *AI-powered diagnostic and problem resolution assistance*
    - [Azure Monitor Coverage Insights](https://techcommunity.microsoft.com/blog/azureobservabilityblog/introducing-monitoring-coverage-assess-and-improve-your-monitoring-posture-at-sc/4470752)  
      *Assess and improve monitoring posture at scale across Azure resources*
    - [Azure Copilot Observability Agent](https://techcommunity.microsoft.com/blog/azureobservabilityblog/azure-copilot-observability-agent-intelligent-investigations-across-your-azure-s/4469719)  
      *AI-powered intelligent investigations and troubleshooting across Azure services*
    - [Azure Monitor Private Link Scope (AMPLS) Scale Limits - General Availability](https://techcommunity.microsoft.com/blog/azureobservabilityblog/generally-available---azure-monitor-private-link-scope-ampls-scale-limits-increa/4471482)  
      *Increased scale limits for private connectivity to Azure Monitor services*
    - [Simplified Application Monitoring for AKS with Azure Monitor - Public Preview](https://techcommunity.microsoft.com/blog/azureobservabilityblog/simplify-application-monitoring-for-aks-with-azure-monitor-public-preview/4470136)  
      *Streamlined application observability and monitoring for Azure Kubernetes Service*
    - [Granular RBAC in Azure Monitor Logs - General Availability](https://techcommunity.microsoft.com/blog/azureobservabilityblog/general-availability-granular-rbac-in-azure-monitor-logs/4471299)  
      *Fine-grained role-based access control for Azure Monitor log data and queries*
    - [Azure Migrate Business Case Generator](https://techcommunity.microsoft.com/blog/azuremigrationblog/migrate-or-modernize-your-applications-using-azure-migrate/4468587)  
      *Automated business case generation for application migration and modernization decisions*
    - [Admin Center Virtualization Mode](https://techcommunity.microsoft.com/blog/windowsservernewsandbestpractices/introducing-windows-admin-center-virtualization-mode-vmode/4471024)  
      *Enhanced Windows Admin Center capabilities for virtualized environments*
    - [Kubernetes Center](https://techcommunity.microsoft.com/blog/azureinfrastructureblog/announcing-kubernetes-center-preview-on-azure-portal/4471110)  
      *Centralized Kubernetes management experience in the Azure Portal*

- **Compute:**
    - **New VM SKUs:**
        - [DLsv7, DSv7, and ESv7 VMs based on Intel® Xeon® 6](https://techcommunity.microsoft.com/blog/azurecompute/announcing-preview-of-new-azure-dlsv7-dsv7-and-esv7-vms-based-on-intel%C2%AE-xeon%C2%AE-6-/4467928)  
          *Latest generation VMs with Intel Xeon 6 processors for enhanced performance*
        - [EBSv6 VMs based on 5th Gen Intel® Xeon®](https://techcommunity.microsoft.com/blog/azurecompute/announcing-the-preview-of-the-new-azure-ebsv6-vms-based-on-the-5th-gen-intel%C2%AE-xe/4470139)  
          *Memory-optimized VMs with 5th generation Intel Xeon processors*
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
    - [What's new in Azure Local](https://techcommunity.microsoft.com/blog/azurearcblog/what%E2%80%99s-new-in-azure-local-cloud-infrastructure-for-distributed-locations-enabled/4469773)  
      *New Hardware, GPU Support, VMWare Migration, Rack-Aware Clustering, and SAN support.*
    - [Arc Multi-Cloud Updates](https://techcommunity.microsoft.com/blog/azurearcblog/expanding-azure-arc-for-hybrid-and-multicloud-management/4470656)  
      *Enhanced hybrid and multi-cloud resource management capabilities, adding GCP.*
    - [What's new in AKS Enabled by Azure Arc - Ignite 2025](https://techcommunity.microsoft.com/blog/azurearcblog/aks-enabled-by-azure-arc-powering-ai-applications-from-cloud-to-edge-ignite-2025/4471511)  
      *Kubernetes platform for AI workloads across cloud, edge, and hybrid environments*
    - [Foundry Local on Windows Server](https://techcommunity.microsoft.com/blog/windowsservernewsandbestpractices/microsoft-foundry-on-windows-server/4471093)  
      *AI platform capabilities deployed locally on Windows Server infrastructure*
    - [AKS Fleet Manager with Arc-enabled Kubernetes Clusters](https://learn.microsoft.com/en-us/azure/kubernetes-fleet/concepts-fleet-arc-integration)  
      *Centralized management for Kubernetes clusters across hybrid environments*
    - [Arc-Enabled Azure Migrate](https://techcommunity.microsoft.com/blog/azurearcblog/accelerate-your-cloud-migration-journey-with-azure-arc-resource-discovery-in-azu/4469975)  
      *Resource discovery and assessment for hybrid cloud migrations*
    - [AVD Hybrid Deployment Options](https://techcommunity.microsoft.com/blog/azurevirtualdesktopblog/announcing-new-hybrid-deployment-options-for-azure-virtual-desktop/4468781)  
      *New deployment models for Azure Virtual Desktop in hybrid environments*
    - [SQL Server Migration in Azure Arc - GA](https://techcommunity.microsoft.com/blog/microsoftdatamigration/sql-server-migration-in-azure-arc-%E2%80%93-generally-available/4471020)  
      *Generally available database migration service for hybrid SQL deployments*
    - [Arc Edge Video Indexer](https://techcommunity.microsoft.com/blog/azurearcblog/ignite-2025-preview---intelligent-real-time-video-insights-and-agents-with-azure/4470704)  
      *AI-powered video analytics for edge computing scenarios*

- **Networking:**
    - [NAT Gateway v2 - StandardV2 NAT Gateway and StandardV2 Public IP](https://techcommunity.microsoft.com/blog/azurenetworkingblog/announcing-the-public-preview-of-standardv2-nat-gateway-and-standardv2-public-ip/4458292)  
      *Next-generation network address translation with enhanced performance*
    - [ExpressRoute Scalable Gateway](https://learn.microsoft.com/en-us/azure/expressroute/scalable-gateway)  
      *Scalable ExR gatways without having to swap to a new instance or have downtime*
    - [Azure DNS Security Policy with Threat Intelligence Feed - General Availability](https://techcommunity.microsoft.com/blog/azurenetworkingblog/announcing-azure-dns-security-policy-with-threat-intelligence-feed-general-avail/4470183)  
      *DNS-based threat protection using Microsoft threat intelligence for enhanced security*

- **Misc:**
    - **IoT Announcements:**
        - [Bridging the Digital and Physical Worlds with Azure IoT Hub and Azure IoT Operations](https://techcommunity.microsoft.com/blog/iotblog/bridging-the-digital-and-physical-worlds-with-azure-iot-hub-and-azure-iot-operat/4469774)  
          *Comprehensive IoT platform for connecting and managing digital-physical integration*
        - [Azure IoT Hub with ADR Preview - Extending Azure Capabilities and Certificate Management](https://techcommunity.microsoft.com/blog/iotblog/azure-iot-hub-with-adr-preview-extending-azure-capabilities-and-certificate-mana/4465265)  
          *Azure Device Registry, Certificate Management, and Identity for IoT*


## 🔧 Azure Apps

> *Application development, deployment, and management services*

### Key Announcements

- **Azure App Service:**
    - [App Service Managed Instance - Public Preview](https://techcommunity.microsoft.com/blog/appsonazureblog/announcing-public-preview-of-managed-instance-on-azure-app-service/4469930)  
      *Dedicated App Service environment with enhanced isolation and control*
    - [Client Side App Configurations in Front Door](https://techcommunity.microsoft.com/blog/appsonazureblog/unlocking-client-side-configuration-at-scale-with-azure-app-configuration-and-az/4470781)  
      *Scalable client-side configuration management through Azure Front Door*

- **Azure Kubernetes Service (AKS):**
    - [Agentic CLI for AKS - Updates](https://azure.microsoft.com/en-us/updates/?id=523062) | [Documentation](https://learn.microsoft.com/en-us/azure/aks/cli-agent-for-aks-overview)  
      *AI-powered command line interface for Kubernetes cluster management*
    - [Pod Sandboxing in AKS](https://learn.microsoft.com/en-us/azure/aks/use-pod-sandboxing)  
      *Enhanced container isolation using hardware-based security boundaries*
    - [Managed System Node Pools in AKS Automatic](https://learn.microsoft.com/en-us/azure/aks/automatic/aks-automatic-managed-system-node-pools-about)  
      *Automated system workload management in AKS clusters*

- **Azure Container Apps:**
    - [What's New in Azure Container Apps at Ignite25](https://techcommunity.microsoft.com/blog/appsonazureblog/whats-new-in-azure-container-apps-at-ignite25/4470391)  
      *Latest updates and enhancements to the serverless container platform*

- **Azure Functions:**
    - [Azure Functions Ignite 2025 Update](https://techcommunity.microsoft.com/blog/appsonazureblog/azure-functions-ignite-2025-update/4469815)  
      *Latest serverless computing enhancements and new capabilities*
    - [Azure Functions Durable Task Scheduler - Dedicated SKU GA & Consumption Preview](https://techcommunity.microsoft.com/blog/appsonazureblog/announcing-azure-functions-durable-task-scheduler-dedicated-sku-ga--consumption-/4465328)  
      *Advanced task scheduling capabilities with dedicated and consumption-based options*

- **Logic Apps & Integration:**
    - [RabbitMQ Connector - General Availability](https://techcommunity.microsoft.com/blog/integrationsonazureblog/announcing-the-general-availability-of-the-rabbitmq-connector/4470639)  
      *Native integration with RabbitMQ message broker for workflow automation*
    - [Logic Apps Connectors Updates](https://azure.microsoft.com/en-us/updates/?id=527683) | [Additional Updates](https://azure.microsoft.com/en-us/updates/?id=531783)  
      *Enhanced connectivity options and improved connector capabilities*
    - [Healthcare Connectors in Logic Apps](https://azure.microsoft.com/en-us/updates/?id=531778)  
      *Specialized connectors for healthcare data integration and compliance*

- **Event-Driven Architecture:**
    - [Large Message Support in Event Hubs - General Availability](https://techcommunity.microsoft.com/blog/messagingonazureblog/general-availability-large-message-support-in-azure-event-hubs/4471094)  
      *Support for messages up to 20MB in Azure Event Hubs streaming platform*

- **Cache & In-Memory Services:**
    - [Azure Managed Redis - Ignite 2025 Feature Announcements](https://techcommunity.microsoft.com/blog/azure-managed-redis/whats-new-in-azure-managed-redis-ignite-2025-feature-announcements/4470201)  
      *Latest Redis caching service enhancements and new capabilities*

- **API Management:**
    - [Azure API Management - Govern, Secure, and Observe A2A APIs](https://techcommunity.microsoft.com/blog/integrationsonazureblog/preview-govern-secure-and-observe-a2a-apis-with-azure-api-management/4469800)  
      *Enhanced API governance, security, and observability for application-to-application APIs*
    - [Azure API Management Premium v2 Tier - General Availability](https://techcommunity.microsoft.com/blog/integrationsonazureblog/announcing-the-general-availability-ga-of-the-premium-v2-tier-of-azure-api-manag/4471499)  
      *Next-generation premium tier with enhanced performance and capabilities*

### Notable Updates

- **Development Platforms:**
    - [.NET 10 - General Availability](https://devblogs.microsoft.com/dotnet/announcing-dotnet-10/)  
      *Latest version of Microsoft's unified development platform*

- **AI-Powered Development:**
    - [App Modernization with GitHub Copilot - AI Agents Rewriting the Playbook](https://techcommunity.microsoft.com/blog/appsonazureblog/ai-agents-are-rewriting-the-app-modernization-playbook/4470162)  
      *AI-assisted application modernization strategies and automation*

---

## 📊 Azure Data

> *Data storage, analytics, databases, and data management services*

### Key Announcements

- **Data Platform Overview:**
    - [The New Frontier of Data for the Next Generation of Innovation](https://techcommunity.microsoft.com/blog/azuredatablog/the-new-frontier-of-data-for-the-next-generation-of-innovation/4463236)  
      *Strategic vision for next-generation data platforms and AI integration*

- **PostgreSQL Services:**
    - [Azure HorizonDB - Announcement](https://techcommunity.microsoft.com/blog/adforpostgresql/announcing-azure-horizondb/4469710)  
      *Next-generation PostgreSQL-compatible database service*
    - [Build Smarter with Azure HorizonDB](https://techcommunity.microsoft.com/blog/adforpostgresql/build-smarter-with-azure-horizondb/4470302)  
      *Development capabilities and AI integration with HorizonDB*
    - [PostgreSQL for the Enterprise - Scale, Secure, Simplify](https://techcommunity.microsoft.com/blog/adforpostgresql/postgresql-for-the-enterprise-scale-secure-simplify/4470412)  
      *Enterprise-grade PostgreSQL capabilities with enhanced security and scale*
    - [PostgreSQL Mirroring in Fabric](https://learn.microsoft.com/en-us/fabric/mirroring/azure-database-postgresql)  
      *Real-time data replication from PostgreSQL to Microsoft Fabric*

- **MySQL Services:**
    - [Ignite 2025: Advancing Azure Database for MySQL](https://techcommunity.microsoft.com/blog/adformysql/ignite-2025-advancing-azure-database-for-mysql-with-powerful-new-capabilities/4470824)  
      *Enhanced MySQL database service with new performance and feature improvements*

- **Cosmos DB & Document Services:**
    - [Azure Document DB - Generally Available](https://devblogs.microsoft.com/cosmosdb/azure-documentdb-is-now-generally-available/)  
      *Globally distributed document database service for modern applications*
    - [Cosmos DB Mirroring in Fabric - GA](https://devblogs.microsoft.com/cosmosdb/cosmos-db-fabric-mirroring-ga/)  
      *Near real-time data replication from Cosmos DB to Microsoft Fabric*
    - [Dynamic Data Masking in Cosmos DB](https://learn.microsoft.com/en-us/azure/cosmos-db/nosql/dynamic-data-masking)  
      *Runtime data obfuscation for sensitive information protection*

- **SQL Server & Azure SQL:**
    - [SQL Server 2025 - Generally Available](https://techcommunity.microsoft.com/blog/SQLServer/sql-server-2025-is-now-generally-available/4470570)  
      *Latest version of Microsoft's flagship database platform*
    - [NextGen SQL Managed Instance General Purpose - GA](https://techcommunity.microsoft.com/blog/AzureSQLBlog/generally-available-azure-sql-managed-instance-next-gen-general-purpose/4470970)  
      *Enhanced managed instance with improved performance and cost optimization*
    - [Backup Immutability for Long-term Retention in Azure SQL](https://techcommunity.microsoft.com/blog/azuresqlblog/azure-sql-database-ltr-backup-immutability-is-now-generally-available/4471457)  
      *Tamper-proof backup protection for compliance and security*
    - [Stream Data from SQL to Azure Event Hubs - Public Preview](https://techcommunity.microsoft.com/blog/azuresqlblog/stream-data-in-near-real-time-from-sql-to-azure-event-hubs---public-preview/4470724)  
      *Near real-time data streaming from SQL databases to Event Hubs for analytics and processing*

- **Microsoft Fabric:
    - [Fabric November 2025 Feature Summary](https://blog.fabric.microsoft.com/en-us/blog/fabric-november-2025-feature-summary/)  
      *Comprehensive overview of new Fabric capabilities and features announced in November 2025*
    - [Fabric Data Agents at Ignite 2025](https://blog.fabric.microsoft.com/en/blog/whats-new-for-fabric-data-agents-at-ignite-2025-unlocking-deeper-data-reasoning-and-seamless-ai-interoperability)  
      *AI-powered data agents for deeper data reasoning and seamless AI interoperability*
    - [Fabric Databases - Unified SaaS Native Experience - GA](https://blog.fabric.microsoft.com/en-us/blog/fabric-databases-a-unified-saas-native-experience-for-modern-data-workloads-generally-available)  
      *Integrated database experience within Microsoft Fabric analytics platform*
    - [SAP Connector in Microsoft Fabric](https://blog.fabric.microsoft.com/en-us/blog/29410)  
      *Native SAP data integration and analytics capabilities within Fabric*

- **Analytics & AI Integration:**
    - [Azure Databricks Genie Integration with Copilot Studio and Microsoft Foundry](https://techcommunity.microsoft.com/blog/analyticsonazure/azure-databricks-genie-integration-with-copilot-studio-and-microsoft-foundry-is-/4471087)  
      *AI-powered data analytics integration across Microsoft's AI platform stack*

### Notable Updates

- **Healthcare & Life Sciences:**
    - [Azure Health Data Services De-identification - Protect Patient Privacy](https://techcommunity.microsoft.com/blog/healthcareandlifesciencesblog/protect-patient-privacy-across-languages-with-the-de-identification-services-pre/4471104)  
      *Multi-language patient data anonymization for healthcare compliance*

- **Migration Tools:**
    - Oracle to PostgreSQL Migration in VS Code (link pending)  
      *Development tools for database migration workflows*

---

## 🤖 Azure AI

> *Artificial Intelligence, Machine Learning, and Cognitive Services*

### Key Announcements

- **Microsoft Foundry Platform:**
    - [Accelerating Enterprise AI with Microsoft Foundry - Ignite Day 1 Recap](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/accelerating-enterprise-ai-with-microsoft-foundry/4471122)  
      *Comprehensive overview of Microsoft's enterprise AI platform strategy*
    - [Foundry Control Plane - Build, Operate, and Govern Every Agent](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/foundry-control-plane-where-developers-build-operate-and-govern-every-agent/4467885)  
      *Centralized management and governance platform for AI agents and applications*
    - [Foundry IQ - Boost Response Relevance by 36% with Agentic Retrieval](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/foundry-iq-boost-response-relevance-by-36-with-agentic-retrieval/4470720)  
      *AI-powered retrieval system for enhanced response accuracy*

- **AI Agent Services:**
    - [Foundry Agent Service - Simple to Build, Powerful to Deploy, Trusted](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/foundry-agent-service-at-ignite-2025-simple-to-build-powerful-to-deploy-trusted-/4469788)  
      *Streamlined AI agent development and deployment platform*
    - [Agent Loop in Logic Apps - General Availability](https://techcommunity.microsoft.com/blog/integrationsonazureblog/%F0%9F%8E%89announcing-general-availability-of-agent-loop-in-azure-logic-apps/4470739)  
      *AI agent integration within workflow automation platform*
    - [Secure AI Agent Knowledge Retrieval - Security Filters in Agent Loop](https://techcommunity.microsoft.com/blog/integrationsonazureblog/%F0%9F%94%90secure-ai-agent-knowledge-retrieval---introducing-security-filters-in-agent-lo/4467561)  
      *Enhanced security controls for AI agent data access and retrieval*
    - [Durable AI Agent Task Extension](https://techcommunity.microsoft.com/blog/appsonazureblog/bulletproof-agents-with-the-durable-task-extension-for-microsoft-agent-framework/4467122)  
      *Resilient AI agent framework with fault tolerance and recovery capabilities*

- **AI Development Tools:**
    - [AI Templates in Foundry - Azure Updates](https://azure.microsoft.com/en-us/updates/?id=522554) | [Documentation](https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/ai-template-get-started?view=foundry-classic)  
      *Pre-built AI application templates for accelerated development*
    - [Synthetic Data Generation in Foundry](https://learn.microsoft.com/en-us/azure/ai-foundry/fine-tuning/data-generation?view=foundry)  
      *AI-powered synthetic dataset creation for model training and testing*
    - [Azure AI Search with Sensitivity Labels and SharePoint ACLs](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/sensitivity-labels-preservation-and-sharepoint-acls-in-azure-ai-search/4471216)  
      *Enhanced data governance with Purview sensitivity labels and SharePoint access controls*
    - [Advancements in Azure Speech in Microsoft Foundry](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/advancing-speech-innovation-with-azure-speech-in-microsoft-foundry/4471461)  
      *Advanced speech capabilities and innovation within the Foundry AI platform*

- **Model Fine-Tuning & Training:**
    - [Fine Tuning Developer Tier with Spot Instances](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/fine-tuning-overview?view=foundry-classic)  
      *Cost-effective model customization using low-priority compute resources*

### Notable Updates

- **Healthcare AI Models:**
    - [Fine-Tuned Healthcare AI Models - Custom Segmentation for Healthcare Data](https://techcommunity.microsoft.com/blog/healthcareandlifesciencesblog/fine-tuning-healthcare-ai-models-custom-segmentation-for-your-healthcare-data/4471044)  
      *Specialized AI models for medical data analysis and healthcare workflows*

---

## 🔒 Security & Governance

> *Security, compliance, identity, and access management across Azure services*

### Key Announcements

- **Microsoft Defender for Cloud:**
    - [Defender for Cloud Integration with GitHub Advanced Security](https://techcommunity.microsoft.com/blog/MicrosoftDefenderCloudBlog/microsoft-defender-for-cloud-innovations-at-ignite-2025/4469386)  
      *Enhanced DevSecOps integration with GitHub's security scanning capabilities*
    - [Microsoft Defender for Cloud Innovations at Ignite 2025](https://techcommunity.microsoft.com/blog/MicrosoftDefenderCloudBlog/microsoft-defender-for-cloud-innovations-at-ignite-2025/4469386)  
      *Latest cloud security posture management and threat protection features*

- **AI Security & Governance:**
    - [Agent 365 - Security Dashboard for AI](https://techcommunity.microsoft.com/blog/microsoft-security-blog/security-as-the-core-primitive-in-the-agentic-era-new-innovations-to-secure-ai-a/4470197)  
      *Comprehensive security monitoring and governance for AI agents*
    - [Security as the Core Primitive in the Agentic Era](https://techcommunity.microsoft.com/blog/microsoft-security-blog/security-as-the-core-primitive-in-the-agentic-era-new-innovations-to-secure-ai-a/4470197)  
      *Security framework for AI-powered applications and autonomous systems*

### Notable Updates

- **Backup & Data Protection:**
    - [Threat Protection in Azure Backup](https://azure.microsoft.com/en-us/updates/?id=520454)  
      *Advanced threat detection and protection for backup infrastructure and data*

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

*Last updated: November 20, 2025*
