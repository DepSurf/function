# Function: <code>intel_pmu_save_and_restart_reload</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int intel_pmu_save_and_restart_reload(struct perf_event *event, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100e770)
Location: arch/x86/events/intel/ds.c:1344
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
```
**Symbols:**

```
ffffffff8100e770-ffffffff8100e805: intel_pmu_save_and_restart_reload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int intel_pmu_save_and_restart_reload(struct perf_event *event, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100ec40)
Location: arch/x86/events/intel/ds.c:1355
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
```
**Symbols:**

```
ffffffff8100ec40-ffffffff8100ecd5: intel_pmu_save_and_restart_reload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int intel_pmu_save_and_restart_reload(struct perf_event *event, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/intel/ds.c:1623
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
```
**Symbols:**

```
ffffffff8100f530-ffffffff8100f5c6: intel_pmu_save_and_restart_reload (STB_LOCAL)
ffffffff8101183f-ffffffff81011865: intel_pmu_save_and_restart_reload.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int intel_pmu_save_and_restart_reload(struct perf_event *event, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100fc00)
Location: arch/x86/events/intel/ds.c:1666
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
```
**Symbols:**

```
ffffffff8100fc00-ffffffff8100fca4: intel_pmu_save_and_restart_reload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81011260)
Location: arch/x86/events/intel/ds.c:1667
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
```
**Symbols:**

```
ffffffff81011260-ffffffff81011302: intel_pmu_save_and_restart_reload.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010890)
Location: arch/x86/events/intel/ds.c:1672
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
```
**Symbols:**

```
ffffffff81010890-ffffffff81010932: intel_pmu_save_and_restart_reload.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81011830)
Location: arch/x86/events/intel/ds.c:1792
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
```
**Symbols:**

```
ffffffff81011830-ffffffff810118d2: intel_pmu_save_and_restart_reload.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/intel/ds.c:1801
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
```
**Symbols:**

```
ffffffff810126f0-ffffffff810127ab: intel_pmu_save_and_restart_reload.isra.0 (STB_LOCAL)
ffffffff81c95e56-ffffffff81c95ed9: intel_pmu_save_and_restart_reload.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/intel/ds.c:1859
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
```
**Symbols:**

```
ffffffff810142e0-ffffffff810143bc: intel_pmu_save_and_restart_reload.isra.0 (STB_LOCAL)
ffffffff81e4516c-ffffffff81e451ed: intel_pmu_save_and_restart_reload.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/intel/ds.c:1918
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
```
**Symbols:**

```
ffffffff810184a0-ffffffff8101857c: intel_pmu_save_and_restart_reload.isra.0 (STB_LOCAL)
ffffffff820509df-ffffffff82050a60: intel_pmu_save_and_restart_reload.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/intel/ds.c:1972
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
```
**Symbols:**

```
ffffffff81017d80-ffffffff81017e5f: intel_pmu_save_and_restart_reload.isra.0 (STB_LOCAL)
ffffffff820cee1c-ffffffff820cee76: intel_pmu_save_and_restart_reload.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/intel/ds.c:1977
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
```
**Symbols:**

```
ffffffff8101d8f0-ffffffff8101d9cf: intel_pmu_save_and_restart_reload.isra.0 (STB_LOCAL)
ffffffff821a96bb-ffffffff821a9715: intel_pmu_save_and_restart_reload.isra.0.cold (STB_LOCAL)
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
int intel_pmu_save_and_restart_reload(struct perf_event *event, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100fc00)
Location: arch/x86/events/intel/ds.c:1666
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
```
**Symbols:**

```
ffffffff8100fc00-ffffffff8100fca4: intel_pmu_save_and_restart_reload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int intel_pmu_save_and_restart_reload(struct perf_event *event, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100e960)
Location: arch/x86/events/intel/ds.c:1666
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
```
**Symbols:**

```
ffffffff8100e960-ffffffff8100ea47: intel_pmu_save_and_restart_reload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int intel_pmu_save_and_restart_reload(struct perf_event *event, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100fbc0)
Location: arch/x86/events/intel/ds.c:1666
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
```
**Symbols:**

```
ffffffff8100fbc0-ffffffff8100fc64: intel_pmu_save_and_restart_reload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int intel_pmu_save_and_restart_reload(struct perf_event *event, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100fdd0)
Location: arch/x86/events/intel/ds.c:1666
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
```
**Symbols:**

```
ffffffff8100fdd0-ffffffff8100fe74: intel_pmu_save_and_restart_reload (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
