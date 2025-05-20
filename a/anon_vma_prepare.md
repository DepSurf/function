# Function: <code>anon_vma_prepare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811cbda0)
Location: mm/rmap.c:169
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/mmap.c:expand_downwards
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_fault
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffffffff811cbda0-ffffffff811cbf11: anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int anon_vma_prepare(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811e8f70)
Location: mm/rmap.c:170
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
ffffffff811e8f70-ffffffff811e90f2: anon_vma_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811a92e7)
Location: include/linux/rmap.h:146
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811eb3dd)
Location: include/linux/rmap.h:146
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (ffffffff811f2b46)
Location: include/linux/rmap.h:146
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (ffffffff8120e35f)
Location: include/linux/rmap.h:146
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/huge_memory.c (ffffffff812267f0)
Location: include/linux/rmap.h:146
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff8123fcb6)
Location: include/linux/rmap.h:146
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811b0864)
Location: include/linux/rmap.h:144
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811f5df0)
Location: include/linux/rmap.h:144
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (ffffffff811fdb05)
Location: include/linux/rmap.h:144
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (ffffffff81218ba5)
Location: include/linux/rmap.h:144
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/huge_memory.c (ffffffff81232673)
Location: include/linux/rmap.h:144
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff8124bbf6)
Location: include/linux/rmap.h:144
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81089042)
Location: include/linux/rmap.h:148
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff811c436b)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff8120da4c)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (ffffffff812160b5)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (ffffffff81233b56)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff8124a0ad)
Location: include/linux/rmap.h:148
Inline: True
```
```
In mm/huge_memory.c (ffffffff8124fd35)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff8126bf5f)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108b990)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/fork.c:copy_mm
```
```
In kernel/events/uprobes.c (ffffffff811e4879)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff8122e1c7)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (ffffffff81236e6d)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (ffffffff81256a54)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff8126f010)
Location: include/linux/rmap.h:148
Inline: True
```
```
In mm/huge_memory.c (ffffffff812742b1)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff81290b5b)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81095492)
Location: include/linux/rmap.h:148
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff811f56d5)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff812422d6)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (ffffffff8124a71d)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (ffffffff8126afb4)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812836c0)
Location: include/linux/rmap.h:148
Inline: True
```
```
In mm/huge_memory.c (ffffffff812892df)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff812a5b8a)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810977be)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/events/uprobes.c (ffffffff8120d453)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff81253aa7)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (ffffffff8125ca86)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (ffffffff812862ac)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/huge_memory.c (ffffffff812a3e83)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff812c1270)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109de7e)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/events/uprobes.c (ffffffff8121a8e3)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff81262007)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (ffffffff8126b1e6)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (ffffffff81295e8c)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812af142)
Location: include/linux/rmap.h:148
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b5383)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff812d31c0)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812472da)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff81291e01)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (ffffffff8129a8e6)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (ffffffff812c9396)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812e51cf)
Location: include/linux/rmap.h:148
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ea817)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff81308ead)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81251956)
Location: include/linux/rmap.h:147
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff8129c6c1)
Location: include/linux/rmap.h:147
Inline: True
Inline callers:
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (ffffffff812a5ab6)
Location: include/linux/rmap.h:147
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (ffffffff812d4fb5)
Location: include/linux/rmap.h:147
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812f0592)
Location: include/linux/rmap.h:147
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f5c77)
Location: include/linux/rmap.h:147
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff81314d37)
Location: include/linux/rmap.h:147
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81255788)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff812a1f41)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (ffffffff812ac1f6)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (ffffffff812dbd6d)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812f68a9)
Location: include/linux/rmap.h:148
Inline: True
```
```
In mm/huge_memory.c (ffffffff812fc0e3)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff8131b3ce)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81291438)
Location: include/linux/rmap.h:144
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff812e2e7d)
Location: include/linux/rmap.h:144
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (ffffffff812ed946)
Location: include/linux/rmap.h:144
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (ffffffff81322f8c)
Location: include/linux/rmap.h:144
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff81340ef3)
Location: include/linux/rmap.h:144
Inline: True
```
```
In mm/huge_memory.c (ffffffff81345f37)
Location: include/linux/rmap.h:144
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff813686be)
Location: include/linux/rmap.h:144
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e6a27)
Location: include/linux/rmap.h:154
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff813437ad)
Location: include/linux/rmap.h:154
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (ffffffff81350cea)
Location: include/linux/rmap.h:154
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (ffffffff8139080f)
Location: include/linux/rmap.h:154
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
```
```
In mm/migrate_device.c (ffffffff813b7dc5)
Location: include/linux/rmap.h:154
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bc167)
Location: include/linux/rmap.h:154
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff813e5edd)
Location: include/linux/rmap.h:154
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81350517)
Location: include/linux/rmap.h:154
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff813bb83a)
Location: include/linux/rmap.h:154
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (ffffffff813cb1b3)
Location: include/linux/rmap.h:154
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (ffffffff8141101f)
Location: include/linux/rmap.h:154
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
```
```
In mm/migrate_device.c (ffffffff81439a9f)
Location: include/linux/rmap.h:154
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143e721)
Location: include/linux/rmap.h:154
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff8146d97e)
Location: include/linux/rmap.h:154
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81381743)
Location: include/linux/rmap.h:154
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff813f0271)
Location: include/linux/rmap.h:154
Inline: True
Inline callers:
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (ffffffff813ff89e)
Location: include/linux/rmap.h:154
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (ffffffff81444591)
Location: include/linux/rmap.h:154
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
```
```
In mm/migrate_device.c (ffffffff8146e7cd)
Location: include/linux/rmap.h:154
Inline: True
```
```
In mm/huge_memory.c (ffffffff81473f04)
Location: include/linux/rmap.h:154
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff814a23d7)
Location: include/linux/rmap.h:154
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813aaad0)
Location: include/linux/rmap.h:159
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff8141fa99)
Location: include/linux/rmap.h:159
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/mmap.c (ffffffff8142be14)
Location: include/linux/rmap.h:159
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (ffffffff8147e665)
Location: include/linux/rmap.h:159
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
```
```
In mm/migrate_device.c (ffffffff8149d23a)
Location: include/linux/rmap.h:159
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/huge_memory.c (ffffffff814a3404)
Location: include/linux/rmap.h:159
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff814d31b2)
Location: include/linux/rmap.h:159
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f2b00)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/events/uprobes.c (ffff8000102a5ca4)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffff8000102f92c0)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (ffff800010302920)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (ffff800010334b0c)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/huge_memory.c (ffff8000103568ac)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffff800010378bac)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0351348)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/events/uprobes.c (c04d5070)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (c051b6fc)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (c0520fe0)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/userfaultfd.c (c056419c)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c000000000138698)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/events/uprobes.c (c000000000358ce0)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (c0000000003c2e9c)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (c0000000003cefb4)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (c00000000040dfe8)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (c00000000043294c)
Location: include/linux/rmap.h:148
Inline: True
```
```
In mm/huge_memory.c (c00000000043dc34)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (c00000000046bd78)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000bf6be)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffffffe0002092b8)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (ffffffe00020f762)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (ffffffe000230ada)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/userfaultfd.c (ffffffe0002505f8)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109779e)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/events/uprobes.c (ffffffff81212f33)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff8125a657)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (ffffffff81263836)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (ffffffff8128e46c)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812a7722)
Location: include/linux/rmap.h:148
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ad963)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff812cb7a0)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108621e)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/events/uprobes.c (ffffffff81205ca3)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff8124ca77)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (ffffffff81255c56)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (ffffffff812801f0)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff81299142)
Location: include/linux/rmap.h:148
Inline: True
```
```
In mm/huge_memory.c (ffffffff8129efe3)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff812bc604)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109774e)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/events/uprobes.c (ffffffff81210cd3)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff812583f7)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (ffffffff812615d6)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (ffffffff8128c27c)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812a5532)
Location: include/linux/rmap.h:148
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ab773)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff812c95b0)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109f34e)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/events/uprobes.c (ffffffff8121fbeb)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff81267dd7)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mmap.c (ffffffff81270fa6)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/hugetlb.c (ffffffff8129c061)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812b4c62)
Location: include/linux/rmap.h:148
Inline: True
```
```
In mm/huge_memory.c (ffffffff812bbae3)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff812da297)
Location: include/linux/rmap.h:148
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
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
</ul>
