# Function: <code>__pte_alloc_kernel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bd3a0)
Location: mm/memory.c:604
Inline: False
```
**Symbols:**

```
ffffffff811bd3a0-ffffffff811bd481: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d8110)
Location: mm/memory.c:610
Inline: False
Direct callers:
  - mm/memory.c:apply_to_page_range
```
**Symbols:**

```
ffffffff811d8110-ffffffff811d820b: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e7de0)
Location: mm/memory.c:612
Inline: False
Direct callers:
  - mm/memory.c:apply_to_page_range
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff811e7de0-ffffffff811e7edb: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f2f80)
Location: mm/memory.c:677
Inline: False
Direct callers:
  - mm/memory.c:apply_to_page_range
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff811f2f80-ffffffff811f307e: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120a0f0)
Location: mm/memory.c:679
Inline: False
Direct callers:
  - mm/memory.c:apply_to_page_range
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8120a0f0-ffffffff8120a1f8: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122af10)
Location: mm/memory.c:694
Inline: False
Direct callers:
  - mm/memory.c:apply_to_page_range
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8122af10-ffffffff8122b01b: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123e2d0)
Location: mm/memory.c:437
Inline: False
Direct callers:
  - mm/memory.c:apply_to_page_range
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8123e2d0-ffffffff8123e3db: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81250170)
Location: mm/memory.c:439
Inline: False
Direct callers:
  - mm/memory.c:apply_to_page_range
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81250170-ffffffff81250263: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125e720)
Location: mm/memory.c:439
Inline: False
Direct callers:
  - mm/memory.c:apply_to_page_range
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8125e720-ffffffff8125e813: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128e740)
Location: mm/memory.c:457
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pte_range
  - mm/vmalloc.c:vmap_pte_range
  - lib/ioremap.c:ioremap_pte_range
```
**Symbols:**

```
ffffffff8128e740-ffffffff8128e833: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81299360)
Location: mm/memory.c:459
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pte_range
  - mm/vmalloc.c:vmap_pte_range
  - mm/ioremap.c:ioremap_pte_range
```
**Symbols:**

```
ffffffff81299360-ffffffff81299453: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129e5f0)
Location: mm/memory.c:471
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pte_range
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff8129e5f0-ffffffff8129e6eb: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812df830)
Location: mm/memory.c:470
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pte_range
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff812df830-ffffffff812df92b: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8133fd80)
Location: mm/memory.c:478
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pte_range
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff8133fd80-ffffffff8133fe87: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813b7cd0)
Location: mm/memory.c:431
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pte_range
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff813b7cd0-ffffffff813b7dd7: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813eca40)
Location: mm/memory.c:450
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pte_range
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff813eca40-ffffffff813ecb47: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81417f30)
Location: mm/memory.c:450
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pte_range
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff81417f30-ffffffff81418096: __pte_alloc_kernel (STB_GLOBAL)
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
int __pte_alloc_kernel(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f60f0)
Location: mm/memory.c:439
Inline: False
Direct callers:
  - mm/memory.c:apply_to_page_range
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffff8000102f60f0-ffff8000102f622c: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c05180d4)
Location: mm/memory.c:439
Inline: False
Direct callers:
  - mm/memory.c:apply_to_page_range
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
c05180d4-c05181ac: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003bda60)
Location: mm/memory.c:439
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/hash_pgtable.c:hash__map_kernel_page
  - arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page
  - mm/memory.c:apply_to_page_range
  - mm/vmalloc.c:vmap_page_range_noflush
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
c0000000003bda60-c0000000003bdba8: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000207312)
Location: mm/memory.c:439
Inline: False
Direct callers:
  - mm/memory.c:apply_to_page_range
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffe000207312-ffffffe0002073d6: __pte_alloc_kernel (STB_GLOBAL)
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
int __pte_alloc_kernel(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256d70)
Location: mm/memory.c:439
Inline: False
Direct callers:
  - mm/memory.c:apply_to_page_range
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81256d70-ffffffff81256e63: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81249710)
Location: mm/memory.c:439
Inline: False
Direct callers:
  - mm/memory.c:apply_to_page_range
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81249710-ffffffff812497b2: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81254b10)
Location: mm/memory.c:439
Inline: False
Direct callers:
  - mm/memory.c:apply_to_page_range
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81254b10-ffffffff81254c03: __pte_alloc_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __pte_alloc_kernel(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81264590)
Location: mm/memory.c:439
Inline: False
Direct callers:
  - mm/memory.c:apply_to_page_range
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81264590-ffffffff8126468f: __pte_alloc_kernel (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int address</code>
</li>
</ul>
</details>
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
