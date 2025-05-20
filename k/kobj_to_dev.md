# Function: <code>kobj_to_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (0)
Location: include/linux/device.h:841
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/device.h:841
Inline: True
```
```
In drivers/xen/pcpu.c (0)
Location: include/linux/device.h:841
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/device.h:841
Inline: True
```
```
In drivers/base/core.c (ffffffff81546209)
Location: include/linux/device.h:841
Inline: True
Inline callers:
  - drivers/base/core.c:dev_attr_store
  - drivers/base/core.c:device_release
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/device.h:841
Inline: True
```
```
In drivers/base/firmware_class.c (0)
Location: include/linux/device.h:841
Inline: True
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/device.h:841
Inline: True
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (0)
Location: include/linux/device.h:857
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/device.h:857
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/device.h:857
Inline: True
```
```
In drivers/pci/pci-label.c (0)
Location: include/linux/device.h:857
Inline: True
```
```
In drivers/rapidio/rio-sysfs.c (0)
Location: include/linux/device.h:857
Inline: True
```
```
In drivers/xen/pcpu.c (0)
Location: include/linux/device.h:857
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/device.h:857
Inline: True
```
```
In drivers/base/core.c (ffffffff8159afae)
Location: include/linux/device.h:857
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:device_release
  - drivers/base/core.c:dev_attr_store
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/device.h:857
Inline: True
```
```
In drivers/base/firmware_class.c (0)
Location: include/linux/device.h:857
Inline: True
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/device.h:857
Inline: True
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (0)
Location: include/linux/device.h:966
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/device.h:966
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/device.h:966
Inline: True
```
```
In drivers/pci/pci-label.c (0)
Location: include/linux/device.h:966
Inline: True
```
```
In drivers/rapidio/rio-sysfs.c (0)
Location: include/linux/device.h:966
Inline: True
```
```
In drivers/xen/pcpu.c (0)
Location: include/linux/device.h:966
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/device.h:966
Inline: True
```
```
In drivers/base/core.c (ffffffff815c950e)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:device_release
  - drivers/base/core.c:dev_attr_store
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/device.h:966
Inline: True
```
```
In drivers/base/firmware_class.c (0)
Location: include/linux/device.h:966
Inline: True
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/device.h:966
Inline: True
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (0)
Location: include/linux/device.h:970
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/device.h:970
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/device.h:970
Inline: True
```
```
In drivers/pci/pci-label.c (0)
Location: include/linux/device.h:970
Inline: True
```
```
In drivers/rapidio/rio-sysfs.c (0)
Location: include/linux/device.h:970
Inline: True
```
```
In drivers/xen/pcpu.c (0)
Location: include/linux/device.h:970
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/device.h:970
Inline: True
```
```
In drivers/base/core.c (ffffffff815de22e)
Location: include/linux/device.h:970
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:device_release
  - drivers/base/core.c:dev_attr_store
  - drivers/base/core.c:dev_attr_show
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/device.h:970
Inline: True
```
```
In drivers/base/firmware_class.c (0)
Location: include/linux/device.h:970
Inline: True
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/device.h:970
Inline: True
```
```
In drivers/rtc/nvmem.c (ffffffff8171b3bb)
Location: include/linux/device.h:970
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:rtc_nvram_write
  - drivers/rtc/nvmem.c:rtc_nvram_read
```
```
In drivers/edac/edac_mc_sysfs.c (0)
Location: include/linux/device.h:970
Inline: True
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (0)
Location: include/linux/device.h:968
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/device.h:968
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/device.h:968
Inline: True
```
```
In drivers/pci/pci-label.c (0)
Location: include/linux/device.h:968
Inline: True
```
```
In drivers/rapidio/rio-sysfs.c (0)
Location: include/linux/device.h:968
Inline: True
```
```
In drivers/xen/pcpu.c (0)
Location: include/linux/device.h:968
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/device.h:968
Inline: True
```
```
In drivers/base/core.c (ffffffff8164522e)
Location: include/linux/device.h:968
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:device_release
  - drivers/base/core.c:dev_attr_store
  - drivers/base/core.c:dev_attr_show
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/device.h:968
Inline: True
```
```
In drivers/base/firmware_class.c (0)
Location: include/linux/device.h:968
Inline: True
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/device.h:968
Inline: True
```
```
In drivers/rtc/nvmem.c (ffffffff8178c65b)
Location: include/linux/device.h:968
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:rtc_nvram_write
  - drivers/rtc/nvmem.c:rtc_nvram_read
