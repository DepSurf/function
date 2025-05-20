# Function: <code>pud_set_huge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81071180)
Location: arch/x86/mm/pgtable.c:584
Inline: False
```
**Symbols:**

```
ffffffff81071180-ffffffff81071244: pud_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81071070)
Location: arch/x86/mm/pgtable.c:570
Inline: False
```
**Symbols:**

```
ffffffff81071070-ffffffff81071131: pud_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81074bf0)
Location: arch/x86/mm/pgtable.c:570
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81074bf0-ffffffff81074cb1: pud_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810741c0)
Location: arch/x86/mm/pgtable.c:633
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff810741c0-ffffffff8107427a: pud_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81079c50)
Location: arch/x86/mm/pgtable.c:630
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81079c50-ffffffff81079d0a: pud_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8107c810)
Location: arch/x86/mm/pgtable.c:647
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8107c810-ffffffff8107c92d: pud_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81083240)
Location: arch/x86/mm/pgtable.c:713
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81083240-ffffffff8108335d: pud_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086eb0)
Location: arch/x86/mm/pgtable.c:700
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81086eb0-ffffffff81086fcb: pud_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81087ba0)
Location: arch/x86/mm/pgtable.c:696
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81087ba0-ffffffff81087cbb: pud_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108a040)
Location: arch/x86/mm/pgtable.c:703
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8108a040-ffffffff8108a15a: pud_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108a2c0)
Location: arch/x86/mm/pgtable.c:703
Inline: False
Direct callers:
  - mm/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8108a2c0-ffffffff8108a3d8: pud_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108af20)
Location: arch/x86/mm/pgtable.c:703
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff8108af20-ffffffff8108b038: pud_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8109a4c0)
Location: arch/x86/mm/pgtable.c:703
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff8109a4c0-ffffffff8109a5d8: pud_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810ad720)
Location: arch/x86/mm/pgtable.c:712
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff810ad720-ffffffff810ad84b: pud_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810c78c0)
Location: arch/x86/mm/pgtable.c:719
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff810c78c0-ffffffff810c79eb: pud_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810cb010)
Location: arch/x86/mm/pgtable.c:713
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff810cb010-ffffffff810cb137: pud_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810d3560)
Location: arch/x86/mm/pgtable.c:725
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff810d3560-ffffffff810d3687: pud_set_huge (STB_GLOBAL)
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
int pud_set_huge(pud_t *pudp, phys_addr_t phys, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/mmu.c (ffff8000100ae860)
Location: arch/arm64/mm/mmu.c:956
Inline: False
Direct callers:
  - arch/arm64/mm/mmu.c:alloc_init_pud
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffff8000100ae860-ffff8000100ae8dc: pud_set_huge (STB_GLOBAL)
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
Location: include/asm-generic/pgtable.h:1067
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000095840)
Location: arch/powerpc/mm/book3s64/radix_pgtable.c:1100
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
c000000000095840-c0000000000958c8: pud_set_huge (STB_GLOBAL)
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
Location: include/asm-generic/pgtable.h:1067
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
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086ba0)
Location: arch/x86/mm/pgtable.c:696
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81086ba0-ffffffff81086cbb: pud_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81075820)
Location: arch/x86/mm/pgtable.c:696
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81075820-ffffffff8107592e: pud_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086b50)
Location: arch/x86/mm/pgtable.c:696
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81086b50-ffffffff81086c6b: pud_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pud_set_huge(pud_t *pud, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81088c80)
Location: arch/x86/mm/pgtable.c:696
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81088c80-ffffffff81088d9b: pud_set_huge (STB_GLOBAL)
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
<b>Param added. </b>
<code>phys_addr_t phys</code>
</li>
<li>
<b>Param removed. </b>
<code>pud_t *pud</code>
</li>
<li>
<b>Param removed. </b>
<code>phys_addr_t addr</code>
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
