# Function: <code>get_mm_counter</code>

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
In kernel/fork.c (ffffffff8108000e)
Location: include/linux/mm.h:1355
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff81083d31)
Location: include/linux/mm.h:1355
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff81092976)
Location: include/linux/mm.h:1355
Inline: True
Inline callers:
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
```
```
In kernel/sched/fair.c (ffffffff810b1df0)
Location: include/linux/mm.h:1355
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_scan_min
  - kernel/sched/fair.c:task_scan_min
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
```
```
In kernel/tsacct.c (ffffffff8113f018)
Location: include/linux/mm.h:1355
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff81208bed)
Location: include/linux/mm.h:1355
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/memory.c (ffffffff811bde03)
Location: include/linux/mm.h:1355
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff811c4182)
Location: include/linux/mm.h:1355
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff811cb1e6)
Location: include/linux/mm.h:1355
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In fs/exec.c (ffffffff8121388c)
Location: include/linux/mm.h:1355
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81277174)
Location: include/linux/mm.h:1355
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
```
```
In fs/proc/array.c (ffffffff81280201)
Location: include/linux/mm.h:1355
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffffffff8108192e)
Location: include/linux/mm.h:1449
Inline: True
```
```
In kernel/exit.c (ffffffff810870f9)
Location: include/linux/mm.h:1449
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff81095af7)
Location: include/linux/mm.h:1449
Inline: True
Inline callers:
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
```
```
In kernel/sched/fair.c (ffffffff810b490d)
Location: include/linux/mm.h:1449
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/tsacct.c (ffffffff81147602)
Location: include/linux/mm.h:1449
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff811a4b1e)
Location: include/linux/mm.h:1449
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task
  - mm/oom_kill.c:__oom_reap_task
  - mm/oom_kill.c:__oom_reap_task
```
```
In mm/memory.c (ffffffff811d9623)
Location: include/linux/mm.h:1449
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff811e0042)
Location: include/linux/mm.h:1449
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff811e82a0)
Location: include/linux/mm.h:1449
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff811ee70e)
Location: include/linux/mm.h:1449
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffffffff8123a33a)
Location: include/linux/mm.h:1449
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812a36fe)
Location: include/linux/mm.h:1449
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff812ad24d)
Location: include/linux/mm.h:1449
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffffffff8108631e)
Location: include/linux/mm.h:1423
Inline: True
```
```
In kernel/exit.c (ffffffff8108c049)
Location: include/linux/mm.h:1423
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff8109aae7)
Location: include/linux/mm.h:1423
Inline: True
Inline callers:
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
```
```
In kernel/sched/fair.c (ffffffff810baeed)
Location: include/linux/mm.h:1423
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/tsacct.c (ffffffff811514a2)
Location: include/linux/mm.h:1423
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff811b578c)
Location: include/linux/mm.h:1423
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff811e8a33)
Location: include/linux/mm.h:1423
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff811eff92)
Location: include/linux/mm.h:1423
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff811f96c9)
Location: include/linux/mm.h:1423
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff811ff05e)
Location: include/linux/mm.h:1423
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffffffff8124d091)
Location: include/linux/mm.h:1423
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812b90dd)
Location: include/linux/mm.h:1423
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff812c2b49)
Location: include/linux/mm.h:1423
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffffffff8108351b)
Location: include/linux/mm.h:1455
Inline: True
```
```
In kernel/exit.c (ffffffff8108920f)
Location: include/linux/mm.h:1455
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff8109b1c9)
Location: include/linux/mm.h:1455
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffffffff810b579d)
Location: include/linux/mm.h:1455
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/tsacct.c (ffffffff81153b22)
Location: include/linux/mm.h:1455
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff811bd4d5)
Location: include/linux/mm.h:1455
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
```
```
In mm/memory.c (ffffffff811f3ca3)
Location: include/linux/mm.h:1455
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff811faf12)
Location: include/linux/mm.h:1455
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff81204303)
Location: include/linux/mm.h:1455
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81209c14)
Location: include/linux/mm.h:1455
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffffffff81259033)
Location: include/linux/mm.h:1455
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812c744e)
Location: include/linux/mm.h:1455
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff812cfe4c)
Location: include/linux/mm.h:1455
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffffffff81089e4e)
Location: include/linux/mm.h:1529
Inline: True
```
```
In kernel/exit.c (ffffffff8108ff63)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810a1ea9)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffffffff810bcabd)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/tsacct.c (ffffffff81160322)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff811d20fa)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
```
```
In mm/memory.c (ffffffff8120b963)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff81213432)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff8121d0d2)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81222d44)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffffffff8127b1c7)
Location: include/linux/mm.h:1529
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812eb270)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff812f45ce)
Location: include/linux/mm.h:1529
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffffffff8108bb0c)
Location: include/linux/mm.h:1616
Inline: True
Inline callers:
  - kernel/fork.c:copy_mm
  - kernel/fork.c:copy_mm
  - kernel/fork.c:copy_mm
