# Function: <code>pci_get_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8143aa90)
Location: drivers/pci/search.c:185
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - drivers/pci/access.c:pci_vpd_f0_write
  - drivers/pci/access.c:pci_vpd_f0_read
  - drivers/pci/quirks.c:quirk_f0_vpd_link
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/tty/serial/8250/8250_pci.c:byt_serial_setup
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffff8143aa90-ffffffff8143ab16: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814869b0)
Location: drivers/pci/search.c:189
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - drivers/pci/access.c:pci_vpd_f0_set_size
  - drivers/pci/access.c:pci_vpd_f0_write
  - drivers/pci/access.c:pci_vpd_f0_read
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_f0_vpd_link
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/tty/serial/8250/8250_pci.c:byt_serial_setup
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffff814869b0-ffffffff81486a35: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814a8160)
Location: drivers/pci/search.c:189
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - drivers/pci/access.c:pci_vpd_f0_set_size
  - drivers/pci/access.c:pci_vpd_f0_write
  - drivers/pci/access.c:pci_vpd_f0_read
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_f0_vpd_link
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffff814a8160-ffffffff814a81e5: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814b2130)
Location: drivers/pci/search.c:193
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - drivers/pci/access.c:pci_vpd_f0_set_size
  - drivers/pci/access.c:pci_vpd_f0_write
  - drivers/pci/access.c:pci_vpd_f0_read
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_f0_vpd_link
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffff814b2130-ffffffff814b21a7: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814f1820)
Location: drivers/pci/search.c:193
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - drivers/pci/access.c:pci_vpd_f0_set_size
  - drivers/pci/access.c:pci_vpd_f0_write
  - drivers/pci/access.c:pci_vpd_f0_read
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_f0_vpd_link
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffff814f1820-ffffffff814f1897: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81521ab0)
Location: drivers/pci/search.c:194
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffff81521ab0-ffffffff81521b27: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff815378e0)
Location: drivers/pci/search.c:194
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffff815378e0-ffffffff81537957: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/search.c (0)
Location: drivers/pci/search.c:190
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffff815676e9-ffffffff815676fc: pci_get_slot.cold (STB_LOCAL)
ffffffff81567270-ffffffff815672e4: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff815885d0)
Location: drivers/pci/search.c:189
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffff815885d0-ffffffff81588644: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8162f1b0)
Location: drivers/pci/search.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/hotplug/cpci_hotplug_core.c:init_slots
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:uli_agp_init
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffff8162f1b0-ffffffff8162f224: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81654840)
Location: drivers/pci/search.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/hotplug/cpci_hotplug_core.c:init_slots
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/char/agp/amd64-agp.c:uli_agp_init
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffff81654840-ffffffff816548b4: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff816372b0)
Location: drivers/pci/search.c:194
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffff816372b0-ffffffff81637312: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff816a7520)
Location: drivers/pci/search.c:194
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:vpd_write
  - drivers/pci/vpd.c:vpd_read
  - drivers/pci/vpd.c:pci_vpd_size
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffff816a7520-ffffffff816a7582: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff817c9f20)
Location: drivers/pci/search.c:194
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_write_vpd_any
  - drivers/pci/vpd.c:vpd_write
  - drivers/pci/vpd.c:vpd_read
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffff817c9f20-ffffffff817c9f89: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff818e79a0)
Location: drivers/pci/search.c:194
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_write_vpd_any
  - drivers/pci/vpd.c:vpd_write
  - drivers/pci/vpd.c:vpd_read
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:sriov_enable
  - drivers/tty/serial/8250/8250_mid.c:tng_setup
  - drivers/tty/serial/8250/8250_mid.c:pnw_setup
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffff818e79a0-ffffffff818e7a09: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8192afc0)
Location: drivers/pci/search.c:194
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_write_vpd_any
  - drivers/pci/vpd.c:vpd_write
  - drivers/pci/vpd.c:vpd_read
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:sriov_enable
  - drivers/tty/serial/8250/8250_mid.c:tng_setup
  - drivers/tty/serial/8250/8250_mid.c:pnw_setup
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffff8192afc0-ffffffff8192b029: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81973840)
Location: drivers/pci/search.c:194
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_write_vpd_any
  - drivers/pci/vpd.c:vpd_write
  - drivers/pci/vpd.c:vpd_read
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:sriov_enable
  - drivers/tty/serial/8250/8250_mid.c:tng_setup
  - drivers/tty/serial/8250/8250_mid.c:pnw_setup
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffff81973840-ffffffff819738a9: pci_get_slot (STB_GLOBAL)
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
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffff8000106ecaf8)
Location: drivers/pci/search.c:189
Inline: False
Direct callers:
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffff8000106ecaf8-ffff8000106ecb98: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (c0887d2c)
Location: drivers/pci/search.c:189
Inline: False
Direct callers:
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/iov.c:sriov_enable
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
c0887d2c-c0887de4: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (c0000000008688d0)
Location: drivers/pci/search.c:189
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci_of_scan.c:__of_scan_bus
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/iov.c:sriov_enable
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
c0000000008688d0-c0000000008689dc: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffe0004c19ec)
Location: drivers/pci/search.c:189
Inline: False
Direct callers:
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/iov.c:sriov_enable
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffe0004c19ec-ffffffe0004c1a76: pci_get_slot (STB_GLOBAL)
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
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8157c460)
Location: drivers/pci/search.c:189
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffff8157c460-ffffffff8157c4d4: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8156b230)
Location: drivers/pci/search.c:189
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/ata/pata_sis.c:sis_init_one
```
**Symbols:**

```
ffffffff8156b230-ffffffff8156b2a4: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8157c320)
Location: drivers/pci/search.c:189
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffff8157c320-ffffffff8157c394: pci_get_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pci_dev *pci_get_slot(struct pci_bus *bus, unsigned int devfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff815967d0)
Location: drivers/pci/search.c:189
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
  - drivers/pci/vpd.c:quirk_f0_vpd_link
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
  - drivers/pci/vpd.c:pci_vpd_f0_write
  - drivers/pci/vpd.c:pci_vpd_f0_read
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:nforce3_agp_init
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/host/ohci-pci.c:ohci_quirk_ns
```
**Symbols:**

```
ffffffff815967d0-ffffffff81596844: pci_get_slot (STB_GLOBAL)
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
