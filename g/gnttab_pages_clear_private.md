# Function: <code>gnttab_pages_clear_private</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void gnttab_pages_clear_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8160c580)
Location: drivers/xen/grant-table.c:818
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
**Symbols:**

```
ffffffff8160c580-ffffffff8160c5cf: gnttab_pages_clear_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void gnttab_pages_clear_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81641740)
Location: drivers/xen/grant-table.c:818
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
**Symbols:**

```
ffffffff81641740-ffffffff81641770: gnttab_pages_clear_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void gnttab_pages_clear_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff816628e0)
Location: drivers/xen/grant-table.c:818
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
**Symbols:**

```
ffffffff816628e0-ffffffff81662910: gnttab_pages_clear_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void gnttab_pages_clear_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81711dc0)
Location: drivers/xen/grant-table.c:816
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
**Symbols:**

```
ffffffff81711dc0-ffffffff81711dfb: gnttab_pages_clear_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void gnttab_pages_clear_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8172eb50)
Location: drivers/xen/grant-table.c:939
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
**Symbols:**

```
ffffffff8172eb50-ffffffff8172eb8b: gnttab_pages_clear_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void gnttab_pages_clear_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81713a59)
Location: drivers/xen/grant-table.c:939
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
**Symbols:**

```
ffffffff81712810-ffffffff8171284b: gnttab_pages_clear_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void gnttab_pages_clear_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8179046b)
Location: drivers/xen/grant-table.c:946
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
**Symbols:**

```
ffffffff8178f2b0-ffffffff8178f2eb: gnttab_pages_clear_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void gnttab_pages_clear_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff818c8925)
Location: drivers/xen/grant-table.c:1012
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
**Symbols:**

```
ffffffff818c7040-ffffffff818c707d: gnttab_pages_clear_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void gnttab_pages_clear_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a19385)
Location: drivers/xen/grant-table.c:1012
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
**Symbols:**

```
ffffffff81a17af0-ffffffff81a17b2d: gnttab_pages_clear_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void gnttab_pages_clear_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a626f5)
Location: drivers/xen/grant-table.c:1030
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
**Symbols:**

```
ffffffff81a60b80-ffffffff81a60bbd: gnttab_pages_clear_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void gnttab_pages_clear_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab4f25)
Location: drivers/xen/grant-table.c:1028
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
**Symbols:**

```
ffffffff81ab3350-ffffffff81ab338d: gnttab_pages_clear_private (STB_GLOBAL)
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
void gnttab_pages_clear_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffff80001082ca80)
Location: drivers/xen/grant-table.c:818
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
**Symbols:**

```
ffff80001082ca80-ffff80001082caf8: gnttab_pages_clear_private (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void gnttab_pages_clear_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81628750)
Location: drivers/xen/grant-table.c:818
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
**Symbols:**

```
ffffffff81628750-ffffffff81628780: gnttab_pages_clear_private (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void gnttab_pages_clear_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81656720)
Location: drivers/xen/grant-table.c:818
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
**Symbols:**

```
ffffffff81656720-ffffffff81656750: gnttab_pages_clear_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void gnttab_pages_clear_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81670d00)
Location: drivers/xen/grant-table.c:818
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
**Symbols:**

```
ffffffff81670d00-ffffffff81670d30: gnttab_pages_clear_private (STB_GLOBAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
