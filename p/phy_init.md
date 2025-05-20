# Function: <code>phy_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8141c350)
Location: drivers/phy/phy-core.c:218
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/net/phy/phy_device.c (ffffffff81fafe37)
Location: drivers/net/phy/phy_device.c:1470
Inline: True
```
**Symbols:**

```
ffffffff81fafe37-ffffffff81fafe70: phy_init (STB_LOCAL)
ffffffff8141c350-ffffffff8141c40b: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81464930)
Location: drivers/phy/phy-core.c:218
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/net/phy/phy_device.c (ffffffff81fdc9e4)
Location: drivers/net/phy/phy_device.c:1712
Inline: True
```
**Symbols:**

```
ffffffff81fdc9e4-ffffffff81fdca16: phy_init (STB_LOCAL)
ffffffff81464930-ffffffff814649ee: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81483c30)
Location: drivers/phy/phy-core.c:218
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/net/phy/phy_device.c (ffffffff8201a4e5)
Location: drivers/net/phy/phy_device.c:1888
Inline: True
```
**Symbols:**

```
ffffffff8201a4e5-ffffffff8201a517: phy_init (STB_LOCAL)
ffffffff81483c30-ffffffff81483cee: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8148d1e0)
Location: drivers/phy/phy-core.c:218
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/net/phy/phy_device.c (ffffffff820fc533)
Location: drivers/net/phy/phy_device.c:1887
Inline: True
```
**Symbols:**

```
ffffffff820fc533-ffffffff820fc586: phy_init (STB_LOCAL)
ffffffff8148d1e0-ffffffff8148d291: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff814c9330)
Location: drivers/phy/phy-core.c:218
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/net/phy/phy_device.c (ffffffff82705ca8)
Location: drivers/net/phy/phy_device.c:1935
Inline: True
```
**Symbols:**

```
ffffffff82705ca8-ffffffff82705cfb: phy_init (STB_LOCAL)
ffffffff814c9330-ffffffff814c93e4: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff814fa370)
Location: drivers/phy/phy-core.c:236
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/net/phy/phy_device.c (ffffffff8272fae8)
Location: drivers/net/phy/phy_device.c:1980
Inline: False
```
**Symbols:**

```
ffffffff8272fae8-ffffffff8272fb3b: phy_init (STB_LOCAL)
ffffffff814fa370-ffffffff814fa41e: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8150efe0)
Location: drivers/phy/phy-core.c:236
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/net/phy/phy_device.c (ffffffff828e8546)
Location: drivers/net/phy/phy_device.c:2337
Inline: False
```
**Symbols:**

```
ffffffff828e8546-ffffffff828e87f8: phy_init (STB_LOCAL)
ffffffff8150efe0-ffffffff8150f08e: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8153d6e8)
Location: drivers/phy/phy-core.c:232
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/net/phy/phy_device.c (ffffffff82902e70)
Location: drivers/net/phy/phy_device.c:2415
Inline: False
```
**Symbols:**

```
ffffffff8153df73-ffffffff8153df89: phy_init.cold (STB_LOCAL)
ffffffff82902e70-ffffffff8290312c: phy_init (STB_LOCAL)
ffffffff8153d6b0-ffffffff8153d75a: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8155e4f8)
Location: drivers/phy/phy-core.c:232
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/net/phy/phy_device.c (ffffffff8290c06d)
Location: drivers/net/phy/phy_device.c:2384
Inline: False
```
**Symbols:**

```
ffffffff8155ed93-ffffffff8155eda9: phy_init.cold (STB_LOCAL)
ffffffff8290c06d-ffffffff8290c329: phy_init (STB_LOCAL)
ffffffff8155e4c0-ffffffff8155e56a: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81600fa4)
Location: drivers/phy/phy-core.c:232
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/net/phy/phy_device.c (ffffffff82d20f96)
Location: drivers/net/phy/phy_device.c:2882
Inline: False
```
**Symbols:**

```
ffffffff8160119a-ffffffff816011b0: phy_init.cold (STB_LOCAL)
ffffffff82d20f96-ffffffff82d20ff4: phy_init (STB_LOCAL)
ffffffff81600f70-ffffffff81601047: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81625e94)
Location: drivers/phy/phy-core.c:232
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/net/phy/phy_device.c (ffffffff8300ed75)
Location: drivers/net/phy/phy_device.c:3047
Inline: False
```
**Symbols:**

```
ffffffff81bf4e35-ffffffff81bf4e4b: phy_init.cold (STB_LOCAL)
ffffffff8300ed75-ffffffff8300eddf: phy_init (STB_LOCAL)
ffffffff81625e60-ffffffff81625f37: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81609844)
Location: drivers/phy/phy-core.c:232
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/net/phy/phy_device.c (ffffffff83219d59)
Location: drivers/net/phy/phy_device.c:3093
Inline: False
```
**Symbols:**

```
ffffffff81be6d4a-ffffffff81be6d60: phy_init.cold (STB_LOCAL)
ffffffff83219d59-ffffffff83219dc3: phy_init (STB_LOCAL)
ffffffff81609810-ffffffff816098e7: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff816784c4)
Location: drivers/phy/phy-core.c:232
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/net/phy/phy_device.c (ffffffff8330382e)
Location: drivers/net/phy/phy_device.c:3225
Inline: False
```
**Symbols:**

```
ffffffff81ce01d6-ffffffff81ce01ec: phy_init.cold (STB_LOCAL)
ffffffff8330382e-ffffffff83303898: phy_init (STB_LOCAL)
ffffffff81678490-ffffffff81678567: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81793883)
Location: drivers/phy/phy-core.c:243
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/net/phy/phy_device.c (ffffffff834bc7ee)
Location: drivers/net/phy/phy_device.c:3263
Inline: False
```
**Symbols:**

```
ffffffff81ea6928-ffffffff81ea6958: phy_init.cold (STB_LOCAL)
ffffffff834bc7ee-ffffffff834bc85a: phy_init (STB_LOCAL)
ffffffff81793850-ffffffff81793942: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff818a8500)
Location: drivers/phy/phy-core.c:243
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/net/phy/phy_device.c (ffffffff83efac20)
Location: drivers/net/phy/phy_device.c:3269
Inline: False
```
**Symbols:**

```
ffffffff83efac20-ffffffff83efac9c: phy_init (STB_LOCAL)
ffffffff818a8500-ffffffff818a8619: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff818eb3f0)
Location: drivers/phy/phy-core.c:245
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/net/phy/phy_device.c (ffffffff83720960)
Location: drivers/net/phy/phy_device.c:3441
Inline: False
```
**Symbols:**

```
ffffffff83720960-ffffffff837209d8: phy_init (STB_LOCAL)
ffffffff818eb3f0-ffffffff818eb509: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81932930)
Location: drivers/phy/phy-core.c:245
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/net/phy/phy_device.c (ffffffff83954830)
Location: drivers/net/phy/phy_device.c:3531
Inline: False
```
**Symbols:**

```
ffffffff83954830-ffffffff839548d2: phy_init (STB_LOCAL)
ffffffff81932930-ffffffff81932a49: phy_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffff8000106871c0)
Location: drivers/phy/phy-core.c:232
Inline: True
Direct callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/ata/libahci_platform.c:ahci_platform_enable_phys
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/net/phy/phy_device.c (ffff80001149b890)
Location: drivers/net/phy/phy_device.c:2384
Inline: False
```
**Symbols:**

```
ffff80001149b890-ffff80001149b908: phy_init (STB_LOCAL)
ffff8000106871c0-ffff800010687290: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (c082ae00)
Location: drivers/phy/phy-core.c:232
Inline: True
Direct callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_enable_phy
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/ata/libahci_platform.c:ahci_platform_enable_phys
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/net/phy/phy_device.c (c159cafc)
Location: drivers/net/phy/phy_device.c:2384
Inline: False
```
**Symbols:**

```
c159cafc-c159cb68: phy_init (STB_LOCAL)
c082ae00-c082aec4: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (c000000000821f90)
Location: drivers/phy/phy-core.c:232
Inline: True
Direct callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/net/phy/phy_device.c (c0000000013afc54)
Location: drivers/net/phy/phy_device.c:2384
Inline: False
```
**Symbols:**

```
c0000000013afc54-c0000000013afcf0: phy_init (STB_LOCAL)
c000000000821f90-c0000000008220bc: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffe000496abc)
Location: drivers/phy/phy-core.c:232
Inline: True
Direct callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/net/phy/phy_device.c (ffffffe000034ac4)
Location: drivers/net/phy/phy_device.c:2384
Inline: False
```
**Symbols:**

```
ffffffe000034ac4-ffffffe000034b3c: phy_init (STB_LOCAL)
ffffffe000496abc-ffffffe000496b60: phy_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81556ae8)
Location: drivers/phy/phy-core.c:232
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/net/phy/phy_device.c (ffffffff828f3a2a)
Location: drivers/net/phy/phy_device.c:2384
Inline: False
```
**Symbols:**

```
ffffffff81557383-ffffffff81557399: phy_init.cold (STB_LOCAL)
ffffffff828f3a2a-ffffffff828f3ce6: phy_init (STB_LOCAL)
ffffffff81556ab0-ffffffff81556b5a: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81546fa8)
Location: drivers/phy/phy-core.c:232
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_init
```
```
In drivers/net/phy/phy_device.c (ffffffff828eaed5)
Location: drivers/net/phy/phy_device.c:2384
Inline: False
```
**Symbols:**

```
ffffffff81547843-ffffffff81547859: phy_init.cold (STB_LOCAL)
ffffffff828eaed5-ffffffff828eb191: phy_init (STB_LOCAL)
ffffffff81546f70-ffffffff8154701a: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81552828)
Location: drivers/phy/phy-core.c:232
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/net/phy/phy_device.c (ffffffff82907468)
Location: drivers/net/phy/phy_device.c:2384
Inline: False
```
**Symbols:**

```
ffffffff815530c3-ffffffff815530d9: phy_init.cold (STB_LOCAL)
ffffffff82907468-ffffffff82907724: phy_init (STB_LOCAL)
ffffffff815527f0-ffffffff8155289a: phy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int phy_init(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8156c6b8)
Location: drivers/phy/phy-core.c:232
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/net/phy/phy_device.c (ffffffff8290d0cf)
Location: drivers/net/phy/phy_device.c:2384
Inline: False
```
**Symbols:**

```
ffffffff8156cf53-ffffffff8156cf69: phy_init.cold (STB_LOCAL)
ffffffff8290d0cf-ffffffff8290d38b: phy_init (STB_LOCAL)
ffffffff8156c680-ffffffff8156c72a: phy_init (STB_GLOBAL)
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
