# Function: <code>__free_one_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811940c0)
Location: mm/page_alloc.c:656
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a71c7)
Location: mm/page_alloc.c:769
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b75b7)
Location: mm/page_alloc.c:785
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811bf3b8)
Location: mm/page_alloc.c:798
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
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
In mm/page_alloc.c (ffffffff811d3ed8)
Location: mm/page_alloc.c:813
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
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
In mm/page_alloc.c (ffffffff811f5b8a)
Location: mm/page_alloc.c:771
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
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
In mm/page_alloc.c (ffffffff81207826)
Location: mm/page_alloc.c:816
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
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
In mm/page_alloc.c (ffffffff8126d75f)
Location: mm/page_alloc.c:903
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
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
In mm/page_alloc.c (ffffffff8127c57f)
Location: mm/page_alloc.c:884
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __free_one_page(struct page *page, long unsigned int pfn, struct zone *zone, unsigned int order, int migratetype, bool report);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812ae8c0)
Location: mm/page_alloc.c:945
Inline: False
Direct callers:
  - mm/page_alloc.c:__putback_isolated_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
**Symbols:**

```
ffffffff812ae8c0-ffffffff812aec9b: __free_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __free_one_page(struct page *page, long unsigned int pfn, struct zone *zone, unsigned int order, int migratetype, fpi_t fpi_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812ba4d0)
Location: mm/page_alloc.c:983
Inline: False
Direct callers:
  - mm/page_alloc.c:__putback_isolated_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
**Symbols:**

```
ffffffff812ba4d0-ffffffff812ba8c9: __free_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __free_one_page(struct page *page, long unsigned int pfn, struct zone *zone, unsigned int order, int migratetype, fpi_t fpi_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bf620)
Location: mm/page_alloc.c:1012
Inline: False
Direct callers:
  - mm/page_alloc.c:__putback_isolated_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
**Symbols:**

```
ffffffff812bf620-ffffffff812bfa30: __free_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __free_one_page(struct page *page, long unsigned int pfn, struct zone *zone, unsigned int order, int migratetype, fpi_t fpi_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1058
Inline: False
Direct callers:
  - mm/page_alloc.c:__putback_isolated_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
```
**Symbols:**

```
ffffffff81301fe0-ffffffff81302514: __free_one_page (STB_LOCAL)
ffffffff81cbd274-ffffffff81cbd295: __free_one_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __free_one_page(struct page *page, long unsigned int pfn, struct zone *zone, unsigned int order, int migratetype, fpi_t fpi_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1020
Inline: False
Direct callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:__putback_isolated_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:split_free_page
```
**Symbols:**

```
ffffffff813692b0-ffffffff813697d3: __free_one_page (STB_LOCAL)
ffffffff81e6f004-ffffffff81e6f037: __free_one_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __free_one_page(struct page *page, long unsigned int pfn, struct zone *zone, unsigned int order, int migratetype, fpi_t fpi_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1092
Inline: False
Direct callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:__putback_isolated_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:split_free_page
```
**Symbols:**

```
ffffffff813e5310-ffffffff813e5836: __free_one_page (STB_LOCAL)
ffffffff82064dab-ffffffff82064dde: __free_one_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __free_one_page(struct page *page, long unsigned int pfn, struct zone *zone, unsigned int order, int migratetype, fpi_t fpi_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:788
Inline: False
Direct callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:__putback_isolated_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:split_free_page
```
**Symbols:**

```
ffffffff81419fa0-ffffffff8141a51a: __free_one_page (STB_LOCAL)
ffffffff820e4522-ffffffff820e4543: __free_one_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __free_one_page(struct page *page, long unsigned int pfn, struct zone *zone, unsigned int order, int migratetype, fpi_t fpi_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:764
Inline: False
Direct callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:__putback_isolated_page
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:split_free_page
```
**Symbols:**

```
ffffffff81447240-ffffffff81447779: __free_one_page (STB_LOCAL)
ffffffff821c122b-ffffffff821c124c: __free_one_page.cold (STB_LOCAL)
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
void __free_one_page(struct page *page, long unsigned int pfn, struct zone *zone, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010313fd8)
Location: mm/page_alloc.c:884
Inline: False
Direct callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
**Symbols:**

```
ffff800010313fd8-ffff8000103143bc: __free_one_page (STB_LOCAL)
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
In mm/page_alloc.c (c052e468)
Location: mm/page_alloc.c:884
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
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
In mm/page_alloc.c (c0000000003e55a8)
Location: mm/page_alloc.c:884
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
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
In mm/page_alloc.c (ffffffe00021ab7e)
Location: mm/page_alloc.c:884
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
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
In mm/page_alloc.c (ffffffff81274bcf)
Location: mm/page_alloc.c:884
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
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
In mm/page_alloc.c (ffffffff81266b3f)
Location: mm/page_alloc.c:884
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
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
In mm/page_alloc.c (ffffffff8127296f)
Location: mm/page_alloc.c:884
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
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
In mm/page_alloc.c (ffffffff8128241c)
Location: mm/page_alloc.c:884
Inline: True
Inline callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>fpi_t fpi_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool report</code>
</li>
</ul>
</details>
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
</ul>
