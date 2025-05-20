# Function: <code>paravirt_read_pmc</code>

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
In arch/x86/events/core.c (ffffffff810059a9)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008276)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
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
In arch/x86/events/core.c (ffffffff81005c39)
Location: arch/x86/include/asm/paravirt.h:200
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff810084c6)
Location: arch/x86/include/asm/paravirt.h:200
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
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
In arch/x86/events/core.c (ffffffff81005b79)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff810084e6)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
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
In arch/x86/events/core.c (ffffffff81005911)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008196)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
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
In arch/x86/events/core.c (ffffffff81005c71)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008616)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
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
In arch/x86/events/core.c (ffffffff81006409)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008dc6)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e7b3)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
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
In arch/x86/events/core.c (ffffffff81006359)
Location: arch/x86/include/asm/paravirt.h:235
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008ce6)
Location: arch/x86/include/asm/paravirt.h:235
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/intel/ds.c (ffffffff8100ec83)
Location: arch/x86/include/asm/paravirt.h:235
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105cc11)
Location: arch/x86/include/asm/paravirt.h:235
Inline: True
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
In arch/x86/events/core.c (ffffffff8100656a)
Location: arch/x86/include/asm/paravirt.h:235
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009176)
Location: arch/x86/include/asm/paravirt.h:235
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f57a)
Location: arch/x86/include/asm/paravirt.h:235
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105ff3c)
Location: arch/x86/include/asm/paravirt.h:235
Inline: True
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
In arch/x86/events/core.c (ffffffff810065fa)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009576)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fc42)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810607ec)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
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
In arch/x86/events/core.c (ffffffff8100775a)
Location: arch/x86/include/asm/paravirt.h:229
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100a726)
Location: arch/x86/include/asm/paravirt.h:229
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/intel/ds.c (ffffffff810112a2)
Location: arch/x86/include/asm/paravirt.h:229
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810664fc)
Location: arch/x86/include/asm/paravirt.h:229
Inline: True
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
In arch/x86/events/core.c (ffffffff81006815)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009586)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/intel/core.c (ffffffff8100e198)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:icl_update_topdown_event
  - arch/x86/events/intel/core.c:icl_update_topdown_event
```
```
In arch/x86/events/intel/ds.c (ffffffff810108d2)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106479c)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
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
In arch/x86/events/core.c (ffffffff81006966)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009f56)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/intel/core.c (ffffffff8100e5de)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
```
```
In arch/x86/events/intel/ds.c (ffffffff81011872)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81064d3c)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
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
In arch/x86/events/core.c (ffffffff8100704c)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100efbe)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
```
```
In arch/x86/events/intel/ds.c (ffffffff81012736)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106edec)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
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
In arch/x86/events/core.c (ffffffff8100652e)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff810104b3)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
```
```
In arch/x86/events/intel/ds.c (ffffffff8101432f)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107c64d)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
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
In arch/x86/events/core.c (ffffffff81005eb2)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81014213)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
```
```
In arch/x86/events/intel/ds.c (ffffffff810184ef)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108d969)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
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
In arch/x86/events/core.c (ffffffff8100565d)
Location: arch/x86/include/asm/paravirt.h:252
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81013a73)
Location: arch/x86/include/asm/paravirt.h:252
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
```
```
In arch/x86/events/intel/ds.c (ffffffff81017dcf)
Location: arch/x86/include/asm/paravirt.h:252
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81090819)
Location: arch/x86/include/asm/paravirt.h:252
Inline: True
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
In arch/x86/events/core.c (ffffffff8100ad5c)
Location: arch/x86/include/asm/paravirt.h:254
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81019103)
Location: arch/x86/include/asm/paravirt.h:254
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
```
```
In arch/x86/events/intel/ds.c (ffffffff8101d93f)
Location: arch/x86/include/asm/paravirt.h:254
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81097ba9)
Location: arch/x86/include/asm/paravirt.h:254
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810065fa)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009576)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fc42)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106036c)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810065ba)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009536)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fc02)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106079c)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
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
In arch/x86/events/core.c (ffffffff8100671a)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009696)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fe12)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81061d1c)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
```
</details>
</li>
</ul>

## Differences
