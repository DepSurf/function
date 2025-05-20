# Function: <code>mmdrop</code>

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
In kernel/fork.c (ffffffff8107ddc8)
Location: include/linux/sched.h:2579
Inline: True
```
```
In kernel/sched/core.c (ffffffff810a94a0)
Location: include/linux/sched.h:2579
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:idle_task_exit
```
```
In kernel/futex.c (ffffffff810ffcdd)
Location: include/linux/sched.h:2579
Inline: True
```
```
In mm/oom_kill.c (ffffffff81190f1d)
Location: include/linux/sched.h:2579
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/mmu_context.c (ffffffff811afd07)
Location: include/linux/sched.h:2579
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff811e3d71)
Location: include/linux/sched.h:2579
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff811e5209)
Location: include/linux/sched.h:2579
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__ksm_exit
```
```
In mm/huge_memory.c (ffffffff811f4366)
Location: include/linux/sched.h:2579
Inline: True
Inline callers:
  - mm/huge_memory.c:collect_mm_slot
  - mm/huge_memory.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff812139cb)
Location: include/linux/sched.h:2579
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81276b08)
Location: include/linux/sched.h:2579
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:pagemap_release
```
```
In fs/proc/base.c (ffffffff8127a751)
Location: include/linux/sched.h:2579
Inline: True
Inline callers:
  - fs/proc/base.c:mem_release
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
In kernel/fork.c (ffffffff8107fd2c)
Location: include/linux/sched.h:2829
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/sched/core.c (ffffffff810b1575)
Location: include/linux/sched.h:2829
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/futex.c (ffffffff81106e4d)
Location: include/linux/sched.h:2829
Inline: True
```
```
In mm/oom_kill.c (ffffffff811a4b94)
Location: include/linux/sched.h:2829
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task
```
```
In mm/mmu_context.c (ffffffff811c9096)
Location: include/linux/sched.h:2829
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff81202811)
Location: include/linux/sched.h:2829
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff81203d90)
Location: include/linux/sched.h:2829
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff81219746)
Location: include/linux/sched.h:2829
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff8123a402)
Location: include/linux/sched.h:2829
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81283d8d)
Location: include/linux/sched.h:2829
Inline: True
Inline callers:
  - fs/userfaultfd.c:SyS_userfaultfd
```
```
In fs/proc/task_mmu.c (ffffffff812a4471)
Location: include/linux/sched.h:2829
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff812a9afe)
Location: include/linux/sched.h:2829
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
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
In kernel/fork.c (ffffffff81084518)
Location: include/linux/sched.h:2929
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/sched/core.c (ffffffff810b7825)
Location: include/linux/sched.h:2929
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/futex.c (ffffffff8110e60d)
Location: include/linux/sched.h:2929
Inline: True
```
```
In mm/oom_kill.c (ffffffff811b586a)
Location: include/linux/sched.h:2929
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/mmu_context.c (ffffffff811d9176)
Location: include/linux/sched.h:2929
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff81214651)
Location: include/linux/sched.h:2929
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff81215db0)
Location: include/linux/sched.h:2929
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8122bcc6)
Location: include/linux/sched.h:2929
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff8124d165)
Location: include/linux/sched.h:2929
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812979fd)
Location: include/linux/sched.h:2929
Inline: True
Inline callers:
  - fs/userfaultfd.c:SyS_userfaultfd
```
```
In fs/proc/task_mmu.c (ffffffff812b9dd1)
Location: include/linux/sched.h:2929
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff812bf41e)
Location: include/linux/sched.h:2929
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
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
In kernel/fork.c (ffffffff81081483)
Location: include/linux/sched/mm.h:39
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/sched/core.c (ffffffff810b39e5)
Location: include/linux/sched/mm.h:39
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/futex.c (ffffffff8110febd)
Location: include/linux/sched/mm.h:39
Inline: True
```
```
In mm/oom_kill.c (ffffffff811bd5b1)
Location: include/linux/sched/mm.h:39
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/mmu_context.c (ffffffff811e1f86)
Location: include/linux/sched/mm.h:39
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff8121fad1)
Location: include/linux/sched/mm.h:39
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff812214a6)
Location: include/linux/sched/mm.h:39
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812377f2)
Location: include/linux/sched/mm.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff81259191)
Location: include/linux/sched/mm.h:39
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812a5814)
Location: include/linux/sched/mm.h:39
Inline: True
Inline callers:
  - fs/userfaultfd.c:SyS_userfaultfd
