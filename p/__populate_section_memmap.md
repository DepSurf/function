# Function: <code>__populate_section_memmap</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *__populate_section_memmap(long unsigned int pfn, long unsigned int nr_pages, int nid, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a97bfe)
Location: mm/sparse-vmemmap.c:248
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81a97bfe-ffffffff81a97c53: __populate_section_memmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *__populate_section_memmap(long unsigned int pfn, long unsigned int nr_pages, int nid, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81acf4cc)
Location: mm/sparse-vmemmap.c:248
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81acf4cc-ffffffff81acf521: __populate_section_memmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *__populate_section_memmap(long unsigned int pfn, long unsigned int nr_pages, int nid, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81bc7f08)
Location: mm/sparse-vmemmap.c:247
Inline: False
Direct callers:
  - mm/sparse.c:section_activate
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81bc7f08-ffffffff81bc7f5d: __populate_section_memmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *__populate_section_memmap(long unsigned int pfn, long unsigned int nr_pages, int nid, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81c40c44)
Location: mm/sparse-vmemmap.c:251
Inline: False
Direct callers:
  - mm/sparse.c:section_activate
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81c40c44-ffffffff81c40c97: __populate_section_memmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *__populate_section_memmap(long unsigned int pfn, long unsigned int nr_pages, int nid, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81c32ba7)
Location: mm/sparse-vmemmap.c:251
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81c32ba7-ffffffff81c32bfa: __populate_section_memmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *__populate_section_memmap(long unsigned int pfn, long unsigned int nr_pages, int nid, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81d51573)
Location: mm/sparse-vmemmap.c:605
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81d51573-ffffffff81d515c6: __populate_section_memmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *__populate_section_memmap(long unsigned int pfn, long unsigned int nr_pages, int nid, struct vmem_altmap *altmap, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81f2189a)
Location: mm/sparse-vmemmap.c:775
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81f2189a-ffffffff81f21aae: __populate_section_memmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *__populate_section_memmap(long unsigned int pfn, long unsigned int nr_pages, int nid, struct vmem_altmap *altmap, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff820cbf80)
Location: mm/sparse-vmemmap.c:449
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff820cbf80-ffffffff820cc08b: __populate_section_memmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *__populate_section_memmap(long unsigned int pfn, long unsigned int nr_pages, int nid, struct vmem_altmap *altmap, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff82150230)
Location: mm/sparse-vmemmap.c:449
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff82150230-ffffffff8215033b: __populate_section_memmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *__populate_section_memmap(long unsigned int pfn, long unsigned int nr_pages, int nid, struct vmem_altmap *altmap, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff82233060)
Location: mm/sparse-vmemmap.c:452
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff82233060-ffffffff82233172: __populate_section_memmap (STB_GLOBAL)
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
struct page *__populate_section_memmap(long unsigned int pfn, long unsigned int nr_pages, int nid, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffff800010da10a8)
Location: mm/sparse-vmemmap.c:248
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffff800010da10a8-ffff800010da1100: __populate_section_memmap (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *__populate_section_memmap(long unsigned int pfn, long unsigned int nr_pages, int nid, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (c000000000eedfd4)
Location: mm/sparse-vmemmap.c:248
Inline: False
Direct callers:
  - mm/sparse.c:section_activate
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
c000000000eedfd4-c000000000eee058: __populate_section_memmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *__populate_section_memmap(long unsigned int pfn, long unsigned int nr_pages, int nid, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffe00004917a)
Location: mm/sparse-vmemmap.c:248
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffe00004917a-ffffffe0000491be: __populate_section_memmap (STB_GLOBAL)
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
struct page *__populate_section_memmap(long unsigned int pfn, long unsigned int nr_pages, int nid, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a6e33c)
Location: mm/sparse-vmemmap.c:248
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81a6e33c-ffffffff81a6e391: __populate_section_memmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *__populate_section_memmap(long unsigned int pfn, long unsigned int nr_pages, int nid, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a2a744)
Location: mm/sparse-vmemmap.c:248
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81a2a744-ffffffff81a2a799: __populate_section_memmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *__populate_section_memmap(long unsigned int pfn, long unsigned int nr_pages, int nid, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81ada74c)
Location: mm/sparse-vmemmap.c:248
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81ada74c-ffffffff81ada7a1: __populate_section_memmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *__populate_section_memmap(long unsigned int pfn, long unsigned int nr_pages, int nid, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81ae6c02)
Location: mm/sparse-vmemmap.c:248
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81ae6c02-ffffffff81ae6c57: __populate_section_memmap (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dev_pagemap *pgmap</code>
</li>
</ul>
</details>
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
