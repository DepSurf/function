# Function: <code>outer_clean_range</code>

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
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/setup.c (c1504e40)
Location: arch/arm/include/asm/outercache.h:51
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:setup_arch
```
```
In arch/arm/kernel/suspend.c (c0311af8)
Location: arch/arm/include/asm/outercache.h:51
Inline: True
Inline callers:
  - arch/arm/kernel/suspend.c:cpu_suspend_alloc_sp
  - arch/arm/kernel/suspend.c:__cpu_suspend_save
  - arch/arm/kernel/suspend.c:__cpu_suspend_save
```
```
In arch/arm/kernel/smp.c (c031265c)
Location: arch/arm/include/asm/outercache.h:51
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:__cpu_up
```
```
In arch/arm/mm/dma-mapping.c (c031af8c)
Location: arch/arm/include/asm/outercache.h:51
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:__dma_page_cpu_to_dev
```
```
In arch/arm/common/mcpm_entry.c (c0325c74)
Location: arch/arm/include/asm/outercache.h:51
Inline: True
Inline callers:
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_set_early_poke
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
```
```
In arch/arm/mach-exynos/platsmp.c (c032e6d8)
Location: arch/arm/include/asm/outercache.h:51
Inline: True
Inline callers:
  - arch/arm/mach-exynos/platsmp.c:exynos_boot_secondary
  - arch/arm/mach-exynos/platsmp.c:exynos_secondary_init
```
```
In arch/arm/mach-hisi/platmcpm.c (c150cea8)
Location: arch/arm/include/asm/outercache.h:51
Inline: True
Inline callers:
  - arch/arm/mach-hisi/platmcpm.c:hip04_smp_init
```
```
In arch/arm/mach-mvebu/coherency.c (c150db88)
Location: arch/arm/include/asm/outercache.h:51
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/coherency.c:coherency_init
```
```
In arch/arm/mach-imx/platsmp.c (c150f4fc)
Location: arch/arm/include/asm/outercache.h:51
Inline: True
Inline callers:
  - arch/arm/mach-imx/platsmp.c:imx_smp_prepare_cpus
```
```
In arch/arm/mach-omap2/omap-secure.c (c033b938)
Location: arch/arm/include/asm/outercache.h:51
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-secure.c:rx51_secure_dispatcher
  - arch/arm/mach-omap2/omap-secure.c:omap_secure_dispatcher
```
```
In arch/arm/mach-rockchip/platsmp.c (c1519528)
Location: arch/arm/include/asm/outercache.h:51
Inline: True
Inline callers:
  - arch/arm/mach-rockchip/platsmp.c:rockchip_smp_prepare_cpus
```
```
In arch/arm/mach-vexpress/spc.c (c034d44c)
Location: arch/arm/include/asm/outercache.h:51
Inline: True
Inline callers:
  - arch/arm/mach-vexpress/spc.c:__sync_cache_range_w
```
```
In arch/arm/plat-versatile/platsmp.c (c034faf8)
Location: arch/arm/include/asm/outercache.h:51
Inline: True
Inline callers:
  - arch/arm/plat-versatile/platsmp.c:versatile_boot_secondary
  - arch/arm/plat-versatile/platsmp.c:versatile_secondary_init
```
```
In drivers/bus/arm-cci.c (c08235bc)
Location: arch/arm/include/asm/outercache.h:51
Inline: True
Inline callers:
  - drivers/bus/arm-cci.c:__sync_cache_range_w
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
