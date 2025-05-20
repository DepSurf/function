# Function: <code>atomic_long_xchg</code>

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
In kernel/sched/loadavg.c (ffffffff810d491f)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff812284ff)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812ad365)
Location: include/asm-generic/atomic-long.h:386
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
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8123639f)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812beeb5)
Location: include/asm-generic/atomic-long.h:386
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
Location: include/asm-generic/atomic-long.h:387
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff81264f10)
Location: include/asm-generic/atomic-long.h:387
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812f4190)
Location: include/asm-generic/atomic-long.h:387
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
Location: include/asm-generic/atomic-long.h:387
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8126f88a)
Location: include/asm-generic/atomic-long.h:387
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812ffa80)
Location: include/asm-generic/atomic-long.h:387
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
Location: include/asm-generic/atomic-long.h:387
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8127356a)
Location: include/asm-generic/atomic-long.h:387
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff81306723)
Location: include/asm-generic/atomic-long.h:387
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (ffffffff810fe377)
Location: include/linux/atomic/atomic-instrumented.h:1601
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff812b083e)
Location: include/linux/atomic/atomic-instrumented.h:1601
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff81350553)
Location: include/linux/atomic/atomic-instrumented.h:1601
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/build_utility.c (ffffffff8114890f)
Location: include/linux/atomic/atomic-instrumented.h:1708
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8130c0ba)
Location: include/linux/atomic/atomic-instrumented.h:1708
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff813c8803)
Location: include/linux/atomic/atomic-instrumented.h:1708
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/build_utility.c (ffffffff8117712f)
Location: include/linux/atomic/atomic-instrumented.h:1708
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8137838a)
Location: include/linux/atomic/atomic-instrumented.h:1708
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff8144cecd)
Location: include/linux/atomic/atomic-instrumented.h:1708
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/build_utility.c (ffffffff81187d7f)
Location: include/linux/atomic/atomic-instrumented.h:4244
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff813ac68a)
Location: include/linux/atomic/atomic-instrumented.h:4244
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff8148278d)
Location: include/linux/atomic/atomic-instrumented.h:4244
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/build_utility.c (ffffffff8119652f)
Location: include/linux/atomic/atomic-instrumented.h:4244
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load
```
```
In mm/shrinker.c (ffffffff813e3f38)
Location: include/linux/atomic/atomic-instrumented.h:4244
Inline: True
Inline callers:
  - mm/shrinker.c:do_shrink_slab
  - mm/shrinker.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff814b1b0d)
Location: include/linux/atomic/atomic-instrumented.h:4244
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (ffff80001013eba8)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/events/core.c (ffff800010294178)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_stop
  - kernel/events/core.c:cpu_clock_event_update
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In kernel/events/ring_buffer.c (ffff8000102a27bc)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/vmscan.c (ffff8000102c7c68)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffff8000103609a8)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In drivers/perf/arm-ccn.c (ffff800010b930a8)
Location: include/asm-generic/atomic-long.h:386
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
In kernel/sched/loadavg.c (c038eac8)
Location: include/asm-generic/atomic-long.h:880
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/events/ring_buffer.c (c04d2378)
Location: include/asm-generic/atomic-long.h:880
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/vmscan.c (c04f16b8)
Location: include/asm-generic/atomic-long.h:880
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (c055312c)
Location: include/asm-generic/atomic-long.h:880
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (c00000000018db60)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (c0000000003828b0)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (c00000000044bae0)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
In kernel/sched/loadavg.c (ffffffe0000ed428)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/events/core.c (ffffffe0001c37a2)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In kernel/events/ring_buffer.c (ffffffe0001d141c)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/vmscan.c (ffffffe0001e69a8)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/memory.c (ffffffe0002076a6)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mprotect.c (ffffffe000211204)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffe000211c38)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffe000212d54)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (0)
Location: include/asm-generic/atomic-long.h:386
Inline: True
```
```
In mm/vmalloc.c (ffffffe00021561e)
Location: include/asm-generic/atomic-long.h:386
Inline: True
```
```
In mm/madvise.c (ffffffe000220648)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffe000230dde)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/page_counter.c (ffffffe0002402cc)
Location: include/asm-generic/atomic-long.h:386
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
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8122e9ef)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812b7495)
Location: include/asm-generic/atomic-long.h:386
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
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81116691)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
```
In mm/vmscan.c (ffffffff81221aaf)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812a8665)
Location: include/asm-generic/atomic-long.h:386
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
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8122c78f)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812b52a5)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
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
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In mm/vmscan.c (ffffffff8123bb7a)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/page_counter.c (ffffffff812c57e5)
Location: include/asm-generic/atomic-long.h:386
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
</details>
</li>
</ul>

## Differences
