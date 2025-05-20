# Function: <code>strtobool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int strtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff813f1cd0)
Location: lib/string.c:642
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bint
  - fs/debugfs/file.c:debugfs_write_file_bool
  - drivers/pci/pcie/aspm.c:clk_ctl_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/base/core.c:device_store_bool
  - drivers/base/core.c:online_store
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/usb/core/hcd.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
ffffffff813f1cd0-ffffffff813f1d06: strtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81f818bb)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - init/main.c:set_debug_rodata
```
```
In arch/x86/xen/setup.c (ffffffff81f89700)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In kernel/params.c (ffffffff810a27dd)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In fs/debugfs/file.c (ffffffff81353b1a)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_write_file_bool
```
```
In drivers/pci/pcie/aspm.c (ffffffff81493a6c)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clk_ctl_store
```
```
In drivers/acpi/sysfs.c (ffffffff814d89d7)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:force_remove_store
```
```
In drivers/base/core.c (ffffffff8159ae7c)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
```
```
In drivers/nvdimm/region_devs.c (ffffffff815efbec)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff815f168c)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
```
In drivers/usb/core/hcd.c (ffffffff8166c4ac)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:interface_authorized_default_store
```
```
In drivers/usb/core/sysfs.c (ffffffff81678ffc)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
```
In drivers/powercap/powercap_sys.c (ffffffff8175694c)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:enabled_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81fbd8ec)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - init/main.c:set_debug_rodata
```
```
In arch/x86/xen/setup.c (ffffffff81fc4af4)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In kernel/params.c (ffffffff810a789d)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In fs/debugfs/file.c (ffffffff81369dca)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_write_file_bool
```
```
In drivers/pci/pcie/aspm.c (ffffffff814b53fc)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clk_ctl_store
```
```
In drivers/acpi/sysfs.c (ffffffff814fb0b6)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:force_remove_store
```
```
In drivers/base/core.c (ffffffff815c93dc)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
```
```
In drivers/nvdimm/region_devs.c (ffffffff8161cdcc)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8161ee0c)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
```
In drivers/usb/core/hcd.c (ffffffff8169a1ac)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:interface_authorized_default_store
```
```
In drivers/usb/core/sysfs.c (ffffffff816a6cdc)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
```
In drivers/powercap/powercap_sys.c (ffffffff81782f2c)
Location: include/linux/string.h:132
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:enabled_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8209d915)
Location: include/linux/string.h:147
Inline: True
Inline callers:
  - init/main.c:set_debug_rodata
```
```
In arch/x86/xen/setup.c (ffffffff820a4933)
Location: include/linux/string.h:147
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In kernel/params.c (ffffffff810a48ed)
Location: include/linux/string.h:147
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In fs/debugfs/file.c (ffffffff8137e438)
Location: include/linux/string.h:147
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_write_file_bool
```
```
In drivers/pci/pcie/aspm.c (ffffffff814bfafc)
Location: include/linux/string.h:147
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clk_ctl_store
```
```
In drivers/acpi/sysfs.c (ffffffff8150a6a6)
Location: include/linux/string.h:147
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:force_remove_store
```
```
In drivers/iommu/iommu.c (ffffffff820f40e2)
Location: include/linux/string.h:147
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
```
```
In drivers/base/core.c (ffffffff815de0fc)
Location: include/linux/string.h:147
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
```
```
In drivers/nvdimm/region_devs.c (ffffffff81630f5c)
Location: include/linux/string.h:147
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:deep_flush_store
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8163320c)
Location: include/linux/string.h:147
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
```
In drivers/dax/super.c (ffffffff8163cffe)
Location: include/linux/string.h:147
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_store
```
```
In drivers/usb/core/hcd.c (ffffffff816af46c)
Location: include/linux/string.h:147
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:interface_authorized_default_store
```
```
In drivers/usb/core/sysfs.c (ffffffff816bc03c)
Location: include/linux/string.h:147
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
```
In drivers/powercap/powercap_sys.c (ffffffff817a1cec)
Location: include/linux/string.h:147
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:enabled_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff826a38bb)
Location: include/linux/string.h:178
Inline: True
Inline callers:
  - init/main.c:set_debug_rodata
