# Function: <code>uncore_event_to_box</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct intel_uncore_box *uncore_event_to_box(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81016660)
Location: arch/x86/events/intel/uncore.c:115
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_del
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_stop
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_del
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_start
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_add
```
**Symbols:**

```
ffffffff81016660-ffffffff81016697: uncore_event_to_box (STB_GLOBAL)
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
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.h:334
Inline: True
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: arch/x86/events/intel/uncore.h:334
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
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.h:339
Inline: True
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: arch/x86/events/intel/uncore.h:339
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
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.h:339
Inline: True
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: arch/x86/events/intel/uncore.h:339
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
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.h:340
Inline: True
```
```
In arch/x86/events/intel/uncore_snb.c (0)
Location: arch/x86/events/intel/uncore.h:340
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
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.h:461
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
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.h:478
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
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.h:500
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
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.h:488
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
In arch/x86/events/intel/uncore.c (ffffffff81019965)
Location: arch/x86/events/intel/uncore.h:491
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_del
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
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
In arch/x86/events/intel/uncore.c (ffffffff81019fd5)
Location: arch/x86/events/intel/uncore.h:528
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_del
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
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
In arch/x86/events/intel/uncore.c (ffffffff8101b355)
Location: arch/x86/events/intel/uncore.h:541
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_del
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
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
In arch/x86/events/intel/uncore.c (ffffffff8101dcc5)
Location: arch/x86/events/intel/uncore.h:542
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_del
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
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
In arch/x86/events/intel/uncore.c (ffffffff81020765)
Location: arch/x86/events/intel/uncore.h:542
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_del
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
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
In arch/x86/events/intel/uncore.c (ffffffff810250b5)
Location: arch/x86/events/intel/uncore.h:558
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_del
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
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
In arch/x86/events/intel/uncore.c (ffffffff81024fa5)
Location: arch/x86/events/intel/uncore.h:561
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_del
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
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
In arch/x86/events/intel/uncore.c (ffffffff8102b105)
Location: arch/x86/events/intel/uncore.h:561
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_del
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
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
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.h:488
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
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.h:488
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
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.h:488
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
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.h:488
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
