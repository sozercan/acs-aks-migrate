# acs-aks-migrate
⚒ Script to migrate from ACS Kubernetes clusters to ACS (RP v2 [regions](https://github.com/Azure/ACS/blob/master/acs_regional_avilability) ) or AKS cluster

__USE IT AT YOUR OWN RISK - DO NOT USE IN PRODUCTION__

* Set the following environment variables

```bash
AZURE_SUBSCRIPTION_ID=
AZURE_TENANT_ID=
AZURE_CLIENT_ID=
AZURE_CLIENT_SECRET=
KUBECONFIG=
DESTINATION_CLUSTERNAME=
DESTINATION_ACS_RESOURCEGROUP=
DESTINATION_STORAGEACCOUNT=
DESTINATION_STORAGEACCOUNT_CONTAINER=
DESTINATION_CLUSTERNAME_LOCATION=westus2
DESTINATION_MANAGED_DISK=
SOURCE_BLOB=
SOURCE_STORAGEACCOUNT_CONTAINER=
#SOURCE_SNAPSHOT=''
SOURCE_STORAGEACCOUNT=
SOURCE_STORAGEACCOUNT_KEY=
```
* Run script

```bash
bash migrate.sh
```
