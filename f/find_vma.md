# Function: <code>find_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c4240)
Location: mm/mmap.c:2041
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - kernel/sys.c:prctl_set_mm
  - kernel/sched/fair.c:task_numa_work
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/gup.c:__mm_populate
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:print_vma_addr
  - mm/mincore.c:SyS_mincore
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:SyS_brk
  - mm/mmap.c:mmap_region
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mprotect.c:SyS_mprotect
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:SyS_msync
  - mm/msync.c:SyS_msync
  - mm/pagewalk.c:walk_page_range
  - mm/madvise.c:SyS_madvise
  - mm/hugetlb.c:huge_pmd_share
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:do_mbind
  - mm/ksm.c:find_mergeable_vma
  - mm/ksm.c:ksm_scan_thread
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:SyS_move_pages
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_zeropage
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_map_files_lookup
  - ipc/shm.c:do_shmat
  - ipc/shm.c:SyS_shmdt
```
**Symbols:**

```
ffffffff811c4240-ffffffff811c42ae: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e0110)
Location: mm/mmap.c:1940
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - kernel/sys.c:prctl_set_mm
  - kernel/sched/fair.c:task_numa_work
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:__mm_populate
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:SyS_mincore
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:mmap_region
  - mm/mmap.c:SyS_brk
  - mm/mprotect.c:SyS_mprotect
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:SyS_msync
  - mm/msync.c:SyS_msync
  - mm/pagewalk.c:walk_page_range
  - mm/madvise.c:SyS_madvise
  - mm/hugetlb.c:huge_pmd_share
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:do_get_mempolicy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:find_mergeable_vma
  - mm/migrate.c:SyS_move_pages
  - mm/migrate.c:do_pages_stat
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - ipc/shm.c:SyS_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff811e0110-ffffffff811e017e: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f0060)
Location: mm/mmap.c:2093
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - kernel/sys.c:prctl_set_mm
  - kernel/sched/fair.c:task_numa_work
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:__mm_populate
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:SyS_mincore
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:mmap_region
  - mm/mmap.c:SyS_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:SyS_msync
  - mm/msync.c:SyS_msync
  - mm/pagewalk.c:walk_page_range
  - mm/madvise.c:SyS_madvise
  - mm/hugetlb.c:huge_pmd_share
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:find_mergeable_vma
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:do_pages_stat
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - ipc/shm.c:SyS_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff811f0060-ffffffff811f00ce: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fafe0)
Location: mm/mmap.c:2115
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - kernel/sys.c:prctl_set_mm
  - kernel/sched/fair.c:task_numa_work
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:__mm_populate
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:SyS_mincore
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:mmap_region
  - mm/mmap.c:SyS_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:SyS_msync
  - mm/msync.c:SyS_msync
  - mm/pagewalk.c:walk_page_range
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:SyS_madvise
  - mm/hugetlb.c:huge_pmd_share
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:find_mergeable_vma
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:do_pages_stat
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - ipc/shm.c:SyS_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff811fafe0-ffffffff811fb04e: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81213500)
Location: mm/mmap.c:2131
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
  - kernel/sys.c:prctl_set_mm
  - kernel/sched/fair.c:task_numa_work
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:__mm_populate
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:SyS_mincore
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:mmap_region
  - mm/mmap.c:SyS_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:SyS_msync
  - mm/msync.c:SyS_msync
  - mm/pagewalk.c:walk_page_range
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:SyS_madvise
  - mm/hugetlb.c:huge_pmd_share
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:find_mergeable_vma
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:do_pages_stat
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - ipc/shm.c:SyS_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81213500-ffffffff8121356e: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812345c0)
Location: mm/mmap.c:2191
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
  - kernel/sys.c:prctl_set_mm
  - kernel/sched/fair.c:task_numa_work
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:__mm_populate
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
  - mm/msync.c:__x64_sys_msync
  - mm/pagewalk.c:walk_page_range
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - mm/hugetlb.c:huge_pmd_share
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:find_mergeable_vma
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:do_pages_stat
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff812345c0-ffffffff8123462e: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81247d70)
Location: mm/mmap.c:2226
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
  - kernel/sys.c:prctl_set_mm
  - kernel/sched/fair.c:task_numa_work
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:__mm_populate
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
  - mm/msync.c:__x64_sys_msync
  - mm/pagewalk.c:walk_page_range
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - mm/hugetlb.c:huge_pmd_share
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:find_mergeable_vma
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:do_pages_stat
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81247d70-ffffffff81247dde: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81259f90)
Location: mm/mmap.c:2227
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
  - kernel/sys.c:prctl_set_mm
  - kernel/sched/fair.c:task_numa_work
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:__mm_populate
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
  - mm/msync.c:__x64_sys_msync
  - mm/pagewalk.c:walk_page_range
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/hugetlb.c:huge_pmd_share
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:find_mergeable_vma
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
  - mm/hmm.c:hmm_range_fault
  - mm/hmm.c:hmm_range_snapshot
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81259f90-ffffffff81259ffd: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81268440)
Location: mm/mmap.c:2235
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
  - kernel/sys.c:prctl_set_mm
  - kernel/sched/fair.c:task_numa_work
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:__mm_populate
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
  - mm/msync.c:__x64_sys_msync
  - mm/pagewalk.c:walk_page_range
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/hugetlb.c:huge_pmd_share
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:find_mergeable_vma
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
  - mm/hmm.c:hmm_range_fault
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
**Symbols:**

