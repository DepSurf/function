# Function: <code>is_metric_idx</code>

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
In arch/x86/events/core.c (ffffffff81006056)
Location: arch/x86/include/asm/perf_event.h:286
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100d758)
Location: arch/x86/include/asm/perf_event.h:286
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:icl_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_fixed
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
In arch/x86/events/core.c (ffffffff81005dc6)
Location: arch/x86/include/asm/perf_event.h:296
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100f83d)
Location: arch/x86/include/asm/perf_event.h:296
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
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
In arch/x86/events/core.c (ffffffff81006476)
Location: arch/x86/include/asm/perf_event.h:296
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100ed10)
Location: arch/x86/include/asm/perf_event.h:296
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
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
In arch/x86/events/core.c (ffffffff81005875)
Location: arch/x86/include/asm/perf_event.h:315
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff810100f0)
Location: arch/x86/include/asm/perf_event.h:315
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
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
In arch/x86/events/core.c (ffffffff81006da5)
Location: arch/x86/include/asm/perf_event.h:333
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff810139b2)
Location: arch/x86/include/asm/perf_event.h:333
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
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
In arch/x86/events/core.c (ffffffff81006545)
Location: arch/x86/include/asm/perf_event.h:354
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff81012f62)
Location: arch/x86/include/asm/perf_event.h:354
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
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
In arch/x86/events/core.c (ffffffff8100bc45)
Location: arch/x86/include/asm/perf_event.h:367
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff81018602)
Location: arch/x86/include/asm/perf_event.h:367
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
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