```
```
In arch/x86/xen/setup.c (ffffffff826ab02a)
Location: include/linux/string.h:178
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In kernel/params.c (ffffffff810aaf3d)
Location: include/linux/string.h:178
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In fs/debugfs/file.c (ffffffff813a3065)
Location: include/linux/string.h:178
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_write_file_bool
```
```
In drivers/pci/pcie/aspm.c (ffffffff814ffe7c)
Location: include/linux/string.h:178
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clk_ctl_store
```
```
In drivers/acpi/sysfs.c (ffffffff8154cf66)
Location: include/linux/string.h:178
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:force_remove_store
```
```
In drivers/iommu/iommu.c (ffffffff826fd797)
Location: include/linux/string.h:178
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
```
```
In drivers/base/core.c (ffffffff816450fc)
Location: include/linux/string.h:178
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
```
```
In drivers/nvdimm/region_devs.c (ffffffff8169978c)
Location: include/linux/string.h:178
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:deep_flush_store
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8169bb7c)
Location: include/linux/string.h:178
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
```
In drivers/dax/super.c (ffffffff816a5d8e)
Location: include/linux/string.h:178
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_store
```
```
In drivers/usb/core/hcd.c (ffffffff8171aa9c)
Location: include/linux/string.h:178
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:interface_authorized_default_store
```
```
In drivers/usb/core/sysfs.c (ffffffff817279fc)
Location: include/linux/string.h:178
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
```
In drivers/powercap/powercap_sys.c (ffffffff81818e0c)
Location: include/linux/string.h:178
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:enabled_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff826ccba7)
Location: include/linux/string.h:179
Inline: True
Inline callers:
  - init/main.c:set_debug_rodata
```
```
In arch/x86/xen/setup.c (ffffffff826d41a9)
Location: include/linux/string.h:179
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In kernel/params.c (ffffffff810b1a12)
Location: include/linux/string.h:179
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In mm/page_poison.c (ffffffff82708d0b)
Location: include/linux/string.h:179
Inline: True
Inline callers:
  - mm/page_poison.c:early_page_poison_param
```
```
In drivers/pci/pcie/aspm.c (ffffffff81531a7c)
Location: include/linux/string.h:179
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clk_ctl_store
```
```
In drivers/acpi/sysfs.c (ffffffff815836e7)
Location: include/linux/string.h:179
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:force_remove_store
```
```
In drivers/base/core.c (ffffffff8168055c)
Location: include/linux/string.h:179
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
```
```
In drivers/nvdimm/region_devs.c (ffffffff816d5a3c)
Location: include/linux/string.h:179
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:deep_flush_store
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816d7fcc)
Location: include/linux/string.h:179
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
```
In drivers/dax/super.c (ffffffff816e22fe)
Location: include/linux/string.h:179
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_store
```
```
In drivers/usb/core/hcd.c (ffffffff817597fd)
Location: include/linux/string.h:179
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:interface_authorized_default_store
```
```
In drivers/usb/core/sysfs.c (ffffffff8176687d)
Location: include/linux/string.h:179
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
```
In drivers/powercap/powercap_sys.c (ffffffff81862efc)
Location: include/linux/string.h:179
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:enabled_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82882afc)
Location: include/linux/string.h:186
Inline: True
Inline callers:
  - init/main.c:set_debug_rodata
```
```
In arch/x86/xen/setup.c (ffffffff8288a23c)
Location: include/linux/string.h:186
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In kernel/params.c (ffffffff810bab52)
Location: include/linux/string.h:186
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In mm/page_poison.c (ffffffff828bffb0)
Location: include/linux/string.h:186
Inline: True
Inline callers:
  - mm/page_poison.c:early_page_poison_param
```
```
In mm/usercopy.c (ffffffff828c2301)
Location: include/linux/string.h:186
Inline: True
Inline callers:
  - mm/usercopy.c:parse_hardened_usercopy
