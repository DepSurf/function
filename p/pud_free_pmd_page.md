# Function: <code>pud_free_pmd_page</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
int pud_free_pmd_page(pud_t *pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81079ec0)
Location: arch/x86/mm/pgtable.c:713
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81079ec0-ffffffff81079f8f: pud_free_pmd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pud_free_pmd_page(pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8107cb20)
Location: arch/x86/mm/pgtable.c:742
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8107cb20-ffffffff8107ccb1: pud_free_pmd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pud_free_pmd_page(pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81083560)
Location: arch/x86/mm/pgtable.c:816
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81083560-ffffffff810836df: pud_free_pmd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pud_free_pmd_page(pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810871d0)
Location: arch/x86/mm/pgtable.c:803
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff810871d0-ffffffff8108734f: pud_free_pmd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pud_free_pmd_page(pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81087ec0)
Location: arch/x86/mm/pgtable.c:799
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81087ec0-ffffffff8108803f: pud_free_pmd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pud_free_pmd_page(pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108a360)
Location: arch/x86/mm/pgtable.c:802
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8108a360-ffffffff8108a4dc: pud_free_pmd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pud_free_pmd_page(pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108a5d0)
Location: arch/x86/mm/pgtable.c:802
Inline: False
Direct callers:
  - mm/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8108a5d0-ffffffff8108a7ac: pud_free_pmd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pud_free_pmd_page(pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108b220)
Location: arch/x86/mm/pgtable.c:794
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff8108b220-ffffffff8108b3d6: pud_free_pmd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pud_free_pmd_page(pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8109a7c0)
Location: arch/x86/mm/pgtable.c:794
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff8109a7c0-ffffffff8109a976: pud_free_pmd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pud_free_pmd_page(pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810ada90)
Location: arch/x86/mm/pgtable.c:803
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff810ada90-ffffffff810adc61: pud_free_pmd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pud_free_pmd_page(pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810c7ca0)
Location: arch/x86/mm/pgtable.c:810
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff810c7ca0-ffffffff810c7e78: pud_free_pmd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pud_free_pmd_page(pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810cb3e0)
Location: arch/x86/mm/pgtable.c:802
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff810cb3e0-ffffffff810cb5b8: pud_free_pmd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pud_free_pmd_page(pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810d3930)
Location: arch/x86/mm/pgtable.c:814
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff810d3930-ffffffff810d3b17: pud_free_pmd_page (STB_GLOBAL)
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
int pud_free_pmd_page(pud_t *pudp, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/mmu.c (ffff8000100af4a0)
Location: arch/arm64/mm/mmu.c:1019
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffff8000100af4a0-ffff8000100af594: pud_free_pmd_page (STB_GLOBAL)
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
Location: include/asm-generic/pgtable.h:1091
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pud_free_pmd_page(pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000095900)
Location: arch/powerpc/mm/book3s64/radix_pgtable.c:1123
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
c000000000095900-c000000000095a60: pud_free_pmd_page (STB_GLOBAL)
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
Location: include/asm-generic/pgtable.h:1091
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
int pud_free_pmd_page(pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086ec0)
Location: arch/x86/mm/pgtable.c:799
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81086ec0-ffffffff8108703f: pud_free_pmd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pud_free_pmd_page(pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81075b00)
Location: arch/x86/mm/pgtable.c:799
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81075b00-ffffffff81075c2a: pud_free_pmd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pud_free_pmd_page(pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086e70)
Location: arch/x86/mm/pgtable.c:799
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81086e70-ffffffff81086fef: pud_free_pmd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pud_free_pmd_page(pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81088fa0)
Location: arch/x86/mm/pgtable.c:799
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81088fa0-ffffffff8108911f: pud_free_pmd_page (STB_GLOBAL)
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
<code>pud_t *pudp</code>
</li>
<li>
<b>Param removed. </b>
<code>pud_t *pud</code>
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
