# Function: <code>__skb_wait_for_more_packets</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817740f0)
Location: net/core/datagram.c:86
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff817740f0-ffffffff8177425b: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817a1400)
Location: net/core/datagram.c:86
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff817a1400-ffffffff817a1566: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817bf500)
Location: net/core/datagram.c:86
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff817bf500-ffffffff817bf662: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81838e90)
Location: net/core/datagram.c:87
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81838e90-ffffffff81838ff2: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818835b0)
Location: net/core/datagram.c:85
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff818835b0-ffffffff81883718: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818a4000)
Location: net/core/datagram.c:85
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff818a4000-ffffffff818a4168: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818ef320)
Location: net/core/datagram.c:87
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff818ef320-ffffffff818ef481: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819212d0)
Location: net/core/datagram.c:87
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff819212d0-ffffffff81921434: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, struct sk_buff_head *queue, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f4f60)
Location: net/core/datagram.c:88
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff819f4f60-ffffffff819f50cc: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, struct sk_buff_head *queue, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f4980)
Location: net/core/datagram.c:88
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff819f4980-ffffffff819f4aff: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, struct sk_buff_head *queue, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819dab10)
Location: net/core/datagram.c:88
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff819dab10-ffffffff819dac8f: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, struct sk_buff_head *queue, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81a8b190)
Location: net/core/datagram.c:88
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81a8b190-ffffffff81a8b30f: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, struct sk_buff_head *queue, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81c00940)
Location: net/core/datagram.c:86
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81c00940-ffffffff81c00ad3: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, struct sk_buff_head *queue, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81dafc10)
Location: net/core/datagram.c:86
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81dafc10-ffffffff81dafda3: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, struct sk_buff_head *queue, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81e1fe80)
Location: net/core/datagram.c:86
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81e1fe80-ffffffff81e20013: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, struct sk_buff_head *queue, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81eddd60)
Location: net/core/datagram.c:87
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81eddd60-ffffffff81eddef3: __skb_wait_for_more_packets (STB_GLOBAL)
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
int __skb_wait_for_more_packets(struct sock *sk, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffff800010bbc698)
Location: net/core/datagram.c:87
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffff800010bbc698-ffff800010bbc814: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c0cd8a60)
Location: net/core/datagram.c:87
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
c0cd8a60-c0cd8bf4: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c000000000c95770)
Location: net/core/datagram.c:87
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
c000000000c95770-c000000000c95958: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffe00074a828)
Location: net/core/datagram.c:87
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffe00074a828-ffffffe00074a942: __skb_wait_for_more_packets (STB_GLOBAL)
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
int __skb_wait_for_more_packets(struct sock *sk, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818c12d0)
Location: net/core/datagram.c:87
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff818c12d0-ffffffff818c1434: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8187b210)
Location: net/core/datagram.c:87
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff8187b210-ffffffff8187b374: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819122d0)
Location: net/core/datagram.c:87
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff819122d0-ffffffff81912434: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock *sk, int *err, long int *timeo_p, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81933470)
Location: net/core/datagram.c:87
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81933470-ffffffff819335d4: __skb_wait_for_more_packets (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sk_buff_head *queue</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, err, timeo_p, skb</code> ➡️ <code>sk, queue, err, timeo_p, skb</code>
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
