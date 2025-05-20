# Function: <code>allocate_shared_regs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct intel_shared_regs *allocate_shared_regs(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c7a0)
Location: arch/x86/events/intel/core.c:2774
Inline: False
Direct callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff8100c7a0-ffffffff8100c80a: allocate_shared_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct intel_shared_regs *allocate_shared_regs(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100ca00)
Location: arch/x86/events/intel/core.c:3057
Inline: False
Direct callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff8100ca00-ffffffff8100ca6a: allocate_shared_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct intel_shared_regs *allocate_shared_regs(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100cad0)
Location: arch/x86/events/intel/core.c:3072
Inline: False
Direct callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff8100cad0-ffffffff8100cb3a: allocate_shared_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct intel_shared_regs *allocate_shared_regs(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c830)
Location: arch/x86/events/intel/core.c:3225
Inline: False
Direct callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff8100c830-ffffffff8100c89a: allocate_shared_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct intel_shared_regs *allocate_shared_regs(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100cdd0)
Location: arch/x86/events/intel/core.c:3229
Inline: False
Direct callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff8100cdd0-ffffffff8100ce3a: allocate_shared_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct intel_shared_regs *allocate_shared_regs(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d500)
Location: arch/x86/events/intel/core.c:3248
Inline: False
Direct callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff8100d500-ffffffff8100d56a: allocate_shared_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d912)
Location: arch/x86/events/intel/core.c:3463
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e1de)
Location: arch/x86/events/intel/core.c:3607
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e81e)
Location: arch/x86/events/intel/core.c:3615
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100fb2e)
Location: arch/x86/events/intel/core.c:3646
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100f23e)
Location: arch/x86/events/intel/core.c:3989
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81010263)
Location: arch/x86/events/intel/core.c:4211
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81010dd2)
Location: arch/x86/events/intel/core.c:4218
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81012502)
Location: arch/x86/events/intel/core.c:4280
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81016482)
Location: arch/x86/events/intel/core.c:4406
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81015e14)
Location: arch/x86/events/intel/core.c:4515
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8101b8b4)
Location: arch/x86/events/intel/core.c:4595
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e81e)
Location: arch/x86/events/intel/core.c:3615
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d51e)
Location: arch/x86/events/intel/core.c:3615
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e7de)
Location: arch/x86/events/intel/core.c:3615
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e9ae)
Location: arch/x86/events/intel/core.c:3615
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
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
</ul>