```
```
In drivers/pci/pcie/aspm.c (ffffffff8154905c)
Location: include/linux/string.h:186
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clk_ctl_store
```
```
In drivers/acpi/sysfs.c (ffffffff8159b817)
Location: include/linux/string.h:186
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:force_remove_store
```
```
In drivers/base/core.c (ffffffff8169ffec)
Location: include/linux/string.h:186
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
```
```
In drivers/nvdimm/region_devs.c (ffffffff816f77bc)
Location: include/linux/string.h:186
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:deep_flush_store
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816f9f3c)
Location: include/linux/string.h:186
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
```
In drivers/dax/super.c (ffffffff8170571e)
Location: include/linux/string.h:186
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_store
```
```
In drivers/usb/core/hcd.c (ffffffff8177dd6d)
Location: include/linux/string.h:186
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:interface_authorized_default_store
```
```
In drivers/usb/core/sysfs.c (ffffffff8178adfd)
Location: include/linux/string.h:186
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
```
In drivers/powercap/powercap_sys.c (ffffffff8188268c)
Location: include/linux/string.h:186
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:enabled_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82899a81)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - init/main.c:set_debug_rodata
```
```
In arch/x86/xen/setup.c (ffffffff828a15ea)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In kernel/params.c (ffffffff810c0a72)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In mm/page_poison.c (ffffffff828d9321)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - mm/page_poison.c:early_page_poison_param
```
```
In mm/usercopy.c (ffffffff828db737)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - mm/usercopy.c:parse_hardened_usercopy
```
```
In drivers/pci/pcie/aspm.c (ffffffff815791cc)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clk_ctl_store
```
```
In drivers/acpi/sysfs.c (ffffffff815cce97)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:force_remove_store
```
```
In drivers/base/core.c (ffffffff816d875c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
```
```
In drivers/nvdimm/region_devs.c (ffffffff81730f6c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff817339fc)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
```
In drivers/dax/super.c (ffffffff8173f2be)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_store
```
```
In drivers/usb/core/sysfs.c (ffffffff817c93b0)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
```
In drivers/powercap/powercap_sys.c (ffffffff818cccec)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:enabled_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8289ca81)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - init/main.c:set_debug_rodata
```
```
In arch/x86/xen/setup.c (ffffffff828a46aa)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828c82e5)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:setup_bau
```
```
In kernel/params.c (ffffffff810c6e72)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In mm/page_poison.c (ffffffff828e1774)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - mm/page_poison.c:early_page_poison_param
```
```
In mm/usercopy.c (ffffffff828e3b6d)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - mm/usercopy.c:parse_hardened_usercopy
```
```
In drivers/pci/pcie/aspm.c (ffffffff8159aa3d)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
```
```
In drivers/acpi/sysfs.c (ffffffff815ee117)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:force_remove_store
```
```
In drivers/base/core.c (ffffffff816fc85c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
```
```
In drivers/nvdimm/region_devs.c (ffffffff8175505c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff817576cc)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
```
In drivers/dax/super.c (ffffffff8176349e)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_store
```
```
In drivers/usb/core/sysfs.c (ffffffff817f9ef0)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
```
In drivers/powercap/powercap_sys.c (ffffffff818ff0dc)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:enabled_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82cc2c12)
Location: include/linux/string.h:194
Inline: True
Inline callers:
  - init/main.c:set_debug_rodata
```
```
In arch/x86/xen/setup.c (ffffffff82ccaacf)
Location: include/linux/string.h:194
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff82ceb3e4)
Location: include/linux/string.h:194
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:setup_bau
```
```
In kernel/params.c (ffffffff810cee72)
Location: include/linux/string.h:194
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In mm/page_poison.c (ffffffff82cfed33)
Location: include/linux/string.h:194
Inline: True
Inline callers:
  - mm/page_poison.c:early_page_poison_param
```
```
In mm/usercopy.c (ffffffff82d00768)
Location: include/linux/string.h:194
Inline: True
Inline callers:
  - mm/usercopy.c:parse_hardened_usercopy
