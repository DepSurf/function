# Function: <code>of_find_matching_node_and_match</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (0)
Location: include/linux/of.h:604
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
In arch/x86/kernel/x86_init.c (0)
Location: include/linux/of.h:606
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
In arch/x86/kernel/x86_init.c (0)
Location: include/linux/of.h:621
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
In arch/x86/kernel/x86_init.c (0)
Location: include/linux/of.h:621
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
In arch/x86/kernel/x86_init.c (0)
Location: include/linux/of.h:489
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
In arch/x86/kernel/x86_init.c (0)
Location: include/linux/of.h:487
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
In arch/x86/kernel/x86_init.c (0)
Location: include/linux/of.h:499
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
In arch/x86/kernel/x86_init.c (0)
Location: include/linux/of.h:498
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
struct device_node *of_find_matching_node_and_match(struct device_node *from, const struct of_device_id *matches, const struct of_device_id **match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b69ed0)
Location: drivers/of/base.c:1162
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_init
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_init
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_init
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_init
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_init
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_init
  - drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c:its_fsl_mc_msi_init
  - drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c:its_fsl_mc_msi_init
  - drivers/clk/clk.c:of_clk_init
  - drivers/clk/clk.c:of_clk_init
  - drivers/soc/bcm/brcmstb/common.c:brcmstb_soc_device_init
  - drivers/soc/bcm/brcmstb/common.c:brcmstb_soc_device_early_init
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
  - drivers/soc/renesas/rcar-rst.c:rcar_rst_read_mode_pins
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init
  - drivers/soc/rockchip/grf.c:rockchip_grf_init
  - drivers/reset/reset-sunxi.c:sun6i_reset_init
  - drivers/reset/reset-sunxi.c:sun6i_reset_init
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_init
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_init
  - drivers/net/ethernet/freescale/fman/fman.c:read_dts_node
  - drivers/firmware/arm_sdei.c:sdei_init
  - drivers/firmware/psci/psci.c:psci_dt_init
  - drivers/clocksource/timer-probe.c:timer_probe
  - drivers/clocksource/timer-probe.c:timer_probe
  - drivers/clocksource/arm_arch_timer.c:arch_timer_needs_of_probing
  - drivers/of/platform.c:of_platform_default_populate_init
  - drivers/of/platform.c:of_platform_default_populate_init
  - drivers/of/address.c:of_find_matching_node_by_address
  - drivers/of/address.c:of_find_matching_node_by_address
  - drivers/of/irq.c:of_irq_init
  - drivers/of/irq.c:of_irq_init
