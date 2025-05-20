# Function: <code>mas_find</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
void *mas_find(struct ma_state *mas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff82030850)
Location: lib/maple_tree.c:5994
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/acct.c:acct_collect
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:update_ref_ctr
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/vmscan.c:get_next_vma
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:do_mlock
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:do_mas_munmap
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:count_vma_pages_range
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_unmap_prep
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_next
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_readdir
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
```
**Symbols:**

```
ffffffff82030850-ffffffff820308e0: mas_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *mas_find(struct ma_state *mas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820ac6a0)
Location: lib/maple_tree.c:5969
Inline: True
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/acct.c:acct_collect
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:update_ref_ctr
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/vmscan.c:get_next_vma
  - mm/memory.c:unmap_vmas
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_vmi_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:__split_vma
  - mm/mmap.c:count_vma_pages_range
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:move_vma
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:new_folio
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/ksm.c:ksm_disable_merge_any
  - mm/ksm.c:ksm_enable_merge_any
  - mm/ksm.c:ksm_del_vmas
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/userfaultfd.c:mwriteprotect_range
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/coredump.c:dump_vma_snapshot
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_next
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_readdir
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
  - drivers/base/regmap/regcache-maple.c:regcache_maple_exit
  - drivers/base/regmap/regcache-maple.c:regcache_maple_sync
  - drivers/base/regmap/regcache-maple.c:regcache_maple_drop
  - drivers/base/regmap/regcache-maple.c:regcache_maple_write
  - drivers/base/regmap/regcache-maple.c:regcache_maple_write
```
**Symbols:**

```
ffffffff820ac6a0-ffffffff820ac77e: mas_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *mas_find(struct ma_state *mas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff8218d810)
Location: lib/maple_tree.c:6012
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/acct.c:acct_collect
  - kernel/bpf/task_iter.c:bpf_iter_task_vma_next
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:update_ref_ctr
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/vmscan.c:get_next_vma
  - mm/memory.c:unmap_vmas
  - mm/memory.c:free_pgtables
  - mm/memory.c:free_pgtables
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_vmi_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:__split_vma
  - mm/mmap.c:count_vma_pages_range
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mremap.c:move_vma
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/ksm.c:ksm_disable_merge_any
  - mm/ksm.c:ksm_enable_merge_any
  - mm/ksm.c:ksm_del_vmas
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/userfaultfd.c:mwriteprotect_range
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/coredump.c:dump_vma_snapshot
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_next
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_map_files_readdir
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
  - drivers/base/regmap/regcache-maple.c:regcache_maple_exit
  - drivers/base/regmap/regcache-maple.c:regcache_maple_sync
  - drivers/base/regmap/regcache-maple.c:regcache_maple_drop
  - drivers/base/regmap/regcache-maple.c:regcache_maple_write
  - drivers/base/regmap/regcache-maple.c:regcache_maple_write
```
**Symbols:**

```
ffffffff8218d810-ffffffff8218d96f: mas_find (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
