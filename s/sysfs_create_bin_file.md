# Function: <code>sysfs_create_bin_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8128cb60)
Location: fs/sysfs/file.c:480
Inline: True
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:load_module
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_install_table
  - drivers/base/core.c:device_create_bin_file
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
```
**Symbols:**

```
ffffffff8128cb60-ffffffff8128cb91: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff812ba1f0)
Location: fs/sysfs/file.c:486
Inline: True
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:load_module
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
  - drivers/sfi/sfi_core.c:sfi_sysfs_install_table
  - drivers/base/core.c:device_create_bin_file
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
```
**Symbols:**

```
ffffffff812ba1f0-ffffffff812ba221: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff812cf920)
Location: fs/sysfs/file.c:486
Inline: True
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:load_module
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_install_table
  - drivers/base/core.c:device_create_bin_file
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
```
**Symbols:**

```
ffffffff812cf920-ffffffff812cf951: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff812dd040)
Location: fs/sysfs/file.c:488
Inline: True
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:load_module
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_install_table
  - drivers/base/core.c:device_create_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_register
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
```
**Symbols:**

```
ffffffff812dd040-ffffffff812dd071: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81301970)
Location: fs/sysfs/file.c:488
Inline: True
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:load_module
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/acpi/sysfs.c:acpi_bert_data_init
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_install_table
  - drivers/base/core.c:device_create_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_register
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
```
**Symbols:**

```
ffffffff81301970-ffffffff813019a1: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8132f770)
Location: fs/sysfs/file.c:534
Inline: True
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files
  - drivers/acpi/sysfs.c:acpi_bert_data_init
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_install_table
  - drivers/base/core.c:device_create_bin_file
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
```
**Symbols:**

```
ffffffff8132f770-ffffffff8132f7f3: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81346b10)
Location: fs/sysfs/file.c:535
Inline: False
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files
  - drivers/acpi/sysfs.c:acpi_bert_data_init
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_install_table
  - drivers/base/core.c:device_create_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_register
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
```
**Symbols:**

```
ffffffff81346b10-ffffffff81346b9b: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/file.c (0)
Location: fs/sysfs/file.c:535
Inline: False
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files
  - drivers/acpi/sysfs.c:acpi_bert_data_init
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_install_table
  - drivers/base/core.c:device_create_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_register
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
```
**Symbols:**

```
ffffffff8136ef33-ffffffff8136ef4b: sysfs_create_bin_file.cold (STB_LOCAL)
ffffffff8136ee20-ffffffff8136eeae: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81387120)
Location: fs/sysfs/file.c:535
Inline: False
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files
  - drivers/acpi/sysfs.c:acpi_bert_data_init
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_install_table
  - drivers/base/core.c:device_create_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_register
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
```
**Symbols:**

```
ffffffff81387120-ffffffff813871ab: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813d1e00)
Location: fs/sysfs/file.c:536
Inline: False
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:add_notes_attrs
  - kernel/bpf/sysfs_btf.c:btf_vmlinux_init
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files
  - drivers/acpi/sysfs.c:acpi_bert_data_init
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_install_table
  - drivers/base/core.c:device_create_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_register
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:create_efivars_bin_attributes
  - drivers/firmware/efi/efivars.c:create_efivars_bin_attributes
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
```
**Symbols:**

```
ffffffff813d1e00-ffffffff813d1e8b: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813e3b60)
Location: fs/sysfs/file.c:537
Inline: False
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:add_notes_attrs
  - kernel/bpf/sysfs_btf.c:btf_vmlinux_init
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files
  - drivers/acpi/sysfs.c:acpi_bert_data_init
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_install_table
  - drivers/base/core.c:device_create_bin_file
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:create_efivars_bin_attributes
  - drivers/firmware/efi/efivars.c:create_efivars_bin_attributes
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
```
**Symbols:**

```
ffffffff813e3b60-ffffffff813e3beb: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813ea770)
Location: fs/sysfs/file.c:548
Inline: False
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:add_notes_attrs
  - kernel/bpf/sysfs_btf.c:btf_vmlinux_init
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/acpi/sysfs.c:acpi_bert_data_init
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/base/core.c:device_create_bin_file
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
```
**Symbols:**

```
ffffffff813ea770-ffffffff813ea7fb: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8143c4f0)
Location: fs/sysfs/file.c:548
Inline: False
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:add_notes_attrs
  - kernel/bpf/sysfs_btf.c:btf_vmlinux_init
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/acpi/sysfs.c:acpi_bert_data_init
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/base/core.c:device_create_bin_file
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
```
**Symbols:**

```
ffffffff8143c4f0-ffffffff8143c57b: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff814b7b00)
Location: fs/sysfs/file.c:558
Inline: False
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/bpf/btf.c:btf_module_notify
  - kernel/bpf/sysfs_btf.c:btf_vmlinux_init
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/acpi/sysfs.c:acpi_bert_data_init
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/base/core.c:device_create_bin_file
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
```
**Symbols:**

```
ffffffff814b7b00-ffffffff814b7ba5: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8154efb0)
Location: fs/sysfs/file.c:558
Inline: False
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/bpf/btf.c:btf_module_notify
  - kernel/bpf/sysfs_btf.c:btf_vmlinux_init
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/acpi/sysfs.c:acpi_bert_data_init
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/base/core.c:device_create_bin_file
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
```
**Symbols:**

```
ffffffff8154efb0-ffffffff8154f055: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81586c80)
Location: fs/sysfs/file.c:558
Inline: False
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/bpf/btf.c:btf_module_notify
  - kernel/bpf/sysfs_btf.c:btf_vmlinux_init
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/acpi/sysfs.c:acpi_ccel_data_init
  - drivers/acpi/sysfs.c:acpi_bert_data_init
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/base/core.c:device_create_bin_file
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
```
**Symbols:**

```
ffffffff81586c80-ffffffff81586d25: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff815bf7e0)
Location: fs/sysfs/file.c:571
Inline: False
Direct callers:
  - init/initramfs.c:do_populate_rootfs
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/bpf/btf.c:btf_module_notify
  - kernel/bpf/sysfs_btf.c:btf_vmlinux_init
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/acpi/sysfs.c:acpi_ccel_data_init
  - drivers/acpi/sysfs.c:acpi_bert_data_init
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/base/core.c:device_create_bin_file
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
```
**Symbols:**

```
ffffffff815bf7e0-ffffffff815bf885: sysfs_create_bin_file (STB_GLOBAL)
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
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffff800010456eb0)
Location: fs/sysfs/file.c:535
Inline: False
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files
  - drivers/acpi/sysfs.c:acpi_bert_data_init
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/base/core.c:device_create_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_register
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/of/kobj.c:__of_add_property_sysfs
  - drivers/of/fdt.c:of_fdt_raw_init
