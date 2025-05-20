# Function: <code>pmd_free_pte_page</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pmd_free_pte_page(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81079f38)
Location: arch/x86/mm/pgtable.c:740
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
Direct callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81079540-ffffffff810795b2: pmd_free_pte_page.part.17 (STB_LOCAL)
ffffffff81079f90-ffffffff81079fb4: pmd_free_pte_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pmd_free_pte_page(pmd_t *pmd, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8107ccc0)
Location: arch/x86/mm/pgtable.c:788
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8107ccc0-ffffffff8107cd50: pmd_free_pte_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pmd_free_pte_page(pmd_t *pmd, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810836e0)
Location: arch/x86/mm/pgtable.c:859
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff810836e0-ffffffff81083762: pmd_free_pte_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pmd_free_pte_page(pmd_t *pmd, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81087350)
Location: arch/x86/mm/pgtable.c:846
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81087350-ffffffff810873d3: pmd_free_pte_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pmd_free_pte_page(pmd_t *pmd, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81088040)
Location: arch/x86/mm/pgtable.c:842
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81088040-ffffffff810880c3: pmd_free_pte_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pmd_free_pte_page(pmd_t *pmd, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108a4e0)
Location: arch/x86/mm/pgtable.c:845
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8108a4e0-ffffffff8108a560: pmd_free_pte_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pmd_free_pte_page(pmd_t *pmd, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108a7b0)
Location: arch/x86/mm/pgtable.c:847
Inline: False
Direct callers:
  - mm/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8108a7b0-ffffffff8108a826: pmd_free_pte_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pmd_free_pte_page(pmd_t *pmd, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108b3e0)
Location: arch/x86/mm/pgtable.c:839
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff8108b3e0-ffffffff8108b456: pmd_free_pte_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pmd_free_pte_page(pmd_t *pmd, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8109a980)
Location: arch/x86/mm/pgtable.c:839
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff8109a980-ffffffff8109a9f6: pmd_free_pte_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pmd_free_pte_page(pmd_t *pmd, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810adc70)
Location: arch/x86/mm/pgtable.c:848
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff810adc70-ffffffff810adcfb: pmd_free_pte_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pmd_free_pte_page(pmd_t *pmd, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810c7e90)
Location: arch/x86/mm/pgtable.c:855
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff810c7e90-ffffffff810c7f22: pmd_free_pte_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pmd_free_pte_page(pmd_t *pmd, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810cb5d0)
Location: arch/x86/mm/pgtable.c:847
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff810cb5d0-ffffffff810cb662: pmd_free_pte_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pmd_free_pte_page(pmd_t *pmd, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810d3b30)
Location: arch/x86/mm/pgtable.c:859
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff810d3b30-ffffffff810d3bc2: pmd_free_pte_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pmd_free_pte_page(pmd_t *pmdp, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm64/mm/mmu.c (ffff8000100af514)
Location: arch/arm64/mm/mmu.c:1000
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:pud_free_pmd_page
Direct callers:
  - arch/arm64/mm/mmu.c:pud_free_pmd_page
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffff8000100ae430-ffff8000100ae4a0: pmd_free_pte_page.part.0 (STB_LOCAL)
ffff8000100af448-ffff8000100af4a0: pmd_free_pte_page (STB_GLOBAL)
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
In lib/ioremap.c (0)
Location: include/asm-generic/pgtable.h:1095
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pmd_free_pte_page(pmd_t *pmd, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000095b20)
Location: arch/powerpc/mm/book3s64/radix_pgtable.c:1170
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
c000000000095b20-c000000000095bb8: pmd_free_pte_page (STB_GLOBAL)
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
In lib/ioremap.c (0)
Location: include/asm-generic/pgtable.h:1095
Inline: True
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
int pmd_free_pte_page(pmd_t *pmd, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81087040)
Location: arch/x86/mm/pgtable.c:842
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81087040-ffffffff810870c3: pmd_free_pte_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pmd_free_pte_page(pmd_t *pmd, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81075c30)
Location: arch/x86/mm/pgtable.c:842
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81075c30-ffffffff81075c92: pmd_free_pte_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pmd_free_pte_page(pmd_t *pmd, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086ff0)
Location: arch/x86/mm/pgtable.c:842
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81086ff0-ffffffff81087073: pmd_free_pte_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pmd_free_pte_page(pmd_t *pmd, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089120)
Location: arch/x86/mm/pgtable.c:842
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81089120-ffffffff810891a3: pmd_free_pte_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int addr</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>pmd_t *pmdp</code>
</li>
<li>
<b>Param removed. </b>
<code>pmd_t *pmd</code>
</li>
</ul>
</details>
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
