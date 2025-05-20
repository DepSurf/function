# Function: <code>__ipv4_sk_update_pmtu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81757093)
Location: net/ipv4/route.c:1025
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817c3364)
Location: net/ipv4/route.c:1031
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff817f15b0)
Location: net/ipv4/route.c:1037
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffff817f15b0-ffffffff817f166c: __ipv4_sk_update_pmtu.isra.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81812e70)
Location: net/ipv4/route.c:1055
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffff81812e70-ffffffff81812f20: __ipv4_sk_update_pmtu.isra.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff818924b0)
Location: net/ipv4/route.c:1062
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffff818924b0-ffffffff81892560: __ipv4_sk_update_pmtu.isra.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff818e6480)
Location: net/ipv4/route.c:1062
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffff818e6480-ffffffff818e6530: __ipv4_sk_update_pmtu.isra.51 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81913705)
Location: net/ipv4/route.c:1064
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
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
In net/ipv4/route.c (ffffffff81975910)
Location: net/ipv4/route.c:1073
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffff81975910-ffffffff819759c0: __ipv4_sk_update_pmtu.isra.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff819ac320)
Location: net/ipv4/route.c:1075
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffff819ac320-ffffffff819ac3d0: __ipv4_sk_update_pmtu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __ipv4_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a96130)
Location: net/ipv4/route.c:1079
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffff81a96130-ffffffff81a96282: __ipv4_sk_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __ipv4_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81aa01d0)
Location: net/ipv4/route.c:1085
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffff81aa01d0-ffffffff81aa0322: __ipv4_sk_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __ipv4_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a8b110)
Location: net/ipv4/route.c:1069
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffff81a8b110-ffffffff81a8b262: __ipv4_sk_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __ipv4_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b46050)
Location: net/ipv4/route.c:1084
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffff81b46050-ffffffff81b461a2: __ipv4_sk_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __ipv4_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81cd2e30)
Location: net/ipv4/route.c:1091
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffff81cd2e30-ffffffff81cd2faf: __ipv4_sk_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ipv4_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e93130)
Location: net/ipv4/route.c:1091
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffff81e93130-ffffffff81e9320f: __ipv4_sk_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ipv4_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81ef18d0)
Location: net/ipv4/route.c:1091
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffff81ef18d0-ffffffff81ef19af: __ipv4_sk_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ipv4_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81fb5a20)
Location: net/ipv4/route.c:1091
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffff81fb5a20-ffffffff81fb5aff: __ipv4_sk_update_pmtu (STB_LOCAL)
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
In net/ipv4/route.c (ffff800010c5c3d8)
Location: net/ipv4/route.c:1075
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffff800010c5c3d8-ffff800010c5c4b8: __ipv4_sk_update_pmtu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __ipv4_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d6bb00)
Location: net/ipv4/route.c:1075
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
c0d6bb00-c0d6bbd0: __ipv4_sk_update_pmtu (STB_LOCAL)
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
In net/ipv4/route.c (c000000000d5e7e0)
Location: net/ipv4/route.c:1075
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
c000000000d5e7e0-c000000000d5e8e0: __ipv4_sk_update_pmtu.isra.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffe0007c53f6)
Location: net/ipv4/route.c:1075
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffe0007c53f6-ffffffe0007c548e: __ipv4_sk_update_pmtu.isra.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff8194c190)
Location: net/ipv4/route.c:1075
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffff8194c190-ffffffff8194c240: __ipv4_sk_update_pmtu.isra.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff81905c80)
Location: net/ipv4/route.c:1075
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffff81905c80-ffffffff81905d30: __ipv4_sk_update_pmtu.isra.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff819b6960)
Location: net/ipv4/route.c:1075
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffff819b6960-ffffffff819b6a10: __ipv4_sk_update_pmtu.isra.0 (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff819c01d0)
Location: net/ipv4/route.c:1075
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffff819c01d0-ffffffff819c0280: __ipv4_sk_update_pmtu.isra.0 (STB_LOCAL)
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
