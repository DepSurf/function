# Function: <code>page_trans_huge_mapcount</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int page_trans_huge_mapcount(struct page *page, int *total_mapcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81216960)
Location: mm/huge_memory.c:1925
Inline: True
Direct callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff81216960-ffffffff812169fc: page_trans_huge_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int page_trans_huge_mapcount(struct page *page, int *total_mapcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81228f20)
Location: mm/huge_memory.c:2056
Inline: True
Direct callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff81228f20-ffffffff81228fbc: page_trans_huge_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int page_trans_huge_mapcount(struct page *page, int *total_mapcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81234c00)
Location: mm/huge_memory.c:2380
Inline: True
Direct callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff81234c00-ffffffff81234c9c: page_trans_huge_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int page_trans_huge_mapcount(struct page *page, int *total_mapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81254620)
Location: mm/huge_memory.c:2532
Inline: False
```
**Symbols:**

```
ffffffff81254620-ffffffff812546bd: page_trans_huge_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int page_trans_huge_mapcount(struct page *page, int *total_mapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81278470)
Location: mm/huge_memory.c:2524
Inline: False
```
**Symbols:**

```
ffffffff81278470-ffffffff8127850d: page_trans_huge_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int page_trans_huge_mapcount(struct page *page, int *total_mapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8128cac0)
Location: mm/huge_memory.c:2543
Inline: False
Direct callers:
  - mm/swapfile.c:reuse_swap_page
```
**Symbols:**

```
ffffffff8128cac0-ffffffff8128cb61: page_trans_huge_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int page_trans_huge_mapcount(struct page *page, int *total_mapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a77c0)
Location: mm/huge_memory.c:2604
Inline: False
Direct callers:
  - mm/swapfile.c:reuse_swap_page
```
**Symbols:**

```
ffffffff812a77c0-ffffffff812a7861: page_trans_huge_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int page_trans_huge_mapcount(struct page *page, int *total_mapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b8c60)
Location: mm/huge_memory.c:2627
Inline: False
Direct callers:
  - mm/swapfile.c:reuse_swap_page
```
**Symbols:**

```
ffffffff812b8c60-ffffffff812b8d01: page_trans_huge_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int page_trans_huge_mapcount(struct page *page, int *total_mapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ed810)
Location: mm/huge_memory.c:2537
Inline: False
Direct callers:
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
**Symbols:**

```
ffffffff812ed810-ffffffff812ed8b4: page_trans_huge_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int page_trans_huge_mapcount(struct page *page, int *total_mapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f8e90)
Location: mm/huge_memory.c:2594
Inline: False
Direct callers:
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
**Symbols:**

```
ffffffff812f8e90-ffffffff812f8f5d: page_trans_huge_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int page_trans_huge_mapcount(struct page *page, int *total_mapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ff4d0)
Location: mm/huge_memory.c:2605
Inline: False
Direct callers:
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
**Symbols:**

```
ffffffff812ff4d0-ffffffff812ff5a0: page_trans_huge_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int page_trans_huge_mapcount(struct page *page, int *total_mapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813490e0)
Location: mm/huge_memory.c:2544
Inline: False
Direct callers:
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
**Symbols:**

```
ffffffff813490e0-ffffffff813491b0: page_trans_huge_mapcount (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int page_trans_huge_mapcount(struct page *page, int *total_mapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff800010359320)
Location: mm/huge_memory.c:2627
Inline: False
Direct callers:
  - mm/swapfile.c:reuse_swap_page
```
**Symbols:**

```
ffff800010359320-ffff8000103593fc: page_trans_huge_mapcount (STB_GLOBAL)
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
In mm/swapfile.c (c053c704)
Location: include/linux/mm.h:734
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int page_trans_huge_mapcount(struct page *page, int *total_mapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c000000000442770)
Location: mm/huge_memory.c:2627
Inline: False
Direct callers:
  - mm/swapfile.c:reuse_swap_page
```
**Symbols:**

```
c000000000442770-c0000000004428b4: page_trans_huge_mapcount (STB_GLOBAL)
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
In mm/swapfile.c (ffffffe000225312)
Location: include/linux/mm.h:734
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
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
int page_trans_huge_mapcount(struct page *page, int *total_mapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b1240)
Location: mm/huge_memory.c:2627
Inline: False
Direct callers:
  - mm/swapfile.c:reuse_swap_page
```
**Symbols:**

```
ffffffff812b1240-ffffffff812b12e1: page_trans_huge_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int page_trans_huge_mapcount(struct page *page, int *total_mapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a2610)
Location: mm/huge_memory.c:2627
Inline: False
Direct callers:
  - mm/swapfile.c:reuse_swap_page
```
**Symbols:**

```
ffffffff812a2610-ffffffff812a26b1: page_trans_huge_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int page_trans_huge_mapcount(struct page *page, int *total_mapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812af050)
Location: mm/huge_memory.c:2627
Inline: False
Direct callers:
  - mm/swapfile.c:reuse_swap_page
```
**Symbols:**

```
ffffffff812af050-ffffffff812af0f1: page_trans_huge_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int page_trans_huge_mapcount(struct page *page, int *total_mapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812bf3a0)
Location: mm/huge_memory.c:2627
Inline: False
Direct callers:
  - mm/swapfile.c:reuse_swap_page
```
**Symbols:**

```
ffffffff812bf3a0-ffffffff812bf441: page_trans_huge_mapcount (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
