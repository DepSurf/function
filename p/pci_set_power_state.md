# Function: <code>pci_set_power_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81436610)
Location: drivers/pci/pci.c:856
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
```
**Symbols:**

```
ffffffff81436610-ffffffff8143670f: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81482160)
Location: drivers/pci/pci.c:877
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
```
**Symbols:**

```
ffffffff81482160-ffffffff8148226e: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a36f0)
Location: drivers/pci/pci.c:902
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
```
**Symbols:**

```
ffffffff814a36f0-ffffffff814a37fe: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ad6e0)
Location: drivers/pci/pci.c:898
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
```
**Symbols:**

```
ffffffff814ad6e0-ffffffff814ad7fe: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ecab0)
Location: drivers/pci/pci.c:901
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
```
**Symbols:**

```
ffffffff814ecab0-ffffffff814ecbce: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151c680)
Location: drivers/pci/pci.c:913
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
```
**Symbols:**

```
ffffffff8151c680-ffffffff8151c783: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81531f70)
Location: drivers/pci/pci.c:1084
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
```
**Symbols:**

```
ffffffff81531f70-ffffffff8153207e: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81561600)
Location: drivers/pci/pci.c:1110
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
```
**Symbols:**

```
ffffffff81561600-ffffffff81561711: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815827b0)
Location: drivers/pci/pci.c:1095
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
```
**Symbols:**

```
ffffffff815827b0-ffffffff815828c3: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81629080)
Location: drivers/pci/pci.c:1166
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
```
**Symbols:**

```
ffffffff81629080-ffffffff81629219: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164f2d0)
Location: drivers/pci/pci.c:1300
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
```
**Symbols:**

```
ffffffff8164f2d0-ffffffff8164f469: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81631da0)
Location: drivers/pci/pci.c:1330
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
```
**Symbols:**

```
ffffffff81631da0-ffffffff81631f37: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a16c0)
Location: drivers/pci/pci.c:1340
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_power_state
```
**Symbols:**

```
ffffffff816a16c0-ffffffff816a1857: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1433
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_power_state
```
**Symbols:**

```
ffffffff81eab253-ffffffff81eab27e: pci_set_power_state.cold (STB_LOCAL)
ffffffff817c36b0-ffffffff817c38ff: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e0540)
Location: drivers/pci/pci.c:1411
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_resume
```
**Symbols:**

```
ffffffff818e0540-ffffffff818e0786: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81923980)
Location: drivers/pci/pci.c:1449
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:do_pci_enable_device
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/platform/x86/intel/pmc/mtl.c:mtl_set_device_d3
```
**Symbols:**

```
ffffffff81923980-ffffffff81923bcf: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196c410)
Location: drivers/pci/pci.c:1590
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:do_pci_enable_device
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_resume
```
**Symbols:**

```
ffffffff8196c250-ffffffff8196c26c: pci_set_power_state (STB_GLOBAL)
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
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e6398)
Location: drivers/pci/pci.c:1095
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
```
**Symbols:**

```
ffff8000106e6398-ffff8000106e64cc: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c08816b8)
Location: drivers/pci/pci.c:1095
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
```
**Symbols:**

```
c08816b8-c0881810: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000860600)
Location: drivers/pci/pci.c:1095
Inline: False
Direct callers:
  - arch/powerpc/kernel/eeh.c:eeh_disable_and_save_dev_state
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
```
**Symbols:**

```
c000000000860600-c0000000008607bc: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bce10)
Location: drivers/pci/pci.c:1095
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
```
**Symbols:**

```
ffffffe0004bce10-ffffffe0004bcf00: pci_set_power_state (STB_GLOBAL)
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
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81576cd0)
Location: drivers/pci/pci.c:1095
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
```
**Symbols:**

```
ffffffff81576cd0-ffffffff81576de3: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81565430)
Location: drivers/pci/pci.c:1095
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
```
**Symbols:**

```
ffffffff81565430-ffffffff81565543: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81576500)
Location: drivers/pci/pci.c:1095
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
```
**Symbols:**

```
ffffffff81576500-ffffffff81576613: pci_set_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815909e0)
Location: drivers/pci/pci.c:1095
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_dev_save_and_disable
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_back_from_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/char/agp/amd64-agp.c:agp_amd64_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
  - drivers/char/agp/via-agp.c:agp_via_resume
  - drivers/char/agp/via-agp.c:agp_via_suspend
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/ata/ata_piix.c:piix_pci_device_resume
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state
  - drivers/usb/host/xhci-pci.c:xhci_pci_shutdown
  - drivers/usb/host/xhci-pci.c:xhci_pci_remove
```
**Symbols:**

```
ffffffff815909e0-ffffffff81590af3: pci_set_power_state (STB_GLOBAL)
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
