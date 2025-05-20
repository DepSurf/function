# Function: <code>__sync_cache_range_w</code>

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
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __sync_cache_range_w(volatile void *p, size_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/setup.c (c1504e18)
Location: arch/arm/include/asm/cacheflush.h:392
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:setup_arch
```
```
In arch/arm/kernel/suspend.c (c0311ad8)
Location: arch/arm/include/asm/cacheflush.h:392
Inline: True
Inline callers:
  - arch/arm/kernel/suspend.c:cpu_suspend_alloc_sp
```
```
In arch/arm/kernel/smp.c (c031263c)
Location: arch/arm/include/asm/cacheflush.h:392
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:__cpu_up
```
```
In arch/arm/common/mcpm_entry.c (c0325c60)
Location: arch/arm/include/asm/cacheflush.h:392
Inline: True
Inline callers:
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_set_early_poke
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
Direct callers:
  - arch/arm/common/mcpm_entry.c:nocache_trampoline
  - arch/arm/common/mcpm_entry.c:nocache_trampoline
  - arch/arm/common/mcpm_entry.c:nocache_trampoline
  - arch/arm/common/mcpm_entry.c:nocache_trampoline
  - arch/arm/common/mcpm_entry.c:mcpm_sync_init
  - arch/arm/common/mcpm_entry.c:mcpm_sync_init
```
```
In arch/arm/mach-exynos/platsmp.c (c032e6b4)
Location: arch/arm/include/asm/cacheflush.h:392
Inline: True
Inline callers:
  - arch/arm/mach-exynos/platsmp.c:exynos_boot_secondary
  - arch/arm/mach-exynos/platsmp.c:exynos_secondary_init
```
```
In arch/arm/mach-hisi/platmcpm.c (c150ce88)
Location: arch/arm/include/asm/cacheflush.h:392
Inline: True
Inline callers:
  - arch/arm/mach-hisi/platmcpm.c:hip04_smp_init
```
```
In arch/arm/mach-mvebu/coherency.c (c150db68)
Location: arch/arm/include/asm/cacheflush.h:392
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/coherency.c:coherency_init
```
```
In arch/arm/mach-imx/platsmp.c (c150f4dc)
Location: arch/arm/include/asm/cacheflush.h:392
Inline: True
Inline callers:
  - arch/arm/mach-imx/platsmp.c:imx_smp_prepare_cpus
```
```
In arch/arm/mach-vexpress/spc.c (c034d41c)
Location: arch/arm/include/asm/cacheflush.h:392
Inline: False
Direct callers:
  - arch/arm/mach-vexpress/spc.c:ve_spc_init
  - arch/arm/mach-vexpress/spc.c:ve_spc_init
```
```
In arch/arm/plat-versatile/platsmp.c (c034fad4)
Location: arch/arm/include/asm/cacheflush.h:392
Inline: True
Inline callers:
  - arch/arm/plat-versatile/platsmp.c:versatile_boot_secondary
  - arch/arm/plat-versatile/platsmp.c:versatile_secondary_init
```
```
In drivers/bus/arm-cci.c (c082358c)
Location: arch/arm/include/asm/cacheflush.h:392
Inline: False
Direct callers:
  - drivers/bus/arm-cci.c:cci_probe_ports
  - drivers/bus/arm-cci.c:cci_probe_ports
  - drivers/bus/arm-cci.c:cci_probe_ports
  - drivers/bus/arm-cci.c:cci_probe_ports
  - drivers/bus/arm-cci.c:cci_probe_ports
```
**Symbols:**

```
c0325764-c03257a4: __sync_cache_range_w (STB_LOCAL)
c034d41c-c034d45c: __sync_cache_range_w (STB_LOCAL)
c082358c-c08235cc: __sync_cache_range_w (STB_LOCAL)
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
