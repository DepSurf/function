# Function: <code>vma_end_write_all</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004489)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
```
```
In arch/x86/kernel/process_64.c (ffffffff8104a7c6)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
```
```
In kernel/fork.c (ffffffff810f2a25)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff8111ac5f)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_vma
```
```
In kernel/trace/trace_events_user.c (ffffffff812c72e0)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_mm_remove
```
```
In kernel/events/uprobes.c (ffffffff813801ba)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_add_vma
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/util.c (ffffffff813c424f)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/memory.c (ffffffff813f17b6)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
```
```
In mm/mlock.c (ffffffff813f76a3)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff814013ac)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:do_vmi_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:expand_stack
  - mm/mmap.c:expand_stack
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff814023c9)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff81406792)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/madvise.c (ffffffff81429294)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
```
```
In mm/mempolicy.c (ffffffff8144cfd7)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff8144fd77)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81457c0e)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/khugepaged.c (ffffffff814824cf)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/ptdump.c (ffffffff814a6e2f)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff814b956c)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:alloc_bprm
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:get_arg_page
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff81525f2c)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff8152936e)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/binfmt_elf.c (ffffffff81546a85)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81549804)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff8154f86f)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff81564cfc)
Location: include/linux/mmap_lock.h:76
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In ipc/shm.c (ffffffff81680b2c)
Location: include/linux/mmap_lock.h:76
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
In arch/x86/entry/vdso/vma.c (ffffffff81006d98)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
```
```
In arch/x86/kernel/process_64.c (ffffffff81051919)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
```
```
In arch/x86/kernel/shstk.c (ffffffff810ca179)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/shstk.c:alloc_shstk
```
```
In kernel/fork.c (ffffffff810fc05e)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff811247b1)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_vma
```
```
In kernel/trace/trace_events_user.c (ffffffff812e3ca0)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_mm_remove
```
```
In kernel/events/uprobes.c (ffffffff813a956a)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_add_vma
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/util.c (ffffffff813eee03)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/memory.c (ffffffff8141c496)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
```
```
In mm/mlock.c (ffffffff81423283)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff8142a96a)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:do_vmi_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:expand_stack
  - mm/mmap.c:expand_stack
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff8142e9f9)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff81432ea1)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/madvise.c (ffffffff81462ac4)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
```
```
In mm/mempolicy.c (ffffffff814868ca)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff81489aa7)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff814926de)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/khugepaged.c (ffffffff814af26c)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/ptdump.c (ffffffff814d7e2f)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff814ec070)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:alloc_bprm
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:get_arg_page
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff81559988)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff8155e242)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/binfmt_elf.c (ffffffff8157bed5)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8157ea84)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff815856ae)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff8159b7bb)
Location: include/linux/mmap_lock.h:84
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In ipc/shm.c (ffffffff816bcf4b)
Location: include/linux/mmap_lock.h:84
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
