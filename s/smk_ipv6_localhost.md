# Function: <code>smk_ipv6_localhost</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8135e425)
Location: security/smack/smack_lsm.c:2381
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81394565)
Location: security/smack/smack_lsm.c:2400
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813ab0a5)
Location: security/smack/smack_lsm.c:2399
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813c19b5)
Location: security/smack/smack_lsm.c:2313
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813e8055)
Location: security/smack/smack_lsm.c:2282
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81418e95)
Location: security/smack/smack_lsm.c:2407
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81435575)
Location: security/smack/smack_lsm.c:2245
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool smk_ipv6_localhost(struct sockaddr_in6 *sip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81464090)
Location: security/smack/smack_lsm.c:2332
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
**Symbols:**

```
ffffffff81464090-ffffffff814640c2: smk_ipv6_localhost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool smk_ipv6_localhost(struct sockaddr_in6 *sip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8147de60)
Location: security/smack/smack_lsm.c:2329
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
**Symbols:**

```
ffffffff8147de60-ffffffff8147de92: smk_ipv6_localhost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814d6d2e)
Location: security/smack/smack_lsm.c:2316
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_ipv6host_label
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f29ca)
Location: security/smack/smack_lsm.c:2316
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_ipv6host_label
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f991d)
Location: security/smack/smack_lsm.c:2315
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_ipv6host_label
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff815544fd)
Location: security/smack/smack_lsm.c:2315
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_ipv6host_label
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff815f02c7)
Location: security/smack/smack_lsm.c:2321
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_ipv6host_label
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff816a0677)
Location: security/smack/smack_lsm.c:2396
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_ipv6host_label
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff816d8e3f)
Location: security/smack/smack_lsm.c:2459
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_ipv6host_label
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81715a16)
Location: security/smack/smack_lsm.c:2512
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_ipv6host_label
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool smk_ipv6_localhost(struct sockaddr_in6 *sip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffff80001056e8a8)
Location: security/smack/smack_lsm.c:2329
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
**Symbols:**

```
ffff80001056e8a8-ffff80001056e914: smk_ipv6_localhost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool smk_ipv6_localhost(struct sockaddr_in6 *sip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0722614)
Location: security/smack/smack_lsm.c:2329
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
**Symbols:**

```
c0722614-c0722674: smk_ipv6_localhost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool smk_ipv6_localhost(struct sockaddr_in6 *sip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0000000006d4b20)
Location: security/smack/smack_lsm.c:2329
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
**Symbols:**

```
c0000000006d4b20-c0000000006d4b88: smk_ipv6_localhost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool smk_ipv6_localhost(struct sockaddr_in6 *sip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffe0003c4bdc)
Location: security/smack/smack_lsm.c:2329
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
**Symbols:**

```
ffffffe0003c4bdc-ffffffe0003c4c2e: smk_ipv6_localhost (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool smk_ipv6_localhost(struct sockaddr_in6 *sip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81476440)
Location: security/smack/smack_lsm.c:2329
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
**Symbols:**

```
ffffffff81476440-ffffffff81476472: smk_ipv6_localhost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool smk_ipv6_localhost(struct sockaddr_in6 *sip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81466e60)
Location: security/smack/smack_lsm.c:2329
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
**Symbols:**

```
ffffffff81466e60-ffffffff81466e92: smk_ipv6_localhost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool smk_ipv6_localhost(struct sockaddr_in6 *sip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814724e0)
Location: security/smack/smack_lsm.c:2329
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
**Symbols:**

```
ffffffff814724e0-ffffffff81472512: smk_ipv6_localhost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool smk_ipv6_localhost(struct sockaddr_in6 *sip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81489dd0)
Location: security/smack/smack_lsm.c:2329
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_ipv6host_label
```
**Symbols:**

```
ffffffff81489dd0-ffffffff81489e02: smk_ipv6_localhost (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
