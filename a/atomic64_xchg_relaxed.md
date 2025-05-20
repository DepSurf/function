# Function: <code>atomic64_xchg_relaxed</code>

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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/context.c (ffff8000100aff18)
Location: include/asm-generic/atomic-instrumented.h:1451
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
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
In arch/arm/mm/context.c (c0322304)
Location: arch/arm/include/asm/atomic.h:429
Inline: True
Inline callers:
  - arch/arm/mm/context.c:check_and_switch_context
  - arch/arm/mm/context.c:check_and_switch_context
```
```
In arch/arm/mm/cache-l2x0-pmu.c (c0324acc)
Location: arch/arm/include/asm/atomic.h:429
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_read
```
```
In kernel/events/core.c (c04c03dc)
Location: arch/arm/include/asm/atomic.h:429
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_update
  - kernel/events/core.c:cpu_clock_event_update
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In drivers/perf/arm-ccn.c (c0c7cde8)
Location: arch/arm/include/asm/atomic.h:429
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
