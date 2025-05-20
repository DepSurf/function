# Function: <code>gfpflags_to_migratetype</code>

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
In mm/page_alloc.c (ffffffff8119304b)
Location: include/linux/gfp.h:257
Inline: True
Inline callers:
  - mm/page_alloc.c:gfp_pfmemalloc_allowed
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/compaction.c (ffffffff811b7526)
Location: include/linux/gfp.h:257
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
In mm/page_alloc.c (ffffffff811ab020)
Location: include/linux/gfp.h:267
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/compaction.c (ffffffff811d0f66)
Location: include/linux/gfp.h:267
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
In mm/page_alloc.c (ffffffff811bb6a0)
Location: include/linux/gfp.h:260
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/compaction.c (ffffffff811e0fb6)
Location: include/linux/gfp.h:260
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
In mm/page_alloc.c (ffffffff811c3a10)
Location: include/linux/gfp.h:306
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/compaction.c (ffffffff811eacbc)
Location: include/linux/gfp.h:306
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d87ad)
Location: include/linux/gfp.h:291
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/compaction.c (ffffffff8120103c)
Location: include/linux/gfp.h:291
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f9977)
Location: include/linux/gfp.h:291
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/compaction.c (ffffffff81222475)
Location: include/linux/gfp.h:291
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120bfd2)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/compaction.c (ffffffff812354c5)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81246551)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
```
```
In mm/page_alloc.c (ffffffff812721f5)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
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
In mm/compaction.c (ffffffff81254a60)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
```
```
In mm/page_alloc.c (ffffffff81281055)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/compaction.c (ffff8000102ebf30)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
```
```
In mm/page_alloc.c (ffff800010318cf4)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
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
In mm/compaction.c (c050ff70)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
```
```
In mm/page_alloc.c (c05336e8)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
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
In mm/compaction.c (c0000000003af72c)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
```
```
In mm/page_alloc.c (c0000000003eb684)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
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
In mm/compaction.c (ffffffe000200944)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
```
```
In mm/page_alloc.c (ffffffe00021ea70)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
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
In mm/compaction.c (ffffffff8124d0b0)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
```
```
In mm/page_alloc.c (ffffffff812796a5)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
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
In mm/compaction.c (ffffffff81240050)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
```
```
In mm/page_alloc.c (ffffffff8126b595)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
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
In mm/compaction.c (ffffffff8124ae50)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
```
```
In mm/page_alloc.c (ffffffff81277445)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
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
In mm/compaction.c (ffffffff8125a6e0)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
```
```
In mm/page_alloc.c (ffffffff81287035)
Location: include/linux/gfp.h:308
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
</ul>

## Differences
