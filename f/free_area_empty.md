# Function: <code>free_area_empty</code>

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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81246b37)
Location: include/linux/mmzone.h:154
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
```
In mm/page_alloc.c (ffffffff81274128)
Location: include/linux/mmzone.h:154
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__zone_watermark_ok
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81255037)
Location: include/linux/mmzone.h:154
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
```
In mm/page_alloc.c (ffffffff81282f46)
Location: include/linux/mmzone.h:154
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__zone_watermark_ok
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812817af)
Location: include/linux/mmzone.h:110
Inline: True
Inline callers:
  - mm/compaction.c:compact_finished
```
```
In mm/page_alloc.c (ffffffff812b4fcf)
Location: include/linux/mmzone.h:110
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128ae49)
Location: include/linux/mmzone.h:108
Inline: True
Inline callers:
  - mm/compaction.c:__compact_finished
```
```
In mm/page_alloc.c (ffffffff81be832a)
Location: include/linux/mmzone.h:108
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81290c20)
Location: include/linux/mmzone.h:108
Inline: True
Inline callers:
  - mm/compaction.c:__compact_finished
```
```
In mm/page_alloc.c (ffffffff81bda12d)
Location: include/linux/mmzone.h:108
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812d0df6)
Location: include/linux/mmzone.h:109
Inline: True
Inline callers:
  - mm/compaction.c:__compact_finished
```
```
In mm/page_alloc.c (ffffffff81cbe074)
Location: include/linux/mmzone.h:109
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
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
In mm/compaction.c (ffffffff8132f5b3)
Location: include/linux/mmzone.h:117
Inline: True
Inline callers:
  - mm/compaction.c:__compact_finished
```
```
In mm/page_alloc.c (ffffffff81e6ff75)
Location: include/linux/mmzone.h:117
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:find_suitable_fallback
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
In mm/compaction.c (ffffffff813a5c46)
Location: include/linux/mmzone.h:117
Inline: True
Inline callers:
  - mm/compaction.c:__compact_finished
```
```
In mm/page_alloc.c (ffffffff813ee2a8)
Location: include/linux/mmzone.h:117
Inline: True
Inline callers:
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:find_suitable_fallback
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
In mm/compaction.c (ffffffff813d98b6)
Location: mm/internal.h:523
Inline: True
Inline callers:
  - mm/compaction.c:__compact_finished
```
```
In mm/show_mem.c (ffffffff813de5f1)
Location: mm/internal.h:523
Inline: True
Inline callers:
  - mm/show_mem.c:__show_free_areas
```
```
In mm/page_alloc.c (ffffffff8141d25f)
Location: mm/internal.h:523
Inline: True
Inline callers:
  - mm/page_alloc.c:find_suitable_fallback
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
In mm/compaction.c (ffffffff814035e6)
Location: mm/internal.h:550
Inline: True
Inline callers:
  - mm/compaction.c:__compact_finished
```
```
In mm/show_mem.c (ffffffff814083e1)
Location: mm/internal.h:550
Inline: True
Inline callers:
  - mm/show_mem.c:show_free_areas
```
```
In mm/page_alloc.c (ffffffff81449cff)
Location: mm/internal.h:550
Inline: True
Inline callers:
  - mm/page_alloc.c:find_suitable_fallback
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffff8000102ec470)
Location: include/linux/mmzone.h:154
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
```
In mm/page_alloc.c (ffff8000103197c4)
Location: include/linux/mmzone.h:154
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__zone_watermark_ok
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0510660)
Location: include/linux/mmzone.h:154
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
```
In mm/page_alloc.c (c0534174)
Location: include/linux/mmzone.h:154
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__zone_watermark_ok
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0000000003afe34)
Location: include/linux/mmzone.h:154
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
```
In mm/page_alloc.c (c0000000003ec118)
Location: include/linux/mmzone.h:154
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__zone_watermark_ok
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffe000200e56)
Location: include/linux/mmzone.h:154
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
```
In mm/page_alloc.c (ffffffe00021f3ac)
Location: include/linux/mmzone.h:154
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__zone_watermark_ok
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124d687)
Location: include/linux/mmzone.h:154
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
```
In mm/page_alloc.c (ffffffff8127b596)
Location: include/linux/mmzone.h:154
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__zone_watermark_ok
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81240627)
Location: include/linux/mmzone.h:154
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
```
In mm/page_alloc.c (ffffffff8126d476)
Location: include/linux/mmzone.h:154
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__zone_watermark_ok
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124b427)
Location: include/linux/mmzone.h:154
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
```
In mm/page_alloc.c (ffffffff81279336)
Location: include/linux/mmzone.h:154
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__zone_watermark_ok
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8125acc4)
Location: include/linux/mmzone.h:154
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
```
In mm/page_alloc.c (ffffffff81288f26)
Location: include/linux/mmzone.h:154
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__zone_watermark_ok
```
</details>
</li>
</ul>

## Differences
