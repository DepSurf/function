# Function: <code>replace_nexthop_single</code>

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
In net/ipv4/nexthop.c (ffffffff819d5ea2)
Location: net/ipv4/nexthop.c:866
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
In net/ipv4/nexthop.c (ffffffff81a0ca19)
Location: net/ipv4/nexthop.c:868
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
In net/ipv4/nexthop.c (ffffffff81afd47b)
Location: net/ipv4/nexthop.c:964
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:replace_nexthop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int replace_nexthop_single(struct net *net, struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b0a390)
Location: net/ipv4/nexthop.c:1124
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81b0a390-ffffffff81b0a596: replace_nexthop_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int replace_nexthop_single(struct net *net, struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af69d0)
Location: net/ipv4/nexthop.c:2079
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81af69d0-ffffffff81af6bfb: replace_nexthop_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int replace_nexthop_single(struct net *net, struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2102
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81bb8740-ffffffff81bb897a: replace_nexthop_single (STB_LOCAL)
ffffffff81d3e4c6-ffffffff81d3e4da: replace_nexthop_single.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int replace_nexthop_single(struct net *net, struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2101
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81d4c5f0-ffffffff81d4c84e: replace_nexthop_single (STB_LOCAL)
ffffffff81f0adb5-ffffffff81f0add1: replace_nexthop_single.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int replace_nexthop_single(struct net *net, struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2101
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81f15e10-ffffffff81f1606e: replace_nexthop_single (STB_LOCAL)
ffffffff820b263e-ffffffff820b265a: replace_nexthop_single.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int replace_nexthop_single(struct net *net, struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2101
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81f75ac0-ffffffff81f75d1e: replace_nexthop_single (STB_LOCAL)
ffffffff821337f6-ffffffff82133812: replace_nexthop_single.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int replace_nexthop_single(struct net *net, struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2124
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff8203c290-ffffffff8203c4ee: replace_nexthop_single (STB_LOCAL)
ffffffff82215202-ffffffff8221521e: replace_nexthop_single.cold (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffff800010cc60a8)
Location: net/ipv4/nexthop.c:868
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
In net/ipv4/nexthop.c (c0dd188c)
Location: net/ipv4/nexthop.c:868
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
In net/ipv4/nexthop.c (c000000000de2b30)
Location: net/ipv4/nexthop.c:868
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
In net/ipv4/nexthop.c (ffffffe00081ab48)
Location: net/ipv4/nexthop.c:868
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
In net/ipv4/nexthop.c (ffffffff819ac7b9)
Location: net/ipv4/nexthop.c:868
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
In net/ipv4/nexthop.c (ffffffff81966279)
Location: net/ipv4/nexthop.c:868
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
In net/ipv4/nexthop.c (ffffffff81a17059)
Location: net/ipv4/nexthop.c:868
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
In net/ipv4/nexthop.c (ffffffff81a21a89)
Location: net/ipv4/nexthop.c:868
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
