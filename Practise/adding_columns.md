# Practice: Adding Columns in Wireshark

Wireshark allows you to customize the packet list view by adding columns for any field you want to monitor closely. This helps you analyze traffic more efficiently.

---

## Easy Method

1. In the **Packet Details** pane (middle pane), right-click the field you want to add as a column (e.g., `ip.src`, `tcp.dstport`).
2. Select **Apply as Column**.
3. The new column appears immediately in the packet list.

<img width="1366" height="716" alt="Screenshot (773)" src="https://github.com/user-attachments/assets/316c0a87-059a-4e0b-bd01-13aa5248d567" />

<img width="1366" height="718" alt="Screenshot (772)" src="https://github.com/user-attachments/assets/42147c4e-36c8-4dc2-9584-641d484f87b6" />


---

## Hard Method

1. Go to **Edit > Preferences > Appearance > Columns**.
2. Click the **+** button to add a new column.
3. Enter a **name** for the column.
4. Set **Type** to **Custom**.
5. In the **Fields** box, enter the exact field name (e.g., `ip.src`, `tcp.dstport`).
6. Click **OK** or **Apply** to save changes.

<img width="1366" height="714" alt="Screenshot (775)" src="https://github.com/user-attachments/assets/67f852d1-54e9-44ae-93b3-511ff84cdd9a" />

<img width="1366" height="720" alt="Screenshot (774)" src="https://github.com/user-attachments/assets/9f0f5917-6d00-4ae2-b822-42ac6d928b77" />


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


