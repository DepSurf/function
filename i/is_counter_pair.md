# Function: <code>is_counter_pair</code>

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
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007cd1)
Location: arch/x86/events/perf_event.h:837
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:x86_schedule_events
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81008a85)
Location: arch/x86/events/perf_event.h:837
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_put_event_constraints_f17h
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100d861)
Location: arch/x86/events/perf_event.h:837
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/core.c (ffffffff81008d41)
Location: arch/x86/events/perf_event.h:846
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:x86_schedule_events
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81009bb5)
Location: arch/x86/events/perf_event.h:846
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_put_event_constraints_f17h
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100e42e)
Location: arch/x86/events/perf_event.h:846
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8101f9d6)
Location: arch/x86/events/perf_event.h:846
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
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
In arch/x86/events/core.c (ffffffff81007df1)
Location: arch/x86/events/perf_event.h:977
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_schedule_events
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81008a35)
Location: arch/x86/events/perf_event.h:977
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_put_event_constraints_f17h
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100d5ee)
Location: arch/x86/events/perf_event.h:977
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81020476)
Location: arch/x86/events/perf_event.h:977
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
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
In arch/x86/events/core.c (ffffffff810085c1)
Location: arch/x86/events/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:collect_event
  - arch/x86/events/core.c:x86_schedule_events
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff810093c5)
Location: arch/x86/events/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_put_event_constraints_f17h
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100e37e)
Location: arch/x86/events/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81022806)
Location: arch/x86/events/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
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
In arch/x86/events/core.c (ffffffff810093b1)
Location: arch/x86/events/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:collect_event
  - arch/x86/events/core.c:x86_schedule_events
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff8100a325)
Location: arch/x86/events/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_put_event_constraints_f17h
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100eb2f)
Location: arch/x86/events/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81026689)
Location: arch/x86/events/perf_event.h:1100
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
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
In arch/x86/events/core.c (ffffffff81008a2b)
Location: arch/x86/events/perf_event.h:1126
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:collect_event
  - arch/x86/events/core.c:x86_schedule_events
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff8100b345)
Location: arch/x86/events/perf_event.h:1126
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100feef)
Location: arch/x86/events/perf_event.h:1126
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8102a789)
Location: arch/x86/events/perf_event.h:1126
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
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
In arch/x86/events/core.c (ffffffff81009bdb)
Location: arch/x86/events/perf_event.h:1134
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:collect_event
  - arch/x86/events/core.c:x86_schedule_events
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff8100cd15)
Location: arch/x86/events/perf_event.h:1134
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
```
```
In arch/x86/events/intel/core.c (ffffffff81013b8f)
Location: arch/x86/events/perf_event.h:1134
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81031359)
Location: arch/x86/events/perf_event.h:1134
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
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
In arch/x86/events/core.c (ffffffff810093fb)
Location: arch/x86/events/perf_event.h:1139
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:collect_event
  - arch/x86/events/core.c:x86_schedule_events
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff8100c4d5)
Location: arch/x86/events/perf_event.h:1139
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
```
```
In arch/x86/events/intel/core.c (ffffffff810133e7)
Location: arch/x86/events/perf_event.h:1139
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81031369)
Location: arch/x86/events/perf_event.h:1139
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
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
In arch/x86/events/core.c (ffffffff8100eb1b)
Location: arch/x86/events/perf_event.h:1154
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:collect_event
  - arch/x86/events/core.c:x86_schedule_events
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81011cb5)
Location: arch/x86/events/perf_event.h:1154
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
```
```
In arch/x86/events/intel/core.c (ffffffff81018a77)
Location: arch/x86/events/perf_event.h:1154
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81037659)
Location: arch/x86/events/perf_event.h:1154
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
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
In arch/x86/events/core.c (ffffffff81007cd1)
Location: arch/x86/events/perf_event.h:837
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:x86_schedule_events
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81008a85)
Location: arch/x86/events/perf_event.h:837
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_put_event_constraints_f17h
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100d861)
Location: arch/x86/events/perf_event.h:837
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/core.c (ffffffff810064a5)
Location: arch/x86/events/perf_event.h:837
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:x86_schedule_events
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81007295)
Location: arch/x86/events/perf_event.h:837
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_put_event_constraints_f17h
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100bfe1)
Location: arch/x86/events/perf_event.h:837
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/core.c (ffffffff81007c91)
Location: arch/x86/events/perf_event.h:837
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:x86_schedule_events
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81008a45)
Location: arch/x86/events/perf_event.h:837
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_put_event_constraints_f17h
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100d821)
Location: arch/x86/events/perf_event.h:837
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/core.c (ffffffff81007df1)
Location: arch/x86/events/perf_event.h:837
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:x86_schedule_events
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81008ba5)
Location: arch/x86/events/perf_event.h:837
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_put_event_constraints_f17h
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100d9f1)
Location: arch/x86/events/perf_event.h:837
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
</details>
</li>
</ul>

## Differences
