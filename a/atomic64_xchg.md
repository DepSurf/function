# Function: <code>atomic64_xchg</code>

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
In kernel/sched/loadavg.c (ffffffff810b10d8)
Location: arch/x86/include/asm/atomic64_64.h:169
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/sched/fair.c (ffffffff810b519a)
Location: arch/x86/include/asm/atomic64_64.h:169
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
```
```
In mm/vmscan.c (ffffffff811a06a9)
Location: arch/x86/include/asm/atomic64_64.h:169
Inline: True
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
In kernel/sched/loadavg.c (ffffffff810b3b85)
Location: arch/x86/include/asm/atomic64_64.h:179
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/sched/fair.c (ffffffff810b9c21)
Location: arch/x86/include/asm/atomic64_64.h:179
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_task_cfs_rq
  - kernel/sched/fair.c:attach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
```
```
In mm/vmscan.c (ffffffff811b6a5c)
Location: arch/x86/include/asm/atomic64_64.h:179
Inline: True
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
In kernel/sched/loadavg.c (ffffffff810ba1c5)
Location: arch/x86/include/asm/atomic64_64.h:179
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/sched/fair.c (ffffffff810c3cf7)
Location: arch/x86/include/asm/atomic64_64.h:179
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
```
```
In mm/vmscan.c (ffffffff811c7010)
Location: arch/x86/include/asm/atomic64_64.h:179
Inline: True
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
In kernel/sched/loadavg.c (ffffffff810b4893)
Location: arch/x86/include/asm/atomic64_64.h:185
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/sched/fair.c (ffffffff810c23b0)
Location: arch/x86/include/asm/atomic64_64.h:185
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In mm/vmscan.c (ffffffff811cf795)
Location: arch/x86/include/asm/atomic64_64.h:185
Inline: True
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
In kernel/sched/loadavg.c (ffffffff810bbb63)
Location: arch/x86/include/asm/atomic64_64.h:186
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff811e4bc2)
Location: arch/x86/include/asm/atomic64_64.h:186
Inline: True
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
In kernel/sched/loadavg.c (ffffffff810c3233)
Location: include/asm-generic/atomic-instrumented.h:49
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff81206340)
Location: include/asm-generic/atomic-instrumented.h:49
Inline: True
```
```
In mm/page_counter.c (ffffffff8127e2a5)
Location: include/asm-generic/atomic-instrumented.h:49
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (ffffffff810cc4e3)
Location: include/asm-generic/atomic-instrumented.h:49
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff81218abf)
Location: include/asm-generic/atomic-instrumented.h:49
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff81292995)
Location: include/asm-generic/atomic-instrumented.h:49
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (ffffffff810d491f)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff812284ff)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812ad365)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (ffffffff810deedf)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8123639f)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812beeb5)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (ffffffff810e728a)
Location: include/asm-generic/atomic-instrumented.h:1422
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff81264f10)
Location: include/asm-generic/atomic-instrumented.h:1422
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812f4190)
Location: include/asm-generic/atomic-instrumented.h:1422
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (ffffffff810e4eca)
Location: include/asm-generic/atomic-instrumented.h:1422
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8126f88a)
Location: include/asm-generic/atomic-instrumented.h:1422
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812ffa80)
Location: include/asm-generic/atomic-instrumented.h:1422
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (ffffffff810e6da7)
Location: include/asm-generic/atomic-instrumented.h:1422
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8127356a)
Location: include/asm-generic/atomic-instrumented.h:1422
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff81306723)
Location: include/asm-generic/atomic-instrumented.h:1422
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/sched/loadavg.c (ffff80001013eba8)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/events/core.c (ffff800010294178)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_stop
  - kernel/events/core.c:cpu_clock_event_update
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In kernel/events/ring_buffer.c (ffff8000102a27bc)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/vmscan.c (ffff8000102c7c68)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffff8000103609a8)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In drivers/perf/arm-ccn.c (ffff800010b930a8)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_update
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
In arch/arm/mm/context.c (c0322300)
Location: include/linux/atomic-fallback.h:1961
Inline: True
Inline callers:
  - arch/arm/mm/context.c:check_and_switch_context
  - arch/arm/mm/context.c:check_and_switch_context
```
```
In arch/arm/mm/cache-l2x0-pmu.c (c0324ac8)
Location: include/linux/atomic-fallback.h:1961
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_read
```
```
In kernel/events/core.c (c04c03d8)
Location: include/linux/atomic-fallback.h:1961
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_update
  - kernel/events/core.c:cpu_clock_event_update
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In drivers/perf/arm-ccn.c (c0c7cde4)
Location: include/linux/atomic-fallback.h:1961
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_update
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffe0000ed428)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/events/core.c (ffffffe0001c37a2)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In kernel/events/ring_buffer.c (ffffffe0001d141c)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/vmscan.c (ffffffe0001e69a8)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/memory.c (ffffffe0002076a6)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mprotect.c (ffffffe000211204)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffe000211c38)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffe000212d54)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (0)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
```
```
In mm/vmalloc.c (ffffffe00021561e)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
```
```
In mm/madvise.c (ffffffe000220648)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffe000230dde)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/page_counter.c (ffffffe0002402cc)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (ffffffff810d90cf)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8122e9ef)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812b7495)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (ffffffff810c7acf)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81116691)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
```
In mm/vmscan.c (ffffffff81221aaf)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812a8665)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (ffffffff810d540f)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8122c78f)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812b52a5)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ac1dc)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:dump_counters
  - net/netfilter/nf_conntrack_netlink.c:dump_counters
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
In kernel/sched/loadavg.c (ffffffff810e0cbf)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8123bb7a)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812c57e5)
Location: include/asm-generic/atomic-instrumented.h:1421
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
</details>
</li>
</ul>

## Differences
