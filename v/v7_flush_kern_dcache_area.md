# Function: <code>v7_flush_kern_dcache_area</code>

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
<summary>In <code>armhf</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:hyp_mode_check
  - arch/arm/kernel/setup.c:hyp_mode_check
  - arch/arm/kernel/suspend.c:cpu_suspend_alloc_sp
  - arch/arm/kernel/suspend.c:__cpu_suspend_save
  - arch/arm/kernel/suspend.c:__cpu_suspend_save
  - arch/arm/kernel/smp.c:__cpu_up
  - arch/arm/mm/flush.c:__flush_anon_page
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_set_early_poke
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
  - arch/arm/mach-exynos/platsmp.c:exynos_boot_secondary
  - arch/arm/mach-exynos/platsmp.c:exynos_secondary_init
  - arch/arm/mach-hisi/platmcpm.c:hip04_smp_init
  - arch/arm/mach-mvebu/coherency.c:coherency_init
  - arch/arm/mach-imx/platsmp.c:imx_smp_prepare_cpus
  - arch/arm/mach-vexpress/spc.c:__sync_cache_range_w
  - arch/arm/plat-versatile/platsmp.c:versatile_boot_secondary
  - arch/arm/plat-versatile/platsmp.c:versatile_secondary_init
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_table_entry
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_table_entry
  - drivers/irqchip/irq-gic-v3-its.c:its_allocate_pending_table
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables
  - drivers/irqchip/irq-gic-v3-its.c:gic_reset_prop_table
  - drivers/irqchip/irq-gic-v3-its.c:lpi_write_config
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_vcommand
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_vcommand
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_command
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_command
  - drivers/bus/arm-cci.c:__sync_cache_range_w
```
**Symbols:**

```
c0321fec-c0322028: v7_flush_kern_dcache_area (STB_GLOBAL)
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
