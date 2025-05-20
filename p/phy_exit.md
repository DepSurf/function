# Function: <code>phy_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8141c410)
Location: drivers/phy/phy-core.c:247
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/net/phy/phy_device.c (ffffffff820b05a0)
Location: drivers/net/phy/phy_device.c:1486
Inline: False
```
**Symbols:**

```
ffffffff820b05a0-ffffffff820b05c3: phy_exit (STB_LOCAL)
ffffffff8141c410-ffffffff8141c4cd: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff814649f0)
Location: drivers/phy/phy-core.c:247
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/net/phy/phy_device.c (ffffffff820e80cd)
Location: drivers/net/phy/phy_device.c:1728
Inline: False
```
**Symbols:**

```
ffffffff820e80cd-ffffffff820e80f0: phy_exit (STB_LOCAL)
ffffffff814649f0-ffffffff81464ab0: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81483cf0)
Location: drivers/phy/phy-core.c:247
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/net/phy/phy_device.c (ffffffff821cde63)
Location: drivers/net/phy/phy_device.c:1904
Inline: False
```
**Symbols:**

```
ffffffff821cde63-ffffffff821cde86: phy_exit (STB_LOCAL)
ffffffff81483cf0-ffffffff81483db0: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8148d2a0)
Location: drivers/phy/phy-core.c:247
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/net/phy/phy_device.c (ffffffff822c3067)
Location: drivers/net/phy/phy_device.c:1909
Inline: False
```
**Symbols:**

```
ffffffff822c3067-ffffffff822c308a: phy_exit (STB_LOCAL)
ffffffff8148d2a0-ffffffff8148d358: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff814c93f0)
Location: drivers/phy/phy-core.c:247
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/net/phy/phy_device.c (ffffffff828d627f)
Location: drivers/net/phy/phy_device.c:1957
Inline: False
```
**Symbols:**

```
ffffffff828d627f-ffffffff828d62a2: phy_exit (STB_LOCAL)
ffffffff814c93f0-ffffffff814c94ab: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff814fa420)
Location: drivers/phy/phy-core.c:265
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_exit
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/net/phy/phy_device.c (ffffffff82907b5d)
Location: drivers/net/phy/phy_device.c:2002
Inline: False
```
**Symbols:**

```
ffffffff82907b5d-ffffffff82907b80: phy_exit (STB_LOCAL)
ffffffff814fa420-ffffffff814fa4d0: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8150f090)
Location: drivers/phy/phy-core.c:265
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_exit
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/net/phy/phy_device.c (ffffffff82adf981)
Location: drivers/net/phy/phy_device.c:2361
Inline: False
```
**Symbols:**

```
ffffffff82adf981-ffffffff82adf9a4: phy_exit (STB_LOCAL)
ffffffff8150f090-ffffffff8150f140: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8153d798)
Location: drivers/phy/phy-core.c:261
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_exit
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/net/phy/phy_device.c (ffffffff82b049ee)
Location: drivers/net/phy/phy_device.c:2439
Inline: False
```
**Symbols:**

```
ffffffff8153df89-ffffffff8153df9f: phy_exit.cold (STB_LOCAL)
ffffffff82b049ee-ffffffff82b04a11: phy_exit (STB_LOCAL)
ffffffff8153d760-ffffffff8153d80c: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8155e5a8)
Location: drivers/phy/phy-core.c:261
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_exit
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/net/phy/phy_device.c (ffffffff82b138bd)
Location: drivers/net/phy/phy_device.c:2408
Inline: False
```
**Symbols:**

```
ffffffff8155eda9-ffffffff8155edbf: phy_exit.cold (STB_LOCAL)
ffffffff82b138bd-ffffffff82b138e0: phy_exit (STB_LOCAL)
ffffffff8155e570-ffffffff8155e61c: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81600ec4)
Location: drivers/phy/phy-core.c:261
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/net/phy/phy_device.c (ffffffff82f25357)
Location: drivers/net/phy/phy_device.c:2906
Inline: False
```
**Symbols:**

```
ffffffff81601184-ffffffff8160119a: phy_exit.cold (STB_LOCAL)
ffffffff82f25357-ffffffff82f2537a: phy_exit (STB_LOCAL)
ffffffff81600e90-ffffffff81600f6c: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81625db4)
Location: drivers/phy/phy-core.c:261
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/net/phy/phy_device.c (ffffffff8321d8bd)
Location: drivers/net/phy/phy_device.c:3072
Inline: False
```
**Symbols:**

```
ffffffff81bf4e1f-ffffffff81bf4e35: phy_exit.cold (STB_LOCAL)
ffffffff8321d8bd-ffffffff8321d8e7: phy_exit (STB_LOCAL)
ffffffff81625d80-ffffffff81625e5c: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81609764)
Location: drivers/phy/phy-core.c:261
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/net/phy/phy_device.c (ffffffff83451876)
Location: drivers/net/phy/phy_device.c:3118
Inline: False
```
**Symbols:**

```
ffffffff81be6d34-ffffffff81be6d4a: phy_exit.cold (STB_LOCAL)
ffffffff83451876-ffffffff834518a0: phy_exit (STB_LOCAL)
ffffffff81609730-ffffffff8160980c: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff816783e4)
Location: drivers/phy/phy-core.c:261
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/net/phy/phy_device.c (ffffffff83544e93)
Location: drivers/net/phy/phy_device.c:3250
Inline: False
```
**Symbols:**

```
ffffffff81ce01c0-ffffffff81ce01d6: phy_exit.cold (STB_LOCAL)
ffffffff83544e93-ffffffff83544ebd: phy_exit (STB_LOCAL)
ffffffff816783b0-ffffffff8167848c: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff817936b3)
Location: drivers/phy/phy-core.c:283
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/net/phy/phy_device.c (ffffffff83723264)
Location: drivers/net/phy/phy_device.c:3288
Inline: False
```
**Symbols:**

```
ffffffff81ea6912-ffffffff81ea6928: phy_exit.cold (STB_LOCAL)
ffffffff83723264-ffffffff83723294: phy_exit (STB_LOCAL)
ffffffff81793680-ffffffff81793763: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff818a8300)
Location: drivers/phy/phy-core.c:283
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/net/phy/phy_device.c (ffffffff842b1cd0)
Location: drivers/net/phy/phy_device.c:3294
Inline: False
```
**Symbols:**

```
ffffffff842b1cd0-ffffffff842b1d00: phy_exit (STB_LOCAL)
ffffffff818a8300-ffffffff818a83f5: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff818eb1f0)
Location: drivers/phy/phy-core.c:285
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/net/phy/phy_device.c (ffffffff83af4940)
Location: drivers/net/phy/phy_device.c:3473
Inline: False
```
**Symbols:**

```
ffffffff83af4940-ffffffff83af4970: phy_exit (STB_LOCAL)
ffffffff818eb1f0-ffffffff818eb2e5: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81932730)
Location: drivers/phy/phy-core.c:285
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/net/phy/phy_device.c (ffffffff83d506d0)
Location: drivers/net/phy/phy_device.c:3569
Inline: False
```
**Symbols:**

```
ffffffff83d506d0-ffffffff83d50715: phy_exit (STB_LOCAL)
ffffffff81932730-ffffffff81932825: phy_exit (STB_GLOBAL)
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
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffff800010687290)
Location: drivers/phy/phy-core.c:261
Inline: True
Direct callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_disable_phy
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_deinit_phys
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/ata/libahci_platform.c:ahci_platform_disable_phys
  - drivers/ata/libahci_platform.c:ahci_platform_enable_phys
  - drivers/ata/libahci_platform.c:ahci_platform_enable_phys
  - drivers/usb/core/phy.c:usb_phy_roothub_exit
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/net/phy/phy_device.c (ffff8000114ba304)
Location: drivers/net/phy/phy_device.c:2408
Inline: False
```
**Symbols:**

```
ffff8000114ba304-ffff8000114ba334: phy_exit (STB_LOCAL)
ffff800010687290-ffff800010687364: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (c082aec4)
Location: drivers/phy/phy-core.c:261
Inline: True
Direct callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_disable_phy
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_phys_put
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_phys_put
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_deinit_phys
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_enable_phy
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_enable_phy
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_disable_phy
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_remove
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/ata/libahci_platform.c:ahci_platform_disable_phys
  - drivers/ata/libahci_platform.c:ahci_platform_enable_phys
  - drivers/ata/libahci_platform.c:ahci_platform_enable_phys
  - drivers/usb/core/phy.c:usb_phy_roothub_exit
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/net/phy/phy_device.c (c15c04fc)
Location: drivers/net/phy/phy_device.c:2408
Inline: False
```
**Symbols:**

```
c15c04fc-c15c0528: phy_exit (STB_LOCAL)
c082aec4-c082af7c: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (c0000000008220c0)
Location: drivers/phy/phy-core.c:261
Inline: True
Direct callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_disable_phy
  - drivers/usb/core/phy.c:usb_phy_roothub_exit
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/net/phy/phy_device.c (c0000000013cda40)
Location: drivers/net/phy/phy_device.c:2408
Inline: False
```
**Symbols:**

```
c0000000013cda40-c0000000013cda8c: phy_exit (STB_LOCAL)
c0000000008220c0-c0000000008221f0: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffe000496b60)
Location: drivers/phy/phy-core.c:261
Inline: True
Direct callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_disable_phy
  - drivers/usb/core/phy.c:usb_phy_roothub_exit
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/net/phy/phy_device.c (ffffffe0000a1e6e)
Location: drivers/net/phy/phy_device.c:2408
Inline: False
```
**Symbols:**

```
ffffffe0000a1e6e-ffffffe0000a1ea6: phy_exit (STB_LOCAL)
ffffffe000496b60-ffffffe000496c08: phy_exit (STB_GLOBAL)
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
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81556b98)
Location: drivers/phy/phy-core.c:261
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_exit
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/net/phy/phy_device.c (ffffffff82af390e)
Location: drivers/net/phy/phy_device.c:2408
Inline: False
```
**Symbols:**

```
ffffffff81557399-ffffffff815573af: phy_exit.cold (STB_LOCAL)
ffffffff82af390e-ffffffff82af3931: phy_exit (STB_LOCAL)
ffffffff81556b60-ffffffff81556c0c: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81547058)
Location: drivers/phy/phy-core.c:261
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_exit
  - drivers/usb/core/phy.c:usb_phy_roothub_init
