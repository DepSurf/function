# Function: <code>__sk_queue_drop_skb</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817a1320)
Location: net/core/datagram.c:334
Inline: False
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff817a1320-ffffffff817a13da: __sk_queue_drop_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817bf430)
Location: net/core/datagram.c:355
Inline: False
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff817bf430-ffffffff817bf4d8: __sk_queue_drop_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81838db0)
Location: net/core/datagram.c:356
Inline: False
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81838db0-ffffffff81838e66: __sk_queue_drop_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818834f0)
Location: net/core/datagram.c:354
Inline: False
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff818834f0-ffffffff818835ac: __sk_queue_drop_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818a3f40)
Location: net/core/datagram.c:354
Inline: False
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff818a3f40-ffffffff818a3ffc: __sk_queue_drop_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818ef230)
Location: net/core/datagram.c:353
Inline: False
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff818ef230-ffffffff818ef2f3: __sk_queue_drop_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819211e0)
Location: net/core/datagram.c:353
Inline: False
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff819211e0-ffffffff819212a3: __sk_queue_drop_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f4b20)
Location: net/core/datagram.c:350
Inline: False
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff819f4b20-ffffffff819f4c08: __sk_queue_drop_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f4810)
Location: net/core/datagram.c:350
Inline: False
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff819f4810-ffffffff819f48f8: __sk_queue_drop_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819da8e0)
Location: net/core/datagram.c:350
Inline: False
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff819da8e0-ffffffff819da9c8: __sk_queue_drop_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81a8af60)
Location: net/core/datagram.c:350
Inline: False
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81a8af60-ffffffff81a8b048: __sk_queue_drop_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81c006e0)
Location: net/core/datagram.c:347
Inline: False
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81c006e0-ffffffff81c007c0: __sk_queue_drop_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81db0419)
Location: net/core/datagram.c:345
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81dafa00-ffffffff81dafae0: __sk_queue_drop_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81e208c9)
Location: net/core/datagram.c:345
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81e1fc70-ffffffff81e1fd50: __sk_queue_drop_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81ede799)
Location: net/core/datagram.c:346
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
Direct callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81edd320-ffffffff81edd400: __sk_queue_drop_skb (STB_GLOBAL)
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
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffff800010bbc878)
Location: net/core/datagram.c:353
Inline: False
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffff800010bbc878-ffff800010bbc9cc: __sk_queue_drop_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c0cd7dac)
Location: net/core/datagram.c:353
Inline: False
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
c0cd7dac-c0cd7e6c: __sk_queue_drop_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c000000000c94470)
Location: net/core/datagram.c:353
Inline: False
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
c000000000c94470-c000000000c945c4: __sk_queue_drop_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffe00074a608)
Location: net/core/datagram.c:353
Inline: False
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffe00074a608-ffffffe00074a6ae: __sk_queue_drop_skb (STB_GLOBAL)
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
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818c11e0)
Location: net/core/datagram.c:353
Inline: False
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff818c11e0-ffffffff818c12a3: __sk_queue_drop_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8187b120)
Location: net/core/datagram.c:353
Inline: False
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff8187b120-ffffffff8187b1e3: __sk_queue_drop_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819121e0)
Location: net/core/datagram.c:353
Inline: False
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff819121e0-ffffffff819122a3: __sk_queue_drop_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sk_queue_drop_skb(struct sock *sk, struct sk_buff_head *sk_queue, struct sk_buff *skb, unsigned int flags, void (*destructor)(struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81933380)
Location: net/core/datagram.c:353
Inline: False
Direct callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
**Symbols:**

```
ffffffff81933380-ffffffff81933443: __sk_queue_drop_skb (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sk_buff_head *sk_queue</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, skb, flags, destructor</code> ➡️ <code>sk, sk_queue, skb, flags, destructor</code>
</li>
</ul>
</details>
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