```
```
In kernel/exit.c (ffffffff81093830)
Location: include/linux/mm.h:1616
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810a82b9)
Location: include/linux/mm.h:1616
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffffffff810c4817)
Location: include/linux/mm.h:1616
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/tsacct.c (ffffffff8116f252)
Location: include/linux/mm.h:1616
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff811f3cfe)
Location: include/linux/mm.h:1616
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
```
```
In mm/memory.c (ffffffff8122c673)
Location: include/linux/mm.h:1616
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff812343d2)
Location: include/linux/mm.h:1616
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff8123efc0)
Location: include/linux/mm.h:1616
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81244b6f)
Location: include/linux/mm.h:1616
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffffffff812a2359)
Location: include/linux/mm.h:1616
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81317412)
Location: include/linux/mm.h:1616
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff813219f8)
Location: include/linux/mm.h:1616
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffffffff81095930)
Location: include/linux/mm.h:1686
Inline: True
```
```
In kernel/exit.c (ffffffff8109baf6)
Location: include/linux/mm.h:1686
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810b0fc9)
Location: include/linux/mm.h:1686
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffffffff810cda77)
Location: include/linux/mm.h:1686
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/tsacct.c (ffffffff8117cd52)
Location: include/linux/mm.h:1686
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff81204992)
Location: include/linux/mm.h:1686
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
```
```
In mm/memory.c (ffffffff8123fcc9)
Location: include/linux/mm.h:1686
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff81247b82)
Location: include/linux/mm.h:1686
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff812535d9)
Location: include/linux/mm.h:1686
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81258f25)
Location: include/linux/mm.h:1686
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffffffff812b74ba)
Location: include/linux/mm.h:1686
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8132e887)
Location: include/linux/mm.h:1686
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff81338b08)
Location: include/linux/mm.h:1686
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffffffff81097c01)
Location: include/linux/mm.h:1681
Inline: True
Inline callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
```
```
In kernel/exit.c (ffffffff810a03ed)
Location: include/linux/mm.h:1681
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810b6b06)
Location: include/linux/mm.h:1681
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffffffff810d5d87)
Location: include/linux/mm.h:1681
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/tsacct.c (ffffffff81189c12)
Location: include/linux/mm.h:1681
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff8121c13e)
Location: include/linux/mm.h:1681
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/memory.c (ffffffff81251e0f)
Location: include/linux/mm.h:1681
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff81259da5)
Location: include/linux/mm.h:1681
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff81265842)
Location: include/linux/mm.h:1681
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8127474d)
Location: include/linux/mm.h:1681
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffffffff812d4f40)
Location: include/linux/mm.h:1681
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8135732a)
Location: include/linux/mm.h:1681
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff813611aa)
Location: include/linux/mm.h:1681
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffffffff8109e2c1)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
```
```
In kernel/exit.c (ffffffff810a640b)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810bd0c6)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffffffff810e0387)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/tsacct.c (ffffffff81195b22)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff81229af5)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/memory.c (ffffffff812603bf)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff81268255)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff81274157)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812836dd)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffffffff812e6ac9)
Location: include/linux/mm.h:1653
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8136ee5d)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff8137940a)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffffffff810a58b1)
Location: include/linux/mm.h:1865
Inline: True
Inline callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
```
```
In kernel/exit.c (ffffffff810ae1ce)
Location: include/linux/mm.h:1865
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810c4806)
Location: include/linux/mm.h:1865
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffffffff810e86e7)
Location: include/linux/mm.h:1865
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/tsacct.c (ffffffff811ab170)
Location: include/linux/mm.h:1865
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff8125694b)
Location: include/linux/mm.h:1865
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reap_task_mm
  - mm/oom_kill.c:oom_reap_task_mm
  - mm/oom_kill.c:oom_reap_task_mm
