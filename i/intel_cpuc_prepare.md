# Function: <code>intel_cpuc_prepare</code>

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
int intel_cpuc_prepare(struct cpu_hw_events *cpuc, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d8f0)
Location: arch/x86/events/intel/core.c:3496
Inline: False
Direct callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff8100d8f0-ffffffff8100daac: intel_cpuc_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int intel_cpuc_prepare(struct cpu_hw_events *cpuc, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e1b0)
Location: arch/x86/events/intel/core.c:3640
Inline: False
Direct callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff8100e1b0-ffffffff8100e375: intel_cpuc_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int intel_cpuc_prepare(struct cpu_hw_events *cpuc, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e7f0)
Location: arch/x86/events/intel/core.c:3648
Inline: False
Direct callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff8100e7f0-ffffffff8100e9b5: intel_cpuc_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int intel_cpuc_prepare(struct cpu_hw_events *cpuc, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100fb00)
Location: arch/x86/events/intel/core.c:3679
Inline: False
Direct callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff8100fb00-ffffffff8100fcbd: intel_cpuc_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int intel_cpuc_prepare(struct cpu_hw_events *cpuc, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100f210)
Location: arch/x86/events/intel/core.c:4022
Inline: False
Direct callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff8100f210-ffffffff8100f3cd: intel_cpuc_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int intel_cpuc_prepare(struct cpu_hw_events *cpuc, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81010230)
Location: arch/x86/events/intel/core.c:4244
Inline: False
Direct callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff81010230-ffffffff810103f5: intel_cpuc_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int intel_cpuc_prepare(struct cpu_hw_events *cpuc, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81010da0)
Location: arch/x86/events/intel/core.c:4251
Inline: False
Direct callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff81010da0-ffffffff81010fd4: intel_cpuc_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int intel_cpuc_prepare(struct cpu_hw_events *cpuc, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff810124d0)
Location: arch/x86/events/intel/core.c:4313
Inline: False
Direct callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff810124d0-ffffffff810126e4: intel_cpuc_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_cpuc_prepare(struct cpu_hw_events *cpuc, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81016450)
Location: arch/x86/events/intel/core.c:4439
Inline: False
Direct callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff81016450-ffffffff81016664: intel_cpuc_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_cpuc_prepare(struct cpu_hw_events *cpuc, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81015de0)
Location: arch/x86/events/intel/core.c:4548
Inline: False
Direct callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff81015de0-ffffffff81015ffd: intel_cpuc_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_cpuc_prepare(struct cpu_hw_events *cpuc, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8101b880)
Location: arch/x86/events/intel/core.c:4628
Inline: False
Direct callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff8101b880-ffffffff8101bb37: intel_cpuc_prepare (STB_GLOBAL)
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
int intel_cpuc_prepare(struct cpu_hw_events *cpuc, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e7f0)
Location: arch/x86/events/intel/core.c:3648
Inline: False
Direct callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff8100e7f0-ffffffff8100e9b5: intel_cpuc_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int intel_cpuc_prepare(struct cpu_hw_events *cpuc, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d4f0)
Location: arch/x86/events/intel/core.c:3648
Inline: False
Direct callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff8100d4f0-ffffffff8100d6b5: intel_cpuc_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int intel_cpuc_prepare(struct cpu_hw_events *cpuc, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e7b0)
Location: arch/x86/events/intel/core.c:3648
Inline: False
Direct callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff8100e7b0-ffffffff8100e975: intel_cpuc_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int intel_cpuc_prepare(struct cpu_hw_events *cpuc, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e980)
Location: arch/x86/events/intel/core.c:3648
Inline: False
Direct callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff8100e980-ffffffff8100eb45: intel_cpuc_prepare (STB_GLOBAL)
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