```
```
In drivers/edac/edac_mc_sysfs.c (0)
Location: include/linux/device.h:968
Inline: True
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810401d5)
Location: include/linux/device.h:1013
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
```
```
In block/genhd.c (0)
Location: include/linux/device.h:1013
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff81521fe5)
Location: include/linux/device.h:1013
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:sriov_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_hp_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/pci/pci-sysfs.c:pci_write_rom
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/pci/vpd.c (ffffffff81525275)
Location: include/linux/device.h:1013
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:read_vpd_attr
```
```
In drivers/pci/pci-label.c (ffffffff81545fa5)
Location: include/linux/device.h:1013
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:acpi_index_string_exist
  - drivers/pci/pci-label.c:smbios_instance_string_exist
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff8154d735)
Location: include/linux/device.h:1013
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_dev_is_attr_visible
  - drivers/rapidio/rio-sysfs.c:rio_write_config
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
```
In drivers/xen/pcpu.c (ffffffff81600605)
Location: include/linux/device.h:1013
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:pcpu_dev_is_visible
```
```
In drivers/regulator/core.c (ffffffff81605b55)
Location: include/linux/device.h:1013
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_attr_is_visible
```
```
In drivers/base/core.c (ffffffff81680678)
Location: include/linux/device.h:1013
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:device_get_ownership
  - drivers/base/core.c:device_namespace
  - drivers/base/core.c:device_release
  - drivers/base/core.c:dev_attr_store
  - drivers/base/core.c:dev_attr_show
  - drivers/base/core.c:device_links_unbind_consumers
```
```
In drivers/base/cacheinfo.c (ffffffff8168a1f5)
Location: include/linux/device.h:1013
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8169b485)
Location: include/linux/device.h:1013
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
```
In drivers/base/devcoredump.c (ffffffff816a8f55)
Location: include/linux/device.h:1013
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/base/devcoredump.c:devcd_data_read
```
```
In drivers/rtc/nvmem.c (ffffffff817cece4)
Location: include/linux/device.h:1013
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:rtc_nvram_write
  - drivers/rtc/nvmem.c:rtc_nvram_read
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff817dff15)
Location: include/linux/device.h:1013
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_is_attribute_visible
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff818197c5)
Location: include/linux/device.h:1013
Inline: True
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81041795)
Location: include/linux/device.h:1056
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
```
```
In block/genhd.c (0)
Location: include/linux/device.h:1056
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff81537e15)
Location: include/linux/device.h:1056
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:sriov_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_hp_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/pci/pci-sysfs.c:pci_write_rom
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/pci/vpd.c (ffffffff8153b105)
Location: include/linux/device.h:1056
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:read_vpd_attr
```
```
In drivers/pci/pcie/aer.c (ffffffff8154a285)
Location: include/linux/device.h:1056
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
```
```
In drivers/pci/pci-label.c (ffffffff8155c545)
Location: include/linux/device.h:1056
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:acpi_index_string_exist
  - drivers/pci/pci-label.c:smbios_instance_string_exist
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81564b75)
Location: include/linux/device.h:1056
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_dev_is_attr_visible
  - drivers/rapidio/rio-sysfs.c:rio_write_config
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
```
In drivers/xen/pcpu.c (ffffffff8161b6d5)
Location: include/linux/device.h:1056
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:pcpu_dev_is_visible
```
```
In drivers/regulator/core.c (ffffffff81620c35)
Location: include/linux/device.h:1056
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_attr_is_visible
```
```
In drivers/base/core.c (ffffffff816a0108)
Location: include/linux/device.h:1056
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:device_get_ownership
  - drivers/base/core.c:device_namespace
  - drivers/base/core.c:device_release
  - drivers/base/core.c:dev_attr_store
  - drivers/base/core.c:dev_attr_show
  - drivers/base/core.c:device_links_unbind_consumers
```
```
In drivers/base/cacheinfo.c (ffffffff816a96f5)
Location: include/linux/device.h:1056
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816bbd05)
Location: include/linux/device.h:1056
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
```
In drivers/base/devcoredump.c (ffffffff816c9b35)
Location: include/linux/device.h:1056
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/base/devcoredump.c:devcd_data_read
```
```
In drivers/rtc/nvmem.c (ffffffff817f5e10)
Location: include/linux/device.h:1056
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:rtc_nvram_write
  - drivers/rtc/nvmem.c:rtc_nvram_read
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff8180b4e5)
Location: include/linux/device.h:1056
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_is_attribute_visible
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff81845065)
Location: include/linux/device.h:1056
Inline: True
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81043c45)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
```
```
In block/genhd.c (0)
Location: include/linux/device.h:1079
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff81567815)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:sriov_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_hp_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/pci/pci-sysfs.c:pci_write_rom
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/pci/vpd.c (ffffffff8156ab95)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:read_vpd_attr
```
```
In drivers/pci/pcie/aer.c (ffffffff8157a405)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
```
```
In drivers/pci/pci-label.c (ffffffff8158c865)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:acpi_index_string_exist
  - drivers/pci/pci-label.c:smbios_instance_string_exist
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81594f15)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_dev_is_attr_visible
  - drivers/rapidio/rio-sysfs.c:rio_write_config
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
```
In drivers/xen/pcpu.c (ffffffff8164f355)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:pcpu_dev_is_visible
```
```
In drivers/regulator/core.c (ffffffff81654235)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_attr_is_visible
```
```
In drivers/base/core.c (ffffffff816d8819)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:device_get_ownership
  - drivers/base/core.c:device_namespace
  - drivers/base/core.c:device_release
  - drivers/base/core.c:dev_attr_store
  - drivers/base/core.c:dev_attr_show
  - drivers/base/core.c:device_links_unbind_consumers
```
```
In drivers/base/cacheinfo.c (ffffffff816e2d05)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816f64b5)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
```
In drivers/base/devcoredump.c (ffffffff817050e5)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/base/devcoredump.c:devcd_data_read
```
```
In drivers/rtc/nvmem.c (ffffffff81836c7a)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:rtc_nvram_write
  - drivers/rtc/nvmem.c:rtc_nvram_read
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff8184d1d5)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_is_attribute_visible
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff81887e45)
Location: include/linux/device.h:1079
Inline: True
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044395)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
```
```
In block/genhd.c (0)
Location: include/linux/device.h:1321
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff81588af5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_hp_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/pci/pci-sysfs.c:pci_write_rom
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/pci/vpd.c (ffffffff8158bb65)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:read_vpd_attr
```
```
In drivers/pci/pcie/aspm.c (ffffffff81599fb5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
```
```
In drivers/pci/pcie/aer.c (ffffffff8159be45)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
```
```
In drivers/pci/iov.c (ffffffff815aca85)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_attrs_are_visible
```
```
In drivers/pci/pci-label.c (ffffffff815ae485)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:acpi_index_string_exist
  - drivers/pci/pci-label.c:smbios_instance_string_exist
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815b6195)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_dev_is_attr_visible
  - drivers/rapidio/rio-sysfs.c:rio_write_config
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
```
In drivers/xen/pcpu.c (ffffffff81671905)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:pcpu_dev_is_visible
```
```
In drivers/regulator/core.c (ffffffff816767d5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_attr_is_visible
```
```
In drivers/base/core.c (ffffffff816fc91e)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:device_get_ownership
  - drivers/base/core.c:device_namespace
  - drivers/base/core.c:device_release
  - drivers/base/core.c:dev_attr_store
  - drivers/base/core.c:dev_attr_show
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/cacheinfo.c (ffffffff81706eb5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8171a8b5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
```
In drivers/base/devcoredump.c (ffffffff81729375)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/base/devcoredump.c:devcd_data_read
```
```
In drivers/input/input-poller.c (ffffffff8185a465)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_poller_attrs_visible
```
```
In drivers/rtc/nvmem.c (ffffffff818685ea)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:rtc_nvram_write
  - drivers/rtc/nvmem.c:rtc_nvram_read
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff8187ec15)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_is_attribute_visible
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff818b9e05)
Location: include/linux/device.h:1321
Inline: True
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048055)
Location: include/linux/device.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
```
```
In block/genhd.c (0)
Location: include/linux/device.h:628
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff8162fa65)
Location: include/linux/device.h:628
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_hp_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/pci/pci-sysfs.c:pci_write_rom
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/pci/vpd.c (ffffffff81632e45)
Location: include/linux/device.h:628
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:read_vpd_attr
```
```
In drivers/pci/pcie/aspm.c (ffffffff8163b185)
Location: include/linux/device.h:628
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
```
```
In drivers/pci/pcie/aer.c (ffffffff8163b975)
Location: include/linux/device.h:628
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
```
```
In drivers/pci/iov.c (ffffffff81655cb5)
Location: include/linux/device.h:628
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_attrs_are_visible
```
```
In drivers/pci/pci-label.c (ffffffff816579b5)
Location: include/linux/device.h:628
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:acpi_index_string_exist
  - drivers/pci/pci-label.c:smbios_instance_string_exist
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff8165fe45)
Location: include/linux/device.h:628
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_dev_is_attr_visible
  - drivers/rapidio/rio-sysfs.c:rio_write_config
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
```
In drivers/xen/pcpu.c (ffffffff81721fc5)
Location: include/linux/device.h:628
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:pcpu_dev_is_visible
```
```
In drivers/regulator/core.c (ffffffff817271f5)
Location: include/linux/device.h:628
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_attr_is_visible
```
```
In drivers/base/core.c (ffffffff817b6304)
Location: include/linux/device.h:628
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:device_get_ownership
  - drivers/base/core.c:device_namespace
  - drivers/base/core.c:device_release
  - drivers/base/core.c:dev_attr_store
  - drivers/base/core.c:dev_attr_show
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/cacheinfo.c (ffffffff817c1c55)
Location: include/linux/device.h:628
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817d6885)
Location: include/linux/device.h:628
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
```
In drivers/base/devcoredump.c (ffffffff817e5b85)
Location: include/linux/device.h:628
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/base/devcoredump.c:devcd_data_read
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8183b2a5)
Location: include/linux/device.h:628
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sdev_bin_attr_is_visible
  - drivers/scsi/scsi_sysfs.c:scsi_sdev_attr_is_visible
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg0
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg89
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
```
```
In drivers/usb/core/sysfs.c (ffffffff818c8ab5)
Location: include/linux/device.h:628
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:intf_assoc_attrs_are_visible
  - drivers/usb/core/sysfs.c:read_descriptors
  - drivers/usb/core/sysfs.c:dev_string_attrs_are_visible
