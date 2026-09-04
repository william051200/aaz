# [Command] _mcc ent node get-deployment-details_

Retrieves Microsoft Connected Cache for Enterprise cache node details and keys needed to deploy cache node.

## Versions

### [2024-11-30-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5jb25uZWN0ZWRjYWNoZS9lbnRlcnByaXNlbWNjY3VzdG9tZXJzL3t9L2VudGVycHJpc2VtY2NjYWNoZW5vZGVzL3t9L2dldGNhY2hlbm9kZWluc3RhbGxkZXRhaWxz/2024-11-30-preview.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.connectedcache/enterprisemcccustomers/{}/enterprisemcccachenodes/{}/getcachenodeinstalldetails 2024-11-30-preview -->

### [2026-06-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5jb25uZWN0ZWRjYWNoZS9lbnRlcnByaXNlbWNjY3VzdG9tZXJzL3t9L2VudGVycHJpc2VtY2NjYWNoZW5vZGVzL3t9L2dldGNhY2hlbm9kZWluc3RhbGxkZXRhaWxz/2026-06-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.connectedcache/enterprisemcccustomers/{}/enterprisemcccachenodes/{}/getcachenodeinstalldetails 2026-06-01 -->

#### examples

- Get the keys and details needed to deploy a cache node
    ```bash
        mcc ent node get-deployment-details --mcc-resource-name MyMccResource --cache-node-name MyCacheNode --resource-group MyResourceGroup
    ```
