# Function: <code>icmp_route_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rtable *icmp_route_lookup(struct net *net, struct flowi4 *fl4, struct sk_buff *skb_in, const struct iphdr *iph, __be32 saddr, u8 tos, u32 mark, int type, int code, struct icmp_bxm *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff8178e140)
Location: net/ipv4/icmp.c:459
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_send
```
**Symbols:**

```
ffffffff8178e140-ffffffff8178e4ac: icmp_route_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rtable *icmp_route_lookup(struct net *net, struct flowi4 *fl4, struct sk_buff *skb_in, const struct iphdr *iph, __be32 saddr, u8 tos, u32 mark, int type, int code, struct icmp_bxm *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff817fb730)
Location: net/ipv4/icmp.c:459
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_send
```
**Symbols:**

```
ffffffff817fb730-ffffffff817fba97: icmp_route_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rtable *icmp_route_lookup(struct net *net, struct flowi4 *fl4, struct sk_buff *skb_in, const struct iphdr *iph, __be32 saddr, u8 tos, u32 mark, int type, int code, struct icmp_bxm *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff8182c5f0)
Location: net/ipv4/icmp.c:460
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_send
```
**Symbols:**

```
ffffffff8182c5f0-ffffffff8182c9e3: icmp_route_lookup (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff8184da70)
Location: net/ipv4/icmp.c:467
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_send
```
**Symbols:**

```
ffffffff8184da70-ffffffff8184de09: icmp_route_lookup.constprop.25 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff818cd780)
Location: net/ipv4/icmp.c:467
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_send
```
**Symbols:**

```
ffffffff818cd780-ffffffff818cdb2e: icmp_route_lookup.constprop.25 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff81923b60)
Location: net/ipv4/icmp.c:467
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_send
```
**Symbols:**

```
ffffffff81923b60-ffffffff81923ee3: icmp_route_lookup.constprop.27 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff81952950)
Location: net/ipv4/icmp.c:464
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff81952950-ffffffff81952cbf: icmp_route_lookup.constprop.28 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff819b71b0)
Location: net/ipv4/icmp.c:459
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff819b71b0-ffffffff819b7529: icmp_route_lookup.constprop.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff819edeb0)
Location: net/ipv4/icmp.c:460
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff819edeb0-ffffffff819ee229: icmp_route_lookup.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81adbc90)
Location: net/ipv4/icmp.c:460
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff81adbc90-ffffffff81adbfe8: icmp_route_lookup.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81ae8770)
Location: net/ipv4/icmp.c:480
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff81ae8770-ffffffff81ae8b44: icmp_route_lookup.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81ad3a10)
Location: net/ipv4/icmp.c:480
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff81ad3a10-ffffffff81ad3dff: icmp_route_lookup.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81b926d0)
Location: net/ipv4/icmp.c:480
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff81b926d0-ffffffff81b92ae8: icmp_route_lookup.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81d23d10)
Location: net/ipv4/icmp.c:473
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff81d23d10-ffffffff81d2413c: icmp_route_lookup.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81eeb3a0)
Location: net/ipv4/icmp.c:473
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff81eeb3a0-ffffffff81eeb7cc: icmp_route_lookup.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81f4acc0)
Location: net/ipv4/icmp.c:476
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff81f4acc0-ffffffff81f4b0f9: icmp_route_lookup.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (ffffffff82010dd0)
Location: net/ipv4/icmp.c:476
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff82010dd0-ffffffff82011203: icmp_route_lookup.constprop.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffff800010ca3a50)
Location: net/ipv4/icmp.c:460
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffff800010ca3a50-ffff800010ca3dc0: icmp_route_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (c0db06e0)
Location: net/ipv4/icmp.c:460
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
c0db06e0-c0db0a38: icmp_route_lookup.constprop.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (c000000000db7370)
Location: net/ipv4/icmp.c:460
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
c000000000db7370-c000000000db77e4: icmp_route_lookup.isra.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffe0007ff968)
Location: net/ipv4/icmp.c:460
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffe0007ff968-ffffffe0007ffc14: icmp_route_lookup.isra.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff8198dc50)
Location: net/ipv4/icmp.c:460
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff8198dc50-ffffffff8198dfc9: icmp_route_lookup.constprop.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff81947710)
Location: net/ipv4/icmp.c:460
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff81947710-ffffffff81947a89: icmp_route_lookup.constprop.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff819f84f0)
Location: net/ipv4/icmp.c:460
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff819f84f0-ffffffff819f8869: icmp_route_lookup.constprop.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff81a02810)
Location: net/ipv4/icmp.c:460
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff81a02810-ffffffff81a02bd7: icmp_route_lookup.constprop.0 (STB_LOCAL)
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
</ul>