```
```
In fs/proc/task_mmu.c (ffffffff812c7021)
Location: include/linux/sched/mm.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff812cc039)
Location: include/linux/sched/mm.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
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
In kernel/fork.c (ffffffff81087d6b)
Location: include/linux/sched/mm.h:40
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/sched/core.c (ffffffff810bac85)
Location: include/linux/sched/mm.h:40
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/futex.c (ffffffff8111b1bd)
Location: include/linux/sched/mm.h:40
Inline: True
```
```
In mm/oom_kill.c (ffffffff811d21e9)
Location: include/linux/sched/mm.h:40
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/mmu_context.c (ffffffff811f7f26)
Location: include/linux/sched/mm.h:40
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff8123ace4)
Location: include/linux/sched/mm.h:40
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff8123c7b6)
Location: include/linux/sched/mm.h:40
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff81256b82)
Location: include/linux/sched/mm.h:40
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff8127b32b)
Location: include/linux/sched/mm.h:40
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812c8d24)
Location: include/linux/sched/mm.h:40
Inline: True
Inline callers:
  - fs/userfaultfd.c:SyS_userfaultfd
```
```
In fs/proc/task_mmu.c (ffffffff812eac25)
Location: include/linux/sched/mm.h:40
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff812f07d7)
Location: include/linux/sched/mm.h:40
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
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
In kernel/fork.c (ffffffff8108b24c)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/sched/core.c (ffffffff810c20e7)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/futex.c (ffffffff81127f4f)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In mm/oom_kill.c (ffffffff811f3e35)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/mmu_context.c (ffffffff812191da)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff8125e0a5)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff8125fd47)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8127ab52)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff812a2531)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812ef912)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
```
In fs/proc/task_mmu.c (ffffffff813183f1)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff8131dee6)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
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
In kernel/fork.c (ffffffff81092fe0)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/sched/core.c (ffffffff810cb407)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/futex.c (ffffffff8113378f)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In mm/oom_kill.c (ffffffff81205c5c)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mmu_context.c (ffffffff8122c13a)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff81272924)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff81274487)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8128f162)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff812b7692)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81304292)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
```
In fs/proc/task_mmu.c (ffffffff8132f271)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff813352c9)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
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
In kernel/fork.c (ffffffff8109711d)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/sched/core.c (ffffffff810d3475)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/futex.c (ffffffff8113e73f)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In mm/oom_kill.c (ffffffff8121c261)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mmu_context.c (ffffffff8123be4a)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff8128dee5)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff812905f5)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812a9a23)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/hmm.c (ffffffff812c2f29)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/hmm.c:hmm_free_rcu
```
```
In fs/exec.c (ffffffff812d4406)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8132558b)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
```
In fs/io_uring.c (ffffffff8133148b)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/proc/task_mmu.c (ffffffff81356da1)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff8135cdc6)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
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
In kernel/fork.c (ffffffff8109d81d)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/sched/core.c (ffffffff810dd9e5)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/futex.c (ffffffff8114a2b8)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In mm/oom_kill.c (ffffffff81229c2d)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mmu_context.c (ffffffff8124a29a)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff8129db03)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff812a0375)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812baf93)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff812e5f96)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8133831b)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
```
In fs/io_uring.c (ffffffff81345032)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/proc/task_mmu.c (ffffffff8136f371)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff81375536)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
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
In kernel/fork.c (ffffffff810a49dd)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/cpu.c (ffffffff810a8f89)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/cpu.c:finish_cpu
```
```
In kernel/kthread.c (ffffffff810d13ae)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/sched/core.c (ffffffff810df044)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
```
```
In mm/oom_kill.c (ffffffff81256a95)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mmu_notifier.c (ffffffff812d1bc4)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff812d6c08)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff812efe54)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff8131ddd5)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:bprm_mm_init
```
```
In fs/userfaultfd.c (ffffffff81372114)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
```
```
In fs/io_uring.c (ffffffff813850cd)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_sq_offload_start
  - fs/io_uring.c:io_poll_add
  - fs/io_uring.c:__io_req_aux_free
