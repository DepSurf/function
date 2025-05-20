# Function: <code>raw_atomic_set_release</code>

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
In arch/x86/kernel/alternative.c (ffffffff8105aa2d)
Location: include/linux/atomic/atomic-arch-fallback.h:507
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In kernel/sched/build_policy.c (ffffffff8116a441)
Location: include/linux/atomic/atomic-arch-fallback.h:507
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8118e635)
Location: include/linux/atomic/atomic-arch-fallback.h:507
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_up_write
```
```
In kernel/printk/printk.c (ffffffff8119ff93)
Location: include/linux/atomic/atomic-arch-fallback.h:507
Inline: True
```
```
In kernel/kexec_core.c (ffffffff812153c0)
Location: include/linux/atomic/atomic-arch-fallback.h:507
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:crash_get_memory_size
  - kernel/kexec_core.c:__crash_kexec
```
```
In kernel/kexec.c (ffffffff81215777)
Location: include/linux/atomic/atomic-arch-fallback.h:507
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
```
```
In kernel/kexec_file.c (ffffffff812171d5)
Location: include/linux/atomic/atomic-arch-fallback.h:507
Inline: True
Inline callers:
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
```
In kernel/trace/rethook.c (ffffffff812debba)
Location: include/linux/atomic/atomic-arch-fallback.h:507
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_try_get
  - kernel/trace/rethook.c:rethook_add_node
  - kernel/trace/rethook.c:rethook_flush_task
```
```
In kernel/jump_label.c (ffffffff813865c7)
Location: include/linux/atomic/atomic-arch-fallback.h:507
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff813b6ce0)
Location: include/linux/atomic/atomic-arch-fallback.h:507
Inline: True
Inline callers:
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/hugetlb.c (ffffffff8143e04b)
Location: include/linux/atomic/atomic-arch-fallback.h:507
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
Location: include/linux/atomic/atomic-arch-fallback.h:507
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff81471cad)
Location: include/linux/atomic/atomic-arch-fallback.h:507
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
Location: include/linux/atomic/atomic-arch-fallback.h:518
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In kernel/sched/build_policy.c (ffffffff81177b01)
Location: include/linux/atomic/atomic-arch-fallback.h:518
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8119cfe5)
Location: include/linux/atomic/atomic-arch-fallback.h:518
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_up_write
```
```
In kernel/power/swap.c (ffffffff811a9719)
Location: include/linux/atomic/atomic-arch-fallback.h:518
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
Location: include/linux/atomic/atomic-arch-fallback.h:518
Inline: True
```
```
In kernel/smp.c (ffffffff81225c08)
Location: include/linux/atomic/atomic-arch-fallback.h:518
Inline: True
Inline callers:
  - kernel/smp.c:__flush_smp_call_function_queue
```
```
In kernel/crash_core.c (ffffffff8122a2a2)
Location: include/linux/atomic/atomic-arch-fallback.h:518
Inline: True
Inline callers:
  - kernel/crash_core.c:crash_handle_hotplug_event
  - kernel/crash_core.c:crash_check_update_elfcorehdr
```
```
In kernel/kexec_core.c (ffffffff8122d365)
Location: include/linux/atomic/atomic-arch-fallback.h:518
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:crash_get_memory_size
  - kernel/kexec_core.c:__crash_kexec
```
```
In kernel/kexec.c (ffffffff8122d724)
Location: include/linux/atomic/atomic-arch-fallback.h:518
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
```
```
In kernel/kexec_file.c (ffffffff8122f0dc)
Location: include/linux/atomic/atomic-arch-fallback.h:518
Inline: True
Inline callers:
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
```
In kernel/bpf/ringbuf.c (ffffffff81357cdf)
Location: include/linux/atomic/atomic-arch-fallback.h:518
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
```
```
In kernel/jump_label.c (ffffffff813afa87)
Location: include/linux/atomic/atomic-arch-fallback.h:518
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff813dfba0)
Location: include/linux/atomic/atomic-arch-fallback.h:518
Inline: True
Inline callers:
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/hugetlb.c (ffffffff81477cdc)
Location: include/linux/atomic/atomic-arch-fallback.h:518
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
Location: include/linux/atomic/atomic-arch-fallback.h:518
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff814a243c)
Location: include/linux/atomic/atomic-arch-fallback.h:518
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
