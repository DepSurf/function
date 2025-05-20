# Function: <code>mmap_write_lock</code>

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
In arch/x86/entry/vdso/vma.c (ffffffff81005cb6)
Location: include/linux/mmap_lock.h:14
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
```
```
In kernel/events/uprobes.c (ffffffff8124795f)
Location: include/linux/mmap_lock.h:14
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/util.c (ffffffff81272f46)
Location: include/linux/mmap_lock.h:14
Inline: True
```
```
In mm/mmap.c (ffffffff8129ce4f)
Location: include/linux/mmap_lock.h:14
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In mm/mprotect.c (ffffffff8129e202)
Location: include/linux/mmap_lock.h:14
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
```
In mm/mempolicy.c (ffffffff812cfe07)
Location: include/linux/mmap_lock.h:14
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff812d2556)
Location: include/linux/mmap_lock.h:14
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert
```
```
In mm/ksm.c (ffffffff812d6bd8)
Location: include/linux/mmap_lock.h:14
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/khugepaged.c (ffffffff812f2640)
Location: include/linux/mmap_lock.h:14
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/userfaultfd.c (ffffffff813725fb)
Location: include/linux/mmap_lock.h:14
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
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
In arch/x86/entry/vdso/vma.c (ffffffff81004c98)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
```
```
In kernel/events/uprobes.c (ffffffff81251fd1)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/util.c (ffffffff8127d6e5)
Location: include/linux/mmap_lock.h:68
Inline: True
```
```
In mm/mmap.c (ffffffff812a8203)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In mm/mprotect.c (ffffffff812a9692)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
```
```
In mm/mempolicy.c (ffffffff812db8c7)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff812dded5)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff812e2718)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/khugepaged.c (ffffffff812fcb16)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/userfaultfd.c (ffffffff8138044c)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/io_uring.c (ffffffff813969d0)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_unaccount_mem
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
In arch/x86/entry/vdso/vma.c (ffffffff81004c88)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
```
```
In kernel/events/uprobes.c (ffffffff81255f51)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/util.c (ffffffff812828d5)
Location: include/linux/mmap_lock.h:68
Inline: True
```
```
In mm/mmap.c (ffffffff812abc11)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In mm/mprotect.c (ffffffff812aeb22)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
```
```
In mm/mempolicy.c (ffffffff812e3150)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff812e5485)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff812e9ea8)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/khugepaged.c (ffffffff813038c4)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/userfaultfd.c (ffffffff81386ee5)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
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
In arch/x86/entry/vdso/vma.c (ffffffff810052a8)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
```
```
In kernel/events/uprobes.c (ffffffff81291c01)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/util.c (ffffffff812c09f5)
Location: include/linux/mmap_lock.h:68
Inline: True
```
```
In mm/mmap.c (ffffffff812ed318)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In mm/mprotect.c (ffffffff812f0306)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
```
```
In mm/mempolicy.c (ffffffff8132a4b6)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/sparse-vmemmap.c (ffffffff8132c637)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_free
```
```
In mm/mmu_notifier.c (ffffffff8132d075)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81331dd8)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/khugepaged.c (ffffffff8134d622)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/userfaultfd.c (ffffffff813d4175)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
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
In arch/x86/entry/vdso/vma.c (ffffffff81004308)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
```
```
In kernel/sys.c (ffffffff810e9ef9)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_vma
```
```
In kernel/events/uprobes.c (ffffffff812e73e2)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/util.c (ffffffff8131d684)
Location: include/linux/mmap_lock.h:68
Inline: True
```
```
In mm/mmap.c (ffffffff8135055d)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In mm/mprotect.c (ffffffff813536d6)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
```
```
In mm/mempolicy.c (ffffffff81399afa)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff8139d324)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff813a2f5f)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/khugepaged.c (ffffffff813c6790)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/userfaultfd.c (ffffffff8145eebe)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
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
In arch/x86/entry/vdso/vma.c (ffffffff81004c41)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
```
```
In kernel/sys.c (ffffffff8110a709)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_vma
```
```
In kernel/events/uprobes.c (ffffffff81350f02)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/util.c (ffffffff81391354)
Location: include/linux/mmap_lock.h:68
Inline: True
```
```
In mm/mmap.c (ffffffff813c9f49)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In mm/mprotect.c (ffffffff813cdb36)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
```
```
In mm/mempolicy.c (ffffffff81419a49)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff8141c7a4)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81422bdf)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/khugepaged.c (ffffffff8144cd24)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/ptdump.c (ffffffff8147269f)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/userfaultfd.c (ffffffff814eec11)
Location: include/linux/mmap_lock.h:68
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
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
In arch/x86/entry/vdso/vma.c (ffffffff81004421)
Location: include/linux/mmap_lock.h:97
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
```
```
In kernel/sys.c (ffffffff8111777d)
Location: include/linux/mmap_lock.h:97
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_vma
```
```
In kernel/trace/trace_events_user.c (ffffffff812c72c6)
Location: include/linux/mmap_lock.h:97
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_mm_remove
```
```
In kernel/events/uprobes.c (ffffffff81382141)
Location: include/linux/mmap_lock.h:97
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/util.c (ffffffff813c3d17)
Location: include/linux/mmap_lock.h:97
Inline: True
```
```
In mm/mmap.c (ffffffff813fe45e)
Location: include/linux/mmap_lock.h:97
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In mm/mprotect.c (ffffffff81402376)
Location: include/linux/mmap_lock.h:97
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
```
```
In mm/mempolicy.c (ffffffff8144cec5)
Location: include/linux/mmap_lock.h:97
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff8144fd54)
Location: include/linux/mmap_lock.h:97
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81457bef)
Location: include/linux/mmap_lock.h:97
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/khugepaged.c (ffffffff8148249d)
Location: include/linux/mmap_lock.h:97
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/ptdump.c (ffffffff814a6def)
Location: include/linux/mmap_lock.h:97
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff814ba1d1)
Location: include/linux/mmap_lock.h:97
Inline: True
Inline callers:
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff81525b42)
Location: include/linux/mmap_lock.h:97
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
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
In arch/x86/entry/vdso/vma.c (ffffffff81006d30)
Location: include/linux/mmap_lock.h:105
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
```
```
In arch/x86/kernel/shstk.c (ffffffff810ca12f)
Location: include/linux/mmap_lock.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/shstk.c:alloc_shstk
```
```
In kernel/fork.c (ffffffff810fc035)
Location: include/linux/mmap_lock.h:105
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/sys.c (ffffffff8112116d)
Location: include/linux/mmap_lock.h:105
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_vma
```
```
In kernel/trace/trace_events_user.c (ffffffff812e3c86)
Location: include/linux/mmap_lock.h:105
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_mm_remove
```
```
In kernel/events/uprobes.c (ffffffff813ab521)
Location: include/linux/mmap_lock.h:105
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/util.c (ffffffff813ee8c7)
Location: include/linux/mmap_lock.h:105
Inline: True
```
```
In mm/mmap.c (ffffffff8142a850)
Location: include/linux/mmap_lock.h:105
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
```
```
In mm/mprotect.c (ffffffff8142e9a6)
Location: include/linux/mmap_lock.h:105
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
```
```
In mm/mempolicy.c (ffffffff814867b4)
Location: include/linux/mmap_lock.h:105
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff81489a84)
Location: include/linux/mmap_lock.h:105
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff814926bf)
Location: include/linux/mmap_lock.h:105
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
```
```
In mm/khugepaged.c (ffffffff814af22e)
Location: include/linux/mmap_lock.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/ptdump.c (ffffffff814d7def)
Location: include/linux/mmap_lock.h:105
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff814ec751)
Location: include/linux/mmap_lock.h:105
Inline: True
Inline callers:
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff81559822)
Location: include/linux/mmap_lock.h:105
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
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
