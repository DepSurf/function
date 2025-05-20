# Function: <code>dlpar_release_drc</code>

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
int dlpar_release_drc(u32 drc_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/platforms/pseries/dlpar.c (c0000000000f3840)
Location: arch/powerpc/platforms/pseries/dlpar.c:311
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_remove
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_add
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_add
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_add
  - arch/powerpc/platforms/pseries/hotplug-memory.c:dlpar_memory
  - arch/powerpc/platforms/pseries/hotplug-memory.c:dlpar_memory
  - arch/powerpc/platforms/pseries/hotplug-memory.c:dlpar_memory
  - arch/powerpc/platforms/pseries/hotplug-memory.c:dlpar_memory
  - arch/powerpc/platforms/pseries/hotplug-memory.c:dlpar_memory
  - arch/powerpc/platforms/pseries/hotplug-memory.c:dlpar_memory
  - arch/powerpc/platforms/pseries/hotplug-memory.c:dlpar_memory
  - arch/powerpc/platforms/pseries/hotplug-memory.c:dlpar_memory
  - arch/powerpc/platforms/pseries/hotplug-memory.c:dlpar_memory
  - arch/powerpc/platforms/pseries/pmem.c:dlpar_hp_pmem
  - arch/powerpc/platforms/pseries/pmem.c:dlpar_hp_pmem
  - arch/powerpc/platforms/pseries/pmem.c:dlpar_hp_pmem
```
**Symbols:**

```
c0000000000f3840-c0000000000f3960: dlpar_release_drc (STB_GLOBAL)
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
