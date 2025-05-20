# Function: <code>cpu_to_chip_id</code>

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
int cpu_to_chip_id(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/prom.c (c00000000002c450)
Location: arch/powerpc/kernel/prom.c:876
Inline: False
Direct callers:
  - arch/powerpc/kernel/smp.c:start_secondary
  - arch/powerpc/kernel/smp.c:start_secondary
  - arch/powerpc/platforms/powernv/rng.c:__machine_initcall_powernv_rng_init
  - arch/powerpc/platforms/powernv/vas.c:vas_probe
  - arch/powerpc/platforms/powernv/vas.c:chip_to_vas_id
  - arch/powerpc/perf/imc-pmu.c:nest_imc_event_init
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - drivers/base/topology.c:physical_package_id_show
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_init
```
**Symbols:**

```
c00000000002c450-c00000000002c4b4: cpu_to_chip_id (STB_GLOBAL)
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
