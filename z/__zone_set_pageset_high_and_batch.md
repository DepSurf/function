# Function: <code>__zone_set_pageset_high_and_batch</code>

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
In mm/page_alloc.c (ffffffff812bfe38)
Location: mm/page_alloc.c:6440
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_pcp_enable
  - mm/page_alloc.c:zone_pcp_disable
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
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
In mm/page_alloc.c (ffffffff812c55c1)
Location: mm/page_alloc.c:6661
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_pcp_enable
  - mm/page_alloc.c:zone_pcp_disable
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81309bdd)
Location: mm/page_alloc.c:6904
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_pcp_enable
  - mm/page_alloc.c:zone_pcp_disable
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8137249a)
Location: mm/page_alloc.c:7025
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_pcp_enable
  - mm/page_alloc.c:zone_pcp_disable
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __zone_set_pageset_high_and_batch(struct zone *zone, long unsigned int high, long unsigned int batch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e5070)
Location: mm/page_alloc.c:7198
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_enable
  - mm/page_alloc.c:zone_pcp_disable
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
**Symbols:**

```
ffffffff813e5070-ffffffff813e5117: __zone_set_pageset_high_and_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __zone_set_pageset_high_and_batch(struct zone *zone, long unsigned int high, long unsigned int batch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81419ac0)
Location: mm/page_alloc.c:5404
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_enable
  - mm/page_alloc.c:zone_pcp_disable
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
**Symbols:**

```
ffffffff81419ac0-ffffffff81419b67: __zone_set_pageset_high_and_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __zone_set_pageset_high_and_batch(struct zone *zone, long unsigned int high_min, long unsigned int high_max, long unsigned int batch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81446820)
Location: mm/page_alloc.c:5497
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_enable
  - mm/page_alloc.c:zone_pcp_disable
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
**Symbols:**

```
ffffffff81446820-ffffffff814468d2: __zone_set_pageset_high_and_batch (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int high_min</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int high_max</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int high</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone, high, batch</code> ➡️ <code>zone, high_min, high_max, batch</code>
</li>
</ul>
</details>
</li>
</ul>
