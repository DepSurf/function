# Function: <code>vma_is_dax</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff811f6933)
Location: include/linux/dax.h:35
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:__split_huge_page_pmd
```
```
In fs/binfmt_elf.c (ffffffff8126912f)
Location: include/linux/dax.h:35
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8126be59)
Location: include/linux/dax.h:35
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81215f71)
Location: include/linux/dax.h:58
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In fs/binfmt_elf.c (ffffffff8129539b)
Location: include/linux/dax.h:58
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81297ffc)
Location: include/linux/dax.h:58
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
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
In kernel/sched/fair.c (ffffffff810bb61f)
Location: include/linux/dax.h:90
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/mempolicy.c (ffffffff8121188a)
Location: include/linux/dax.h:90
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
```
```
In mm/migrate.c (ffffffff81224d1b)
Location: include/linux/dax.h:90
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
```
```
In mm/huge_memory.c (ffffffff8122853d)
Location: include/linux/dax.h:90
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In fs/binfmt_elf.c (ffffffff812aa02e)
Location: include/linux/dax.h:90
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff812acacd)
Location: include/linux/dax.h:90
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
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
In kernel/sched/fair.c (ffffffff810b5e4a)
Location: include/linux/fs.h:3143
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/memory.c (ffffffff811f590f)
Location: include/linux/fs.h:3143
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mempolicy.c (ffffffff8121d1aa)
Location: include/linux/fs.h:3143
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
```
```
In mm/migrate.c (ffffffff81230403)
Location: include/linux/fs.h:3143
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
```
```
In mm/huge_memory.c (ffffffff81231c7c)
Location: include/linux/fs.h:3143
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pud
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In fs/binfmt_elf.c (ffffffff812b69e5)
Location: include/linux/fs.h:3143
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff812b9ad0)
Location: include/linux/fs.h:3143
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
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
In kernel/sched/fair.c (ffffffff810be6ea)
Location: include/linux/fs.h:3209
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/gup.c (ffffffff81207a67)
Location: include/linux/fs.h:3209
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_longterm
```
```
In mm/memory.c (ffffffff8120e84b)
Location: include/linux/fs.h:3209
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mempolicy.c (ffffffff8123839a)
Location: include/linux/fs.h:3209
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
```
```
In mm/migrate.c (ffffffff8124e092)
Location: include/linux/fs.h:3209
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
```
```
In mm/huge_memory.c (ffffffff812528c3)
Location: include/linux/fs.h:3209
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:zap_huge_pud
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/frame_vector.c (ffffffff8126c92e)
Location: include/linux/fs.h:3209
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In fs/binfmt_elf.c (ffffffff812da2bf)
Location: include/linux/fs.h:3209
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff812dd3e9)
Location: include/linux/fs.h:3209
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
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
In kernel/sched/fair.c (ffffffff810c683b)
Location: include/linux/fs.h:3234
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/gup.c (ffffffff81228629)
Location: include/linux/fs.h:3234
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_longterm
```
```
In mm/memory.c (ffffffff8122fed7)
Location: include/linux/fs.h:3234
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mlock.c (ffffffff812333c5)
Location: include/linux/fs.h:3234
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffffffff81237bb5)
Location: include/linux/fs.h:3234
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff8125b91e)
Location: include/linux/fs.h:3234
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
```
```
In mm/ksm.c (ffffffff81262563)
Location: include/linux/fs.h:3234
Inline: True
Inline callers:
  - mm/ksm.c:ksm_madvise
```
```
In mm/migrate.c (ffffffff8126fb97)
Location: include/linux/fs.h:3234
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:kernel_move_pages
```
```
In mm/huge_memory.c (ffffffff81276cc6)
Location: include/linux/fs.h:3234
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:zap_huge_pud
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/frame_vector.c (ffffffff812914b1)
Location: include/linux/fs.h:3234
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In mm/hmm.c (ffffffff81293903)
Location: include/linux/fs.h:3234
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_fault
  - mm/hmm.c:hmm_vma_get_pfns