```
```
In fs/proc/task_mmu.c (ffffffff813b6a41)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff813bb691)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/base.c:mem_release
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
In kernel/fork.c (ffffffff810a00ed)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/cpu.c (ffffffff810a49d9)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/cpu.c:finish_cpu
```
```
In kernel/kthread.c (ffffffff810cbb8b)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/sched/core.c (ffffffff810dbd1b)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In mm/oom_kill.c (ffffffff81261630)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mmu_notifier.c (ffffffff812dd5c4)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff812e275b)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff812fb613)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff81328b78)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
```
```
In fs/userfaultfd.c (ffffffff8137ff3c)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
```
```
In fs/io_uring.c (ffffffff8138fa86)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_req_clean_work
```
```
In fs/proc/task_mmu.c (ffffffff813c80e1)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff813cd221)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/base.c:mem_release
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
In kernel/fork.c (ffffffff810a0ead)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/cpu.c (ffffffff810a56a9)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/cpu.c:finish_cpu
```
```
In kernel/kthread.c (ffffffff810cd4bb)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/sched/core.c (ffffffff810ddd3b)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In mm/oom_kill.c (ffffffff81265e70)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mmu_notifier.c (ffffffff812e4d44)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff812e9ee8)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff813023e3)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff8132e9d8)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
```
```
In fs/userfaultfd.c (ffffffff81386bef)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
```
```
In fs/io_uring.c (ffffffff8139aba9)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
```
```
In fs/proc/task_mmu.c (ffffffff813cf121)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff813d40f1)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/base.c:mem_release
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
In kernel/fork.c (ffffffff810b2398)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/cpu.c (ffffffff810b6ee9)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/cpu.c:finish_cpu
```
```
In kernel/kthread.c (ffffffff810e06ab)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/sched/core.c (ffffffff810f29b6)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In mm/oom_kill.c (ffffffff812a269a)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mmu_notifier.c (ffffffff8132cb54)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff81331e0f)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff8134c153)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff8137c1e8)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
```
```
In fs/userfaultfd.c (ffffffff813d3ef1)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
```
```
In fs/io_uring.c (ffffffff813e5129)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
```
```
In fs/proc/task_mmu.c (ffffffff814203b1)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff81425801)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/base.c:mem_release
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
In kernel/fork.c (ffffffff810c87c6)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/cpu.c (ffffffff810cd639)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - kernel/cpu.c:finish_cpu
```
```
In kernel/kthread.c (ffffffff810f9967)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/sched/core.c (ffffffff8110eff1)
Location: include/linux/sched/mm.h:42
Inline: True
```
```
In mm/oom_kill.c (ffffffff812fb1ba)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mmu_notifier.c (ffffffff8139cedf)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff813a3032)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff813c3800)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff813fb0f8)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
```
```
In fs/userfaultfd.c (ffffffff8145d900)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
```
```
In fs/proc/task_mmu.c (ffffffff81498331)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff8149ebc1)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - fs/proc/base.c:mem_release
```
```
In io_uring/io_uring.c (ffffffff81e910a0)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
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
In kernel/fork.c (ffffffff810e59a9)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - kernel/fork.c:__mmput
```
```
In kernel/cpu.c (ffffffff810eb6f9)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - kernel/cpu.c:finish_cpu
```
```
In kernel/kthread.c (ffffffff8111c6b7)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/sched/core.c (ffffffff81135e04)
Location: include/linux/sched/mm.h:42
Inline: True
```
```
In mm/oom_kill.c (ffffffff81364467)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mmu_notifier.c (ffffffff8141c30f)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff81422ccf)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff8144cbe5)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff81484a26)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
```
```
In fs/userfaultfd.c (ffffffff814ecdf5)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - fs/userfaultfd.c:new_userfaultfd
```
```
In fs/proc/task_mmu.c (ffffffff8152c521)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff81533911)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - fs/proc/base.c:mem_release
```
```
In io_uring/io_uring.c (ffffffff8178bae1)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
```
```
In drivers/iommu/iommu.c (ffffffff81acea2c)
Location: include/linux/sched/mm.h:42
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_domain_free
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
In kernel/fork.c (ffffffff810f101c)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - kernel/fork.c:__mmput
```
```
In kernel/cpu.c (ffffffff810f7339)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - kernel/cpu.c:finish_cpu
```
```
In kernel/kthread.c (ffffffff8112a8f2)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/sched/core.c (ffffffff81143575)
Location: include/linux/sched/mm.h:46
Inline: True
```
```
In kernel/trace/trace_events_user.c (ffffffff812c51ad)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_mm_destroy
```
```
In mm/oom_kill.c (ffffffff81396939)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mmu_notifier.c (ffffffff8144f8bf)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff81457d44)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff81482510)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff814b962b)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
```
```
In fs/userfaultfd.c (ffffffff81523b24)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - fs/userfaultfd.c:new_userfaultfd
```
```
In fs/proc/task_mmu.c (ffffffff815648e1)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff8156bb01)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - fs/proc/base.c:mem_release
```
```
In io_uring/io_uring.c (ffffffff817ccc26)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
```
```
In drivers/iommu/iommu.c (ffffffff81b1d43c)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_domain_free
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
In kernel/fork.c (ffffffff810fa3ec)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - kernel/fork.c:__mmput
```
```
In kernel/cpu.c (ffffffff811006e9)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - kernel/cpu.c:finish_cpu
```
```
In kernel/kthread.c (ffffffff81134f82)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/sched/core.c (ffffffff8114ea4f)
Location: include/linux/sched/mm.h:46
Inline: True
```
```
In kernel/trace/trace_events_user.c (ffffffff812e1a5d)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_mm_destroy
```
```
In mm/oom_kill.c (ffffffff813c0249)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mmu_notifier.c (ffffffff8148959f)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff81492814)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff814b1899)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff814ec0f9)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
```
```
In fs/userfaultfd.c (ffffffff815580a4)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - fs/userfaultfd.c:new_userfaultfd
```
```
In fs/proc/task_mmu.c (ffffffff8159b2c1)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff815a4271)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - fs/proc/base.c:mem_release
```
```
In io_uring/io_uring.c (ffffffff81811370)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
```
```
In drivers/iommu/iommu.c (ffffffff81b739c1)
Location: include/linux/sched/mm.h:46
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_domain_free
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
In virt/kvm/kvm_main.c (ffff8000100bcf58)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_put_kvm
  - virt/kvm/kvm_main.c:kvm_create_vm
