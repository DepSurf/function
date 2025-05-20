# Function: <code>zone_set_pageset_high_and_batch</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
void zone_set_pageset_high_and_batch(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b9630)
Location: mm/page_alloc.c:6456
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_update
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_zone_pageset
```
**Symbols:**

```
ffffffff812b9630-ffffffff812b96f3: zone_set_pageset_high_and_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void zone_set_pageset_high_and_batch(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bea00)
Location: mm/page_alloc.c:6677
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_update
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_zone_pageset
```
**Symbols:**

```
ffffffff812bea00-ffffffff812beacb: zone_set_pageset_high_and_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void zone_set_pageset_high_and_batch(struct zone *zone, int cpu_online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:6920
Inline: False
Direct callers:
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:page_alloc_cpu_online
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:setup_zone_pageset
```
**Symbols:**

```
ffffffff81301670-ffffffff813017f0: zone_set_pageset_high_and_batch (STB_LOCAL)
ffffffff81cbd1ac-ffffffff81cbd1ca: zone_set_pageset_high_and_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void zone_set_pageset_high_and_batch(struct zone *zone, int cpu_online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:7041
Inline: False
Direct callers:
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:page_alloc_cpu_online
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:setup_zone_pageset
```
**Symbols:**

```
ffffffff81368f80-ffffffff8136910a: zone_set_pageset_high_and_batch (STB_LOCAL)
ffffffff81e6efe6-ffffffff81e6f004: zone_set_pageset_high_and_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void zone_set_pageset_high_and_batch(struct zone *zone, int cpu_online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:7214
Inline: False
Direct callers:
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:page_alloc_cpu_online
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:setup_zone_pageset
```
**Symbols:**

```
ffffffff813e5130-ffffffff813e5270: zone_set_pageset_high_and_batch (STB_LOCAL)
ffffffff82064d8d-ffffffff82064dab: zone_set_pageset_high_and_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void zone_set_pageset_high_and_batch(struct zone *zone, int cpu_online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5420
Inline: False
Direct callers:
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:page_alloc_cpu_online
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:setup_zone_pageset
```
**Symbols:**

```
ffffffff81419b80-ffffffff81419cc0: zone_set_pageset_high_and_batch (STB_LOCAL)
ffffffff820e4504-ffffffff820e4522: zone_set_pageset_high_and_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void zone_set_pageset_high_and_batch(struct zone *zone, int cpu_online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff814469d0)
Location: mm/page_alloc.c:5513
Inline: False
Direct callers:
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:page_alloc_cpu_online
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:setup_zone_pageset
```
**Symbols:**

```
ffffffff814469d0-ffffffff81446bac: zone_set_pageset_high_and_batch (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int cpu_online</code>
</li>
</ul>
</details>
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
