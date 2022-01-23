{
    "sku": {
        "name": "Standard_LRS",
        "tier": "Standard"
    },
    "kind": "StorageV2",
    "id": "/subscriptions/4dba6910-695d-4537-ac42-54d88f0387e5/resourceGroups/learn-f66b3ccb-e126-4023-b817-979c182b7ad1/providers/Microsoft.Storage/storageAccounts/theazurestorageaccount",
    "name": "praveenkinghut",
    "type": "Microsoft.Storage/storageAccounts",
    "location": "southindia",
    "tags": {
        "Tobey Maguire": "Cheeseburger",
        "Andrew Garfield": "Hot Dog",
        "Tom Holland": "Peanut Butter Sandwich"
    },
    "properties": {
        "minimumTlsVersion": "TLS1_2",
        "allowBlobPublicAccess": true,
        "allowSharedKeyAccess": true,
        "networkAcls": {
            "bypass": "AzureServices",
            "virtualNetworkRules": [],
            "ipRules": [],
            "defaultAction": "Allow"
        },
        "supportsHttpsTrafficOnly": true,
        "encryption": {
            "services": {
                "file": {
                    "enabled": true,
                    "lastEnabledTime": "2022-01-23T14:23:35.3694062Z"
                },
                "blob": {
                    "enabled": true,
                    "lastEnabledTime": "2022-01-23T14:23:35.3694062Z"
                }
            },
            "keySource": "Microsoft.Storage"
        },
        "accessTier": "Hot",
        "provisioningState": "Succeeded",
        "creationTime": "2022-01-23T14:23:35.3069050Z",
        "primaryEndpoints": {
            "dfs": "https://praveenkinghut.dfs.core.windows.net/",
            "web": "https://praveenkinghut.z30.web.core.windows.net/",
            "blob": "https://praveenkinghut.blob.core.windows.net/",
            "queue": "https://praveenkinghut.queue.core.windows.net/",
            "table": "https://praveenkinghut.table.core.windows.net/",
            "file": "https://praveenkinghut.file.core.windows.net/"
        },
        "primaryLocation": "southindia",
        "statusOfPrimary": "available"
    }
}
