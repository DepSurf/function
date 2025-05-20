# Function: <code>free_excl_cntrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_excl_cntrs(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100afb0)
Location: arch/x86/events/intel/core.c:2898
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff8100afb0-ffffffff8100b016: free_excl_cntrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_excl_cntrs(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100b060)
Location: arch/x86/events/intel/core.c:3179
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff8100b060-ffffffff8100b0c6: free_excl_cntrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_excl_cntrs(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100b120)
Location: arch/x86/events/intel/core.c:3197
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff8100b120-ffffffff8100b186: free_excl_cntrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_excl_cntrs(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100ae40)
Location: arch/x86/events/intel/core.c:3365
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff8100ae40-ffffffff8100aea6: free_excl_cntrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_excl_cntrs(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100b190)
Location: arch/x86/events/intel/core.c:3369
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff8100b190-ffffffff8100b1f6: free_excl_cntrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_excl_cntrs(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100b630)
Location: arch/x86/events/intel/core.c:3389
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff8100b630-ffffffff8100b696: free_excl_cntrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c120)
Location: arch/x86/events/intel/core.c:3613
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_cpuc_finish
```
**Symbols:**

```
ffffffff8100c120-ffffffff8100c16f: free_excl_cntrs.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c8c0)
Location: arch/x86/events/intel/core.c:3765
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_cpuc_finish
```
**Symbols:**

```
ffffffff8100c8c0-ffffffff8100c90f: free_excl_cntrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100ccf0)
Location: arch/x86/events/intel/core.c:3773
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_cpuc_finish
```
**Symbols:**

```
ffffffff8100ccf0-ffffffff8100cd3f: free_excl_cntrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_excl_cntrs(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100fd26)
Location: arch/x86/events/intel/core.c:3804
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_finish
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
```
**Symbols:**

```
ffffffff8100fdc4-ffffffff8100fe1a: free_excl_cntrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void free_excl_cntrs(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100f436)
Location: arch/x86/events/intel/core.c:4158
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_finish
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
```
**Symbols:**

```
ffffffff81bd2127-ffffffff81bd217d: free_excl_cntrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void free_excl_cntrs(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81010466)
Location: arch/x86/events/intel/core.c:4435
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_finish
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
```
**Symbols:**

```
ffffffff81bc4244-ffffffff81bc429a: free_excl_cntrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void free_excl_cntrs(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81011066)
Location: arch/x86/events/intel/core.c:4442
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_finish
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
```
**Symbols:**

```
ffffffff81c956a2-ffffffff81c956f8: free_excl_cntrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void free_excl_cntrs(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81012786)
Location: arch/x86/events/intel/core.c:4504
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_finish
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
```
**Symbols:**

```
ffffffff81e449da-ffffffff81e44a36: free_excl_cntrs (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff83e6635f)
Location: arch/x86/events/intel/core.c:4628
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_cpuc_finish
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
In arch/x86/events/intel/core.c (ffffffff836869cf)
Location: arch/x86/events/intel/core.c:4759
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_cpuc_finish
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
In arch/x86/events/intel/core.c (ffffffff838b5bdf)
Location: arch/x86/events/intel/core.c:4914
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_cpuc_finish
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100ccf0)
Location: arch/x86/events/intel/core.c:3773
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_cpuc_finish
```
**Symbols:**

```
ffffffff8100ccf0-ffffffff8100cd3f: free_excl_cntrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100b4f0)
Location: arch/x86/events/intel/core.c:3773
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_cpuc_finish
```
**Symbols:**

```
ffffffff8100b4f0-ffffffff8100b53f: free_excl_cntrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100ccb0)
Location: arch/x86/events/intel/core.c:3773
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_cpuc_finish
```
**Symbols:**

```
ffffffff8100ccb0-ffffffff8100ccff: free_excl_cntrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100cee0)
Location: arch/x86/events/intel/core.c:3773
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_cpuc_finish
```
**Symbols:**

```
ffffffff8100cee0-ffffffff8100cf2f: free_excl_cntrs.isra.0 (STB_LOCAL)
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
</ul>
