# Function: <code>__perf_event_count</code>

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
In arch/x86/events/intel/cqm.c (ffffffff8100d7b9)
Location: include/linux/perf_event.h:952
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_count
```
```
In kernel/events/core.c (ffffffff8117a3a3)
Location: include/linux/perf_event.h:952
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_exit_task
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
In arch/x86/events/intel/cqm.c (ffffffff8100de13)
Location: include/linux/perf_event.h:1078
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_count
  - arch/x86/events/intel/cqm.c:intel_cqm_event_count
```
```
In kernel/events/core.c (ffffffff81196867)
Location: include/linux/perf_event.h:1078
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_read_value
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
In arch/x86/events/intel/cqm.c (ffffffff8100ded3)
Location: include/linux/perf_event.h:1101
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_count
  - arch/x86/events/intel/cqm.c:intel_cqm_event_count
```
```
In kernel/events/core.c (ffffffff811a62e4)
Location: include/linux/perf_event.h:1101
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_read_value
```
</details>
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
