# Function: <code>x86_pmu_update_cpu_context</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void x86_pmu_update_cpu_context(struct pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff831bba43)
Location: arch/x86/events/core.c:2056
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
Direct callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
**Symbols:**

```
ffffffff81008b90-ffffffff81008bb3: x86_pmu_update_cpu_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void x86_pmu_update_cpu_context(struct pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8329bfb7)
Location: arch/x86/events/core.c:2054
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
Direct callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
**Symbols:**

```
ffffffff810099d0-ffffffff81009a23: x86_pmu_update_cpu_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void x86_pmu_update_cpu_context(struct pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8344a7d7)
Location: arch/x86/events/core.c:2068
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
Direct callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
**Symbols:**

```
ffffffff810090d0-ffffffff8100912d: x86_pmu_update_cpu_context (STB_GLOBAL)
```
</details>
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
