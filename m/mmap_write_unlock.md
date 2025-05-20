# Function: <code>mmap_write_unlock</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81005cfb)
Location: include/linux/mmap_lock.h:34
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In kernel/fork.c (ffffffff810a5725)
Location: include/linux/mmap_lock.h:34
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff810c4d15)
Location: include/linux/mmap_lock.h:34
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/events/uprobes.c (ffffffff8124595a)
Location: include/linux/mmap_lock.h:34
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_add_vma
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/util.c (ffffffff812734f3)
Location: include/linux/mmap_lock.h:34
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff81297d5b)
Location: include/linux/mmap_lock.h:34
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff8129ce5b)
Location: include/linux/mmap_lock.h:34
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff8129e272)
Location: include/linux/mmap_lock.h:34
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff812a119f)
Location: include/linux/mmap_lock.h:34
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/madvise.c (ffffffff812b645f)
Location: include/linux/mmap_lock.h:34
Inline: True
```
```
In mm/mempolicy.c (ffffffff812cffd6)
Location: include/linux/mmap_lock.h:34
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff812d2573)
Location: include/linux/mmap_lock.h:34
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert
```
```
In mm/ksm.c (ffffffff812d6be4)
Location: include/linux/mmap_lock.h:34
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/khugepaged.c (ffffffff812f3d01)
Location: include/linux/mmap_lock.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff8131b7fb)
Location: include/linux/mmap_lock.h:34
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:__bprm_mm_init
  - fs/exec.c:__bprm_mm_init
```
```
In fs/userfaultfd.c (ffffffff8137273a)
Location: include/linux/mmap_lock.h:34
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff813778e4)
Location: include/linux/mmap_lock.h:34
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/coredump.c (ffffffff813a7ddd)
Location: include/linux/mmap_lock.h:34
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/task_mmu.c (ffffffff813b71ce)
Location: include/linux/mmap_lock.h:34
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In ipc/shm.c (ffffffff814912b4)
Location: include/linux/mmap_lock.h:34
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189e342)
Location: include/linux/mmap_lock.h:34
Inline: True
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
In arch/x86/entry/vdso/vma.c (ffffffff81004cef)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
```
```
In kernel/fork.c (ffffffff810a0ef1)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff810c0129)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/events/uprobes.c (ffffffff8125025d)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_add_vma
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/util.c (ffffffff8127dc5f)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff812a2e72)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff812a821c)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff812a9720)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff812ac8c1)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/madvise.c (ffffffff812c14ab)
Location: include/linux/mmap_lock.h:102
Inline: True
```
```
In mm/mempolicy.c (ffffffff812dba7f)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff812ddf00)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff812e2732)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/khugepaged.c (ffffffff812ff5a4)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff8132721c)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:__bprm_mm_init
  - fs/exec.c:__bprm_mm_init
```
```
In fs/userfaultfd.c (ffffffff81380620)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff8138523e)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff81396a03)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_unaccount_mem
```
```
In fs/coredump.c (ffffffff813b97e5)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/task_mmu.c (ffffffff813c8a5f)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In ipc/shm.c (ffffffff814aeab3)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ad37c)
Location: include/linux/mmap_lock.h:102
Inline: True
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
In arch/x86/entry/vdso/vma.c (ffffffff81004cdc)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
```
```
In kernel/fork.c (ffffffff810a1c68)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff810c1b2b)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/events/uprobes.c (ffffffff81256ba0)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/util.c (ffffffff81282e2c)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff812a86cf)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff812abc27)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff812aebad)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff812b1bbb)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/madvise.c (ffffffff812c827a)
Location: include/linux/mmap_lock.h:102
Inline: True
```
```
In mm/mempolicy.c (ffffffff812e3311)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff812e54ad)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff812e9ebf)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/khugepaged.c (ffffffff8130621b)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff8132d2b9)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:__bprm_mm_init
  - fs/exec.c:__bprm_mm_init
```
```
In fs/userfaultfd.c (ffffffff8138712f)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff8138bfeb)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/coredump.c (ffffffff813c0940)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/task_mmu.c (ffffffff813cfa9e)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In ipc/shm.c (ffffffff814b48d0)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81890414)
Location: include/linux/mmap_lock.h:102
Inline: True
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
In arch/x86/entry/vdso/vma.c (ffffffff810052f3)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
```
```
In kernel/fork.c (ffffffff810b3846)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff810d48e0)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/events/uprobes.c (ffffffff8129293a)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/util.c (ffffffff812c0f17)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff812e9d09)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff812ed328)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff812f0396)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff812f378b)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/madvise.c (ffffffff8130d090)
Location: include/linux/mmap_lock.h:102
Inline: True
```
```
In mm/mempolicy.c (ffffffff8132a4ff)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff8132d094)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81331de9)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/khugepaged.c (ffffffff81350079)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff8137ab32)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:__bprm_mm_init
  - fs/exec.c:__bprm_mm_init
