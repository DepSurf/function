# Function: <code>bitmap_zalloc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int *bitmap_zalloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d7fa0)
Location: lib/bitmap.c:1130
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
```
**Symbols:**

```
ffffffff814d7fa0-ffffffff814d7fbf: bitmap_zalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int *bitmap_zalloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81503b10)
Location: lib/bitmap.c:1158
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffffffff81503b10-ffffffff81503b2f: bitmap_zalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int *bitmap_zalloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81521ab0)
Location: lib/bitmap.c:1178
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffffffff81521ab0-ffffffff81521acf: bitmap_zalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int *bitmap_zalloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81584d50)
Location: lib/bitmap.c:1253
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
  - kernel/sysctl.c:proc_do_large_bitmap
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffffffff81584d50-ffffffff81584d6f: bitmap_zalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int *bitmap_zalloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a1e50)
Location: lib/bitmap.c:1253
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
  - kernel/sysctl.c:proc_do_large_bitmap
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffffffff815a1e50-ffffffff815a1e6f: bitmap_zalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int *bitmap_zalloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a8f30)
Location: lib/bitmap.c:1264
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - kernel/sysctl.c:proc_do_large_bitmap
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_queue_show
  - net/core/net-sysfs.c:xps_queue_show
```
**Symbols:**

```
ffffffff815a8f30-ffffffff815a8f4f: bitmap_zalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int *bitmap_zalloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81612040)
Location: lib/bitmap.c:1395
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - kernel/sysctl.c:proc_do_large_bitmap
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_queue_show
  - net/core/net-sysfs.c:xps_queue_show
```
**Symbols:**

```
ffffffff81612040-ffffffff8161205f: bitmap_zalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int *bitmap_zalloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816de3e0)
Location: lib/bitmap.c:1412
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irq_sim.c:irq_domain_create_sim
  - io_uring/io_uring.c:io_sqe_files_register
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/iommu/intel/iommu.c:iommu_init_domains
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/input/evdev.c:evdev_do_ioctl
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_queue_show
  - net/core/net-sysfs.c:xps_queue_show
```
**Symbols:**

```
ffffffff816de3e0-ffffffff816de407: bitmap_zalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int *bitmap_zalloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff817ce6d0)
Location: lib/bitmap.c:1393
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irq_sim.c:irq_domain_create_sim
  - mm/vmscan.c:iterate_mm_list
  - io_uring/filetable.c:io_alloc_file_tables
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:iommu_init_domains
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/input/evdev.c:evdev_do_ioctl
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_queue_show
  - net/core/net-sysfs.c:xps_queue_show
```
**Symbols:**

```
ffffffff817ce6d0-ffffffff817ce6f7: bitmap_zalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int *bitmap_zalloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8180cb80)
Location: lib/bitmap.c:1393
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irq_sim.c:irq_domain_create_sim
  - io_uring/filetable.c:io_alloc_file_tables
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:iommu_init_domains
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_queue_show
  - net/core/net-sysfs.c:xps_queue_show
```
**Symbols:**

```
ffffffff8180cb80-ffffffff8180cba7: bitmap_zalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int *bitmap_zalloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81852c90)
Location: lib/bitmap.c:717
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irq_sim.c:irq_domain_create_sim
  - io_uring/filetable.c:io_alloc_file_tables
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:iommu_init_domains
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
  - drivers/md/dm-zone.c:dm_zone_revalidate_cb
  - net/core/dev.c:__dev_alloc_name
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_queue_show
  - net/core/net-sysfs.c:xps_queue_show
```
**Symbols:**

```
ffffffff81852c90-ffffffff81852cb7: bitmap_zalloc (STB_GLOBAL)
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
long unsigned int *bitmap_zalloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062b200)
Location: lib/bitmap.c:1178
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffff80001062b200-ffff80001062b228: bitmap_zalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int *bitmap_zalloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c07d2514)
Location: lib/bitmap.c:1178
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
c07d2514-c07d2538: bitmap_zalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int *bitmap_zalloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007cd830)
Location: lib/bitmap.c:1178
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
c0000000007cd830-c0000000007cd870: bitmap_zalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int *bitmap_zalloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffe00045bf96)
Location: lib/bitmap.c:1178
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffffffe00045bf96-ffffffe00045bfbe: bitmap_zalloc (STB_GLOBAL)
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
long unsigned int *bitmap_zalloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8151a090)
Location: lib/bitmap.c:1178
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffffffff8151a090-ffffffff8151a0af: bitmap_zalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int *bitmap_zalloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8150a380)
Location: lib/bitmap.c:1178
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irq_sim.c:irq_sim_init
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffffffff8150a380-ffffffff8150a39f: bitmap_zalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int *bitmap_zalloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81516120)
Location: lib/bitmap.c:1178
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffffffff81516120-ffffffff8151613f: bitmap_zalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int *bitmap_zalloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152f8b0)
Location: lib/bitmap.c:1178
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/pci/pci.c:pci_add_dma_alias
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffffffff8152f8b0-ffffffff8152f8cf: bitmap_zalloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
