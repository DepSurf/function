# Function: <code>of_find_matching_node</code>

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
Location: include/linux/of.h:1023
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
Location: include/linux/of.h:1040
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
Location: include/linux/of.h:1055
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
Location: include/linux/of.h:1060
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
Location: include/linux/of.h:882
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
Location: include/linux/of.h:881
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
Location: include/linux/of.h:914
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
Location: include/linux/of.h:913
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
In drivers/irqchip/irq-gic-v2m.c (ffff80001147235c)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_init
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_init
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800011474624)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_init
```
```
In drivers/irqchip/irq-gic-v3-its-platform-msi.c (ffff800011474ce8)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_init
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_init
```
```
In drivers/irqchip/irq-gic-v3-its-pci-msi.c (ffff800011474ef0)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_init
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_init
```
```
In drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c (ffff80001147505c)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c:its_fsl_mc_msi_init
  - drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c:its_fsl_mc_msi_init
```
```
In drivers/bus/arm-cci.c (ffff80001067ee50)
Location: include/linux/of.h:1015
Inline: True
```
```
In drivers/soc/bcm/brcmstb/common.c (ffff80001148f880)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/soc/bcm/brcmstb/common.c:brcmstb_soc_device_init
  - drivers/soc/bcm/brcmstb/common.c:brcmstb_soc_device_early_init
```
```
In drivers/soc/amlogic/meson-mx-socinfo.c (ffff800011490640)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
```
```
In drivers/reset/reset-sunxi.c (ffff8000114928c4)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/reset/reset-sunxi.c:sun6i_reset_init
  - drivers/reset/reset-sunxi.c:sun6i_reset_init
```
```
In drivers/mfd/vexpress-sysreg.c (ffff8000114991fc)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_init
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_init
```
```
In drivers/net/ethernet/freescale/fman/fman.c (ffff8000109ee3e8)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman.c:read_dts_node
```
```
In drivers/firmware/arm_sdei.c (ffff8000114a3230)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/firmware/arm_sdei.c:sdei_init
```
```
In drivers/clocksource/arm_arch_timer.c (ffff8000114a8ed0)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_needs_of_probing
```
```
In drivers/of/platform.c (ffff8000114aa388)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_default_populate_init
  - drivers/of/platform.c:of_platform_default_populate_init
```
```
In drivers/of/address.c (ffff800010b743d4)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/of/address.c:of_find_matching_node_by_address
  - drivers/of/address.c:of_find_matching_node_by_address
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
In arch/arm/mm/cache-feroceon-l2.c (c1509b8c)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - arch/arm/mm/cache-feroceon-l2.c:feroceon_of_init
```
```
In arch/arm/mm/cache-l2x0.c (c150af04)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0.c:l2x0_of_init
```
```
In arch/arm/mm/cache-tauros2.c (c150b380)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - arch/arm/mm/cache-tauros2.c:tauros2_init
```
```
In arch/arm/mm/cache-uniphier.c (c150b8f4)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - arch/arm/mm/cache-uniphier.c:uniphier_cache_init
```
```
In arch/arm/mach-exynos/exynos.c (c150c420)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - arch/arm/mach-exynos/exynos.c:exynos_init_irq
```
```
In arch/arm/mach-exynos/mcpm-exynos.c (c150ca4c)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - arch/arm/mach-exynos/mcpm-exynos.c:exynos_mcpm_init
```
```
In arch/arm/mach-mvebu/mvebu-soc-id.c (c150d388)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/mvebu-soc-id.c:mvebu_soc_id_init
```
```
In arch/arm/mach-mvebu/coherency.c (c150db20)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/coherency.c:coherency_init
```
```
In arch/arm/mach-mvebu/pmsu.c (c150debc)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_cpu_pm_init
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_init
```
```
In arch/arm/mach-mvebu/platsmp.c (c0331988)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/platsmp.c:mv98dx3236_boot_secondary
```
```
In arch/arm/mach-omap2/timer.c (c15127bc)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - arch/arm/mach-omap2/timer.c:omap_get_timer_dt
  - arch/arm/mach-omap2/timer.c:omap_get_timer_dt
```
```
In arch/arm/mach-omap2/omap_hwmod.c (c1513894)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init
```
```
In arch/arm/mach-omap2/omap4-common.c (c1514e74)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap4-common.c:omap_gic_of_init
```
```
In arch/arm/mach-omap2/prm3xxx.c (c0340e4c)
Location: include/linux/of.h:1015
Inline: True
```
```
In arch/arm/mach-shmobile/platsmp-apmu.c (c03499c4)
Location: include/linux/of.h:1015
Inline: True
```
```
In arch/arm/mach-tegra/irq.c (c151a690)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - arch/arm/mach-tegra/irq.c:tegra_init_irq
  - arch/arm/mach-tegra/irq.c:tegra_init_irq
