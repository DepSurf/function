# Function: <code>rmqueue</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c1c4d)
Location: mm/page_alloc.c:2813
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (ffffffff811d619b)
Location: mm/page_alloc.c:2870
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (ffffffff811f7662)
Location: mm/page_alloc.c:2974
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (ffffffff81209ad8)
Location: mm/page_alloc.c:3075
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *rmqueue(struct zone *preferred_zone, struct zone *zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126f0c0)
Location: mm/page_alloc.c:3250
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff8126f0c0-ffffffff8126ffb1: rmqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *rmqueue(struct zone *preferred_zone, struct zone *zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127df00)
Location: mm/page_alloc.c:3241
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff8127df00-ffffffff8127edf1: rmqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *rmqueue(struct zone *preferred_zone, struct zone *zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b0840)
Location: mm/page_alloc.c:3352
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff812b0840-ffffffff812b0fa2: rmqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *rmqueue(struct zone *preferred_zone, struct zone *zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bc480)
Location: mm/page_alloc.c:3454
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff812bc480-ffffffff812bcb80: rmqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *rmqueue(struct zone *preferred_zone, struct zone *zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c1270)
Location: mm/page_alloc.c:3504
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff812c1270-ffffffff812c1a9e: rmqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *rmqueue(struct zone *preferred_zone, struct zone *zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3675
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff81304620-ffffffff813051bf: rmqueue (STB_LOCAL)
ffffffff81cbd5fa-ffffffff81cbd78f: rmqueue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct page *rmqueue(struct zone *preferred_zone, struct zone *zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3711
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff8136c960-ffffffff8136d3b9: rmqueue (STB_LOCAL)
ffffffff81e6f67d-ffffffff81e6f6ef: rmqueue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct page *rmqueue(struct zone *preferred_zone, struct zone *zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3818
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff813e8b00-ffffffff813e972a: rmqueue (STB_LOCAL)
ffffffff820653b9-ffffffff820654b7: rmqueue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct page *rmqueue(struct zone *preferred_zone, struct zone *zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2807
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff8141dd10-ffffffff8141ebb2: rmqueue (STB_LOCAL)
ffffffff820e4c19-ffffffff820e4cab: rmqueue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct page *rmqueue(struct zone *preferred_zone, struct zone *zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2885
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff8144a8c0-ffffffff8144b79f: rmqueue (STB_LOCAL)
ffffffff821c18ed-ffffffff821c197f: rmqueue.cold (STB_LOCAL)
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
struct page *rmqueue(struct zone *preferred_zone, struct zone *zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010315940)
Location: mm/page_alloc.c:3241
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffff800010315940-ffff8000103169c8: rmqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *rmqueue(struct zone *preferred_zone, struct zone *zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0530750)
Location: mm/page_alloc.c:3241
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
c0530750-c05310f4: rmqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *rmqueue(struct zone *preferred_zone, struct zone *zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e7940)
Location: mm/page_alloc.c:3241
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
c0000000003e7940-c0000000003e8c38: rmqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffe00021c6c4)
Location: mm/page_alloc.c:3241
Inline: True
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffe00021c6c4-ffffffe00021ce32: rmqueue.isra.0 (STB_LOCAL)
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
struct page *rmqueue(struct zone *preferred_zone, struct zone *zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81276550)
Location: mm/page_alloc.c:3241
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff81276550-ffffffff81277441: rmqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *rmqueue(struct zone *preferred_zone, struct zone *zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812684a0)
Location: mm/page_alloc.c:3241
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff812684a0-ffffffff81269371: rmqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *rmqueue(struct zone *preferred_zone, struct zone *zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812742f0)
Location: mm/page_alloc.c:3241
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff812742f0-ffffffff812751e1: rmqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *rmqueue(struct zone *preferred_zone, struct zone *zone, unsigned int order, gfp_t gfp_flags, unsigned int alloc_flags, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812843c0)
Location: mm/page_alloc.c:3241
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff812843c0-ffffffff81284d9e: rmqueue (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
