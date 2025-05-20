# Function: <code>nh_notifier_info_fini</code>

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
In net/ipv4/nexthop.c (ffffffff81b0adaa)
Location: net/ipv4/nexthop.c:123
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
In net/ipv4/nexthop.c (ffffffff81af608b)
Location: net/ipv4/nexthop.c:213
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
void nh_notifier_info_fini(struct nh_notifier_info *info, const struct nexthop *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:213
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:call_nexthop_notifiers
```
**Symbols:**

```
ffffffff81bb4e20-ffffffff81bb4e98: nh_notifier_info_fini (STB_LOCAL)
ffffffff81d3dfa3-ffffffff81d3dfe0: nh_notifier_info_fini.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nh_notifier_info_fini(struct nh_notifier_info *info, const struct nexthop *nh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d4892f)
Location: net/ipv4/nexthop.c:214
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:call_nexthop_notifiers
```
**Symbols:**

```
ffffffff81d488c0-ffffffff81d48948: nh_notifier_info_fini (STB_LOCAL)
ffffffff81f0a87f-ffffffff81f0a8bc: nh_notifier_info_fini.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nh_notifier_info_fini(struct nh_notifier_info *info, const struct nexthop *nh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f11edf)
Location: net/ipv4/nexthop.c:214
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:call_nexthop_notifiers
```
**Symbols:**

```
ffffffff81f11e70-ffffffff81f11ef8: nh_notifier_info_fini (STB_LOCAL)
ffffffff820b2134-ffffffff820b2171: nh_notifier_info_fini.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nh_notifier_info_fini(struct nh_notifier_info *info, const struct nexthop *nh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f71bcf)
Location: net/ipv4/nexthop.c:214
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:call_nexthop_notifiers
```
**Symbols:**

```
ffffffff81f71b60-ffffffff81f71be8: nh_notifier_info_fini (STB_LOCAL)
ffffffff82133314-ffffffff82133351: nh_notifier_info_fini.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nh_notifier_info_fini(struct nh_notifier_info *info, const struct nexthop *nh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff820382df)
Location: net/ipv4/nexthop.c:214
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:call_nexthop_notifiers
```
**Symbols:**

```
ffffffff82038270-ffffffff820382f8: nh_notifier_info_fini (STB_LOCAL)
ffffffff82214d27-ffffffff82214d64: nh_notifier_info_fini.cold (STB_LOCAL)
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
