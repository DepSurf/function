# Function: <code>nh_notifier_info_init</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b0ad1c)
Location: net/ipv4/nexthop.c:111
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:call_nexthop_notifiers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af603b)
Location: net/ipv4/nexthop.c:202
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv4/nexthop.c:call_nexthop_notifiers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int nh_notifier_info_init(struct nh_notifier_info *info, const struct nexthop *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:202
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:call_nexthop_notifiers
```
**Symbols:**

```
ffffffff81bb80f0-ffffffff81bb82e1: nh_notifier_info_init (STB_LOCAL)
ffffffff81d3e3cb-ffffffff81d3e467: nh_notifier_info_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int nh_notifier_info_init(struct nh_notifier_info *info, const struct nexthop *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:203
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:call_nexthop_notifiers
```
**Symbols:**

```
ffffffff81d4bf00-ffffffff81d4c121: nh_notifier_info_init (STB_LOCAL)
ffffffff81f0aca9-ffffffff81f0ad47: nh_notifier_info_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int nh_notifier_info_init(struct nh_notifier_info *info, const struct nexthop *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:203
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:call_nexthop_notifiers
```
**Symbols:**

```
ffffffff81f156c0-ffffffff81f158e1: nh_notifier_info_init (STB_LOCAL)
ffffffff820b2532-ffffffff820b25d0: nh_notifier_info_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int nh_notifier_info_init(struct nh_notifier_info *info, const struct nexthop *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:203
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:call_nexthop_notifiers
```
**Symbols:**

```
ffffffff81f75350-ffffffff81f75571: nh_notifier_info_init (STB_LOCAL)
ffffffff821336ea-ffffffff82133788: nh_notifier_info_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int nh_notifier_info_init(struct nh_notifier_info *info, const struct nexthop *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:203
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:call_nexthop_notifiers
```
**Symbols:**

```
ffffffff8203baf0-ffffffff8203bd44: nh_notifier_info_init (STB_LOCAL)
ffffffff822150f6-ffffffff82215194: nh_notifier_info_init.cold (STB_LOCAL)
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