```
```
In drivers/input/input-poller.c (ffffffff8192d0e5)
Location: include/linux/device.h:628
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_poller_attrs_visible
```
```
In drivers/rtc/nvmem.c (ffffffff8193c1dd)
Location: include/linux/device.h:628
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:rtc_nvram_write
  - drivers/rtc/nvmem.c:rtc_nvram_read
```
```
In drivers/rtc/sysfs.c (ffffffff8193cd45)
Location: include/linux/device.h:628
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff8194d115)
Location: include/linux/device.h:628
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_is_attribute_visible
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff8198a595)
Location: include/linux/device.h:628
Inline: True
```
```
In drivers/leds/led-triggers.c (ffffffff819b8305)
Location: include/linux/device.h:628
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_read
  - drivers/leds/led-triggers.c:led_trigger_write
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101d015)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_mapping_visible
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81047505)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8163c295)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
```
```
In drivers/pci/pci-sysfs.c (ffffffff816550f5)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_hp_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/pci/pci-sysfs.c:pci_write_rom
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/pci/vpd.c (ffffffff81657f95)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:read_vpd_attr
```
```
In drivers/pci/pcie/aspm.c (ffffffff816619d5)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
```
```
In drivers/pci/pcie/aer.c (ffffffff81662835)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
```
```
In drivers/pci/iov.c (ffffffff81676255)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_attrs_are_visible
```
```
In drivers/pci/pci-label.c (ffffffff81677e15)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:acpi_index_string_exist
  - drivers/pci/pci-label.c:smbios_instance_string_exist
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81681105)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_dev_is_attr_visible
  - drivers/rapidio/rio-sysfs.c:rio_write_config
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
```
In drivers/xen/pcpu.c (ffffffff8173ec75)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:pcpu_dev_is_visible
```
```
In drivers/regulator/core.c (ffffffff81743dc5)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_attr_is_visible
```
```
In drivers/base/core.c (ffffffff817cb774)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:device_get_ownership
  - drivers/base/core.c:device_namespace
  - drivers/base/core.c:device_release
  - drivers/base/core.c:dev_attr_store
  - drivers/base/core.c:dev_attr_show
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/cacheinfo.c (ffffffff817d6e75)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817eb2d3)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
```
In drivers/base/devcoredump.c (ffffffff817fa815)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/base/devcoredump.c:devcd_data_read
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8184ba35)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sdev_bin_attr_is_visible
  - drivers/scsi/scsi_sysfs.c:scsi_sdev_attr_is_visible
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg0
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg89
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
```
```
In drivers/usb/core/sysfs.c (ffffffff818d3c05)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:intf_assoc_attrs_are_visible
  - drivers/usb/core/sysfs.c:read_descriptors
  - drivers/usb/core/sysfs.c:dev_string_attrs_are_visible
