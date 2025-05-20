# Function: <code>setup_pebs_fixed_sample_data</code>

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
void setup_pebs_fixed_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100fcb0)
Location: arch/x86/events/intel/ds.c:1296
Inline: False
```
**Symbols:**

```
ffffffff8100fcb0-ffffffff81010059: setup_pebs_fixed_sample_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void setup_pebs_fixed_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010390)
Location: arch/x86/events/intel/ds.c:1339
Inline: False
```
**Symbols:**

```
ffffffff81010390-ffffffff81010739: setup_pebs_fixed_sample_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void setup_pebs_fixed_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81011b00)
Location: arch/x86/events/intel/ds.c:1340
Inline: False
```
**Symbols:**

```
ffffffff81011b00-ffffffff81011e98: setup_pebs_fixed_sample_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void setup_pebs_fixed_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81011020)
Location: arch/x86/events/intel/ds.c:1345
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
```
**Symbols:**

```
ffffffff81011020-ffffffff810113b8: setup_pebs_fixed_sample_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void setup_pebs_fixed_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81012010)
Location: arch/x86/events/intel/ds.c:1444
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
```
**Symbols:**

```
ffffffff81012010-ffffffff810123ae: setup_pebs_fixed_sample_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void setup_pebs_fixed_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81012f00)
Location: arch/x86/events/intel/ds.c:1453
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
```
**Symbols:**

```
ffffffff81012f00-ffffffff810132af: setup_pebs_fixed_sample_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void setup_pebs_fixed_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81014a50)
Location: arch/x86/events/intel/ds.c:1511
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
```
**Symbols:**

```
ffffffff81014a50-ffffffff81014e13: setup_pebs_fixed_sample_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void setup_pebs_fixed_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81018c20)
Location: arch/x86/events/intel/ds.c:1549
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
```
**Symbols:**

```
ffffffff81018c20-ffffffff81018fdb: setup_pebs_fixed_sample_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void setup_pebs_fixed_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81018620)
Location: arch/x86/events/intel/ds.c:1606
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
```
**Symbols:**

```
ffffffff81018620-ffffffff81018a1f: setup_pebs_fixed_sample_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void setup_pebs_fixed_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8101e170)
Location: arch/x86/events/intel/ds.c:1611
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
```
**Symbols:**

```
ffffffff8101e170-ffffffff8101e577: setup_pebs_fixed_sample_data (STB_LOCAL)
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
void setup_pebs_fixed_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010390)
Location: arch/x86/events/intel/ds.c:1339
Inline: False
```
**Symbols:**

```
ffffffff81010390-ffffffff81010739: setup_pebs_fixed_sample_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void setup_pebs_fixed_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100f130)
Location: arch/x86/events/intel/ds.c:1339
Inline: False
```
**Symbols:**

```
ffffffff8100f130-ffffffff8100f4d9: setup_pebs_fixed_sample_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void setup_pebs_fixed_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010350)
Location: arch/x86/events/intel/ds.c:1339
Inline: False
```
**Symbols:**

```
ffffffff81010350-ffffffff810106f9: setup_pebs_fixed_sample_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void setup_pebs_fixed_sample_data(struct perf_event *event, struct pt_regs *iregs, void *__pebs, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010560)
Location: arch/x86/events/intel/ds.c:1339
Inline: False
```
**Symbols:**

```
ffffffff81010560-ffffffff81010909: setup_pebs_fixed_sample_data (STB_LOCAL)
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
