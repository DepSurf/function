# Function: <code>__ppc64_runlatch_on</code>

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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __ppc64_runlatch_on();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/process.c (c000000000022df0)
Location: arch/powerpc/kernel/process.c:2100
Inline: False
Direct callers:
  - arch/powerpc/kernel/idle.c:arch_cpu_idle
  - arch/powerpc/platforms/powernv/idle.c:pnv_cpu_offline
  - arch/powerpc/platforms/powernv/idle.c:pnv_cpu_offline
  - arch/powerpc/platforms/powernv/idle.c:pnv_cpu_offline
  - arch/powerpc/platforms/powernv/idle.c:pnv_cpu_offline
  - drivers/cpuidle/cpuidle-pseries.c:shared_cede_loop
  - drivers/cpuidle/cpuidle-pseries.c:dedicated_cede_loop
  - drivers/cpuidle/cpuidle-pseries.c:snooze_loop
  - drivers/cpuidle/cpuidle-powernv.c:snooze_loop
```
**Symbols:**

```
c000000000022df0-c000000000022e0c: __ppc64_runlatch_on (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