```
```
In kernel/fork.c (ffff8000100f1f70)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/sched/core.c (ffff80001013d0fc)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/futex.c (ffff8000101b6acc)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In mm/oom_kill.c (ffff8000102b7a14)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mmu_context.c (ffff8000102e0018)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffff80001033cd20)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffff80001033fba8)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffff80001035c6f0)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffff80001038e33c)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In fs/userfaultfd.c (ffff8000103f6e00)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__arm64_sys_userfaultfd
```
```
In fs/io_uring.c (ffff800010403440)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/proc/task_mmu.c (ffff8000104397d8)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffff80001043f6c8)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
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
In kernel/fork.c (c0350e9c)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/sched/core.c (c038d2c0)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/futex.c (c0400cf8)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In mm/oom_kill.c (c04e469c)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mmu_context.c (c0504904)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (c0543888)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (c0545ec0)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_do_scan
```
```
In fs/exec.c (c05759f0)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In fs/userfaultfd.c (c05cdd3c)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__se_sys_userfaultfd
```
```
In fs/io_uring.c (c05d69c4)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/proc/task_mmu.c (c0600e44)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (c0606120)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
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
In arch/powerpc/mm/book3s64/radix_tlb.c (c000000000096540)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_exit_flush_lazy_tlb
```
```
In kernel/fork.c (c000000000137de8)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/sched/core.c (c00000000018be94)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/futex.c (c00000000021c1c8)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In mm/oom_kill.c (c00000000036f85c)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mmu_context.c (c00000000039f814)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (c0000000004186a0)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (c00000000041c46c)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
```
```
In mm/khugepaged.c (c000000000445e60)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (c000000000485e90)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In fs/userfaultfd.c (c0000000004fea74)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__se_sys_userfaultfd
```
```
In fs/io_uring.c (c00000000050fd60)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/proc/task_mmu.c (c00000000054babc)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (c000000000554c10)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
```
In drivers/vfio/vfio_iommu_spapr_tce.c (c000000000ab44a0)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_spapr_tce.c:tce_iommu_release
```
```
In drivers/vfio/pci/vfio_pci_nvlink2.c (c000000000abe1b4)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvgpu_release
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
In kernel/fork.c (ffffffe0000c0ed4)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_access
  - kernel/fork.c:mmput_async_fn
```
```
In kernel/sched/core.c (ffffffe0000e7088)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/futex.c (ffffffe00013c562)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In mm/oom_kill.c (ffffffe0001dbcc8)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mmu_context.c (ffffffe0001f77dc)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffe00023258c)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffe000234454)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_do_scan
```
```
In fs/exec.c (ffffffe00025ed58)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In fs/userfaultfd.c (ffffffe0002a8fb6)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__se_sys_userfaultfd
```
```
In fs/io_uring.c (ffffffe0002b0af6)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/proc/task_mmu.c (ffffffe0002d1c64)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffe0002d7372)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
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
In kernel/fork.c (ffffffff8109713d)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/sched/core.c (ffffffff810d7bd5)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/futex.c (ffffffff811428d8)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In mm/oom_kill.c (ffffffff8122227d)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mmu_context.c (ffffffff812428ea)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff812960e3)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff81298955)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812b3573)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff812de576)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In fs/userfaultfd.c (ffffffff813308fb)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
```
In fs/io_uring.c (ffffffff8133d612)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/proc/task_mmu.c (ffffffff81367951)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff8136db16)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
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
In kernel/fork.c (ffffffff81085bbd)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/sched/core.c (ffffffff810c64f5)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/futex.c (ffffffff81135c38)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In mm/oom_kill.c (ffffffff8121542d)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mmu_context.c (ffffffff812358ba)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff81287cf3)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff8128a515)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812a48f3)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff812cf257)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In fs/userfaultfd.c (ffffffff813214eb)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
```
In fs/io_uring.c (ffffffff8132e2d2)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/proc/task_mmu.c (ffffffff813585f1)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff8135e5a6)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
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
In kernel/fork.c (ffffffff810970ed)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/sched/core.c (ffffffff810d43c5)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/futex.c (ffffffff81140788)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In mm/oom_kill.c (ffffffff8122001d)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mmu_context.c (ffffffff8124068a)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff81293ef3)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff81296765)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812b1383)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff812dc386)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8132e3cb)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
```
In fs/io_uring.c (ffffffff8133b0e2)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/proc/task_mmu.c (ffffffff81365421)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff8136b5e6)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
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
In kernel/fork.c (ffffffff8109eeeb)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/sched/core.c (ffffffff810df7d5)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/futex.c (ffffffff8114d538)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In mm/oom_kill.c (ffffffff8122f11d)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mmu_context.c (ffffffff8124fde2)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff812a4133)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff812a654f)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812c16c3)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/exec.c (ffffffff812ed11b)
Location: include/linux/sched/mm.h:41
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81340ccb)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
```
In fs/io_uring.c (ffffffff8134e292)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/proc/task_mmu.c (ffffffff81378b01)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff8137ed44)
Location: include/linux/sched/mm.h:41
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
</details>
</li>
</ul>

## Differences
