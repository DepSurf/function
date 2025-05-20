# Function: <code>__anon_vma_prepare</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811fa160)
Location: mm/rmap.c:171
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff811fa160-ffffffff811fa2d4: __anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81204e50)
Location: mm/rmap.c:173
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81204e50-ffffffff81204fc7: __anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121de00)
Location: mm/rmap.c:174
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8121de00-ffffffff8121df77: __anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8123fd50)
Location: mm/rmap.c:175
Inline: False
Direct callers:
  - kernel/fork.c:copy_mm
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8123fd50-ffffffff8123fec7: __anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812543d0)
Location: mm/rmap.c:175
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812543d0-ffffffff81254547: __anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81266690)
Location: mm/rmap.c:175
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81266690-ffffffff81266808: __anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81274fb0)
Location: mm/rmap.c:176
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81274fb0-ffffffff81275128: __anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812a63d0)
Location: mm/rmap.c:182
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812a63d0-ffffffff812a6548: __anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b1850)
Location: mm/rmap.c:182
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812b1850-ffffffff812b19c8: __anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b6f20)
Location: mm/rmap.c:182
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812b6f20-ffffffff812b7098: __anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812f9340)
Location: mm/rmap.c:183
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812f9340-ffffffff812f94b8: __anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8135fbe0)
Location: mm/rmap.c:187
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8135fbe0-ffffffff8135fd5c: __anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813daa60)
Location: mm/rmap.c:187
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff813daa60-ffffffff813dabd6: __anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8140f1a0)
Location: mm/rmap.c:188
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
```
**Symbols:**

```
ffffffff8140f1a0-ffffffff8140f319: __anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8143bb60)
Location: mm/rmap.c:188
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
```
**Symbols:**

```
ffffffff8143bb60-ffffffff8143bcd9: __anon_vma_prepare (STB_GLOBAL)
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
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffff80001030acd0)
Location: mm/rmap.c:176
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffff80001030acd0-ffff80001030ae9c: __anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c05271c8)
Location: mm/rmap.c:176
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
c05271c8-c0527350: __anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0000000003dab60)
Location: mm/rmap.c:176
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
c0000000003dab60-c0000000003daddc: __anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffe0002143ae)
Location: mm/rmap.c:176
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffe0002143ae-ffffffe000214544: __anon_vma_prepare (STB_GLOBAL)
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
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126d600)
Location: mm/rmap.c:176
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8126d600-ffffffff8126d778: __anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125f630)
Location: mm/rmap.c:176
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8125f630-ffffffff8125f7a8: __anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126b3a0)
Location: mm/rmap.c:176
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8126b3a0-ffffffff8126b518: __anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8127ad10)
Location: mm/rmap.c:176
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8127ad10-ffffffff8127ae72: __anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
