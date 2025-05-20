# Function: <code>of_find_compatible_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:495
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:519
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:639
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:665
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:670
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:679
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:698
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:698
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:698
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:700
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:707
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
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:722
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
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:722
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
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:590
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
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:588
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:600
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:599
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct device_node *of_find_compatible_node(struct device_node *from, const char *type, const char *compatible);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b69c48)
Location: drivers/of/base.c:1055
Inline: False
Direct callers:
  - arch/arm/xen/enlighten.c:xen_guest_init
  - drivers/bus/vexpress-config.c:vexpress_config_init
  - drivers/bus/vexpress-config.c:vexpress_config_init
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/clk/clk-qoriq.c:clockgen_init
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/soc/bcm/brcmstb/biuctrl.c:brcmstb_biuctrl_init
  - drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision
  - drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision
  - drivers/soc/imx/soc-imx8.c:imx8mq_soc_revision
  - drivers/soc/imx/soc-imx-scu.c:imx_scu_soc_init
  - drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_compatible
  - drivers/mfd/vexpress-sysreg.c:vexpress_flags_set
  - drivers/edac/altera_edac.c:socfpga_init_sdmmc_ecc
  - drivers/edac/altera_edac.c:ocram_alloc_mem
  - drivers/edac/altera_edac.c:altr_init_a10_ecc_device_type
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_firmware_probe
  - drivers/of/of_numa.c:of_numa_init
