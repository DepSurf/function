# Function: <code>ip_append_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8175ddd0)
Location: net/ipv4/ip_output.c:1166
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff8175ddd0-ffffffff8175dea3: ip_append_data.part.43 (STB_LOCAL)
ffffffff8175eae0-ffffffff8175eb16: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817cba21)
Location: net/ipv4/ip_output.c:1164
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff817c9260-ffffffff817c9333: ip_append_data.part.44 (STB_LOCAL)
ffffffff817cad90-ffffffff817cadc6: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817fb68e)
Location: net/ipv4/ip_output.c:1205
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff817f8e00-ffffffff817f8ed3: ip_append_data.part.46 (STB_LOCAL)
ffffffff817fa9f0-ffffffff817faa26: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8181ba60)
Location: net/ipv4/ip_output.c:1217
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81819230-ffffffff818192f5: ip_append_data.part.46 (STB_LOCAL)
ffffffff8181ae00-ffffffff8181ae28: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8189a999)
Location: net/ipv4/ip_output.c:1149
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81899270-ffffffff81899335: ip_append_data.part.43 (STB_LOCAL)
ffffffff81899de0-ffffffff81899e08: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff818eeecd)
Location: net/ipv4/ip_output.c:1173
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff818ed440-ffffffff818ed503: ip_append_data.part.50 (STB_LOCAL)
ffffffff818ee270-ffffffff818ee298: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8191c6bd)
Location: net/ipv4/ip_output.c:1199
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff8191ae80-ffffffff8191af43: ip_append_data.part.54 (STB_LOCAL)
ffffffff8191ba40-ffffffff8191ba68: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8197e9e8)
Location: net/ipv4/ip_output.c:1288
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff8197d130-ffffffff8197d1ec: ip_append_data.part.0 (STB_LOCAL)
ffffffff8197dd20-ffffffff8197dd48: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819b537a)
Location: net/ipv4/ip_output.c:1296
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff819b3ad0-ffffffff819b3b9b: ip_append_data.part.0 (STB_LOCAL)
ffffffff819b46c0-ffffffff819b46e8: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a9f5df)
Location: net/ipv4/ip_output.c:1295
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81a9dbd0-ffffffff81a9dc98: ip_append_data.part.0 (STB_LOCAL)
ffffffff81a9e7c0-ffffffff81a9e896: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81aa951f)
Location: net/ipv4/ip_output.c:1302
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81aa7aa0-ffffffff81aa7b68: ip_append_data.part.0 (STB_LOCAL)
ffffffff81aa8710-ffffffff81aa87e6: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a946ec)
Location: net/ipv4/ip_output.c:1306
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81a92c90-ffffffff81a92d58: ip_append_data.part.0 (STB_LOCAL)
ffffffff81a93830-ffffffff81a93906: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81b4fb6c)
Location: net/ipv4/ip_output.c:1305
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81b4e090-ffffffff81b4e158: ip_append_data.part.0 (STB_LOCAL)
ffffffff81b4ec70-ffffffff81b4ed46: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81cdd5d9)
Location: net/ipv4/ip_output.c:1305
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81cdb930-ffffffff81cdba0a: ip_append_data.part.0 (STB_LOCAL)
ffffffff81cdc5a0-ffffffff81cdc688: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81e9e097)
Location: net/ipv4/ip_output.c:1322
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81e9c2d0-ffffffff81e9c3d9: ip_append_data.part.0 (STB_LOCAL)
ffffffff820ae465-ffffffff820ae498: ip_append_data.part.0.cold (STB_LOCAL)
ffffffff820ae498-ffffffff820ae4d3: ip_append_data.cold (STB_LOCAL)
ffffffff81e9cfe0-ffffffff81e9d0d6: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81efc861)
Location: net/ipv4/ip_output.c:1340
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81efaeb0-ffffffff81efafc0: ip_append_data.part.0 (STB_LOCAL)
ffffffff8212f97e-ffffffff8212f9b1: ip_append_data.part.0.cold (STB_LOCAL)
ffffffff8212f9b1-ffffffff8212f9ec: ip_append_data.cold (STB_LOCAL)
ffffffff81efbc20-ffffffff81efbd1d: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81fc07a1)
Location: net/ipv4/ip_output.c:1344
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81fbedb0-ffffffff81fbeec0: ip_append_data.part.0 (STB_LOCAL)
ffffffff82211711-ffffffff82211744: ip_append_data.part.0.cold (STB_LOCAL)
ffffffff82211744-ffffffff8221177f: ip_append_data.cold (STB_LOCAL)
ffffffff81fbfb60-ffffffff81fbfc5d: ip_append_data (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffff800010c65aac)
Location: net/ipv4/ip_output.c:1296
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffff800010c63428-ffff800010c63514: ip_append_data.part.0 (STB_LOCAL)
ffff800010c64e10-ffff800010c64eac: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (c0d75718)
Location: net/ipv4/ip_output.c:1296
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
c0d73e30-c0d73ef0: ip_append_data.part.0 (STB_LOCAL)
c0d74a74-c0d74acc: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (c000000000d6a23c)
Location: net/ipv4/ip_output.c:1296
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
c000000000d68230-c000000000d68350: ip_append_data.part.0 (STB_LOCAL)
c000000000d691b0-c000000000d691e8: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffe0007cd1a8)
Location: net/ipv4/ip_output.c:1296
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffe0007cbca0-ffffffe0007cbd5c: ip_append_data.part.0 (STB_LOCAL)
ffffffe0007cc728-ffffffe0007cc79c: ip_append_data (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819551ea)
Location: net/ipv4/ip_output.c:1296
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81953940-ffffffff81953a0b: ip_append_data.part.0 (STB_LOCAL)
ffffffff81954530-ffffffff81954558: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8190ecda)
Location: net/ipv4/ip_output.c:1296
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff8190d430-ffffffff8190d4fb: ip_append_data.part.0 (STB_LOCAL)
ffffffff8190e020-ffffffff8190e048: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819bf9ba)
Location: net/ipv4/ip_output.c:1296
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff819be110-ffffffff819be1db: ip_append_data.part.0 (STB_LOCAL)
ffffffff819bed00-ffffffff819bed28: ip_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ip_append_data(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819c9339)
Location: net/ipv4/ip_output.c:1296
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff819c7a20-ffffffff819c7aeb: ip_append_data.part.0 (STB_LOCAL)
ffffffff819c8680-ffffffff819c86a8: ip_append_data (STB_GLOBAL)
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
