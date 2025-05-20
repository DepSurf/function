# Function: <code>is_ht_workaround_enabled</code>

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
In arch/x86/events/core.c (0)
Location: arch/x86/events/perf_event.h:932
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/perf_event.h:932
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
In arch/x86/events/core.c (0)
Location: arch/x86/events/perf_event.h:953
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/perf_event.h:953
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
In arch/x86/events/core.c (0)
Location: arch/x86/events/perf_event.h:960
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/perf_event.h:960
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
In arch/x86/events/core.c (0)
Location: arch/x86/events/perf_event.h:969
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/perf_event.h:969
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
In arch/x86/events/core.c (0)
Location: arch/x86/events/perf_event.h:979
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/perf_event.h:979
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
In arch/x86/events/core.c (ffffffff810072c1)
Location: arch/x86/events/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100c6fc)
Location: arch/x86/events/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_stop_scheduling
  - arch/x86/events/intel/core.c:intel_commit_scheduling
  - arch/x86/events/intel/core.c:intel_start_scheduling
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
In arch/x86/events/core.c (ffffffff81007181)
Location: arch/x86/events/perf_event.h:1015
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100c775)
Location: arch/x86/events/perf_event.h:1015
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_stop_scheduling
  - arch/x86/events/intel/core.c:intel_commit_scheduling
  - arch/x86/events/intel/core.c:intel_start_scheduling
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
In arch/x86/events/core.c (ffffffff8100745a)
Location: arch/x86/events/perf_event.h:1054
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100cf95)
Location: arch/x86/events/perf_event.h:1054
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_stop_scheduling
  - arch/x86/events/intel/core.c:intel_commit_scheduling
  - arch/x86/events/intel/core.c:intel_start_scheduling
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
In arch/x86/events/core.c (ffffffff810075e3)
Location: arch/x86/events/perf_event.h:1091
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100d405)
Location: arch/x86/events/perf_event.h:1091
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_stop_scheduling
  - arch/x86/events/intel/core.c:intel_commit_scheduling
  - arch/x86/events/intel/core.c:intel_start_scheduling
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
In arch/x86/events/core.c (ffffffff81008648)
Location: arch/x86/events/perf_event.h:1103
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100e683)
Location: arch/x86/events/perf_event.h:1103
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_stop_scheduling
  - arch/x86/events/intel/core.c:intel_commit_scheduling
  - arch/x86/events/intel/core.c:intel_start_scheduling
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
In arch/x86/events/core.c (ffffffff810076eb)
Location: arch/x86/events/perf_event.h:1251
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100da90)
Location: arch/x86/events/perf_event.h:1251
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_stop_scheduling
  - arch/x86/events/intel/core.c:intel_commit_scheduling
  - arch/x86/events/intel/core.c:intel_start_scheduling
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
In arch/x86/events/core.c (ffffffff81007e99)
Location: arch/x86/events/perf_event.h:1396
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100fd44)
Location: arch/x86/events/perf_event.h:1396
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_stop_scheduling
  - arch/x86/events/intel/core.c:intel_commit_scheduling
  - arch/x86/events/intel/core.c:intel_start_scheduling
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
In arch/x86/events/core.c (ffffffff81008949)
Location: arch/x86/events/perf_event.h:1396
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/core.c (ffffffff81010775)
Location: arch/x86/events/perf_event.h:1396
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_stop_scheduling
  - arch/x86/events/intel/core.c:intel_commit_scheduling
  - arch/x86/events/intel/core.c:intel_start_scheduling
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
In arch/x86/events/core.c (ffffffff81007f92)
Location: arch/x86/events/perf_event.h:1532
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/core.c (ffffffff81011e1c)
Location: arch/x86/events/perf_event.h:1532
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_stop_scheduling
  - arch/x86/events/intel/core.c:intel_commit_scheduling
  - arch/x86/events/intel/core.c:intel_start_scheduling
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
In arch/x86/events/core.c (ffffffff810098a9)
Location: arch/x86/events/perf_event.h:1616
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/core.c (ffffffff810135b7)
Location: arch/x86/events/perf_event.h:1616
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_excl_constraints
  - arch/x86/events/intel/core.c:intel_stop_scheduling
  - arch/x86/events/intel/core.c:intel_commit_scheduling
  - arch/x86/events/intel/core.c:intel_start_scheduling
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
In arch/x86/events/core.c (ffffffff810090c2)
Location: arch/x86/events/perf_event.h:1625
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/core.c (ffffffff81012b67)
Location: arch/x86/events/perf_event.h:1625
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_excl_constraints
  - arch/x86/events/intel/core.c:intel_stop_scheduling
  - arch/x86/events/intel/core.c:intel_commit_scheduling
  - arch/x86/events/intel/core.c:intel_start_scheduling
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
In arch/x86/events/core.c (ffffffff8100e7e2)
Location: arch/x86/events/perf_event.h:1646
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/core.c (ffffffff810187e7)
Location: arch/x86/events/perf_event.h:1646
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_excl_constraints
  - arch/x86/events/intel/core.c:intel_stop_scheduling
  - arch/x86/events/intel/core.c:intel_commit_scheduling
  - arch/x86/events/intel/core.c:intel_start_scheduling
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810075e3)
Location: arch/x86/events/perf_event.h:1091
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100d405)
Location: arch/x86/events/perf_event.h:1091
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_stop_scheduling
  - arch/x86/events/intel/core.c:intel_commit_scheduling
  - arch/x86/events/intel/core.c:intel_start_scheduling
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
In arch/x86/events/core.c (ffffffff81005d83)
Location: arch/x86/events/perf_event.h:1091
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100bc05)
Location: arch/x86/events/perf_event.h:1091
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_stop_scheduling
  - arch/x86/events/intel/core.c:intel_commit_scheduling
  - arch/x86/events/intel/core.c:intel_start_scheduling
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
In arch/x86/events/core.c (ffffffff810075a3)
Location: arch/x86/events/perf_event.h:1091
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100d3c5)
Location: arch/x86/events/perf_event.h:1091
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_stop_scheduling
  - arch/x86/events/intel/core.c:intel_commit_scheduling
  - arch/x86/events/intel/core.c:intel_start_scheduling
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
In arch/x86/events/core.c (ffffffff81007703)
Location: arch/x86/events/perf_event.h:1091
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100d5f5)
Location: arch/x86/events/perf_event.h:1091
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_stop_scheduling
  - arch/x86/events/intel/core.c:intel_commit_scheduling
  - arch/x86/events/intel/core.c:intel_start_scheduling
```
</details>
</li>
</ul>

## Differences