```
```
In mm/memory.c (ffffffff8129098f)
Location: include/linux/mm.h:1865
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff81298835)
Location: include/linux/mm.h:1865
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff812a53d8)
Location: include/linux/mm.h:1865
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812b5540)
Location: include/linux/mm.h:1865
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffffffff8131dd4e)
Location: include/linux/mm.h:1865
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
```
```
In fs/proc/task_mmu.c (ffffffff813b7193)
Location: include/linux/mm.h:1865
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff813c24b2)
Location: include/linux/mm.h:1865
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffffffff810a10a1)
Location: include/linux/mm.h:1910
Inline: True
Inline callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
```
```
In kernel/exit.c (ffffffff810a9881)
Location: include/linux/mm.h:1910
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810bfc06)
Location: include/linux/mm.h:1910
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffffffff810e62f7)
Location: include/linux/mm.h:1910
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/tsacct.c (ffffffff811a8720)
Location: include/linux/mm.h:1910
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff812614f1)
Location: include/linux/mm.h:1910
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reap_task_mm
  - mm/oom_kill.c:oom_reap_task_mm
  - mm/oom_kill.c:oom_reap_task_mm
```
```
In mm/memory.c (ffffffff8129b41f)
Location: include/linux/mm.h:1910
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff812a39b5)
Location: include/linux/mm.h:1910
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff812b086c)
Location: include/linux/mm.h:1910
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812c0800)
Location: include/linux/mm.h:1910
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffffffff81329217)
Location: include/linux/mm.h:1910
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
```
```
In fs/proc/task_mmu.c (ffffffff813c8be8)
Location: include/linux/mm.h:1910
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff813d4640)
Location: include/linux/mm.h:1910
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffffffff810a1e1a)
Location: include/linux/mm.h:1918
Inline: True
Inline callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
```
```
In kernel/exit.c (ffffffff810aa8bd)
Location: include/linux/mm.h:1918
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810c1636)
Location: include/linux/mm.h:1918
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffffffff810e82d6)
Location: include/linux/mm.h:1918
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/tsacct.c (ffffffff811a92b3)
Location: include/linux/mm.h:1918
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff81265d2d)
Location: include/linux/mm.h:1918
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/memory.c (ffffffff812a072b)
Location: include/linux/mm.h:1918
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff812a91df)
Location: include/linux/mm.h:1918
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff812b5e97)
Location: include/linux/mm.h:1918
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812c778f)
Location: include/linux/mm.h:1918
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffffffff8132f021)
Location: include/linux/mm.h:1918
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
```
```
In fs/proc/task_mmu.c (ffffffff813cfc27)
Location: include/linux/mm.h:1918
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff813db47d)
Location: include/linux/mm.h:1918
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffffffff810b39ea)
Location: include/linux/mm.h:1947
Inline: True
Inline callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
```
```
In kernel/exit.c (ffffffff810bc3e4)
Location: include/linux/mm.h:1947
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810d4126)
Location: include/linux/mm.h:1947
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffffffff811008fd)
Location: include/linux/mm.h:1947
Inline: True
```
```
In kernel/tsacct.c (ffffffff811d2e03)
Location: include/linux/mm.h:1947
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff812a2557)
Location: include/linux/mm.h:1947
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/memory.c (ffffffff812e16bb)
Location: include/linux/mm.h:1947
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff812ea83f)
Location: include/linux/mm.h:1947
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff812f8510)
Location: include/linux/mm.h:1947
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8130c54f)
Location: include/linux/mm.h:1947
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffffffff8137c811)
Location: include/linux/mm.h:1947
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
```
```
In fs/proc/task_mmu.c (ffffffff81421004)
Location: include/linux/mm.h:1947
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff8142cb0b)
Location: include/linux/mm.h:1947
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffffffff810c9c39)
Location: include/linux/mm.h:2025
Inline: True
Inline callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
```
```
In kernel/exit.c (ffffffff810d2ed3)
Location: include/linux/mm.h:2025
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810ece06)
Location: include/linux/mm.h:2025
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffffffff8111b99d)
Location: include/linux/mm.h:2025
Inline: True
```
```
In kernel/tsacct.c (ffffffff812077c3)
Location: include/linux/mm.h:2025
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff812fa092)
Location: include/linux/mm.h:2025
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
```
```
In mm/memory.c (ffffffff81342221)
Location: include/linux/mm.h:2025
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff8134d4d0)
Location: include/linux/mm.h:2025
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff8135e5b0)
Location: include/linux/mm.h:2025
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81375ae3)
Location: include/linux/mm.h:2025
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffffffff813fa8b2)
Location: include/linux/mm.h:2025
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
```
```
In fs/proc/task_mmu.c (ffffffff81498e9a)
Location: include/linux/mm.h:2025
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff814a63df)
Location: include/linux/mm.h:2025
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffffffff810e7239)
Location: include/linux/mm.h:2201
Inline: True
```
```
In kernel/exit.c (ffffffff810f1a0e)
Location: include/linux/mm.h:2201
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff8110e1a6)
Location: include/linux/mm.h:2201
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffffffff811434fd)
Location: include/linux/mm.h:2201
Inline: True
```
```
In kernel/tsacct.c (ffffffff8124fb93)
Location: include/linux/mm.h:2201
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff813647c2)
Location: include/linux/mm.h:2201
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
```
```
In mm/vmscan.c (ffffffff813771e6)
Location: include/linux/mm.h:2201
Inline: True
Inline callers:
  - mm/vmscan.c:should_skip_mm
  - mm/vmscan.c:should_skip_mm
  - mm/vmscan.c:should_skip_mm
