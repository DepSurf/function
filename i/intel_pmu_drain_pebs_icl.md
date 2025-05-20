# Function: <code>intel_pmu_drain_pebs_icl</code>

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
void intel_pmu_drain_pebs_icl(struct pt_regs *iregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810103f0)
Location: arch/x86/events/intel/ds.c:1898
Inline: False
```
**Symbols:**

```
ffffffff810103f0-ffffffff810105e0: intel_pmu_drain_pebs_icl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void intel_pmu_drain_pebs_icl(struct pt_regs *iregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010ad0)
Location: arch/x86/events/intel/ds.c:1943
Inline: False
```
**Symbols:**

```
ffffffff81010ad0-ffffffff81010cc0: intel_pmu_drain_pebs_icl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_pmu_drain_pebs_icl(struct pt_regs *iregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810121a0)
Location: arch/x86/events/intel/ds.c:1944
Inline: False
```
**Symbols:**

```
ffffffff810121a0-ffffffff81012389: intel_pmu_drain_pebs_icl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_pmu_drain_pebs_icl(struct pt_regs *iregs, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81011470)
Location: arch/x86/events/intel/ds.c:1960
Inline: False
```
**Symbols:**

```
ffffffff81011470-ffffffff810119c7: intel_pmu_drain_pebs_icl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_pmu_drain_pebs_icl(struct pt_regs *iregs, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81012850)
Location: arch/x86/events/intel/ds.c:2080
Inline: False
```
**Symbols:**

```
ffffffff81012850-ffffffff81012e26: intel_pmu_drain_pebs_icl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void intel_pmu_drain_pebs_icl(struct pt_regs *iregs, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/intel/ds.c:2089
Inline: False
```
**Symbols:**

```
ffffffff81013c90-ffffffff8101435d: intel_pmu_drain_pebs_icl (STB_LOCAL)
ffffffff81c960eb-ffffffff81c96291: intel_pmu_drain_pebs_icl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void intel_pmu_drain_pebs_icl(struct pt_regs *iregs, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/intel/ds.c:2147
Inline: False
```
**Symbols:**

```
ffffffff810152c0-ffffffff81015a0e: intel_pmu_drain_pebs_icl (STB_LOCAL)
ffffffff81e45209-ffffffff81e4537e: intel_pmu_drain_pebs_icl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void intel_pmu_drain_pebs_icl(struct pt_regs *iregs, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/intel/ds.c:2206
Inline: False
```
**Symbols:**

```
ffffffff81019d40-ffffffff8101a493: intel_pmu_drain_pebs_icl (STB_LOCAL)
ffffffff82050c65-ffffffff82050dff: intel_pmu_drain_pebs_icl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void intel_pmu_drain_pebs_icl(struct pt_regs *iregs, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/intel/ds.c:2260
Inline: False
```
**Symbols:**

```
ffffffff810197d0-ffffffff81019f1d: intel_pmu_drain_pebs_icl (STB_LOCAL)
ffffffff820cf071-ffffffff820cf1f5: intel_pmu_drain_pebs_icl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void intel_pmu_drain_pebs_icl(struct pt_regs *iregs, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/intel/ds.c:2265
Inline: False
```
**Symbols:**

```
ffffffff8101f330-ffffffff8101fa7d: intel_pmu_drain_pebs_icl (STB_LOCAL)
ffffffff821a9910-ffffffff821a9a94: intel_pmu_drain_pebs_icl.cold (STB_LOCAL)
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
void intel_pmu_drain_pebs_icl(struct pt_regs *iregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010ad0)
Location: arch/x86/events/intel/ds.c:1943
Inline: False
```
**Symbols:**

```
ffffffff81010ad0-ffffffff81010cc0: intel_pmu_drain_pebs_icl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void intel_pmu_drain_pebs_icl(struct pt_regs *iregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100f870)
Location: arch/x86/events/intel/ds.c:1943
Inline: False
```
**Symbols:**

```
ffffffff8100f870-ffffffff8100fa60: intel_pmu_drain_pebs_icl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void intel_pmu_drain_pebs_icl(struct pt_regs *iregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010a90)
Location: arch/x86/events/intel/ds.c:1943
Inline: False
```
**Symbols:**

```
ffffffff81010a90-ffffffff81010c80: intel_pmu_drain_pebs_icl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void intel_pmu_drain_pebs_icl(struct pt_regs *iregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010ca0)
Location: arch/x86/events/intel/ds.c:1943
Inline: False
```
**Symbols:**

```
ffffffff81010ca0-ffffffff81010e90: intel_pmu_drain_pebs_icl (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct perf_sample_data *data</code>
</li>
</ul>
</details>
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
