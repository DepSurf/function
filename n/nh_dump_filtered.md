# Function: <code>nh_dump_filtered</code>

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
In net/ipv4/nexthop.c (ffffffff819d480d)
Location: net/ipv4/nexthop.c:1595
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
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
In net/ipv4/nexthop.c (ffffffff81a0b37d)
Location: net/ipv4/nexthop.c:1597
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
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
In net/ipv4/nexthop.c (ffffffff81afbd88)
Location: net/ipv4/nexthop.c:1733
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b09618)
Location: net/ipv4/nexthop.c:1956
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool nh_dump_filtered(struct nexthop *nh, struct nh_dump_filter *filter, u8 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af3f00)
Location: net/ipv4/nexthop.c:3032
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket_nh
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
**Symbols:**

```
ffffffff81af3f00-ffffffff81af3fd5: nh_dump_filtered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool nh_dump_filtered(struct nexthop *nh, struct nh_dump_filter *filter, u8 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3061
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket_nh
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
**Symbols:**

```
ffffffff81bb45f0-ffffffff81bb46d1: nh_dump_filtered (STB_LOCAL)
ffffffff81d3dd1d-ffffffff81d3dd6e: nh_dump_filtered.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool nh_dump_filtered(struct nexthop *nh, struct nh_dump_filter *filter, u8 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3061
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket_nh
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
**Symbols:**

```
ffffffff81d480b0-ffffffff81d481d4: nh_dump_filtered (STB_LOCAL)
ffffffff81f0a5b5-ffffffff81f0a633: nh_dump_filtered.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool nh_dump_filtered(struct nexthop *nh, struct nh_dump_filter *filter, u8 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3061
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket_nh
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
**Symbols:**

```
ffffffff81f11610-ffffffff81f11734: nh_dump_filtered (STB_LOCAL)
ffffffff820b1e6a-ffffffff820b1ee8: nh_dump_filtered.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool nh_dump_filtered(struct nexthop *nh, struct nh_dump_filter *filter, u8 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3061
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket_nh
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
**Symbols:**

```
ffffffff81f71300-ffffffff81f71429: nh_dump_filtered (STB_LOCAL)
ffffffff82133077-ffffffff821330c8: nh_dump_filtered.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool nh_dump_filtered(struct nexthop *nh, struct nh_dump_filter *filter, u8 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3084
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket_nh
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
**Symbols:**

```
ffffffff82037a60-ffffffff82037b89: nh_dump_filtered (STB_LOCAL)
ffffffff82214a26-ffffffff82214a77: nh_dump_filtered.cold (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffff800010cc48f8)
Location: net/ipv4/nexthop.c:1597
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
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
In net/ipv4/nexthop.c (c0dd0378)
Location: net/ipv4/nexthop.c:1597
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
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
In net/ipv4/nexthop.c (c000000000de09e8)
Location: net/ipv4/nexthop.c:1597
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
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
In net/ipv4/nexthop.c (ffffffe000819d00)
Location: net/ipv4/nexthop.c:1597
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
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
In net/ipv4/nexthop.c (ffffffff819ab11d)
Location: net/ipv4/nexthop.c:1597
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
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
In net/ipv4/nexthop.c (ffffffff81964bdd)
Location: net/ipv4/nexthop.c:1597
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
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
In net/ipv4/nexthop.c (ffffffff81a159bd)
Location: net/ipv4/nexthop.c:1597
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
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
In net/ipv4/nexthop.c (ffffffff81a203fd)
Location: net/ipv4/nexthop.c:1597
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
</details>
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
