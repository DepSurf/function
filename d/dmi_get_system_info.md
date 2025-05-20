# Function: <code>dmi_get_system_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff816ceec0)
Location: drivers/firmware/dmi_scan.c:830
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/pci/quirks.c:nvenet_msi_disable
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
  - drivers/firmware/dmi-id.c:get_modalias
```
**Symbols:**

```
ffffffff816ceec0-ffffffff816ceed6: dmi_get_system_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff817325a5)
Location: drivers/firmware/dmi_scan.c:852
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/pci/quirks.c:nvenet_msi_disable
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
ffffffff81732220-ffffffff81732236: dmi_get_system_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81765575)
Location: drivers/firmware/dmi_scan.c:852
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/pci/quirks.c:nvenet_msi_disable
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
ffffffff817651f0-ffffffff81765206: dmi_get_system_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81783d15)
Location: drivers/firmware/dmi_scan.c:877
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
ffffffff81783a20-ffffffff81783a36: dmi_get_system_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff817fa0e5)
Location: drivers/firmware/dmi_scan.c:877
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/video/fbdev/core/fbcon_dmi_quirks.c:fbcon_platform_get_rotate
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
ffffffff817f9df0-ffffffff817f9e06: dmi_get_system_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff818435c5)
Location: drivers/firmware/dmi_scan.c:895
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_prepare_identity_map
  - drivers/iommu/intel-iommu.c:domain_prepare_identity_map
  - drivers/iommu/intel-iommu.c:domain_prepare_identity_map
  - drivers/iommu/intel-iommu.c:domain_prepare_identity_map
  - drivers/iommu/intel-iommu.c:domain_prepare_identity_map
  - drivers/iommu/intel-iommu.c:domain_prepare_identity_map
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
ffffffff81843440-ffffffff81843456: dmi_get_system_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff8186f645)
Location: drivers/firmware/dmi_scan.c:895
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_prepare_identity_map
  - drivers/iommu/intel-iommu.c:domain_prepare_identity_map
  - drivers/iommu/intel-iommu.c:domain_prepare_identity_map
  - drivers/iommu/intel-iommu.c:domain_prepare_identity_map
  - drivers/iommu/intel-iommu.c:domain_prepare_identity_map
  - drivers/iommu/intel-iommu.c:domain_prepare_identity_map
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
ffffffff8186f450-ffffffff8186f466: dmi_get_system_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff818b3935)
Location: drivers/firmware/dmi_scan.c:898
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
ffffffff818b3760-ffffffff818b3776: dmi_get_system_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff818e6255)
Location: drivers/firmware/dmi_scan.c:898
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
ffffffff818e6080-ffffffff818e6096: dmi_get_system_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff819b95a5)
Location: drivers/firmware/dmi_scan.c:934
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_quirks
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check
  - drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
ffffffff819b9330-ffffffff819b9346: dmi_get_system_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff819bba15)
Location: drivers/firmware/dmi_scan.c:934
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_quirks
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check
  - drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
ffffffff819bb7a0-ffffffff819bb7b6: dmi_get_system_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff819a0225)
Location: drivers/firmware/dmi_scan.c:935
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_quirks
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
ffffffff8199ffb0-ffffffff8199ffc6: dmi_get_system_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81a4cef5)
Location: drivers/firmware/dmi_scan.c:935
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_quirks
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
ffffffff81a4cc60-ffffffff81a4cc92: dmi_get_system_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81bbb725)
Location: drivers/firmware/dmi_scan.c:935
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_quirks
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/host/uhci-hcd.c:uhci_pci_global_suspend_mode_is_broken
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
ffffffff81bbb420-ffffffff81bbb45a: dmi_get_system_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81d60e75)
Location: drivers/firmware/dmi_scan.c:941
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_quirks
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/host/uhci-hcd.c:uhci_pci_global_suspend_mode_is_broken
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
ffffffff81d60b40-ffffffff81d60b7a: dmi_get_system_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81dcbf45)
Location: drivers/firmware/dmi_scan.c:941
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_quirks
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/host/uhci-hcd.c:uhci_pci_global_suspend_mode_is_broken
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
ffffffff81dcbc20-ffffffff81dcbc5a: dmi_get_system_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81e84a85)
Location: drivers/firmware/dmi_scan.c:941
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_quirks
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/host/uhci-hcd.c:uhci_pci_global_suspend_mode_is_broken
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:dmi_id_init_attr_table
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
ffffffff81e84760-ffffffff81e8479a: dmi_get_system_info (STB_GLOBAL)
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
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffff800010b4d9e4)
Location: drivers/firmware/dmi_scan.c:898
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
ffff800010b4d708-ffff800010b4d73c: dmi_get_system_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (c0c34a90)
Location: drivers/firmware/dmi_scan.c:898
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
c0c34844-c0c3486c: dmi_get_system_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: include/linux/dmi.h:120
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/dmi.h:120
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/dmi.h:120
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: include/linux/dmi.h:120
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/dmi.h:120
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/dmi.h:120
Inline: True
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
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81888fd5)
Location: drivers/firmware/dmi_scan.c:898
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
ffffffff81888e00-ffffffff81888e16: dmi_get_system_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81840955)
Location: drivers/firmware/dmi_scan.c:898
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
ffffffff81840780-ffffffff81840796: dmi_get_system_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff818db0b5)
Location: drivers/firmware/dmi_scan.c:898
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
ffffffff818daee0-ffffffff818daef6: dmi_get_system_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const char *dmi_get_system_info(int field);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff818f7bd5)
Location: drivers/firmware/dmi_scan.c:898
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_match
  - drivers/firmware/dmi_scan.c:dmi_get_date
Direct callers:
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/usb/host/xhci.c:xhci_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/dmi-id.c:get_modalias
  - drivers/firmware/dmi-id.c:sys_dmi_field_show
```
**Symbols:**

```
ffffffff818f7a00-ffffffff818f7a16: dmi_get_system_info (STB_GLOBAL)
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