```
```
In drivers/usb/roles/class.c (ffffffff8192b545)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_is_visible
```
```
In drivers/input/input-poller.c (ffffffff819345a5)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_poller_attrs_visible
```
```
In drivers/rtc/sysfs.c (ffffffff81942d55)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81952b25)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_is_attribute_visible
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81954ae5)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_attr_is_visible
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8195cae6)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_passive_is_visible
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81963805)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:wdt_is_visible
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff8198e1d5)
Location: include/linux/device.h:585
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff819b18c5)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:sd_std_is_visible
```
```
In drivers/leds/led-triggers.c (ffffffff819ba735)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_read
  - drivers/leds/led-triggers.c:led_trigger_write
```
```
In drivers/nvmem/core.c (ffffffff819d94b5)
Location: include/linux/device.h:585
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_bin_attr_is_visible
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
In arch/x86/events/intel/core.c (ffffffff8100dc45)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:hybrid_format_is_visible
  - arch/x86/events/intel/core.c:hybrid_tsx_is_visible
  - arch/x86/events/intel/core.c:hybrid_tsx_is_visible
  - arch/x86/events/intel/core.c:hybrid_events_is_visible
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101e4c5)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_mapping_visible
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048e35)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8161fdd5)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
```
```
In drivers/pci/pci-sysfs.c (ffffffff81637d25)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_hp_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_reset_attr_is_visible
  - drivers/pci/pci-sysfs.c:pci_dev_rom_attr_is_visible
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/pci/pci-sysfs.c:pci_write_rom
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
  - drivers/pci/pci-sysfs.c:pci_dev_config_attr_is_visible
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/pci/vpd.c (ffffffff8163a565)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/pci/vpd.c:vpd_attr_is_visible
  - drivers/pci/vpd.c:vpd_write
  - drivers/pci/vpd.c:vpd_read
```
```
In drivers/pci/pcie/aspm.c (ffffffff816435c5)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
```
```
In drivers/pci/pcie/aer.c (ffffffff81644ca5)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
```
```
In drivers/pci/iov.c (ffffffff816587e5)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_pf_attrs_are_visible
  - drivers/pci/iov.c:sriov_vf_attrs_are_visible
```
```
In drivers/pci/pci-label.c (ffffffff8165a4f5)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:acpi_attr_is_visible
  - drivers/pci/pci-label.c:smbios_attr_is_visible
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81663f65)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_dev_is_attr_visible
  - drivers/rapidio/rio-sysfs.c:rio_write_config
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
```
In drivers/xen/pcpu.c (ffffffff817227a5)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:pcpu_dev_is_visible
```
```
In drivers/regulator/core.c (ffffffff817277a5)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_attr_is_visible
```
```
In drivers/base/core.c (ffffffff817af0e4)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:device_get_ownership
  - drivers/base/core.c:device_namespace
  - drivers/base/core.c:device_release
  - drivers/base/core.c:dev_attr_store
  - drivers/base/core.c:dev_attr_show
  - drivers/base/core.c:fw_devlink_link_device
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/cacheinfo.c (ffffffff817ba895)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817cfa4a)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
```
In drivers/base/devcoredump.c (ffffffff817df525)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/base/devcoredump.c:devcd_data_read
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8182eec5)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sdev_bin_attr_is_visible
  - drivers/scsi/scsi_sysfs.c:scsi_sdev_attr_is_visible
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg0
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg89
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
```
```
In drivers/usb/core/sysfs.c (ffffffff818b7165)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:intf_assoc_attrs_are_visible
  - drivers/usb/core/sysfs.c:read_descriptors
  - drivers/usb/core/sysfs.c:dev_string_attrs_are_visible
```
```
In drivers/usb/roles/class.c (ffffffff8190ea85)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_is_visible
```
```
In drivers/input/input-poller.c (ffffffff81917915)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_poller_attrs_visible
```
```
In drivers/rtc/sysfs.c (ffffffff81926575)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81936995)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_is_attribute_visible
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81938955)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_attr_is_visible
```
```
In drivers/hwmon/hwmon.c (ffffffff8193b4e5)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_dev_name_is_visible
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81947c25)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:wdt_is_visible
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff81972865)
Location: include/linux/device.h:591
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff819960e0)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:sd_std_is_visible
```
```
In drivers/leds/led-triggers.c (ffffffff8199ef55)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_read
  - drivers/leds/led-triggers.c:led_trigger_write
