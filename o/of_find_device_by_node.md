# Function: <code>of_find_device_by_node</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (0)
Location: include/linux/of_platform.h:58
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
In drivers/media/cec/cec-notifier.c (0)
Location: include/linux/of_platform.h:58
Inline: True
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct platform_device *of_find_device_by_node(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (ffff800010b6d020)
Location: drivers/of/platform.c:49
Inline: True
Direct callers:
  - lib/genalloc.c:of_gen_pool_get
  - lib/genalloc.c:of_gen_pool_get
  - drivers/iommu/rockchip-iommu.c:rk_iommu_of_xlate
  - drivers/iommu/qcom_iommu.c:qcom_iommu_of_xlate
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/net/ethernet/freescale/fman/fman_port.c:fman_port_probe
  - drivers/net/ethernet/freescale/fman/mac.c:mac_probe
  - drivers/net/ethernet/freescale/fman/mac.c:mac_probe
  - drivers/usb/common/common.c:usb_of_get_companion_dev
  - drivers/media/cec/cec-notifier.c:cec_notifier_parse_hdmi_phandle
  - drivers/firmware/raspberrypi.c:rpi_firmware_get
  - drivers/memory/mtk-smi.c:mtk_smi_larb_probe
```
**Symbols:**

```
ffff800010b6d020-ffff800010b6d06c: of_find_device_by_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct platform_device *of_find_device_by_node(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (c0c4ffdc)
Location: drivers/of/platform.c:49
Inline: True
Direct callers:
  - arch/arm/mach-imx/pm-imx6.c:imx6q_suspend_init
  - lib/genalloc.c:of_gen_pool_get
  - lib/genalloc.c:of_gen_pool_get
  - drivers/clk/tegra/clk-emc.c:emc_set_timing
  - drivers/dma/ti/dma-crossbar.c:ti_dra7_xbar_route_allocate
  - drivers/dma/ti/dma-crossbar.c:ti_am335x_xbar_route_allocate
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_of_xlate
  - drivers/iommu/omap-iommu.c:_omap_iommu_add_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_of_xlate
  - drivers/iommu/tegra-smmu.c:tegra_smmu_add_device
  - drivers/iommu/exynos-iommu.c:exynos_iommu_of_xlate
  - drivers/iommu/qcom_iommu.c:qcom_iommu_of_xlate
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/mtd/nand/raw/omap2.c:omap_nand_attach_chip
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe_dt
  - drivers/usb/common/common.c:usb_of_get_companion_dev
  - drivers/media/cec/cec-notifier.c:cec_notifier_parse_hdmi_phandle
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_get
  - drivers/memory/mtk-smi.c:mtk_smi_larb_probe
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe
  - sound/soc/fsl/imx-sgtl5000.c:imx_sgtl5000_probe
```
**Symbols:**

```
c0c4ffdc-c0c50018: of_find_device_by_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct platform_device *of_find_device_by_node(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (c000000000c47760)
Location: drivers/of/platform.c:49
Inline: True
Direct callers:
  - lib/genalloc.c:of_gen_pool_get
  - lib/genalloc.c:of_gen_pool_get
  - drivers/usb/common/common.c:usb_of_get_companion_dev
  - drivers/media/cec/cec-notifier.c:cec_notifier_parse_hdmi_phandle
```
**Symbols:**

```
c000000000c47760-c000000000c477b8: of_find_device_by_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct platform_device *of_find_device_by_node(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (ffffffe000721e54)
Location: drivers/of/platform.c:49
Inline: True
Direct callers:
  - lib/genalloc.c:of_gen_pool_get
  - lib/genalloc.c:of_gen_pool_get
  - drivers/usb/common/common.c:usb_of_get_companion_dev
  - drivers/media/cec/cec-notifier.c:cec_notifier_parse_hdmi_phandle
```
**Symbols:**

```
ffffffe000721e54-ffffffe000721e94: of_find_device_by_node (STB_GLOBAL)
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
In drivers/media/cec/cec-notifier.c (0)
Location: include/linux/of_platform.h:58
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
In drivers/media/cec/cec-notifier.c (0)
Location: include/linux/of_platform.h:58
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
In drivers/media/cec/cec-notifier.c (0)
Location: include/linux/of_platform.h:58
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
In drivers/media/cec/cec-notifier.c (0)
Location: include/linux/of_platform.h:58
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
