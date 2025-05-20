# Function: <code>zone_batchsize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff81191c40)
Location: mm/page_alloc.c:4534
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff81191c40-ffffffff81191c97: zone_batchsize.isra.62 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff811a6810)
Location: mm/page_alloc.c:5070
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff811a6810-ffffffff811a6865: zone_batchsize.isra.68 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff811b6b50)
Location: mm/page_alloc.c:5153
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff811b6b50-ffffffff811b6ba6: zone_batchsize.isra.70 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff811bea90)
Location: mm/page_alloc.c:5452
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff811bea90-ffffffff811beae6: zone_batchsize.isra.73 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff811d3810)
Location: mm/page_alloc.c:5424
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff811d3810-ffffffff811d3865: zone_batchsize.isra.74 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff811f4ad0)
Location: mm/page_alloc.c:5562
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff811f4ad0-ffffffff811f4b23: zone_batchsize.isra.80 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int zone_batchsize(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81206720)
Location: mm/page_alloc.c:5808
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_init
```
**Symbols:**

```
ffffffff81206720-ffffffff81206777: zone_batchsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int zone_batchsize(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126c6d0)
Location: mm/page_alloc.c:5994
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_init
```
**Symbols:**

```
ffffffff8126c6d0-ffffffff8126c731: zone_batchsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int zone_batchsize(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127b4e0)
Location: mm/page_alloc.c:6012
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_init
```
**Symbols:**

```
ffffffff8127b4e0-ffffffff8127b541: zone_batchsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int zone_batchsize(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812ad650)
Location: mm/page_alloc.c:6109
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_init
```
**Symbols:**

```
ffffffff812ad650-ffffffff812ad6a5: zone_batchsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int zone_batchsize(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b9030)
Location: mm/page_alloc.c:6347
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_init
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
**Symbols:**

```
ffffffff812b9030-ffffffff812b9085: zone_batchsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int zone_batchsize(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812be500)
Location: mm/page_alloc.c:6568
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_init
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
**Symbols:**

```
ffffffff812be500-ffffffff812be555: zone_batchsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int zone_batchsize(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff81301675)
Location: mm/page_alloc.c:6764
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
Direct callers:
  - mm/page_alloc.c:zone_init_internals
```
**Symbols:**

```
ffffffff81300c60-ffffffff81300cb7: zone_batchsize (STB_LOCAL)
ffffffff81cbd04f-ffffffff81cbd07a: zone_batchsize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int zone_batchsize(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff81368f85)
Location: mm/page_alloc.c:6885
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
Direct callers:
  - mm/page_alloc.c:zone_init_internals
```
**Symbols:**

```
ffffffff813681b0-ffffffff81368213: zone_batchsize (STB_LOCAL)
ffffffff81e6eeb5-ffffffff81e6eeec: zone_batchsize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff820c7c9b)
Location: mm/page_alloc.c:7057
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_pcp_init
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8214c71b)
Location: mm/page_alloc.c:5262
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_pcp_init
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int zone_batchsize(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5351
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_init
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
**Symbols:**

```
ffffffff81445ac0-ffffffff81445b23: zone_batchsize (STB_LOCAL)
ffffffff821c10eb-ffffffff821c1122: zone_batchsize.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int zone_batchsize(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010312a78)
Location: mm/page_alloc.c:6012
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_init
```
**Symbols:**

```
ffff800010312a78-ffff800010312b00: zone_batchsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int zone_batchsize(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c052d788)
Location: mm/page_alloc.c:6012
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
c052d788-c052d7e4: zone_batchsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int zone_batchsize(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e3af0)
Location: mm/page_alloc.c:6012
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_init_internals
```
**Symbols:**

```
c0000000003e3af0-c0000000003e3b58: zone_batchsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int zone_batchsize(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021a92c)
Location: mm/page_alloc.c:6012
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffe00021a92c-ffffffe00021a9bc: zone_batchsize (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int zone_batchsize(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81273b30)
Location: mm/page_alloc.c:6012
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_init
```
**Symbols:**

```
ffffffff81273b30-ffffffff81273b91: zone_batchsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int zone_batchsize(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81265aa0)
Location: mm/page_alloc.c:6012
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_init
```
**Symbols:**

```
ffffffff81265aa0-ffffffff81265b01: zone_batchsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int zone_batchsize(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812718d0)
Location: mm/page_alloc.c:6012
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_init
```
**Symbols:**

```
ffffffff812718d0-ffffffff81271931: zone_batchsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int zone_batchsize(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81281330)
Location: mm/page_alloc.c:6012
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_init
```
**Symbols:**

```
ffffffff81281330-ffffffff81281391: zone_batchsize (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