```
```
In drivers/nvmem/core.c (ffffffff819bf585)
Location: include/linux/device.h:591
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_bin_attr_is_visible
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
In arch/x86/events/intel/core.c (ffffffff8100e2b5)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:hybrid_format_is_visible
  - arch/x86/events/intel/core.c:hybrid_tsx_is_visible
  - arch/x86/events/intel/core.c:hybrid_tsx_is_visible
  - arch/x86/events/intel/core.c:hybrid_events_is_visible
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81023b37)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_iio_mapping_visible
  - arch/x86/events/intel/uncore_snbep.c:snr_iio_mapping_visible
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_mapping_visible
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104f825)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8168f995)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
```
```
In drivers/pci/pci.c (ffffffff8169c085)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_reset_method_attr_is_visible
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a7f95)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_hp_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_reset_attr_is_visible
  - drivers/pci/pci-sysfs.c:pci_dev_rom_attr_is_visible
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/pci/pci-sysfs.c:pci_write_rom
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
  - drivers/pci/pci-sysfs.c:pci_dev_config_attr_is_visible
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/pci/vpd.c (ffffffff816aad25)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/pci/vpd.c:vpd_attr_is_visible
  - drivers/pci/vpd.c:vpd_write
  - drivers/pci/vpd.c:vpd_read
```
```
In drivers/pci/pcie/aspm.c (ffffffff816b4315)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
```
```
In drivers/pci/pcie/aer.c (ffffffff816b5a55)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
```
```
In drivers/pci/iov.c (ffffffff816ca825)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_pf_attrs_are_visible
  - drivers/pci/iov.c:sriov_vf_attrs_are_visible
```
```
In drivers/pci/pci-label.c (ffffffff816cc835)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:acpi_attr_is_visible
  - drivers/pci/pci-label.c:smbios_attr_is_visible
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff816d6e45)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_dev_is_attr_visible
  - drivers/rapidio/rio-sysfs.c:rio_write_config
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
```
In drivers/xen/pcpu.c (ffffffff817a15f5)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:pcpu_dev_is_visible
```
```
In drivers/regulator/core.c (ffffffff817a68f5)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_attr_is_visible
```
```
In drivers/base/core.c (ffffffff81838306)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:device_get_ownership
  - drivers/base/core.c:device_namespace
  - drivers/base/core.c:device_release
  - drivers/base/core.c:dev_attr_store
  - drivers/base/core.c:dev_attr_show
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/topology.c (ffffffff81842065)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/base/topology.c:die_cpus_list_read
  - drivers/base/topology.c:die_cpus_read
```
```
In drivers/base/cacheinfo.c (ffffffff81844745)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8185a25a)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
```
In drivers/base/node.c (ffffffff8185b8c8)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/base/node.c:cpulist_read
  - drivers/base/node.c:cpumap_read
```
```
In drivers/base/devcoredump.c (ffffffff8186af85)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/base/devcoredump.c:devcd_data_read
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff818bac95)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sdev_bin_attr_is_visible
  - drivers/scsi/scsi_sysfs.c:scsi_sdev_attr_is_visible
  - drivers/scsi/scsi_sysfs.c:show_inquiry
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg0
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg89
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg80
  - drivers/scsi/scsi_sysfs.c:show_vpd_pg83
```
```
In drivers/usb/core/sysfs.c (ffffffff8194cc45)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:intf_assoc_attrs_are_visible
  - drivers/usb/core/sysfs.c:read_descriptors
  - drivers/usb/core/sysfs.c:dev_string_attrs_are_visible
```
```
In drivers/usb/roles/class.c (ffffffff819afac5)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_is_visible
```
```
In drivers/input/input-poller.c (ffffffff819b9b85)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_poller_attrs_visible
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819be8f5)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_attr_is_visible
```
```
In drivers/rtc/sysfs.c (ffffffff819c94b5)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff819da8c5)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_is_attribute_visible
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff819dcee5)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_attr_is_visible
```
```
In drivers/hwmon/hwmon.c (ffffffff819dfcb5)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_dev_name_is_visible
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff819ecb85)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:wdt_is_visible
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff81a1b565)
Location: include/linux/device.h:608
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff81a41f80)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:sd_std_is_visible
```
```
In drivers/leds/led-triggers.c (ffffffff81a4bbf5)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_read
  - drivers/leds/led-triggers.c:led_trigger_write
