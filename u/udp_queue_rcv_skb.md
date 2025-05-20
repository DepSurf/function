# Function: <code>udp_queue_rcv_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81789680)
Location: net/ipv4/udp.c:1507
Inline: False
Direct callers:
  - net/ipv4/udp.c:flush_stack
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81789680-ffffffff81789af9: udp_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff817f6d90)
Location: net/ipv4/udp.c:1498
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff817f6d90-ffffffff817f72ba: udp_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81827e40)
Location: net/ipv4/udp.c:1671
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81827e40-ffffffff818281da: udp_queue_rcv_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818486e0)
Location: net/ipv4/udp.c:1829
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff818486e0-ffffffff81848b4b: udp_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818c8100)
Location: net/ipv4/udp.c:1828
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff818c8100-ffffffff818c855e: udp_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8191e010)
Location: net/ipv4/udp.c:1911
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff8191e010-ffffffff8191e47c: udp_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8194d0e0)
Location: net/ipv4/udp.c:2079
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff8194d0e0-ffffffff8194d27b: udp_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819b18b0)
Location: net/ipv4/udp.c:2065
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff819b18b0-ffffffff819b1a2b: udp_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819e8610)
Location: net/ipv4/udp.c:2101
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff819e8610-ffffffff819e87ac: udp_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad6b19)
Location: net/ipv4/udp.c:2110
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
Direct callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
```
**Symbols:**

```
ffffffff81ad65d0-ffffffff81ad6739: udp_queue_rcv_skb.part.0 (STB_LOCAL)
ffffffff81ad6740-ffffffff81ad677a: udp_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ae30f9)
Location: net/ipv4/udp.c:2163
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
Direct callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
```
**Symbols:**

```
ffffffff81ae2bb0-ffffffff81ae2d13: udp_queue_rcv_skb.part.0 (STB_LOCAL)
ffffffff81ae2d20-ffffffff81ae2d5a: udp_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff81acdad0)
Location: net/ipv4/udp.c:2212
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
```
**Symbols:**

```
ffffffff81acdad0-ffffffff81acdc69: udp_queue_rcv_skb.part.0 (STB_LOCAL)
ffffffff81acdc70-ffffffff81acdcbe: udp_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff81b8c4a0)
Location: net/ipv4/udp.c:2224
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
```
**Symbols:**

```
ffffffff81b8c4a0-ffffffff81b8c62e: udp_queue_rcv_skb.part.0 (STB_LOCAL)
ffffffff81b8c630-ffffffff81b8c67e: udp_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff81d1cb10)
Location: net/ipv4/udp.c:2233
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
```
**Symbols:**

```
ffffffff81d1cb10-ffffffff81d1cc98: udp_queue_rcv_skb.part.0 (STB_LOCAL)
ffffffff81d1cca0-ffffffff81d1ccfe: udp_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ee3bf0)
Location: net/ipv4/udp.c:2235
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
```
**Symbols:**

```
ffffffff81ee3bf0-ffffffff81ee3d78: udp_queue_rcv_skb.part.0 (STB_LOCAL)
ffffffff81ee3d90-ffffffff81ee3dee: udp_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff81f43460)
Location: net/ipv4/udp.c:2207
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
```
**Symbols:**

```
ffffffff81f43460-ffffffff81f435e9: udp_queue_rcv_skb.part.0 (STB_LOCAL)
ffffffff81f43600-ffffffff81f4365e: udp_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff820093c0)
Location: net/ipv4/udp.c:2180
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_unicast_rcv_skb
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
```
**Symbols:**

```
ffffffff820093c0-ffffffff82009549: udp_queue_rcv_skb.part.0 (STB_LOCAL)
ffffffff82009560-ffffffff820095c7: udp_queue_rcv_skb (STB_LOCAL)
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
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffff800010c9da98)
Location: net/ipv4/udp.c:2101
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffff800010c9da98-ffff800010c9dc68: udp_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c0dab554)
Location: net/ipv4/udp.c:2101
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_unicast_rcv_skb
```
**Symbols:**

```
c0dab554-c0dab714: udp_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c000000000daf3f0)
Location: net/ipv4/udp.c:2101
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
c000000000daf3f0-c000000000daf61c: udp_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007fabc6)
Location: net/ipv4/udp.c:2101
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffe0007fabc6-ffffffe0007fad50: udp_queue_rcv_skb (STB_LOCAL)
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
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81988480)
Location: net/ipv4/udp.c:2101
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81988480-ffffffff8198861c: udp_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81941f40)
Location: net/ipv4/udp.c:2101
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81941f40-ffffffff819420dc: udp_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f2c50)
Location: net/ipv4/udp.c:2101
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff819f2c50-ffffffff819f2dec: udp_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819fd160)
Location: net/ipv4/udp.c:2101
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff819fd160-ffffffff819fd2fc: udp_queue_rcv_skb (STB_LOCAL)
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
