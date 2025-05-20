# Function: <code>phy_set_drvdata</code>

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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-xgene.c (ffff800010688124)
Location: include/linux/phy/phy.h:186
Inline: True
Inline callers:
  - drivers/phy/phy-xgene.c:xgene_phy_probe
```
```
In drivers/phy/broadcom/phy-bcm-ns2-pcie.c (ffff80001068a2b0)
Location: include/linux/phy/phy.h:186
Inline: True
Inline callers:
  - drivers/phy/broadcom/phy-bcm-ns2-pcie.c:ns2_pci_phy_probe
```
```
In drivers/phy/broadcom/phy-brcm-sata.c (ffff80001068a520)
Location: include/linux/phy/phy.h:186
Inline: True
Inline callers:
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_probe
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
In drivers/phy/marvell/phy-armada375-usb2.c (c082bc74)
Location: include/linux/phy/phy.h:186
Inline: True
Inline callers:
  - drivers/phy/marvell/phy-armada375-usb2.c:armada375_usb_phy_probe
```
```
In drivers/phy/marvell/phy-mvebu-sata.c (c082bf64)
Location: include/linux/phy/phy.h:186
Inline: True
Inline callers:
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_probe
```
```
In drivers/phy/samsung/phy-exynos-dp-video.c (c082c0a8)
Location: include/linux/phy/phy.h:186
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos-dp-video.c:exynos_dp_video_phy_probe
```
```
In drivers/phy/samsung/phy-exynos-mipi-video.c (c082c250)
Location: include/linux/phy/phy.h:186
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos-mipi-video.c:exynos_mipi_video_phy_probe
```
```
In drivers/phy/samsung/phy-exynos-pcie.c (c082c94c)
Location: include/linux/phy/phy.h:186
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos_pcie_phy_probe
```
```
In drivers/phy/samsung/phy-exynos5250-sata.c (c082cb28)
Location: include/linux/phy/phy.h:186
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_probe
```
```
In drivers/phy/ti/phy-gmii-sel.c (c082d128)
Location: include/linux/phy/phy.h:186
Inline: True
Inline callers:
  - drivers/phy/ti/phy-gmii-sel.c:phy_gmii_sel_probe
```
```
In drivers/pinctrl/tegra/pinctrl-tegra-xusb.c (c08440f0)
Location: include/linux/phy/phy.h:186
Inline: True
Inline callers:
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_legacy_probe
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_legacy_probe
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
