# Function: <code>sysfs_remove_bin_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8128c760)
Location: fs/sysfs/file.c:494
Inline: False
Direct callers:
  - kernel/module.c:free_notes_attrs
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff8128c760-ffffffff8128c779: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff812b9df0)
Location: fs/sysfs/file.c:500
Inline: False
Direct callers:
  - kernel/module.c:free_notes_attrs
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff812b9df0-ffffffff812b9e09: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff812cf520)
Location: fs/sysfs/file.c:500
Inline: False
Direct callers:
  - kernel/module.c:free_notes_attrs
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff812cf520-ffffffff812cf539: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff812dcc60)
Location: fs/sysfs/file.c:502
Inline: False
Direct callers:
  - kernel/module.c:free_notes_attrs
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_unregister
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff812dcc60-ffffffff812dcc79: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81301570)
Location: fs/sysfs/file.c:502
Inline: False
Direct callers:
  - kernel/module.c:free_notes_attrs
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_unregister
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff81301570-ffffffff81301589: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8132f2b0)
Location: fs/sysfs/file.c:553
Inline: False
Direct callers:
  - kernel/module.c:free_notes_attrs
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/vpd.c:pcie_vpd_remove_sysfs_dev_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_unregister
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff8132f2b0-ffffffff8132f2c9: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81346670)
Location: fs/sysfs/file.c:555
Inline: False
Direct callers:
  - kernel/module.c:free_notes_attrs
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/vpd.c:pcie_vpd_remove_sysfs_dev_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_unregister
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff81346670-ffffffff81346689: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8136e990)
Location: fs/sysfs/file.c:555
Inline: False
Direct callers:
  - kernel/module.c:free_notes_attrs
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/vpd.c:pcie_vpd_remove_sysfs_dev_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_unregister
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff8136e990-ffffffff8136e9a9: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81386c10)
Location: fs/sysfs/file.c:555
Inline: False
Direct callers:
  - kernel/module.c:free_notes_attrs
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/vpd.c:pcie_vpd_remove_sysfs_dev_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_unregister
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff81386c10-ffffffff81386c29: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813d17a0)
Location: fs/sysfs/file.c:556
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:add_notes_attrs
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/vpd.c:pcie_vpd_remove_sysfs_dev_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_unregister
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:create_efivars_bin_attributes
```
**Symbols:**

```
ffffffff813d17a0-ffffffff813d17b9: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813e33a0)
Location: fs/sysfs/file.c:557
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:add_notes_attrs
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/vpd.c:pcie_vpd_remove_sysfs_dev_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:create_efivars_bin_attributes
```
**Symbols:**

```
ffffffff813e33a0-ffffffff813e33b9: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813e9fe0)
Location: fs/sysfs/file.c:568
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:add_notes_attrs
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff813e9fe0-ffffffff813e9ff9: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8143bd60)
Location: fs/sysfs/file.c:568
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:add_notes_attrs
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff8143bd60-ffffffff8143bd79: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff814b71c0)
Location: fs/sysfs/file.c:578
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/bpf/btf.c:btf_module_notify
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff814b71c0-ffffffff814b71e5: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8154e4e0)
Location: fs/sysfs/file.c:578
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/bpf/btf.c:btf_module_notify
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/firmware/dmi_scan.c:dmi_init
```
**Symbols:**

```
ffffffff8154e4e0-ffffffff8154e505: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff815861a0)
Location: fs/sysfs/file.c:578
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/bpf/btf.c:btf_module_notify
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/firmware/dmi_scan.c:dmi_init
```
**Symbols:**

```
ffffffff815861a0-ffffffff815861c5: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff815bec80)
Location: fs/sysfs/file.c:591
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/bpf/btf.c:btf_module_notify
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/firmware/dmi_scan.c:dmi_init
```
**Symbols:**

```
ffffffff815bec80-ffffffff815beca5: sysfs_remove_bin_file (STB_GLOBAL)
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
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffff800010456890)
Location: fs/sysfs/file.c:555
Inline: False
Direct callers:
  - kernel/module.c:free_notes_attrs
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/vpd.c:pcie_vpd_remove_sysfs_dev_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_unregister
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/of/kobj.c:__of_detach_node_sysfs
  - drivers/of/kobj.c:__of_update_property_sysfs
  - drivers/of/kobj.c:__of_remove_property_sysfs
```
**Symbols:**

```
ffff800010456890-ffff8000104568c8: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (c06188d0)
Location: fs/sysfs/file.c:555
Inline: False
Direct callers:
  - kernel/module.c:free_notes_attrs
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/vpd.c:pcie_vpd_remove_sysfs_dev_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_unregister
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/of/kobj.c:__of_detach_node_sysfs
  - drivers/of/kobj.c:__of_update_property_sysfs
  - drivers/of/kobj.c:__of_remove_property_sysfs
```
**Symbols:**

```
c06188d0-c06188f8: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (c000000000570810)
Location: fs/sysfs/file.c:555
Inline: False
Direct callers:
  - kernel/module.c:free_notes_attrs
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/vpd.c:pcie_vpd_remove_sysfs_dev_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_unregister
  - drivers/of/kobj.c:__of_detach_node_sysfs
  - drivers/of/kobj.c:__of_update_property_sysfs
  - drivers/of/kobj.c:__of_remove_property_sysfs
```
**Symbols:**

```
c000000000570810-c000000000570850: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffe0002e8014)
Location: fs/sysfs/file.c:555
Inline: False
Direct callers:
  - kernel/module.c:free_notes_attrs
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/vpd.c:pcie_vpd_remove_sysfs_dev_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_unregister
  - drivers/of/kobj.c:__of_detach_node_sysfs
  - drivers/of/kobj.c:__of_update_property_sysfs
  - drivers/of/kobj.c:__of_remove_property_sysfs
```
**Symbols:**

```
ffffffe0002e8014-ffffffe0002e804a: sysfs_remove_bin_file (STB_GLOBAL)
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
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8137f1f0)
Location: fs/sysfs/file.c:555
Inline: False
Direct callers:
  - kernel/module.c:free_notes_attrs
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/vpd.c:pcie_vpd_remove_sysfs_dev_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_unregister
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff8137f1f0-ffffffff8137f209: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8136fc80)
Location: fs/sysfs/file.c:555
Inline: False
Direct callers:
  - kernel/module.c:free_notes_attrs
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/vpd.c:pcie_vpd_remove_sysfs_dev_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_unregister
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff8136fc80-ffffffff8136fc99: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8137ccc0)
Location: fs/sysfs/file.c:555
Inline: False
Direct callers:
  - kernel/module.c:free_notes_attrs
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/vpd.c:pcie_vpd_remove_sysfs_dev_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_unregister
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff8137ccc0-ffffffff8137ccd9: sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sysfs_remove_bin_file(struct kobject *kobj, const struct bin_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813907a0)
Location: fs/sysfs/file.c:555
Inline: False
Direct callers:
  - kernel/module.c:free_notes_attrs
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/pci-sysfs.c:pci_remove_resource_files
  - drivers/pci/vpd.c:pcie_vpd_remove_sysfs_dev_files
  - drivers/base/core.c:device_remove_bin_file
  - drivers/rtc/nvmem.c:rtc_nvmem_unregister
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff813907a0-ffffffff813907b9: sysfs_remove_bin_file (STB_GLOBAL)
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
