# Function: <code>arch_atomic_set_release</code>

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
In kernel/sched/rt.c (ffffffff810f8099)
Location: include/linux/atomic-arch-fallback.h:91
Inline: True
Inline callers:
  - kernel/sched/rt.c:tell_cpu_to_push
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110f175)
Location: include/linux/atomic-arch-fallback.h:91
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_up_write
```
```
In kernel/jump_label.c (ffffffff8124ad20)
Location: include/linux/atomic-arch-fallback.h:91
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff81266276)
Location: include/linux/atomic-arch-fallback.h:91
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff812d7108)
Location: include/linux/atomic-arch-fallback.h:91
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812e7d0e)
Location: include/linux/atomic-arch-fallback.h:91
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812e8905)
Location: include/linux/atomic-arch-fallback.h:91
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page_tail
```
```
In mm/khugepaged.c (ffffffff812f1853)
Location: include/linux/atomic-arch-fallback.h:91
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
Location: include/linux/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In kernel/sched/rt.c (ffffffff810f62a9)
Location: include/linux/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - kernel/sched/rt.c:tell_cpu_to_push
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110c335)
Location: include/linux/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_up_write
```
```
In kernel/kprobes.c (ffffffff81193531)
Location: include/linux/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:kprobe_flush_task
```
```
In kernel/jump_label.c (ffffffff81255110)
Location: include/linux/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff81270c72)
Location: include/linux/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff812f30fa)
Location: include/linux/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812f3d20)
Location: include/linux/atomic-arch-fallback.h:161
Inline: True
```
```
In mm/khugepaged.c (ffffffff812fdda8)
Location: include/linux/atomic-arch-fallback.h:161
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
Location: include/linux/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In kernel/sched/rt.c (ffffffff810f9529)
Location: include/linux/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110e175)
Location: include/linux/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_up_write
```
```
In kernel/kprobes.c (ffffffff811944e1)
Location: include/linux/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:kprobe_flush_task
```
```
In kernel/events/core.c (ffffffff8124f4c9)
Location: include/linux/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/jump_label.c (ffffffff81259610)
Location: include/linux/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff8127575b)
Location: include/linux/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff812f9493)
Location: include/linux/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812fa180)
Location: include/linux/atomic-arch-fallback.h:161
Inline: True
```
```
In mm/khugepaged.c (ffffffff81304f17)
Location: include/linux/atomic-arch-fallback.h:161
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
Location: include/linux/atomic/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In kernel/sched/rt.c (ffffffff81112ce9)
Location: include/linux/atomic/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8112d8c5)
Location: include/linux/atomic/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_up_write
```
```
In kernel/printk/printk.c (ffffffff811393a3)
Location: include/linux/atomic/atomic-arch-fallback.h:161
Inline: True
```
```
In kernel/kprobes.c (ffffffff811bd381)
Location: include/linux/atomic/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:kprobe_flush_task
```
```
In kernel/events/core.c (ffffffff8128a149)
Location: include/linux/atomic/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/jump_label.c (ffffffff812952cf)
Location: include/linux/atomic/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff812b4bea)
Location: include/linux/atomic/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff81342a42)
Location: include/linux/atomic/atomic-arch-fallback.h:161
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81343ea0)
Location: include/linux/atomic/atomic-arch-fallback.h:161
Inline: True
```
```
In mm/khugepaged.c (ffffffff8134ecaa)
Location: include/linux/atomic/atomic-arch-fallback.h:161
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
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8114e8e5)
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_up_write
```
```
In kernel/printk/printk.c (ffffffff8115bc13)
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
```
```
In kernel/trace/rethook.c (ffffffff81268cfa)
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_try_get
  - kernel/trace/rethook.c:rethook_add_node
  - kernel/trace/rethook.c:rethook_flush_task
```
```
In kernel/events/core.c (ffffffff812deaa8)
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/jump_label.c (ffffffff812eb097)
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff81313400)
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
Inline callers:
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff813b4f49)
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff813b9bbf)
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
```
```
In mm/khugepaged.c (ffffffff813c58dc)
Location: include/linux/atomic/atomic-arch-fallback.h:240
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
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In kernel/sched/build_policy.c (ffffffff8115a231)
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8117d995)
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_up_write
```
```
In kernel/printk/printk.c (ffffffff8118e633)
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
```
```
In kernel/kexec_core.c (ffffffff811fff60)
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:crash_get_memory_size
  - kernel/kexec_core.c:__crash_kexec
```
```
In kernel/kexec.c (ffffffff81200317)
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
```
```
In kernel/kexec_file.c (ffffffff81201ddb)
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
Inline callers:
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
```
In kernel/trace/rethook.c (ffffffff812bafba)
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_try_get
  - kernel/trace/rethook.c:rethook_add_node
  - kernel/trace/rethook.c:rethook_flush_task
```
```
In kernel/jump_label.c (ffffffff813550d7)
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff81386850)
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
Inline callers:
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/hugetlb.c (ffffffff81412b65)
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:__remove_hugetlb_folio
```
```
In mm/migrate.c (ffffffff814340d1)
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff8143c667)
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
```
```
In mm/khugepaged.c (ffffffff8144a23f)
Location: include/linux/atomic/atomic-arch-fallback.h:240
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
