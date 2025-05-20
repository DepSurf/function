# Function: <code>wb_min_pause</code>

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
In mm/page-writeback.c (ffffffff81198990)
Location: mm/page-writeback.c:1396
Inline: True
```
**Symbols:**

```
ffffffff81198990-ffffffff81198a96: wb_min_pause.isra.18 (STB_LOCAL)
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
In mm/page-writeback.c (ffffffff811ad9f0)
Location: mm/page-writeback.c:1439
Inline: True
```
**Symbols:**

```
ffffffff811ad9f0-ffffffff811adaf2: wb_min_pause.isra.21 (STB_LOCAL)
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
In mm/page-writeback.c (ffffffff811bdf50)
Location: mm/page-writeback.c:1439
Inline: True
```
**Symbols:**

```
ffffffff811bdf50-ffffffff811be054: wb_min_pause.isra.21 (STB_LOCAL)
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
In mm/page-writeback.c (ffffffff811c6100)
Location: mm/page-writeback.c:1439
Inline: True
```
**Symbols:**

```
ffffffff811c6100-ffffffff811c6217: wb_min_pause.isra.23 (STB_LOCAL)
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
In mm/page-writeback.c (ffffffff811daf10)
Location: mm/page-writeback.c:1438
Inline: True
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff811daf10-ffffffff811db021: wb_min_pause.isra.24 (STB_LOCAL)
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
In mm/page-writeback.c (ffffffff811fbfc0)
Location: mm/page-writeback.c:1438
Inline: True
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff811fbfc0-ffffffff811fc0ca: wb_min_pause.isra.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page-writeback.c (ffffffff8120e8d0)
Location: mm/page-writeback.c:1437
Inline: True
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff8120e8d0-ffffffff8120e9da: wb_min_pause.isra.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page-writeback.c (ffffffff8121e400)
Location: mm/page-writeback.c:1438
Inline: True
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff8121e400-ffffffff8121e517: wb_min_pause.isra.0 (STB_LOCAL)
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
In mm/page-writeback.c (ffffffff8122bea0)
Location: mm/page-writeback.c:1438
Inline: True
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff8122bea0-ffffffff8122bfb7: wb_min_pause.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int wb_min_pause(struct bdi_writeback *wb, long int max_pause, long unsigned int task_ratelimit, long unsigned int dirty_ratelimit, int *nr_dirtied_pause);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812584e0)
Location: mm/page-writeback.c:1432
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff812584e0-ffffffff812585f8: wb_min_pause (STB_LOCAL)
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
In mm/page-writeback.c (ffffffff81264556)
Location: mm/page-writeback.c:1432
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
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
In mm/page-writeback.c (ffffffff81268765)
Location: mm/page-writeback.c:1432
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
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
In mm/page-writeback.c (ffffffff812a51d8)
Location: mm/page-writeback.c:1437
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
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
In mm/page-writeback.c (ffffffff812fe1c7)
Location: mm/page-writeback.c:1434
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
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
In mm/page-writeback.c (ffffffff813686e5)
Location: mm/page-writeback.c:1546
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
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
In mm/page-writeback.c (ffffffff8139a885)
Location: mm/page-writeback.c:1546
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813c47bc)
Location: mm/page-writeback.c:1546
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
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
In mm/page-writeback.c (ffff8000102ba570)
Location: mm/page-writeback.c:1438
Inline: True
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffff8000102ba570-ffff8000102ba6d0: wb_min_pause.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int wb_min_pause(struct bdi_writeback *wb, long int max_pause, long unsigned int task_ratelimit, long unsigned int dirty_ratelimit, int *nr_dirtied_pause);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c04e6698)
Location: mm/page-writeback.c:1438
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
c04e6698-c04e67ec: wb_min_pause (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int wb_min_pause(struct bdi_writeback *wb, long int max_pause, long unsigned int task_ratelimit, long unsigned int dirty_ratelimit, int *nr_dirtied_pause);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c000000000372d60)
Location: mm/page-writeback.c:1438
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
c000000000372d60-c000000000372e84: wb_min_pause (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int wb_min_pause(struct bdi_writeback *wb, long int max_pause, long unsigned int task_ratelimit, long unsigned int dirty_ratelimit, int *nr_dirtied_pause);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffe0001de39e)
Location: mm/page-writeback.c:1438
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffe0001de39e-ffffffe0001de512: wb_min_pause (STB_LOCAL)
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
In mm/page-writeback.c (ffffffff812244f0)
Location: mm/page-writeback.c:1438
Inline: True
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff812244f0-ffffffff81224607: wb_min_pause.isra.0 (STB_LOCAL)
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
In mm/page-writeback.c (ffffffff812176a0)
Location: mm/page-writeback.c:1438
Inline: True
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff812176a0-ffffffff812177b7: wb_min_pause.isra.0 (STB_LOCAL)
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
In mm/page-writeback.c (ffffffff81222290)
Location: mm/page-writeback.c:1438
Inline: True
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff81222290-ffffffff812223a7: wb_min_pause.isra.0 (STB_LOCAL)
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
In mm/page-writeback.c (ffffffff812316d0)
Location: mm/page-writeback.c:1438
Inline: True
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff812316d0-ffffffff812317e7: wb_min_pause.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
