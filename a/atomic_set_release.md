# Function: <code>atomic_set_release</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e49cc)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/jump_label.c (ffffffff8121122a)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff8122bef0)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff81292c08)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812a134f)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a23c0)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812aad46)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/kernfs/dir.c (ffffffff8136bfad)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
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
In kernel/sched/rt.c (ffffffff810efb9c)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/jump_label.c (ffffffff8121eeda)
Location: include/linux/atomic-fallback.h:89
Inline: True
```
```
In mm/vmscan.c (ffffffff81239dba)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff812a2988)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812b276f)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b38bd)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812bc317)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/kernfs/dir.c (ffffffff8138416c)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
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
In kernel/sched/rt.c (ffffffff810f8099)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - kernel/sched/rt.c:tell_cpu_to_push
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110f175)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_up_write
```
```
In kernel/jump_label.c (ffffffff8124ad20)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff81266276)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff812d7108)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812e7d0e)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812e8905)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page_tail
```
```
In mm/khugepaged.c (ffffffff812f1853)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8104bdfc)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In kernel/sched/rt.c (ffffffff810f62a9)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - kernel/sched/rt.c:tell_cpu_to_push
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110c335)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_up_write
```
```
In kernel/kprobes.c (ffffffff81193531)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:kprobe_flush_task
```
```
In kernel/jump_label.c (ffffffff81255110)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff81270c72)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff812f30fa)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812f3d20)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
```
```
In mm/khugepaged.c (ffffffff812fdda8)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8104d92b)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In kernel/sched/rt.c (ffffffff810f9529)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110e175)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_up_write
```
```
In kernel/kprobes.c (ffffffff811944e1)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:kprobe_flush_task
```
```
In kernel/events/core.c (ffffffff8124f4c9)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/jump_label.c (ffffffff81259610)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff8127575b)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff812f9493)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812fa180)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
```
```
In mm/khugepaged.c (ffffffff81304f17)
Location: include/asm-generic/atomic-instrumented.h:52
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8105508b)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In kernel/sched/rt.c (ffffffff81112ce9)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8112d8c5)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_up_write
```
```
In kernel/printk/printk.c (ffffffff811393a3)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
```
```
In kernel/kprobes.c (ffffffff811bd381)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:kprobe_flush_task
```
```
In kernel/events/core.c (ffffffff8128a149)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/jump_label.c (ffffffff812952cf)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff812b4bea)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff81342a42)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81343ea0)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
```
```
In mm/khugepaged.c (ffffffff8134ecaa)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
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
In kernel/sched/build_policy.c (ffffffff8112ffe3)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8114e8e5)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_up_write
```
```
In kernel/printk/printk.c (ffffffff8115bc13)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
```
```
In kernel/trace/rethook.c (ffffffff81268cfa)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_try_get
  - kernel/trace/rethook.c:rethook_add_node
  - kernel/trace/rethook.c:rethook_flush_task
```
```
In kernel/events/core.c (ffffffff812deaa8)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/jump_label.c (ffffffff812eb097)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff81313400)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff813b4f49)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff813b9bbf)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
```
```
In mm/khugepaged.c (ffffffff813c58dc)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
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
In arch/x86/kernel/alternative.c (ffffffff81059486)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In kernel/sched/build_policy.c (ffffffff8115a231)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8117d995)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_up_write
```
```
In kernel/printk/printk.c (ffffffff8118e633)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
```
```
In kernel/kexec_core.c (ffffffff811fff60)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:crash_get_memory_size
  - kernel/kexec_core.c:__crash_kexec
```
```
In kernel/kexec.c (ffffffff81200317)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
```
```
In kernel/kexec_file.c (ffffffff81201ddb)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
```
In kernel/trace/rethook.c (ffffffff812bafba)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_try_get
  - kernel/trace/rethook.c:rethook_add_node
  - kernel/trace/rethook.c:rethook_flush_task
```
```
In kernel/jump_label.c (ffffffff813550d7)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff81386850)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/hugetlb.c (ffffffff81412b65)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:__remove_hugetlb_folio
```
```
In mm/migrate.c (ffffffff814340d1)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff8143c667)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
```
```
In mm/khugepaged.c (ffffffff8144a23f)
Location: include/linux/atomic/atomic-instrumented.h:46
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
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
In arch/x86/kernel/alternative.c (ffffffff8105aa2d)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In kernel/sched/build_policy.c (ffffffff8116a441)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8118e635)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_up_write
```
```
In kernel/printk/printk.c (ffffffff8119ff93)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
```
```
In kernel/kexec_core.c (ffffffff812153c0)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:crash_get_memory_size
  - kernel/kexec_core.c:__crash_kexec
```
```
In kernel/kexec.c (ffffffff81215777)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
```
```
In kernel/kexec_file.c (ffffffff812171d5)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
```
In kernel/trace/rethook.c (ffffffff812debba)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_try_get
  - kernel/trace/rethook.c:rethook_add_node
  - kernel/trace/rethook.c:rethook_flush_task
