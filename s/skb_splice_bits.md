# Function: <code>skb_splice_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags, ssize_t (*splice_cb)(struct sock *, struct pipe_inode_info *, struct splice_pipe_desc *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81708790)
Location: net/core/skbuff.c:1973
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffff81708790-ffffffff817088c5: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags, ssize_t (*splice_cb)(struct sock *, struct pipe_inode_info *, struct splice_pipe_desc *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176fe80)
Location: net/core/skbuff.c:1990
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffff8176fe80-ffffffff8176ff58: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179d000)
Location: net/core/skbuff.c:1969
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffff8179d000-ffffffff8179d0c7: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b9b80)
Location: net/core/skbuff.c:1984
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffff817b9b80-ffffffff817b9c62: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81832500)
Location: net/core/skbuff.c:2239
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffff81832500-ffffffff818325e2: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187c8d0)
Location: net/core/skbuff.c:2255
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffff8187c8d0-ffffffff8187c98c: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189d690)
Location: net/core/skbuff.c:2264
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffff8189d690-ffffffff8189d74c: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e7ef0)
Location: net/core/skbuff.c:2423
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffff818e7ef0-ffffffff818e7fad: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191a370)
Location: net/core/skbuff.c:2425
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffff8191a370-ffffffff8191a42d: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ebe90)
Location: net/core/skbuff.c:2424
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffff819ebe90-ffffffff819ebf56: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ebd30)
Location: net/core/skbuff.c:2441
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffff819ebd30-ffffffff819ebdf6: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d2340)
Location: net/core/skbuff.c:2483
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffff819d2340-ffffffff819d23f9: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a81fc0)
Location: net/core/skbuff.c:2555
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffff81a81fc0-ffffffff81a82079: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf6cc0)
Location: net/core/skbuff.c:2604
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffff81bf6cc0-ffffffff81bf6da6: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da54f0)
Location: net/core/skbuff.c:2810
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffff81da54f0-ffffffff81da55d6: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e14540)
Location: net/core/skbuff.c:2974
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffff81e14540-ffffffff81e14626: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed1900)
Location: net/core/skbuff.c:3062
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffff81ed1900-ffffffff81ed19e6: skb_splice_bits (STB_GLOBAL)
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
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb3528)
Location: net/core/skbuff.c:2425
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffff800010bb3528-ffff800010bb35ec: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd1a28)
Location: net/core/skbuff.c:2425
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
c0cd1a28-c0cd1af0: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8afb0)
Location: net/core/skbuff.c:2425
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
c000000000c8afb0-c000000000c8b0a0: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000744b16)
Location: net/core/skbuff.c:2425
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffe000744b16-ffffffe000744bbe: skb_splice_bits (STB_GLOBAL)
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
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818ba370)
Location: net/core/skbuff.c:2425
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffff818ba370-ffffffff818ba42d: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818742c0)
Location: net/core/skbuff.c:2425
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffff818742c0-ffffffff8187437d: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190b370)
Location: net/core/skbuff.c:2425
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffff8190b370-ffffffff8190b42d: skb_splice_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff *skb, struct sock *sk, unsigned int offset, struct pipe_inode_info *pipe, unsigned int tlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192c470)
Location: net/core/skbuff.c:2425
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_data_recv
  - net/unix/af_unix.c:unix_stream_splice_actor
```
**Symbols:**

```
ffffffff8192c470-ffffffff8192c52d: skb_splice_bits (STB_GLOBAL)
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
<b>Param removed. </b>
<code>ssize_t (*splice_cb)(struct sock *, struct pipe_inode_info *, struct splice_pipe_desc *)</code>
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