```
```
In fs/binfmt_elf.c (ffffffff81305f6f)
Location: include/linux/fs.h:3234
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81309914)
Location: include/linux/fs.h:3234
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
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
In kernel/sched/fair.c (ffffffff810cedbb)
Location: include/linux/fs.h:3313
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/gup.c (ffffffff8123be49)
Location: include/linux/fs.h:3313
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_longterm
```
```
In mm/memory.c (ffffffff81241bcd)
Location: include/linux/fs.h:3313
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mlock.c (ffffffff81246b95)
Location: include/linux/fs.h:3313
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffffffff8124b54e)
Location: include/linux/fs.h:3313
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff812701d2)
Location: include/linux/fs.h:3313
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81276de3)
Location: include/linux/fs.h:3313
Inline: True
Inline callers:
  - mm/ksm.c:ksm_madvise
```
```
In mm/migrate.c (ffffffff8128422d)
Location: include/linux/fs.h:3313
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:kernel_move_pages
```
```
In mm/huge_memory.c (ffffffff8128855c)
Location: include/linux/fs.h:3313
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pud
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:transparent_hugepage_enabled
```
```
In mm/frame_vector.c (ffffffff812a64d1)
Location: include/linux/fs.h:3313
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In mm/hmm.c (ffffffff812a85d3)
Location: include/linux/fs.h:3313
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_fault
  - mm/hmm.c:hmm_vma_get_pfns
```
```
In fs/binfmt_elf.c (ffffffff8131b6ff)
Location: include/linux/fs.h:3313
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8131f114)
Location: include/linux/fs.h:3313
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
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
In kernel/sched/fair.c (ffffffff810d768b)
Location: include/linux/fs.h:3324
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/gup.c (ffffffff8124d697)
Location: include/linux/fs.h:3324
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (ffffffff81254530)
Location: include/linux/fs.h:3324
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mlock.c (ffffffff81258da6)
Location: include/linux/fs.h:3324
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffffffff8125d9a2)
Location: include/linux/fs.h:3324
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff8128b7e2)
Location: include/linux/fs.h:3324
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81292653)
Location: include/linux/fs.h:3324
Inline: True
Inline callers:
  - mm/ksm.c:ksm_madvise
```
```
In mm/migrate.c (ffffffff812a06c9)
Location: include/linux/fs.h:3324
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffffffff812a319a)
Location: include/linux/fs.h:3324
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pud
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:transparent_hugepage_enabled
```
```
In mm/frame_vector.c (ffffffff812c1bca)
Location: include/linux/fs.h:3324
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In fs/binfmt_elf.c (ffffffff813431a9)
Location: include/linux/fs.h:3324
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81346b38)
Location: include/linux/fs.h:3324
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
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
In kernel/sched/fair.c (ffffffff810e1c9b)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/gup.c (ffffffff8125bbc7)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (ffffffff81262a90)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mlock.c (ffffffff81267276)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffffffff8126c172)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff8129b352)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff812a23d3)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/ksm.c:ksm_madvise
```
```
In mm/migrate.c (ffffffff812afdf6)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffffffff812b469a)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pud
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:transparent_hugepage_enabled
```
```
In mm/frame_vector.c (ffffffff812d3afa)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In fs/binfmt_elf.c (ffffffff8135b5e7)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8135ee46)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d321f)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
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
In mm/gup.c (ffffffff8128a32b)
Location: include/linux/fs.h:3436
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (ffffffff812947df)
Location: include/linux/fs.h:3436
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mlock.c (ffffffff8129739f)
Location: include/linux/fs.h:3436
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffffffff8129beaa)
Location: include/linux/fs.h:3436
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff812ce724)
Location: include/linux/fs.h:3436
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/ksm.c (ffffffff812d6adc)
Location: include/linux/fs.h:3436
Inline: True
Inline callers:
  - mm/ksm.c:ksm_madvise
