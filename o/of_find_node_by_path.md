# Function: <code>of_find_node_by_path</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: include/linux/of.h:614
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: include/linux/of.h:629
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: include/linux/of.h:629
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: include/linux/of.h:497
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: include/linux/of.h:495
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (0)
Location: include/linux/of.h:507
Inline: True
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/of.h:507
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (0)
Location: include/linux/of.h:506
Inline: True
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/of.h:506
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/imx/clk.c (ffff800011485848)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/clk/imx/clk.c:imx_obtain_fixed_clock_from_dt
```
```
In drivers/soc/bcm/brcmstb/common.c (ffff80001080f43c)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/soc/bcm/brcmstb/common.c:soc_is_brcmstb
```
```
In drivers/soc/fsl/guts.c (ffff800010817ccc)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/soc/fsl/guts.c:fsl_guts_probe
```
```
In drivers/soc/amlogic/meson-gx-socinfo.c (ffff800011490434)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init
```
```
In drivers/soc/amlogic/meson-mx-socinfo.c (ffff8000114906cc)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
```
```
In drivers/soc/renesas/renesas-soc.c (ffff800011490de4)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
```
```
In drivers/tty/sysrq.c (ffff800010864cc4)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_toggle_support
```
```
In drivers/base/arch_topology.c (ffff800011498544)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:init_cpu_topology
```
```
In drivers/cpufreq/cpufreq-dt-platdev.c (ffff8000114a1eb0)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init
```
```
In drivers/of/base.c (ffff800010b6c0cc)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/of/base.c:of_alias_scan
  - drivers/of/base.c:of_alias_scan
  - drivers/of/base.c:of_alias_scan
  - drivers/of/base.c:of_alias_scan
  - drivers/of/base.c:of_find_node_opts_by_path
  - drivers/of/base.c:of_get_next_cpu_node
  - drivers/of/base.c:of_machine_is_compatible
```
```
In drivers/of/platform.c (ffff8000114aa3d8)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_default_populate_init
  - drivers/of/platform.c:of_platform_populate
  - drivers/of/platform.c:of_platform_bus_probe
```
```
In drivers/of/resolver.c (ffff800010b76d8c)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:of_resolve_phandles
```
```
In drivers/of/overlay.c (ffff800010b77b10)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/of/overlay.c:init_overlay_changeset
  - drivers/of/overlay.c:init_overlay_changeset
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/setup.c (c1503c54)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:init_machine_late
```
```
In arch/arm/kernel/devtree.c (c15061bc)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/arm/kernel/devtree.c:arm_dt_init_cpu_maps
```
```
In arch/arm/mach-imx/cpu.c (c150e714)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/arm/mach-imx/cpu.c:imx_soc_device_init
```
```
In arch/arm/mach-omap2/omap_hwmod.c (c1514390)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_hwmod.c:__omap_hwmod_setup_all
  - arch/arm/mach-omap2/omap_hwmod.c:__omap_hwmod_setup_all
```
```
In arch/arm/mach-rockchip/platsmp.c (c1519350)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/arm/mach-rockchip/platsmp.c:rockchip_smp_prepare_cpus
```
```
In drivers/bus/ti-sysc.c (c08281a0)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_map_and_check_registers
  - drivers/bus/ti-sysc.c:sysc_map_and_check_registers
```
```
In drivers/clk/imx/clk.c (c1557ddc)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/clk/imx/clk.c:imx_obtain_fixed_clock_from_dt
```
```
In drivers/soc/fsl/guts.c (c0933fd4)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/soc/fsl/guts.c:fsl_guts_probe
```
```
In drivers/soc/amlogic/meson-gx-socinfo.c (c158ff84)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init
```
```
In drivers/soc/amlogic/meson-mx-socinfo.c (c1590248)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
```
```
In drivers/soc/renesas/renesas-soc.c (c15907f0)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
```
```
In drivers/soc/samsung/exynos-chipid.c (c15917c4)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/soc/samsung/exynos-chipid.c:exynos_chipid_early_init
```
```
In drivers/soc/tegra/common.c (c093aa98)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/soc/tegra/common.c:soc_is_tegra
```
```
In drivers/tty/sysrq.c (c096a5b0)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_toggle_support
```
```
In drivers/cpufreq/cpufreq-dt-platdev.c (c15a3ed8)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init
```
```
In drivers/cpufreq/ti-cpufreq.c (c0c01054)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/cpufreq/ti-cpufreq.c:ti_cpufreq_init
```
```
In drivers/cpuidle/cpuidle-big_little.c (c15a4660)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-big_little.c:bl_idle_init
```
```
In drivers/of/base.c (c0c4f2dc)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/of/base.c:of_alias_scan
  - drivers/of/base.c:of_alias_scan
  - drivers/of/base.c:of_alias_scan
  - drivers/of/base.c:of_alias_scan
  - drivers/of/base.c:of_find_node_opts_by_path
  - drivers/of/base.c:of_get_next_cpu_node
  - drivers/of/base.c:of_machine_is_compatible
