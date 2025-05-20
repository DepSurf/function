# Function: <code>nh_create_ipv6</code>

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
In net/ipv4/nexthop.c (ffffffff819d3e60)
Location: net/ipv4/nexthop.c:1175
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff819d3e60-ffffffff819d3f7b: nh_create_ipv6.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff81a0a9d0)
Location: net/ipv4/nexthop.c:1177
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81a0a9d0-ffffffff81a0aaeb: nh_create_ipv6.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nh_create_ipv6(struct net *net, struct nexthop *nh, struct nh_info *nhi, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afaba0)
Location: net/ipv4/nexthop.c:1293
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_create
```
**Symbols:**

```
ffffffff81afaba0-ffffffff81afacc7: nh_create_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nh_create_ipv6(struct net *net, struct nexthop *nh, struct nh_info *nhi, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b09290)
Location: net/ipv4/nexthop.c:1516
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_create
```
**Symbols:**

```
ffffffff81b09290-ffffffff81b093c6: nh_create_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nh_create_ipv6(struct net *net, struct nexthop *nh, struct nh_info *nhi, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af46a0)
Location: net/ipv4/nexthop.c:2521
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_create
```
**Symbols:**

```
ffffffff81af46a0-ffffffff81af47d6: nh_create_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nh_create_ipv6(struct net *net, struct nexthop *nh, struct nh_info *nhi, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb4ea0)
Location: net/ipv4/nexthop.c:2545
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_create
```
**Symbols:**

```
ffffffff81bb4ea0-ffffffff81bb4fff: nh_create_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nh_create_ipv6(struct net *net, struct nexthop *nh, struct nh_info *nhi, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d48950)
Location: net/ipv4/nexthop.c:2545
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_create
```
**Symbols:**

```
ffffffff81d48950-ffffffff81d48ac4: nh_create_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nh_create_ipv6(struct net *net, struct nexthop *nh, struct nh_info *nhi, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f11f10)
Location: net/ipv4/nexthop.c:2545
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_create
```
**Symbols:**

```
ffffffff81f11f10-ffffffff81f12084: nh_create_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nh_create_ipv6(struct net *net, struct nexthop *nh, struct nh_info *nhi, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f71c00)
Location: net/ipv4/nexthop.c:2545
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_create
```
**Symbols:**

```
ffffffff81f71c00-ffffffff81f71d74: nh_create_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nh_create_ipv6(struct net *net, struct nexthop *nh, struct nh_info *nhi, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff82038310)
Location: net/ipv4/nexthop.c:2568
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_create
```
**Symbols:**

```
ffffffff82038310-ffffffff82038484: nh_create_ipv6 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffff800010cc3f88)
Location: net/ipv4/nexthop.c:1177
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffff800010cc3f88-ffff800010cc40c4: nh_create_ipv6.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nh_create_ipv6(struct net *net, struct nexthop *nh, struct nh_info *nhi, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c0dcf458)
Location: net/ipv4/nexthop.c:1177
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_create
```
**Symbols:**

```
c0dcf458-c0dcf584: nh_create_ipv6 (STB_LOCAL)
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
In net/ipv4/nexthop.c (c000000000ddfe10)
Location: net/ipv4/nexthop.c:1177
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
c000000000ddfe10-c000000000ddff84: nh_create_ipv6.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffe0008195e8)
Location: net/ipv4/nexthop.c:1177
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffe0008195e8-ffffffe0008196d4: nh_create_ipv6.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff819aa770)
Location: net/ipv4/nexthop.c:1177
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff819aa770-ffffffff819aa88b: nh_create_ipv6.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff81964230)
Location: net/ipv4/nexthop.c:1177
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81964230-ffffffff8196434b: nh_create_ipv6.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff81a15010)
Location: net/ipv4/nexthop.c:1177
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81a15010-ffffffff81a1512b: nh_create_ipv6.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff81a1fa30)
Location: net/ipv4/nexthop.c:1177
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81a1fa30-ffffffff81a1fb61: nh_create_ipv6.isra.0 (STB_LOCAL)
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
