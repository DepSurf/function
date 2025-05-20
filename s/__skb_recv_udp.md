# Function: <code>__skb_recv_udp</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81826f7d)
Location: include/net/udp.h:254
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81882fff)
Location: include/net/udp.h:254
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int noblock, int *peeked, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81845bb0)
Location: net/ipv4/udp.c:1488
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81845bb0-ffffffff81845e40: __skb_recv_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int noblock, int *peeked, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818c55f0)
Location: net/ipv4/udp.c:1495
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff818c55f0-ffffffff818c5862: __skb_recv_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int noblock, int *peeked, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8191cf70)
Location: net/ipv4/udp.c:1565
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff8191cf70-ffffffff8191d1e9: __skb_recv_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int noblock, int *peeked, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8194b520)
Location: net/ipv4/udp.c:1633
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff8194b520-ffffffff8194b799: __skb_recv_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int noblock, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819afc00)
Location: net/ipv4/udp.c:1620
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff819afc00-ffffffff819afe82: __skb_recv_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int noblock, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819e6890)
Location: net/ipv4/udp.c:1652
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff819e6890-ffffffff819e6b18: __skb_recv_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int noblock, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad4060)
Location: net/ipv4/udp.c:1658
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81ad4060-ffffffff81ad4364: __skb_recv_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int noblock, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ae05a0)
Location: net/ipv4/udp.c:1708
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81ae05a0-ffffffff81ae08d4: __skb_recv_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int noblock, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81acc580)
Location: net/ipv4/udp.c:1727
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_read_sock
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81acc580-ffffffff81acc8aa: __skb_recv_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int noblock, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81b8ae10)
Location: net/ipv4/udp.c:1728
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_read_sock
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81b8ae10-ffffffff81b8b13a: __skb_recv_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81d1ac00)
Location: net/ipv4/udp.c:1728
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_read_sock
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81d1ac00-ffffffff81d1af30: __skb_recv_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ee21a0)
Location: net/ipv4/udp.c:1743
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81ee21a0-ffffffff81ee24d0: __skb_recv_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81f41ca0)
Location: net/ipv4/udp.c:1718
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81f41ca0-ffffffff81f41fd0: __skb_recv_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff82007b30)
Location: net/ipv4/udp.c:1688
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff82007b30-ffffffff82007e60: __skb_recv_udp (STB_GLOBAL)
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
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int noblock, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffff800010c99cc8)
Location: net/ipv4/udp.c:1652
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffff800010c99cc8-ffff800010c99fdc: __skb_recv_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int noblock, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c0daa29c)
Location: net/ipv4/udp.c:1652
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
c0daa29c-c0daa564: __skb_recv_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int noblock, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c000000000dab2f0)
Location: net/ipv4/udp.c:1652
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
c000000000dab2f0-c000000000dab634: __skb_recv_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int noblock, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007f8eae)
Location: net/ipv4/udp.c:1652
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffe0007f8eae-ffffffe0007f90c4: __skb_recv_udp (STB_GLOBAL)
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
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int noblock, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81986700)
Location: net/ipv4/udp.c:1652
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81986700-ffffffff81986988: __skb_recv_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int noblock, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819401c0)
Location: net/ipv4/udp.c:1652
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff819401c0-ffffffff81940448: __skb_recv_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int noblock, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f0ed0)
Location: net/ipv4/udp.c:1652
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff819f0ed0-ffffffff819f1158: __skb_recv_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_udp(struct sock *sk, unsigned int flags, int noblock, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f92d0)
Location: net/ipv4/udp.c:1652
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff819f92d0-ffffffff819f9532: __skb_recv_udp (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int *peeked</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, flags, noblock, peeked, off, err</code> ➡️ <code>sk, flags, noblock, off, err</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int noblock</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, flags, noblock, off, err</code> ➡️ <code>sk, flags, off, err</code>
</li>
</ul>
</details>
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