```
```
In drivers/nvmem/core.c (ffffffff81a6f1e5)
Location: include/linux/device.h:608
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_bin_attr_is_visible
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
In arch/x86/events/intel/core.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/pci/iov.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/pci/pci-label.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/rapidio/rio-sysfs.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/xen/pcpu.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/base/topology.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/base/firmware_loader/sysfs.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/base/node.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/usb/core/sysfs.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/usb/roles/class.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/rtc/sysfs.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/ptp/ptp_sysfs.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/edac/edac_mc_sysfs.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/mmc/core/sd.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/leds/led-triggers.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/remoteproc/remoteproc_sysfs.c (0)
Location: include/linux/device.h:683
Inline: True
```
```
In drivers/nvmem/core.c (0)
Location: include/linux/device.h:683
Inline: True
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
In arch/arm64/kernel/perf_event.c (ffff8000100a3ab4)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_event.c:armv8pmu_event_attr_is_visible
```
```
In block/genhd.c (0)
Location: include/linux/device.h:1321
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffff8000106ed1a4)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_hp_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/pci/pci-sysfs.c:pci_write_rom
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/pci/vpd.c (ffff8000106f0aa8)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:read_vpd_attr
```
```
In drivers/pci/pcie/aspm.c (ffff8000107018e4)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
```
```
In drivers/pci/pcie/aer.c (ffff8000107039c4)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
```
```
In drivers/pci/iov.c (ffff800010716784)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_attrs_are_visible
```
```
In drivers/pci/pci-label.c (ffff800010718818)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:acpi_index_string_exist
  - drivers/pci/pci-label.c:smbios_instance_string_exist
```
```
In drivers/rapidio/rio-sysfs.c (ffff80001073e8f4)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_dev_is_attr_visible
  - drivers/rapidio/rio-sysfs.c:rio_write_config
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
```
In drivers/regulator/core.c (ffff80001083f558)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_attr_is_visible
```
```
In drivers/base/core.c (ffff8000108e733c)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:device_get_ownership
  - drivers/base/core.c:device_namespace
  - drivers/base/core.c:device_release
  - drivers/base/core.c:dev_attr_store
  - drivers/base/core.c:dev_attr_show
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/cacheinfo.c (ffff8000108f3be8)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/base/firmware_loader/fallback.c (ffff80001090e344)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
```
In drivers/base/devcoredump.c (ffff80001091f05c)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/base/devcoredump.c:devcd_data_read
```
```
In drivers/input/input-poller.c (ffff800010a9a4b8)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_poller_attrs_visible
```
```
In drivers/rtc/nvmem.c (ffff800010aaa1b8)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:rtc_nvram_write
  - drivers/rtc/nvmem.c:rtc_nvram_read
```
```
In drivers/ptp/ptp_sysfs.c (ffff800010ac88b4)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_is_attribute_visible
```
```
In drivers/edac/edac_mc_sysfs.c (ffff800010b120b4)
Location: include/linux/device.h:1321
Inline: True
```
```
In drivers/perf/arm-ccn.c (ffff800010b9219c)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_events_is_visible
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
In arch/arm/mm/cache-l2x0-pmu.c (c0324e68)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_attr_is_visible
```
```
In block/genhd.c (0)
Location: include/linux/device.h:1321
Inline: True
```
```
In drivers/pci/pci-sysfs.c (c08883f8)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_hp_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/pci/pci-sysfs.c:pci_write_rom
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
  - drivers/pci/pci-sysfs.c:pci_mmap_resource
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/pci/vpd.c (c088b4d8)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:read_vpd_attr
```
```
In drivers/pci/pcie/aspm.c (c08994d8)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
```
```
In drivers/pci/pcie/aer.c (c089b278)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
```
```
In drivers/pci/iov.c (c08a10a4)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_attrs_are_visible
```
```
In drivers/pci/pci-label.c (c08a2eac)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:smbios_instance_string_exist
```
```
In drivers/rapidio/rio-sysfs.c (c08c36a4)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_dev_is_attr_visible
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
```
In drivers/soc/tegra/fuse/fuse-tegra.c (c093a2ec)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/soc/tegra/fuse/fuse-tegra.c:fuse_read
```
```
In drivers/regulator/core.c (c0948d3c)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_attr_is_visible
```
```
In drivers/base/core.c (c09d5930)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:device_get_ownership
  - drivers/base/core.c:device_namespace
  - drivers/base/core.c:device_release
  - drivers/base/core.c:dev_attr_store
  - drivers/base/core.c:dev_attr_show
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/cacheinfo.c (c09e0248)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/base/firmware_loader/fallback.c (c09f7008)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
```
In drivers/base/devcoredump.c (c0a042f8)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/base/devcoredump.c:devcd_data_read
```
```
In drivers/input/input-poller.c (c0b7c118)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_poller_attrs_visible
```
```
In drivers/rtc/nvmem.c (c0b88f98)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:rtc_nvram_write
  - drivers/rtc/nvmem.c:rtc_nvram_read
```
```
In drivers/ptp/ptp_sysfs.c (c0ba8248)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_is_attribute_visible
```
```
In drivers/edac/edac_mc_sysfs.c (c0bf0308)
Location: include/linux/device.h:1321
Inline: True
```
```
In drivers/perf/arm-ccn.c (c0c7bbb8)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_events_is_visible
```
```
In sound/soc/soc-core.c (c0c9eda4)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - sound/soc/soc-core.c:soc_dev_attr_is_visible
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
In arch/powerpc/kernel/cacheinfo.c (c00000000002a10c)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - arch/powerpc/kernel/cacheinfo.c:shared_cpu_map_show
```
```
In block/genhd.c (0)
Location: include/linux/device.h:1321
Inline: True
```
```
In drivers/pci/pci-sysfs.c (c000000000869188)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_hp_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/pci/pci-sysfs.c:pci_write_rom
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
  - drivers/pci/pci-sysfs.c:pci_mmap_legacy_io
  - drivers/pci/pci-sysfs.c:pci_mmap_legacy_mem
  - drivers/pci/pci-sysfs.c:pci_write_legacy_io
  - drivers/pci/pci-sysfs.c:pci_read_legacy_io
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/pci/vpd.c (c00000000086e0f0)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:read_vpd_attr
```
```
In drivers/pci/iov.c (c0000000008869d0)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_attrs_are_visible
```
```
In drivers/rapidio/rio-sysfs.c (c000000000898170)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_dev_is_attr_visible
  - drivers/rapidio/rio-sysfs.c:rio_write_config
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
```
In drivers/regulator/core.c (c0000000008d86f8)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_attr_is_visible
```
```
In drivers/base/core.c (c00000000097d5f8)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:device_get_ownership
  - drivers/base/core.c:device_namespace
  - drivers/base/core.c:device_release
  - drivers/base/core.c:dev_attr_store
  - drivers/base/core.c:dev_attr_show
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/cacheinfo.c (c00000000098da74)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/base/firmware_loader/fallback.c (c0000000009aec98)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
```
In drivers/base/devcoredump.c (c0000000009c4270)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/base/devcoredump.c:devcd_data_read
```
```
In drivers/input/input-poller.c (c000000000b7a5c8)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_poller_attrs_visible
```
```
In drivers/rtc/nvmem.c (c000000000b8c4a0)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:rtc_nvram_write
  - drivers/rtc/nvmem.c:rtc_nvram_read
