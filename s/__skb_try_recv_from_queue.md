# Function: <code>__skb_try_recv_from_queue</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *peeked, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817c0510)
Location: net/core/datagram.c:164
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff817c0510-ffffffff817c06b5: __skb_try_recv_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *peeked, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81839f40)
Location: net/core/datagram.c:165
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81839f40-ffffffff8183a0ee: __skb_try_recv_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *peeked, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81884670)
Location: net/core/datagram.c:163
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81884670-ffffffff81884825: __skb_try_recv_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *peeked, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818a48f0)
Location: net/core/datagram.c:163
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff818a48f0-ffffffff818a4a90: __skb_try_recv_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818f0080)
Location: net/core/datagram.c:165
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff818f0080-ffffffff818f01f9: __skb_try_recv_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81922060)
Location: net/core/datagram.c:165
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81922060-ffffffff819221d9: __skb_try_recv_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f5a90)
Location: net/core/datagram.c:167
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff819f5a90-ffffffff819f5c3b: __skb_try_recv_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f5550)
Location: net/core/datagram.c:167
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff819f5550-ffffffff819f56fb: __skb_try_recv_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819db6f0)
Location: net/core/datagram.c:167
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff819db6f0-ffffffff819db89e: __skb_try_recv_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81a8b940)
Location: net/core/datagram.c:167
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81a8b940-ffffffff81a8baee: __skb_try_recv_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81c011a0)
Location: net/core/datagram.c:165
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81c011a0-ffffffff81c01328: __skb_try_recv_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81db04e0)
Location: net/core/datagram.c:165
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81db04e0-ffffffff81db0668: __skb_try_recv_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81e20990)
Location: net/core/datagram.c:165
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81e20990-ffffffff81e20b26: __skb_try_recv_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81ede860)
Location: net/core/datagram.c:166
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81ede860-ffffffff81ede9f6: __skb_try_recv_from_queue (STB_GLOBAL)
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
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffff800010bbcad8)
Location: net/core/datagram.c:165
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffff800010bbcad8-ffff800010bbcc94: __skb_try_recv_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c0cd8cc8)
Location: net/core/datagram.c:165
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
c0cd8cc8-c0cd8e58: __skb_try_recv_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c000000000c95b40)
Location: net/core/datagram.c:165
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
c000000000c95b40-c000000000c95d7c: __skb_try_recv_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffe00074b360)
Location: net/core/datagram.c:165
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffe00074b360-ffffffe00074b4b0: __skb_try_recv_from_queue (STB_GLOBAL)
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
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818c2060)
Location: net/core/datagram.c:165
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff818c2060-ffffffff818c21d9: __skb_try_recv_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8187bfa0)
Location: net/core/datagram.c:165
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff8187bfa0-ffffffff8187c119: __skb_try_recv_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81913060)
Location: net/core/datagram.c:165
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81913060-ffffffff819131d9: __skb_try_recv_from_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *__skb_try_recv_from_queue(struct sock *sk, struct sk_buff_head *queue, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *), int *off, int *err, struct sk_buff **last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819341e0)
Location: net/core/datagram.c:165
Inline: False
Direct callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff819341e0-ffffffff81934359: __skb_try_recv_from_queue (STB_GLOBAL)
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
<code>sk, queue, flags, destructor, peeked, off, err, last</code> ➡️ <code>sk, queue, flags, destructor, off, err, last</code>
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
<b>Param removed. </b>
<code>void (*destructor)(struct sock *, struct sk_buff *)</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, queue, flags, destructor, off, err, last</code> ➡️ <code>sk, queue, flags, off, err, last</code>
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
