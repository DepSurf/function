# Function: <code>pm_runtime_forbid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81557490)
Location: drivers/base/power/runtime.c:1230
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
```
**Symbols:**

```
ffffffff81557490-ffffffff815574e9: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815a94e0)
Location: drivers/base/power/runtime.c:1234
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
```
**Symbols:**

```
ffffffff815a94e0-ffffffff815a953d: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d81b0)
Location: drivers/base/power/runtime.c:1322
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
```
**Symbols:**

```
ffffffff815d81b0-ffffffff815d820d: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815ed150)
Location: drivers/base/power/runtime.c:1322
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff815ed150-ffffffff815ed1af: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81654500)
Location: drivers/base/power/runtime.c:1314
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff81654500-ffffffff8165455f: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8168fba0)
Location: drivers/base/power/runtime.c:1314
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff8168fba0-ffffffff8168fbff: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816aff30)
Location: drivers/base/power/runtime.c:1321
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff816aff30-ffffffff816aff8f: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816e9b30)
Location: drivers/base/power/runtime.c:1405
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff816e9b30-ffffffff816e9b91: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8170db90)
Location: drivers/base/power/runtime.c:1407
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff8170db90-ffffffff8170dbf1: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c8e50)
Location: drivers/base/power/runtime.c:1428
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff817c8e50-ffffffff817c8eb1: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817dda60)
Location: drivers/base/power/runtime.c:1460
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff817dda60-ffffffff817ddac1: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c1df0)
Location: drivers/base/power/runtime.c:1460
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff817c1df0-ffffffff817c1e4d: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8184bbc0)
Location: drivers/base/power/runtime.c:1496
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff8184bbc0-ffffffff8184bc1d: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff819915e0)
Location: drivers/base/power/runtime.c:1532
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_unregister_device
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff819915e0-ffffffff81991636: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b019a0)
Location: drivers/base/power/runtime.c:1545
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff81b019a0-ffffffff81b019f6: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b4fad0)
Location: drivers/base/power/runtime.c:1545
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff81b4fad0-ffffffff81b4fb26: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba8050)
Location: drivers/base/power/runtime.c:1546
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff81ba8050-ffffffff81ba80a6: pm_runtime_forbid (STB_GLOBAL)
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
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffff8000108fd220)
Location: drivers/base/power/runtime.c:1407
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffff8000108fd220-ffff8000108fd2f8: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c09e8160)
Location: drivers/base/power/runtime.c:1407
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
c09e8160-c09e81e0: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c000000000999b00)
Location: drivers/base/power/runtime.c:1407
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
c000000000999b00-c000000000999bf4: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffe00058c048)
Location: drivers/base/power/runtime.c:1407
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffe00058c048-ffffffe00058c0e0: pm_runtime_forbid (STB_GLOBAL)
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
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816d32e0)
Location: drivers/base/power/runtime.c:1407
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff816d32e0-ffffffff816d3341: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ae5d0)
Location: drivers/base/power/runtime.c:1407
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff816ae5d0-ffffffff816ae62b: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81701850)
Location: drivers/base/power/runtime.c:1407
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_remove
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff81701850-ffffffff817018b1: pm_runtime_forbid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pm_runtime_forbid(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8171c010)
Location: drivers/base/power/runtime.c:1407
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/base/power/sysfs.c:control_store
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/driver.c:usb_disable_autosuspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff8171c010-ffffffff8171c068: pm_runtime_forbid (STB_GLOBAL)
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
