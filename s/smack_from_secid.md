# Function: <code>smack_from_secid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81362ce0)
Location: security/smack/smack_access.c:601
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_kernel_act_as
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81362ce0-ffffffff81362d26: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81398eb0)
Location: security/smack/smack_access.c:601
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffffffff81398eb0-ffffffff81398ef3: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813afa90)
Location: security/smack/smack_access.c:596
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffffffff813afa90-ffffffff813afad3: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813c6640)
Location: security/smack/smack_access.c:596
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffffffff813c6640-ffffffff813c6678: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813ec930)
Location: security/smack/smack_access.c:596
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffffffff813ec930-ffffffff813ec968: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8141d760)
Location: security/smack/smack_access.c:596
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffffffff8141d760-ffffffff8141d798: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81439d50)
Location: security/smack/smack_access.c:596
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffffffff81439d50-ffffffff81439d88: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81467910)
Location: security/smack/smack_access.c:592
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffffffff81467910-ffffffff81467945: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814816f0)
Location: security/smack/smack_access.c:592
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffffffff814816f0-ffffffff81481725: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814d76f0)
Location: security/smack/smack_access.c:592
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffffffff814d76f0-ffffffff814d7725: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814f4c30)
Location: security/smack/smack_access.c:614
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_from_netlbl
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffffffff814f4c30-ffffffff814f4c84: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814fbba0)
Location: security/smack/smack_access.c:614
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_from_netlbl
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffffffff814fbba0-ffffffff814fbbf4: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81556810)
Location: security/smack/smack_access.c:616
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_from_netlbl
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffffffff81556810-ffffffff81556864: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff815f0c10)
Location: security/smack/smack_access.c:613
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_from_netlbl
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffffffff815f0c10-ffffffff815f0c75: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff816a1060)
Location: security/smack/smack_access.c:610
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_from_netlbl
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffffffff816a1060-ffffffff816a10c5: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff816d99a0)
Location: security/smack/smack_access.c:610
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_from_netlbl
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffffffff816d99a0-ffffffff816d9a05: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81716440)
Location: security/smack/smack_access.c:610
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_from_netlbl
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffffffff81716440-ffffffff817164a5: smack_from_secid (STB_GLOBAL)
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
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffff8000105730b8)
Location: security/smack/smack_access.c:592
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffff8000105730b8-ffff800010573120: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (c0726244)
Location: security/smack/smack_access.c:592
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
c0726244-c072629c: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (c0000000006db340)
Location: security/smack/smack_access.c:592
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
c0000000006db340-c0000000006db3a8: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffe0003c65cc)
Location: security/smack/smack_access.c:592
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffffffe0003c65cc-ffffffe0003c6620: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81479cd0)
Location: security/smack/smack_access.c:592
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffffffff81479cd0-ffffffff81479d05: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8146a6f0)
Location: security/smack/smack_access.c:592
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffffffff8146a6f0-ffffffff8146a725: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81475d70)
Location: security/smack/smack_access.c:592
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffffffff81475d70-ffffffff81475da5: smack_from_secid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct smack_known *smack_from_secid(const u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8148d7c0)
Location: security/smack/smack_access.c:592
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_secid_to_secctx
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_kernel_act_as
```
**Symbols:**

```
ffffffff8148d7c0-ffffffff8148d81a: smack_from_secid (STB_GLOBAL)
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
