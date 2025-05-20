# Function: <code>pci_find_capability</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81435000)
Location: drivers/pci/pci.c:237
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_pci22_init
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_cfg_space_size
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffff81435000-ffffffff81435073: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81480960)
Location: drivers/pci/pci.c:258
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_init
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffff81480960-ffffffff814809d3: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a2020)
Location: drivers/pci/pci.c:258
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_init
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffff814a2020-ffffffff814a2093: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814abdd0)
Location: drivers/pci/pci.c:260
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_init
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffff814abdd0-ffffffff814abe43: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814eaea0)
Location: drivers/pci/pci.c:261
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_init
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffff814eaea0-ffffffff814eaf13: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151a450)
Location: drivers/pci/pci.c:273
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/vpd.c:pci_vpd_init
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/pci-acpi.c:shpchp_is_native
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffff8151a450-ffffffff8151a4c5: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815301b0)
Location: drivers/pci/pci.c:439
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/vpd.c:pci_vpd_init
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffff815301b0-ffffffff81530225: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8155f990)
Location: drivers/pci/pci.c:439
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:program_hpx_type3
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/vpd.c:pci_vpd_init
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffff8155f990-ffffffff8155fa05: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81580ad0)
Location: drivers/pci/pci.c:439
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/vpd.c:pci_vpd_init
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffff81580ad0-ffffffff81580b45: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81626b10)
Location: drivers/pci/pci.c:471
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_msi_setup_pci_dev
  - drivers/pci/probe.c:pci_msi_setup_pci_dev
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/vpd.c:pci_vpd_init
  - drivers/pci/pci-acpi.c:acpi_run_hpx
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffff81626b10-ffffffff81626bac: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u8 pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164c780)
Location: drivers/pci/pci.c:480
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/vpd.c:pci_vpd_init
  - drivers/pci/msi.c:pci_msix_init
  - drivers/pci/msi.c:pci_msi_init
  - drivers/pci/pci-acpi.c:acpi_run_hpx
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffff8164c780-ffffffff8164c81c: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u8 pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162f300)
Location: drivers/pci/pci.c:480
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/vpd.c:pci_vpd_init
  - drivers/pci/msi.c:pci_msix_init
  - drivers/pci/msi.c:pci_msi_init
  - drivers/pci/pci-acpi.c:acpi_run_hpx
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffff8162f300-ffffffff8162f39c: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u8 pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169ee90)
Location: drivers/pci/pci.c:490
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/vpd.c:pci_vpd_init
  - drivers/pci/msi.c:pci_msix_init
  - drivers/pci/msi.c:pci_msi_init
  - drivers/pci/pci-acpi.c:acpi_run_hpx
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffff8169ee90-ffffffff8169ef2c: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u8 pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c1580)
Location: drivers/pci/pci.c:507
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_cfg_space_size
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:_pci_add_cap_save_buffer
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/vpd.c:pci_vpd_init
  - drivers/pci/msi/pcidev_msi.c:pci_msix_init
  - drivers/pci/msi/pcidev_msi.c:pci_msi_init
  - drivers/pci/pci-acpi.c:acpi_run_hpx
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:nvbridge_check_legacy_irq_routing
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffff817c1580-ffffffff817c1631: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u8 pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818ddcf0)
Location: drivers/pci/pci.c:491
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_cfg_space_size
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:_pci_add_cap_save_buffer
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/vpd.c:pci_vpd_init
  - drivers/pci/msi/pcidev_msi.c:pci_msix_init
  - drivers/pci/msi/pcidev_msi.c:pci_msi_init
  - drivers/pci/pci-acpi.c:acpi_run_hpx
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:nvbridge_check_legacy_irq_routing
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffff818ddcf0-ffffffff818ddda1: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u8 pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81921150)
Location: drivers/pci/pci.c:506
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_cfg_space_size
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:_pci_add_cap_save_buffer
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/vpd.c:pci_vpd_init
  - drivers/pci/msi/pcidev_msi.c:pci_msix_init
  - drivers/pci/msi/pcidev_msi.c:pci_msi_init
  - drivers/pci/pci-acpi.c:acpi_run_hpx
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:nvbridge_check_legacy_irq_routing
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffff81921150-ffffffff81921201: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u8 pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff819692f0)
Location: drivers/pci/pci.c:506
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_cfg_space_size
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/probe.c:pci_set_bus_speed
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:_pci_add_cap_save_buffer
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/vpd.c:pci_vpd_init
  - drivers/pci/msi/pcidev_msi.c:pci_msix_init
  - drivers/pci/msi/pcidev_msi.c:pci_msi_init
  - drivers/pci/pci-acpi.c:acpi_run_hpx
  - drivers/pci/pci-acpi.c:program_hpx_type3_register
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:nvbridge_check_legacy_irq_routing
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffff819692f0-ffffffff819693a1: pci_find_capability (STB_GLOBAL)
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
int pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e38c0)
Location: drivers/pci/pci.c:439
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/vpd.c:pci_vpd_init
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffff8000106e38c0-ffff8000106e3958: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087f770)
Location: drivers/pci/pci.c:439
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/vpd.c:pci_vpd_init
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
c087f770-c087f808: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085da20)
Location: drivers/pci/pci.c:439
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/vpd.c:pci_vpd_init
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
c00000000085da20-c00000000085dad0: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bae2e)
Location: drivers/pci/pci.c:439
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/vpd.c:pci_vpd_init
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffe0004bae2e-ffffffe0004bae98: pci_find_capability (STB_GLOBAL)
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
int pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81574ff0)
Location: drivers/pci/pci.c:439
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/vpd.c:pci_vpd_init
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffff81574ff0-ffffffff81575065: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81563750)
Location: drivers/pci/pci.c:439
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/vpd.c:pci_vpd_init
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
```
**Symbols:**

```
ffffffff81563750-ffffffff815637c5: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81574820)
Location: drivers/pci/pci.c:439
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/vpd.c:pci_vpd_init
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffff81574820-ffffffff81574895: pci_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_find_capability(struct pci_dev *dev, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158edf0)
Location: drivers/pci/pci.c:439
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:set_pcie_port_type
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_get_mmrbc
  - drivers/pci/pci.c:pcix_get_max_mmrbc
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_ea_init
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/vpd.c:pci_vpd_init
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/generic.c:agp_collect_device_status
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/char/agp/via-agp.c:agp_via_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffff8158edf0-ffffffff8158ee65: pci_find_capability (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>u8</code>
</li>
</ul>
</details>
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