```
```
In mm/memory.c (ffffffff813ba329)
Location: include/linux/mm.h:2201
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff813c65d4)
Location: include/linux/mm.h:2201
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff813d9481)
Location: include/linux/mm.h:2201
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff813f3080)
Location: include/linux/mm.h:2201
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffffffff8148390c)
Location: include/linux/mm.h:2201
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
```
```
In fs/proc/task_mmu.c (ffffffff8152d0f2)
Location: include/linux/mm.h:2201
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff8153ba1f)
Location: include/linux/mm.h:2201
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffffffff810f2d49)
Location: include/linux/mm.h:2521
Inline: True
```
```
In kernel/exit.c (ffffffff810fd991)
Location: include/linux/mm.h:2521
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff8111a26d)
Location: include/linux/mm.h:2521
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffffffff81152616)
Location: include/linux/mm.h:2521
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/tsacct.c (ffffffff81266f43)
Location: include/linux/mm.h:2521
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff81396c9d)
Location: include/linux/mm.h:2521
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
```
```
In mm/vmscan.c (ffffffff813a9237)
Location: include/linux/mm.h:2521
Inline: True
Inline callers:
  - mm/vmscan.c:should_skip_mm
  - mm/vmscan.c:should_skip_mm
  - mm/vmscan.c:should_skip_mm