```
```
In drivers/pci/pcie/aspm.c (ffffffff8163993d)
Location: include/linux/string.h:194
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
```
```
In drivers/acpi/sysfs.c (ffffffff8169a7d7)
Location: include/linux/string.h:194
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:force_remove_store
```
```
In drivers/base/core.c (ffffffff817b61cc)
Location: include/linux/string.h:194
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
```
```
In drivers/nvdimm/region_devs.c (ffffffff81813d8c)
Location: include/linux/string.h:194
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81816f2c)
Location: include/linux/string.h:194
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
```
In drivers/dax/super.c (ffffffff8182333e)
Location: include/linux/string.h:194
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_store
```
```
In drivers/usb/core/sysfs.c (ffffffff818ca0e0)
Location: include/linux/string.h:194
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
```
In drivers/powercap/powercap_sys.c (ffffffff819d615c)
Location: include/linux/string.h:194
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:enabled_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82faf06f)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - init/main.c:set_debug_rodata
```
```
In arch/x86/xen/setup.c (ffffffff82fb693d)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In kernel/params.c (ffffffff810c99a2)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In mm/usercopy.c (ffffffff82fed12d)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - mm/usercopy.c:parse_hardened_usercopy
```
```
In drivers/pci/pcie/aspm.c (ffffffff816607ed)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
```
```
In drivers/acpi/sysfs.c (ffffffff816b7857)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:force_remove_store
```
```
In drivers/base/core.c (ffffffff817cb63c)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
```
```
In drivers/nvdimm/region_devs.c (ffffffff81822f7c)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8182607c)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
```
In drivers/dax/super.c (ffffffff8183206e)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_store
```
```
In drivers/usb/core/sysfs.c (ffffffff818d5230)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
```
In drivers/input/input.c (ffffffff81932132)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - drivers/input/input.c:inhibited_store
```
```
In drivers/powercap/powercap_sys.c (ffffffff819d557c)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:enabled_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff831b9132)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - init/main.c:set_debug_rodata
```
```
In init/initramfs.c (ffffffff831ba545)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - init/initramfs.c:initramfs_async_setup
```
```
In arch/x86/xen/setup.c (ffffffff831c1030)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In kernel/params.c (ffffffff810cb4b2)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In mm/usercopy.c (ffffffff831f795e)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - mm/usercopy.c:parse_hardened_usercopy
```
```
In drivers/pci/pcie/aspm.c (ffffffff81642ccd)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
```
```
In drivers/acpi/sysfs.c (ffffffff816998b7)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:force_remove_store
```
```
In drivers/base/core.c (ffffffff817aefac)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/base/core.c:fw_devlink_strict_setup
```
```
In drivers/nvdimm/region_devs.c (ffffffff818061cc)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff818093fc)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
```
In drivers/dax/super.c (ffffffff8181590e)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_store
```
```
In drivers/usb/core/sysfs.c (ffffffff818b87f0)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
```
In drivers/input/input.c (ffffffff819162e2)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - drivers/input/input.c:inhibited_store
```
```
In drivers/powercap/powercap_sys.c (ffffffff819bb64c)
Location: include/linux/string.h:188
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:enabled_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff832991cc)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - init/main.c:set_debug_rodata
```
```
In init/initramfs.c (ffffffff8329aa1d)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - init/initramfs.c:initramfs_async_setup
```
```
In arch/x86/xen/setup.c (ffffffff832a1a87)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In kernel/params.c (ffffffff810de864)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In mm/usercopy.c (ffffffff832de6c9)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - mm/usercopy.c:parse_hardened_usercopy
```
```
In drivers/pci/pcie/aspm.c (ffffffff816b3a0d)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
```
```
In drivers/acpi/sysfs.c (ffffffff8170f7c9)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:force_remove_store
```
```
In drivers/base/core.c (ffffffff818381be)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/base/core.c:fw_devlink_strict_setup
```
```
In drivers/nvdimm/region_devs.c (ffffffff818904de)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:deep_flush_store
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8189448e)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
```
In drivers/dax/super.c (ffffffff8189ffee)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_store
```
```
In drivers/usb/core/sysfs.c (ffffffff8194e2b2)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
```
In drivers/input/input.c (ffffffff819b8522)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - drivers/input/input.c:inhibited_store
```
```
In drivers/powercap/powercap_sys.c (ffffffff81a6b4e0)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:enabled_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff83448eb4)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - init/initramfs.c:initramfs_async_setup
```
```
In arch/x86/xen/setup.c (ffffffff83450aec)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In kernel/params.c (ffffffff810f88c8)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In mm/usercopy.c (ffffffff83493fa3)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - mm/usercopy.c:parse_hardened_usercopy
```
```
In drivers/acpi/sysfs.c (ffffffff8183e2dd)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:force_remove_store
```
```
In drivers/base/core.c (ffffffff8197a522)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/base/core.c:fw_devlink_strict_setup
```
```
In drivers/nvdimm/region_devs.c (ffffffff819da352)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:deep_flush_store
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff819de1f2)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
```
In drivers/usb/core/sysfs.c (ffffffff81aa7226)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
```
In drivers/input/input.c (ffffffff81b16106)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - drivers/input/input.c:inhibited_store
```
```
In drivers/powercap/powercap_sys.c (ffffffff81bdbf34)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:enabled_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff83e62b45)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - init/initramfs.c:initramfs_async_setup
```
```
In kernel/params.c (ffffffff8111b3a8)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In kernel/module/main.c (ffffffff811c7fce)
Location: include/linux/kstrtox.h:150
Inline: True
```
```
In drivers/nvdimm/region_devs.c (ffffffff81b55642)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:deep_flush_store
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81b59ac2)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81ba8b92)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:deep_flush_store
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81bad012)
Location: include/linux/kstrtox.h:150
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffff8000114309d0)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - init/main.c:set_debug_rodata
```
```
In arch/arm64/kernel/cpufeature.c (ffff800011435154)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - arch/arm64/kernel/cpufeature.c:early_enable_pseudo_nmi
  - arch/arm64/kernel/cpufeature.c:parse_kpti
