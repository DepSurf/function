# Function: <code>pebs_update_state</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events *cpuc, struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100f6b0)
Location: arch/x86/events/intel/ds.c:835
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_del
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_add
```
**Symbols:**

```
ffffffff8100f6b0-ffffffff8100f73b: pebs_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events *cpuc, struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100d790)
Location: arch/x86/events/intel/ds.c:853
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_del
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_add
```
**Symbols:**

```
ffffffff8100d790-ffffffff8100d824: pebs_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events *cpuc, struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100df10)
Location: arch/x86/events/intel/ds.c:909
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_del
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_add
```
**Symbols:**

```
ffffffff8100df10-ffffffff8100dfa4: pebs_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events *cpuc, struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100e6d0)
Location: arch/x86/events/intel/ds.c:911
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_del
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_add
```
**Symbols:**

```
ffffffff8100e6d0-ffffffff8100e764: pebs_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events *cpuc, struct pmu *pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100eb90)
Location: arch/x86/events/intel/ds.c:918
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_del
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_add
```
**Symbols:**

```
ffffffff8100eb90-ffffffff8100ec35: pebs_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events *cpuc, struct perf_event *event, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100f2c0)
Location: arch/x86/events/intel/ds.c:1006
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_del
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_add
```
**Symbols:**

```
ffffffff8100f2c0-ffffffff8100f524: pebs_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events *cpuc, struct perf_event *event, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100f970)
Location: arch/x86/events/intel/ds.c:1012
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_del
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_add
```
**Symbols:**

```
ffffffff8100f970-ffffffff8100fc00: pebs_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events *cpuc, struct perf_event *event, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010f00)
Location: arch/x86/events/intel/ds.c:1013
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_del
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_add
```
**Symbols:**

```
ffffffff81010f00-ffffffff810110c6: pebs_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events *cpuc, struct perf_event *event, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010560)
Location: arch/x86/events/intel/ds.c:1014
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_del
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_add
```
**Symbols:**

```
ffffffff81010560-ffffffff81010726: pebs_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events *cpuc, struct perf_event *event, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810113f0)
Location: arch/x86/events/intel/ds.c:1112
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_del
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_add
```
**Symbols:**

```
ffffffff810113f0-ffffffff810116c7: pebs_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events *cpuc, struct perf_event *event, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81012210)
Location: arch/x86/events/intel/ds.c:1113
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_del
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_add
```
**Symbols:**

```
ffffffff81012210-ffffffff810124e7: pebs_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events *cpuc, struct perf_event *event, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81013bb0)
Location: arch/x86/events/intel/ds.c:1162
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_del
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_add
```
**Symbols:**

```
ffffffff81013bb0-ffffffff81013ee9: pebs_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events *cpuc, struct perf_event *event, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81017c10)
Location: arch/x86/events/intel/ds.c:1179
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_del
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_add
```
**Symbols:**

```
ffffffff81017c10-ffffffff81017f2a: pebs_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events *cpuc, struct perf_event *event, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810175b0)
Location: arch/x86/events/intel/ds.c:1228
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_del
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_add
```
**Symbols:**

```
ffffffff810175b0-ffffffff81017809: pebs_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events *cpuc, struct perf_event *event, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8101d0f0)
Location: arch/x86/events/intel/ds.c:1233
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_del
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_add
```
**Symbols:**

```
ffffffff8101d0f0-ffffffff8101d349: pebs_update_state (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events *cpuc, struct perf_event *event, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100f970)
Location: arch/x86/events/intel/ds.c:1012
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_del
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_add
```
**Symbols:**

```
ffffffff8100f970-ffffffff8100fc00: pebs_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events *cpuc, struct perf_event *event, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100e6d0)
Location: arch/x86/events/intel/ds.c:1012
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_del
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_add
```
**Symbols:**

```
ffffffff8100e6d0-ffffffff8100e960: pebs_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events *cpuc, struct perf_event *event, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100f930)
Location: arch/x86/events/intel/ds.c:1012
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_del
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_add
```
**Symbols:**

```
ffffffff8100f930-ffffffff8100fbc0: pebs_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events *cpuc, struct perf_event *event, bool add);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100fb40)
Location: arch/x86/events/intel/ds.c:1012
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_del
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_add
```
**Symbols:**

```
ffffffff8100fb40-ffffffff8100fdd0: pebs_update_state (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct perf_event *event</code>
</li>
<li>
<b>Param added. </b>
<code>bool add</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pmu *pmu</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
