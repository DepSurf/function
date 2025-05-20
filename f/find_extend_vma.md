# Function: <code>find_extend_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c63a0)
Location: mm/mmap.c:2347
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:fixup_user_fault
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff811c63a0-ffffffff811c6418: find_extend_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e2e70)
Location: mm/mmap.c:2244
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff811e2e70-ffffffff811e2ee8: find_extend_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f2e50)
Location: mm/mmap.c:2397
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff811f2e50-ffffffff811f2ec8: find_extend_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fdd80)
Location: mm/mmap.c:2432
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff811fdd80-ffffffff811fddf8: find_extend_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81216330)
Location: mm/mmap.c:2448
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81216330-ffffffff812163a8: find_extend_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81237100)
Location: mm/mmap.c:2508
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81237100-ffffffff81237178: find_extend_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8124a9b0)
Location: mm/mmap.c:2542
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff8124a9b0-ffffffff8124aa28: find_extend_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125cd20)
Location: mm/mmap.c:2544
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff8125cd20-ffffffff8125cdb0: find_extend_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126b4f0)
Location: mm/mmap.c:2549
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff8126b4f0-ffffffff8126b580: find_extend_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129ac20)
Location: mm/mmap.c:2547
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff8129ac20-ffffffff8129acb0: find_extend_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a5df0)
Location: mm/mmap.c:2613
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff812a5df0-ffffffff812a5e6f: find_extend_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ac4f0)
Location: mm/mmap.c:2617
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff812ac4f0-ffffffff812ac56f: find_extend_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812edc40)
Location: mm/mmap.c:2587
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - drivers/iommu/io-pgfault.c:iopf_handle_single
```
**Symbols:**

```
ffffffff812edc40-ffffffff812edcbf: find_extend_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81351020)
Location: mm/mmap.c:2608
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - drivers/iommu/io-pgfault.c:iopf_handle_single
```
**Symbols:**

```
ffffffff81351020-ffffffff813510bc: find_extend_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813cb490)
Location: mm/mmap.c:2124
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
**Symbols:**

```
ffffffff813cb490-ffffffff813cb53e: find_extend_vma (STB_GLOBAL)
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
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010302c98)
Location: mm/mmap.c:2549
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffff800010302c98-ffff800010302d50: find_extend_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c05212f4)
Location: mm/mmap.c:2549
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
c05212f4-c0521390: find_extend_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cf400)
Location: mm/mmap.c:2549
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
c0000000003cf400-c0000000003cf51c: find_extend_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020fa02)
Location: mm/mmap.c:2549
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
```
**Symbols:**

```
ffffffe00020fa02-ffffffe00020fa8a: find_extend_vma (STB_GLOBAL)
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
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81263b40)
Location: mm/mmap.c:2549
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81263b40-ffffffff81263bd0: find_extend_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81255f60)
Location: mm/mmap.c:2549
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81255f60-ffffffff81255ff0: find_extend_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812618e0)
Location: mm/mmap.c:2549
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff812618e0-ffffffff81261970: find_extend_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vm_area_struct *find_extend_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812712a0)
Location: mm/mmap.c:2549
Inline: False
Direct callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - drivers/iommu/intel-svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff812712a0-ffffffff81271330: find_extend_vma (STB_GLOBAL)
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
