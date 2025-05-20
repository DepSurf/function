# Function: <code>setup_pebs_adaptive_sample_data</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void setup_pebs_adaptive_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100f8d0)
Location: arch/x86/events/intel/ds.c:1465
Inline: False
```
**Symbols:**

```
ffffffff8100f8d0-ffffffff8100fcb0: setup_pebs_adaptive_sample_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void setup_pebs_adaptive_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100ffb0)
Location: arch/x86/events/intel/ds.c:1508
Inline: False
```
**Symbols:**

```
ffffffff8100ffb0-ffffffff81010390: setup_pebs_adaptive_sample_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void setup_pebs_adaptive_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81011450)
Location: arch/x86/events/intel/ds.c:1509
Inline: False
```
**Symbols:**

```
ffffffff81011450-ffffffff81011834: setup_pebs_adaptive_sample_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void setup_pebs_adaptive_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010a80)
Location: arch/x86/events/intel/ds.c:1514
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
```
**Symbols:**

```
ffffffff81010a80-ffffffff81010e64: setup_pebs_adaptive_sample_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void setup_pebs_adaptive_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81011a40)
Location: arch/x86/events/intel/ds.c:1616
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
```
**Symbols:**

```
ffffffff81011a40-ffffffff81011e4a: setup_pebs_adaptive_sample_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void setup_pebs_adaptive_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/intel/ds.c:1625
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
```
**Symbols:**

```
ffffffff81012910-ffffffff81012d33: setup_pebs_adaptive_sample_data (STB_LOCAL)
ffffffff81c95ed9-ffffffff81c95ef5: setup_pebs_adaptive_sample_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void setup_pebs_adaptive_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/intel/ds.c:1683
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
```
**Symbols:**

```
ffffffff81014600-ffffffff81014a47: setup_pebs_adaptive_sample_data (STB_LOCAL)
ffffffff81e451ed-ffffffff81e45209: setup_pebs_adaptive_sample_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void setup_pebs_adaptive_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/intel/ds.c:1733
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
```
**Symbols:**

```
ffffffff810187e0-ffffffff81018c10: setup_pebs_adaptive_sample_data (STB_LOCAL)
ffffffff82050a60-ffffffff82050a7c: setup_pebs_adaptive_sample_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void setup_pebs_adaptive_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/intel/ds.c:1787
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
```
**Symbols:**

```
ffffffff810180c0-ffffffff8101855c: setup_pebs_adaptive_sample_data (STB_LOCAL)
ffffffff820cee76-ffffffff820cee92: setup_pebs_adaptive_sample_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void setup_pebs_adaptive_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/intel/ds.c:1792
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
```
**Symbols:**

```
ffffffff8101dc40-ffffffff8101e0a6: setup_pebs_adaptive_sample_data (STB_LOCAL)
ffffffff821a9715-ffffffff821a9731: setup_pebs_adaptive_sample_data.cold (STB_LOCAL)
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
void setup_pebs_adaptive_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100ffb0)
Location: arch/x86/events/intel/ds.c:1508
Inline: False
```
**Symbols:**

```
ffffffff8100ffb0-ffffffff81010390: setup_pebs_adaptive_sample_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void setup_pebs_adaptive_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100ed50)
Location: arch/x86/events/intel/ds.c:1508
Inline: False
```
**Symbols:**

```
ffffffff8100ed50-ffffffff8100f130: setup_pebs_adaptive_sample_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void setup_pebs_adaptive_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100ff70)
Location: arch/x86/events/intel/ds.c:1508
Inline: False
```
**Symbols:**

```
ffffffff8100ff70-ffffffff81010350: setup_pebs_adaptive_sample_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void setup_pebs_adaptive_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010180)
Location: arch/x86/events/intel/ds.c:1508
Inline: False
```
**Symbols:**

```
ffffffff81010180-ffffffff81010560: setup_pebs_adaptive_sample_data (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