```
```
In drivers/of/platform.c (c15ae8f4)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_default_populate_init
  - drivers/of/platform.c:of_platform_populate
  - drivers/of/platform.c:of_platform_bus_probe
```
```
In drivers/of/resolver.c (c0c59020)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:of_resolve_phandles
```
```
In drivers/of/overlay.c (c0c59ac8)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/of/overlay.c:init_overlay_changeset
  - drivers/of/overlay.c:init_overlay_changeset
```
```
In sound/soc/fsl/fsl_ssi.c (c0cc0978)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/setup-common.c (c00000000134a3c8)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
  - arch/powerpc/kernel/setup-common.c:show_cpuinfo
```
```
In arch/powerpc/kernel/setup_64.c (c00000000134b0ec)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup_64.c:check_smt_enabled
```
```
In arch/powerpc/kernel/proc_powerpc.c (c00000000134d120)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/kernel/proc_powerpc.c:proc_ppc64_create
```
```
In arch/powerpc/kernel/rtas.c (c00000000003e12c)
Location: include/linux/of.h:280
Inline: True
```
```
In arch/powerpc/kernel/fadump.c (c00000000004d804)
Location: include/linux/of.h:280
Inline: True
```
```
In arch/powerpc/kernel/legacy_serial.c (c000000001350ee0)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/kernel/legacy_serial.c:check_legacy_serial_console
  - arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports
```
```
In arch/powerpc/kernel/machine_kexec.c (c000000001352aec)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/kernel/machine_kexec.c:kexec_setup
```
```
In arch/powerpc/kernel/machine_kexec_64.c (c000000001352f64)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/kernel/machine_kexec_64.c:export_htab_values
```
```
In arch/powerpc/kernel/ima_kexec.c (c000000000072668)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/kernel/ima_kexec.c:get_addr_size_cells
```
```
In arch/powerpc/kernel/kvm.c (c000000000075208)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/kernel/kvm.c:kvm_para_available
```
```
In arch/powerpc/mm/drmem.c (c000000001354958)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/mm/drmem.c:drmem_init
  - arch/powerpc/mm/drmem.c:drmem_update_dt
```
```
In arch/powerpc/mm/numa.c (c0000000000a2f60)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:memory_hotplug_max
  - arch/powerpc/mm/numa.c:memory_hotplug_max
  - arch/powerpc/mm/numa.c:hot_add_scn_to_nid
  - arch/powerpc/mm/numa.c:mem_topology_setup
  - arch/powerpc/mm/numa.c:parse_numa_properties
  - arch/powerpc/mm/numa.c:parse_numa_properties
  - arch/powerpc/mm/numa.c:parse_numa_properties
  - arch/powerpc/mm/numa.c:parse_numa_properties
```
```
In arch/powerpc/sysdev/xive/spapr.c (c00000000135a33c)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/spapr.c:xive_spapr_init
```
```
In arch/powerpc/platforms/powernv/setup.c (c0000000000c19b4)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/setup.c:pnv_show_cpuinfo
```
```
In arch/powerpc/platforms/powernv/opal.c (c00000000135ad7c)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal.c:opal_init
  - arch/powerpc/platforms/powernv/opal.c:opal_init
  - arch/powerpc/platforms/powernv/opal.c:opal_init
  - arch/powerpc/platforms/powernv/opal.c:opal_init
  - arch/powerpc/platforms/powernv/opal.c:opal_init
```
```
In arch/powerpc/platforms/powernv/opal-async.c (c00000000135ba10)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-async.c:opal_async_comp_init
```
```
In arch/powerpc/platforms/powernv/idle.c (c0000000000c884c)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/idle.c:pnv_parse_cpuidle_dt
```
```
In arch/powerpc/platforms/powernv/opal-rtc.c (c00000000135c2f8)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-rtc.c:__machine_initcall_powernv_opal_time_init
```
```
In arch/powerpc/platforms/powernv/opal-sysparam.c (c00000000135d1b4)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-sysparam.c:opal_sys_param_init
```
```
In arch/powerpc/platforms/powernv/opal-sensor.c (c00000000135d628)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-sensor.c:opal_sensor_init
```
```
In arch/powerpc/platforms/powernv/opal-power.c (c00000000135d8bc)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-power.c:opal_power_control_init
```
```
In arch/powerpc/platforms/powernv/opal-irqchip.c (c00000000135da48)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_init
```
```
In arch/powerpc/platforms/pseries/reconfig.c (c0000000000ecbe0)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/reconfig.c:ofdt_write
  - arch/powerpc/platforms/pseries/reconfig.c:ofdt_write
