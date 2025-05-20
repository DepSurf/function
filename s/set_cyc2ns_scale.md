# Function: <code>set_cyc2ns_scale</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_cyc2ns_scale(long unsigned int cpu_khz, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81037ac0)
Location: arch/x86/kernel/tsc.c:242
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:tsc_init
```
**Symbols:**

```
ffffffff81037ac0-ffffffff81037c26: set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void set_cyc2ns_scale(long unsigned int khz, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81036cd0)
Location: arch/x86/kernel/tsc.c:243
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
```
**Symbols:**

```
ffffffff81036cd0-ffffffff81036e34: set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void set_cyc2ns_scale(long unsigned int khz, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81036a00)
Location: arch/x86/kernel/tsc.c:244
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
```
**Symbols:**

```
ffffffff81036a00-ffffffff81036b6f: set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81034920)
Location: arch/x86/kernel/tsc.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
```
**Symbols:**

```
ffffffff81034920-ffffffff81034a85: set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81036c80)
Location: arch/x86/kernel/tsc.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
```
**Symbols:**

```
ffffffff81036c80-ffffffff81036de5: set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81037d10)
Location: arch/x86/kernel/tsc.c:141
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
```
**Symbols:**

```
ffffffff81037d10-ffffffff81037e5e: set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff810392d0)
Location: arch/x86/kernel/tsc.c:160
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
```
**Symbols:**

```
ffffffff810392d0-ffffffff81039327: set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103b870)
Location: arch/x86/kernel/tsc.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
**Symbols:**

```
ffffffff8103b870-ffffffff8103b8c7: set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c040)
Location: arch/x86/kernel/tsc.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
**Symbols:**

```
ffffffff8103c040-ffffffff8103c097: set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103f2da)
Location: arch/x86/kernel/tsc.c:168
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
**Symbols:**

```
ffffffff8103ef00-ffffffff8103ef57: set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103f39a)
Location: arch/x86/kernel/tsc.c:168
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
**Symbols:**

```
ffffffff8103efc0-ffffffff8103f017: set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff810409ba)
Location: arch/x86/kernel/tsc.c:169
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
**Symbols:**

```
ffffffff81040aa0-ffffffff81040b0a: set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81046aaa)
Location: arch/x86/kernel/tsc.c:169
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
**Symbols:**

```
ffffffff81046b90-ffffffff81046bfa: set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8104f740)
Location: arch/x86/kernel/tsc.c:169
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
```
**Symbols:**

```
ffffffff8104f740-ffffffff8104f7a6: set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8105c8e0)
Location: arch/x86/kernel/tsc.c:169
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
**Symbols:**

```
ffffffff8105c8e0-ffffffff8105c948: set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8105d4d0)
Location: arch/x86/kernel/tsc.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
**Symbols:**

```
ffffffff8105d4d0-ffffffff8105d538: set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81064590)
Location: arch/x86/kernel/tsc.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
**Symbols:**

```
ffffffff81064590-ffffffff810645f8: set_cyc2ns_scale (STB_LOCAL)
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
void set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c1a0)
Location: arch/x86/kernel/tsc.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
**Symbols:**

```
ffffffff8103c1a0-ffffffff8103c1f7: set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8102b470)
Location: arch/x86/kernel/tsc.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
**Symbols:**

```
ffffffff8102b470-ffffffff8102b4b1: set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c000)
Location: arch/x86/kernel/tsc.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
**Symbols:**

```
ffffffff8103c000-ffffffff8103c057: set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103d050)
Location: arch/x86/kernel/tsc.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
**Symbols:**

```
ffffffff8103d050-ffffffff8103d0a7: set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int khz</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int cpu_khz</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long long unsigned int tsc_now</code>
</li>
</ul>
</details>
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
