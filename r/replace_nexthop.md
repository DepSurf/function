# Function: <code>replace_nexthop</code>

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
In net/ipv4/nexthop.c (ffffffff819d5bce)
Location: net/ipv4/nexthop.c:932
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
In net/ipv4/nexthop.c (ffffffff81a0c73e)
Location: net/ipv4/nexthop.c:934
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int replace_nexthop(struct net *net, struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afd210)
Location: net/ipv4/nexthop.c:1030
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthop_add
```
**Symbols:**

```
ffffffff81afd210-ffffffff81afd516: replace_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int replace_nexthop(struct net *net, struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b0b1f0)
Location: net/ipv4/nexthop.c:1243
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:insert_nexthop
```
**Symbols:**

```
ffffffff81b0b1f0-ffffffff81b0b4d4: replace_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int replace_nexthop(struct net *net, struct nexthop *old, struct nexthop *new, const struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af8e00)
Location: net/ipv4/nexthop.c:2198
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:insert_nexthop
```
**Symbols:**

```
ffffffff81af8e00-ffffffff81af9074: replace_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int replace_nexthop(struct net *net, struct nexthop *old, struct nexthop *new, const struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2221
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:insert_nexthop
```
**Symbols:**

```
ffffffff81bb9860-ffffffff81bb9bad: replace_nexthop (STB_LOCAL)
ffffffff81d3e7c2-ffffffff81d3e846: replace_nexthop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int replace_nexthop(struct net *net, struct nexthop *old, struct nexthop *new, const struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2220
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:insert_nexthop
```
**Symbols:**

```
ffffffff81d4d840-ffffffff81d4db84: replace_nexthop (STB_LOCAL)
ffffffff81f0b103-ffffffff81f0b187: replace_nexthop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int replace_nexthop(struct net *net, struct nexthop *old, struct nexthop *new, const struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2220
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:insert_nexthop
```
**Symbols:**

```
ffffffff81f17160-ffffffff81f174a4: replace_nexthop (STB_LOCAL)
ffffffff820b2999-ffffffff820b2a1d: replace_nexthop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int replace_nexthop(struct net *net, struct nexthop *old, struct nexthop *new, const struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2220
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:insert_nexthop
```
**Symbols:**

```
ffffffff81f76e40-ffffffff81f77184: replace_nexthop (STB_LOCAL)
ffffffff82133b51-ffffffff82133bd5: replace_nexthop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int replace_nexthop(struct net *net, struct nexthop *old, struct nexthop *new, const struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2243
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:insert_nexthop
```
**Symbols:**

```
ffffffff8203d610-ffffffff8203d954: replace_nexthop (STB_LOCAL)
ffffffff8221555d-ffffffff822155e1: replace_nexthop.cold (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffff800010cc5d64)
Location: net/ipv4/nexthop.c:934
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
In net/ipv4/nexthop.c (c0dd1608)
Location: net/ipv4/nexthop.c:934
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
In net/ipv4/nexthop.c (c000000000de26a8)
Location: net/ipv4/nexthop.c:934
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
In net/ipv4/nexthop.c (ffffffe00081a8b6)
Location: net/ipv4/nexthop.c:934
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
In net/ipv4/nexthop.c (ffffffff819ac4de)
Location: net/ipv4/nexthop.c:934
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
In net/ipv4/nexthop.c (ffffffff81965f9e)
Location: net/ipv4/nexthop.c:934
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
In net/ipv4/nexthop.c (ffffffff81a16d7e)
Location: net/ipv4/nexthop.c:934
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
In net/ipv4/nexthop.c (ffffffff81a217ae)
Location: net/ipv4/nexthop.c:934
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct nh_config *cfg</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, old, new, extack</code> ➡️ <code>net, old, new, cfg, extack</code>
</li>
</ul>
</details>
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