```
```
In kernel/jump_label.c (ffffffff813865c7)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff813b6ce0)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/hugetlb.c (ffffffff8143e04b)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio_nodemask
  - mm/hugetlb.c:__remove_hugetlb_folio
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/migrate.c (ffffffff81469a11)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff81471cad)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
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
In arch/x86/kernel/alternative.c (ffffffff81061ced)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In kernel/sched/build_policy.c (ffffffff81177b01)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8119cfe5)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_up_write
```
```
In kernel/power/swap.c (ffffffff811a9719)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
```
```
In kernel/printk/printk.c (ffffffff811aeff3)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
```
```
In kernel/smp.c (ffffffff81225c08)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - kernel/smp.c:__flush_smp_call_function_queue
```
```
In kernel/crash_core.c (ffffffff8122a2a2)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - kernel/crash_core.c:crash_handle_hotplug_event
  - kernel/crash_core.c:crash_check_update_elfcorehdr
```
```
In kernel/kexec_core.c (ffffffff8122d365)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:crash_get_memory_size
  - kernel/kexec_core.c:__crash_kexec
```
```
In kernel/kexec.c (ffffffff8122d724)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
```
```
In kernel/kexec_file.c (ffffffff8122f0dc)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
```
In kernel/bpf/ringbuf.c (ffffffff81357cdf)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
```
```
In kernel/jump_label.c (ffffffff813afa87)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff813dfba0)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/hugetlb.c (ffffffff81477cdc)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio_nodemask
  - mm/hugetlb.c:__remove_hugetlb_folio
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/migrate.c (ffffffff81498982)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff814a243c)
Location: include/linux/atomic/atomic-instrumented.h:83
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
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
In kernel/sched/rt.c (ffff800010150fac)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/jump_label.c (ffff8000102ab098)
Location: include/linux/atomic-fallback.h:89
Inline: True
```
```
In mm/vmscan.c (ffff8000102caed8)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffff8000103423d8)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffff800010352fd0)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffff80001035494c)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffff80001035d490)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/kernfs/dir.c (ffff80001045273c)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d51d4)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
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
In kernel/sched/rt.c (c039c51c)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/bpf/helpers.c (c04a9030)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_unlock
```
```
In mm/vmscan.c (c04f5048)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (c0548130)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/slub.c (c054d5a4)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (c05526cc)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In fs/dcache.c (c0588f38)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (c05edee8)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/kernfs/dir.c (c0614c94)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
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
In kernel/sched/rt.c (c0000000001a1e38)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/bpf/helpers.c (c00000000031efd8)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_unlock
```
```
In kernel/jump_label.c (c00000000035eca0)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (c00000000038783c)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (c00000000041fdc0)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (c000000000439b6c)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (c00000000043b95c)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (c000000000448f8c)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/kernfs/dir.c (c00000000056a860)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
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
In kernel/sched/rt.c (ffffffe0000f95fa)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/bpf/helpers.c (ffffffe0001aedb4)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_unlock
```
```
In mm/vmscan.c (ffffffe0001e9ba2)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffe0002365f2)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffe00023f95e)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In fs/kernfs/dir.c (ffffffe0002e5274)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
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
In kernel/sched/rt.c (ffffffff810e948c)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/jump_label.c (ffffffff8121752a)
Location: include/linux/atomic-fallback.h:89
Inline: True
```
```
In mm/vmscan.c (ffffffff8123240a)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff8129af68)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812aad4f)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812abe9d)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812b48f7)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/kernfs/dir.c (ffffffff8137c74c)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
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
In kernel/sched/rt.c (ffffffff810d8f5c)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/jump_label.c (ffffffff8120a28a)
Location: include/linux/atomic-fallback.h:89
Inline: True
```
```
In mm/vmscan.c (ffffffff812254b6)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff8128cb28)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff8129c689)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8129da0d)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812a595a)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/kernfs/dir.c (ffffffff8136d21c)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
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
In kernel/sched/rt.c (ffffffff810e60cc)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/jump_label.c (ffffffff812152ca)
Location: include/linux/atomic-fallback.h:89
Inline: True
```
```
In mm/vmscan.c (ffffffff812301aa)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff81298d78)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812a8b5f)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a9cad)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812b2707)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/kernfs/dir.c (ffffffff8137a21c)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
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
In kernel/sched/rt.c (ffffffff810efdc4)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/jump_label.c (ffffffff812242ba)
Location: include/linux/atomic-fallback.h:89
Inline: True
```
```
In mm/vmscan.c (ffffffff8123f5f3)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff812a8b58)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812b8e7f)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b9f2d)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812c2ddc)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/kernfs/dir.c (ffffffff8138d2ad)
Location: include/linux/atomic-fallback.h:89
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
</details>
</li>
</ul>

## Differences
