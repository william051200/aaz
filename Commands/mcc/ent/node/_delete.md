# [Command] _mcc ent node delete_

Deletes a Microsoft Connected Cache for Enterprise cache node.

## Versions

### [2023-05-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5jb25uZWN0ZWRjYWNoZS9lbnRlcnByaXNlbWNjY3VzdG9tZXJzL3t9L2VudGVycHJpc2VtY2NjYWNoZW5vZGVzL3t9/2023-05-01-preview.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.connectedcache/enterprisemcccustomers/{}/enterprisemcccachenodes/{} 2023-05-01-preview -->

### [2024-11-30-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5jb25uZWN0ZWRjYWNoZS9lbnRlcnByaXNlbWNjY3VzdG9tZXJzL3t9L2VudGVycHJpc2VtY2NjYWNoZW5vZGVzL3t9/2024-11-30-preview.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.connectedcache/enterprisemcccustomers/{}/enterprisemcccachenodes/{} 2024-11-30-preview -->

### [2026-06-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5jb25uZWN0ZWRjYWNoZS9lbnRlcnByaXNlbWNjY3VzdG9tZXJzL3t9L2VudGVycHJpc2VtY2NjYWNoZW5vZGVzL3t9/2026-06-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.connectedcache/enterprisemcccustomers/{}/enterprisemcccachenodes/{} 2026-06-01 -->

#### examples

- Delete an MCC Enterprise cache node
    ```bash
        mcc ent node delete --mcc-resource-name MyMccResource --cache-node-name MyCacheNode --resource-group MyResourceGroup
    ```
