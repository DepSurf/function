# Function: <code>pmd_set_huge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81071250)
Location: arch/x86/mm/pgtable.c:609
Inline: False
```
**Symbols:**

```
ffffffff81071250-ffffffff81071345: pmd_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81071140)
Location: arch/x86/mm/pgtable.c:595
Inline: False
```
**Symbols:**

```
ffffffff81071140-ffffffff81071232: pmd_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81074cc0)
Location: arch/x86/mm/pgtable.c:595
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81074cc0-ffffffff81074db2: pmd_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81074280)
Location: arch/x86/mm/pgtable.c:658
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81074280-ffffffff8107436d: pmd_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81079d10)
Location: arch/x86/mm/pgtable.c:655
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81079d10-ffffffff81079dfd: pmd_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:676
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8107cd50-ffffffff8107cd77: pmd_set_huge.cold.18 (STB_LOCAL)
ffffffff8107c930-ffffffff8107ca64: pmd_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:742
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81083762-ffffffff81083789: pmd_set_huge.cold.26 (STB_LOCAL)
ffffffff81083360-ffffffff81083494: pmd_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:729
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff810873d3-ffffffff810873fa: pmd_set_huge.cold (STB_LOCAL)
ffffffff81086fd0-ffffffff81087106: pmd_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:725
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff810880c3-ffffffff810880ea: pmd_set_huge.cold (STB_LOCAL)
ffffffff81087cc0-ffffffff81087df6: pmd_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:730
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8108a560-ffffffff8108a587: pmd_set_huge.cold (STB_LOCAL)
ffffffff8108a160-ffffffff8108a295: pmd_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:730
Inline: False
Direct callers:
  - mm/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81bd97b6-ffffffff81bd97dd: pmd_set_huge.cold (STB_LOCAL)
ffffffff8108a3e0-ffffffff8108a513: pmd_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:730
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff81bcb81e-ffffffff81bcb845: pmd_set_huge.cold (STB_LOCAL)
ffffffff8108b040-ffffffff8108b173: pmd_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:730
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff81ca1140-ffffffff81ca117b: pmd_set_huge.cold (STB_LOCAL)
ffffffff8109a5e0-ffffffff8109a71f: pmd_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:739
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff81e50741-ffffffff81e5077a: pmd_set_huge.cold (STB_LOCAL)
ffffffff810ad850-ffffffff810ad99e: pmd_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:746
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff82054beb-ffffffff82054bff: pmd_set_huge.cold (STB_LOCAL)
ffffffff810c7a00-ffffffff810c7b6e: pmd_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:739
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff820d31cf-ffffffff820d31e4: pmd_set_huge.cold (STB_LOCAL)
ffffffff810cb150-ffffffff810cb2c0: pmd_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:751
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_range_noflush
```
**Symbols:**

```
ffffffff821ae03d-ffffffff821ae052: pmd_set_huge.cold (STB_LOCAL)
ffffffff810d36a0-ffffffff810d3810: pmd_set_huge (STB_GLOBAL)
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
int pmd_set_huge(pmd_t *pmdp, phys_addr_t phys, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/mmu.c (ffff8000100ae8e0)
Location: arch/arm64/mm/mmu.c:970
Inline: False
Direct callers:
  - arch/arm64/mm/mmu.c:vmemmap_populate
  - arch/arm64/mm/mmu.c:init_pmd
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffff8000100ae8e0-ffff8000100ae95c: pmd_set_huge (STB_GLOBAL)
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
Location: include/asm-generic/pgtable.h:1071
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000095a60)
Location: arch/powerpc/mm/book3s64/radix_pgtable.c:1147
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
c000000000095a60-c000000000095ae8: pmd_set_huge (STB_GLOBAL)
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
Location: include/asm-generic/pgtable.h:1071
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:725
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff810870c3-ffffffff810870ea: pmd_set_huge.cold (STB_LOCAL)
ffffffff81086cc0-ffffffff81086df6: pmd_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:725
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81075c92-ffffffff81075cb9: pmd_set_huge.cold (STB_LOCAL)
ffffffff81075930-ffffffff81075a53: pmd_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:725
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81087073-ffffffff8108709a: pmd_set_huge.cold (STB_LOCAL)
ffffffff81086c70-ffffffff81086da6: pmd_set_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pmd_set_huge(pmd_t *pmd, phys_addr_t addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:725
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff810891a3-ffffffff810891ca: pmd_set_huge.cold (STB_LOCAL)
ffffffff81088da0-ffffffff81088ed6: pmd_set_huge (STB_GLOBAL)
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
<code>pmd_t *pmdp</code>
</li>
<li>
<b>Param added. </b>
<code>phys_addr_t phys</code>
</li>
<li>
<b>Param removed. </b>
<code>pmd_t *pmd</code>
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
