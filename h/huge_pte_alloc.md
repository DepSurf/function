# Function: <code>huge_pte_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pte_t *huge_pte_alloc(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811de6f0)
Location: mm/hugetlb.c:4280
Inline: False
Direct callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff811de6f0-ffffffff811de7f2: huge_pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pte_t *huge_pte_alloc(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811fcb40)
Location: mm/hugetlb.c:4302
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff811fcb40-ffffffff811fcc56: huge_pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pte_t *huge_pte_alloc(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120d620)
Location: mm/hugetlb.c:4415
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff8120d620-ffffffff8120d736: huge_pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
pte_t *huge_pte_alloc(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81219470)
Location: mm/hugetlb.c:4576
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81219470-ffffffff8121958e: huge_pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pte_t *huge_pte_alloc(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81234470)
Location: mm/hugetlb.c:4636
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81234470-ffffffff812345d7: huge_pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pte_t *huge_pte_alloc(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81257420)
Location: mm/hugetlb.c:4665
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81257420-ffffffff8125755a: huge_pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pte_t *huge_pte_alloc(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8126baa0)
Location: mm/hugetlb.c:4754
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8126baa0-ffffffff8126bbda: huge_pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pte_t *huge_pte_alloc(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81286da0)
Location: mm/hugetlb.c:4859
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81286da0-ffffffff81286eda: huge_pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pte_t *huge_pte_alloc(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812969a0)
Location: mm/hugetlb.c:4976
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812969a0-ffffffff81296ada: huge_pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pte_t *huge_pte_alloc(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c9f00)
Location: mm/hugetlb.c:5463
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812c9f00-ffffffff812ca0a9: huge_pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pte_t *huge_pte_alloc(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d5b40)
Location: mm/hugetlb.c:5475
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812d5b40-ffffffff812d5ce9: huge_pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pte_t *huge_pte_alloc(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812dc800)
Location: mm/hugetlb.c:5755
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812dc800-ffffffff812dca02: huge_pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
pte_t *huge_pte_alloc(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:6092
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81cbff39-ffffffff81cbff55: huge_pte_alloc.cold (STB_LOCAL)
ffffffff813239c0-ffffffff81323bd6: huge_pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
pte_t *huge_pte_alloc(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:6819
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81e7227c-ffffffff81e72298: huge_pte_alloc.cold (STB_LOCAL)
ffffffff813915b0-ffffffff813917d0: huge_pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
pte_t *huge_pte_alloc(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:7158
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff820669a5-ffffffff820669c1: huge_pte_alloc.cold (STB_LOCAL)
ffffffff8140e5b0-ffffffff8140e7b2: huge_pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
pte_t *huge_pte_alloc(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:7252
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_copy
```
**Symbols:**

```
ffffffff820e6190-ffffffff820e61ac: huge_pte_alloc.cold (STB_LOCAL)
ffffffff81441970-ffffffff81441b74: huge_pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
pte_t *huge_pte_alloc(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:7389
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_copy
```
**Symbols:**

```
ffffffff821c331a-ffffffff821c3336: huge_pte_alloc.cold (STB_LOCAL)
ffffffff8147bbe0-ffffffff8147bde4: huge_pte_alloc (STB_GLOBAL)
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
pte_t *huge_pte_alloc(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/hugetlbpage.c (ffff8000100b0df8)
Location: arch/arm64/mm/hugetlbpage.c:216
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffff8000100b0df8-ffff8000100b1008: huge_pte_alloc (STB_GLOBAL)
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
pte_t *huge_pte_alloc(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a5460)
Location: arch/powerpc/mm/hugetlbpage.c:119
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
c0000000000a5460-c0000000000a5a84: huge_pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
pte_t *huge_pte_alloc(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe000231196)
Location: mm/hugetlb.c:4976
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffe000231196-ffffffe000231228: huge_pte_alloc (STB_GLOBAL)
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
pte_t *huge_pte_alloc(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128ef80)
Location: mm/hugetlb.c:4976
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8128ef80-ffffffff8128f0ba: huge_pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pte_t *huge_pte_alloc(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81280c90)
Location: mm/hugetlb.c:4976
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81280c90-ffffffff81280da8: huge_pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pte_t *huge_pte_alloc(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128cd90)
Location: mm/hugetlb.c:4976
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8128cd90-ffffffff8128ceca: huge_pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pte_t *huge_pte_alloc(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8129cb60)
Location: mm/hugetlb.c:4976
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8129cb60-ffffffff8129cc9a: huge_pte_alloc (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, addr, sz</code> ➡️ <code>mm, vma, addr, sz</code>
</li>
</ul>
</details>
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