```
ffffffff81268440-ffffffff812684ad: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129a7f5)
Location: mm/mmap.c:2234
Inline: True
Inline callers:
  - mm/mmap.c:find_vma_prev
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - kernel/sys.c:prctl_set_mm
  - kernel/sched/fair.c:task_numa_work
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:__mm_populate
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:do_mincore
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__do_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
  - mm/pagewalk.c:walk_page_range
  - mm/hugetlb.c:huge_pmd_share
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mbind_range
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:find_mergeable_vma
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
**Symbols:**

```
ffffffff81298900-ffffffff81298967: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a59d5)
Location: mm/mmap.c:2300
Inline: True
Inline callers:
  - mm/mmap.c:find_vma_prev
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - kernel/sys.c:prctl_set_mm
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:__mm_populate
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:do_mincore
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__do_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
  - mm/pagewalk.c:walk_page_range
  - mm/hugetlb.c:huge_pmd_share
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mbind_range
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:find_mergeable_vma
  - mm/migrate.c:do_pages_stat_array
  - mm/migrate.c:add_page_for_migration
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
**Symbols:**

```
ffffffff812a3a80-ffffffff812a3ae7: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ab165)
Location: mm/mmap.c:2304
Inline: True
Inline callers:
  - mm/mmap.c:find_vma_prev
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - kernel/sys.c:prctl_set_mm
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:__mm_populate
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:__do_sys_mincore
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__do_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
  - mm/pagewalk.c:walk_page_range
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mbind_range
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:find_mergeable_vma
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
**Symbols:**

```
ffffffff812a92a0-ffffffff812a930d: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ec835)
Location: mm/mmap.c:2273
Inline: True
Inline callers:
  - mm/mmap.c:find_vma_prev
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - kernel/sys.c:prctl_set_mm
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:__mm_populate
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:__do_sys_mincore
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__do_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
  - mm/pagewalk.c:walk_page_range
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mbind_range
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:find_mergeable_vma
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
**Symbols:**

