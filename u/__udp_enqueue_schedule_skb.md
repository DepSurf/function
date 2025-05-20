# Function: <code>__udp_enqueue_schedule_skb</code>

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
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81824c60)
Location: net/ipv4/udp.c:1240
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
**Symbols:**

```
ffffffff81824c60-ffffffff81824e2b: __udp_enqueue_schedule_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81848110)
Location: net/ipv4/udp.c:1280
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
**Symbols:**

```
ffffffff81848110-ffffffff818482d0: __udp_enqueue_schedule_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818c7b60)
Location: net/ipv4/udp.c:1287
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
**Symbols:**

```
ffffffff818c7b60-ffffffff818c7d2d: __udp_enqueue_schedule_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8191de30)
Location: net/ipv4/udp.c:1357
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
**Symbols:**

```
ffffffff8191de30-ffffffff8191e009: __udp_enqueue_schedule_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8194ca80)
Location: net/ipv4/udp.c:1425
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff8194ca80-ffffffff8194cc59: __udp_enqueue_schedule_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819b1230)
Location: net/ipv4/udp.c:1412
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff819b1230-ffffffff819b1418: __udp_enqueue_schedule_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819e7f10)
Location: net/ipv4/udp.c:1447
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff819e7f10-ffffffff819e8186: __udp_enqueue_schedule_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad5e20)
Location: net/ipv4/udp.c:1453
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
**Symbols:**

```
ffffffff81ad5e20-ffffffff81ad6091: __udp_enqueue_schedule_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ae2400)
Location: net/ipv4/udp.c:1503
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
**Symbols:**

```
ffffffff81ae2400-ffffffff81ae2671: __udp_enqueue_schedule_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81acd320)
Location: net/ipv4/udp.c:1522
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff81acd320-ffffffff81acd591: __udp_enqueue_schedule_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:1523
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff81d3c03c-ffffffff81d3c058: __udp_enqueue_schedule_skb.cold (STB_LOCAL)
ffffffff81b8bce0-ffffffff81b8bf65: __udp_enqueue_schedule_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:1523
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff81f087a6-ffffffff81f087c2: __udp_enqueue_schedule_skb.cold (STB_LOCAL)
ffffffff81d189b0-ffffffff81d18c4c: __udp_enqueue_schedule_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:1534
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff820b029e-ffffffff820b02ba: __udp_enqueue_schedule_skb.cold (STB_LOCAL)
ffffffff81ee1840-ffffffff81ee1ad9: __udp_enqueue_schedule_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:1517
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff82131537-ffffffff82131553: __udp_enqueue_schedule_skb.cold (STB_LOCAL)
ffffffff81f41270-ffffffff81f414f6: __udp_enqueue_schedule_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:1492
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff82212e36-ffffffff82212e52: __udp_enqueue_schedule_skb.cold (STB_LOCAL)
ffffffff82006ec0-ffffffff8200715c: __udp_enqueue_schedule_skb (STB_GLOBAL)
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
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffff800010c9c418)
Location: net/ipv4/udp.c:1447
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffff800010c9c418-ffff800010c9c758: __udp_enqueue_schedule_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c0da7604)
Location: net/ipv4/udp.c:1447
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
c0da7604-c0da7854: __udp_enqueue_schedule_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c000000000dae8b0)
Location: net/ipv4/udp.c:1447
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
c000000000dae8b0-c000000000daed28: __udp_enqueue_schedule_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007fa490)
Location: net/ipv4/udp.c:1447
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffe0007fa490-ffffffe0007fa792: __udp_enqueue_schedule_skb (STB_GLOBAL)
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
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81987d80)
Location: net/ipv4/udp.c:1447
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff81987d80-ffffffff81987ff6: __udp_enqueue_schedule_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81941840)
Location: net/ipv4/udp.c:1447
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff81941840-ffffffff81941ab6: __udp_enqueue_schedule_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f2550)
Location: net/ipv4/udp.c:1447
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff819f2550-ffffffff819f27c6: __udp_enqueue_schedule_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __udp_enqueue_schedule_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819fc3a0)
Location: net/ipv4/udp.c:1447
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff819fc3a0-ffffffff819fc610: __udp_enqueue_schedule_skb (STB_GLOBAL)
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
