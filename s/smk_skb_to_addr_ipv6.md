# Function: <code>smk_skb_to_addr_ipv6</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81361e00)
Location: security/smack/smack_lsm.c:3892
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81361e00-ffffffff81361fb2: smk_skb_to_addr_ipv6.isra.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81397f50)
Location: security/smack/smack_lsm.c:3911
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81397f50-ffffffff81398178: smk_skb_to_addr_ipv6.isra.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813aeb30)
Location: security/smack/smack_lsm.c:3901
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff813aeb30-ffffffff813aed58: smk_skb_to_addr_ipv6.isra.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813c3540)
Location: security/smack/smack_lsm.c:3743
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff813c3540-ffffffff813c374e: smk_skb_to_addr_ipv6.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813e9800)
Location: security/smack/smack_lsm.c:3708
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff813e9800-ffffffff813e9a0e: smk_skb_to_addr_ipv6.isra.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8141a720)
Location: security/smack/smack_lsm.c:3865
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff8141a720-ffffffff8141a93c: smk_skb_to_addr_ipv6.isra.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81436b00)
Location: security/smack/smack_lsm.c:3685
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81436b00-ffffffff81436d14: smk_skb_to_addr_ipv6.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814647c0)
Location: security/smack/smack_lsm.c:3784
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff814647c0-ffffffff814649db: smk_skb_to_addr_ipv6.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8147e590)
Location: security/smack/smack_lsm.c:3779
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff8147e590-ffffffff8147e7ab: smk_skb_to_addr_ipv6.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int smk_skb_to_addr_ipv6(struct sk_buff *skb, struct sockaddr_in6 *sip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814d3e30)
Location: security/smack/smack_lsm.c:3765
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff814d3e30-ffffffff814d404a: smk_skb_to_addr_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int smk_skb_to_addr_ipv6(struct sk_buff *skb, struct sockaddr_in6 *sip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f1300)
Location: security/smack/smack_lsm.c:3787
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff814f1300-ffffffff814f151a: smk_skb_to_addr_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int smk_skb_to_addr_ipv6(struct sk_buff *skb, struct sockaddr_in6 *sip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f7fa0)
Location: security/smack/smack_lsm.c:3786
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff814f7fa0-ffffffff814f81cb: smk_skb_to_addr_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int smk_skb_to_addr_ipv6(struct sk_buff *skb, struct sockaddr_in6 *sip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81552b90)
Location: security/smack/smack_lsm.c:3786
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81552b90-ffffffff81552dbb: smk_skb_to_addr_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int smk_skb_to_addr_ipv6(struct sk_buff *skb, struct sockaddr_in6 *sip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff815ec680)
Location: security/smack/smack_lsm.c:3795
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff815ec680-ffffffff815ec90d: smk_skb_to_addr_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int smk_skb_to_addr_ipv6(struct sk_buff *skb, struct sockaddr_in6 *sip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8169c380)
Location: security/smack/smack_lsm.c:3863
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff8169c380-ffffffff8169c60d: smk_skb_to_addr_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int smk_skb_to_addr_ipv6(struct sk_buff *skb, struct sockaddr_in6 *sip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff816d50b0)
Location: security/smack/smack_lsm.c:3926
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff816d50b0-ffffffff816d5349: smk_skb_to_addr_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int smk_skb_to_addr_ipv6(struct sk_buff *skb, struct sockaddr_in6 *sip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81711460)
Location: security/smack/smack_lsm.c:4050
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81711460-ffffffff817116f9: smk_skb_to_addr_ipv6 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (ffff80001056f798)
Location: security/smack/smack_lsm.c:3779
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffff80001056f798-ffff80001056f9ac: smk_skb_to_addr_ipv6.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int smk_skb_to_addr_ipv6(struct sk_buff *skb, struct sockaddr_in6 *sip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0722e00)
Location: security/smack/smack_lsm.c:3779
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
c0722e00-c0723038: smk_skb_to_addr_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (c0000000006d4cf0)
Location: security/smack/smack_lsm.c:3779
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
c0000000006d4cf0-c0000000006d4fbc: smk_skb_to_addr_ipv6.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int smk_skb_to_addr_ipv6(struct sk_buff *skb, struct sockaddr_in6 *sip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffe0003c57b4)
Location: security/smack/smack_lsm.c:3779
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffe0003c57b4-ffffffe0003c5986: smk_skb_to_addr_ipv6 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81476b70)
Location: security/smack/smack_lsm.c:3779
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81476b70-ffffffff81476d8b: smk_skb_to_addr_ipv6.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81467590)
Location: security/smack/smack_lsm.c:3779
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81467590-ffffffff814677ab: smk_skb_to_addr_ipv6.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81472c10)
Location: security/smack/smack_lsm.c:3779
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81472c10-ffffffff81472e2b: smk_skb_to_addr_ipv6.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8148a500)
Location: security/smack/smack_lsm.c:3779
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff8148a500-ffffffff8148a71b: smk_skb_to_addr_ipv6.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