```
```
In mm/migrate.c (ffffffff812e3baf)
Location: include/linux/fs.h:3436
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff812e9c26)
Location: include/linux/fs.h:3436
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pud
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:transparent_hugepage_enabled
```
```
In mm/frame_vector.c (ffffffff81309983)
Location: include/linux/fs.h:3436
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In fs/binfmt_elf.c (ffffffff8139ecf9)
Location: include/linux/fs.h:3436
Inline: True
Inline callers:
  - fs/binfmt_elf.c:vma_dump_size
```
```
In fs/compat_binfmt_elf.c (ffffffff813a1e09)
Location: include/linux/fs.h:3436
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:vma_dump_size
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
In mm/gup.c (ffffffff812932dc)
Location: include/linux/fs.h:3229
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8129f05f)
Location: include/linux/fs.h:3229
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mlock.c (ffffffff812a234f)
Location: include/linux/fs.h:3229
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffffffff812a7162)
Location: include/linux/fs.h:3229
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff812da064)
Location: include/linux/fs.h:3229
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/ksm.c (ffffffff812e261c)
Location: include/linux/fs.h:3229
Inline: True
Inline callers:
  - mm/ksm.c:ksm_madvise
```
```
In mm/migrate.c (ffffffff812ef00f)
Location: include/linux/fs.h:3229
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff812f4e06)
Location: include/linux/fs.h:3229
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pud
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:transparent_hugepage_enabled
```
```
In mm/frame_vector.c (ffffffff813157a7)
Location: include/linux/fs.h:3229
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In fs/coredump.c (ffffffff813b7e59)
Location: include/linux/fs.h:3229
Inline: True
Inline callers:
  - fs/coredump.c:vma_dump_size
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
In mm/gup.c (ffffffff81298c73)
Location: include/linux/fs.h:3481
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812a40bf)
Location: include/linux/fs.h:3481
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mlock.c (ffffffff812a7be2)
Location: include/linux/fs.h:3481
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffffffff812acf95)
Location: include/linux/fs.h:3481
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff812e18c4)
Location: include/linux/fs.h:3481
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/ksm.c (ffffffff812e9dac)
Location: include/linux/fs.h:3481
Inline: True
Inline callers:
  - mm/ksm.c:ksm_madvise
```
```
In mm/migrate.c (ffffffff812f51b2)
Location: include/linux/fs.h:3481
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff81300675)
Location: include/linux/fs.h:3481
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pud
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:transparent_hugepage_active
```
```
In fs/coredump.c (ffffffff813bef59)
Location: include/linux/fs.h:3481
Inline: True
Inline callers:
  - fs/coredump.c:vma_dump_size
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
In mm/gup.c (ffffffff812d7318)
Location: include/linux/fs.h:3461
Inline: True
Inline callers:
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff812e53eb)
Location: include/linux/fs.h:3461
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mlock.c (ffffffff812e9222)
Location: include/linux/fs.h:3461
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffffffff812ee6e5)
Location: include/linux/fs.h:3461
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff81328994)
Location: include/linux/fs.h:3461
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/ksm.c (ffffffff81331cdc)
Location: include/linux/fs.h:3461
Inline: True
Inline callers:
  - mm/ksm.c:ksm_madvise
```
```
In mm/migrate.c (ffffffff8133f7b2)
Location: include/linux/fs.h:3461
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff8134a315)
Location: include/linux/fs.h:3461
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pud
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:transparent_hugepage_active
```
```
In fs/coredump.c (ffffffff8140ed89)
Location: include/linux/fs.h:3461
Inline: True
Inline callers:
  - fs/coredump.c:vma_dump_size
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
In mm/gup.c (ffffffff81336eb7)
Location: include/linux/fs.h:3239
Inline: True
Inline callers:
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff813476e4)
Location: include/linux/fs.h:3239
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mlock.c (ffffffff813497ea)
Location: include/linux/fs.h:3239
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffffffff81351ad1)
Location: include/linux/fs.h:3239
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff81397bd4)
Location: include/linux/fs.h:3239
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/ksm.c (ffffffff813a2e69)
Location: include/linux/fs.h:3239
Inline: True
Inline callers:
  - mm/ksm.c:ksm_madvise
