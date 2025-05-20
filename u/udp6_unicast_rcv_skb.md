# Function: <code>udp6_unicast_rcv_skb</code>

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
In net/ipv6/udp.c (ffffffff81984de0)
Location: net/ipv6/udp.c:754
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81984de0-ffffffff81984e86: udp6_unicast_rcv_skb.isra.24 (STB_LOCAL)
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
In net/ipv6/udp.c (ffffffff819bb570)
Location: net/ipv6/udp.c:836
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff819bb570-ffffffff819bb60f: udp6_unicast_rcv_skb.isra.31 (STB_LOCAL)
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
In net/ipv6/udp.c (ffffffff81a2a160)
Location: net/ipv6/udp.c:824
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81a2a160-ffffffff81a2a1fe: udp6_unicast_rcv_skb.isra.0 (STB_LOCAL)
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
In net/ipv6/udp.c (ffffffff81a60cb0)
Location: net/ipv6/udp.c:824
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81a60cb0-ffffffff81a60d4e: udp6_unicast_rcv_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int udp6_unicast_rcv_skb(struct sock *sk, struct sk_buff *skb, struct udphdr *uh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b59bc0)
Location: net/ipv6/udp.c:826
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81b59bc0-ffffffff81b59ca5: udp6_unicast_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int udp6_unicast_rcv_skb(struct sock *sk, struct sk_buff *skb, struct udphdr *uh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b68220)
Location: net/ipv6/udp.c:880
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81b68220-ffffffff81b68305: udp6_unicast_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int udp6_unicast_rcv_skb(struct sock *sk, struct sk_buff *skb, struct udphdr *uh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b56570)
Location: net/ipv6/udp.c:893
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81b56570-ffffffff81b5660e: udp6_unicast_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int udp6_unicast_rcv_skb(struct sock *sk, struct sk_buff *skb, struct udphdr *uh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81c1cf40)
Location: net/ipv6/udp.c:895
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81c1cf40-ffffffff81c1cfde: udp6_unicast_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int udp6_unicast_rcv_skb(struct sock *sk, struct sk_buff *skb, struct udphdr *uh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81db9810)
Location: net/ipv6/udp.c:897
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81db9810-ffffffff81db98be: udp6_unicast_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int udp6_unicast_rcv_skb(struct sock *sk, struct sk_buff *skb, struct udphdr *uh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81f89890)
Location: net/ipv6/udp.c:927
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81f89890-ffffffff81f8993e: udp6_unicast_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int udp6_unicast_rcv_skb(struct sock *sk, struct sk_buff *skb, struct udphdr *uh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81fe8960)
Location: net/ipv6/udp.c:943
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81fe8960-ffffffff81fe8a0f: udp6_unicast_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int udp6_unicast_rcv_skb(struct sock *sk, struct sk_buff *skb, struct udphdr *uh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff820b74c0)
Location: net/ipv6/udp.c:913
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff820b74c0-ffffffff820b756f: udp6_unicast_rcv_skb (STB_LOCAL)
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
In net/ipv6/udp.c (ffff800010d26910)
Location: net/ipv6/udp.c:824
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffff800010d26910-ffff800010d269c8: udp6_unicast_rcv_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int udp6_unicast_rcv_skb(struct sock *sk, struct sk_buff *skb, struct udphdr *uh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (c0e29f54)
Location: net/ipv6/udp.c:824
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
c0e29f54-c0e2a018: udp6_unicast_rcv_skb (STB_LOCAL)
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
In net/ipv6/udp.c (c000000000e56650)
Location: net/ipv6/udp.c:824
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
c000000000e56650-c000000000e56730: udp6_unicast_rcv_skb.isra.0 (STB_LOCAL)
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
In net/ipv6/udp.c (ffffffe0008670ac)
Location: net/ipv6/udp.c:824
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffe0008670ac-ffffffe00086714c: udp6_unicast_rcv_skb.isra.0 (STB_LOCAL)
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
In net/ipv6/udp.c (ffffffff81a00340)
Location: net/ipv6/udp.c:824
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81a00340-ffffffff81a003de: udp6_unicast_rcv_skb.isra.0 (STB_LOCAL)
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
In net/ipv6/udp.c (ffffffff819bd100)
Location: net/ipv6/udp.c:824
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff819bd100-ffffffff819bd19e: udp6_unicast_rcv_skb.isra.0 (STB_LOCAL)
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
In net/ipv6/udp.c (ffffffff81a6adc0)
Location: net/ipv6/udp.c:824
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81a6adc0-ffffffff81a6ae5e: udp6_unicast_rcv_skb.isra.0 (STB_LOCAL)
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
In net/ipv6/udp.c (ffffffff81a773d0)
Location: net/ipv6/udp.c:824
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81a773d0-ffffffff81a7746e: udp6_unicast_rcv_skb.isra.0 (STB_LOCAL)
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