```
```
In mm/memory.c (ffffffff813eecd3)
Location: include/linux/mm.h:2521
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
```
```
In mm/mmap.c (ffffffff813facdd)
Location: include/linux/mm.h:2521
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff8140db72)
Location: include/linux/mm.h:2521
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81426adf)
Location: include/linux/mm.h:2521
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffffffff814b91c7)
Location: include/linux/mm.h:2521
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
```
```
In fs/proc/task_mmu.c (ffffffff81564e2b)
Location: include/linux/mm.h:2521
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff81573d4a)
Location: include/linux/mm.h:2521
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffffffff810fb8a9)
Location: include/linux/mm.h:2570
Inline: True
```
```
In kernel/exit.c (ffffffff8110680c)
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff81123beb)
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffffffff8115e5c6)
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/tsacct.c (ffffffff81280ed3)
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:acct_account_cputime
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff813c0a0d)
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
```
```
In mm/memory.c (ffffffff8141a783)
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
```
```
In mm/mmap.c (ffffffff81426d15)
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff8143a2cc)
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8146071f)
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffffffff814eb9b7)
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
```
```
In fs/proc/task_mmu.c (ffffffff8159b8ea)
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff815ac719)
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffff8000100f2e60)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
```
```
In kernel/exit.c (ffff8000100fd388)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffff800010119b9c)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffff800010140190)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/tsacct.c (ffff80001020dde4)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffff8000102b78d4)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/memory.c (ffff8000102f76b8)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffff8000102ff42c)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffff800010309d9c)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffff80001031de88)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffff80001038edc0)
Location: include/linux/mm.h:1653
Inline: True
```
```
In fs/proc/task_mmu.c (ffff8000104392e0)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffff800010445870)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (c0351710)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
```
```
In kernel/exit.c (c035a498)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (c036e188)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/tsacct.c (c044c7bc)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (c04e4520)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/memory.c (c05196c4)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (c051e2f8)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (c05265e8)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (c053750c)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (c05752d8)
Location: include/linux/mm.h:1653
Inline: True
```
```
In fs/proc/task_mmu.c (c0600260)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (c060a94c)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (c000000000138b68)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
```
```
In kernel/exit.c (c0000000001441cc)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (c000000000161470)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (c00000000018f360)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/tsacct.c (c00000000028bf84)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (c00000000036f6ec)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/memory.c (c0000000003c0498)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (c0000000003cb228)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (c0000000003d9734)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (c0000000003f1a4c)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (c000000000485d58)
Location: include/linux/mm.h:1653
Inline: True
```
```
In fs/proc/task_mmu.c (c00000000054c140)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (c00000000055b2bc)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffffffe0000bf990)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
```
```
In kernel/exit.c (ffffffe0000c5c04)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffe0000d489a)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/tsacct.c (ffffffe00016eca8)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffe0001dbbb0)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/memory.c (ffffffe000207cbe)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffe00020d42c)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffe000213d4a)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffe000220e8c)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffffffe00025e792)
Location: include/linux/mm.h:1653
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffe0002d3044)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffe0002db82e)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffffffff81097be1)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
```
```
In kernel/exit.c (ffffffff8109fd2b)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810b7436)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffffffff810da537)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/tsacct.c (ffffffff8118e142)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff81222145)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/memory.c (ffffffff81258a0f)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff812608a5)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff8126c7a7)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8127bd2d)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffffffff812df0a9)
Location: include/linux/mm.h:1653
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8136743d)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff813719ea)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffffffff81086651)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
```
```
In kernel/exit.c (ffffffff8108e75b)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810a5d76)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffffffff810c9547)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/tsacct.c (ffffffff81181252)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff812152f5)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/memory.c (ffffffff8124aecf)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff81252cc5)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff8125e800)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8126dc0d)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffffffff812cf1b1)
Location: include/linux/mm.h:1653
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813580dd)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff813624c6)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffffffff81097b91)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
```
```
In kernel/exit.c (ffffffff8109fcdb)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810b6996)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffffffff810d68b7)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/tsacct.c (ffffffff8118bf12)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff8121fee5)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/memory.c (ffffffff812567af)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff8125e645)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff8126a547)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81279acd)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffffffff812dceb9)
Location: include/linux/mm.h:1653
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81364f0d)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff8136f4ba)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/fork.c (ffffffff8109f791)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
```
```
In kernel/exit.c (ffffffff810a7c4b)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810bed16)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
```
In kernel/sched/fair.c (ffffffff810e21c7)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
  - kernel/sched/fair.c:task_nr_scan_windows
```
```
In kernel/tsacct.c (ffffffff81199892)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:__acct_update_integrals
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff8122efdb)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/memory.c (ffffffff8126624f)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
```
```
In mm/mmap.c (ffffffff8126e095)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
  - mm/mmap.c:unmap_region
```
```
In mm/rmap.c (ffffffff81279f25)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812896bd)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
```
In fs/exec.c (ffffffff812edcaa)
Location: include/linux/mm.h:1653
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81377f4a)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_statm
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
```
```
In fs/proc/array.c (ffffffff81382e4a)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
```
</details>
</li>
</ul>

## Differences