```
```
In mm/migrate_device.c (ffffffff813b6c1e)
Location: include/linux/fs.h:3239
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff813c0ea4)
Location: include/linux/fs.h:3239
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pud
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:transparent_hugepage_active
```
```
In mm/khugepaged.c (ffffffff813c6113)
Location: include/linux/fs.h:3239
Inline: True
```
```
In fs/coredump.c (ffffffff81484495)
Location: include/linux/fs.h:3239
Inline: True
Inline callers:
  - fs/coredump.c:vma_dump_size
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
In mm/gup.c (ffffffff813ae3cb)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - mm/gup.c:check_vma_flags
```
```
In mm/mlock.c (ffffffff813c1afa)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffffffff813cbaff)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff814177e4)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/ksm.c (ffffffff81422ad6)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - mm/ksm.c:ksm_madvise
```
```
In mm/migrate_device.c (ffffffff814385c0)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff81442d69)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pud
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:hugepage_vma_check
```
```
In fs/coredump.c (ffffffff81517982)
Location: include/linux/fs.h:3381
Inline: True
Inline callers:
  - fs/coredump.c:vma_dump_size
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
In mm/gup.c (ffffffff813e2832)
Location: include/linux/fs.h:2996
Inline: True
Inline callers:
  - mm/gup.c:check_vma_flags
```
```
In mm/mlock.c (ffffffff813f70cb)
Location: include/linux/fs.h:2996
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffffffff814003ba)
Location: include/linux/fs.h:2996
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff8144ad74)
Location: include/linux/fs.h:2996
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/ksm.c (ffffffff81457ae3)
Location: include/linux/fs.h:2996
Inline: True
Inline callers:
  - mm/ksm.c:ksm_madvise
```
```
In mm/migrate_device.c (ffffffff8146e29e)
Location: include/linux/fs.h:2996
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff81478638)
Location: include/linux/fs.h:2996
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pud
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:hugepage_vma_check
```
```
In fs/coredump.c (ffffffff8154f252)
Location: include/linux/fs.h:2996
Inline: True
Inline callers:
  - fs/coredump.c:vma_dump_size
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
In mm/gup.c (ffffffff8140d062)
Location: include/linux/fs.h:3293
Inline: True
Inline callers:
  - mm/gup.c:check_vma_flags
```
```
In mm/mlock.c (ffffffff8142262e)
Location: include/linux/fs.h:3293
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffffffff8142c801)
Location: include/linux/fs.h:3293
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff814847b4)
Location: include/linux/fs.h:3293
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/ksm.c (ffffffff814925b3)
Location: include/linux/fs.h:3293
Inline: True
Inline callers:
  - mm/ksm.c:ksm_madvise
