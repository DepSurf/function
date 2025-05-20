# Function: <code>page_zone_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:704
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/mm.h:704
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/mm.h:704
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a81cb)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/mlock.c (ffffffff811df22c)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b8598)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/mlock.c (ffffffff811ef040)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c03f3)
Location: include/linux/mm.h:829
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/mlock.c (ffffffff811f9fdd)
Location: include/linux/mm.h:829
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d4edf)
Location: include/linux/mm.h:880
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f62fa)
Location: include/linux/mm.h:957
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812085d5)
Location: include/linux/mm.h:1008
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126ea33)
Location: include/linux/mm.h:1076
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
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
In mm/page_alloc.c (ffffffff8127d873)
Location: include/linux/mm.h:1090
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
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
In mm/page_alloc.c (ffffffff812af94a)
Location: include/linux/mm.h:1264
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
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
In mm/page_alloc.c (ffffffff812bb5ba)
Location: include/linux/mm.h:1306
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
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
In mm/page_alloc.c (ffffffff812c0658)
Location: include/linux/mm.h:1362
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
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
In mm/page_alloc.c (ffffffff813034b2)
Location: include/linux/mm.h:1366
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8136b318)
Location: include/linux/mm.h:1296
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/page_isolation.c (ffffffff813ddbb5)
Location: include/linux/mm.h:1296
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e7639)
Location: include/linux/mm.h:1384
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/page_isolation.c (ffffffff81464835)
Location: include/linux/mm.h:1384
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8141c800)
Location: include/linux/mm.h:1583
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/page_isolation.c (ffffffff8149a335)
Location: include/linux/mm.h:1583
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81449314)
Location: include/linux/mm.h:1637
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/page_isolation.c (ffffffff814c9ab5)
Location: include/linux/mm.h:1637
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (ffff800010315138)
Location: include/linux/mm.h:1090
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
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
In mm/page_alloc.c (c052fa14)
Location: include/linux/mm.h:1090
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
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
In mm/page_alloc.c (c0000000003e6ebc)
Location: include/linux/mm.h:1090
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
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
In mm/page_alloc.c (ffffffe00021bbf4)
Location: include/linux/mm.h:1090
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
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
In mm/page_alloc.c (ffffffff81275ec3)
Location: include/linux/mm.h:1090
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
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
In mm/page_alloc.c (ffffffff81267e13)
Location: include/linux/mm.h:1090
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
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
In mm/page_alloc.c (ffffffff81273c63)
Location: include/linux/mm.h:1090
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
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
In mm/page_alloc.c (ffffffff81283763)
Location: include/linux/mm.h:1090
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
</details>
</li>
</ul>

## Differences
