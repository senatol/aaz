# [Command] _stack-hci cluster-update summary create_

Create Update summaries under the HCI cluster

## Versions

### [2023-03-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5henVyZXN0YWNraGNpL2NsdXN0ZXJzL3t9L3VwZGF0ZXN1bW1hcmllcy9kZWZhdWx0/2023-03-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.azurestackhci/clusters/{}/updatesummaries/default 2023-03-01 -->

#### examples

- Create cluster update summary
    ```bash
        stack-hci cluster-update summary create --cluster-name name -g rg
    ```