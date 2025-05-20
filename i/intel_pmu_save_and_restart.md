# Function: <code>intel_pmu_save_and_restart</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int intel_pmu_save_and_restart(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c280)
Location: arch/x86/events/intel/core.c:1771
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100c280-ffffffff8100c2ce: intel_pmu_save_and_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int intel_pmu_save_and_restart(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c4c0)
Location: arch/x86/events/intel/core.c:2000
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100c4c0-ffffffff8100c50e: intel_pmu_save_and_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int intel_pmu_save_and_restart(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c580)
Location: arch/x86/events/intel/core.c:2003
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100c580-ffffffff8100c5ce: intel_pmu_save_and_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int intel_pmu_save_and_restart(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c2c0)
Location: arch/x86/events/intel/core.c:2138
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100c2c0-ffffffff8100c30e: intel_pmu_save_and_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int intel_pmu_save_and_restart(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c860)
Location: arch/x86/events/intel/core.c:2138
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100c860-ffffffff8100c8ae: intel_pmu_save_and_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int intel_pmu_save_and_restart(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100cfc0)
Location: arch/x86/events/intel/core.c:2146
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100cfc0-ffffffff8100d005: intel_pmu_save_and_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int intel_pmu_save_and_restart(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d390)
Location: arch/x86/events/intel/core.c:2197
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100d390-ffffffff8100d3d5: intel_pmu_save_and_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int intel_pmu_save_and_restart(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100dc20)
Location: arch/x86/events/intel/core.c:2274
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100dc20-ffffffff8100dc76: intel_pmu_save_and_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int intel_pmu_save_and_restart(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e260)
Location: arch/x86/events/intel/core.c:2275
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100e260-ffffffff8100e2b6: intel_pmu_save_and_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_save_and_restart(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100f4cd)
Location: arch/x86/events/intel/core.c:2282
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
Direct callers:
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100fa40-ffffffff8100fa9a: intel_pmu_save_and_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_save_and_restart(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100eae8)
Location: arch/x86/events/intel/core.c:2542
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100f150-ffffffff8100f1aa: intel_pmu_save_and_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_save_and_restart(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100eeb2)
Location: arch/x86/events/intel/core.c:2724
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100faa0-ffffffff8100fafa: intel_pmu_save_and_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_save_and_restart(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100f9fc)
Location: arch/x86/events/intel/core.c:2726
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
**Symbols:**

```
ffffffff810104d0-ffffffff8101052a: intel_pmu_save_and_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_save_and_restart(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81010f94)
Location: arch/x86/events/intel/core.c:2794
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
**Symbols:**

```
ffffffff81011b00-ffffffff81011b83: intel_pmu_save_and_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_save_and_restart(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff810153fc)
Location: arch/x86/events/intel/core.c:2811
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
**Symbols:**

```
ffffffff81015bf0-ffffffff81015c73: intel_pmu_save_and_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_save_and_restart(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81014c5c)
Location: arch/x86/events/intel/core.c:2831
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
**Symbols:**

```
ffffffff81015480-ffffffff81015503: intel_pmu_save_and_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_save_and_restart(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81019c4c)
Location: arch/x86/events/intel/core.c:2839
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
**Symbols:**

```
ffffffff8101ae10-ffffffff8101ae93: intel_pmu_save_and_restart (STB_GLOBAL)
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
int intel_pmu_save_and_restart(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e260)
Location: arch/x86/events/intel/core.c:2275
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100e260-ffffffff8100e2b6: intel_pmu_save_and_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int intel_pmu_save_and_restart(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100ceb0)
Location: arch/x86/events/intel/core.c:2275
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100ceb0-ffffffff8100cf12: intel_pmu_save_and_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int intel_pmu_save_and_restart(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e220)
Location: arch/x86/events/intel/core.c:2275
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100e220-ffffffff8100e276: intel_pmu_save_and_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int intel_pmu_save_and_restart(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e3f0)
Location: arch/x86/events/intel/core.c:2275
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100e3f0-ffffffff8100e446: intel_pmu_save_and_restart (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
