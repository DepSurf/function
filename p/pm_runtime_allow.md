# Function: <code>pm_runtime_allow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81557790)
Location: drivers/base/power/runtime.c:1251
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/gpio/gpio-intel-mid.c:intel_gpio_probe
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
```
**Symbols:**

```
ffffffff81557790-ffffffff815577f0: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815a9850)
Location: drivers/base/power/runtime.c:1255
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
```
**Symbols:**

```
ffffffff815a9850-ffffffff815a98ac: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d8640)
Location: drivers/base/power/runtime.c:1343
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
```
**Symbols:**

```
ffffffff815d8640-ffffffff815d869c: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815ecc00)
Location: drivers/base/power/runtime.c:1343
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff815ecc00-ffffffff815ecc60: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81653fc0)
Location: drivers/base/power/runtime.c:1335
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81653fc0-ffffffff81654020: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8168fc00)
Location: drivers/base/power/runtime.c:1335
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/pci/quirks.c:quirk_gpu_hda
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff8168fc00-ffffffff8168fc60: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816aff90)
Location: drivers/base/power/runtime.c:1342
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/pci/quirks.c:quirk_gpu_hda
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff816aff90-ffffffff816afff0: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816e9e20)
Location: drivers/base/power/runtime.c:1426
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff816e9e20-ffffffff816e9e88: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8170de80)
Location: drivers/base/power/runtime.c:1428
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff8170de80-ffffffff8170dee8: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c90a0)
Location: drivers/base/power/runtime.c:1449
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817c90a0-ffffffff817c9191: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817dcd60)
Location: drivers/base/power/runtime.c:1481
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817dcd60-ffffffff817dce40: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c1120)
Location: drivers/base/power/runtime.c:1481
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817c1120-ffffffff817c11fc: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8184bc20)
Location: drivers/base/power/runtime.c:1517
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff8184bc20-ffffffff8184bcf9: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81990600)
Location: drivers/base/power/runtime.c:1553
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/base/power/sysfs.c:control_store
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81990600-ffffffff8199070d: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b00910)
Location: drivers/base/power/runtime.c:1566
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81b00910-ffffffff81b00a1d: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b4eaf0)
Location: drivers/base/power/runtime.c:1566
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81b4eaf0-ffffffff81b4ebbd: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba7070)
Location: drivers/base/power/runtime.c:1567
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81ba7070-ffffffff81ba713d: pm_runtime_allow (STB_GLOBAL)
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
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffff8000108fd6a0)
Location: drivers/base/power/runtime.c:1428
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffff8000108fd6a0-ffff8000108fd78c: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c09e7eb8)
Location: drivers/base/power/runtime.c:1428
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
c09e7eb8-c09e7f48: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c00000000099ab50)
Location: drivers/base/power/runtime.c:1428
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
c00000000099ab50-c00000000099ac70: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffe00058c382)
Location: drivers/base/power/runtime.c:1428
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffe00058c382-ffffffe00058c424: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816d35d0)
Location: drivers/base/power/runtime.c:1428
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff816d35d0-ffffffff816d3638: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ae890)
Location: drivers/base/power/runtime.c:1428
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff816ae890-ffffffff816ae8f2: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81701b40)
Location: drivers/base/power/runtime.c:1428
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe
```
**Symbols:**

```
ffffffff81701b40-ffffffff81701ba8: pm_runtime_allow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pm_runtime_allow(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8171bd80)
Location: drivers/base/power/runtime.c:1428
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/driver.c:usb_enable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff8171bd80-ffffffff8171bdeb: pm_runtime_allow (STB_GLOBAL)
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
