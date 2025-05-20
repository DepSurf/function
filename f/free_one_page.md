# Function: <code>free_one_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_one_page(struct zone *zone, struct page *page, long unsigned int pfn, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81194060)
Location: mm/page_alloc.c:833
Inline: False
Direct callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_hot_cold_page
```
**Symbols:**

```
ffffffff81194060-ffffffff8119438a: free_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_one_page(struct zone *zone, struct page *page, long unsigned int pfn, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a7160)
Location: mm/page_alloc.c:1129
Inline: False
Direct callers:
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffffffff811a7160-ffffffff811a752b: free_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_one_page(struct zone *zone, struct page *page, long unsigned int pfn, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b7550)
Location: mm/page_alloc.c:1145
Inline: False
Direct callers:
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffffffff811b7550-ffffffff811b7917: free_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_one_page(struct zone *zone, struct page *page, long unsigned int pfn, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811bf360)
Location: mm/page_alloc.c:1155
Inline: False
Direct callers:
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffffffff811bf360-ffffffff811bf752: free_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_one_page(struct zone *zone, struct page *page, long unsigned int pfn, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d3e80)
Location: mm/page_alloc.c:1169
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffffffff811d3e80-ffffffff811d427c: free_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_one_page(struct zone *zone, struct page *page, long unsigned int pfn, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f5880)
Location: mm/page_alloc.c:1157
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffffffff811f5880-ffffffff811f5c7d: free_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_one_page(struct zone *zone, struct page *page, long unsigned int pfn, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81207520)
Location: mm/page_alloc.c:1202
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffffffff81207520-ffffffff81207912: free_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_one_page(struct zone *zone, struct page *page, long unsigned int pfn, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126d710)
Location: mm/page_alloc.c:1326
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffffffff8126d710-ffffffff8126dbb6: free_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_one_page(struct zone *zone, struct page *page, long unsigned int pfn, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127c530)
Location: mm/page_alloc.c:1313
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffffffff8127c530-ffffffff8127c9d6: free_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_one_page(struct zone *zone, struct page *page, long unsigned int pfn, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812aeca0)
Location: mm/page_alloc.c:1368
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffffffff812aeca0-ffffffff812aed7d: free_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_one_page(struct zone *zone, struct page *page, long unsigned int pfn, unsigned int order, int migratetype, fpi_t fpi_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812ba8d0)
Location: mm/page_alloc.c:1432
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffffffff812ba8d0-ffffffff812ba9a6: free_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_one_page(struct zone *zone, struct page *page, long unsigned int pfn, unsigned int order, int migratetype, fpi_t fpi_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bfa30)
Location: mm/page_alloc.c:1467
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffffffff812bfa30-ffffffff812bfb06: free_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff81302990)
Location: mm/page_alloc.c:1545
Inline: True
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff81302990-ffffffff81302a6a: free_one_page.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff81369f10)
Location: mm/page_alloc.c:1528
Inline: True
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff81369f10-ffffffff8136a017: free_one_page.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff813e6070)
Location: mm/page_alloc.c:1604
Inline: True
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff813e6070-ffffffff813e6177: free_one_page.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff8141ade0)
Location: mm/page_alloc.c:1276
Inline: True
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff8141ade0-ffffffff8141aee7: free_one_page.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void free_one_page(struct zone *zone, struct page *page, long unsigned int pfn, unsigned int order, int migratetype, fpi_t fpi_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144c3e1)
Location: mm/page_alloc.c:1246
Inline: True
Inline callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffffffff81448190-ffffffff81448238: free_one_page (STB_LOCAL)
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
void free_one_page(struct zone *zone, struct page *page, long unsigned int pfn, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff8000103143c0)
Location: mm/page_alloc.c:1313
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffff8000103143c0-ffff8000103144e4: free_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_one_page(struct zone *zone, struct page *page, long unsigned int pfn, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c052e410)
Location: mm/page_alloc.c:1313
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
c052e410-c052e81c: free_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_one_page(struct zone *zone, struct page *page, long unsigned int pfn, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e5500)
Location: mm/page_alloc.c:1313
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
c0000000003e5500-c0000000003e5ae8: free_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_one_page(struct zone *zone, struct page *page, long unsigned int pfn, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021ab2e)
Location: mm/page_alloc.c:1313
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffffffe00021ab2e-ffffffe00021af1c: free_one_page (STB_LOCAL)
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
void free_one_page(struct zone *zone, struct page *page, long unsigned int pfn, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81274b80)
Location: mm/page_alloc.c:1313
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffffffff81274b80-ffffffff81275026: free_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_one_page(struct zone *zone, struct page *page, long unsigned int pfn, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81266af0)
Location: mm/page_alloc.c:1313
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffffffff81266af0-ffffffff81266f96: free_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_one_page(struct zone *zone, struct page *page, long unsigned int pfn, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81272920)
Location: mm/page_alloc.c:1313
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffffffff81272920-ffffffff81272dc6: free_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_one_page(struct zone *zone, struct page *page, long unsigned int pfn, unsigned int order, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812823d0)
Location: mm/page_alloc.c:1313
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffffffff812823d0-ffffffff81282883: free_one_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>fpi_t fpi_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
