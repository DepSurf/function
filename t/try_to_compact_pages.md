# Function: <code>try_to_compact_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int try_to_compact_pages(gfp_t gfp_mask, unsigned int order, int alloc_flags, const struct alloc_context *ac, enum migrate_mode mode, int *contended);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811b7fd0)
Location: mm/compaction.c:1527
Inline: False
```
**Symbols:**

```
ffffffff811b7fd0-ffffffff811b8264: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811d20b0)
Location: mm/compaction.c:1665
Inline: False
```
**Symbols:**

```
ffffffff811d20b0-ffffffff811d231f: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811e1fe0)
Location: mm/compaction.c:1683
Inline: False
```
**Symbols:**

```
ffffffff811e1fe0-ffffffff811e223f: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811ebde0)
Location: mm/compaction.c:1721
Inline: False
```
**Symbols:**

```
ffffffff811ebde0-ffffffff811ec051: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81202150)
Location: mm/compaction.c:1745
Inline: False
```
**Symbols:**

```
ffffffff81202150-ffffffff812023b3: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81223510)
Location: mm/compaction.c:1745
Inline: False
```
**Symbols:**

```
ffffffff81223510-ffffffff81223763: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81236570)
Location: mm/compaction.c:1746
Inline: False
```
**Symbols:**

```
ffffffff81236570-ffffffff812367c3: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, struct page **capture);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81247a80)
Location: mm/compaction.c:2334
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff81247a80-ffffffff81247d1f: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, struct page **capture);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81255ee0)
Location: mm/compaction.c:2339
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff81255ee0-ffffffff8125617f: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, struct page **capture);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812845d0)
Location: mm/compaction.c:2356
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff812845d0-ffffffff8128480c: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, struct page **capture);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128e8d0)
Location: mm/compaction.c:2510
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff8128e8d0-ffffffff8128eb27: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, struct page **capture);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81293f60)
Location: mm/compaction.c:2558
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff81293f60-ffffffff812941b6: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, struct page **capture);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812d4500)
Location: mm/compaction.c:2550
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff812d4500-ffffffff812d471e: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, struct page **capture);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81333490)
Location: mm/compaction.c:2570
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff81333490-ffffffff8133370e: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, struct page **capture);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813aa1a0)
Location: mm/compaction.c:2569
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff813aa1a0-ffffffff813aa406: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, struct page **capture);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813dd430)
Location: mm/compaction.c:2654
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff813dd430-ffffffff813dd6ae: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, struct page **capture);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81407390)
Location: mm/compaction.c:2722
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff81407390-ffffffff8140760e: try_to_compact_pages (STB_GLOBAL)
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
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, struct page **capture);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffff8000102ed480)
Location: mm/compaction.c:2339
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffff8000102ed480-ffff8000102ed760: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, struct page **capture);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c05113b4)
Location: mm/compaction.c:2339
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
c05113b4-c051170c: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, struct page **capture);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0000000003b11a0)
Location: mm/compaction.c:2339
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
c0000000003b11a0-c0000000003b1568: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, struct page **capture);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffe000201ac2)
Location: mm/compaction.c:2339
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffe000201ac2-ffffffe000201d1a: try_to_compact_pages (STB_GLOBAL)
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
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, struct page **capture);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124e530)
Location: mm/compaction.c:2339
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff8124e530-ffffffff8124e7cf: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, struct page **capture);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812414d0)
Location: mm/compaction.c:2339
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff812414d0-ffffffff8124176f: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, struct page **capture);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124c2d0)
Location: mm/compaction.c:2339
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff8124c2d0-ffffffff8124c56f: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum compact_result try_to_compact_pages(gfp_t gfp_mask, unsigned int order, unsigned int alloc_flags, const struct alloc_context *ac, enum compact_priority prio, struct page **capture);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8125bc30)
Location: mm/compaction.c:2339
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
**Symbols:**

```
ffffffff8125bc30-ffffffff8125bf01: try_to_compact_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum compact_priority prio</code>
</li>
<li>
<b>Param removed. </b>
<code>enum migrate_mode mode</code>
</li>
<li>
<b>Param removed. </b>
<code>int *contended</code>
</li>
<li>
<b>Param type changed. </b>
<code>int alloc_flags</code> ➡️ <code>unsigned int alloc_flags</code>
</li>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>enum compact_result</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct page **capture</code>
</li>
</ul>
</details>
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
