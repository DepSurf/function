# Function: <code>intel_pmu_has_bts_period</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c611)
Location: arch/x86/events/perf_event.h:871
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100cd9a)
Location: arch/x86/events/perf_event.h:906
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d20a)
Location: arch/x86/events/perf_event.h:943
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100dca5)
Location: arch/x86/events/perf_event.h:952
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_check_period
  - arch/x86/events/intel/core.c:intel_pmu_check_period
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100ce75)
Location: arch/x86/events/perf_event.h:1083
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_check_period
  - arch/x86/events/intel/core.c:intel_pmu_check_period
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d995)
Location: arch/x86/events/perf_event.h:1222
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_check_period
  - arch/x86/events/intel/core.c:intel_pmu_check_period
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100dfc5)
Location: arch/x86/events/perf_event.h:1222
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_check_period
  - arch/x86/events/intel/core.c:intel_pmu_check_period
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100f535)
Location: arch/x86/events/perf_event.h:1333
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_check_period
  - arch/x86/events/intel/core.c:intel_pmu_check_period
  - arch/x86/events/intel/core.c:intel_pmu_bts_config
  - arch/x86/events/intel/core.c:intel_pmu_bts_config
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
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
In arch/x86/events/intel/core.c (ffffffff81012f15)
Location: arch/x86/events/perf_event.h:1415
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_check_period
  - arch/x86/events/intel/core.c:intel_pmu_check_period
  - arch/x86/events/intel/core.c:intel_pmu_bts_config
  - arch/x86/events/intel/core.c:intel_pmu_bts_config
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
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
In arch/x86/events/intel/core.c (ffffffff810124e5)
Location: arch/x86/events/perf_event.h:1420
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_check_period
  - arch/x86/events/intel/core.c:intel_pmu_check_period
  - arch/x86/events/intel/core.c:intel_pmu_bts_config
  - arch/x86/events/intel/core.c:intel_pmu_bts_config
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
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
In arch/x86/events/intel/core.c (ffffffff81017e05)
Location: arch/x86/events/perf_event.h:1435
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_check_period
  - arch/x86/events/intel/core.c:intel_pmu_check_period
  - arch/x86/events/intel/core.c:intel_pmu_bts_config
  - arch/x86/events/intel/core.c:intel_pmu_bts_config
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d20a)
Location: arch/x86/events/perf_event.h:943
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100ba0a)
Location: arch/x86/events/perf_event.h:943
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d1ca)
Location: arch/x86/events/perf_event.h:943
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d3fa)
Location: arch/x86/events/perf_event.h:943
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
</details>
</li>
</ul>

## Differences
