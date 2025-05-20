# Function: <code>get_this_hybrid_cpu_type</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
u8 get_this_hybrid_cpu_type();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104f780)
Location: arch/x86/kernel/cpu/intel.c:1280
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
**Symbols:**

```
ffffffff8104f780-ffffffff8104f7e4: get_this_hybrid_cpu_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u8 get_this_hybrid_cpu_type();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81057960)
Location: arch/x86/kernel/cpu/intel.c:1320
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
**Symbols:**

```
ffffffff81057960-ffffffff810579c4: get_this_hybrid_cpu_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u8 get_this_hybrid_cpu_type();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81063c50)
Location: arch/x86/kernel/cpu/intel.c:1378
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
**Symbols:**

```
ffffffff81063c50-ffffffff81063cd9: get_this_hybrid_cpu_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u8 get_this_hybrid_cpu_type();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81072db0)
Location: arch/x86/kernel/cpu/intel.c:1563
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
  - drivers/cpufreq/intel_pstate.c:hybrid_get_type
```
**Symbols:**

```
ffffffff81072db0-ffffffff81072e39: get_this_hybrid_cpu_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u8 get_this_hybrid_cpu_type();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81074990)
Location: arch/x86/kernel/cpu/intel.c:1548
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
  - drivers/cpufreq/intel_pstate.c:hybrid_get_type
```
**Symbols:**

```
ffffffff81074990-ffffffff81074a19: get_this_hybrid_cpu_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u8 get_this_hybrid_cpu_type();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8107be60)
Location: arch/x86/kernel/cpu/intel.c:1364
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
  - drivers/cpufreq/intel_pstate.c:hybrid_get_type
```
**Symbols:**

```
ffffffff8107be60-ffffffff8107bee9: get_this_hybrid_cpu_type (STB_GLOBAL)
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
