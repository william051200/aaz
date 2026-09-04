# [Command] _mcc ent node list_

Retrieves relevant information about all Microsoft Connected Cache for Enterprise cache nodes under the Microsoft Connected Cache for Enterprise resource.

## Versions

### [2023-05-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5jb25uZWN0ZWRjYWNoZS9lbnRlcnByaXNlbWNjY3VzdG9tZXJzL3t9L2VudGVycHJpc2VtY2NjYWNoZW5vZGVz/2023-05-01-preview.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.connectedcache/enterprisemcccustomers/{}/enterprisemcccachenodes 2023-05-01-preview -->

### [2024-11-30-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5jb25uZWN0ZWRjYWNoZS9lbnRlcnByaXNlbWNjY3VzdG9tZXJzL3t9L2VudGVycHJpc2VtY2NjYWNoZW5vZGVz/2024-11-30-preview.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.connectedcache/enterprisemcccustomers/{}/enterprisemcccachenodes 2024-11-30-preview -->

### [2026-06-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5jb25uZWN0ZWRjYWNoZS9lbnRlcnByaXNlbWNjY3VzdG9tZXJzL3t9L2VudGVycHJpc2VtY2NjYWNoZW5vZGVz/2026-06-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.connectedcache/enterprisemcccustomers/{}/enterprisemcccachenodes 2026-06-01 -->

#### examples

- List every cache node attached to an MCC Enterprise resource
    ```bash
        mcc ent node list --mcc-resource-name MyMccResource --resource-group MyResourceGroup
    ```

- List cache nodes with the full set of details
    ```bash
        mcc ent node list --mcc-resource-name MyMccResource --resource-group MyResourceGroup --expand-output
    ```