```
```
In arch/arm64/mm/mmu.c (ffff80001143797c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:parse_rodata
```
```
In virt/kvm/arm/vgic/vgic-v3.c (ffff80001143a6a4)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v3.c:early_gicv4_enable
  - virt/kvm/arm/vgic/vgic-v3.c:early_common_trap_cfg
  - virt/kvm/arm/vgic/vgic-v3.c:early_group1_trap_cfg
  - virt/kvm/arm/vgic/vgic-v3.c:early_group0_trap_cfg
```
```
In kernel/params.c (ffff800010125d60)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In mm/page_poison.c (ffff80001145a94c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - mm/page_poison.c:early_page_poison_param
```
```
In mm/usercopy.c (ffff80001145d128)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - mm/usercopy.c:parse_hardened_usercopy
```
```
In drivers/irqchip/irq-gic.c (ffff800011471550)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gicv2_force_probe_cfg
```
```
In drivers/irqchip/irq-gic-v3.c (ffff8000114726b8)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gicv3_nolpi_cfg
```
```
In drivers/pci/pcie/aspm.c (ffff8000107023e0)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
```
```
In drivers/acpi/sysfs.c (ffff800010779698)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:force_remove_store
```
```
In drivers/base/core.c (ffff8000108e720c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
```
```
In drivers/nvdimm/region_devs.c (ffff800010956110)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
```
```
In drivers/nvdimm/namespace_devs.c (ffff800010958df4)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
```
In drivers/dax/super.c (ffff800010963814)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_store
```
```
In drivers/usb/core/sysfs.c (ffff800010a2b25c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
```
In drivers/clocksource/arm_arch_timer.c (ffff8000114a8ca8)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:early_evtstrm_cfg
```
```
In drivers/powercap/powercap_sys.c (ffff800010b8e8dc)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:enabled_store
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (c150098c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - init/main.c:set_debug_rodata
```
```
In kernel/params.c (c0378a5c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In mm/page_poison.c (c15335a4)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - mm/page_poison.c:early_page_poison_param
```
```
In mm/usercopy.c (c153554c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - mm/usercopy.c:parse_hardened_usercopy
```
```
In drivers/irqchip/irq-gic.c (c154ab30)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gicv2_force_probe_cfg
```
```
In drivers/irqchip/irq-gic-v3.c (c154b748)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gicv3_nolpi_cfg
```
```
In drivers/pci/pcie/aspm.c (c0899ea4)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
```
```
In drivers/base/core.c (c09d57f4)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
```
```
In drivers/dax/super.c (c0a3a4b8)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_store
```
```
In drivers/usb/core/sysfs.c (c0b00db0)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
```
In drivers/clocksource/arm_arch_timer.c (c15acd74)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:early_evtstrm_cfg
```
```
In drivers/powercap/powercap_sys.c (c0c7896c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:enabled_store
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
In kernel/params.c (c00000000016fec8)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In mm/page_poison.c (c000000001384aa0)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - mm/page_poison.c:early_page_poison_param
```
```
In mm/usercopy.c (c0000000013878a8)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - mm/usercopy.c:parse_hardened_usercopy
```
```
In drivers/base/core.c (c00000000097d430)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
```
```
In drivers/nvdimm/region_devs.c (c000000000a04054)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:deep_flush_store
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a08820)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
```
In drivers/dax/super.c (c000000000a19884)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_store
```
```
In drivers/usb/core/sysfs.c (c000000000ae8090)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
```
In drivers/powercap/powercap_sys.c (c000000000c6d144)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:enabled_store
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
In kernel/params.c (ffffffe0000dd916)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In mm/page_poison.c (ffffffe000018a7c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - mm/page_poison.c:early_page_poison_param
```
```
In mm/usercopy.c (ffffffe00001a0ac)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - mm/usercopy.c:parse_hardened_usercopy
```
```
In drivers/pci/pcie/aspm.c (ffffffe0004d1060)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
```
```
In drivers/base/core.c (ffffffe00057b9f2)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
```
```
In drivers/nvdimm/region_devs.c (ffffffe0005c5522)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005c7f74)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
```
In drivers/dax/super.c (ffffffe0005d088a)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_store
```
```
In drivers/usb/core/sysfs.c (ffffffe00064c846)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
```
In drivers/powercap/powercap_sys.c (ffffffe00073480a)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:enabled_store
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8288aa81)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - init/main.c:set_debug_rodata
```
```
In arch/x86/xen/setup.c (ffffffff828926d0)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In kernel/params.c (ffffffff810c11f2)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In mm/page_poison.c (ffffffff828ca628)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - mm/page_poison.c:early_page_poison_param
```
```
In mm/usercopy.c (ffffffff828cca21)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - mm/usercopy.c:parse_hardened_usercopy
```
```
In drivers/pci/pcie/aspm.c (ffffffff8158e8cd)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
```
```
In drivers/acpi/sysfs.c (ffffffff815dce67)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:force_remove_store
```
```
In drivers/base/core.c (ffffffff816c204c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
```
```
In drivers/nvdimm/region_devs.c (ffffffff8170974c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170bdbc)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
```
In drivers/dax/super.c (ffffffff81717b8e)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_store
```
```
In drivers/usb/core/sysfs.c (ffffffff817b22d0)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82888a25)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - init/main.c:set_debug_rodata
```
```
In kernel/params.c (ffffffff810af9e2)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In mm/page_poison.c (ffffffff828c2d4d)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - mm/page_poison.c:early_page_poison_param
```
```
In mm/usercopy.c (ffffffff828c513d)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - mm/usercopy.c:parse_hardened_usercopy
```
```
In drivers/pci/pcie/aspm.c (ffffffff8157d40d)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
```
```
In drivers/acpi/sysfs.c (ffffffff815c84a7)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:force_remove_store
```
```
In drivers/base/core.c (ffffffff8169d2fc)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
```
```
In drivers/nvdimm/region_devs.c (ffffffff816dd1cc)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816df83c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
```
In drivers/dax/super.c (ffffffff816f00be)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_store
```
```
In drivers/usb/core/sysfs.c (ffffffff817a3d00)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8289da81)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - init/main.c:set_debug_rodata
```
```
In arch/x86/xen/setup.c (ffffffff828a56aa)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In kernel/params.c (ffffffff810c0742)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In mm/page_poison.c (ffffffff828dd3a8)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - mm/page_poison.c:early_page_poison_param
```
```
In mm/usercopy.c (ffffffff828df7a1)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - mm/usercopy.c:parse_hardened_usercopy
```
```
In drivers/pci/pcie/aspm.c (ffffffff8158e78d)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
```
```
In drivers/acpi/sysfs.c (ffffffff815e23f7)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:force_remove_store
```
```
In drivers/base/core.c (ffffffff816f051c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
```
```
In drivers/nvdimm/region_devs.c (ffffffff8174851c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174ab8c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
```
In drivers/dax/super.c (ffffffff8175695e)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_store
```
```
In drivers/usb/core/sysfs.c (ffffffff817eed70)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
```
In drivers/powercap/powercap_sys.c (ffffffff818efafc)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:enabled_store
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8289da81)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - init/main.c:set_debug_rodata
```
```
In arch/x86/xen/setup.c (ffffffff828a567e)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828c9322)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:setup_bau
```
```
In kernel/params.c (ffffffff810c8c12)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
```
```
In mm/page_poison.c (ffffffff828e27bf)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - mm/page_poison.c:early_page_poison_param
```
```
In mm/usercopy.c (ffffffff828e4bb8)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - mm/usercopy.c:parse_hardened_usercopy
```
```
In drivers/pci/pcie/aspm.c (ffffffff815a8c3d)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:clkpm_store
```
```
In drivers/acpi/sysfs.c (ffffffff815fc2b7)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:force_remove_store
```
```
In drivers/base/core.c (ffffffff8170ad5c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
```
```
In drivers/nvdimm/region_devs.c (ffffffff8176399c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:read_only_store
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8176600c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:force_raw_store
```
```
In drivers/dax/super.c (ffffffff81771dbe)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/dax/super.c:write_cache_store
```
```
In drivers/usb/core/sysfs.c (ffffffff81808fb0)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
```
```
In drivers/powercap/powercap_sys.c (ffffffff81910b7c)
Location: include/linux/string.h:193
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:enabled_store
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
