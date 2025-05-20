# Function: <code>truncate_error_page</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int truncate_error_page(struct page *p, long unsigned int pfn, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81244740)
Location: mm/memory-failure.c:557
Inline: True
Direct callers:
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff81244740-ffffffff812447df: truncate_error_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int truncate_error_page(struct page *p, long unsigned int pfn, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812645d0)
Location: mm/memory-failure.c:557
Inline: True
Direct callers:
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff812645d0-ffffffff81264672: truncate_error_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int truncate_error_page(struct page *p, long unsigned int pfn, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:590
Inline: True
Direct callers:
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff81288690-ffffffff812886fd: truncate_error_page (STB_LOCAL)
ffffffff8128a9d7-ffffffff8128aa24: truncate_error_page.cold.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int truncate_error_page(struct page *p, long unsigned int pfn, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff8129d9be)
Location: mm/memory-failure.c:592
Inline: True
Direct callers:
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff8129d960-ffffffff8129d9cd: truncate_error_page (STB_LOCAL)
ffffffff8129f94f-ffffffff8129f99c: truncate_error_page.cold.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int truncate_error_page(struct page *p, long unsigned int pfn, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff812b86d1)
Location: mm/memory-failure.c:589
Inline: True
Direct callers:
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff812b8670-ffffffff812b86e0: truncate_error_page (STB_LOCAL)
ffffffff812baadf-ffffffff812bab2c: truncate_error_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int truncate_error_page(struct page *p, long unsigned int pfn, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff812ca5b1)
Location: mm/memory-failure.c:593
Inline: True
Direct callers:
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff812ca550-ffffffff812ca5c0: truncate_error_page (STB_LOCAL)
ffffffff812cc9bb-ffffffff812cca08: truncate_error_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int truncate_error_page(struct page *p, long unsigned int pfn, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:591
Inline: False
Direct callers:
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff812fff90-ffffffff81300000: truncate_error_page (STB_LOCAL)
ffffffff81302a76-ffffffff81302ac3: truncate_error_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int truncate_error_page(struct page *p, long unsigned int pfn, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:617
Inline: False
Direct callers:
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff8130c2d0-ffffffff8130c340: truncate_error_page (STB_LOCAL)
ffffffff81be9e16-ffffffff81be9e63: truncate_error_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int truncate_error_page(struct page *p, long unsigned int pfn, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:621
Inline: False
Direct callers:
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_clean
```
**Symbols:**

```
ffffffff81312a30-ffffffff81312aa0: truncate_error_page (STB_LOCAL)
ffffffff81bdbe42-ffffffff81bdbe8f: truncate_error_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int truncate_error_page(struct page *p, long unsigned int pfn, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:776
Inline: False
Direct callers:
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_clean
```
**Symbols:**

```
ffffffff8135e460-ffffffff8135e4d3: truncate_error_page (STB_LOCAL)
ffffffff81cc2e16-ffffffff81cc2e63: truncate_error_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int truncate_error_page(struct page *p, long unsigned int pfn, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:773
Inline: False
Direct callers:
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_clean
```
**Symbols:**

```
ffffffff813d8cf0-ffffffff813d8d6b: truncate_error_page (STB_LOCAL)
ffffffff81e753af-ffffffff81e753ec: truncate_error_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int truncate_error_page(struct page *p, long unsigned int pfn, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8145f420)
Location: mm/memory-failure.c:837
Inline: False
Direct callers:
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_clean
```
**Symbols:**

```
ffffffff8145f420-ffffffff8145f518: truncate_error_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int truncate_error_page(struct page *p, long unsigned int pfn, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814953d0)
Location: mm/memory-failure.c:934
Inline: False
Direct callers:
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_clean
```
**Symbols:**

```
ffffffff814953d0-ffffffff814954c5: truncate_error_page (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int truncate_error_page(struct page *p, long unsigned int pfn, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffff80001036dd50)
Location: mm/memory-failure.c:593
Inline: True
Direct callers:
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffff80001036dd50-ffff80001036de18: truncate_error_page (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int truncate_error_page(struct page *p, long unsigned int pfn, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (c00000000045ece0)
Location: mm/memory-failure.c:593
Inline: True
Direct callers:
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
c00000000045ece0-c00000000045ee00: truncate_error_page (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int truncate_error_page(struct page *p, long unsigned int pfn, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff812c2b91)
Location: mm/memory-failure.c:593
Inline: True
Direct callers:
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff812c2b30-ffffffff812c2ba0: truncate_error_page (STB_LOCAL)
ffffffff812c4f9b-ffffffff812c4fe8: truncate_error_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int truncate_error_page(struct page *p, long unsigned int pfn, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff812b3be1)
Location: mm/memory-failure.c:593
Inline: True
Direct callers:
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff812b3b80-ffffffff812b3bf0: truncate_error_page (STB_LOCAL)
ffffffff812b5fdb-ffffffff812b6028: truncate_error_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int truncate_error_page(struct page *p, long unsigned int pfn, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff812c09a1)
Location: mm/memory-failure.c:593
Inline: True
Direct callers:
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff812c0940-ffffffff812c09b0: truncate_error_page (STB_LOCAL)
ffffffff812c2dab-ffffffff812c2df8: truncate_error_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int truncate_error_page(struct page *p, long unsigned int pfn, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff812d1461)
Location: mm/memory-failure.c:593
Inline: True
Direct callers:
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff812d1400-ffffffff812d1470: truncate_error_page (STB_LOCAL)
ffffffff812d384b-ffffffff812d3898: truncate_error_page.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
