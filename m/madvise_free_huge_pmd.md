# Function: <code>madvise_free_huge_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81218210)
Location: mm/huge_memory.c:1256
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff81218210-ffffffff81218511: madvise_free_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8122a7b0)
Location: mm/huge_memory.c:1345
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff8122a7b0-ffffffff8122aaae: madvise_free_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812363d0)
Location: mm/huge_memory.c:1561
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff812363d0-ffffffff81236660: madvise_free_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81255250)
Location: mm/huge_memory.c:1612
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff81255250-ffffffff8125561f: madvise_free_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812790a0)
Location: mm/huge_memory.c:1610
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff812790a0-ffffffff8127946c: madvise_free_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8128d750)
Location: mm/huge_memory.c:1632
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff8128d750-ffffffff8128daf0: madvise_free_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a80c0)
Location: mm/huge_memory.c:1690
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff812a80c0-ffffffff812a8475: madvise_free_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b95a0)
Location: mm/huge_memory.c:1695
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff812b95a0-ffffffff812b9955: madvise_free_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ee100)
Location: mm/huge_memory.c:1554
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff812ee100-ffffffff812ee4b6: madvise_free_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f9770)
Location: mm/huge_memory.c:1575
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff812f9770-ffffffff812f9b23: madvise_free_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ffd40)
Location: mm/huge_memory.c:1580
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff812ffd40-ffffffff813000a0: madvise_free_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81349990)
Location: mm/huge_memory.c:1501
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff81349990-ffffffff81349ced: madvise_free_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813c01a0)
Location: mm/huge_memory.c:1506
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff813c01a0-ffffffff813c05d3: madvise_free_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814424a0)
Location: mm/huge_memory.c:1601
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff814424a0-ffffffff8144289b: madvise_free_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81477c90)
Location: mm/huge_memory.c:1585
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff81477c90-ffffffff8147802a: madvise_free_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a7410)
Location: mm/huge_memory.c:1800
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff814a7410-ffffffff814a7775: madvise_free_huge_pmd (STB_GLOBAL)
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
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff800010359dc0)
Location: mm/huge_memory.c:1695
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffff800010359dc0-ffff80001035a0c0: madvise_free_huge_pmd (STB_GLOBAL)
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
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c000000000443580)
Location: mm/huge_memory.c:1695
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
c000000000443580-c000000000443ad0: madvise_free_huge_pmd (STB_GLOBAL)
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
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b1b80)
Location: mm/huge_memory.c:1695
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff812b1b80-ffffffff812b1f35: madvise_free_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a2f50)
Location: mm/huge_memory.c:1695
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff812a2f50-ffffffff812a32c4: madvise_free_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812af990)
Location: mm/huge_memory.c:1695
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff812af990-ffffffff812afd45: madvise_free_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool madvise_free_huge_pmd(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812bfcd0)
Location: mm/huge_memory.c:1695
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff812bfcd0-ffffffff812c0088: madvise_free_huge_pmd (STB_GLOBAL)
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
