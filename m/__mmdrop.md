# Function: <code>__mmdrop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107dce0)
Location: kernel/fork.c:686
Inline: True
Direct callers:
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:idle_task_exit
  - mm/oom_kill.c:oom_kill_process
  - mm/mmu_context.c:use_mm
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:run_store
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__ksm_exit
  - mm/huge_memory.c:collect_mm_slot
  - mm/huge_memory.c:__khugepaged_exit
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/base.c:mem_release
```
**Symbols:**

```
ffffffff8107dce0-ffffffff8107dda6: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107f8d0)
Location: kernel/fork.c:699
Inline: True
Direct callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
  - mm/oom_kill.c:__oom_reap_task
  - mm/mmu_context.c:use_mm
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
**Symbols:**

```
ffffffff8107f8d0-ffffffff8107f999: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81083fb0)
Location: kernel/fork.c:850
Inline: True
Direct callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
  - mm/oom_kill.c:oom_kill_process
  - mm/mmu_context.c:use_mm
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
**Symbols:**

```
ffffffff81083fb0-ffffffff810840a0: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81080f00)
Location: kernel/fork.c:897
Inline: True
Direct callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
  - mm/oom_kill.c:oom_kill_process
  - mm/mmu_context.c:use_mm
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
**Symbols:**

```
ffffffff81080f00-ffffffff81080ff0: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81087800)
Location: kernel/fork.c:907
Inline: True
Direct callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
  - mm/oom_kill.c:oom_kill_process
  - mm/mmu_context.c:use_mm
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
**Symbols:**

```
ffffffff81087800-ffffffff810878d9: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/fork.c (0)
Location: kernel/fork.c:629
Inline: False
Direct callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
  - mm/oom_kill.c:oom_kill_process
  - mm/mmu_context.c:use_mm
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
**Symbols:**

```
ffffffff8108e380-ffffffff8108e3a8: __mmdrop.cold.44 (STB_LOCAL)
ffffffff8108a810-ffffffff8108a904: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/fork.c (0)
Location: kernel/fork.c:672
Inline: False
Direct callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
  - mm/oom_kill.c:__oom_kill_process
  - mm/mmu_context.c:use_mm
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
**Symbols:**

```
ffffffff81096610-ffffffff81096638: __mmdrop.cold.42 (STB_LOCAL)
ffffffff810927b0-ffffffff810928a4: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/fork.c (0)
Location: kernel/fork.c:678
Inline: False
Direct callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
  - mm/oom_kill.c:__oom_kill_process
  - mm/mmu_context.c:use_mm
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - mm/hmm.c:hmm_free_rcu
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
**Symbols:**

```
ffffffff8109ab50-ffffffff8109ab7c: __mmdrop.cold (STB_LOCAL)
ffffffff81096680-ffffffff81096768: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/fork.c (0)
Location: kernel/fork.c:690
Inline: False
Direct callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
  - mm/oom_kill.c:__oom_kill_process
  - mm/mmu_context.c:use_mm
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
**Symbols:**

```
ffffffff810a10bc-ffffffff810a10ed: __mmdrop.cold (STB_LOCAL)
ffffffff8109cd50-ffffffff8109ce3a: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/fork.c (0)
Location: kernel/fork.c:698
Inline: False
Direct callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/cpu.c:finish_cpu
  - kernel/kthread.c:kthread_use_mm
  - kernel/sched/core.c:finish_task_switch
  - mm/oom_kill.c:__oom_kill_process
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - fs/exec.c:exec_mmap
  - fs/exec.c:bprm_mm_init
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_sq_offload_start
  - fs/io_uring.c:io_poll_add
  - fs/io_uring.c:__io_req_aux_free
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:mem_release
```
**Symbols:**

```
ffffffff810a7f29-ffffffff810a7f5a: __mmdrop.cold (STB_LOCAL)
ffffffff810a3980-ffffffff810a3a6a: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/fork.c (0)
Location: kernel/fork.c:683
Inline: False
Direct callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/cpu.c:finish_cpu
  - kernel/kthread.c:kthread_use_mm
  - mm/oom_kill.c:__oom_kill_process
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_req_clean_work
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:mem_release
```
**Symbols:**

```
ffffffff81bdb0bc-ffffffff81bdb0ed: __mmdrop.cold (STB_LOCAL)
ffffffff8109f7c0-ffffffff8109f8d4: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/fork.c (0)
Location: kernel/fork.c:687
Inline: False
Direct callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/cpu.c:finish_cpu
  - kernel/kthread.c:kthread_use_mm
  - mm/oom_kill.c:__oom_kill_process
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/io_uring.c:io_ring_ctx_free
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:mem_release
```
**Symbols:**

```
ffffffff81bcd1ae-ffffffff81bcd1df: __mmdrop.cold (STB_LOCAL)
ffffffff810a08f0-ffffffff810a0a04: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/fork.c (0)
Location: kernel/fork.c:699
Inline: False
Direct callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/cpu.c:finish_cpu
  - kernel/kthread.c:kthread_use_mm
  - mm/oom_kill.c:__oom_kill_process
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/io_uring.c:io_ring_ctx_free
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:mem_release
```
**Symbols:**

```
ffffffff81ca391f-ffffffff81ca3935: __mmdrop.cold (STB_LOCAL)
ffffffff810b1d00-ffffffff810b1e78: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/fork.c (0)
Location: kernel/fork.c:788
Inline: False
Direct callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/cpu.c:finish_cpu
  - kernel/kthread.c:kthread_use_mm
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:mem_release
  - io_uring/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff81e5303b-ffffffff81e53051: __mmdrop.cold (STB_LOCAL)
