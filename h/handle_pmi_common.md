# Function: <code>handle_pmi_common</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int handle_pmi_common(struct pt_regs *regs, u64 status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d3e0)
Location: arch/x86/events/intel/core.c:2252
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
```
**Symbols:**

```
ffffffff8100d3e0-ffffffff8100d5ea: handle_pmi_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int handle_pmi_common(struct pt_regs *regs, u64 status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100dc80)
Location: arch/x86/events/intel/core.c:2329
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
```
**Symbols:**

```
ffffffff8100dc80-ffffffff8100debe: handle_pmi_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int handle_pmi_common(struct pt_regs *regs, u64 status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e2c0)
Location: arch/x86/events/intel/core.c:2330
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
```
**Symbols:**

```
ffffffff8100e2c0-ffffffff8100e4fe: handle_pmi_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int handle_pmi_common(struct pt_regs *regs, u64 status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100f380)
Location: arch/x86/events/intel/core.c:2337
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
```
**Symbols:**

```
ffffffff8100f380-ffffffff8100f623: handle_pmi_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int handle_pmi_common(struct pt_regs *regs, u64 status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e970)
Location: arch/x86/events/intel/core.c:2597
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
```
**Symbols:**

```
ffffffff8100e970-ffffffff8100ec4c: handle_pmi_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int handle_pmi_common(struct pt_regs *regs, u64 status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100ed30)
Location: arch/x86/events/intel/core.c:2785
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100ed30-ffffffff8100f031: handle_pmi_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int handle_pmi_common(struct pt_regs *regs, u64 status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100f870)
Location: arch/x86/events/intel/core.c:2787
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100f870-ffffffff8100fb92: handle_pmi_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int handle_pmi_common(struct pt_regs *regs, u64 status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81010e20)
Location: arch/x86/events/intel/core.c:2855
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff81010e20-ffffffff81011144: handle_pmi_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int handle_pmi_common(struct pt_regs *regs, u64 status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff810152e0)
Location: arch/x86/events/intel/core.c:2929
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff810152e0-ffffffff810156e1: handle_pmi_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int handle_pmi_common(struct pt_regs *regs, u64 status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81014b40)
Location: arch/x86/events/intel/core.c:2949
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff81014b40-ffffffff81014f72: handle_pmi_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int handle_pmi_common(struct pt_regs *regs, u64 status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81019b30)
Location: arch/x86/events/intel/core.c:2957
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff81019b30-ffffffff81019f2d: handle_pmi_common (STB_LOCAL)
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
int handle_pmi_common(struct pt_regs *regs, u64 status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e2c0)
Location: arch/x86/events/intel/core.c:2330
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
```
**Symbols:**

```
ffffffff8100e2c0-ffffffff8100e4fe: handle_pmi_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int handle_pmi_common(struct pt_regs *regs, u64 status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100cf20)
Location: arch/x86/events/intel/core.c:2330
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
```
**Symbols:**

```
ffffffff8100cf20-ffffffff8100d15e: handle_pmi_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int handle_pmi_common(struct pt_regs *regs, u64 status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e280)
Location: arch/x86/events/intel/core.c:2330
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
```
**Symbols:**

```
ffffffff8100e280-ffffffff8100e4be: handle_pmi_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int handle_pmi_common(struct pt_regs *regs, u64 status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e450)
Location: arch/x86/events/intel/core.c:2330
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
```
**Symbols:**

```
ffffffff8100e450-ffffffff8100e68e: handle_pmi_common (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
