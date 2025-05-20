# Function: <code>amd_pmu_cpu_reset</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100b258)
Location: arch/x86/events/amd/core.c:585
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100c770)
Location: arch/x86/events/amd/core.c:526
Inline: True
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_dead
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
```
**Symbols:**

```
ffffffff8100c770-ffffffff8100c7d7: amd_pmu_cpu_reset.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100bf30)
Location: arch/x86/events/amd/core.c:526
Inline: True
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_dead
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
```
**Symbols:**

```
ffffffff8100bf30-ffffffff8100bf97: amd_pmu_cpu_reset.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81011710)
Location: arch/x86/events/amd/core.c:526
Inline: True
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_dead
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
```
**Symbols:**

```
ffffffff81011710-ffffffff8101177e: amd_pmu_cpu_reset.isra.0 (STB_LOCAL)
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