```
```
In arch/arm/mach-vexpress/platsmp.c (c151b470)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - arch/arm/mach-vexpress/platsmp.c:vexpress_smp_dt_prepare_cpus
```
```
In drivers/irqchip/irq-gic-v2m.c (c154b410)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_of_init
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_of_init
```
```
In drivers/irqchip/irq-gic-v3-its.c (c154cb48)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_init
```
```
In drivers/irqchip/irq-gic-v3-its-platform-msi.c (c154d0d8)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_init
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_init
```
```
In drivers/irqchip/irq-gic-v3-its-pci-msi.c (c154d230)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_init
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_init
```
```
In drivers/bus/arm-cci.c (c0823c1c)
Location: include/linux/of.h:1015
Inline: True
```
```
In drivers/video/fbdev/omap2/omapfb/dss/omapdss-boot-init.c (c1553788)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/video/fbdev/omap2/omapfb/dss/omapdss-boot-init.c:omapdss_boot_init
```
```
In drivers/clk/renesas/clk-emev2.c (c157e384)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-emev2.c:emev2_smu_init
```
```
In drivers/clk/tegra/clk-tegra20.c (c1587650)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-tegra20.c:tegra20_clock_init
```
```
In drivers/clk/tegra/clk-tegra30.c (c15880ec)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-tegra30.c:tegra30_clock_init
```
```
In drivers/clk/tegra/clk-tegra114.c (c158894c)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-tegra114.c:tegra114_clock_init
```
```
In drivers/clk/tegra/clk-tegra124.c (c158952c)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-tegra124.c:tegra124_132_clock_init_pre
```
```
In drivers/clk/ti/clk.c (c1589ea4)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/clk/ti/clk.c:ti_clk_add_aliases
  - drivers/clk/ti/clk.c:ti_clk_add_aliases
```
```
In drivers/clk/ti/clockdomain.c (c158a040)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/clk/ti/clockdomain.c:ti_dt_clockdomains_setup
  - drivers/clk/ti/clockdomain.c:ti_dt_clockdomains_setup
```
```
In drivers/soc/amlogic/meson-mx-socinfo.c (c1590198)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
```
```
In drivers/soc/samsung/exynos-pmu.c (c0939cb4)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/soc/samsung/exynos-pmu.c:exynos_get_pmu_regmap
```
```
In drivers/soc/samsung/pm_domains.c (c1591a88)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/soc/samsung/pm_domains.c:exynos4_pm_init_power_domain
  - drivers/soc/samsung/pm_domains.c:exynos4_pm_init_power_domain
```
```
In drivers/soc/tegra/fuse/fuse-tegra.c (c1591cdc)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/soc/tegra/fuse/fuse-tegra.c:tegra_init_fuse
```
```
In drivers/soc/tegra/fuse/tegra-apbmisc.c (c15921b4)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/soc/tegra/fuse/tegra-apbmisc.c:tegra_init_apbmisc
```
```
In drivers/soc/tegra/flowctrl.c (c1592e34)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/soc/tegra/flowctrl.c:tegra_flowctrl_init
```
```
In drivers/iommu/ipmmu-vmsa.c (c15974d4)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_init
```
```
In drivers/iommu/omap-iommu.c (c159755c)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_init
```
```
In drivers/iommu/tegra-smmu.c (c09c8c70)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/iommu/tegra-smmu.c:tegra_smmu_probe
```
```
In drivers/iommu/exynos-iommu.c (c1597668)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_init
```
```
In drivers/mfd/vexpress-sysreg.c (c159a0ac)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_init
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_init
```
```
In drivers/clocksource/dw_apb_timer_of.c (c15aae94)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/clocksource/dw_apb_timer_of.c:dw_apb_timer_init
```
```
In drivers/clocksource/arm_arch_timer.c (c15acdb8)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_needs_of_probing
  - drivers/clocksource/arm_arch_timer.c:arch_timer_needs_of_probing
```
```
In drivers/of/platform.c (c15ae8a8)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_default_populate_init
  - drivers/of/platform.c:of_platform_default_populate_init
```
```
In drivers/of/address.c (c0c567f4)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/of/address.c:of_find_matching_node_by_address
  - drivers/of/address.c:of_find_matching_node_by_address
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
In arch/powerpc/kernel/secure_boot.c (c000000000085504)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - arch/powerpc/kernel/secure_boot.c:is_ppc_trustedboot_enabled
  - arch/powerpc/kernel/secure_boot.c:is_ppc_secureboot_enabled
```
```
In arch/powerpc/sysdev/mpic.c (c00000000135845c)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
```
```
In drivers/of/address.c (c000000000c513d0)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/of/address.c:of_find_matching_node_by_address
  - drivers/of/address.c:of_find_matching_node_by_address
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
In arch/riscv/mm/sifive_l2_cache.c (ffffffe000003e76)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - arch/riscv/mm/sifive_l2_cache.c:sifive_l2_init
```
```
In drivers/of/platform.c (ffffffe00003a76c)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_default_populate_init
  - drivers/of/platform.c:of_platform_default_populate_init
```
```
In drivers/of/address.c (ffffffe000727dc4)
Location: include/linux/of.h:1015
Inline: True
Inline callers:
  - drivers/of/address.c:of_find_matching_node_by_address
  - drivers/of/address.c:of_find_matching_node_by_address
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
