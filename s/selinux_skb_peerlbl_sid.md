# Function: <code>selinux_skb_peerlbl_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81343e60)
Location: security/selinux/hooks.c:3988
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81343e60-ffffffff81343ef8: selinux_skb_peerlbl_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81378b30)
Location: security/selinux/hooks.c:4119
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81378b30-ffffffff81378bc4: selinux_skb_peerlbl_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8138f510)
Location: security/selinux/hooks.c:4194
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff8138f510-ffffffff8138f5a4: selinux_skb_peerlbl_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a59f0)
Location: security/selinux/hooks.c:4168
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff813a59f0-ffffffff813a5a84: selinux_skb_peerlbl_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cb640)
Location: security/selinux/hooks.c:4183
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff813cb640-ffffffff813cb6d4: selinux_skb_peerlbl_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:4449
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff813fa250-ffffffff813fa2e3: selinux_skb_peerlbl_sid (STB_LOCAL)
ffffffff81402a7d-ffffffff81402a93: selinux_skb_peerlbl_sid.cold.76 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:4169
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff814166b0-ffffffff81416743: selinux_skb_peerlbl_sid (STB_LOCAL)
ffffffff8141e656-ffffffff8141e66c: selinux_skb_peerlbl_sid.cold.72 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:4357
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81444110-ffffffff814441a3: selinux_skb_peerlbl_sid (STB_LOCAL)
ffffffff8144c246-ffffffff8144c25c: selinux_skb_peerlbl_sid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:4415
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff8145dc80-ffffffff8145dd13: selinux_skb_peerlbl_sid (STB_LOCAL)
ffffffff81466036-ffffffff8146604c: selinux_skb_peerlbl_sid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:4408
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff814b0e30-ffffffff814b0ec3: selinux_skb_peerlbl_sid (STB_LOCAL)
ffffffff814b9d1e-ffffffff814b9d34: selinux_skb_peerlbl_sid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:4424
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff814ce040-ffffffff814ce0d3: selinux_skb_peerlbl_sid (STB_LOCAL)
ffffffff81bf01c8-ffffffff81bf01de: selinux_skb_peerlbl_sid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:4588
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff814d4790-ffffffff814d4823: selinux_skb_peerlbl_sid (STB_LOCAL)
ffffffff81be2247-ffffffff81be225d: selinux_skb_peerlbl_sid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:4573
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff8152d430-ffffffff8152d4c3: selinux_skb_peerlbl_sid (STB_LOCAL)
ffffffff81cd3607-ffffffff81cd361d: selinux_skb_peerlbl_sid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:4477
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_process_new_assoc
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff815c3d00-ffffffff815c3dba: selinux_skb_peerlbl_sid (STB_LOCAL)
ffffffff81e8671c-ffffffff81e86732: selinux_skb_peerlbl_sid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81670860)
Location: security/selinux/hooks.c:4495
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_process_new_assoc
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81670860-ffffffff81670921: selinux_skb_peerlbl_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816a8e40)
Location: security/selinux/hooks.c:4456
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_process_new_assoc
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff816a8e40-ffffffff816a8ef7: selinux_skb_peerlbl_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816e58c0)
Location: security/selinux/hooks.c:4544
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_process_new_assoc
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff816e58c0-ffffffff816e5977: selinux_skb_peerlbl_sid (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff80001054ac38)
Location: security/selinux/hooks.c:4415
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffff80001054ac38-ffff80001054acf4: selinux_skb_peerlbl_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0700a74)
Location: security/selinux/hooks.c:4415
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
c0700a74-c0700b34: selinux_skb_peerlbl_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a2a90)
Location: security/selinux/hooks.c:4415
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
c0000000006a2a90-c0000000006a2b80: selinux_skb_peerlbl_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a5628)
Location: security/selinux/hooks.c:4415
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffe0003a5628-ffffffe0003a56ba: selinux_skb_peerlbl_sid (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:4415
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81456260-ffffffff814562f3: selinux_skb_peerlbl_sid (STB_LOCAL)
ffffffff8145e616-ffffffff8145e62c: selinux_skb_peerlbl_sid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:4415
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81446ca0-ffffffff81446d33: selinux_skb_peerlbl_sid (STB_LOCAL)
ffffffff8144f046-ffffffff8144f05c: selinux_skb_peerlbl_sid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:4415
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81452300-ffffffff81452393: selinux_skb_peerlbl_sid (STB_LOCAL)
ffffffff8145a6b6-ffffffff8145a6cc: selinux_skb_peerlbl_sid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff *skb, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:4415
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81468ef0-ffffffff81468f83: selinux_skb_peerlbl_sid (STB_LOCAL)
ffffffff81471e56-ffffffff81471e6c: selinux_skb_peerlbl_sid.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
