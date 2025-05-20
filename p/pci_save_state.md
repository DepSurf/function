# Function: <code>pci_save_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81435ac0)
Location: drivers/pci/pci.c:1050
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff81435ac0-ffffffff81435c42: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814815a0)
Location: drivers/pci/pci.c:1071
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff814815a0-ffffffff81481722: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a2ad0)
Location: drivers/pci/pci.c:1096
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff814a2ad0-ffffffff814a2c52: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ac900)
Location: drivers/pci/pci.c:1092
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff814ac900-ffffffff814aca80: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ebc00)
Location: drivers/pci/pci.c:1095
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff814ebc00-ffffffff814ebd80: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151b440)
Location: drivers/pci/pci.c:1107
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff8151b440-ffffffff8151b5c9: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815312e0)
Location: drivers/pci/pci.c:1278
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff815312e0-ffffffff81531471: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81560b30)
Location: drivers/pci/pci.c:1346
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff81560b30-ffffffff81560d50: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81581d20)
Location: drivers/pci/pci.c:1342
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff81581d20-ffffffff81581f3c: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81628b90)
Location: drivers/pci/pci.c:1407
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff81628b90-ffffffff81628e09: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164edb0)
Location: drivers/pci/pci.c:1541
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff8164edb0-ffffffff8164f033: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81631880)
Location: drivers/pci/pci.c:1571
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff81631880-ffffffff81631b03: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1606
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_power_state
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff81ce47da-ffffffff81ce4819: pci_save_state.cold (STB_LOCAL)
ffffffff816a1110-ffffffff816a140b: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1667
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_power_state
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff81eab1d4-ffffffff81eab21d: pci_save_state.cold (STB_LOCAL)
ffffffff817c2f00-ffffffff817c3214: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1645
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_slot_reset
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff8208f11f-ffffffff8208f15e: pci_save_state.cold (STB_LOCAL)
ffffffff818dfcd0-ffffffff818dffbe: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1683
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_slot_reset
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff8210f485-ffffffff8210f4c4: pci_save_state.cold (STB_LOCAL)
ffffffff81923130-ffffffff8192341e: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1781
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_poweroff_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_slot_reset
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff821ed10c-ffffffff821ed14b: pci_save_state.cold (STB_LOCAL)
ffffffff8196b6b0-ffffffff8196b99e: pci_save_state (STB_GLOBAL)
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
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e4f98)
Location: drivers/pci/pci.c:1342
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffff8000106e4f98-ffff8000106e51c0: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0880bd0)
Location: drivers/pci/pci.c:1342
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
c0880bd0-c0880e0c: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085f690)
Location: drivers/pci/pci.c:1342
Inline: True
Direct callers:
  - arch/powerpc/kernel/eeh.c:eeh_disable_and_save_dev_state
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
c00000000085f690-c00000000085f960: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bc21c)
Location: drivers/pci/pci.c:1342
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
```
**Symbols:**

```
ffffffe0004bc21c-ffffffe0004bc418: pci_save_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81576240)
Location: drivers/pci/pci.c:1342
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/nvme/host/pci.c:nvme_suspend
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff81576240-ffffffff8157645c: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815649a0)
Location: drivers/pci/pci.c:1342
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/nvme/host/pci.c:nvme_suspend
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff815649a0-ffffffff81564bbc: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81575a70)
Location: drivers/pci/pci.c:1342
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_suspend
```
**Symbols:**

```
ffffffff81575a70-ffffffff81575c8c: pci_save_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pci_save_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81590040)
Location: drivers/pci/pci.c:1342
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_freeze_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pci-driver.c:pci_legacy_suspend_late
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_suspend
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
**Symbols:**

```
ffffffff81590040-ffffffff8159025c: pci_save_state (STB_GLOBAL)
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
