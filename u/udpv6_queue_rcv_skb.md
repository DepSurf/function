# Function: <code>udpv6_queue_rcv_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff817e4010)
Location: net/ipv6/udp.c:627
Inline: False
Direct callers:
  - net/ipv6/udp.c:flush_stack
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff817e4010-ffffffff817e4450: udpv6_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81852350)
Location: net/ipv6/udp.c:556
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81852350-ffffffff81852854: udpv6_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff818841f0)
Location: net/ipv6/udp.c:558
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff818841f0-ffffffff81884560: udpv6_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff818aa380)
Location: net/ipv6/udp.c:583
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff818aa380-ffffffff818aa727: udpv6_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff8192ce90)
Location: net/ipv6/udp.c:586
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff8192ce90-ffffffff8192d239: udpv6_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81984a10)
Location: net/ipv6/udp.c:554
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81984a10-ffffffff81984dd2: udpv6_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff819bb3d0)
Location: net/ipv6/udp.c:695
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff819bb3d0-ffffffff819bb56e: udpv6_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a29fe0)
Location: net/ipv6/udp.c:683
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81a29fe0-ffffffff81a2a15e: udpv6_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a60b00)
Location: net/ipv6/udp.c:683
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81a60b00-ffffffff81a60ca3: udpv6_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b59be3)
Location: net/ipv6/udp.c:686
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
Direct callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
```
**Symbols:**

```
ffffffff81b59a10-ffffffff81b59b7c: udpv6_queue_rcv_skb.part.0 (STB_LOCAL)
ffffffff81b59b80-ffffffff81b59bba: udpv6_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b68243)
Location: net/ipv6/udp.c:740
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
Direct callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
```
**Symbols:**

```
ffffffff81b68070-ffffffff81b681dc: udpv6_queue_rcv_skb.part.0 (STB_LOCAL)
ffffffff81b681e0-ffffffff81b6821a: udpv6_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b56380)
Location: net/ipv6/udp.c:752
Inline: True
Direct callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
```
**Symbols:**

```
ffffffff81b56380-ffffffff81b5651e: udpv6_queue_rcv_skb.part.0 (STB_LOCAL)
ffffffff81b56520-ffffffff81b5656e: udpv6_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffff81c1c9f0)
Location: net/ipv6/udp.c:754
Inline: True
Direct callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
```
**Symbols:**

```
ffffffff81c1c9f0-ffffffff81c1cb83: udpv6_queue_rcv_skb.part.0 (STB_LOCAL)
ffffffff81c1cb90-ffffffff81c1cbde: udpv6_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffff81db92c0)
Location: net/ipv6/udp.c:756
Inline: True
Direct callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
```
**Symbols:**

```
ffffffff81db92c0-ffffffff81db9450: udpv6_queue_rcv_skb.part.0 (STB_LOCAL)
ffffffff81db9450-ffffffff81db94ae: udpv6_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffff81f89310)
Location: net/ipv6/udp.c:786
Inline: True
Direct callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
```
**Symbols:**

```
ffffffff81f89310-ffffffff81f894a0: udpv6_queue_rcv_skb.part.0 (STB_LOCAL)
ffffffff81f894b0-ffffffff81f8950e: udpv6_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffff81fe8740)
Location: net/ipv6/udp.c:802
Inline: True
Direct callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
```
**Symbols:**

```
ffffffff81fe8740-ffffffff81fe88d1: udpv6_queue_rcv_skb.part.0 (STB_LOCAL)
ffffffff81fe88f0-ffffffff81fe894e: udpv6_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffff820b7290)
Location: net/ipv6/udp.c:772
Inline: True
Direct callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
```
**Symbols:**

```
ffffffff820b7290-ffffffff820b7421: udpv6_queue_rcv_skb.part.0 (STB_LOCAL)
ffffffff820b7440-ffffffff820b74a7: udpv6_queue_rcv_skb (STB_LOCAL)
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
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffff800010d26738)
Location: net/ipv6/udp.c:683
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffff800010d26738-ffff800010d2690c: udpv6_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (c0e29d94)
Location: net/ipv6/udp.c:683
Inline: True
Direct callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
```
**Symbols:**

```
c0e29d94-c0e29f54: udpv6_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (c000000000e56420)
Location: net/ipv6/udp.c:683
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
c000000000e56420-c000000000e5664c: udpv6_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffe000866f22)
Location: net/ipv6/udp.c:683
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
```
**Symbols:**

```
ffffffe000866f22-ffffffe0008670ac: udpv6_queue_rcv_skb (STB_LOCAL)
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
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a00190)
Location: net/ipv6/udp.c:683
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81a00190-ffffffff81a00333: udpv6_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff819bcf50)
Location: net/ipv6/udp.c:683
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff819bcf50-ffffffff819bd0f3: udpv6_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a6ac10)
Location: net/ipv6/udp.c:683
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81a6ac10-ffffffff81a6adb3: udpv6_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int udpv6_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a77220)
Location: net/ipv6/udp.c:683
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81a77220-ffffffff81a773c3: udpv6_queue_rcv_skb (STB_LOCAL)
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