```
**Symbols:**

```
ffff800010b69c48-ffff800010b69da8: of_find_compatible_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device_node *of_find_compatible_node(struct device_node *from, const char *type, const char *compatible);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4d554)
Location: drivers/of/base.c:1055
Inline: False
Direct callers:
  - arch/arm/kernel/vdso.c:vdso_init
  - arch/arm/kernel/vdso.c:vdso_init
  - arch/arm/mach-actions/platsmp.c:s500_smp_prepare_cpus
  - arch/arm/mach-actions/platsmp.c:s500_smp_prepare_cpus
  - arch/arm/mach-actions/platsmp.c:s500_smp_prepare_cpus
  - arch/arm/mach-alpine/alpine_cpu_pm.c:alpine_cpu_pm_init
  - arch/arm/mach-aspeed/platsmp.c:aspeed_g6_smp_prepare_cpus
  - arch/arm/mach-berlin/platsmp.c:berlin_smp_prepare_cpus
  - arch/arm/mach-berlin/platsmp.c:berlin_smp_prepare_cpus
  - arch/arm/mach-exynos/exynos.c:exynos_sysram_init
  - arch/arm/mach-exynos/exynos.c:exynos_sysram_init
  - arch/arm/mach-exynos/exynos.c:exynos_sysram_init
  - arch/arm/mach-exynos/exynos.c:exynos_sysram_init
  - arch/arm/mach-exynos/firmware.c:exynos_secure_firmware_available
  - arch/arm/mach-exynos/platsmp.c:exynos_scu_enable
  - arch/arm/mach-exynos/mcpm-exynos.c:exynos_mcpm_init
  - arch/arm/mach-highbank/highbank.c:highbank_init
  - arch/arm/mach-highbank/highbank.c:highbank_init_irq
  - arch/arm/mach-hisi/platmcpm.c:hip04_smp_init
  - arch/arm/mach-hisi/platmcpm.c:hip04_smp_init
  - arch/arm/mach-hisi/platmcpm.c:hip04_smp_init
  - arch/arm/mach-hisi/platsmp.c:hip01_boot_secondary
  - arch/arm/mach-hisi/platsmp.c:hi3xxx_smp_prepare_cpus
  - arch/arm/mach-hisi/hotplug.c:hip01_set_cpu
  - arch/arm/mach-hisi/hotplug.c:hi3xxx_set_cpu
  - arch/arm/mach-meson/platsmp.c:meson_smp_prepare_cpus
  - arch/arm/mach-meson/platsmp.c:meson_smp_prepare_cpus
  - arch/arm/mach-mvebu/cpu-reset.c:mvebu_cpu_reset_init
  - arch/arm/mach-mvebu/cpu-reset.c:mvebu_cpu_reset_init
  - arch/arm/mach-mvebu/board-v7.c:mvebu_dt_init
  - arch/arm/mach-mvebu/board-v7.c:mvebu_dt_init
  - arch/arm/mach-mvebu/board-v7.c:mvebu_init_irq
  - arch/arm/mach-mvebu/coherency.c:coherency_init
  - arch/arm/mach-mvebu/coherency.c:coherency_init
  - arch/arm/mach-mvebu/coherency.c:coherency_init
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_cpu_pm_init
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_cpu_pm_init
  - arch/arm/mach-mvebu/pm.c:mvebu_pm_suspend_init
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_smp_prepare_cpus
  - arch/arm/mach-imx/cpu.c:imx_aips_allow_unprivileged_access
  - arch/arm/mach-imx/cpu.c:imx_aips_allow_unprivileged_access
  - arch/arm/mach-imx/system.c:imx_init_l2cache
  - arch/arm/mach-imx/cpu-imx5.c:imx5_pmu_init
  - arch/arm/mach-imx/cpu-imx5.c:imx5_pmu_init
  - arch/arm/mach-imx/cpu-imx5.c:imx5_read_srev_reg
  - arch/arm/mach-imx/anatop.c:imx_init_revision_from_anatop
  - arch/arm/mach-imx/anatop.c:imx_init_revision_from_anatop
  - arch/arm/mach-imx/gpc.c:imx_gpc_check_dt
  - arch/arm/mach-imx/src.c:imx_src_init
  - arch/arm/mach-imx/platsmp.c:ls1021a_smp_prepare_cpus
  - arch/arm/mach-imx/mach-imx6q.c:imx6q_init_machine
  - arch/arm/mach-imx/pm-imx7ulp.c:imx7ulp_pm_init
  - arch/arm/mach-imx/pm-imx6.c:imx6_pm_ccm_init
  - arch/arm/mach-imx/pm-imx6.c:imx6q_suspend_init
  - arch/arm/mach-imx/pm-imx6.c:imx6_pm_get_base
  - arch/arm/mach-imx/mach-imx51.c:imx51_dt_init
  - arch/arm/mach-npcm/platsmp.c:npcm7xx_smp_prepare_cpus
  - arch/arm/mach-npcm/platsmp.c:npcm7xx_smp_boot_secondary
  - arch/arm/mach-omap2/omap4-common.c:omap_gic_of_init
  - arch/arm/mach-omap2/omap4-common.c:omap_gic_of_init
  - arch/arm/mach-omap2/omap4-common.c:__omap4_sram_init
  - arch/arm/mach-rockchip/pm.c:rk3288_suspend_init
  - arch/arm/mach-rockchip/platsmp.c:rockchip_smp_prepare_cpus
  - arch/arm/mach-rockchip/platsmp.c:rockchip_smp_prepare_cpus
  - arch/arm/mach-rockchip/platsmp.c:rockchip_smp_prepare_cpus
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
  - arch/arm/mach-vexpress/dcscb.c:dcscb_init
  - arch/arm/mach-vexpress/tc2_pm.c:tc2_pm_init
  - drivers/bus/vexpress-config.c:vexpress_config_init
  - drivers/bus/vexpress-config.c:vexpress_config_init
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/clk/clk-highbank.c:hb_clk_init
  - drivers/clk/clk-qoriq.c:clockgen_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/mvebu/armada-370.c:a370_clk_init
  - drivers/clk/mvebu/armada-xp.c:axp_clk_init
  - drivers/clk/mvebu/mv98dx3236.c:mv98dx3236_clk_init
  - drivers/clk/mvebu/dove.c:dove_clk_init
  - drivers/clk/mvebu/dove.c:dove_clk_init
  - drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_clk_probe
  - drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_clk_probe
  - drivers/clk/ti/clk.c:ti_dt_clocks_register
  - drivers/soc/dove/pmu.c:dove_init_pmu
  - drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision
  - drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision
  - drivers/soc/imx/soc-imx8.c:imx8mq_soc_revision
  - drivers/soc/imx/soc-imx-scu.c:imx_scu_soc_init
  - drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init
  - drivers/soc/renesas/rmobile-sysc.c:rmobile_init_pm_domains
  - drivers/soc/renesas/rmobile-sysc.c:rmobile_init_pm_domains
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_compatible
  - drivers/mfd/vexpress-sysreg.c:vexpress_flags_set
  - drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init
  - drivers/firmware/trusted_foundations.c:of_register_trusted_foundations