```
**Symbols:**

```
ffff800010b69ed0-ffff800010b6a02c: of_find_matching_node_and_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device_node *of_find_matching_node_and_match(struct device_node *from, const struct of_device_id *matches, const struct of_device_id **match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4daa4)
Location: drivers/of/base.c:1162
Inline: False
Direct callers:
  - arch/arm/mm/cache-feroceon-l2.c:feroceon_of_init
  - arch/arm/mm/cache-l2x0.c:l2x0_of_init
  - arch/arm/mm/cache-tauros2.c:tauros2_init
  - arch/arm/mm/cache-uniphier.c:uniphier_cache_init
  - arch/arm/mach-exynos/exynos.c:exynos_init_irq
  - arch/arm/mach-exynos/suspend.c:exynos_pm_init
  - arch/arm/mach-exynos/mcpm-exynos.c:exynos_mcpm_init
  - arch/arm/mach-mvebu/system-controller.c:mvebu_system_controller_init
  - arch/arm/mach-mvebu/mvebu-soc-id.c:mvebu_soc_id_init
  - arch/arm/mach-mvebu/coherency.c:coherency_init
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_cpu_pm_init
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_init
  - arch/arm/mach-mvebu/platsmp.c:mv98dx3236_boot_secondary
  - arch/arm/mach-omap2/control.c:omap_control_init
  - arch/arm/mach-omap2/control.c:omap_control_init
  - arch/arm/mach-omap2/control.c:omap2_control_base_init
  - arch/arm/mach-omap2/control.c:omap2_control_base_init
  - arch/arm/mach-omap2/timer.c:omap_get_timer_dt
  - arch/arm/mach-omap2/timer.c:omap_get_timer_dt
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init
  - arch/arm/mach-omap2/omap4-common.c:omap_gic_of_init
  - arch/arm/mach-omap2/prm_common.c:omap_prcm_init
  - arch/arm/mach-omap2/prm_common.c:omap_prcm_init
  - arch/arm/mach-omap2/prm_common.c:omap2_prm_base_init
  - arch/arm/mach-omap2/prm_common.c:omap2_prm_base_init
  - arch/arm/mach-omap2/cm_common.c:omap_cm_init
  - arch/arm/mach-omap2/cm_common.c:omap_cm_init
  - arch/arm/mach-omap2/cm_common.c:omap2_cm_base_init
  - arch/arm/mach-omap2/cm_common.c:omap2_cm_base_init
  - arch/arm/mach-rockchip/pm.c:rockchip_suspend_init
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init
  - arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk
  - arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk
  - arch/arm/mach-tegra/irq.c:tegra_init_irq
  - arch/arm/mach-tegra/irq.c:tegra_init_irq
  - arch/arm/mach-vexpress/platsmp.c:vexpress_smp_dt_prepare_cpus
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_of_init
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_of_init
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_init
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_init
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_init
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_init
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_dt_init
  - drivers/video/fbdev/omap2/omapfb/dss/omapdss-boot-init.c:omapdss_boot_init
  - drivers/clk/clk.c:of_clk_init
  - drivers/clk/clk.c:of_clk_init
  - drivers/clk/renesas/clk-emev2.c:emev2_smu_init
  - drivers/clk/samsung/clk.c:samsung_clk_of_register_fixed_ext
  - drivers/clk/samsung/clk.c:samsung_clk_of_register_fixed_ext
  - drivers/clk/tegra/clk-tegra20.c:tegra20_clock_init
  - drivers/clk/tegra/clk-tegra30.c:tegra30_clock_init
  - drivers/clk/tegra/clk-tegra114.c:tegra114_clock_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_132_clock_init_pre
  - drivers/clk/ti/clk.c:ti_clk_add_aliases
  - drivers/clk/ti/clk.c:ti_clk_add_aliases
  - drivers/clk/ti/clockdomain.c:ti_dt_clockdomains_setup
  - drivers/clk/ti/clockdomain.c:ti_dt_clockdomains_setup
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
  - drivers/soc/renesas/rcar-rst.c:rcar_rst_read_mode_pins
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init
  - drivers/soc/renesas/rmobile-sysc.c:rmobile_init_pm_domains
  - drivers/soc/renesas/rmobile-sysc.c:rmobile_init_pm_domains
  - drivers/soc/rockchip/grf.c:rockchip_grf_init
  - drivers/soc/samsung/exynos-pmu.c:exynos_get_pmu_regmap
  - drivers/soc/samsung/pm_domains.c:exynos4_pm_init_power_domain
  - drivers/soc/samsung/pm_domains.c:exynos4_pm_init_power_domain
  - drivers/soc/samsung/pm_domains.c:exynos4_pm_init_power_domain
  - drivers/soc/samsung/pm_domains.c:exynos4_pm_init_power_domain
  - drivers/soc/tegra/fuse/fuse-tegra.c:tegra_init_fuse
  - drivers/soc/tegra/fuse/fuse-tegra.c:tegra_init_fuse
  - drivers/soc/tegra/fuse/tegra-apbmisc.c:tegra_init_apbmisc
  - drivers/soc/tegra/flowctrl.c:tegra_flowctrl_init
  - drivers/soc/tegra/pmc.c:tegra_pmc_early_init
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_init
  - drivers/iommu/omap-iommu.c:omap_iommu_init
  - drivers/iommu/tegra-smmu.c:tegra_smmu_probe
  - drivers/iommu/exynos-iommu.c:exynos_iommu_init
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_init
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_init
  - drivers/power/reset/arm-versatile-reboot.c:versatile_reboot_probe
  - drivers/firmware/psci/psci.c:psci_dt_init
  - drivers/clocksource/timer-probe.c:timer_probe
  - drivers/clocksource/timer-probe.c:timer_probe
  - drivers/clocksource/dw_apb_timer_of.c:dw_apb_timer_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_needs_of_probing
  - drivers/of/platform.c:of_platform_default_populate_init
  - drivers/of/platform.c:of_platform_default_populate_init
  - drivers/of/address.c:of_find_matching_node_by_address
  - drivers/of/address.c:of_find_matching_node_by_address
  - drivers/of/irq.c:of_irq_init
  - drivers/of/irq.c:of_irq_init
```
**Symbols:**

```
c0c4daa4-c0c4db90: of_find_matching_node_and_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device_node *of_find_matching_node_and_match(struct device_node *from, const struct of_device_id *matches, const struct of_device_id **match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c43940)
Location: drivers/of/base.c:1162
Inline: False
Direct callers:
  - arch/powerpc/kernel/secure_boot.c:is_ppc_trustedboot_enabled
  - arch/powerpc/kernel/secure_boot.c:is_ppc_secureboot_enabled
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
  - drivers/of/address.c:of_find_matching_node_by_address
  - drivers/of/address.c:of_find_matching_node_by_address
  - drivers/of/irq.c:of_irq_init
  - drivers/of/irq.c:of_irq_init
```
**Symbols:**

```
c000000000c43940-c000000000c43ae0: of_find_matching_node_and_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device_node *of_find_matching_node_and_match(struct device_node *from, const struct of_device_id *matches, const struct of_device_id **match);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe00071fc6c)
Location: drivers/of/base.c:1162
Inline: False
Direct callers:
  - arch/riscv/mm/sifive_l2_cache.c:sifive_l2_init
  - drivers/clk/clk.c:of_clk_init
  - drivers/clk/clk.c:of_clk_init
  - drivers/clocksource/timer-probe.c:timer_probe
  - drivers/clocksource/timer-probe.c:timer_probe
  - drivers/of/platform.c:of_platform_default_populate_init
  - drivers/of/platform.c:of_platform_default_populate_init
  - drivers/of/address.c:of_find_matching_node_by_address
  - drivers/of/irq.c:of_irq_init
  - drivers/of/irq.c:of_irq_init
```
**Symbols:**

```
ffffffe00071fc6c-ffffffe00071fd44: of_find_matching_node_and_match (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
