# Function: <code>fib6_check_nh_list</code>

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
In net/ipv4/nexthop.c (ffffffff819d3ab0)
Location: net/ipv4/nexthop.c:597
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff819d3ab0-ffffffff819d3b2a: fib6_check_nh_list.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff81a0a620)
Location: net/ipv4/nexthop.c:599
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81a0a620-ffffffff81a0a69a: fib6_check_nh_list.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fib6_check_nh_list(struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afc780)
Location: net/ipv4/nexthop.c:673
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81afc780-ffffffff81afc821: fib6_check_nh_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fib6_check_nh_list(struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b09e50)
Location: net/ipv4/nexthop.c:801
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81b09e50-ffffffff81b09ef1: fib6_check_nh_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib6_check_nh_list(struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af47e0)
Location: net/ipv4/nexthop.c:1310
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81af47e0-ffffffff81af4857: fib6_check_nh_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fib6_check_nh_list(struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb5000)
Location: net/ipv4/nexthop.c:1310
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81bb5000-ffffffff81bb5077: fib6_check_nh_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fib6_check_nh_list(struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d48ad0)
Location: net/ipv4/nexthop.c:1311
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81d48ad0-ffffffff81d48b74: fib6_check_nh_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fib6_check_nh_list(struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f120a0)
Location: net/ipv4/nexthop.c:1311
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81f120a0-ffffffff81f12144: fib6_check_nh_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fib6_check_nh_list(struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f71d90)
Location: net/ipv4/nexthop.c:1311
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81f71d90-ffffffff81f71e34: fib6_check_nh_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fib6_check_nh_list(struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff820384a0)
Location: net/ipv4/nexthop.c:1334
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff820384a0-ffffffff82038544: fib6_check_nh_list (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffff800010cc3bb0)
Location: net/ipv4/nexthop.c:599
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffff800010cc3bb0-ffff800010cc3c9c: fib6_check_nh_list.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fib6_check_nh_list(struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c0dcf928)
Location: net/ipv4/nexthop.c:599
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
c0dcf928-c0dcf9fc: fib6_check_nh_list (STB_LOCAL)
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
In net/ipv4/nexthop.c (c000000000ddf960)
Location: net/ipv4/nexthop.c:599
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
c000000000ddf960-c000000000ddfa28: fib6_check_nh_list.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffe000818d8e)
Location: net/ipv4/nexthop.c:599
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffe000818d8e-ffffffe000818e56: fib6_check_nh_list.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff819aa3c0)
Location: net/ipv4/nexthop.c:599
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff819aa3c0-ffffffff819aa43a: fib6_check_nh_list.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff81963e80)
Location: net/ipv4/nexthop.c:599
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81963e80-ffffffff81963efa: fib6_check_nh_list.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff81a14c60)
Location: net/ipv4/nexthop.c:599
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81a14c60-ffffffff81a14cda: fib6_check_nh_list.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff81a1f670)
Location: net/ipv4/nexthop.c:599
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81a1f670-ffffffff81a1f6ea: fib6_check_nh_list.isra.0 (STB_LOCAL)
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
