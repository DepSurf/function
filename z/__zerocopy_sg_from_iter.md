# Function: <code>__zerocopy_sg_from_iter</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __zerocopy_sg_from_iter(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81839290)
Location: net/core/datagram.c:583
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/datagram.c:zerocopy_sg_from_iter
```
**Symbols:**

```
ffffffff81839290-ffffffff818394b0: __zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __zerocopy_sg_from_iter(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818839c0)
Location: net/core/datagram.c:581
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/datagram.c:zerocopy_sg_from_iter
```
**Symbols:**

```
ffffffff818839c0-ffffffff81883bdf: __zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __zerocopy_sg_from_iter(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818a4360)
Location: net/core/datagram.c:616
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_dgram
  - net/core/datagram.c:zerocopy_sg_from_iter
```
**Symbols:**

```
ffffffff818a4360-ffffffff818a4576: __zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __zerocopy_sg_from_iter(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818ef9b0)
Location: net/core/datagram.c:615
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_dgram
  - net/core/datagram.c:zerocopy_sg_from_iter
```
**Symbols:**

```
ffffffff818ef9b0-ffffffff818efbb7: __zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __zerocopy_sg_from_iter(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819219d0)
Location: net/core/datagram.c:615
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_dgram
  - net/core/datagram.c:zerocopy_sg_from_iter
```
**Symbols:**

```
ffffffff819219d0-ffffffff81921bdf: __zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __zerocopy_sg_from_iter(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f52b0)
Location: net/core/datagram.c:619
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_dgram
  - net/core/datagram.c:zerocopy_sg_from_iter
```
**Symbols:**

```
ffffffff819f52b0-ffffffff819f5511: __zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __zerocopy_sg_from_iter(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f4ce0)
Location: net/core/datagram.c:619
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_dgram
  - net/core/datagram.c:zerocopy_sg_from_iter
```
**Symbols:**

```
ffffffff819f4ce0-ffffffff819f4fe0: __zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __zerocopy_sg_from_iter(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819dae70)
Location: net/core/datagram.c:619
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_dgram
  - net/core/datagram.c:zerocopy_sg_from_iter
```
**Symbols:**

```
ffffffff819dae70-ffffffff819db169: __zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __zerocopy_sg_from_iter(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81a8b4f0)
Location: net/core/datagram.c:619
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_dgram
  - net/core/datagram.c:zerocopy_sg_from_iter
```
**Symbols:**

```
ffffffff81a8b4f0-ffffffff81a8b8ed: __zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __zerocopy_sg_from_iter(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81c00ae0)
Location: net/core/datagram.c:616
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/ipv4/ip_output.c:__ip_append_data
```
**Symbols:**

```
ffffffff81c00ae0-ffffffff81c00fe1: __zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __zerocopy_sg_from_iter(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, struct iov_iter *from, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81dafef0)
Location: net/core/datagram.c:613
Inline: False
Direct callers:
  - io_uring/net.c:io_sg_from_iter
  - io_uring/net.c:io_sg_from_iter_iovec
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/ipv4/ip_output.c:__ip_append_data
```
**Symbols:**

```
ffffffff81dafef0-ffffffff81db037e: __zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __zerocopy_sg_from_iter(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, struct iov_iter *from, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/datagram.c (0)
Location: net/core/datagram.c:613
Inline: False
Direct callers:
  - io_uring/net.c:io_sg_from_iter
  - io_uring/net.c:io_sg_from_iter_iovec
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/ipv4/ip_output.c:__ip_append_data
```
**Symbols:**

```
ffffffff8212c3bb-ffffffff8212c41f: __zerocopy_sg_from_iter.cold (STB_LOCAL)
ffffffff81e20150-ffffffff81e20822: __zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __zerocopy_sg_from_iter(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, struct iov_iter *from, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/datagram.c (0)
Location: net/core/datagram.c:632
Inline: False
Direct callers:
  - io_uring/net.c:io_sg_from_iter
  - io_uring/net.c:io_sg_from_iter_iovec
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/ipv4/ip_output.c:__ip_append_data
```
**Symbols:**

```
ffffffff8220e0da-ffffffff8220e13e: __zerocopy_sg_from_iter.cold (STB_LOCAL)
ffffffff81ede030-ffffffff81ede6ff: __zerocopy_sg_from_iter (STB_GLOBAL)
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
int __zerocopy_sg_from_iter(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffff800010bbc050)
Location: net/core/datagram.c:615
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_dgram
  - net/core/datagram.c:zerocopy_sg_from_iter
```
**Symbols:**

```
ffff800010bbc050-ffff800010bbc23c: __zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __zerocopy_sg_from_iter(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c0cd84d0)
Location: net/core/datagram.c:615
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_dgram
  - net/core/datagram.c:zerocopy_sg_from_iter
```
**Symbols:**

```
c0cd84d0-c0cd86b4: __zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __zerocopy_sg_from_iter(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c000000000c951e0)
Location: net/core/datagram.c:615
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_dgram
  - net/core/datagram.c:zerocopy_sg_from_iter
```
**Symbols:**

```
c000000000c951e0-c000000000c954c4: __zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __zerocopy_sg_from_iter(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffe00074ae08)
Location: net/core/datagram.c:615
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_dgram
  - net/core/datagram.c:zerocopy_sg_from_iter
```
**Symbols:**

```
ffffffe00074ae08-ffffffe00074afba: __zerocopy_sg_from_iter (STB_GLOBAL)
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
int __zerocopy_sg_from_iter(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818c19d0)
Location: net/core/datagram.c:615
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_dgram
  - net/core/datagram.c:zerocopy_sg_from_iter
```
**Symbols:**

```
ffffffff818c19d0-ffffffff818c1bdf: __zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __zerocopy_sg_from_iter(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8187b910)
Location: net/core/datagram.c:615
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_dgram
  - net/core/datagram.c:zerocopy_sg_from_iter
```
**Symbols:**

```
ffffffff8187b910-ffffffff8187bb1f: __zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __zerocopy_sg_from_iter(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819129d0)
Location: net/core/datagram.c:615
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_dgram
  - net/core/datagram.c:zerocopy_sg_from_iter
```
**Symbols:**

```
ffffffff819129d0-ffffffff81912bdf: __zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __zerocopy_sg_from_iter(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81933b50)
Location: net/core/datagram.c:615
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_dgram
  - net/core/datagram.c:zerocopy_sg_from_iter
```
**Symbols:**

```
ffffffff81933b50-ffffffff81933d5f: __zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct msghdr *msg</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, skb, from, length</code> ➡️ <code>msg, sk, skb, from, length</code>
</li>
</ul>
</details>
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
