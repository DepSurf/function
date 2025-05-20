# Function: <code>udp_unicast_rcv_skb</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff8191e480)
Location: net/ipv4/udp.c:2134
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff8191e480-ffffffff8191e509: udp_unicast_rcv_skb.isra.53 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff8194d280)
Location: net/ipv4/udp.c:2236
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff8194d280-ffffffff8194d306: udp_unicast_rcv_skb.isra.63 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff819b1a30)
Location: net/ipv4/udp.c:2222
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff819b1a30-ffffffff819b1ab6: udp_unicast_rcv_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff819e87b0)
Location: net/ipv4/udp.c:2258
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff819e87b0-ffffffff819e8836: udp_unicast_rcv_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int udp_unicast_rcv_skb(struct sock *sk, struct sk_buff *skb, struct udphdr *uh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad6b00)
Location: net/ipv4/udp.c:2266
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81ad6b00-ffffffff81ad6bc6: udp_unicast_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int udp_unicast_rcv_skb(struct sock *sk, struct sk_buff *skb, struct udphdr *uh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ae30e0)
Location: net/ipv4/udp.c:2319
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81ae30e0-ffffffff81ae31a6: udp_unicast_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int udp_unicast_rcv_skb(struct sock *sk, struct sk_buff *skb, struct udphdr *uh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ace030)
Location: net/ipv4/udp.c:2370
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81ace030-ffffffff81ace0b9: udp_unicast_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int udp_unicast_rcv_skb(struct sock *sk, struct sk_buff *skb, struct udphdr *uh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81b8c9f0)
Location: net/ipv4/udp.c:2382
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81b8c9f0-ffffffff81b8ca79: udp_unicast_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int udp_unicast_rcv_skb(struct sock *sk, struct sk_buff *skb, struct udphdr *uh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81d1d0b0)
Location: net/ipv4/udp.c:2391
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81d1d0b0-ffffffff81d1d145: udp_unicast_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int udp_unicast_rcv_skb(struct sock *sk, struct sk_buff *skb, struct udphdr *uh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ee41c0)
Location: net/ipv4/udp.c:2393
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81ee41c0-ffffffff81ee4255: udp_unicast_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int udp_unicast_rcv_skb(struct sock *sk, struct sk_buff *skb, struct udphdr *uh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81f43a30)
Location: net/ipv4/udp.c:2365
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81f43a30-ffffffff81f43ac6: udp_unicast_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int udp_unicast_rcv_skb(struct sock *sk, struct sk_buff *skb, struct udphdr *uh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff820099a0)
Location: net/ipv4/udp.c:2338
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff820099a0-ffffffff82009a36: udp_unicast_rcv_skb (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffff800010c9dc68)
Location: net/ipv4/udp.c:2258
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffff800010c9dc68-ffff800010c9dd1c: udp_unicast_rcv_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int udp_unicast_rcv_skb(struct sock *sk, struct sk_buff *skb, struct udphdr *uh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c0dab714)
Location: net/ipv4/udp.c:2258
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
c0dab714-c0dab7b8: udp_unicast_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (c000000000daf620)
Location: net/ipv4/udp.c:2258
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
c000000000daf620-c000000000daf6f4: udp_unicast_rcv_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007fad50)
Location: net/ipv4/udp.c:2258
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffe0007fad50-ffffffe0007fadf4: udp_unicast_rcv_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff81988620)
Location: net/ipv4/udp.c:2258
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81988620-ffffffff819886a6: udp_unicast_rcv_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff819420e0)
Location: net/ipv4/udp.c:2258
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff819420e0-ffffffff81942166: udp_unicast_rcv_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f2df0)
Location: net/ipv4/udp.c:2258
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff819f2df0-ffffffff819f2e76: udp_unicast_rcv_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff819fd300)
Location: net/ipv4/udp.c:2258
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff819fd300-ffffffff819fd386: udp_unicast_rcv_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
