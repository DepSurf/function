# Function: <code>is_topdown_count</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007887)
Location: arch/x86/events/perf_event.h:84
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100c7e9)
Location: arch/x86/events/perf_event.h:84
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
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
In arch/x86/events/core.c (ffffffff81008067)
Location: arch/x86/events/perf_event.h:86
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100d209)
Location: arch/x86/events/perf_event.h:86
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
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
In arch/x86/events/core.c (ffffffff81008c2c)
Location: arch/x86/events/perf_event.h:86
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100d6a9)
Location: arch/x86/events/perf_event.h:86
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
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
In arch/x86/events/core.c (ffffffff8100829c)
Location: arch/x86/events/perf_event.h:89
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100e888)
Location: arch/x86/events/perf_event.h:89
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81011845)
Location: arch/x86/events/perf_event.h:87
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_update
  - arch/x86/events/intel/core.c:intel_pmu_set_period
  - arch/x86/events/intel/core.c:intel_pmu_read_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81010ed5)
Location: arch/x86/events/perf_event.h:89
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_update
  - arch/x86/events/intel/core.c:intel_pmu_set_period
  - arch/x86/events/intel/core.c:intel_pmu_read_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff810165d5)
Location: arch/x86/events/perf_event.h:89
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_update
  - arch/x86/events/intel/core.c:intel_pmu_set_period
  - arch/x86/events/intel/core.c:intel_pmu_read_event
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