ffffffff810c83c0-ffffffff810c857a: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e5620)
Location: kernel/fork.c:793
Inline: False
Direct callers:
  - kernel/fork.c:__mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/cpu.c:finish_cpu
  - kernel/kthread.c:kthread_use_mm
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/userfaultfd.c:new_userfaultfd
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:mem_release
  - io_uring/io_uring.c:io_ring_ctx_free
  - drivers/iommu/iommu.c:iommu_domain_free
```
**Symbols:**

```
ffffffff810e5620-ffffffff810e5872: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f0cd0)
Location: kernel/fork.c:915
Inline: False
Direct callers:
  - kernel/fork.c:__mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/cpu.c:finish_cpu
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/trace/trace_events_user.c:user_event_mm_destroy
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/userfaultfd.c:new_userfaultfd
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:mem_release
  - io_uring/io_uring.c:io_ring_ctx_free
  - drivers/iommu/iommu.c:iommu_domain_free
```
**Symbols:**

```
ffffffff810f0cd0-ffffffff810f0eec: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fa0c0)
Location: kernel/fork.c:913
Inline: False
Direct callers:
  - kernel/fork.c:__mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/cpu.c:finish_cpu
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/trace/trace_events_user.c:user_event_mm_destroy
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/userfaultfd.c:new_userfaultfd
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:mem_release
  - io_uring/io_uring.c:io_ring_ctx_free
  - drivers/iommu/iommu.c:iommu_domain_free
```
**Symbols:**

```
ffffffff810fa0c0-ffffffff810fa2ba: __mmdrop (STB_GLOBAL)
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
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f1d08)
Location: kernel/fork.c:690
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_put_kvm
  - virt/kvm/kvm_main.c:kvm_create_vm
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
  - mm/oom_kill.c:__oom_kill_process
  - mm/mmu_context.c:use_mm
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - fs/userfaultfd.c:__arm64_sys_userfaultfd
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
**Symbols:**

```
ffff8000100f1d08-ffff8000100f1e50: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c03501e8)
Location: kernel/fork.c:690
Inline: False
Direct callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
  - mm/oom_kill.c:__oom_kill_process
  - mm/mmu_context.c:use_mm
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_do_scan
  - fs/exec.c:__do_execve_file
  - fs/userfaultfd.c:__se_sys_userfaultfd
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
**Symbols:**

```
c03501e8-c0350398: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0000000001376b0)
Location: kernel/fork.c:690
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_exit_flush_lazy_tlb
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
  - mm/oom_kill.c:__oom_kill_process
  - mm/mmu_context.c:use_mm
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - fs/userfaultfd.c:__se_sys_userfaultfd
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
  - drivers/vfio/vfio_iommu_spapr_tce.c:tce_iommu_release
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvgpu_release
```
**Symbols:**

```
c0000000001376b0-c0000000001378c8: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000be7b8)
Location: kernel/fork.c:690
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_access
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmdrop_async_fn
  - kernel/sched/core.c:finish_task_switch
  - mm/oom_kill.c:__oom_kill_process
  - mm/mmu_context.c:use_mm
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_do_scan
  - fs/exec.c:__do_execve_file
  - fs/userfaultfd.c:__se_sys_userfaultfd
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
**Symbols:**

```
ffffffe0000be7b8-ffffffe0000be8b8: __mmdrop (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/fork.c (0)
Location: kernel/fork.c:690
Inline: False
Direct callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
  - mm/oom_kill.c:__oom_kill_process
  - mm/mmu_context.c:use_mm
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
**Symbols:**

```
ffffffff8109a9dc-ffffffff8109aa0d: __mmdrop.cold (STB_LOCAL)
ffffffff81096670-ffffffff8109675a: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/fork.c (0)
Location: kernel/fork.c:690
Inline: False
Direct callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
  - mm/oom_kill.c:__oom_kill_process
  - mm/mmu_context.c:use_mm
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
**Symbols:**

```
ffffffff8108941c-ffffffff8108944d: __mmdrop.cold (STB_LOCAL)
ffffffff810850f0-ffffffff810851da: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/fork.c (0)
Location: kernel/fork.c:690
Inline: False
Direct callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
  - mm/oom_kill.c:__oom_kill_process
  - mm/mmu_context.c:use_mm
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
**Symbols:**

```
ffffffff8109a98c-ffffffff8109a9bd: __mmdrop.cold (STB_LOCAL)
ffffffff81096620-ffffffff8109670a: __mmdrop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __mmdrop(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/fork.c (0)
Location: kernel/fork.c:690
Inline: False
Direct callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmdrop_async_fn
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
  - mm/oom_kill.c:__oom_kill_process
  - mm/mmu_context.c:use_mm
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
**Symbols:**

```
ffffffff810a260c-ffffffff810a263d: __mmdrop.cold (STB_LOCAL)
ffffffff8109e200-ffffffff8109e2ea: __mmdrop (STB_GLOBAL)
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