```
```
In fs/userfaultfd.c (ffffffff813d4415)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff813d959b)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/coredump.c (ffffffff814107b0)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/task_mmu.c (ffffffff81420e7e)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In ipc/shm.c (ffffffff8150cf80)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff819240c0)
Location: include/linux/mmap_lock.h:102
Inline: True
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
In arch/x86/entry/vdso/vma.c (ffffffff81004359)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
```
```
In kernel/fork.c (ffffffff810c9a27)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff810ed25d)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_vma
```
```
In kernel/events/uprobes.c (ffffffff812e8335)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/util.c (ffffffff8131dd71)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff81349c69)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff81350601)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff81353766)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff81357556)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/madvise.c (ffffffff81378b01)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
```
```
In mm/mempolicy.c (ffffffff81399bde)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff8139d342)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff813a2f73)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/khugepaged.c (ffffffff813c826f)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff813fb087)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:alloc_bprm
  - fs/exec.c:setup_arg_pages
```
```
In fs/userfaultfd.c (ffffffff8145f208)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff8146363e)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/coredump.c (ffffffff81484a9e)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff81498cf4)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In ipc/shm.c (ffffffff8159eeba)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a79afb)
Location: include/linux/mmap_lock.h:102
Inline: True
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
In arch/x86/entry/vdso/vma.c (ffffffff81004c9c)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
```
```
In kernel/fork.c (ffffffff810e6f5f)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff8110e67d)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_vma
```
```
In kernel/events/uprobes.c (ffffffff8134eff2)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_add_vma
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/util.c (ffffffff8139186e)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff813c2759)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff813c9fd4)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff813cdb7d)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff813d1c85)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/madvise.c (ffffffff813f6431)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
```
```
In mm/mempolicy.c (ffffffff81419b2f)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff8141c7c2)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81422bf0)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/khugepaged.c (ffffffff8144cd4e)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/ptdump.c (ffffffff814726d9)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff81484984)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:alloc_bprm
  - fs/exec.c:setup_arg_pages
```
```
In fs/userfaultfd.c (ffffffff814eef7e)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff814f272e)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/coredump.c (ffffffff81517f6e)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff8152cffd)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In ipc/shm.c (ffffffff816485d6)
Location: include/linux/mmap_lock.h:102
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
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
In arch/x86/entry/vdso/vma.c (ffffffff81004484)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
```
```
In arch/x86/kernel/process_64.c (ffffffff8104a7c1)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
```
```
In kernel/fork.c (ffffffff810f2a20)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff8111ac56)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_vma
```
```
In kernel/trace/trace_events_user.c (ffffffff812c72de)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_mm_remove
```
```
In kernel/events/uprobes.c (ffffffff813801b8)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_add_vma
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/util.c (ffffffff813c4244)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/memory.c (ffffffff813f1840)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/memory.c:lock_mm_and_find_vma
```
```
In mm/mlock.c (ffffffff813f76a1)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff813fe516)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:do_vmi_munmap
  - mm/mmap.c:expand_stack
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff814023c7)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff8140678d)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/madvise.c (ffffffff81429292)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
```
```
In mm/mempolicy.c (ffffffff8144cfd5)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff8144fd75)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81457c09)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/khugepaged.c (ffffffff814824ca)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/ptdump.c (ffffffff814a6e2d)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff814b9567)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:alloc_bprm
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff81525f27)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff81529367)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/binfmt_elf.c (ffffffff81546a80)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff815497ff)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff8154f86a)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff81564cf7)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In ipc/shm.c (ffffffff81680b2a)
Location: include/linux/mmap_lock.h:131
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
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
In arch/x86/entry/vdso/vma.c (ffffffff81006d93)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
```
```
In arch/x86/kernel/process_64.c (ffffffff81051914)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
```
```
In arch/x86/kernel/shstk.c (ffffffff810ca173)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/shstk.c:alloc_shstk
```
```
In kernel/fork.c (ffffffff810fc05c)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff811247ac)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_vma
```
```
In kernel/trace/trace_events_user.c (ffffffff812e3c9e)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_mm_remove
```
```
In kernel/events/uprobes.c (ffffffff813a9568)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_add_vma
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/util.c (ffffffff813eedf6)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/memory.c (ffffffff8141c520)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - mm/memory.c:lock_mm_and_find_vma
```
```
In mm/mlock.c (ffffffff81423281)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff8142a965)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:do_vmi_munmap
  - mm/mmap.c:expand_stack
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff8142e9f7)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff81432e9c)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/madvise.c (ffffffff81462ac2)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
```
```
In mm/mempolicy.c (ffffffff814868c8)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff81489aa5)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff814926d9)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/khugepaged.c (ffffffff814af263)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/ptdump.c (ffffffff814d7e2d)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff814ec06b)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:alloc_bprm
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff81559983)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff8155e239)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/binfmt_elf.c (ffffffff8157bed0)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8157ea7f)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff815856a9)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff8159b7b6)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In ipc/shm.c (ffffffff816bcf49)
Location: include/linux/mmap_lock.h:129
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
