# Function: <code>acpi_check_dsm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const u8 *uuid, int rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8147b033)
Location: drivers/acpi/utils.c:680
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/iommu/dmar.c:dmar_get_dsm_handle
  - drivers/iommu/dmar.c:dmar_device_hotplug
```
**Symbols:**

```
ffffffff8147b033-ffffffff8147b0b3: acpi_check_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const u8 *uuid, u64 rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814c963d)
Location: drivers/acpi/utils.c:677
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/iommu/dmar.c:dmar_get_dsm_handle
```
**Symbols:**

```
ffffffff814c963d-ffffffff814c96bb: acpi_check_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const u8 *uuid, u64 rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814eb581)
Location: drivers/acpi/utils.c:677
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/iommu/dmar.c:dmar_get_dsm_handle
```
**Symbols:**

```
ffffffff814eb581-ffffffff814eb5ff: acpi_check_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814f7720)
Location: drivers/acpi/utils.c:677
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/iommu/dmar.c:dmar_get_dsm_handle
```
**Symbols:**

```
ffffffff814f7720-ffffffff814f77c1: acpi_check_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815389c0)
Location: drivers/acpi/utils.c:678
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/iommu/dmar.c:dmar_get_dsm_handle
```
**Symbols:**

```
ffffffff815389c0-ffffffff81538a61: acpi_check_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8156e780)
Location: drivers/acpi/utils.c:678
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/iommu/dmar.c:dmar_get_dsm_handle
```
**Symbols:**

```
ffffffff8156e780-ffffffff8156e820: acpi_check_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81586340)
Location: drivers/acpi/utils.c:678
Inline: True
Direct callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/iommu/dmar.c:dmar_get_dsm_handle
```
**Symbols:**

```
ffffffff81586340-ffffffff815863e0: acpi_check_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b6fd0)
Location: drivers/acpi/utils.c:665
Inline: True
Direct callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/iommu/dmar.c:dmar_get_dsm_handle
```
**Symbols:**

```
ffffffff815b6fd0-ffffffff815b706c: acpi_check_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815d8200)
Location: drivers/acpi/utils.c:665
Inline: True
Direct callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/iommu/dmar.c:dmar_get_dsm_handle
```
**Symbols:**

```
ffffffff815d8200-ffffffff815d829c: acpi_check_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81682190)
Location: drivers/acpi/utils.c:697
Inline: True
Direct callers:
  - drivers/pci/pci-label.c:acpi_index_string_exist
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_get_dsm_handle
```
**Symbols:**

```
ffffffff81682190-ffffffff8168222c: acpi_check_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816a0950)
Location: drivers/acpi/utils.c:693
Inline: True
Direct callers:
  - drivers/pci/pci-label.c:acpi_index_string_exist
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_get_dsm_handle
```
**Symbols:**

```
ffffffff816a0950-ffffffff816a09ec: acpi_check_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816834c0)
Location: drivers/acpi/utils.c:687
Inline: True
Direct callers:
  - drivers/pci/pci-label.c:acpi_attr_is_visible
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_get_dsm_handle
```
**Symbols:**

```
ffffffff816834c0-ffffffff8168355c: acpi_check_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816f88e0)
Location: drivers/acpi/utils.c:701
Inline: True
Direct callers:
  - drivers/pci/pci-label.c:acpi_attr_is_visible
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_get_dsm_handle
```
**Symbols:**

```
ffffffff816f88e0-ffffffff816f897c: acpi_check_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81825150)
Location: drivers/acpi/utils.c:701
Inline: False
Direct callers:
  - drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/pci-label.c:acpi_attr_is_visible
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_get_dsm_handle
  - drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource
```
**Symbols:**

```
ffffffff81825150-ffffffff8182520d: acpi_check_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81956310)
Location: drivers/acpi/utils.c:739
Inline: False
Direct callers:
  - drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/pci-label.c:acpi_attr_is_visible
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_get_dsm_handle
  - drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource
  - drivers/usb/core/usb-acpi.c:usb_acpi_port_lpm_incapable
```
**Symbols:**

```
ffffffff81956310-ffffffff819563cd: acpi_check_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8199c710)
Location: drivers/acpi/utils.c:739
Inline: False
Direct callers:
  - drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/pci-label.c:acpi_attr_is_visible
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_get_dsm_handle
  - drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource
  - drivers/usb/core/usb-acpi.c:usb_acpi_port_lpm_incapable
```
**Symbols:**

```
ffffffff8199c710-ffffffff8199c7cd: acpi_check_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819e5740)
Location: drivers/acpi/utils.c:811
Inline: False
Direct callers:
  - drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/pci-label.c:acpi_attr_is_visible
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/iommu/intel/dmar.c:dmar_get_dsm_handle
  - drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource
  - drivers/usb/core/usb-acpi.c:usb_acpi_port_lpm_incapable
  - drivers/platform/x86/amd/wbrf.c:acpi_amd_wbrf_supported_consumer
  - drivers/platform/x86/amd/wbrf.c:acpi_amd_wbrf_supported_producer
```
**Symbols:**

```
ffffffff819e5740-ffffffff819e57fd: acpi_check_dsm (STB_GLOBAL)
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
bool acpi_check_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffff800010765730)
Location: drivers/acpi/utils.c:665
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
```
**Symbols:**

```
ffff800010765730-ffff800010765820: acpi_check_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cb530)
Location: drivers/acpi/utils.c:665
Inline: True
Direct callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/iommu/dmar.c:dmar_get_dsm_handle
```
**Symbols:**

```
ffffffff815cb530-ffffffff815cb5cc: acpi_check_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b4580)
Location: drivers/acpi/utils.c:665
Inline: True
Direct callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_add_dimm
  - drivers/acpi/nfit/core.c:acpi_nfit_add_dimm
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/iommu/dmar.c:dmar_get_dsm_handle
```
**Symbols:**

```
ffffffff815b4580-ffffffff815b461c: acpi_check_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cc4e0)
Location: drivers/acpi/utils.c:665
Inline: True
Direct callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/iommu/dmar.c:dmar_get_dsm_handle
```
**Symbols:**

```
ffffffff815cc4e0-ffffffff815cc57c: acpi_check_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 funcs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815e6380)
Location: drivers/acpi/utils.c:665
Inline: True
Direct callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/iommu/dmar.c:dmar_get_dsm_handle
```
**Symbols:**

```
ffffffff815e6380-ffffffff815e641c: acpi_check_dsm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int rev</code> ➡️ <code>u64 rev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const guid_t *guid</code>
</li>
<li>
<b>Param removed. </b>
<code>const u8 *uuid</code>
</li>
</ul>
</details>
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
