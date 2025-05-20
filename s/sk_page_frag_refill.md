# Function: <code>sk_page_frag_refill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81701ff0)
Location: net/core/sock.c:1964
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_append_datato_frags
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff81701ff0-ffffffff817020b5: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81769290)
Location: net/core/sock.c:2021
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_append_datato_frags
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff81769290-ffffffff81769303: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817961a0)
Location: net/core/sock.c:2019
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_append_datato_frags
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff817961a0-ffffffff81796213: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b4380)
Location: net/core/sock.c:2178
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_append_datato_frags
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff817b4380-ffffffff817b43f3: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182c5d0)
Location: net/core/sock.c:2216
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_append_datato_frags
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff8182c5d0-ffffffff8182c646: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818772d0)
Location: net/core/sock.c:2236
Inline: True
Direct callers:
  - net/core/sock.c:sk_alloc_sg
  - net/core/skbuff.c:skb_append_datato_frags
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff818772d0-ffffffff81877346: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81897050)
Location: net/core/sock.c:2239
Inline: True
Direct callers:
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81897050-ffffffff818970cd: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e12d0)
Location: net/core/sock.c:2382
Inline: True
Direct callers:
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff818e12d0-ffffffff818e134d: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81913490)
Location: net/core/sock.c:2397
Inline: True
Direct callers:
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81913490-ffffffff8191350d: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e4ea0)
Location: net/core/sock.c:2505
Inline: True
Direct callers:
  - net/core/skbuff.c:linear_to_page
  - net/core/skbuff.c:linear_to_page
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff819e4ea0-ffffffff819e4f1c: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e4720)
Location: net/core/sock.c:2497
Inline: True
Direct callers:
  - net/core/skbuff.c:linear_to_page
  - net/core/skbuff.c:linear_to_page
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff819e4720-ffffffff819e479c: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819ca7a0)
Location: net/core/sock.c:2520
Inline: True
Direct callers:
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff819ca7a0-ffffffff819ca818: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a79d70)
Location: net/core/sock.c:2643
Inline: True
Direct callers:
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81a79d70-ffffffff81a79de8: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bed3b0)
Location: net/core/sock.c:2806
Inline: True
Direct callers:
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81bed3b0-ffffffff81bed459: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d99e30)
Location: net/core/sock.c:2885
Inline: True
Direct callers:
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81d99e30-ffffffff81d99ed9: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e085f0)
Location: net/core/sock.c:2946
Inline: True
Direct callers:
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81e085f0-ffffffff81e08699: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec5060)
Location: net/core/sock.c:2927
Inline: True
Direct callers:
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81ec5060-ffffffff81ec5109: sk_page_frag_refill (STB_GLOBAL)
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
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010bac798)
Location: net/core/sock.c:2397
Inline: True
Direct callers:
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffff800010bac798-ffff800010bac824: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc9880)
Location: net/core/sock.c:2397
Inline: True
Direct callers:
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv6/ip6_output.c:__ip6_append_data
```
**Symbols:**

```
c0cc9880-c0cc98f8: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c82880)
Location: net/core/sock.c:2397
Inline: True
Direct callers:
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
c000000000c82880-c000000000c82958: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073e5d0)
Location: net/core/sock.c:2397
Inline: True
Direct callers:
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffe00073e5d0-ffffffe00073e65a: sk_page_frag_refill (STB_GLOBAL)
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
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b3490)
Location: net/core/sock.c:2397
Inline: True
Direct callers:
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff818b3490-ffffffff818b350d: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186d3e0)
Location: net/core/sock.c:2397
Inline: True
Direct callers:
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff8186d3e0-ffffffff8186d45d: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81904490)
Location: net/core/sock.c:2397
Inline: True
Direct callers:
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81904490-ffffffff8190450d: sk_page_frag_refill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool sk_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81925510)
Location: net/core/sock.c:2397
Inline: True
Direct callers:
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81925510-ffffffff8192558d: sk_page_frag_refill (STB_GLOBAL)
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
