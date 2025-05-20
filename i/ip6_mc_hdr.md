# Function: <code>ip6_mc_hdr</code>

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
In net/ipv6/mcast.c (ffffffff817ea0f9)
Location: net/ipv6/mcast.c:1526
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_send
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
In net/ipv6/mcast.c (ffffffff818581d0)
Location: net/ipv6/mcast.c:1526
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
**Symbols:**

```
ffffffff818581d0-ffffffff8185829b: ip6_mc_hdr.constprop.40 (STB_LOCAL)
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
In net/ipv6/mcast.c (ffffffff8188a5d0)
Location: net/ipv6/mcast.c:1540
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
**Symbols:**

```
ffffffff8188a5d0-ffffffff8188a69b: ip6_mc_hdr.constprop.42 (STB_LOCAL)
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
In net/ipv6/mcast.c (ffffffff818b0640)
Location: net/ipv6/mcast.c:1540
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
**Symbols:**

```
ffffffff818b0640-ffffffff818b070f: ip6_mc_hdr.constprop.41 (STB_LOCAL)
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
In net/ipv6/mcast.c (ffffffff819332e0)
Location: net/ipv6/mcast.c:1540
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
**Symbols:**

```
ffffffff819332e0-ffffffff819333af: ip6_mc_hdr.constprop.38 (STB_LOCAL)
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
In net/ipv6/mcast.c (ffffffff8198be90)
Location: net/ipv6/mcast.c:1565
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
**Symbols:**

```
ffffffff8198be90-ffffffff8198bf5b: ip6_mc_hdr.isra.25.constprop.44 (STB_LOCAL)
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
In net/ipv6/mcast.c (ffffffff819c27a0)
Location: net/ipv6/mcast.c:1565
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
**Symbols:**

```
ffffffff819c27a0-ffffffff819c286b: ip6_mc_hdr.isra.28.constprop.42 (STB_LOCAL)
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
In net/ipv6/mcast.c (ffffffff81a31490)
Location: net/ipv6/mcast.c:1564
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
**Symbols:**

```
ffffffff81a31490-ffffffff81a31558: ip6_mc_hdr.isra.0.constprop.0 (STB_LOCAL)
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
In net/ipv6/mcast.c (ffffffff81a67fe0)
Location: net/ipv6/mcast.c:1564
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
**Symbols:**

```
ffffffff81a67fe0-ffffffff81a680a8: ip6_mc_hdr.isra.0.constprop.0 (STB_LOCAL)
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
In net/ipv6/mcast.c (ffffffff81b603b0)
Location: net/ipv6/mcast.c:1561
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
**Symbols:**

```
ffffffff81b603b0-ffffffff81b60478: ip6_mc_hdr.constprop.0 (STB_LOCAL)
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
In net/ipv6/mcast.c (ffffffff81b6eb20)
Location: net/ipv6/mcast.c:1561
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
**Symbols:**

```
ffffffff81b6eb20-ffffffff81b6ebe8: ip6_mc_hdr.constprop.0 (STB_LOCAL)
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
In net/ipv6/mcast.c (ffffffff81b5cf30)
Location: net/ipv6/mcast.c:1705
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
**Symbols:**

```
ffffffff81b5cf30-ffffffff81b5cff8: ip6_mc_hdr.constprop.0 (STB_LOCAL)
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
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:1700
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff81c24980-ffffffff81c24a59: ip6_mc_hdr.constprop.0 (STB_LOCAL)
ffffffff81d40990-ffffffff81d409b2: ip6_mc_hdr.constprop.0.cold (STB_LOCAL)
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
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:1702
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff81dc1c00-ffffffff81dc1ced: ip6_mc_hdr.constprop.0 (STB_LOCAL)
ffffffff81f0d379-ffffffff81f0d39b: ip6_mc_hdr.constprop.0.cold (STB_LOCAL)
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
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:1702
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff81f92550-ffffffff81f9263d: ip6_mc_hdr.constprop.0 (STB_LOCAL)
ffffffff820b47eb-ffffffff820b480d: ip6_mc_hdr.constprop.0.cold (STB_LOCAL)
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
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:1702
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff81ff2ec0-ffffffff81ff2fa7: ip6_mc_hdr.constprop.0 (STB_LOCAL)
ffffffff82135854-ffffffff8213586d: ip6_mc_hdr.constprop.0.cold (STB_LOCAL)
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
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:1702
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
```
**Symbols:**

```
ffffffff820c0b70-ffffffff820c0c53: ip6_mc_hdr.constprop.0 (STB_LOCAL)
ffffffff82217361-ffffffff8221737a: ip6_mc_hdr.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffff800010d2ff58)
Location: net/ipv6/mcast.c:1564
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
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
In net/ipv6/mcast.c (c0e326dc)
Location: net/ipv6/mcast.c:1564
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
**Symbols:**

```
c0e326dc-c0e3278c: ip6_mc_hdr.constprop.0 (STB_LOCAL)
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
In net/ipv6/mcast.c (c000000000e60b20)
Location: net/ipv6/mcast.c:1564
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
**Symbols:**

```
c000000000e60b20-c000000000e60c30: ip6_mc_hdr.isra.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffe00086f6ce)
Location: net/ipv6/mcast.c:1564
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
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
In net/ipv6/mcast.c (ffffffff81a07670)
Location: net/ipv6/mcast.c:1564
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
**Symbols:**

```
ffffffff81a07670-ffffffff81a07738: ip6_mc_hdr.isra.0.constprop.0 (STB_LOCAL)
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
In net/ipv6/mcast.c (ffffffff819c4430)
Location: net/ipv6/mcast.c:1564
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
**Symbols:**

```
ffffffff819c4430-ffffffff819c44f8: ip6_mc_hdr.isra.0.constprop.0 (STB_LOCAL)
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
In net/ipv6/mcast.c (ffffffff81a720f0)
Location: net/ipv6/mcast.c:1564
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
**Symbols:**

```
ffffffff81a720f0-ffffffff81a721b8: ip6_mc_hdr.isra.0.constprop.0 (STB_LOCAL)
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
In net/ipv6/mcast.c (ffffffff81a7e720)
Location: net/ipv6/mcast.c:1564
Inline: True
Direct callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
**Symbols:**

```
ffffffff81a7e720-ffffffff81a7e7e8: ip6_mc_hdr.isra.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
