# Function: <code>__set_cyc2ns_scale</code>

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
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff82892dad)
Location: arch/x86/kernel/tsc.c:122
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
**Symbols:**

```
ffffffff81038e40-ffffffff81038f75: __set_cyc2ns_scale.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103b2b0)
Location: arch/x86/kernel/tsc.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
**Symbols:**

```
ffffffff8103b2b0-ffffffff8103b3df: __set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103ba60)
Location: arch/x86/kernel/tsc.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
**Symbols:**

```
ffffffff8103ba60-ffffffff8103bb8f: __set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103e7b0)
Location: arch/x86/kernel/tsc.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
```
**Symbols:**

```
ffffffff8103e7b0-ffffffff8103e8db: __set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103e860)
Location: arch/x86/kernel/tsc.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
```
**Symbols:**

```
ffffffff8103e860-ffffffff8103e98b: __set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81040230)
Location: arch/x86/kernel/tsc.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
```
**Symbols:**

```
ffffffff81040230-ffffffff8104035d: __set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/kernel/tsc.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
```
**Symbols:**

```
ffffffff810465c0-ffffffff81046760: __set_cyc2ns_scale (STB_LOCAL)
ffffffff81c99a0f-ffffffff81c99a6b: __set_cyc2ns_scale.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/kernel/tsc.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
**Symbols:**

```
ffffffff8104f550-ffffffff8104f731: __set_cyc2ns_scale (STB_LOCAL)
ffffffff81e49625-ffffffff81e49681: __set_cyc2ns_scale.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/kernel/tsc.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
**Symbols:**

```
ffffffff8105c6e0-ffffffff8105c8c1: __set_cyc2ns_scale (STB_LOCAL)
ffffffff8205252d-ffffffff82052589: __set_cyc2ns_scale.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/kernel/tsc.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
**Symbols:**

```
ffffffff8105d2d0-ffffffff8105d4b1: __set_cyc2ns_scale (STB_LOCAL)
ffffffff820d09fc-ffffffff820d0a58: __set_cyc2ns_scale.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/kernel/tsc.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
**Symbols:**

```
ffffffff81064390-ffffffff81064571: __set_cyc2ns_scale (STB_LOCAL)
ffffffff821ab525-ffffffff821ab581: __set_cyc2ns_scale.cold (STB_LOCAL)
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
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103bbc0)
Location: arch/x86/kernel/tsc.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
**Symbols:**

```
ffffffff8103bbc0-ffffffff8103bcef: __set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8102b340)
Location: arch/x86/kernel/tsc.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
**Symbols:**

```
ffffffff8102b340-ffffffff8102b46f: __set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103ba20)
Location: arch/x86/kernel/tsc.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
**Symbols:**

```
ffffffff8103ba20-ffffffff8103bb4f: __set_cyc2ns_scale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __set_cyc2ns_scale(long unsigned int khz, int cpu, long long unsigned int tsc_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103cad0)
Location: arch/x86/kernel/tsc.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
**Symbols:**

```
ffffffff8103cad0-ffffffff8103cc1d: __set_cyc2ns_scale (STB_LOCAL)
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