```
**Symbols:**

```
c0c4d554-c0c4d63c: of_find_compatible_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device_node *of_find_compatible_node(struct device_node *from, const char *type, const char *compatible);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c42f90)
Location: drivers/of/base.c:1055
Inline: False
Direct callers:
  - arch/powerpc/kernel/setup-common.c:check_legacy_ioport
  - arch/powerpc/kernel/setup-common.c:check_legacy_ioport
  - arch/powerpc/kernel/setup-common.c:add_pcspkr
  - arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports
  - arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports
  - arch/powerpc/kernel/pci_64.c:__se_sys_pciconfig_iobase
  - arch/powerpc/kernel/secvar-sysfs.c:secvar_sysfs_init
  - arch/powerpc/kernel/secvar-sysfs.c:format_show
  - arch/powerpc/sysdev/xics/xics-common.c:xics_init
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_init
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_init
  - arch/powerpc/sysdev/xics/icp-hv.c:icp_hv_init
  - arch/powerpc/sysdev/xics/icp-opal.c:icp_opal_init
  - arch/powerpc/sysdev/xive/native.c:xive_native_init
  - arch/powerpc/sysdev/xive/spapr.c:xive_spapr_init
  - arch/powerpc/platforms/powernv/opal.c:opal_init
  - arch/powerpc/platforms/powernv/opal.c:opal_pdev_init
  - arch/powerpc/platforms/powernv/opal.c:opal_pdev_init
  - arch/powerpc/platforms/powernv/opal-nvram.c:opal_nvram_init
  - arch/powerpc/platforms/powernv/opal-lpc.c:opal_lpc_init
  - arch/powerpc/platforms/powernv/opal-lpc.c:opal_lpc_init
  - arch/powerpc/platforms/powernv/rng.c:__machine_initcall_powernv_rng_init
  - arch/powerpc/platforms/powernv/rng.c:__machine_initcall_powernv_rng_init
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_init
  - arch/powerpc/platforms/powernv/opal-powercap.c:opal_powercap_init
  - arch/powerpc/platforms/powernv/opal-psr.c:opal_psr_init
  - arch/powerpc/platforms/powernv/opal-sensor-groups.c:opal_sensor_groups_init
  - arch/powerpc/platforms/powernv/ultravisor.c:__machine_initcall_powernv_uv_init
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_init
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_init
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_init
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_init
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_init
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_init
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_init
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_init
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_init
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_init
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_init
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_init
  - arch/powerpc/platforms/powernv/opal-imc.c:opal_imc_counters_probe
  - arch/powerpc/platforms/powernv/opal-imc.c:opal_imc_counters_probe
  - arch/powerpc/platforms/powernv/opal-imc.c:get_max_nest_dev
  - arch/powerpc/platforms/powernv/opal-imc.c:get_max_nest_dev
  - arch/powerpc/platforms/powernv/vas.c:vas_init
  - arch/powerpc/platforms/powernv/vas.c:vas_init
  - arch/powerpc/platforms/pseries/rng.c:__machine_initcall_pseries_rng_init
  - security/integrity/platform_certs/load_powerpc.c:load_powerpc_certs
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/tty/hvc/hvsi.c:hvsi_console_init
  - drivers/tty/hvc/hvsi.c:hvsi_console_init
  - drivers/misc/cxl/base.c:cxl_base_init
  - drivers/misc/cxl/base.c:cxl_base_init
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_compatible
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_ppc_of_remove
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_ppc_of_probe
```
**Symbols:**

```
c000000000c42f90-c000000000c430f4: of_find_compatible_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device_node *of_find_compatible_node(struct device_node *from, const char *type, const char *compatible);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe00071f74c)
Location: drivers/of/base.c:1055
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_compatible
```
**Symbols:**

```
ffffffe00071f74c-ffffffe00071f81e: of_find_compatible_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:698
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:698
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:698
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:698
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