```
ffffffff812ea900-ffffffff812ea96d: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8134d6f0)
Location: mm/mmap.c:2301
Inline: True
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - kernel/sys.c:prctl_set_mm
  - kernel/sched/fair.c:task_numa_work
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:__mm_populate
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:__do_sys_mincore
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__do_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
  - mm/pagewalk.c:walk_page_range
  - mm/madvise.c:madvise_walk_vmas
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_populate
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mbind_range
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:find_mergeable_vma
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
**Symbols:**

```
ffffffff8134d6f0-ffffffff8134d768: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813cc712)
Location: mm/mmap.c:1830
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - kernel/sys.c:prctl_set_mm
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:print_vma_addr
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:move_vma
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
  - mm/pagewalk.c:walk_page_range
  - mm/pagewalk.c:walk_page_range
  - mm/madvise.c:madvise_walk_vmas
  - mm/madvise.c:madvise_walk_vmas
  - mm/madvise.c:madvise_vma_behavior
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff813c6980-ffffffff813c69d0: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813ffd66)
Location: mm/mmap.c:1858
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma_locked
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - kernel/sys.c:prctl_set_mm
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:gup_vma_lookup
  - mm/memory.c:print_vma_addr
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
  - mm/pagewalk.c:walk_page_range
  - mm/pagewalk.c:walk_page_range
  - mm/madvise.c:madvise_walk_vmas
  - mm/madvise.c:madvise_walk_vmas
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff813fac00-ffffffff813fac54: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8142c176)
Location: mm/mmap.c:1890
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma_locked
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - arch/x86/kernel/shstk.c:shstk_pop_sigframe
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - kernel/sys.c:prctl_set_mm
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:gup_vma_lookup
  - mm/memory.c:print_vma_addr
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
  - mm/pagewalk.c:walk_page_range
  - mm/pagewalk.c:walk_page_range
  - mm/madvise.c:madvise_walk_vmas
  - mm/madvise.c:madvise_walk_vmas
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
```
**Symbols:**

```
ffffffff814269c0-ffffffff81426a14: find_vma (STB_GLOBAL)
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
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff8000102ff620)
Location: mm/mmap.c:2235
Inline: False
Direct callers:
  - arch/arm64/kernel/traps.c:arm64_notify_segfault
  - arch/arm64/mm/fault.c:do_page_fault
  - virt/kvm/kvm_main.c:__gfn_to_pfn_memslot
  - virt/kvm/kvm_main.c:kvm_host_page_size
  - virt/kvm/arm/mmu.c:kvm_arch_prepare_memory_region
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:stage2_unmap_vm
  - kernel/sys.c:prctl_set_mm
  - kernel/sched/fair.c:task_numa_work
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:__mm_populate
  - mm/memory.c:print_vma_addr
  - mm/mincore.c:__do_sys_mincore
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:__arm64_sys_remap_file_pages
  - mm/mmap.c:__arm64_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__arm64_sys_brk
  - mm/mprotect.c:__arm64_sys_mprotect
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:__arm64_sys_msync
  - mm/msync.c:__arm64_sys_msync
  - mm/pagewalk.c:walk_page_range
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:__arm64_sys_madvise
  - mm/hugetlb.c:huge_pmd_share
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:find_mergeable_vma
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
  - mm/hmm.c:hmm_range_fault
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/hugetlbfs/inode.c:hugetlb_get_unmapped_area
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffff8000102ff620-ffff8000102ff6b8: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c051e390)
Location: mm/mmap.c:2235
Inline: False
Direct callers:
  - arch/arm/mm/fault.c:do_page_fault
  - arch/arm/mm/mmap.c:arch_get_unmapped_area_topdown
  - arch/arm/mm/mmap.c:arch_get_unmapped_area
  - kernel/sys.c:prctl_set_mm
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:__mm_populate
  - mm/memory.c:print_vma_addr
  - mm/mincore.c:__se_sys_mincore
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__se_sys_brk
  - mm/mprotect.c:__se_sys_mprotect
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:__se_sys_msync
  - mm/msync.c:__se_sys_msync
  - mm/pagewalk.c:walk_page_range
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:find_mergeable_vma
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
  - mm/hmm.c:hmm_range_fault
  - fs/exec.c:setup_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
