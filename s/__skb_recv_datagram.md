# Function: <code>__skb_recv_datagram</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, unsigned int flags, int *peeked, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8170c9d0)
Location: net/core/datagram.c:194
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_do_read
  - net/core/datagram.c:skb_recv_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff8170c9d0-ffffffff8170cf8d: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, unsigned int flags, int *peeked, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81774500)
Location: net/core/datagram.c:264
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81774500-ffffffff817745b1: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *peeked, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817a1800)
Location: net/core/datagram.c:270
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff817a1800-ffffffff817a18bf: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *peeked, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817c0830)
Location: net/core/datagram.c:293
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
```
**Symbols:**

```
ffffffff817c0830-ffffffff817c08ee: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *peeked, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8183a250)
Location: net/core/datagram.c:294
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
```
**Symbols:**

```
ffffffff8183a250-ffffffff8183a30e: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *peeked, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81884990)
Location: net/core/datagram.c:292
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
```
**Symbols:**

```
ffffffff81884990-ffffffff81884a4e: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *peeked, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818a4c00)
Location: net/core/datagram.c:292
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
```
**Symbols:**

```
ffffffff818a4c00-ffffffff818a4cbe: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818f0360)
Location: net/core/datagram.c:291
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
```
**Symbols:**

```
ffffffff818f0360-ffffffff818f0412: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81922340)
Location: net/core/datagram.c:291
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
```
**Symbols:**

```
ffffffff81922340-ffffffff819223f2: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, struct sk_buff_head *sk_queue, unsigned int flags, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f5d90)
Location: net/core/datagram.c:287
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
  - net/xfrm/espintcp.c:espintcp_recvmsg
```
**Symbols:**

```
ffffffff819f5d90-ffffffff819f5e45: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, struct sk_buff_head *sk_queue, unsigned int flags, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f5890)
Location: net/core/datagram.c:287
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
  - net/xfrm/espintcp.c:espintcp_recvmsg
```
**Symbols:**

```
ffffffff819f5890-ffffffff819f5945: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, struct sk_buff_head *sk_queue, unsigned int flags, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819dba30)
Location: net/core/datagram.c:287
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
  - net/xfrm/espintcp.c:espintcp_recvmsg
```
**Symbols:**

```
ffffffff819dba30-ffffffff819dbae5: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, struct sk_buff_head *sk_queue, unsigned int flags, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81a8bc80)
Location: net/core/datagram.c:287
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
  - net/xfrm/espintcp.c:espintcp_recvmsg
```
**Symbols:**

```
ffffffff81a8bc80-ffffffff81a8bd35: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, struct sk_buff_head *sk_queue, unsigned int flags, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81c014d0)
Location: net/core/datagram.c:285
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
  - net/xfrm/espintcp.c:espintcp_recvmsg
```
**Symbols:**

```
ffffffff81c014d0-ffffffff81c0159e: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, struct sk_buff_head *sk_queue, unsigned int flags, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81db0830)
Location: net/core/datagram.c:285
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
  - net/xfrm/espintcp.c:espintcp_recvmsg
```
**Symbols:**

```
ffffffff81db0830-ffffffff81db08fe: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, struct sk_buff_head *sk_queue, unsigned int flags, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81e20cf0)
Location: net/core/datagram.c:285
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
  - net/xfrm/espintcp.c:espintcp_recvmsg
```
**Symbols:**

```
ffffffff81e20cf0-ffffffff81e20dbe: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, struct sk_buff_head *sk_queue, unsigned int flags, int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81edebc0)
Location: net/core/datagram.c:286
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
  - net/xfrm/espintcp.c:espintcp_recvmsg
```
**Symbols:**

```
ffffffff81edebc0-ffffffff81edec8e: __skb_recv_datagram (STB_GLOBAL)
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
struct sk_buff *__skb_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffff800010bbce78)
Location: net/core/datagram.c:291
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
```
**Symbols:**

```
ffff800010bbce78-ffff800010bbcf54: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c0cd8ff8)
Location: net/core/datagram.c:291
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
```
**Symbols:**

```
c0cd8ff8-c0cd90d0: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c000000000c95fc0)
Location: net/core/datagram.c:291
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
```
**Symbols:**

```
c000000000c95fc0-c000000000c960d0: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffe00074b5b8)
Location: net/core/datagram.c:291
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
```
**Symbols:**

```
ffffffe00074b5b8-ffffffe00074b64c: __skb_recv_datagram (STB_GLOBAL)
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
struct sk_buff *__skb_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818c2340)
Location: net/core/datagram.c:291
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
```
**Symbols:**

```
ffffffff818c2340-ffffffff818c23f2: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8187c280)
Location: net/core/datagram.c:291
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
```
**Symbols:**

```
ffffffff8187c280-ffffffff8187c332: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81913340)
Location: net/core/datagram.c:291
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
```
**Symbols:**

```
ffffffff81913340-ffffffff819133f2: __skb_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *__skb_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819344c0)
Location: net/core/datagram.c:291
Inline: False
Direct callers:
  - net/core/datagram.c:skb_recv_datagram
```
**Symbols:**

```
ffffffff819344c0-ffffffff81934572: __skb_recv_datagram (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void (*destructor)(struct sock *, struct sk_buff *)</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, flags, peeked, off, err</code> ➡️ <code>sk, flags, destructor, peeked, off, err</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int *peeked</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, flags, destructor, peeked, off, err</code> ➡️ <code>sk, flags, destructor, off, err</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sk_buff_head *sk_queue</code>
</li>
<li>
<b>Param removed. </b>
<code>void (*destructor)(struct sock *, struct sk_buff *)</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, flags, destructor, off, err</code> ➡️ <code>sk, sk_queue, flags, off, err</code>
</li>
</ul>
</details>
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
