# Function: <code>vma_find</code>

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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004c84)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In kernel/fork.c (ffffffff810e6a2d)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/acct.c (ffffffff811fd7cf)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/events/core.c (ffffffff813371ad)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff813501cd)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:update_ref_ctr
```
```
In mm/oom_kill.c (ffffffff81362c43)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/vmscan.c (ffffffff813775bf)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - mm/vmscan.c:get_next_vma
```
```
In mm/mlock.c (ffffffff813c2e62)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff813cc58f)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:count_vma_pages_range
```
```
In mm/swapfile.c (ffffffff813ffbab)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff81419a7f)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/ksm.c (ffffffff81420661)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff8144c136)
Location: include/linux/mm.h:672
Inline: True
```
```
In fs/exec.c (ffffffff81483438)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
```
In fs/userfaultfd.c (ffffffff814f0611)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_prep
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/proc/task_mmu.c (ffffffff8152c499)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_next
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff81537f5a)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
```
```
In ipc/shm.c (ffffffff816484e4)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
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
In mm/mlock.c (ffffffff813f80d0)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
```
```
In mm/mmap.c (ffffffff81400ee9)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:do_vmi_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:count_vma_pages_range
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff8140427a)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mempolicy.c (ffffffff8144cf11)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
```
```
In mm/userfaultfd.c (ffffffff814a2745)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
```
```
In fs/userfaultfd.c (ffffffff81525bab)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
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
In mm/mlock.c (ffffffff81423c9f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
```
```
In mm/mmap.c (ffffffff8142d524)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:do_vmi_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:count_vma_pages_range
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff81430854)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mempolicy.c (ffffffff81486800)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
```
```
In mm/userfaultfd.c (ffffffff814d2804)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
```
```
In fs/userfaultfd.c (ffffffff8155988e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
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