```
```
In arch/powerpc/platforms/pseries/of_helpers.c (c0000000000ed7ac)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/of_helpers.c:pseries_of_derive_parent
```
```
In arch/powerpc/platforms/pseries/setup.c (c0000000013624c4)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch
  - arch/powerpc/platforms/pseries/setup.c:pSeries_show_cpuinfo
```
```
In arch/powerpc/platforms/pseries/ras.c (c000000001362bf0)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/ras.c:__machine_initcall_pseries_init_ras_IRQ
  - arch/powerpc/platforms/pseries/ras.c:__machine_initcall_pseries_init_ras_IRQ
  - arch/powerpc/platforms/pseries/ras.c:init_ras_hotplug_IRQ
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000f9308)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_release
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_add
```
```
In arch/powerpc/platforms/pseries/hotplug-memory.c (c0000000000fad44)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_memory_block_size
  - arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_memory_block_size
  - arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_memory_block_size
```
```
In arch/powerpc/platforms/pseries/io_event_irq.c (c00000000136407c)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/io_event_irq.c:__machine_initcall_pseries_ioei_init
```
```
In arch/powerpc/platforms/pseries/lparcfg.c (c0000000000feee4)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lparcfg.c:lparcfg_data
```
```
In drivers/soc/fsl/guts.c (c0000000008ca0a4)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/soc/fsl/guts.c:fsl_guts_probe
```
```
In drivers/tty/sysrq.c (c000000000903f34)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_toggle_support
```
```
In drivers/tty/hvc/hvc_opal.c (c0000000013a6524)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_opal.c:hvc_opal_init_early
  - drivers/tty/hvc/hvc_opal.c:hvc_opal_init_early
```
```
In drivers/cpufreq/powernv-cpufreq.c (c000000000c1cf8c)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/cpufreq/powernv-cpufreq.c:init_powernv_pstates
```
```
In drivers/cpuidle/governors/haltpoll.c (c0000000013b8be0)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/cpuidle/governors/haltpoll.c:init_haltpoll
```
```
In drivers/of/base.c (c000000000c464d8)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/of/base.c:of_alias_scan
  - drivers/of/base.c:of_alias_scan
  - drivers/of/base.c:of_alias_scan
  - drivers/of/base.c:of_alias_scan
  - drivers/of/base.c:of_find_node_opts_by_path
  - drivers/of/base.c:of_get_next_cpu_node
  - drivers/of/base.c:of_machine_is_compatible
```
```
In drivers/of/platform.c (c000000000c48750)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_populate
  - drivers/of/platform.c:of_platform_bus_probe
```
```
In drivers/of/resolver.c (c000000000c556dc)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:of_resolve_phandles
```
```
In drivers/of/overlay.c (c000000000c5688c)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/of/overlay.c:init_overlay_changeset
  - drivers/of/overlay.c:init_overlay_changeset
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/time.c (ffffffe00000325e)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - arch/riscv/kernel/time.c:time_init
```
```
In drivers/tty/sysrq.c (ffffffe00053b290)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_toggle_support
```
```
In drivers/base/arch_topology.c (ffffffe000031c7c)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:init_cpu_topology
```
```
In drivers/of/base.c (ffffffe000721326)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/of/base.c:of_alias_scan
  - drivers/of/base.c:of_alias_scan
  - drivers/of/base.c:of_alias_scan
  - drivers/of/base.c:of_alias_scan
  - drivers/of/base.c:of_find_node_opts_by_path
  - drivers/of/base.c:of_get_next_cpu_node
  - drivers/of/base.c:of_machine_is_compatible
```
```
In drivers/of/platform.c (ffffffe00003a7ae)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_default_populate_init
  - drivers/of/platform.c:of_platform_populate
  - drivers/of/platform.c:of_platform_bus_probe
```
```
In drivers/of/resolver.c (ffffffe00072a0ac)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:of_resolve_phandles
```
```
In drivers/of/overlay.c (ffffffe00072b0dc)
Location: include/linux/of.h:280
Inline: True
Inline callers:
  - drivers/of/overlay.c:init_overlay_changeset
  - drivers/of/overlay.c:init_overlay_changeset
```
</details>
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