```
```
In drivers/ptp/ptp_sysfs.c (c000000000baa200)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_is_attribute_visible
```
```
In drivers/edac/edac_mc_sysfs.c (c000000000c064b0)
Location: include/linux/device.h:1321
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
In block/genhd.c (0)
Location: include/linux/device.h:1321
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffe0004c1f34)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_hp_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/pci/pci-sysfs.c:pci_write_rom
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/pci/vpd.c (ffffffe0004c4516)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:read_vpd_attr
```
```
In drivers/pci/pcie/aspm.c (ffffffe0004d05b0)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
```
```
In drivers/pci/pcie/aer.c (ffffffe0004d229a)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
```
```
In drivers/pci/iov.c (ffffffe0004dfbd8)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_attrs_are_visible
```
```
In drivers/rapidio/rio-sysfs.c (ffffffe0004edfc4)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_dev_is_attr_visible
  - drivers/rapidio/rio-sysfs.c:rio_write_config
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
```
In drivers/regulator/core.c (ffffffe000521246)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_attr_is_visible
```
```
In drivers/base/core.c (ffffffe00057bae8)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:device_get_ownership
  - drivers/base/core.c:device_namespace
  - drivers/base/core.c:device_release
  - drivers/base/core.c:dev_attr_store
  - drivers/base/core.c:dev_attr_show
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/cacheinfo.c (ffffffe0005850d6)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/base/firmware_loader/fallback.c (ffffffe0005928a2)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
```
In drivers/base/devcoredump.c (ffffffe00059e09c)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/base/devcoredump.c:devcd_data_read
```
```
In drivers/input/input-poller.c (ffffffe0006aadcc)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_poller_attrs_visible
```
```
In drivers/rtc/nvmem.c (ffffffe0006b56d4)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:rtc_nvram_write
  - drivers/rtc/nvmem.c:rtc_nvram_read
