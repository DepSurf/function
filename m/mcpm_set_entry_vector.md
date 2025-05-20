# Function: <code>mcpm_set_entry_vector</code>

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
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void mcpm_set_entry_vector(unsigned int cpu, unsigned int cluster, void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/common/mcpm_entry.c (c150babc)
Location: arch/arm/common/mcpm_entry.c:143
Inline: True
Inline callers:
  - arch/arm/common/mcpm_entry.c:nocache_trampoline
Direct callers:
  - arch/arm/common/mcpm_platsmp.c:mcpm_cpu_die
  - arch/arm/common/mcpm_platsmp.c:mcpm_boot_secondary
  - arch/arm/common/mcpm_platsmp.c:mcpm_boot_secondary
  - arch/arm/common/bL_switcher.c:bL_switch_to
  - arch/arm/common/bL_switcher.c:bL_switch_to
  - arch/arm/common/bL_switcher.c:bL_do_switch
  - arch/arm/mach-exynos/suspend.c:exynos5420_cpu_suspend
  - drivers/cpuidle/cpuidle-big_little.c:bl_powerdown_finisher
```
**Symbols:**

```
c03259c4-c0325a24: mcpm_set_entry_vector (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
