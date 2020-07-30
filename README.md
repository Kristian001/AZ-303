## Microsoft Docs AZ-303 study guide resources

Here are the Microsoft Docs which I will be using to prepare and study for the AZ-303 exam.

### Implement and Monitor an Azure Infrastructure (50-55%)

Implement cloud infrastructure monitoring

* monitor security
  * [Strengthen your security posture with Azure Security Center](https://docs.microsoft.com/en-us/azure/security-center/security-center-monitoring)
  * [Security Control: Logging and Monitoring](https://docs.microsoft.com/en-us/azure/security/benchmarks/security-control-logging-monitoring)
  * [Azure infrastructure monitoring](https://docs.microsoft.com/en-us/azure/security/fundamentals/infrastructure-monitoring)
* monitor performance
  * [Create diagnostic setting to collect platform logs and metrics in Azure](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/diagnostic-settings)
  * [Create diagnostic setting in Azure using a Resource Manager template](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/diagnostic-settings-template)
  * [Metric Baseline -- Get](https://docs.microsoft.com/en-us/rest/api/monitor/metricbaseline/get)
  * [Azure Monitor overview](https://docs.microsoft.com/en-us/azure/azure-monitor/overview)
  * [Quickstart: Monitor an Azure resource with Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/learn/quick-monitor-azure-resource)
  * [Azure Monitor Workbooks](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/workbooks-overview)
  * [Azure Monitor workbook visualizations](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/workbooks-visualizations)
  * [Collect data from an Azure virtual machine with Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/learn/quick-collect-azurevm)
* monitor health and availability
  * [Azure Service Health](https://azure.microsoft.com/en-us/features/service-health)
  * [Resource Health overview](https://docs.microsoft.com/en-us/azure/service-health/resource-health-overview)
* monitor cost
  * [Monitoring your cloud costs](https://docs.microsoft.com/en-us/azure/architecture/framework/cost/monitoring)
  * [Use cost alerts to monitor usage and spending](https://docs.microsoft.com/en-us/azure/cost-management-billing/costs/cost-mgt-alerts-monitor-usage-spending)
  * [Download or view your Azure billing invoice and daily usage data](https://docs.microsoft.com/en-us/azure/cost-management-billing/manage/download-azure-invoice-daily-usage-date)
* configure advanced logging
  * [What is Application Insights?](https://docs.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview)
  * [Overview of Insights in Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/insights/insights-overview)
* configure logging for workloads
  * [Logs in Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/data-platform-logs)
* initiate automated responses by using Action Groups
  * [Create and manage action groups in the Azure portal](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/action-groups)
* configure and manage advanced alerts
  * [Create, view, and manage log alerts using Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/alerts-log)
  * [Manage alert instances with unified alerts](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/alerts-managing-alert-instances)
  * [Create diagnostic setting to collect platform logs and metrics in Azure](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/diagnostic-settings)
  * [Overview of alerts in Microsoft Azure](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/alerts-overview)
  * [Create a Log Analytics workspace in the Azure portal](https://docs.microsoft.com/en-us/azure/azure-monitor/learn/quick-create-workspace)

Implement storage accounts

* select storage account options based on a use case
  * [Storage account overview](https://docs.microsoft.com/en-us/azure/storage/common/storage-account-overview)
  * [Introduction to Azure Storage](https://docs.microsoft.com/en-us/azure/storage/common/storage-introduction)
* configure Azure Files and blob storage
  * [Introduction to Azure Blob storage](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blobs-introduction)
  * [Create an Azure file share](https://docs.microsoft.com/en-us/azure/storage/files/storage-how-to-create-file-share)
* configure network access to the storage account
  * [Configure Azure Storage firewalls and virtual networks](https://docs.microsoft.com/en-us/azure/storage/common/storage-network-security)
* implement Shared Access Signatures and access policies
  * [Delegate access with a shared access signature](https://docs.microsoft.com/en-us/rest/api/storageservices/delegate-access-with-shared-access-signature)
  * [Grant limited access to Azure Storage resources using shared access signatures (SAS)](https://docs.microsoft.com/en-us/azure/storage/common/storage-sas-overview)
* implement Azure AD authentication for storage
  * [Authorize access to blobs and queues using Azure Active Directory](https://docs.microsoft.com/en-us/azure/storage/common/storage-auth-aad)
* manage access keys
  * [Manage storage account access keys](https://docs.microsoft.com/en-us/azure/storage/common/storage-account-keys-manage)
* implement Azure storage replication
  * [Azure Storage redundancy](https://docs.microsoft.com/en-us/azure/storage/common/storage-redundancy)
  * [Disaster recovery and account failover (preview)](https://docs.microsoft.com/en-us/azure/storage/common/storage-disaster-recovery-guidance)
* implement Azure storage account failover
  * [Initiate a storage account failover (preview)](https://docs.microsoft.com/en-us/azure/storage/common/storage-initiate-account-failover)

Implement VMs for Windows and Linux

* configure High Availability
  * [Availability options for virtual machines in Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/availability)
  * [Manage the availability of Windows virtual machines in Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/manage-availability)
* configure storage for VMs
  * [Attach a managed data disk to a Windows VM by using the Azure portal](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/attach-managed-disk-portal)
  * [Attach a data disk to a Windows VM with PowerShell](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/attach-disk-ps)
  * [What disk types are available in Azure?](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/disks-types)
* select virtual machine size
  * [Sizes for Windows virtual machines in Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sizes)
  * [Sizes for Linux virtual machines in Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/sizes)
* implement Azure Dedicated Hosts
  * [Deploy VMs to dedicated hosts using the portal](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/dedicated-hosts-portal)
  * [Azure Dedicated Hosts](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/dedicated-hosts)
* deploy and configure scale sets
  * [What are virtual machine scale sets?](https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/overview)
* configure Azure Disk Encryption
  * [Azure Disk Encryption for Linux VMs](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/disk-encryption-overview)
  * [Azure Disk Encryption for Windows VMs](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/disk-encryption-overview)

Automate deployment and configuration of resources

* save a deployment as an Azure Resource Manager template
  * [Download the template for a VM](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/download-template)
* modify Azure Resource Manager template
  * [Extend Azure Resource Manager template functionality](https://docs.microsoft.com/en-us/azure/architecture/building-blocks/extending-templates)
  * [Azure Resource Manager templates overview](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/overview)
  * [Tutorial: Create and deploy your first Azure Resource Manager template](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-tutorial-create-first-template)
* evaluate location of new resources
  * [Conditional deployment in Resource Manager templates](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/conditional-resource-deployment)
  * [Set resource location in Resource Manager template](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/resource-location)
* configure a virtual disk template
  * [Create a VM from a VHD by using the Azure portal](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/create-vm-specialized-portal)
* deploy from a template
  * [Download the template for a VM](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/download-template)
* manage a template library
  * [Azure Resource Manager templates overview](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/overview)
* create and execute an automation runbook
  * [Start a runbook in Azure Automation](https://docs.microsoft.com/en-us/azure/automation/start-runbooks)

Implement virtual networking

* implement VNet to VNet connections
  * [Configure a VNet-to-VNet VPN gateway connection by using the Azure portal](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-howto-vnet-vnet-resource-manager-portal)
* implement VNet peering
  * [Virtual network peering](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-peering-overview)
  * [Create, change, or delete a virtual network peering](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-manage-peering)

Implement Azure Active Directory

* add custom domains
  * [Add your custom domain name using the Azure Active Directory portal](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/add-custom-domain)
* configure Azure AD Identity Protection
  * [What is Azure Active Directory Identity Protection?](https://docs.microsoft.com/en-us/azure/active-directory/identity-protection/overview-identity-protection)
* implement self-service password reset
  * [Plan an Azure Active Directory self-service password reset](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-sspr-deployment)
  * [How it works: Azure AD self-service password reset](https://docs.microsoft.com/en-us/azure/active-directory/authentication/concept-sspr-howitworks)
  * [Licensing requirements for Azure AD self-service password reset](https://docs.microsoft.com/en-us/azure/active-directory/authentication/concept-sspr-licensing)
* implement Conditional Access including MFA
  * [Conditional Access: Require MFA for all users](https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/howto-conditional-access-policy-all-users-mfa)
  * [Conditional Access: Risk-based Conditional Access](https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/howto-conditional-access-policy-risk)
* configure user accounts for MFA
  * [Tutorial: Secure user sign-in events with Azure Multi-Factor Authentication](https://docs.microsoft.com/en-us/azure/active-directory/authentication/tutorial-enable-azure-mfa)
* configure fraud alerts
  * [Reports in Azure Multi-Factor Authentication](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-mfa-reporting)
  * [Configure Azure Multi-Factor Authentication settings](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-mfa-mfasettings)
* configure bypass options
  * [Configure Azure Multi-Factor Authentication settings](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-mfa-mfasettings)
* configure Trusted IPs
  * [Quickstart: Configure named locations in Azure Active Directory](https://docs.microsoft.com/en-us/azure/active-directory/reports-monitoring/quickstart-configure-named-locations)
  * [What is the location condition in Azure Active Directory Conditional Access?](https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/location-condition)
* configure verification methods
  * [Change your two-factor verification method and settings](https://docs.microsoft.com/en-us/azure/active-directory/user-help/multi-factor-authentication-end-user-manage-settings)
  * [What is the Additional verification page?](https://docs.microsoft.com/en-us/azure/active-directory/user-help/multi-factor-authentication-end-user-first-time)
* implement and manage guest accounts
  * [What is guest user access in Azure Active Directory B2B?](https://docs.microsoft.com/en-us/azure/active-directory/b2b/what-is-b2b)
  * [Manage guest access with Azure AD access reviews](https://docs.microsoft.com/en-us/azure/active-directory/governance/manage-guest-access-with-access-reviews)
  * [Quickstart: Add guest users to your directory in the Azure portal](https://docs.microsoft.com/en-us/azure/active-directory/b2b/b2b-quickstart-add-guest-users-portal)
* manage multiple directories
  * [Understand how multiple Azure Active Directory tenants interact](https://docs.microsoft.com/en-us/azure/active-directory/users-groups-roles/licensing-directory-independence)

Implement and manage hybrid identities

* install and configure Azure AD Connect
  * [Custom installation of Azure AD Connect](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-install-custom)
  * [Select which installation type to use for Azure AD Connect](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-install-select-installation)
* identity synchronization options
  * [Azure AD Connect sync: Understand and customize synchronization](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-sync-whatis)
  * [Azure Active Directory Hybrid Identity Design Considerations](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/plan-hybrid-identity-design-considerations-overview)
* configure and manage password sync and password writeback
  * [Implement password hash synchronization with Azure AD Connect sync](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-password-hash-synchronization)
  * [Tutorial: Enable Azure Active Directory self-service password reset writeback to an on-premises environment](https://docs.microsoft.com/en-us/azure/active-directory/authentication/tutorial-enable-sspr-writeback)
  * [Azure AD Connect: Enabling device writeback](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-device-writeback)
  * [What is password writeback?](https://docs.microsoft.com/en-us/azure/active-directory/authentication/concept-sspr-writeback)
* configure single sign-on
  * [Azure Active Directory Seamless Single Sign-On: Quick start](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-sso-quick-start)
  * [Azure Active Directory Seamless Single Sign-On: Frequently asked questions](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-sso-faq)
* use Azure AD Connect Health
  * [Azure Active Directory Connect Health operations](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-health-operations)
  * [What is Azure AD Connect?](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/whatis-azure-ad-connect)

### Implement Management and Security Solutions (25-30%)

Manage workloads in Azure

* migrate workloads using Azure Migrate
  * [About Azure Migrate](https://docs.microsoft.com/en-us/azure/migrate/migrate-services-overview)
  * [Prepare VMware VMs for assessment and migration to Azure](https://docs.microsoft.com/en-us/azure/migrate/tutorial-prepare-vmware)
  * [Assess VMware VMs by using Azure Migrate Server Assessment](https://docs.microsoft.com/en-us/azure/migrate/tutorial-assess-vmware)
  * [Select a VMware migration option](https://docs.microsoft.com/en-us/azure/migrate/server-migrate-overview)
  * [Migrate VMware VMs to Azure (agentless)](https://docs.microsoft.com/en-us/azure/migrate/tutorial-migrate-vmware)
  * [Migrate VMware VMs to Azure (agent-based)](https://docs.microsoft.com/en-us/azure/migrate/tutorial-migrate-vmware-agent)
* implement Azure Backup for VMs
  * [An overview of Azure VM backup](https://docs.microsoft.com/en-us/azure/backup/backup-azure-vms-introduction)
  * [Get improved backup and restore performance with Azure Backup Instant Restore capability](https://docs.microsoft.com/en-us/azure/backup/backup-instant-restore-capability)
* implement disaster recovery
  * [Set up disaster recovery to a secondary Azure region for an Azure VM](https://docs.microsoft.com/en-us/azure/site-recovery/azure-to-azure-quickstart)
* implement Azure Update Management
  * [Update Management solution in Azure](https://docs.microsoft.com/en-us/azure/automation/automation-update-management)
  * [Enable Update Management, Change Tracking, and Inventory solutions on multiple VMs](https://docs.microsoft.com/en-us/azure/automation/automation-onboard-solutions-from-browse)
  * [Manage updates and patches for your Azure VMs](https://docs.microsoft.com/en-us/azure/automation/automation-tutorial-update-management)

Implement load balancing and network security

* implement Azure Load Balancer
  * [Tutorial: Balance internal traffic load with a Basic load balancer in the Azure portal](https://docs.microsoft.com/en-us/azure/load-balancer/tutorial-load-balancer-basic-internal-portal)
  * [Create an internal load balancer by using the Azure PowerShell module](https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-get-started-ilb-arm-ps)
  * [Quickstart: Create a Load Balancer to load balance VMs using the Azure portal](https://docs.microsoft.com/en-us/azure/load-balancer/quickstart-load-balancer-standard-public-portal)
* implement an application gateway
  * [Application Gateway configuration overview](https://docs.microsoft.com/en-us/azure/application-gateway/configuration-overview)
* implement a Web Application Firewall
  * [Azure Web Application Firewall on Azure Application Gateway](https://docs.microsoft.com/en-us/azure/web-application-firewall/ag/ag-overview)
* implement Azure Firewall
  * [Tutorial: Deploy and configure Azure Firewall using the Azure portal](https://docs.microsoft.com/en-us/azure/firewall/tutorial-firewall-deploy-portal)
* implement the Azure Front Door Service
  * [What is Azure Front Door Service?](https://docs.microsoft.com/en-us/azure/frontdoor/front-door-overview)
  * [Quickstart: Create a Front Door for a highly available global web application](https://docs.microsoft.com/en-us/azure/frontdoor/quickstart-create-front-door)
* implement Azure Traffic Manager
  * [What is Traffic Manager?](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-overview)
  * [Quickstart: Create a Traffic Manager profile using the Azure portal](https://docs.microsoft.com/en-us/azure/traffic-manager/quickstart-create-traffic-manager-profile)
* implement Network Security Groups and Application Security Groups
  * [Security groups](https://docs.microsoft.com/en-us/azure/virtual-network/security-overview)
  * [Create, change, or delete a network security group](https://docs.microsoft.com/en-us/azure/virtual-network/manage-network-security-group)
* implement Bastion
  * [Create an Azure Bastion host](https://docs.microsoft.com/en-us/azure/bastion/bastion-create-host-portal)

Implement and manage Azure governance solutions

* create and manage hierarchical structure that contains management groups, subscriptions and resource groups
  * [Azure Resource Manager overview](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/overview)
  * [Organize your resources with Azure management groups](https://docs.microsoft.com/en-us/azure/governance/management-groups/overview)
  * [Create management groups for resource organization and management](https://docs.microsoft.com/en-us/azure/governance/management-groups/create)
  * [Manage Azure Resource Manager resource groups by using the Azure portal](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resource-groups-portal)
  * [Azure subscription and service limits, quotas, and constraints](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/azure-subscription-service-limits)
* assign RBAC roles
  * [Add or remove role assignments using Azure RBAC and the Azure portal](https://docs.microsoft.com/en-us/azure/role-based-access-control/role-assignments-portal)
* create a custom RBAC role
  * [Custom roles for Azure resources](https://docs.microsoft.com/en-us/azure/role-based-access-control/custom-roles)
  * [Tutorial: Create a custom role for Azure resources using Azure PowerShell](https://docs.microsoft.com/en-us/azure/role-based-access-control/tutorial-custom-role-powershell)
* configure access to Azure resources by assigning roles
  * [Tutorial: Grant a user access to Azure resources using RBAC and the Azure portal](https://docs.microsoft.com/en-us/azure/role-based-access-control/quickstart-assign-role-user-portal)
* configure management access to Azure
  * [Manage access to Azure management with Conditional Access](https://docs.microsoft.com/en-us/azure/role-based-access-control/conditional-access-azure-management)
  * [Manage access to Azure resources with Azure AD Privileged Identity Management](https://docs.microsoft.com/en-us/azure/role-based-access-control/pim-azure-resource)
  * [Add or remove role assignments using Azure RBAC and the Azure portal](https://docs.microsoft.com/en-us/azure/role-based-access-control/role-assignments-portal)
* interpret effective permissions
  * [What is role-based access control (RBAC) for Azure resources?](https://docs.microsoft.com/en-us/azure/role-based-access-control/overview)
  * [Quickstart: View the access a user has to Azure resources](https://docs.microsoft.com/en-us/azure/role-based-access-control/check-access)
* set up and perform an access review
  * [What are Azure AD access reviews?](https://docs.microsoft.com/en-us/azure/active-directory/governance/access-reviews-overview)
* implement and configure an Azure Policy
  * [What is Azure Policy?](https://docs.microsoft.com/en-us/azure/governance/policy/overview)
  * [Quickstart: Create a policy assignment to identify non-compliant resources](https://docs.microsoft.com/en-us/azure/governance/policy/assign-policy-portal)
  * [Tutorial: Create and manage policies to enforce compliance](https://docs.microsoft.com/en-us/azure/governance/policy/tutorials/create-and-manage)
* implement and configure an Azure Blueprint
  * [What is Azure Blueprints?](https://docs.microsoft.com/en-us/azure/governance/blueprints/overview)
  * [Quickstart: Define and assign a blueprint in the portal](https://docs.microsoft.com/en-us/azure/governance/blueprints/create-blueprint-portal)

Manage security for applications

* implement and configure KeyVault
  * [What is Azure Key Vault?](https://docs.microsoft.com/en-us/azure/key-vault/key-vault-overview)
  * [About keys, secrets, and certificates](https://docs.microsoft.com/en-us/azure/key-vault/about-keys-secrets-and-certificates)
* implement and configure Azure AD Managed Identities
  * [What are managed identities for Azure resources?](https://docs.microsoft.com/en-us/azure/active-directory/managed-identities-azure-resources/overview)
  * [Use a Windows VM system-assigned managed identity to access Resource Manager](https://docs.microsoft.com/en-us/azure/active-directory/managed-identities-azure-resources/tutorial-windows-vm-access-arm)
* register and manage applications in Azure AD
  * [Tutorial: Register an application in Azure Active Directory B2C](https://docs.microsoft.com/en-us/azure/active-directory-b2c/tutorial-register-applications?tabs=applications)

### Implement Solutions for Apps (10-15%)

Implement an application infrastructure

* create and configure Azure App Service
  * [App Service overview](https://docs.microsoft.com/en-us/azure/app-service/overview)
  * [Introduction to the App Service Environments](https://docs.microsoft.com/en-us/azure/app-service/environment/intro)
  * [Custom configuration and application settings in Azure Web Sites](https://azure.microsoft.com/en-us/resources/videos/configuration-and-app-settings-of-azure-web-sites)
  * [Configure an App Service app in the Azure portal](https://docs.microsoft.com/en-us/azure/app-service/configure-common)
  * [Buy a custom domain name for Azure App Service](https://docs.microsoft.com/en-us/azure/app-service/manage-custom-dns-buy-domain)
  * [Create an ASP.NET Core web app in Azure](https://docs.microsoft.com/en-us/azure/app-service/app-service-web-get-started-dotnet)
* create an App Service Web App for Containers
  * [Deploy a custom Linux container to Azure App Service](https://docs.microsoft.com/en-us/azure/app-service/containers/quickstart-docker)
* create and configure an App Service plan
  * [Azure App Service plan overview](https://docs.microsoft.com/en-us/azure/app-service/overview-hosting-plans)
  * [Manage an App Service plan in Azure](https://docs.microsoft.com/en-us/azure/app-service/app-service-plan-manage)
* configure an App Service
  * [Custom configuration and application settings in Azure Web Sites](https://azure.microsoft.com/en-us/resources/videos/configuration-and-app-settings-of-azure-web-sites)
  * [Configure an App Service app in the Azure portal](https://docs.microsoft.com/en-us/azure/app-service/configure-common)
  * [Buy a custom domain name for Azure App Service](https://docs.microsoft.com/en-us/azure/app-service/manage-custom-dns-buy-domain)
* configure networking for an App Service
  * [Networking considerations for an App Service Environment](https://docs.microsoft.com/en-us/azure/app-service/environment/network-info)
  * [App Service networking features](https://docs.microsoft.com/en-us/azure/app-service/networking-features)
  * [Integrate your app with an Azure Virtual Network](https://docs.microsoft.com/en-us/azure/app-service/web-sites-integrate-with-vnet)
* create and manage deployment slots
  * [Set up staging environments in Azure App Service](https://docs.microsoft.com/en-us/azure/app-service/deploy-staging-slots)
* implement Logic Apps
  * [Overview -- What is Azure Logic Apps?](https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-overview)
  * [Quickstart: Create your first workflow by using Azure Logic Apps -- Azure portal](https://docs.microsoft.com/en-us/azure/logic-apps/quickstart-create-first-logic-app-workflow)
  * [Quickstart: Create automated tasks, processes, and workflows with Azure Logic Apps -- Visual Studio](https://docs.microsoft.com/en-us/azure/logic-apps/quickstart-create-logic-apps-with-visual-studio)
  * [Quickstart: Create and manage logic app workflow definitions by using Visual Studio Code](https://docs.microsoft.com/en-us/azure/logic-apps/quickstart-create-logic-apps-visual-studio-code)
* implement Azure Functions
  * [An introduction to Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/functions-overview)
  * [Azure Functions triggers and bindings concepts](https://docs.microsoft.com/en-us/azure/azure-functions/functions-triggers-bindings)
  * [Azure Functions trigger and binding example](https://docs.microsoft.com/en-us/azure/azure-functions/functions-bindings-example)
  * [Azure Functions triggers and bindings concepts](https://docs.microsoft.com/en-us/azure/azure-functions/functions-triggers-bindings)
  * [Azure Functions trigger and binding example](https://docs.microsoft.com/en-us/azure/azure-functions/functions-bindings-example)
  * [Azure Functions HTTP triggers and bindings overview](https://docs.microsoft.com/en-us/azure/azure-functions/functions-bindings-http-webhook)
  * [What are Durable Functions?](https://docs.microsoft.com/en-us/azure/azure-functions/durable/durable-functions-overview)

Implement container-based applications

* create a container image
  * [Tutorial: Build and deploy container images in the cloud with Azure Container Registry Tasks](https://docs.microsoft.com/en-us/azure/container-registry/container-registry-tutorial-quick-task)
  * [Tutorial: Create container images on a Linux Service Fabric cluster](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-tutorial-create-container-images)
  * [Tutorial: Create a container image for deployment to Azure Container Instances](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-tutorial-prepare-app)
* configure Azure Kubernetes Service
  * [Azure Kubernetes Service (AKS)](https://docs.microsoft.com/en-us/azure/aks/intro-kubernetes)
  * [Quickstart: Deploy an Azure Kubernetes Service (AKS) cluster using the Azure portal](https://docs.microsoft.com/en-us/azure/aks/kubernetes-walkthrough-portal)
* publish and automate image deployment to the Azure Container Registry
  * [Push your first image to a private Docker container registry using the Docker CLI](https://docs.microsoft.com/en-us/azure/container-registry/container-registry-get-started-docker-cli)
  * [Tutorial: Build and deploy container images in the cloud with Azure Container Registry Tasks](https://docs.microsoft.com/en-us/azure/container-registry/container-registry-tutorial-quick-task)
* publish a solution on an Azure Container Instance
  * [What is Azure Container Instances?](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-overview)
  * [Quickstart: Deploy a container instance in Azure using the Azure portal](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-quickstart-portal)
  * [Quickstart: Deploy a container instance in Azure using the Azure CLI](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-quickstart)

### Implement and Manage Data Platforms (10-15%)

Implement NoSQL databases

* configure storage account tables
  * [Azure Table storage overview](https://docs.microsoft.com/en-us/azure/cosmos-db/table-storage-overview)
  * [Understanding the Table service data model](https://docs.microsoft.com/en-us/rest/api/storageservices/Understanding-the-Table-Service-Data-Model)
* select appropriate CosmosDB APIs
  * [Choose the appropriate API for Azure Cosmos DB storage](https://docs.microsoft.com/en-us/learn/modules/choose-api-for-cosmos-db) (Microsoft Learn module)
  * [Welcome to Azure Cosmos DB](https://docs.microsoft.com/en-us/azure/cosmos-db/introduction)
* set up replicas in CosmosDB
  * [Choose the right consistency level](https://docs.microsoft.com/en-us/azure/cosmos-db/consistency-levels-choosing)
  * [Consistency levels and Azure Cosmos DB APIs](https://docs.microsoft.com/en-us/azure/cosmos-db/consistency-levels-across-apis)
  * [Consistency, availability, and performance tradeoffs](https://docs.microsoft.com/en-us/azure/cosmos-db/consistency-levels-tradeoffs)

Implement Azure SQL databases

* configure Azure SQL database settings
  * [What is the Azure SQL Database service? ](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-technical-overview)
  * [Quickstart: Create a single database in Azure SQL Database using the Azure portal, PowerShell, and Azure CLI](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-single-database-get-started)
  * [Choose the right deployment option in Azure SQL](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-paas-vs-sql-server-iaas)
* implement Azure SQL Database managed instances
  * [SQL managed instance](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-managed-instance-index)
  * [What is Azure SQL Database managed instance?](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-managed-instance)
  * [Quickstart: Create an Azure SQL Database managed instance](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-managed-instance-get-started)
* configure HA for an Azure SQL database
  * [High-availability and Azure SQL Database](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-high-availability)
* publish an Azure SQL database
  * [Azure SQL database deployment](https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/azure-sqldb)
  * [Tutorial: Deploy your ASP.NET app and Azure SQL Database code by using Azure DevOps Projects](https://docs.microsoft.com/en-us/azure/devops-project/azure-devops-project-sql-database)
