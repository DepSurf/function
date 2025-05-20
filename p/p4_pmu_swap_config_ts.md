# Function: <code>p4_pmu_swap_config_ts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff81012d26)
Location: arch/x86/events/intel/p4.c:1066
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff81012827)
Location: arch/x86/events/intel/p4.c:1066
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff8101292d)
Location: arch/x86/events/intel/p4.c:1066
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff81010de4)
Location: arch/x86/events/intel/p4.c:1066
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff81011604)
Location: arch/x86/events/intel/p4.c:1066
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff81011e77)
Location: arch/x86/events/intel/p4.c:1066
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff810124f7)
Location: arch/x86/events/intel/p4.c:1066
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
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
In arch/x86/events/intel/p4.c (ffffffff810139e7)
Location: arch/x86/events/intel/p4.c:1066
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
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
In arch/x86/events/intel/p4.c (ffffffff81014197)
Location: arch/x86/events/intel/p4.c:1066
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void p4_pmu_swap_config_ts(struct hw_perf_event *hwc, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff810151e0)
Location: arch/x86/events/intel/p4.c:1067
Inline: False
Direct callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
**Symbols:**

```
ffffffff810151e0-ffffffff81015304: p4_pmu_swap_config_ts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void p4_pmu_swap_config_ts(struct hw_perf_event *hwc, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff81015680)
Location: arch/x86/events/intel/p4.c:1067
Inline: False
Direct callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
**Symbols:**

```
ffffffff81015680-ffffffff810157a4: p4_pmu_swap_config_ts (STB_LOCAL)
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
In arch/x86/events/intel/p4.c (ffffffff81016f8a)
Location: arch/x86/events/intel/p4.c:1077
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
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
In arch/x86/events/intel/p4.c (ffffffff81018bef)
Location: arch/x86/events/intel/p4.c:1077
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
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
In arch/x86/events/intel/p4.c (ffffffff8101adb3)
Location: arch/x86/events/intel/p4.c:1077
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
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
In arch/x86/events/intel/p4.c (ffffffff8101ef33)
Location: arch/x86/events/intel/p4.c:1100
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
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
In arch/x86/events/intel/p4.c (ffffffff8101ec20)
Location: arch/x86/events/intel/p4.c:1100
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
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
In arch/x86/events/intel/p4.c (ffffffff81024ce0)
Location: arch/x86/events/intel/p4.c:1100
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
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
In arch/x86/events/intel/p4.c (ffffffff81014197)
Location: arch/x86/events/intel/p4.c:1066
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
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
In arch/x86/events/intel/p4.c (ffffffff81013447)
Location: arch/x86/events/intel/p4.c:1066
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
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
In arch/x86/events/intel/p4.c (ffffffff81014157)
Location: arch/x86/events/intel/p4.c:1066
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
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
In arch/x86/events/intel/p4.c (ffffffff81014397)
Location: arch/x86/events/intel/p4.c:1066
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
