# Function: <code>nh_create_ipv4</code>

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
In net/ipv4/nexthop.c (ffffffff819d3d20)
Location: net/ipv4/nexthop.c:1140
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff819d3d20-ffffffff819d3e55: nh_create_ipv4.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff81a0a890)
Location: net/ipv4/nexthop.c:1142
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81a0a890-ffffffff81a0a9c5: nh_create_ipv4.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nh_create_ipv4(struct net *net, struct nexthop *nh, struct nh_info *nhi, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afaa60)
Location: net/ipv4/nexthop.c:1255
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_create
```
**Symbols:**

```
ffffffff81afaa60-ffffffff81afaba0: nh_create_ipv4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nh_create_ipv4(struct net *net, struct nexthop *nh, struct nh_info *nhi, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b08250)
Location: net/ipv4/nexthop.c:1478
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_create
```
**Symbols:**

```
ffffffff81b08250-ffffffff81b0839a: nh_create_ipv4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nh_create_ipv4(struct net *net, struct nexthop *nh, struct nh_info *nhi, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af3fe0)
Location: net/ipv4/nexthop.c:2483
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_create
```
**Symbols:**

```
ffffffff81af3fe0-ffffffff81af412a: nh_create_ipv4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int nh_create_ipv4(struct net *net, struct nexthop *nh, struct nh_info *nhi, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2506
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_create
```
**Symbols:**

```
ffffffff81bb46e0-ffffffff81bb484c: nh_create_ipv4 (STB_LOCAL)
ffffffff81d3dd6e-ffffffff81d3dd9d: nh_create_ipv4.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int nh_create_ipv4(struct net *net, struct nexthop *nh, struct nh_info *nhi, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2506
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_create
```
**Symbols:**

```
ffffffff81d481e0-ffffffff81d4839e: nh_create_ipv4 (STB_LOCAL)
ffffffff81f0a633-ffffffff81f0a662: nh_create_ipv4.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int nh_create_ipv4(struct net *net, struct nexthop *nh, struct nh_info *nhi, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2506
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_create
```
**Symbols:**

```
ffffffff81f11750-ffffffff81f1191d: nh_create_ipv4 (STB_LOCAL)
ffffffff820b1ee8-ffffffff820b1f17: nh_create_ipv4.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int nh_create_ipv4(struct net *net, struct nexthop *nh, struct nh_info *nhi, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2506
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_create
```
**Symbols:**

```
ffffffff81f71440-ffffffff81f7160d: nh_create_ipv4 (STB_LOCAL)
ffffffff821330c8-ffffffff821330f7: nh_create_ipv4.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int nh_create_ipv4(struct net *net, struct nexthop *nh, struct nh_info *nhi, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2529
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_create
```
**Symbols:**

```
ffffffff82037ba0-ffffffff82037d6d: nh_create_ipv4 (STB_LOCAL)
ffffffff82214a77-ffffffff82214aa6: nh_create_ipv4.cold (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffff800010cc3e48)
Location: net/ipv4/nexthop.c:1142
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffff800010cc3e48-ffff800010cc3f88: nh_create_ipv4.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c0dcf6c8)
Location: net/ipv4/nexthop.c:1142
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create
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
In net/ipv4/nexthop.c (c000000000ddfc80)
Location: net/ipv4/nexthop.c:1142
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
c000000000ddfc80-c000000000ddfe08: nh_create_ipv4.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffe000819504)
Location: net/ipv4/nexthop.c:1142
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffe000819504-ffffffe0008195e8: nh_create_ipv4.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff819aa630)
Location: net/ipv4/nexthop.c:1142
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff819aa630-ffffffff819aa765: nh_create_ipv4.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff819640f0)
Location: net/ipv4/nexthop.c:1142
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff819640f0-ffffffff81964225: nh_create_ipv4.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff81a14ed0)
Location: net/ipv4/nexthop.c:1142
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81a14ed0-ffffffff81a15005: nh_create_ipv4.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff81a1f8e0)
Location: net/ipv4/nexthop.c:1142
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81a1f8e0-ffffffff81a1fa2d: nh_create_ipv4.isra.0 (STB_LOCAL)
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
