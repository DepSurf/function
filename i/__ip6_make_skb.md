# Function: <code>__ip6_make_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff817c7d20)
Location: net/ipv6/ip6_output.c:1621
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff817c7d20-ffffffff817c825b: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81834e60)
Location: net/ipv6/ip6_output.c:1625
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81834e60-ffffffff81835365: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81866990)
Location: net/ipv6/ip6_output.c:1652
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81866990-ffffffff81866e9b: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff8188b0b0)
Location: net/ipv6/ip6_output.c:1655
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
```
**Symbols:**

```
ffffffff8188b0b0-ffffffff8188b650: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff8190c2d0)
Location: net/ipv6/ip6_output.c:1604
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
```
**Symbols:**

```
ffffffff8190c2d0-ffffffff8190c8e3: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81963750)
Location: net/ipv6/ip6_output.c:1616
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81963750-ffffffff81963d07: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81998710)
Location: net/ipv6/ip6_output.c:1645
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81998710-ffffffff81998ca2: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1709
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81a04dc5-ffffffff81a04dd9: __ip6_make_skb.cold (STB_LOCAL)
ffffffff81a04560-ffffffff81a04b00: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a3b150)
Location: net/ipv6/ip6_output.c:1713
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81a3b150-ffffffff81a3b6f8: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b30710)
Location: net/ipv6/ip6_output.c:1783
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81b30710-ffffffff81b30cc4: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b3f340)
Location: net/ipv6/ip6_output.c:1822
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81b3f340-ffffffff81b3f8f1: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2d1d0)
Location: net/ipv6/ip6_output.c:1854
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81b2d1d0-ffffffff81b2d78f: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1836
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81d3f576-ffffffff81d3f635: __ip6_make_skb.cold (STB_LOCAL)
ffffffff81bf3380-ffffffff81bf39ab: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1868
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81f0bf30-ffffffff81f0bfdd: __ip6_make_skb.cold (STB_LOCAL)
ffffffff81d8bf90-ffffffff81d8c578: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1906
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff820b3765-ffffffff820b3812: __ip6_make_skb.cold (STB_LOCAL)
ffffffff81f59f50-ffffffff81f5a538: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1925
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff8213488d-ffffffff8213491f: __ip6_make_skb.cold (STB_LOCAL)
ffffffff81fb9c00-ffffffff81fba292: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1872
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff822163d8-ffffffff82216405: __ip6_make_skb.cold (STB_LOCAL)
ffffffff82087110-ffffffff820876ed: __ip6_make_skb (STB_GLOBAL)
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
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffff800010cfc298)
Location: net/ipv6/ip6_output.c:1713
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffff800010cfc298-ffff800010cfc860: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c0e03690)
Location: net/ipv6/ip6_output.c:1713
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
c0e03690-c0e03cdc: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c000000000e23d40)
Location: net/ipv6/ip6_output.c:1713
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
c000000000e23d40-c000000000e244a8: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffe000846ba0)
Location: net/ipv6/ip6_output.c:1713
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffe000846ba0-ffffffe00084709c: __ip6_make_skb (STB_GLOBAL)
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
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819da7e0)
Location: net/ipv6/ip6_output.c:1713
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff819da7e0-ffffffff819dad88: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819975a0)
Location: net/ipv6/ip6_output.c:1713
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff819975a0-ffffffff81997b48: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a45260)
Location: net/ipv6/ip6_output.c:1713
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81a45260-ffffffff81a45808: __ip6_make_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *__ip6_make_skb(struct sock *sk, struct sk_buff_head *queue, struct inet_cork_full *cork, struct inet6_cork *v6_cork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a50f30)
Location: net/ipv6/ip6_output.c:1713
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_push_pending_frames
  - net/ipv6/udp.c:udp_v6_push_pending_frames
```
**Symbols:**

```
ffffffff81a50f30-ffffffff81a514d8: __ip6_make_skb (STB_GLOBAL)
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
