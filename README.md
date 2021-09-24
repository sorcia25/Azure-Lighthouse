
# Microsoft Azure Lighthouse

Azure Lighthouse permite la administración de varios Tenants, lo que proporciona no solo mayores prestaciones de automatización y escalabilidad, sino también una mejor gobernanza de recursos y Tenants.

Con Azure Lighthouse, los proveedores de servicios pueden ofrecer servicios administrados mediante herramientas completas y potentes integradas en la plataforma Azure. Los clientes mantienen el control sobre quién tiene acceso a su Tenant, a qué recursos se puede acceder y qué acciones se pueden realizar. Esta oferta también puede ayudar a las organizaciones de TI empresariales a administrar recursos en varios Tenants.
. [Conocer más](https://azure.com/lighthouse).

Este repositorio contiene plantillas que ayudarán a nuestros clientes a enrolarse mediante [Azure delegated resource management](https://docs.microsoft.com/azure/lighthouse/concepts/azure-delegated-resource-management) y a configurar el monitoreo y la administración de los entornos del cleinte.

Las plantillas mostradas a continuación pueden ser utilizadas para [Hacer el onboarding de un cliente a Azure Lighthouse](https://docs.microsoft.com/en-us/azure/lighthouse/how-to/onboard-customer). Se pueden utilizar estas plantillas para hacer la implementación manual, o usar el botón "Deploy to Azure" para implementarlas directamenteen el portal de Azure del cliente.

# Deploy to Azure

Name | Description   | Auto-deploy   | Manual deploy |
-----| ------------- |--------------- |------- 
| Azure Lighthouse - Subscription Deployment |onboard a *subscription* | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Lighthouse-samples%2Fmaster%2Ftemplates%2Fdelegated-resource-management%2Fsubscription%2Fsubscription.json) | [templates](https://github.com/Azure/Azure-Lighthouse-samples/tree/master/templates/delegated-resource-management/subscription)
| Azure Lighthouse - Resource Group Deployment | onboard a *resource group* | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Lighthouse-samples%2Fmaster%2Ftemplates%2Fdelegated-resource-management%2Frg%2Frg.json) | [templates](https://github.com/Azure/Azure-Lighthouse-samples/tree/master/templates/delegated-resource-management/rg)
| Azure Lighthouse - Multiple Resource Group Deployment | onboard multiple *resource groups* | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Lighthouse-samples%2Fmaster%2Ftemplates%2Fdelegated-resource-management%2Frg%2Fmulti-rg.json) | [templates](https://github.com/Azure/Azure-Lighthouse-samples/tree/master/templates/delegated-resource-management/rg)
| Azure Lighthouse + Azure AD PIM - Subscription Deployment  | onboard a *subscription* using **Azure AD PIM** (preview) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Lighthouse-samples%2Fmaster%2Ftemplates%2Fdelegated-resource-management-eligible-authorizations%2Fsubscription%2Fsubscription.json) | [templates](https://github.com/Azure/Azure-Lighthouse-samples/tree/master/templates/delegated-resource-management-eligible-authorizations/subscription)
| Azure Lighthouse + Azure AD PIM - Resource Group Deployment | onboard a *resource group* using **Azure AD PIM** (preview) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Lighthouse-samples%2Fmaster%2Ftemplates%2Fdelegated-resource-management-eligible-authorizations%2Frg%2Frg.json) | [templates](https://github.com/Azure/Azure-Lighthouse-samples/tree/master/templates/delegated-resource-management-eligible-authorizations/rg)
| Azure Lighthouse + Azure AD PIM - Multiple Resource Group Deployment | onboard multiple *resource groups* using **Azure AD PIM** (preview) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Lighthouse-samples%2Fmaster%2Ftemplates%2Fdelegated-resource-management-eligible-authorizations%2Frg%2Fmultiple-rg.json) | [templates](https://github.com/Azure/Azure-Lighthouse-samples/tree/master/templates/delegated-resource-management-eligible-authorizations/rg)
| Azure Lighthouse + Azure AD PIM Managing Tenant Approvers - Subscription Deployment | onboard a *subscription* using **Azure AD PIM** with support for Managing tenant approvers (preview) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Lighthouse-samples%2Fmaster%2Ftemplates%2Fdelegated-resource-management-eligible-authorizations%2Fsubscription%2Fsubscription-managing-tenant-approvers.json) | [templates](https://github.com/Azure/Azure-Lighthouse-samples/tree/master/templates/delegated-resource-management-eligible-authorizations/subscription)
| Azure Lighthouse + Azure AD PIM Managing Tenant Approvers - Resource Group Deployment | onboard a *resource group* using **Azure AD PIM** with support for Managing tenant approvers (preview) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Lighthouse-samples%2Fmaster%2Ftemplates%2Fdelegated-resource-management-eligible-authorizations%2Frg%2Frg-managing-tenant-approvers.json) | [templates](https://github.com/Azure/Azure-Lighthouse-samples/tree/master/templates/delegated-resource-management-eligible-authorizations/rg)
| Azure Lighthouse + Azure AD PIM Managing Tenant Approvers - Multiple Resource Group Deployment | onboard multiple *resource groups* using **Azure AD PIM** with support for Managing tenant approvers (preview) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Lighthouse-samples%2Fmaster%2Ftemplates%2Fdelegated-resource-management-eligible-authorizations%2Frg%2Fmultiple-rg-managing-tenant-approvers.json) | [templates](https://github.com/Azure/Azure-Lighthouse-samples/tree/master/templates/delegated-resource-management-eligible-authorizations/rg)


**Special Instructions (for MSPs):**
To customize, fork this repository, and follow [these](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-to-azure-button) instructions to update the links to enable your customers to deploy your templates into their Azure environments.
# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

If you contribute any changes affecting the buttons above, please also update the buttons following the instructions [here](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-to-azure-button).
