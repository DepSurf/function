# Function: <code>__sk_backlog_rcv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81701460)
Location: net/core/sock.c:367
Inline: True
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sk_receive_skb
  - net/ipv4/tcp.c:tcp_prequeue_process
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff81701460-ffffffff817014aa: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81768560)
Location: net/core/sock.c:328
Inline: True
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/ipv4/tcp.c:tcp_prequeue_process
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff81768560-ffffffff817685a9: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817955b0)
Location: net/core/sock.c:328
Inline: True
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/ipv4/tcp.c:tcp_prequeue_process
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff817955b0-ffffffff817955f9: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b32e0)
Location: net/core/sock.c:370
Inline: True
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/ipv4/tcp.c:tcp_prequeue_process
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff817b32e0-ffffffff817b3329: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182b6a0)
Location: net/core/sock.c:360
Inline: True
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
**Symbols:**

```
ffffffff8182b6a0-ffffffff8182b6ef: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81875bd0)
Location: net/core/sock.c:366
Inline: True
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
**Symbols:**

```
ffffffff81875bd0-ffffffff81875c1f: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818963c0)
Location: net/core/sock.c:322
Inline: True
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
**Symbols:**

```
ffffffff818963c0-ffffffff8189640f: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e0700)
Location: net/core/sock.c:317
Inline: True
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
**Symbols:**

```
ffffffff818e0700-ffffffff818e074f: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81912940)
Location: net/core/sock.c:317
Inline: True
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
**Symbols:**

```
ffffffff81912940-ffffffff8191298f: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e4d70)
Location: net/core/sock.c:317
Inline: False
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
**Symbols:**

```
ffffffff819e4d70-ffffffff819e4dc5: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e45f0)
Location: net/core/sock.c:318
Inline: False
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
**Symbols:**

```
ffffffff819e45f0-ffffffff819e4645: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819ca510)
Location: net/core/sock.c:318
Inline: False
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
**Symbols:**

```
ffffffff819ca510-ffffffff819ca55f: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a79ab0)
Location: net/core/sock.c:321
Inline: False
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
**Symbols:**

```
ffffffff81a79ab0-ffffffff81a79aff: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bebdb0)
Location: net/core/sock.c:324
Inline: False
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
**Symbols:**

```
ffffffff81bebdb0-ffffffff81bebe2e: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9ab50)
Location: net/core/sock.c:324
Inline: False
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
**Symbols:**

```
ffffffff81d9ab50-ffffffff81d9abce: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e092d0)
Location: net/core/sock.c:328
Inline: False
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
**Symbols:**

```
ffffffff81e092d0-ffffffff81e0934e: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec5cc0)
Location: net/core/sock.c:325
Inline: False
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
**Symbols:**

```
ffffffff81ec5cc0-ffffffff81ec5d3e: __sk_backlog_rcv (STB_GLOBAL)
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
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010baa1f0)
Location: net/core/sock.c:317
Inline: True
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
**Symbols:**

```
ffff800010baa1f0-ffff800010baa264: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc8d50)
Location: net/core/sock.c:317
Inline: True
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
**Symbols:**

```
c0cc8d50-c0cc8dc0: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c7dd90)
Location: net/core/sock.c:317
Inline: False
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
**Symbols:**

```
c000000000c7dd90-c000000000c7de18: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073da90)
Location: net/core/sock.c:317
Inline: True
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
**Symbols:**

```
ffffffe00073da90-ffffffe00073dafc: __sk_backlog_rcv (STB_GLOBAL)
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
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b2940)
Location: net/core/sock.c:317
Inline: True
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
**Symbols:**

```
ffffffff818b2940-ffffffff818b298f: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186c890)
Location: net/core/sock.c:317
Inline: True
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
**Symbols:**

```
ffffffff8186c890-ffffffff8186c8df: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81903940)
Location: net/core/sock.c:317
Inline: True
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
**Symbols:**

```
ffffffff81903940-ffffffff8190398f: __sk_backlog_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __sk_backlog_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81924940)
Location: net/core/sock.c:317
Inline: True
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
**Symbols:**

```
ffffffff81924940-ffffffff8192498f: __sk_backlog_rcv (STB_GLOBAL)
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