```
```
In mm/migrate_device.c (ffffffff8149ec3e)
Location: include/linux/fs.h:3293
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff814a7d68)
Location: include/linux/fs.h:3293
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pud
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:__thp_vma_allowable_orders
```
```
In fs/coredump.c (ffffffff81585092)
Location: include/linux/fs.h:3293
Inline: True
Inline callers:
  - fs/coredump.c:vma_dump_size
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
In kernel/sched/fair.c (ffff800010142bbc)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/gup.c (ffff8000102f2fc8)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (ffff8000102f9ca0)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mlock.c (ffff8000102fe4a8)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffff800010303508)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffff80001033a1f0)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffff800010341cec)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/ksm.c:ksm_madvise
```
```
In mm/migrate.c (ffff8000103521b8)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffff800010355c84)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:transparent_hugepage_enabled
```
```
In mm/frame_vector.c (ffff800010379a30)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In fs/binfmt_elf.c (ffff800010420cf4)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffff8000104245a4)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
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
In mm/gup.c (0)
Location: include/linux/fs.h:3386
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/fs.h:3386
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/fs.h:3386
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/fs.h:3386
Inline: True
```
```
In mm/frame_vector.c (0)
Location: include/linux/fs.h:3386
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/fs.h:3386
Inline: True
```
```
In fs/binfmt_elf_fdpic.c (0)
Location: include/linux/fs.h:3386
Inline: True
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
In kernel/sched/fair.c (c00000000019296c)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/gup.c (c0000000003b9948)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (c0000000003c3ce8)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mlock.c (c0000000003c9dec)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (c0000000003cffb4)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (c00000000041487c)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (c00000000041f430)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/ksm.c:ksm_madvise
```
```
In mm/migrate.c (c000000000435d90)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (c00000000043bfc0)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:transparent_hugepage_enabled
```
```
In mm/frame_vector.c (c00000000046cc80)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In fs/binfmt_elf.c (c00000000052f9e8)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (c000000000533608)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
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
In mm/gup.c (ffffffe00020536a)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffe00020c970)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffffffe0002100a6)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/ksm.c (ffffffe0002360a4)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/ksm.c:ksm_madvise
```
```
In mm/frame_vector.c (ffffffe000250dd4)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In fs/binfmt_elf.c (ffffffe0002c1748)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
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
In kernel/sched/fair.c (ffffffff810dbe4b)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/gup.c (ffffffff81254217)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (ffffffff8125b0e0)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mlock.c (ffffffff8125f8c6)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffffffff812647c2)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff81293932)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff8129a9b3)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/ksm.c:ksm_madvise
```
```
In mm/migrate.c (ffffffff812a83d6)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffffffff812acc7a)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pud
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:transparent_hugepage_enabled
```
```
In mm/frame_vector.c (ffffffff812cc0da)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In fs/binfmt_elf.c (ffffffff81353bc7)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81357426)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
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
In kernel/sched/fair.c (ffffffff810cae5b)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/gup.c (ffffffff81246e67)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (ffffffff8124d51f)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mlock.c (ffffffff81251ce6)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffffffff81256be2)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff81285542)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff8128c573)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/ksm.c:ksm_madvise
```
```
In mm/migrate.c (ffffffff81299d96)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffffffff8129dd5c)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pud
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:transparent_hugepage_enabled
```
```
In mm/frame_vector.c (ffffffff812bcf4a)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In fs/binfmt_elf.c (ffffffff81344887)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813480d6)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In drivers/dax/device.c (ffffffff816f166c)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - drivers/dax/device.c:check_vma
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d2cf)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
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
In kernel/sched/fair.c (ffffffff810d81cb)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/gup.c (ffffffff81251fb7)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (ffffffff81258e80)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mlock.c (ffffffff8125d666)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffffffff81262562)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff81291742)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff812987c3)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/ksm.c:ksm_madvise
```
```
In mm/migrate.c (ffffffff812a61e6)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffffffff812aaa8a)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pud
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:transparent_hugepage_enabled
```
```
In mm/frame_vector.c (ffffffff812c9eea)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In fs/binfmt_elf.c (ffffffff81351697)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81354ef6)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c809f)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
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
In kernel/sched/fair.c (ffffffff810e3c7a)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/gup.c (ffffffff81261967)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (ffffffff81268880)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mlock.c (ffffffff8126d046)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (ffffffff81271f22)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff812a1552)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff812a8543)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/ksm.c:ksm_madvise
```
```
In mm/migrate.c (ffffffff812b6526)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffffffff812badda)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pud
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:transparent_hugepage_enabled
```
```
In mm/frame_vector.c (ffffffff812dabea)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In fs/binfmt_elf.c (ffffffff81364c37)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813684d6)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e233f)
Location: include/linux/fs.h:3386
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
</details>
</li>
</ul>

## Differences
