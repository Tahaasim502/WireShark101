# Practice: Adding Columns in Wireshark

Wireshark allows you to customize the packet list view by adding columns for any field you want to monitor closely. This helps you analyze traffic more efficiently.

---

## Easy Method

1. In the **Packet Details** pane (middle pane), right-click the field you want to add as a column (e.g., `ip.src`, `tcp.dstport`).
2. Select **Apply as Column**.
3. The new column appears immediately in the packet list.

![image.png](attachment:ff80727c-f8a7-4d19-a6cd-43cdc7403f52:3993dc83-cd66-49a4-b9e4-ffa26bf5f240.png)



---

## Hard Method

1. Go to **Edit > Preferences > Appearance > Columns**.
2. Click the **+** button to add a new column.
3. Enter a **name** for the column.
4. Set **Type** to **Custom**.
5. In the **Fields** box, enter the exact field name (e.g., `ip.src`, `tcp.dstport`).
6. Click **OK** or **Apply** to save changes.

![image.png](attachment:ff80727c-f8a7-4d19-a6cd-43cdc7403f52:3993dc83-cd66-49a4-b9e4-ffa26bf5f240.png)

![image.png](attachment:ff80727c-f8a7-4d19-a6cd-43cdc7403f52:3993dc83-cd66-49a4-b9e4-ffa26bf5f240.png)

---

## Useful Fields to Try

| Field Name    | Description            |
|---------------|------------------------|
| `ip.src`      | Source IP address      |
| `ip.dst`      | Destination IP address |
| `tcp.srcport` | TCP source port        |
| `tcp.dstport` | TCP destination port   |
| `http.host`   | HTTP host header       |
| `dns.qry.name`| DNS query name         |

---

Adding custom columns helps you tailor Wireshark’s display to your specific analysis needs.


