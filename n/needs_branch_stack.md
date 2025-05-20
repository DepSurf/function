# Function: <code>needs_branch_stack</code>

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
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1026
Inline: True
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
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1186
Inline: True
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
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1209
Inline: True
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
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1205
Inline: True
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
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1195
Inline: True
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
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1223
Inline: True
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
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1228
Inline: True
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
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1271
Inline: True
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
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1285
Inline: True
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
In arch/x86/events/intel/core.c (ffffffff8100d7fa)
Location: include/linux/perf_event.h:1354
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_add_event
  - arch/x86/events/intel/core.c:intel_pmu_del_event
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
In arch/x86/events/intel/core.c (ffffffff8100c8da)
Location: include/linux/perf_event.h:1370
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_add_event
  - arch/x86/events/intel/core.c:intel_pmu_del_event
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
In arch/x86/events/intel/core.c (ffffffff8100d2fa)
Location: include/linux/perf_event.h:1371
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_add_event
  - arch/x86/events/intel/core.c:intel_pmu_del_event
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
In arch/x86/events/intel/core.c (ffffffff8100d79a)
Location: include/linux/perf_event.h:1376
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_add_event
  - arch/x86/events/intel/core.c:intel_pmu_del_event
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
In arch/x86/events/amd/core.c (ffffffff81009ec5)
Location: include/linux/perf_event.h:1418
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_del_event
  - arch/x86/events/amd/core.c:amd_pmu_add_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100e999)
Location: include/linux/perf_event.h:1418
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_add_event
  - arch/x86/events/intel/core.c:intel_pmu_del_event
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
In arch/x86/events/amd/core.c (ffffffff8100b9d5)
Location: include/linux/perf_event.h:1517
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_del_event
  - arch/x86/events/amd/core.c:amd_pmu_add_event
```
```
In arch/x86/events/intel/core.c (ffffffff81012019)
Location: include/linux/perf_event.h:1517
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_add_event
  - arch/x86/events/intel/core.c:intel_pmu_del_event
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
In arch/x86/events/amd/core.c (ffffffff8100b2d5)
Location: include/linux/perf_event.h:1630
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_del_event
  - arch/x86/events/amd/core.c:amd_pmu_add_event
```
```
In arch/x86/events/intel/core.c (ffffffff810116a9)
Location: include/linux/perf_event.h:1630
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_add_event
  - arch/x86/events/intel/core.c:intel_pmu_del_event
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
In arch/x86/events/amd/core.c (ffffffff81010a55)
Location: include/linux/perf_event.h:1672
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_del_event
  - arch/x86/events/amd/core.c:amd_pmu_add_event
```
```
In arch/x86/events/intel/core.c (ffffffff8101775d)
Location: include/linux/perf_event.h:1672
Inline: True
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
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1285
Inline: True
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
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1285
Inline: True
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
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1285
Inline: True
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
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1285
Inline: True
```
</details>
</li>
</ul>

## Differences
