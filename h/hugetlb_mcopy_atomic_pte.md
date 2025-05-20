# Function: <code>hugetlb_mcopy_atomic_pte</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hugetlb_mcopy_atomic_pte(struct mm_struct *dst_mm, pte_t *dst_pte, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81217720)
Location: mm/hugetlb.c:3973
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81217720-ffffffff812179c4: hugetlb_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hugetlb_mcopy_atomic_pte(struct mm_struct *dst_mm, pte_t *dst_pte, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812323d0)
Location: mm/hugetlb.c:3994
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812323d0-ffffffff81232719: hugetlb_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hugetlb_mcopy_atomic_pte(struct mm_struct *dst_mm, pte_t *dst_pte, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81255420)
Location: mm/hugetlb.c:4023
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81255420-ffffffff8125576e: hugetlb_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hugetlb_mcopy_atomic_pte(struct mm_struct *dst_mm, pte_t *dst_pte, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81269800)
Location: mm/hugetlb.c:4063
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81269800-ffffffff81269b4e: hugetlb_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hugetlb_mcopy_atomic_pte(struct mm_struct *dst_mm, pte_t *dst_pte, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81284940)
Location: mm/hugetlb.c:4143
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81284940-ffffffff81284c9b: hugetlb_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hugetlb_mcopy_atomic_pte(struct mm_struct *dst_mm, pte_t *dst_pte, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812944e0)
Location: mm/hugetlb.c:4260
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812944e0-ffffffff8129483b: hugetlb_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hugetlb_mcopy_atomic_pte(struct mm_struct *dst_mm, pte_t *dst_pte, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c78d0)
Location: mm/hugetlb.c:4698
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812c78d0-ffffffff812c7c26: hugetlb_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hugetlb_mcopy_atomic_pte(struct mm_struct *dst_mm, pte_t *dst_pte, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d3440)
Location: mm/hugetlb.c:4688
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812d3440-ffffffff812d378c: hugetlb_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hugetlb_mcopy_atomic_pte(struct mm_struct *dst_mm, pte_t *dst_pte, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, enum mcopy_atomic_mode mode, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812da240)
Location: mm/hugetlb.c:4930
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812da240-ffffffff812da6d2: hugetlb_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hugetlb_mcopy_atomic_pte(struct mm_struct *dst_mm, pte_t *dst_pte, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, enum mcopy_atomic_mode mode, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:5235
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81cbf8ee-ffffffff81cbfad1: hugetlb_mcopy_atomic_pte.cold (STB_LOCAL)
ffffffff81321000-ffffffff8132167f: hugetlb_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hugetlb_mcopy_atomic_pte(struct mm_struct *dst_mm, pte_t *dst_pte, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, enum mcopy_atomic_mode mode, struct page **pagep, bool wp_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:5883
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81e71c77-ffffffff81e71e4e: hugetlb_mcopy_atomic_pte.cold (STB_LOCAL)
ffffffff8138ddd0-ffffffff8138e67d: hugetlb_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hugetlb_mcopy_atomic_pte(struct mm_struct *dst_mm, pte_t *dst_pte, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, enum mcopy_atomic_mode mode, struct page **pagep, bool wp_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:6165
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff82066771-ffffffff82066861: hugetlb_mcopy_atomic_pte.cold (STB_LOCAL)
ffffffff8140cb30-ffffffff8140d0b9: hugetlb_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int hugetlb_mcopy_atomic_pte(struct mm_struct *dst_mm, pte_t *dst_pte, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010332dd8)
Location: mm/hugetlb.c:4260
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffff800010332dd8-ffff800010333160: hugetlb_mcopy_atomic_pte (STB_GLOBAL)
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
int hugetlb_mcopy_atomic_pte(struct mm_struct *dst_mm, pte_t *dst_pte, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c00000000040ecb0)
Location: mm/hugetlb.c:4260
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
c00000000040ecb0-c00000000040f27c: hugetlb_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hugetlb_mcopy_atomic_pte(struct mm_struct *dst_mm, pte_t *dst_pte, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022f4cc)
Location: mm/hugetlb.c:4260
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffe00022f4cc-ffffffe00022f76e: hugetlb_mcopy_atomic_pte (STB_GLOBAL)
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
int hugetlb_mcopy_atomic_pte(struct mm_struct *dst_mm, pte_t *dst_pte, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128cac0)
Location: mm/hugetlb.c:4260
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8128cac0-ffffffff8128ce1b: hugetlb_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hugetlb_mcopy_atomic_pte(struct mm_struct *dst_mm, pte_t *dst_pte, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127e8e0)
Location: mm/hugetlb.c:4260
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8127e8e0-ffffffff8127ec2d: hugetlb_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hugetlb_mcopy_atomic_pte(struct mm_struct *dst_mm, pte_t *dst_pte, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128a8d0)
Location: mm/hugetlb.c:4260
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8128a8d0-ffffffff8128ac2b: hugetlb_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hugetlb_mcopy_atomic_pte(struct mm_struct *dst_mm, pte_t *dst_pte, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8129a6c0)
Location: mm/hugetlb.c:4260
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8129a6c0-ffffffff8129aa14: hugetlb_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>enum mcopy_atomic_mode mode</code>
</li>
<li>
<b>Param reordered. </b>
<code>dst_mm, dst_pte, dst_vma, dst_addr, src_addr, pagep</code> ➡️ <code>dst_mm, dst_pte, dst_vma, dst_addr, src_addr, mode, pagep</code>
</li>
</ul>
</details>
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
<code>bool wp_copy</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