```
**Symbols:**

```
ffff800010456eb0-ffff800010456f54: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (c0618ea0)
Location: fs/sysfs/file.c:535
Inline: False
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files
  - drivers/base/core.c:device_create_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_register
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/of/kobj.c:__of_add_property_sysfs
  - drivers/of/fdt.c:of_fdt_raw_init
```
**Symbols:**

```
c0618ea0-c0618f6c: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (c000000000571130)
Location: fs/sysfs/file.c:535
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/opal.c:opal_init
  - arch/powerpc/platforms/powernv/opal.c:opal_init
  - arch/powerpc/platforms/powernv/opal-flash.c:opal_flash_update_init
  - arch/powerpc/platforms/powernv/opal-elog.c:elog_event
  - arch/powerpc/platforms/powernv/opal-dump.c:process_dump
  - arch/powerpc/platforms/powernv/opal-msglog.c:opal_msglog_sysfs_init
  - arch/powerpc/platforms/powernv/ultravisor.c:__machine_initcall_powernv_uv_init
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files
  - drivers/base/core.c:device_create_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_register
  - drivers/of/kobj.c:__of_add_property_sysfs
  - drivers/of/fdt.c:of_fdt_raw_init
```
**Symbols:**

```
c000000000571130-c00000000057120c: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffe0002e84a6)
Location: fs/sysfs/file.c:535
Inline: False
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files
  - drivers/base/core.c:device_create_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_register
  - drivers/of/kobj.c:__of_add_property_sysfs
  - drivers/of/fdt.c:of_fdt_raw_init
```
**Symbols:**

```
ffffffe0002e84a6-ffffffe0002e8514: sysfs_create_bin_file (STB_GLOBAL)
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
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8137f700)
Location: fs/sysfs/file.c:535
Inline: False
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files
  - drivers/acpi/sysfs.c:acpi_bert_data_init
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_install_table
  - drivers/base/core.c:device_create_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_register
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
```
**Symbols:**

```
ffffffff8137f700-ffffffff8137f78b: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81370190)
Location: fs/sysfs/file.c:535
Inline: False
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files
  - drivers/acpi/sysfs.c:acpi_bert_data_init
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_install_table
  - drivers/base/core.c:device_create_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_register
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
```
**Symbols:**

```
ffffffff81370190-ffffffff8137021b: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8137d1d0)
Location: fs/sysfs/file.c:535
Inline: False
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files
  - drivers/acpi/sysfs.c:acpi_bert_data_init
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_install_table
  - drivers/base/core.c:device_create_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_register
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
```
**Symbols:**

```
ffffffff8137d1d0-ffffffff8137d25b: sysfs_create_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sysfs_create_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81390cb0)
Location: fs/sysfs/file.c:535
Inline: False
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files
  - drivers/acpi/sysfs.c:acpi_bert_data_init
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_install_table
  - drivers/base/core.c:device_create_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_register
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
```
**Symbols:**

```
ffffffff81390cb0-ffffffff81390d3b: sysfs_create_bin_file (STB_GLOBAL)
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
