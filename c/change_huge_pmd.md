# Function: <code>change_huge_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int change_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff811f6c80)
Location: mm/huge_memory.c:1554
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff811f6c80-ffffffff811f6ec0: change_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int change_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81215b50)
Location: mm/huge_memory.c:1422
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff81215b50-ffffffff81215d77: change_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int change_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81228170)
Location: mm/huge_memory.c:1547
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff81228170-ffffffff81228391: change_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int change_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81234330)
Location: mm/huge_memory.c:1759
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff81234330-ffffffff81234599: change_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int change_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81252090)
Location: mm/huge_memory.c:1844
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff81252090-ffffffff81252497: change_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int change_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81276590)
Location: mm/huge_memory.c:1842
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
ffffffff81276590-ffffffff812768bc: change_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int change_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8128b470)
Location: mm/huge_memory.c:1862
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff8128b470-ffffffff8128b7c4: change_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int change_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a6070)
Location: mm/huge_memory.c:1920
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff812a6070-ffffffff812a63d2: change_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int change_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b7540)
Location: mm/huge_memory.c:1925
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff812b7540-ffffffff812b78a2: change_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int change_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ec6e0)
Location: mm/huge_memory.c:1784
Inline: False
```
**Symbols:**

```
ffffffff812ec6e0-ffffffff812eca64: change_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int change_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f7770)
Location: mm/huge_memory.c:1799
Inline: False
```
**Symbols:**

```
ffffffff812f7770-ffffffff812f7af5: change_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int change_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812fdc60)
Location: mm/huge_memory.c:1804
Inline: False
```
**Symbols:**

```
ffffffff812fdc60-ffffffff812fe0a5: change_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int change_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81347800)
Location: mm/huge_memory.c:1723
Inline: False
```
**Symbols:**

```
ffffffff81347800-ffffffff81347c45: change_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int change_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813bdab0)
Location: mm/huge_memory.c:1728
Inline: False
```
**Symbols:**

```
ffffffff813bdab0-ffffffff813be0c0: change_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int change_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814402d0)
Location: mm/huge_memory.c:1823
Inline: False
```
**Symbols:**

```
ffffffff814402d0-ffffffff814408d5: change_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int change_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81475b10)
Location: mm/huge_memory.c:1808
Inline: False
```
**Symbols:**

```
ffffffff81475b10-ffffffff81476188: change_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int change_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a54e0)
Location: mm/huge_memory.c:2024
Inline: False
```
**Symbols:**

```
ffffffff814a54e0-ffffffff814a5a36: change_huge_pmd (STB_GLOBAL)
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
int change_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff800010358168)
Location: mm/huge_memory.c:1925
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffff800010358168-ffff800010358374: change_huge_pmd (STB_GLOBAL)
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
int change_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c0000000004408a0)
Location: mm/huge_memory.c:1925
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
c0000000004408a0-c000000000440bd8: change_huge_pmd (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int change_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812afb20)
Location: mm/huge_memory.c:1925
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff812afb20-ffffffff812afe82: change_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int change_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a1000)
Location: mm/huge_memory.c:1925
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff812a1000-ffffffff812a1367: change_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int change_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ad930)
Location: mm/huge_memory.c:1925
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff812ad930-ffffffff812adc92: change_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int change_huge_pmd(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, pgprot_t newprot, int prot_numa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812bdca0)
Location: mm/huge_memory.c:1925
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff812bdca0-ffffffff812bdff8: change_huge_pmd (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int cp_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int prot_numa</code>
</li>
</ul>
</details>
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
<code>struct mmu_gather *tlb</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, pmd, addr, newprot, cp_flags</code> ➡️ <code>tlb, vma, pmd, addr, newprot, cp_flags</code>
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