```
```
In drivers/ptp/ptp_sysfs.c (ffffffe0006c6bd2)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_is_attribute_visible
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffe0006fed5c)
Location: include/linux/device.h:1321
Inline: True
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044515)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
```
```
In block/genhd.c (0)
Location: include/linux/device.h:1321
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157c985)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_hp_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/pci/pci-sysfs.c:pci_write_rom
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/pci/vpd.c (ffffffff8157f9e5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:read_vpd_attr
```
```
In drivers/pci/pcie/aspm.c (ffffffff8158de45)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
```
```
In drivers/pci/pcie/aer.c (ffffffff8158fcd5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
```
```
In drivers/pci/iov.c (ffffffff815a0255)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_attrs_are_visible
```
```
In drivers/pci/pci-label.c (ffffffff815a1c45)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:acpi_index_string_exist
  - drivers/pci/pci-label.c:smbios_instance_string_exist
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815aa405)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_dev_is_attr_visible
  - drivers/rapidio/rio-sysfs.c:rio_write_config
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
```
In drivers/xen/pcpu.c (ffffffff816379c5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:pcpu_dev_is_visible
```
```
In drivers/regulator/core.c (ffffffff8163c4c5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_attr_is_visible
```
```
In drivers/base/core.c (ffffffff816c210e)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:device_get_ownership
  - drivers/base/core.c:device_namespace
  - drivers/base/core.c:device_release
  - drivers/base/core.c:dev_attr_store
  - drivers/base/core.c:dev_attr_show
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/cacheinfo.c (ffffffff816cc605)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816e0be5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
```
In drivers/base/devcoredump.c (ffffffff816ef155)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/base/devcoredump.c:devcd_data_read
```
```
In drivers/input/input-poller.c (ffffffff8180f475)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_poller_attrs_visible
```
```
In drivers/rtc/nvmem.c (ffffffff8181b29a)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:rtc_nvram_write
  - drivers/rtc/nvmem.c:rtc_nvram_read
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81827185)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_is_attribute_visible
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff8185fc85)
Location: include/linux/device.h:1321
Inline: True
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81033b35)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
```
```
In block/genhd.c (0)
Location: include/linux/device.h:1321
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156b755)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_hp_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/pci/pci-sysfs.c:pci_write_rom
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/pci/vpd.c (ffffffff8156e7c5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:read_vpd_attr
```
```
In drivers/pci/pcie/aspm.c (ffffffff8157c985)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
```
```
In drivers/pci/pcie/aer.c (ffffffff8157e815)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
```
```
In drivers/pci/iov.c (ffffffff8158f3e5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_attrs_are_visible
```
```
In drivers/pci/pci-label.c (ffffffff81590de5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:acpi_index_string_exist
  - drivers/pci/pci-label.c:smbios_instance_string_exist
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815995a5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_dev_is_attr_visible
  - drivers/rapidio/rio-sysfs.c:rio_write_config
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
```
In drivers/regulator/core.c (ffffffff8161c6b5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_attr_is_visible
```
```
In drivers/base/core.c (ffffffff8169d3be)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:device_get_ownership
  - drivers/base/core.c:device_namespace
  - drivers/base/core.c:device_release
  - drivers/base/core.c:dev_attr_store
  - drivers/base/core.c:dev_attr_show
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/cacheinfo.c (ffffffff816a7935)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816bb225)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
```
In drivers/input/input-poller.c (ffffffff817d6bc5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_poller_attrs_visible
```
```
In drivers/rtc/nvmem.c (ffffffff817e298a)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:rtc_nvram_write
  - drivers/rtc/nvmem.c:rtc_nvram_read
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff817ee815)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_is_attribute_visible
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff81827255)
Location: include/linux/device.h:1321
Inline: True
```
```
In drivers/hv/vmbus_drv.c (ffffffff8184cd85)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/hv/vmbus_drv.c:vmbus_dev_attr_is_visible
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044355)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
```
```
In block/genhd.c (0)
Location: include/linux/device.h:1321
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157c845)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_hp_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/pci/pci-sysfs.c:pci_write_rom
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/pci/vpd.c (ffffffff8157f8b5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:read_vpd_attr
```
```
In drivers/pci/pcie/aspm.c (ffffffff8158dd05)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
```
```
In drivers/pci/pcie/aer.c (ffffffff8158fb95)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
```
```
In drivers/pci/iov.c (ffffffff815a07d5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_attrs_are_visible
```
```
In drivers/pci/pci-label.c (ffffffff815a21d5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:acpi_index_string_exist
  - drivers/pci/pci-label.c:smbios_instance_string_exist
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815aa995)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_dev_is_attr_visible
  - drivers/rapidio/rio-sysfs.c:rio_write_config
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
```
In drivers/xen/pcpu.c (ffffffff81665745)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:pcpu_dev_is_visible
```
```
In drivers/regulator/core.c (ffffffff8166a615)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_attr_is_visible
```
```
In drivers/base/core.c (ffffffff816f05de)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:device_get_ownership
  - drivers/base/core.c:device_namespace
  - drivers/base/core.c:device_release
  - drivers/base/core.c:dev_attr_store
  - drivers/base/core.c:dev_attr_show
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/cacheinfo.c (ffffffff816fab75)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8170e2b5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
```
In drivers/base/devcoredump.c (ffffffff8171c835)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/base/devcoredump.c:devcd_data_read
```
```
In drivers/input/input-poller.c (ffffffff8184e5f5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_poller_attrs_visible
```
```
In drivers/rtc/nvmem.c (ffffffff8185c77a)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:rtc_nvram_write
  - drivers/rtc/nvmem.c:rtc_nvram_read
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff818740c5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_is_attribute_visible
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff818af2b5)
Location: include/linux/device.h:1321
Inline: True
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045755)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible
```
```
In block/genhd.c (0)
Location: include/linux/device.h:1321
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff81596cf5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_bridge_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_hp_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_dev_attrs_are_visible
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/pci/pci-sysfs.c:pci_write_rom
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/pci/vpd.c (ffffffff81599d65)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/vpd.c:write_vpd_attr
  - drivers/pci/vpd.c:read_vpd_attr
```
```
In drivers/pci/pcie/aspm.c (ffffffff815a81b5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
```
```
In drivers/pci/pcie/aer.c (ffffffff815aa045)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_stats_attrs_are_visible
```
```
In drivers/pci/iov.c (ffffffff815bac05)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_attrs_are_visible
```
```
In drivers/pci/pci-label.c (ffffffff815bc5d5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/pci/pci-label.c:acpi_index_string_exist
  - drivers/pci/pci-label.c:smbios_instance_string_exist
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815c4325)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_dev_is_attr_visible
  - drivers/rapidio/rio-sysfs.c:rio_write_config
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
```
In drivers/xen/pcpu.c (ffffffff8167fcf5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:pcpu_dev_is_visible
```
```
In drivers/regulator/core.c (ffffffff81684bd5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_attr_is_visible
```
```
In drivers/base/core.c (ffffffff8170ae1e)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:device_get_ownership
  - drivers/base/core.c:device_namespace
  - drivers/base/core.c:device_release
  - drivers/base/core.c:dev_attr_store
  - drivers/base/core.c:dev_attr_show
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/cacheinfo.c (ffffffff81715415)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff81728ed5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
```
In drivers/base/devcoredump.c (ffffffff81737b95)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_data_write
  - drivers/base/devcoredump.c:devcd_data_read
```
```
In drivers/input/input-poller.c (ffffffff818697c5)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_poller_attrs_visible
```
```
In drivers/rtc/nvmem.c (ffffffff818779fa)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:rtc_nvram_write
  - drivers/rtc/nvmem.c:rtc_nvram_read
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff8188fa75)
Location: include/linux/device.h:1321
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:ptp_is_attribute_visible
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff818cb545)
Location: include/linux/device.h:1321
Inline: True
```
</details>
</li>
</ul>

## Differences
