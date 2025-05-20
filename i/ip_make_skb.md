# Function: <code>ip_make_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8175f4c0)
Location: net/ipv4/ip_output.c:1487
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff8175f4c0-ffffffff8175f5d2: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817cb760)
Location: net/ipv4/ip_output.c:1485
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff817cb760-ffffffff817cb872: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817fb3c0)
Location: net/ipv4/ip_output.c:1526
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff817fb3c0-ffffffff817fb4d2: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8181b7b0)
Location: net/ipv4/ip_output.c:1539
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff8181b7b0-ffffffff8181b8bd: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8189a6e0)
Location: net/ipv4/ip_output.c:1457
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff8189a6e0-ffffffff8189a7ed: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, struct inet_cork *cork, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff818eebb0)
Location: net/ipv4/ip_output.c:1481
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff818eebb0-ffffffff818eecb5: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, struct inet_cork *cork, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8191c350)
Location: net/ipv4/ip_output.c:1508
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff8191c350-ffffffff8191c455: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, struct inet_cork *cork, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8197e680)
Location: net/ipv4/ip_output.c:1597
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff8197e680-ffffffff8197e782: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, struct inet_cork *cork, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819b5020)
Location: net/ipv4/ip_output.c:1605
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff819b5020-ffffffff819b5122: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, struct inet_cork *cork, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a9f2a0)
Location: net/ipv4/ip_output.c:1604
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff81a9f2a0-ffffffff81a9f3a1: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, struct inet_cork *cork, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81aa91e0)
Location: net/ipv4/ip_output.c:1611
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff81aa91e0-ffffffff81aa92e1: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, struct inet_cork *cork, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a94380)
Location: net/ipv4/ip_output.c:1615
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff81a94380-ffffffff81a94481: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, struct inet_cork *cork, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81b4f800)
Location: net/ipv4/ip_output.c:1614
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff81b4f800-ffffffff81b4f901: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, struct inet_cork *cork, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81cdd1e0)
Location: net/ipv4/ip_output.c:1614
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff81cdd1e0-ffffffff81cdd32f: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, struct inet_cork *cork, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81e9dc90)
Location: net/ipv4/ip_output.c:1629
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff81e9dc90-ffffffff81e9dddf: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, struct inet_cork *cork, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81efc450)
Location: net/ipv4/ip_output.c:1529
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff81efc450-ffffffff81efc59f: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, struct inet_cork *cork, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81fc0390)
Location: net/ipv4/ip_output.c:1535
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff81fc0390-ffffffff81fc04df: ip_make_skb (STB_GLOBAL)
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
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, struct inet_cork *cork, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffff800010c657c0)
Location: net/ipv4/ip_output.c:1605
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffff800010c657c0-ffff800010c658fc: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, struct inet_cork *cork, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c0d75430)
Location: net/ipv4/ip_output.c:1605
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
c0d75430-c0d75554: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, struct inet_cork *cork, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c000000000d69ea0)
Location: net/ipv4/ip_output.c:1605
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
c000000000d69ea0-c000000000d6a03c: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, struct inet_cork *cork, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffe0007ccf9e)
Location: net/ipv4/ip_output.c:1605
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffe0007ccf9e-ffffffe0007cd07a: ip_make_skb (STB_GLOBAL)
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
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, struct inet_cork *cork, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81954e90)
Location: net/ipv4/ip_output.c:1605
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff81954e90-ffffffff81954f92: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, struct inet_cork *cork, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8190e980)
Location: net/ipv4/ip_output.c:1605
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff8190e980-ffffffff8190ea82: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, struct inet_cork *cork, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819bf660)
Location: net/ipv4/ip_output.c:1605
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff819bf660-ffffffff819bf762: ip_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *ip_make_skb(struct sock *sk, struct flowi4 *fl4, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm_cookie *ipc, struct rtable **rtp, struct inet_cork *cork, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819c8fe0)
Location: net/ipv4/ip_output.c:1605
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff819c8fe0-ffffffff819c90e2: ip_make_skb (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inet_cork *cork</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, fl4, getfrag, from, length, transhdrlen, ipc, rtp, flags</code> ➡️ <code>sk, fl4, getfrag, from, length, transhdrlen, ipc, rtp, cork, flags</code>
</li>
</ul>
</details>
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
