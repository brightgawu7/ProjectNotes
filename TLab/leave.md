# T-Lab Leave Management API

---

<details>

<summary>
<code>POST</code> <code>api/leaves</code>  <code>Create Leave / Request Leave</code>
</summary>


```json
{
  "startDate": "2023-09-01",
  "endDate": "2023-09-10",
  "reason": "Family vacation"
}
```
</details>

---

<details>

<summary>
<code>GET</code> <code>api/leaves</code>  <code>Get all Leaves</code>
</summary>


```json
{
  "userId": "sasaa-asasa",
  "startDate": "2023-09-01",
  "endDate": "2023-09-10",
  "reason": "Family vacation"
}
```

</details>

---


<details>

<summary>
<code>GET</code> <code>api/users/leaves/id:userId</code>  <code>Get User Leave</code>
</summary>


```json
{
  "userId": "sasaa-asasa",
  "startDate": "2023-09-01",
  "endDate": "2023-09-10",
  "reason": "Family vacation"
}
```

</details>

---

<details>

<summary>
<code>PUT</code> <code>api/leaves/:leaveId</code>  <code>Update Leave</code>
</summary>


>  <b> Authorization Roles </b> [ admin , user ]

```json
{
  "startDate": "2023-09-01",
  "endDate": "2023-09-10",
  "reason": "Family vacation"
}
```
</details>

---

<details>

<summary>
<code>PUT</code> <code>api/leaves/revoke/:leaveId</code>  <code>Revoke Leave</code>
</summary>

>  <b> Authorization Roles </b> [ admin , user ]

</details>

---
<details>

<summary>
<code>DELETE</code> <code>api/leaves/:leaveId</code>  <code>Delete Leave</code>
</summary>

>  <b> Authorization Roles </b> [ admin ]

</details>
