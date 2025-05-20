# Function: <code>icmpv4_xrlim_allow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (ffffffff8178e020)
Location: net/ipv4/icmp.c:289
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_send
```
**Symbols:**

```
ffffffff8178e020-ffffffff8178e131: icmpv4_xrlim_allow.isra.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (ffffffff817fb610)
Location: net/ipv4/icmp.c:289
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_send
```
**Symbols:**

```
ffffffff817fb610-ffffffff817fb721: icmpv4_xrlim_allow.isra.16 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff8182c4d0)
Location: net/ipv4/icmp.c:289
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_send
```
**Symbols:**

```
ffffffff8182c4d0-ffffffff8182c5e1: icmpv4_xrlim_allow.isra.18 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff8184d7d0)
Location: net/ipv4/icmp.c:314
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_send
```
**Symbols:**

```
ffffffff8184d7d0-ffffffff8184d8bf: icmpv4_xrlim_allow.isra.20 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff818cd500)
Location: net/ipv4/icmp.c:314
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_send
```
**Symbols:**

```
ffffffff818cd500-ffffffff818cd5ef: icmpv4_xrlim_allow.isra.20 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff819238e0)
Location: net/ipv4/icmp.c:314
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_send
```
**Symbols:**

```
ffffffff819238e0-ffffffff819239c3: icmpv4_xrlim_allow.isra.22 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff819526d0)
Location: net/ipv4/icmp.c:314
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff819526d0-ffffffff819527bb: icmpv4_xrlim_allow.isra.23 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff819b6f90)
Location: net/ipv4/icmp.c:309
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff819b6f90-ffffffff819b7078: icmpv4_xrlim_allow.isra.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff819edc90)
Location: net/ipv4/icmp.c:310
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff819edc90-ffffffff819edd78: icmpv4_xrlim_allow.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool icmpv4_xrlim_allow(struct net *net, struct rtable *rt, struct flowi4 *fl4, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81adba90)
Location: net/ipv4/icmp.c:310
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff81adba90-ffffffff81adbb69: icmpv4_xrlim_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool icmpv4_xrlim_allow(struct net *net, struct rtable *rt, struct flowi4 *fl4, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81ae8680)
Location: net/ipv4/icmp.c:313
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff81ae8680-ffffffff81ae876a: icmpv4_xrlim_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool icmpv4_xrlim_allow(struct net *net, struct rtable *rt, struct flowi4 *fl4, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81ad3910)
Location: net/ipv4/icmp.c:313
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
**Symbols:**

```
ffffffff81ad3910-ffffffff81ad3a02: icmpv4_xrlim_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool icmpv4_xrlim_allow(struct net *net, struct rtable *rt, struct flowi4 *fl4, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81b9262b)
Location: net/ipv4/icmp.c:313
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
**Symbols:**

```
ffffffff81b925d0-ffffffff81b926c5: icmpv4_xrlim_allow (STB_LOCAL)
ffffffff81d3c0f0-ffffffff81d3c111: icmpv4_xrlim_allow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool icmpv4_xrlim_allow(struct net *net, struct rtable *rt, struct flowi4 *fl4, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81d2419f)
Location: net/ipv4/icmp.c:306
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
**Symbols:**

```
ffffffff81d24140-ffffffff81d24263: icmpv4_xrlim_allow (STB_LOCAL)
ffffffff81f08909-ffffffff81f0892a: icmpv4_xrlim_allow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool icmpv4_xrlim_allow(struct net *net, struct rtable *rt, struct flowi4 *fl4, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81eeb96f)
Location: net/ipv4/icmp.c:306
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
**Symbols:**

```
ffffffff81eeb910-ffffffff81eeba33: icmpv4_xrlim_allow (STB_LOCAL)
ffffffff820b03a9-ffffffff820b03ca: icmpv4_xrlim_allow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool icmpv4_xrlim_allow(struct net *net, struct rtable *rt, struct flowi4 *fl4, int type, int code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (0)
Location: net/ipv4/icmp.c:307
Inline: False
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
**Symbols:**

```
ffffffff81f4b270-ffffffff81f4b3a6: icmpv4_xrlim_allow (STB_LOCAL)
ffffffff8213164f-ffffffff8213166e: icmpv4_xrlim_allow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool icmpv4_xrlim_allow(struct net *net, struct rtable *rt, struct flowi4 *fl4, int type, int code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (0)
Location: net/ipv4/icmp.c:307
Inline: False
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
**Symbols:**

```
ffffffff82011380-ffffffff820114b6: icmpv4_xrlim_allow (STB_LOCAL)
ffffffff82213004-ffffffff82213023: icmpv4_xrlim_allow.cold (STB_LOCAL)
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
In net/ipv4/icmp.c (ffff800010ca3800)
Location: net/ipv4/icmp.c:310
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffff800010ca3800-ffff800010ca3904: icmpv4_xrlim_allow.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool icmpv4_xrlim_allow(struct net *net, struct rtable *rt, struct flowi4 *fl4, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (c0db04b0)
Location: net/ipv4/icmp.c:310
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
c0db04b0-c0db05a8: icmpv4_xrlim_allow (STB_LOCAL)
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
In net/ipv4/icmp.c (c000000000db7050)
Location: net/ipv4/icmp.c:310
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
c000000000db7050-c000000000db71bc: icmpv4_xrlim_allow.isra.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffe0007ff66a)
Location: net/ipv4/icmp.c:310
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffe0007ff66a-ffffffe0007ff73c: icmpv4_xrlim_allow.isra.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff8198da30)
Location: net/ipv4/icmp.c:310
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff8198da30-ffffffff8198db18: icmpv4_xrlim_allow.isra.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff819474f0)
Location: net/ipv4/icmp.c:310
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff819474f0-ffffffff819475d8: icmpv4_xrlim_allow.isra.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff819f82d0)
Location: net/ipv4/icmp.c:310
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff819f82d0-ffffffff819f83b8: icmpv4_xrlim_allow.isra.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff81a025d0)
Location: net/ipv4/icmp.c:310
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff81a025d0-ffffffff81a026d2: icmpv4_xrlim_allow.isra.0 (STB_LOCAL)
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
