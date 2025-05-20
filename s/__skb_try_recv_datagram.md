# Function: <code>__skb_try_recv_datagram</code>

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
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, unsigned int flags, int *peeked, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81774260)
Location: net/core/datagram.c:199
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81774260-ffffffff817744f9: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *peeked, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817a1570)
Location: net/core/datagram.c:200
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff817a1570-ffffffff817a17ff: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *peeked, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817c06c0)
Location: net/core/datagram.c:245
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff817c06c0-ffffffff817c0828: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *peeked, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8183a0f0)
Location: net/core/datagram.c:246
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff8183a0f0-ffffffff8183a250: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *peeked, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81884830)
Location: net/core/datagram.c:244
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81884830-ffffffff8188498d: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *peeked, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818a4a90)
Location: net/core/datagram.c:244
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff818a4a90-ffffffff818a4bf1: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818f0200)
Location: net/core/datagram.c:244
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff818f0200-ffffffff818f0355: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819221e0)
Location: net/core/datagram.c:244
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff819221e0-ffffffff81922335: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f5c40)
Location: net/core/datagram.c:242
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff819f5c40-ffffffff819f5d84: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f5700)
Location: net/core/datagram.c:242
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff819f5700-ffffffff819f5886: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819db8a0)
Location: net/core/datagram.c:242
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff819db8a0-ffffffff819dba26: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81a8baf0)
Location: net/core/datagram.c:242
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81a8baf0-ffffffff81a8bc76: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81c01330)
Location: net/core/datagram.c:240
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81c01330-ffffffff81c014c9: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81db0680)
Location: net/core/datagram.c:240
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81db0680-ffffffff81db0819: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81e20b40)
Location: net/core/datagram.c:240
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81e20b40-ffffffff81e20cd9: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81edea10)
Location: net/core/datagram.c:241
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81edea10-ffffffff81edeba9: __skb_try_recv_datagram (STB_GLOBAL)
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
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffff800010bbcc98)
Location: net/core/datagram.c:244
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffff800010bbcc98-ffff800010bbce78: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c0cd8e58)
Location: net/core/datagram.c:244
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
c0cd8e58-c0cd8ff8: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c000000000c95d80)
Location: net/core/datagram.c:244
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
c000000000c95d80-c000000000c95fb8: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffe00074b4b0)
Location: net/core/datagram.c:244
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffe00074b4b0-ffffffe00074b5b8: __skb_try_recv_datagram (STB_GLOBAL)
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
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818c21e0)
Location: net/core/datagram.c:244
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff818c21e0-ffffffff818c2335: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8187c120)
Location: net/core/datagram.c:244
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff8187c120-ffffffff8187c275: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819131e0)
Location: net/core/datagram.c:244
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff819131e0-ffffffff81913335: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_datagram(struct sock *sk, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81934360)
Location: net/core/datagram.c:244
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81934360-ffffffff819344b5: __skb_try_recv_datagram (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>sk, flags, peeked, off, err, last</code> ➡️ <code>sk, flags, destructor, peeked, off, err, last</code>
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
<code>sk, flags, destructor, peeked, off, err, last</code> ➡️ <code>sk, flags, destructor, off, err, last</code>
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
<code>struct sk_buff_head *queue</code>
</li>
<li>
<b>Param removed. </b>
<code>void (*destructor)(struct sock *, struct sk_buff *)</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, flags, destructor, off, err, last</code> ➡️ <code>sk, queue, flags, off, err, last</code>
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