```
```
In drivers/net/phy/phy_device.c (ffffffff82ac3cff)
Location: drivers/net/phy/phy_device.c:2408
Inline: False
```
**Symbols:**

```
ffffffff81547859-ffffffff8154786f: phy_exit.cold (STB_LOCAL)
ffffffff82ac3cff-ffffffff82ac3d22: phy_exit (STB_LOCAL)
ffffffff81547020-ffffffff815470cc: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff815528d8)
Location: drivers/phy/phy-core.c:261
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_exit
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/net/phy/phy_device.c (ffffffff82b0ebd3)
Location: drivers/net/phy/phy_device.c:2408
Inline: False
```
**Symbols:**

```
ffffffff815530d9-ffffffff815530ef: phy_exit.cold (STB_LOCAL)
ffffffff82b0ebd3-ffffffff82b0ebf6: phy_exit (STB_LOCAL)
ffffffff815528a0-ffffffff8155294c: phy_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int phy_exit(struct phy *phy);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8156c768)
Location: drivers/phy/phy-core.c:261
Inline: True
Direct callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_exit
  - drivers/usb/core/phy.c:usb_phy_roothub_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/net/phy/phy_device.c (ffffffff82b036f5)
Location: drivers/net/phy/phy_device.c:2408
Inline: False
```
**Symbols:**

```
ffffffff8156cf69-ffffffff8156cf7f: phy_exit.cold (STB_LOCAL)
ffffffff82b036f5-ffffffff82b03718: phy_exit (STB_LOCAL)
ffffffff8156c730-ffffffff8156c7dc: phy_exit (STB_GLOBAL)
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
