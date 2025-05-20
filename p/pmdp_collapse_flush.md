# Function: <code>pmdp_collapse_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff811d06c0)
Location: mm/pgtable-generic.c:201
Inline: False
Direct callers:
  - mm/huge_memory.c:khugepaged
```
**Symbols:**

```
ffffffff811d06c0-ffffffff811d0708: pmdp_collapse_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff811ed830)
Location: mm/pgtable-generic.c:172
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff811ed830-ffffffff811ed859: pmdp_collapse_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff811f7c00)
Location: mm/pgtable-generic.c:172
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff811f7c00-ffffffff811f7c29: pmdp_collapse_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (0)
Location: mm/pgtable-generic.c:192
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81202df0-ffffffff81202e00: pmdp_collapse_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (0)
Location: mm/pgtable-generic.c:194
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff8121bb30-ffffffff8121bb40: pmdp_collapse_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (0)
Location: mm/pgtable-generic.c:194
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8123d980-ffffffff8123d990: pmdp_collapse_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (0)
Location: mm/pgtable-generic.c:195
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81251f50-ffffffff81251f60: pmdp_collapse_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81264240)
Location: mm/pgtable-generic.c:195
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81264240-ffffffff81264296: pmdp_collapse_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81272ab0)
Location: mm/pgtable-generic.c:195
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81272ab0-ffffffff81272b06: pmdp_collapse_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (0)
Location: mm/pgtable-generic.c:204
Inline: False
Direct callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812a3880-ffffffff812a38d8: pmdp_collapse_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (0)
Location: mm/pgtable-generic.c:204
Inline: False
Direct callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812af150-ffffffff812af1a8: pmdp_collapse_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (0)
Location: mm/pgtable-generic.c:204
Inline: False
Direct callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812b4600-ffffffff812b465b: pmdp_collapse_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (0)
Location: mm/pgtable-generic.c:204
Inline: False
Direct callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812f61e0-ffffffff812f623b: pmdp_collapse_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (0)
Location: mm/pgtable-generic.c:213
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8135a200-ffffffff8135a268: pmdp_collapse_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (0)
Location: mm/pgtable-generic.c:213
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff813d4c90-ffffffff813d4cf5: pmdp_collapse_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (0)
Location: mm/pgtable-generic.c:215
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff814096f0-ffffffff8140975b: pmdp_collapse_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (0)
Location: mm/pgtable-generic.c:216
Inline: False
Direct callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81435ee0-ffffffff81435f4b: pmdp_collapse_flush (STB_GLOBAL)
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
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (0)
Location: mm/pgtable-generic.c:195
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffff800010308570-ffff8000103085b0: pmdp_collapse_flush (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (c0000000004492f8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1254
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
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
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8126b100)
Location: mm/pgtable-generic.c:195
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8126b100-ffffffff8126b156: pmdp_collapse_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8125d110)
Location: mm/pgtable-generic.c:195
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8125d110-ffffffff8125d166: pmdp_collapse_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81268ea0)
Location: mm/pgtable-generic.c:195
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81268ea0-ffffffff81268ef6: pmdp_collapse_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pmd_t pmdp_collapse_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81278830)
Location: mm/pgtable-generic.c:195
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81278830-ffffffff81278886: pmdp_collapse_flush (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
