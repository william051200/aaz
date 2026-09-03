# [Command] _mcc ent node update_

Configures a Microsoft Connected Cache for Enterprise cache node with specified configuration parameters.

## Versions

### [2023-05-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5jb25uZWN0ZWRjYWNoZS9lbnRlcnByaXNlbWNjY3VzdG9tZXJzL3t9L2VudGVycHJpc2VtY2NjYWNoZW5vZGVzL3t9/2023-05-01-preview.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.connectedcache/enterprisemcccustomers/{}/enterprisemcccachenodes/{} 2023-05-01-preview -->

### [2024-11-30-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5jb25uZWN0ZWRjYWNoZS9lbnRlcnByaXNlbWNjY3VzdG9tZXJzL3t9L2VudGVycHJpc2VtY2NjYWNoZW5vZGVzL3t9/2024-11-30-preview.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.connectedcache/enterprisemcccustomers/{}/enterprisemcccachenodes/{} 2024-11-30-preview -->

### [2026-06-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5jb25uZWN0ZWRjYWNoZS9lbnRlcnByaXNlbWNjY3VzdG9tZXJzL3t9L2VudGVycHJpc2VtY2NjYWNoZW5vZGVzL3t9/2026-06-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.connectedcache/enterprisemcccustomers/{}/enterprisemcccachenodes/{} 2026-06-01 -->

#### examples

- Configure the cache drives of a cache node
    ```bash
        mcc ent node update --mcc-resource-name MyMccResource --cache-node-name MyCacheNode --resource-group MyResourceGroup --cache-drive "[{physical-path:/var/mcc,size-in-gb:200}]"
    ```

- Move a cache node to the Stable update ring (an install schedule is required)
    ```bash
        mcc ent node update --mcc-resource-name MyMccResource --cache-node-name MyCacheNode --resource-group MyResourceGroup --auto-update-ring Stable --auto-update-day 2 --auto-update-week 3 --auto-update-time 02:00
    ```

- Move a cache node to the Beta update ring (the schedule is managed by Microsoft)
    ```bash
        mcc ent node update --mcc-resource-name MyMccResource --cache-node-name MyCacheNode --resource-group MyResourceGroup --auto-update-ring Beta
    ```

- Route a cache node through an outbound proxy
    ```bash
        mcc ent node update --mcc-resource-name MyMccResource --cache-node-name MyCacheNode --resource-group MyResourceGroup --proxy Enabled --proxy-host proxy.contoso.com --proxy-port 8080
    ```
