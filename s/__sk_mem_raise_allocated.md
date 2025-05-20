# Function: <code>__sk_mem_raise_allocated</code>

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
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81794ee0)
Location: net/core/sock.c:2122
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff81794ee0-ffffffff817951f8: __sk_mem_raise_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b35c0)
Location: net/core/sock.c:2281
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff817b35c0-ffffffff817b390b: __sk_mem_raise_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182b9a0)
Location: net/core/sock.c:2319
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff8182b9a0-ffffffff8182bd31: __sk_mem_raise_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81875510)
Location: net/core/sock.c:2400
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff81875510-ffffffff8187587c: __sk_mem_raise_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81895de0)
Location: net/core/sock.c:2342
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff81895de0-ffffffff818961b2: __sk_mem_raise_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e02f0)
Location: net/core/sock.c:2485
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff818e02f0-ffffffff818e06be: __sk_mem_raise_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819124b0)
Location: net/core/sock.c:2500
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff819124b0-ffffffff81912888: __sk_mem_raise_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e4330)
Location: net/core/sock.c:2608
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff819e4330-ffffffff819e46d7: __sk_mem_raise_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e3bb0)
Location: net/core/sock.c:2600
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff819e3bb0-ffffffff819e3f42: __sk_mem_raise_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819c9c40)
Location: net/core/sock.c:2623
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff819c9c40-ffffffff819c9fcc: __sk_mem_raise_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a790e0)
Location: net/core/sock.c:2746
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff81a790e0-ffffffff81a7950e: __sk_mem_raise_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bed540)
Location: net/core/sock.c:2909
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
```
**Symbols:**

```
ffffffff81bed540-ffffffff81bed98f: __sk_mem_raise_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9dac0)
Location: net/core/sock.c:2989
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
```
**Symbols:**

```
ffffffff81d9dac0-ffffffff81d9dfba: __sk_mem_raise_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0c340)
Location: net/core/sock.c:3050
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
```
**Symbols:**

```
ffffffff81e0c340-ffffffff81e0c82b: __sk_mem_raise_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec8ce0)
Location: net/core/sock.c:3042
Inline: False
Direct callers:
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
```
**Symbols:**

```
ffffffff81ec8ce0-ffffffff81ec9182: __sk_mem_raise_allocated (STB_GLOBAL)
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
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010bacb50)
Location: net/core/sock.c:2500
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffff800010bacb50-ffff800010bacedc: __sk_mem_raise_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc8684)
Location: net/core/sock.c:2500
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
c0cc8684-c0cc8aa4: __sk_mem_raise_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c7f8c0)
Location: net/core/sock.c:2500
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
c000000000c7f8c0-c000000000c7fdd4: __sk_mem_raise_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073d51a)
Location: net/core/sock.c:2500
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffe00073d51a-ffffffe00073d7bc: __sk_mem_raise_allocated (STB_GLOBAL)
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
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b24b0)
Location: net/core/sock.c:2500
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff818b24b0-ffffffff818b2888: __sk_mem_raise_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186c400)
Location: net/core/sock.c:2500
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff8186c400-ffffffff8186c7d8: __sk_mem_raise_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819034b0)
Location: net/core/sock.c:2500
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff819034b0-ffffffff81903888: __sk_mem_raise_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sk_mem_raise_allocated(struct sock *sk, int size, int amt, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81924490)
Location: net/core/sock.c:2500
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
**Symbols:**

```
ffffffff81924490-ffffffff81924886: __sk_mem_raise_allocated (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
