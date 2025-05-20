# Function: <code>acpi_device_hid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8147f43c)
Location: drivers/acpi/scan.c:1147
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:find_powerf_dev
  - drivers/acpi/device_sysfs.c:acpi_device_hid_show
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff8147f43c-ffffffff8147f465: acpi_device_hid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814cdcbe)
Location: drivers/acpi/scan.c:1167
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:find_powerf_dev
  - drivers/acpi/device_sysfs.c:acpi_device_hid_show
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/iommu/amd_iommu.c:get_irq_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_get_dm_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:check_device
  - drivers/iommu/amd_iommu.c:get_alias
```
**Symbols:**

```
ffffffff814cdcbe-ffffffff814cdcee: acpi_device_hid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814efc0d)
Location: drivers/acpi/scan.c:1165
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:find_powerf_dev
  - drivers/acpi/device_sysfs.c:acpi_device_hid_show
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/iommu/amd_iommu.c:get_irq_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:check_device
  - drivers/iommu/amd_iommu.c:get_alias
```
**Symbols:**

```
ffffffff814efc0d-ffffffff814efc3d: acpi_device_hid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814fdfbe)
Location: drivers/acpi/scan.c:1156
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del
Direct callers:
  - drivers/acpi/sleep.c:find_powerf_dev
  - drivers/acpi/device_sysfs.c:acpi_device_hid_show
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/iommu/amd_iommu.c:get_irq_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:get_alias
```
**Symbols:**

```
ffffffff814fcd40-ffffffff814fcd70: acpi_device_hid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8153fdce)
Location: drivers/acpi/scan.c:1160
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del
Direct callers:
  - drivers/acpi/sleep.c:find_powerf_dev
  - drivers/acpi/device_sysfs.c:acpi_device_hid_show
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/iommu/amd_iommu.c:get_irq_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:get_alias
```
**Symbols:**

```
ffffffff8153ea90-ffffffff8153eac0: acpi_device_hid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81575d66)
Location: drivers/acpi/scan.c:1161
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del
Direct callers:
  - drivers/acpi/sleep.c:find_powerf_dev
  - drivers/acpi/device_sysfs.c:acpi_device_hid_show
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:get_alias
```
**Symbols:**

```
ffffffff815749d0-ffffffff81574a00: acpi_device_hid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8158d986)
Location: drivers/acpi/scan.c:1161
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del
Direct callers:
  - drivers/acpi/sleep.c:find_powerf_dev
  - drivers/acpi/device_sysfs.c:acpi_device_hid_show
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/acpi_lpss.c:hid_uid_match
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:get_alias
```
**Symbols:**

```
ffffffff8158c5f0-ffffffff8158c620: acpi_device_hid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815be793)
Location: drivers/acpi/scan.c:1159
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_hid_show
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/acpi_lpss.c:hid_uid_match
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:get_alias
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815bd3c0-ffffffff815bd3f2: acpi_device_hid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815dfa53)
Location: drivers/acpi/scan.c:1159
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_hid_show
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/acpi_lpss.c:hid_uid_match
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815de680-ffffffff815de6b2: acpi_device_hid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168b0ec)
Location: drivers/acpi/scan.c:1168
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del
Direct callers:
  - drivers/acpi/utils.c:acpi_dev_hid_uid_match
  - drivers/acpi/device_sysfs.c:acpi_device_hid_show
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff81689030-ffffffff81689062: acpi_device_hid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816a8d9f)
Location: drivers/acpi/scan.c:1237
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del
Direct callers:
  - drivers/acpi/utils.c:acpi_dev_hid_uid_match
  - drivers/acpi/device_sysfs.c:acpi_device_hid_show
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff816a6bc0-ffffffff816a6bf2: acpi_device_hid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168b54f)
Location: drivers/acpi/scan.c:1236
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del
Direct callers:
  - drivers/acpi/utils.c:acpi_dev_hid_uid_match
  - drivers/acpi/device_sysfs.c:hid_show
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff81689850-ffffffff81689882: acpi_device_hid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81700652)
Location: drivers/acpi/scan.c:1244
Inline: True
Inline callers:
  - drivers/acpi/scan.c:__acpi_device_add
  - drivers/acpi/scan.c:__acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del
Direct callers:
  - drivers/acpi/utils.c:acpi_dev_hid_uid_match
  - drivers/acpi/device_sysfs.c:hid_show
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff816fed50-ffffffff816fed82: acpi_device_hid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8182e27e)
Location: drivers/acpi/scan.c:1274
Inline: True
Inline callers:
  - drivers/acpi/scan.c:__acpi_device_add
  - drivers/acpi/scan.c:__acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del_work_fn
Direct callers:
  - drivers/pci/vgaarb.c:vga_is_boot_device
  - drivers/acpi/utils.c:acpi_dev_hid_uid_match
  - drivers/acpi/device_sysfs.c:hid_show
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff8182c6a0-ffffffff8182c6e2: acpi_device_hid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819617b9)
Location: drivers/acpi/scan.c:1257
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del_work_fn
Direct callers:
  - drivers/pci/vgaarb.c:vga_is_boot_device
  - drivers/acpi/utils.c:acpi_dev_hid_uid_match
  - drivers/acpi/device_sysfs.c:hid_show
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff8195f2e0-ffffffff8195f322: acpi_device_hid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a7bc9)
Location: drivers/acpi/scan.c:1259
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del_work_fn
Direct callers:
  - drivers/pci/vgaarb.c:vga_is_boot_device
  - drivers/acpi/utils.c:acpi_dev_hid_uid_match
  - drivers/acpi/device_sysfs.c:hid_show
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff819a56e0-ffffffff819a5722: acpi_device_hid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819f05b9)
Location: drivers/acpi/scan.c:1262
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del_work_fn
Direct callers:
  - drivers/pci/vgaarb.c:vga_is_boot_device
  - drivers/acpi/device_sysfs.c:hid_show
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:rlookup_amd_iommu
  - drivers/iommu/amd/iommu.c:rlookup_amd_iommu
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff819ee060-ffffffff819ee0a2: acpi_device_hid (STB_GLOBAL)
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
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffff80001076c1ac)
Location: drivers/acpi/scan.c:1159
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del
Direct callers:
  - drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe
  - drivers/acpi/device_sysfs.c:acpi_device_hid_show
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffff80001076aac0-ffff80001076ab10: acpi_device_hid (STB_GLOBAL)
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
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d1e63)
Location: drivers/acpi/scan.c:1159
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_hid_show
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815d0b60-ffffffff815d0b92: acpi_device_hid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815bba23)
Location: drivers/acpi/scan.c:1159
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_hid_show
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/acpi_lpss.c:hid_uid_match
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815ba720-ffffffff815ba752: acpi_device_hid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d3d33)
Location: drivers/acpi/scan.c:1159
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_hid_show
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/acpi_lpss.c:hid_uid_match
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815d2960-ffffffff815d2992: acpi_device_hid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_device_hid(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815edbf3)
Location: drivers/acpi/scan.c:1159
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_device_hid_show
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/acpi_lpss.c:hid_uid_match
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815ec820-ffffffff815ec852: acpi_device_hid (STB_GLOBAL)
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
