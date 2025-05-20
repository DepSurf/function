# Function: <code>nexthop_create_group</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819d4ed0)
Location: net/ipv4/nexthop.c:1082
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff819d4ed0-ffffffff819d5139: nexthop_create_group.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff81a0ba30)
Location: net/ipv4/nexthop.c:1084
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81a0ba30-ffffffff81a0bc99: nexthop_create_group.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct nexthop *nexthop_create_group(struct net *net, struct nh_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afcea0)
Location: net/ipv4/nexthop.c:1180
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_add
```
**Symbols:**

```
ffffffff81afcea0-ffffffff81afd157: nexthop_create_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct nexthop *nexthop_create_group(struct net *net, struct nh_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b0ae60)
Location: net/ipv4/nexthop.c:1401
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81b0ae60-ffffffff81b0b138: nexthop_create_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct nexthop *nexthop_create_group(struct net *net, struct nh_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af6200)
Location: net/ipv4/nexthop.c:2385
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81af6200-ffffffff81af661f: nexthop_create_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct nexthop *nexthop_create_group(struct net *net, struct nh_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2408
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81bb7cb0-ffffffff81bb80ed: nexthop_create_group (STB_LOCAL)
ffffffff81d3e38f-ffffffff81d3e3cb: nexthop_create_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct nexthop *nexthop_create_group(struct net *net, struct nh_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2408
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81d4ba60-ffffffff81d4bef4: nexthop_create_group (STB_LOCAL)
ffffffff81f0ac6d-ffffffff81f0aca9: nexthop_create_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct nexthop *nexthop_create_group(struct net *net, struct nh_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2408
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81f15070-ffffffff81f15504: nexthop_create_group (STB_LOCAL)
ffffffff820b2479-ffffffff820b24b5: nexthop_create_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct nexthop *nexthop_create_group(struct net *net, struct nh_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2408
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81f74d30-ffffffff81f75197: nexthop_create_group (STB_LOCAL)
ffffffff82133631-ffffffff8213366d: nexthop_create_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct nexthop *nexthop_create_group(struct net *net, struct nh_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2431
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff8203b670-ffffffff8203bad4: nexthop_create_group (STB_LOCAL)
ffffffff822150ba-ffffffff822150f6: nexthop_create_group.cold (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffff800010cc5920)
Location: net/ipv4/nexthop.c:1084
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct nexthop *nexthop_create_group(struct net *net, struct nh_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c0dd1104)
Location: net/ipv4/nexthop.c:1084
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
c0dd1104-c0dd12d4: nexthop_create_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c000000000de2154)
Location: net/ipv4/nexthop.c:1084
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
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
In net/ipv4/nexthop.c (ffffffe00081a554)
Location: net/ipv4/nexthop.c:1084
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
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
In net/ipv4/nexthop.c (ffffffff819ab7d0)
Location: net/ipv4/nexthop.c:1084
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff819ab7d0-ffffffff819aba39: nexthop_create_group.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff81965290)
Location: net/ipv4/nexthop.c:1084
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81965290-ffffffff819654f9: nexthop_create_group.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff81a16070)
Location: net/ipv4/nexthop.c:1084
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81a16070-ffffffff81a162d9: nexthop_create_group.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff81a20ab0)
Location: net/ipv4/nexthop.c:1084
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81a20ab0-ffffffff81a20d19: nexthop_create_group.isra.0 (STB_LOCAL)
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
