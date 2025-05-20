# Function: <code>vma_next</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a64d6)
Location: mm/mmap.c:570
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:unmap_region
  - mm/mmap.c:vma_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ab7f6)
Location: mm/mmap.c:574
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:unmap_region
  - mm/mmap.c:vma_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ece91)
Location: mm/mmap.c:573
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:unmap_region
  - mm/mmap.c:vma_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8135010b)
Location: mm/mmap.c:579
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:unmap_region
  - mm/mmap.c:vma_merge
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
In arch/x86/entry/vdso/vma.c (ffffffff81004c84)
Location: include/linux/mm.h:677
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In kernel/fork.c (ffffffff810e6a2d)
Location: include/linux/mm.h:677
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/acct.c (ffffffff811fd7cf)
Location: include/linux/mm.h:677
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/events/core.c (ffffffff813371ad)
Location: include/linux/mm.h:677
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff813501cd)
Location: include/linux/mm.h:677
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:update_ref_ctr
```
```
In mm/oom_kill.c (ffffffff81362c43)
Location: include/linux/mm.h:677
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/vmscan.c (ffffffff813775bf)
Location: include/linux/mm.h:677
Inline: True
Inline callers:
  - mm/vmscan.c:get_next_vma
```
```
In mm/swapfile.c (ffffffff813ffbab)
Location: include/linux/mm.h:677
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff81418963)
Location: include/linux/mm.h:677
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/ksm.c (ffffffff81420661)
Location: include/linux/mm.h:677
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff8144c136)
Location: include/linux/mm.h:677
Inline: True
```
```
In fs/exec.c (ffffffff81483438)
Location: include/linux/mm.h:677
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
```
In fs/userfaultfd.c (ffffffff814ee071)
Location: include/linux/mm.h:677
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/proc/task_mmu.c (ffffffff8152c499)
Location: include/linux/mm.h:677
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_next
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff81537f5a)
Location: include/linux/mm.h:677
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
```
```
In ipc/shm.c (ffffffff816484e4)
Location: include/linux/mm.h:677
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
In arch/x86/entry/vdso/vma.c (ffffffff8100446c)
Location: include/linux/mm.h:878
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In kernel/fork.c (ffffffff810f23d5)
Location: include/linux/mm.h:878
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/fair.c (ffffffff811548e8)
Location: include/linux/mm.h:878
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/acct.c (ffffffff81212956)
Location: include/linux/mm.h:878
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/events/core.c (ffffffff81368091)
Location: include/linux/mm.h:878
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff813813a4)
Location: include/linux/mm.h:878
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:update_ref_ctr
```
```
In mm/oom_kill.c (ffffffff81395064)
Location: include/linux/mm.h:878
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/vmscan.c (ffffffff813a94b3)
Location: include/linux/mm.h:878
Inline: True
Inline callers:
  - mm/vmscan.c:get_next_vma
```
```
In mm/mlock.c (ffffffff813f7608)
Location: include/linux/mm.h:878
Inline: True
Inline callers:
  - mm/mlock.c:apply_mlockall_flags
```
```
In mm/mmap.c (ffffffff813fff44)
Location: include/linux/mm.h:878
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:__split_vma
```
```
In mm/mremap.c (ffffffff81406006)
Location: include/linux/mm.h:878
Inline: True
Inline callers:
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff81432a43)
Location: include/linux/mm.h:878
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff8144beaa)
Location: include/linux/mm.h:878
Inline: True
Inline callers:
  - mm/mempolicy.c:new_folio
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/ksm.c (ffffffff81457771)
Location: include/linux/mm.h:878
Inline: True
Inline callers:
  - mm/ksm.c:ksm_disable_merge_any
  - mm/ksm.c:ksm_enable_merge_any
  - mm/ksm.c:ksm_del_vmas
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff81481985)
Location: include/linux/mm.h:878
Inline: True
```
```
In fs/exec.c (ffffffff814b805c)
Location: include/linux/mm.h:878
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
```
In fs/userfaultfd.c (ffffffff81525175)
Location: include/linux/mm.h:878
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/coredump.c (ffffffff8154f832)
Location: include/linux/mm.h:878
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff81564d8d)
Location: include/linux/mm.h:878
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_next
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8157018e)
Location: include/linux/mm.h:878
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
```
```
In ipc/shm.c (ffffffff81680a2b)
Location: include/linux/mm.h:878
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
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81006d7b)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In kernel/fork.c (ffffffff810fbfa3)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/fair.c (ffffffff81169761)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/acct.c (ffffffff81229fef)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/bpf/task_iter.c (ffffffff8134999d)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_iter_task_vma_next
```
```
In kernel/events/core.c (ffffffff81390fb0)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff813aa753)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:update_ref_ctr
```
```
In mm/oom_kill.c (ffffffff813bee23)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/vmscan.c (ffffffff813d2eb2)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - mm/vmscan.c:get_next_vma
```
```
In mm/mlock.c (ffffffff81422a87)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - mm/mlock.c:apply_mlockall_flags
```
```
In mm/mmap.c (ffffffff8142c499)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:__split_vma
```
```
In mm/mremap.c (ffffffff81432636)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - mm/mremap.c:move_vma
```
```
In mm/swapfile.c (ffffffff8146be62)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff81483e27)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/ksm.c (ffffffff81492240)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - mm/ksm.c:ksm_disable_merge_any
  - mm/ksm.c:ksm_enable_merge_any
  - mm/ksm.c:ksm_del_vmas
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff814b0d8e)
Location: include/linux/mm.h:955
Inline: True
```
```
In fs/exec.c (ffffffff814ea55b)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
```
In fs/userfaultfd.c (ffffffff81559192)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/coredump.c (ffffffff81585671)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff8159b84c)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_next
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff815a8b25)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
```
```
In ipc/shm.c (ffffffff816bce4a)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
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
