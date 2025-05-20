# Function: <code>fixed_counter_disabled</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool fixed_counter_disabled(int i, struct pmu *pmu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006e1e)
Location: arch/x86/events/perf_event.h:1195
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
Direct callers:
  - arch/x86/events/core.c:perf_event_print_debug
```
```
In arch/x86/events/intel/core.c (ffffffff8100f3cc)
Location: arch/x86/events/perf_event.h:1195
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
**Symbols:**

```
ffffffff81bc3c2e-ffffffff81bc3c5e: fixed_counter_disabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool fixed_counter_disabled(int i, struct pmu *pmu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007638)
Location: arch/x86/events/perf_event.h:1195
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
Direct callers:
  - arch/x86/events/core.c:perf_event_print_debug
```
```
In arch/x86/events/intel/core.c (ffffffff81010196)
Location: arch/x86/events/perf_event.h:1195
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
**Symbols:**

```
ffffffff81c94c8b-ffffffff81c94cdc: fixed_counter_disabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool fixed_counter_disabled(int i, struct pmu *pmu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006b82)
Location: arch/x86/events/perf_event.h:1221
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
Direct callers:
  - arch/x86/events/core.c:perf_event_print_debug
```
```
In arch/x86/events/intel/core.c (ffffffff810117ac)
Location: arch/x86/events/perf_event.h:1221
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
**Symbols:**

```
ffffffff81e43f55-ffffffff81e43fb2: fixed_counter_disabled (STB_LOCAL)
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
In arch/x86/events/core.c (ffffffff81009e6c)
Location: arch/x86/events/perf_event.h:1291
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/intel/core.c (ffffffff810151c4)
Location: arch/x86/events/perf_event.h:1291
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
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
In arch/x86/events/core.c (ffffffff81009682)
Location: arch/x86/events/perf_event.h:1296
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/intel/core.c (ffffffff81014a27)
Location: arch/x86/events/perf_event.h:1296
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
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
In arch/x86/events/core.c (ffffffff8100eda2)
Location: arch/x86/events/perf_event.h:1311
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/intel/core.c (ffffffff81019a17)
Location: arch/x86/events/perf_event.h:1311
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