c051e390-c051e418: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cb4c0)
Location: mm/mmap.c:2235
Inline: False
Direct callers:
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/mmap.c:radix__arch_get_unmapped_area_topdown
  - arch/powerpc/mm/mmap.c:radix__arch_get_unmapped_area
  - arch/powerpc/mm/book3s64/radix_hugetlbpage.c:radix__hugetlb_get_unmapped_area
  - arch/powerpc/mm/book3s64/subpage_prot.c:__se_sys_subpage_prot
  - arch/powerpc/mm/copro_fault.c:copro_handle_mm_fault
  - kernel/sys.c:prctl_set_mm
  - kernel/sched/fair.c:task_numa_work
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:__mm_populate
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:__se_sys_mincore
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__se_sys_brk
  - mm/mprotect.c:__se_sys_mprotect
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:__se_sys_msync
  - mm/msync.c:__se_sys_msync
  - mm/pagewalk.c:walk_page_range
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:new_page
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:find_mergeable_vma
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
  - mm/hmm.c:hmm_range_fault
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
c0000000003cb4c0-c0000000003cb57c: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020d55c)
Location: mm/mmap.c:2235
Inline: False
Direct callers:
  - arch/riscv/mm/fault.c:do_page_fault
  - kernel/sys.c:prctl_set_mm
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/gup.c:__mm_populate
  - mm/memory.c:print_vma_addr
  - mm/mincore.c:__se_sys_mincore
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__se_sys_brk
  - mm/mprotect.c:__se_sys_mprotect
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:__se_sys_msync
  - mm/msync.c:__se_sys_msync
  - mm/pagewalk.c:walk_page_range
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/hugetlb.c:huge_pmd_share
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:find_mergeable_vma
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
  - mm/hmm.c:hmm_range_fault
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/hugetlbfs/inode.c:hugetlb_get_unmapped_area
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffe00020d55c-ffffffe00020d5ce: find_vma (STB_GLOBAL)
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
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81260a90)
Location: mm/mmap.c:2235
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
  - kernel/sys.c:prctl_set_mm
  - kernel/sched/fair.c:task_numa_work
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:__mm_populate
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
  - mm/msync.c:__x64_sys_msync
  - mm/pagewalk.c:walk_page_range
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/hugetlb.c:huge_pmd_share
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:find_mergeable_vma
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
  - mm/hmm.c:hmm_range_fault
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81260a90-ffffffff81260afd: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81252eb0)
Location: mm/mmap.c:2235
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
  - kernel/sys.c:prctl_set_mm
  - kernel/sched/fair.c:task_numa_work
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:__mm_populate
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
  - mm/msync.c:__x64_sys_msync
  - mm/pagewalk.c:walk_page_range
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/hugetlb.c:huge_pmd_share
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:find_mergeable_vma
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
  - mm/hmm.c:hmm_range_fault
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
**Symbols:**

```
ffffffff81252eb0-ffffffff81252f1d: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125e830)
Location: mm/mmap.c:2235
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
  - kernel/sys.c:prctl_set_mm
  - kernel/sched/fair.c:task_numa_work
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:__mm_populate
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
  - mm/msync.c:__x64_sys_msync
  - mm/pagewalk.c:walk_page_range
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/hugetlb.c:huge_pmd_share
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:find_mergeable_vma
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
  - mm/hmm.c:hmm_range_fault
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
**Symbols:**

```
ffffffff8125e830-ffffffff8125e89d: find_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vm_area_struct *find_vma(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126e280)
Location: mm/mmap.c:2235
Inline: False
Direct callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
  - kernel/sys.c:prctl_set_mm
  - kernel/sched/fair.c:task_numa_work
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/gup.c:__mm_populate
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:find_extend_vma
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:vma_to_resize
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
  - mm/msync.c:__x64_sys_msync
  - mm/pagewalk.c:walk_page_range
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/hugetlb.c:huge_pmd_share
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:find_mergeable_vma
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
  - mm/hmm.c:hmm_range_fault
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:pagemap_pte_hole
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
**Symbols:**

```
ffffffff8126e280-ffffffff8126e2ed: find_vma (STB_GLOBAL)
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
