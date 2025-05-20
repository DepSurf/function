# Function: <code>phy_power_off</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8141bf00)
Location: drivers/phy/phy-core.c:318
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff8141bf00-ffffffff8141bfc0: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81464560)
Location: drivers/phy/phy-core.c:318
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff81464560-ffffffff81464620: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81483860)
Location: drivers/phy/phy-core.c:318
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff81483860-ffffffff81483920: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8148d460)
Location: drivers/phy/phy-core.c:318
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff8148d460-ffffffff8148d526: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff814c95b0)
Location: drivers/phy/phy-core.c:318
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff814c95b0-ffffffff814c967d: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff814fa5d0)
Location: drivers/phy/phy-core.c:336
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_power_off
  - drivers/usb/core/phy.c:usb_phy_roothub_power_on
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff814fa5d0-ffffffff814fa67d: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8150f240)
Location: drivers/phy/phy-core.c:336
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_power_off
  - drivers/usb/core/phy.c:usb_phy_roothub_power_on
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff8150f240-ffffffff8150f2ed: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8153d900)
Location: drivers/phy/phy-core.c:332
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_power_off
  - drivers/usb/core/phy.c:usb_phy_roothub_power_on
  - drivers/usb/core/phy.c:usb_phy_roothub_set_mode
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff8153dfc5-ffffffff8153dfe9: phy_power_off.cold (STB_LOCAL)
ffffffff8153d8e0-ffffffff8153d980: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8155e710)
Location: drivers/phy/phy-core.c:332
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_power_off
  - drivers/usb/core/phy.c:usb_phy_roothub_power_on
  - drivers/usb/core/phy.c:usb_phy_roothub_set_mode
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff8155ede5-ffffffff8155ee09: phy_power_off.cold (STB_LOCAL)
ffffffff8155e6f0-ffffffff8155e790: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81600cf0)
Location: drivers/phy/phy-core.c:332
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
  - drivers/usb/core/phy.c:usb_phy_roothub_power_on
  - drivers/usb/core/phy.c:usb_phy_roothub_set_mode
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff8160113a-ffffffff8160115e: phy_power_off.cold (STB_LOCAL)
ffffffff81600cd0-ffffffff81600d80: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81625be0)
Location: drivers/phy/phy-core.c:332
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
  - drivers/usb/core/phy.c:usb_phy_roothub_power_on
  - drivers/usb/core/phy.c:usb_phy_roothub_set_mode
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff81bf4dd5-ffffffff81bf4df9: phy_power_off.cold (STB_LOCAL)
ffffffff81625bc0-ffffffff81625c70: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff816096a0)
Location: drivers/phy/phy-core.c:332
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
  - drivers/usb/core/phy.c:usb_phy_roothub_power_on
  - drivers/usb/core/phy.c:usb_phy_roothub_set_mode
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff81be6d10-ffffffff81be6d34: phy_power_off.cold (STB_LOCAL)
ffffffff81609680-ffffffff81609730: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81678320)
Location: drivers/phy/phy-core.c:332
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
  - drivers/usb/core/phy.c:usb_phy_roothub_power_on
  - drivers/usb/core/phy.c:usb_phy_roothub_set_mode
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff81ce019c-ffffffff81ce01c0: phy_power_off.cold (STB_LOCAL)
ffffffff81678300-ffffffff816783b0: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (0)
Location: drivers/phy/phy-core.c:370
Inline: False
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
  - drivers/usb/core/phy.c:usb_phy_roothub_power_on
  - drivers/usb/core/phy.c:usb_phy_roothub_set_mode
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff81ea68ee-ffffffff81ea6912: phy_power_off.cold (STB_LOCAL)
ffffffff817935c0-ffffffff81793676: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff818a8210)
Location: drivers/phy/phy-core.c:370
Inline: False
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
  - drivers/usb/core/phy.c:usb_phy_roothub_power_on
  - drivers/usb/core/phy.c:usb_phy_roothub_set_mode
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff818a8210-ffffffff818a82e3: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff818eb100)
Location: drivers/phy/phy-core.c:372
Inline: False
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
  - drivers/usb/core/phy.c:usb_phy_roothub_power_on
  - drivers/usb/core/phy.c:usb_phy_roothub_set_mode
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff818eb100-ffffffff818eb1d3: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81932640)
Location: drivers/phy/phy-core.c:372
Inline: False
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
  - drivers/usb/core/phy.c:usb_phy_roothub_power_on
  - drivers/usb/core/phy.c:usb_phy_roothub_set_mode
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff81932640-ffffffff81932713: phy_power_off (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffff800010687470)
Location: drivers/phy/phy-core.c:332
Inline: True
Direct callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_disable_phy
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_deinit_phys
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/ata/libahci_platform.c:ahci_platform_disable_phys
  - drivers/ata/libahci_platform.c:ahci_platform_enable_phys
  - drivers/usb/core/phy.c:usb_phy_roothub_power_off
  - drivers/usb/core/phy.c:usb_phy_roothub_power_on
  - drivers/usb/core/phy.c:usb_phy_roothub_set_mode
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffff800010687470-ffff800010687540: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (c082b068)
Location: drivers/phy/phy-core.c:332
Inline: True
Direct callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_disable_phy
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_deinit_phys
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_enable_phy
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_disable_phy
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/ata/libahci_platform.c:ahci_platform_disable_phys
  - drivers/ata/libahci_platform.c:ahci_platform_enable_phys
  - drivers/usb/core/phy.c:usb_phy_roothub_power_off
  - drivers/usb/core/phy.c:usb_phy_roothub_power_on
  - drivers/usb/core/phy.c:usb_phy_roothub_set_mode
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_suspend
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_remove
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_probe
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_phy_enable
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_suspend
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_remove
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_probe
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_phy_enable
```
**Symbols:**

```
c082b068-c082b120: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (c000000000822370)
Location: drivers/phy/phy-core.c:332
Inline: True
Direct callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_disable_phy
  - drivers/usb/core/phy.c:usb_phy_roothub_power_off
  - drivers/usb/core/phy.c:usb_phy_roothub_power_on
  - drivers/usb/core/phy.c:usb_phy_roothub_set_mode
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
c000000000822370-c0000000008224a8: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffe000496ce4)
Location: drivers/phy/phy-core.c:332
Inline: True
Direct callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_disable_phy
  - drivers/usb/core/phy.c:usb_phy_roothub_power_off
  - drivers/usb/core/phy.c:usb_phy_roothub_power_on
  - drivers/usb/core/phy.c:usb_phy_roothub_set_mode
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffe000496ce4-ffffffe000496d88: phy_power_off (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81556d00)
Location: drivers/phy/phy-core.c:332
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_power_off
  - drivers/usb/core/phy.c:usb_phy_roothub_power_on
  - drivers/usb/core/phy.c:usb_phy_roothub_set_mode
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff815573d5-ffffffff815573f9: phy_power_off.cold (STB_LOCAL)
ffffffff81556ce0-ffffffff81556d80: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff815471c0)
Location: drivers/phy/phy-core.c:332
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_power_off
  - drivers/usb/core/phy.c:usb_phy_roothub_power_on
  - drivers/usb/core/phy.c:usb_phy_roothub_set_mode
```
**Symbols:**

```
ffffffff81547895-ffffffff815478b9: phy_power_off.cold (STB_LOCAL)
ffffffff815471a0-ffffffff81547240: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81552a40)
Location: drivers/phy/phy-core.c:332
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_power_off
  - drivers/usb/core/phy.c:usb_phy_roothub_power_on
  - drivers/usb/core/phy.c:usb_phy_roothub_set_mode
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff81553115-ffffffff81553139: phy_power_off.cold (STB_LOCAL)
ffffffff81552a20-ffffffff81552ac0: phy_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int phy_power_off(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8156c8d0)
Location: drivers/phy/phy-core.c:332
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_power_off
  - drivers/usb/core/phy.c:usb_phy_roothub_power_on
  - drivers/usb/core/phy.c:usb_phy_roothub_set_mode
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
**Symbols:**

```
ffffffff8156cfa5-ffffffff8156cfc9: phy_power_off.cold (STB_LOCAL)
ffffffff8156c8b0-ffffffff8156c950: phy_power_off (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
