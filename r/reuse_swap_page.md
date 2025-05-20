# Function: <code>reuse_swap_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int reuse_swap_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811d4970)
Location: mm/swapfile.c:931
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:handle_mm_fault
  - mm/huge_memory.c:khugepaged
```
**Symbols:**

```
ffffffff811d4970-ffffffff811d49f0: reuse_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool reuse_swap_page(struct page *page, int *total_mapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811f2820)
Location: mm/swapfile.c:930
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff811f2820-ffffffff811f28bd: reuse_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool reuse_swap_page(struct page *page, int *total_mapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81203220)
Location: mm/swapfile.c:936
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff81203220-ffffffff8120330a: reuse_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool reuse_swap_page(struct page *page, int *total_mapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120e640)
Location: mm/swapfile.c:1345
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8120e640-ffffffff8120e75b: reuse_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool reuse_swap_page(struct page *page, int *total_map_swapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81229b80)
Location: mm/swapfile.c:1550
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff81229b80-ffffffff81229e97: reuse_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool reuse_swap_page(struct page *page, int *total_map_swapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8124ae40)
Location: mm/swapfile.c:1550
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8124ae40-ffffffff8124b12f: reuse_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool reuse_swap_page(struct page *page, int *total_map_swapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125f470)
Location: mm/swapfile.c:1544
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8125f470-ffffffff8125f795: reuse_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool reuse_swap_page(struct page *page, int *total_map_swapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127a130)
Location: mm/swapfile.c:1653
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff8127a130-ffffffff8127a46e: reuse_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool reuse_swap_page(struct page *page, int *total_map_swapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81289c10)
Location: mm/swapfile.c:1653
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff81289c10-ffffffff81289f4e: reuse_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool reuse_swap_page(struct page *page, int *total_map_swapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bcad0)
Location: mm/swapfile.c:1690
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff812bcad0-ffffffff812bcc52: reuse_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool reuse_swap_page(struct page *page, int *total_map_swapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c8600)
Location: mm/swapfile.c:1708
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff812c8600-ffffffff812c8782: reuse_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool reuse_swap_page(struct page *page, int *total_map_swapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cefb0)
Location: mm/swapfile.c:1707
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff812cefb0-ffffffff812cf12c: reuse_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool reuse_swap_page(struct page *page, int *total_map_swapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81314550)
Location: mm/swapfile.c:1676
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff81314550-ffffffff813146ca: reuse_swap_page (STB_GLOBAL)
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
bool reuse_swap_page(struct page *page, int *total_map_swapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010324bc8)
Location: mm/swapfile.c:1653
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffff800010324bc8-ffff800010324df4: reuse_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool reuse_swap_page(struct page *page, int *total_map_swapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053c6c8)
Location: mm/swapfile.c:1653
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
c053c6c8-c053c868: reuse_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool reuse_swap_page(struct page *page, int *total_map_swapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003facc0)
Location: mm/swapfile.c:1653
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
c0000000003facc0-c0000000003fafa8: reuse_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool reuse_swap_page(struct page *page, int *total_map_swapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe0002252e2)
Location: mm/swapfile.c:1653
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffe0002252e2-ffffffe0002254b0: reuse_swap_page (STB_GLOBAL)
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
bool reuse_swap_page(struct page *page, int *total_map_swapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812821f0)
Location: mm/swapfile.c:1653
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff812821f0-ffffffff8128252e: reuse_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool reuse_swap_page(struct page *page, int *total_map_swapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81273d10)
Location: mm/swapfile.c:1653
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff81273d10-ffffffff8127404e: reuse_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool reuse_swap_page(struct page *page, int *total_map_swapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81280000)
Location: mm/swapfile.c:1653
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff81280000-ffffffff8128033e: reuse_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool reuse_swap_page(struct page *page, int *total_map_swapcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128fcf0)
Location: mm/swapfile.c:1653
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff8128fcf0-ffffffff81290054: reuse_swap_page (STB_GLOBAL)
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
<code>int *total_mapcount</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int *total_map_swapcount</code>
</li>
<li>
<b>Param removed. </b>
<code>int *total_mapcount</code>
</li>
</ul>
</details>
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
