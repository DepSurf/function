# Function: <code>init_hybrid_pmu</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool init_hybrid_pmu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:4302
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
```
**Symbols:**

```
ffffffff8100df60-ffffffff8100e086: init_hybrid_pmu (STB_LOCAL)
ffffffff81bc4555-ffffffff81bc45ae: init_hybrid_pmu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool init_hybrid_pmu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:4309
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
```
**Symbols:**

```
ffffffff8100e6e0-ffffffff8100e827: init_hybrid_pmu (STB_LOCAL)
ffffffff81c95ada-ffffffff81c95b33: init_hybrid_pmu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool init_hybrid_pmu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:4371
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
```
**Symbols:**

```
ffffffff8100ea00-ffffffff8100eb3b: init_hybrid_pmu (STB_LOCAL)
ffffffff81e44ae3-ffffffff81e44b34: init_hybrid_pmu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool init_hybrid_pmu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff810120a0)
Location: arch/x86/events/intel/core.c:4497
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
```
**Symbols:**

```
ffffffff810120a0-ffffffff81012217: init_hybrid_pmu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool init_hybrid_pmu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81013120)
Location: arch/x86/events/intel/core.c:4625
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
```
**Symbols:**

```
ffffffff81013120-ffffffff81013399: init_hybrid_pmu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool init_hybrid_pmu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:4789
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
```
**Symbols:**

```
ffffffff8101a380-ffffffff8101a738: init_hybrid_pmu (STB_LOCAL)
ffffffff821a9458-ffffffff821a949c: init_hybrid_pmu.cold (STB_LOCAL)
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
