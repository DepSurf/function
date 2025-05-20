# Function: <code>replace_nexthop_single_notify</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int replace_nexthop_single_notify(struct net *net, struct nexthop *group_nh, struct nexthop *old, struct nh_info *oldi, struct nh_info *newi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af6880)
Location: net/ipv4/nexthop.c:2056
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:replace_nexthop_single
```
**Symbols:**

```
ffffffff81af6880-ffffffff81af69cf: replace_nexthop_single_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int replace_nexthop_single_notify(struct net *net, struct nexthop *group_nh, struct nexthop *old, struct nh_info *oldi, struct nh_info *newi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2079
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:replace_nexthop_single
```
**Symbols:**

```
ffffffff81bb85c0-ffffffff81bb873c: replace_nexthop_single_notify (STB_LOCAL)
ffffffff81d3e47c-ffffffff81d3e4c6: replace_nexthop_single_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int replace_nexthop_single_notify(struct net *net, struct nexthop *group_nh, struct nexthop *old, struct nh_info *oldi, struct nh_info *newi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2078
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:replace_nexthop_single
```
**Symbols:**

```
ffffffff81d4c440-ffffffff81d4c5eb: replace_nexthop_single_notify (STB_LOCAL)
ffffffff81f0ad5c-ffffffff81f0adb5: replace_nexthop_single_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int replace_nexthop_single_notify(struct net *net, struct nexthop *group_nh, struct nexthop *old, struct nh_info *oldi, struct nh_info *newi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2078
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:replace_nexthop_single
```
**Symbols:**

```
ffffffff81f15c50-ffffffff81f15dfb: replace_nexthop_single_notify (STB_LOCAL)
ffffffff820b25e5-ffffffff820b263e: replace_nexthop_single_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int replace_nexthop_single_notify(struct net *net, struct nexthop *group_nh, struct nexthop *old, struct nh_info *oldi, struct nh_info *newi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2078
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:replace_nexthop_single
```
**Symbols:**

```
ffffffff81f758e0-ffffffff81f75aa5: replace_nexthop_single_notify (STB_LOCAL)
ffffffff8213379d-ffffffff821337f6: replace_nexthop_single_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int replace_nexthop_single_notify(struct net *net, struct nexthop *group_nh, struct nexthop *old, struct nh_info *oldi, struct nh_info *newi, struct netlink_ext_ack *extack);
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
  - net/ipv4/nexthop.c:replace_nexthop_single
  - net/ipv4/nexthop.c:replace_nexthop_single
```
**Symbols:**

```
ffffffff8203c0b0-ffffffff8203c275: replace_nexthop_single_notify (STB_LOCAL)
ffffffff822151a9-ffffffff82215202: replace_nexthop_single_notify.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
