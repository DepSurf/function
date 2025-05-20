# Function: <code>insert_nexthop</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819d5949)
Location: net/ipv4/nexthop.c:991
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a0c4b9)
Location: net/ipv4/nexthop.c:993
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afd599)
Location: net/ipv4/nexthop.c:1089
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int insert_nexthop(struct net *net, struct nexthop *new_nh, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b0b4e0)
Location: net/ipv4/nexthop.c:1302
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81b0b4e0-ffffffff81b0b69c: insert_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int insert_nexthop(struct net *net, struct nexthop *new_nh, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af9080)
Location: net/ipv4/nexthop.c:2258
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81af9080-ffffffff81af92c6: insert_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int insert_nexthop(struct net *net, struct nexthop *new_nh, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2281
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81bb9bb0-ffffffff81bb9e18: insert_nexthop (STB_LOCAL)
ffffffff81d3e846-ffffffff81d3e8df: insert_nexthop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int insert_nexthop(struct net *net, struct nexthop *new_nh, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2280
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81d4db90-ffffffff81d4ddf9: insert_nexthop (STB_LOCAL)
ffffffff81f0b187-ffffffff81f0b208: insert_nexthop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int insert_nexthop(struct net *net, struct nexthop *new_nh, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2280
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81f174c0-ffffffff81f17729: insert_nexthop (STB_LOCAL)
ffffffff820b2a1d-ffffffff820b2a9e: insert_nexthop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int insert_nexthop(struct net *net, struct nexthop *new_nh, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2280
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81f771a0-ffffffff81f77409: insert_nexthop (STB_LOCAL)
ffffffff82133bd5-ffffffff82133c56: insert_nexthop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int insert_nexthop(struct net *net, struct nexthop *new_nh, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2303
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff8203d970-ffffffff8203dbd9: insert_nexthop (STB_LOCAL)
ffffffff822155e1-ffffffff82215662: insert_nexthop.cold (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffff800010cc5af0)
Location: net/ipv4/nexthop.c:993
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
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
In net/ipv4/nexthop.c (c0dd14c0)
Location: net/ipv4/nexthop.c:993
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
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
In net/ipv4/nexthop.c (c000000000de2594)
Location: net/ipv4/nexthop.c:993
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
In net/ipv4/nexthop.c (ffffffe00081a6da)
Location: net/ipv4/nexthop.c:993
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819ac259)
Location: net/ipv4/nexthop.c:993
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81965d19)
Location: net/ipv4/nexthop.c:993
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a16af9)
Location: net/ipv4/nexthop.c:993
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a21529)
Location: net/ipv4/nexthop.c:993
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
