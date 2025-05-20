# Function: <code>init_freq_invariance</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void init_freq_invariance(bool secondary);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106a490)
Location: arch/x86/kernel/smpboot.c:2051
Inline: True
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:smp_callin
```
**Symbols:**

```
ffffffff8106a490-ffffffff8106a52d: init_freq_invariance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void init_freq_invariance(bool secondary, bool cppc_ready);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106c17c)
Location: arch/x86/kernel/smpboot.c:2105
Inline: True
Direct callers:
  - arch/x86/kernel/smpboot.c:init_freq_invariance_cppc
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:smp_callin
```
**Symbols:**

```
ffffffff8106c160-ffffffff8106c1f9: init_freq_invariance (STB_LOCAL)
ffffffff81bd68d9-ffffffff81bd68f1: init_freq_invariance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void init_freq_invariance(bool secondary, bool cppc_ready);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106cbbd)
Location: arch/x86/kernel/smpboot.c:2101
Inline: True
Direct callers:
  - arch/x86/kernel/smpboot.c:init_freq_invariance_cppc
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8106cb90-ffffffff8106ccd0: init_freq_invariance (STB_LOCAL)
ffffffff81bc8ab3-ffffffff81bc8acb: init_freq_invariance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void init_freq_invariance(bool secondary, bool cppc_ready);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81077bad)
Location: arch/x86/kernel/smpboot.c:2108
Inline: True
Direct callers:
  - arch/x86/kernel/smpboot.c:init_freq_invariance_cppc
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81077b80-ffffffff81077cb4: init_freq_invariance (STB_LOCAL)
ffffffff81c9d3d7-ffffffff81c9d3ef: init_freq_invariance.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool cppc_ready</code>
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
</ul>
