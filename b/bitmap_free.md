# Function: <code>bitmap_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bitmap_free(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8169c2d0)
Location: drivers/md/bitmap.c:1674
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_destroy
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff8169c2d0-ffffffff8169c424: bitmap_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bitmap_free(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff816fd630)
Location: drivers/md/bitmap.c:1702
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_destroy
```
**Symbols:**

```
ffffffff816fd630-ffffffff816fd795: bitmap_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bitmap_free(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8172f2b0)
Location: drivers/md/bitmap.c:1730
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_destroy
```
**Symbols:**

```
ffffffff8172f2b0-ffffffff8172f409: bitmap_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bitmap_free(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff817488d0)
Location: drivers/md/bitmap.c:1732
Inline: False
Direct callers:
  - drivers/md/bitmap.c:get_bitmap_from_slot
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_destroy
```
**Symbols:**

```
ffffffff817488d0-ffffffff81748a2a: bitmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bitmap_free(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817babb0)
Location: drivers/md/md-bitmap.c:1736
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:get_bitmap_from_slot
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_destroy
```
**Symbols:**

```
ffffffff817babb0-ffffffff817bad10: bitmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bitmap_free(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81802c60)
Location: drivers/md/md-bitmap.c:1736
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:get_bitmap_from_slot
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_destroy
```
**Symbols:**

```
ffffffff81802c60-ffffffff81802dc0: bitmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bitmap_free(const long unsigned int *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d7f10)
Location: lib/bitmap.c:1136
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/pci/probe.c:pci_release_dev
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_release
```
**Symbols:**

```
ffffffff814d7f10-ffffffff814d7f1b: bitmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bitmap_free(const long unsigned int *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81503b00)
Location: lib/bitmap.c:1164
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/pci/probe.c:pci_release_dev
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_release
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_bitmap_free
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffffffff81503b00-ffffffff81503b0b: bitmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bitmap_free(const long unsigned int *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81521aa0)
Location: lib/bitmap.c:1184
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/probe.c:pci_release_dev
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_release
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_bitmap_free
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81521aa0-ffffffff81521aab: bitmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bitmap_free(const long unsigned int *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81584b10)
Location: lib/bitmap.c:1259
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
  - kernel/sysctl.c:proc_do_large_bitmap
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpio_chrdev_release
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/pci/probe.c:pci_release_dev
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_release
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81584b10-ffffffff81584b1b: bitmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bitmap_free(const long unsigned int *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a1c10)
Location: lib/bitmap.c:1259
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
  - arch/x86/kernel/cpu/resctrl/core.c:domain_setup_mon_state
  - kernel/sysctl.c:proc_do_large_bitmap
  - lib/pldmfw/pldmfw.c:pldmfw_free_priv
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/pci/probe.c:pci_release_dev
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_release
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff815a1c10-ffffffff815a1c1b: bitmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bitmap_free(const long unsigned int *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a8cae)
Location: lib/bitmap.c:1270
Inline: True
Inline callers:
  - lib/bitmap.c:devm_bitmap_alloc
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/pci/probe.c:pci_release_dev
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_release
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_queue_show
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff815a8a20-ffffffff815a8a2b: bitmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bitmap_free(const long unsigned int *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81611f4e)
Location: lib/bitmap.c:1401
Inline: True
Inline callers:
  - lib/bitmap.c:devm_bitmap_alloc
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/watch_queue.c:__put_watch_queue
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:validate_slab_cache
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/pci/probe.c:pci_release_dev
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_release
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_queue_show
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81611bd0-ffffffff81611bdb: bitmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bitmap_free(const long unsigned int *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816de272)
Location: lib/bitmap.c:1431
Inline: True
Inline callers:
  - lib/bitmap.c:devm_bitmap_alloc
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
  - kernel/irq/irq_sim.c:irq_domain_create_sim
  - kernel/watch_queue.c:__put_watch_queue
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:validate_slab_cache
  - io_uring/io_uring.c:__io_sqe_files_unregister
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/pci/probe.c:pci_release_dev
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_release
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_queue_show
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff816dde30-ffffffff816dde41: bitmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bitmap_free(const long unsigned int *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff817ce412)
Location: lib/bitmap.c:1412
Inline: True
Inline callers:
  - lib/bitmap.c:devm_bitmap_alloc
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
  - kernel/irq/irq_sim.c:irq_domain_create_sim
  - kernel/watch_queue.c:__put_watch_queue
  - mm/vmscan.c:lru_gen_exit_memcg
  - mm/vmscan.c:lru_gen_exit_memcg
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:validate_slab_cache
  - io_uring/filetable.c:io_free_file_tables
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/pci/probe.c:pci_release_dev
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_release
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_queue_show
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff817cddc0-ffffffff817cddd1: bitmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bitmap_free(const long unsigned int *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8180c8c9)
Location: lib/bitmap.c:1412
Inline: True
Inline callers:
  - lib/bitmap.c:devm_bitmap_alloc
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
  - kernel/irq/irq_sim.c:irq_domain_create_sim
  - kernel/watch_queue.c:__put_watch_queue
  - mm/vmscan.c:lru_gen_exit_memcg
  - mm/vmscan.c:lru_gen_exit_memcg
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:validate_slab_cache
  - io_uring/filetable.c:io_free_file_tables
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/pci/probe.c:pci_release_dev
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_release
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_queue_show
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff8180c270-ffffffff8180c281: bitmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bitmap_free(const long unsigned int *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff818529d9)
Location: lib/bitmap.c:736
Inline: True
Inline callers:
  - lib/bitmap.c:devm_bitmap_alloc
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
  - kernel/irq/irq_sim.c:irq_domain_create_sim
  - kernel/watch_queue.c:__put_watch_queue
  - mm/vmscan.c:lru_gen_exit_memcg
  - mm/vmscan.c:lru_gen_exit_memcg
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:validate_slab_cache
  - io_uring/filetable.c:io_free_file_tables
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_release
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/pci/probe.c:pci_release_dev
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_release
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_release
  - drivers/ptp/ptp_chardev.c:ptp_release
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - net/core/dev.c:__dev_alloc_name
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_queue_show
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81852750-ffffffff81852761: bitmap_free (STB_GLOBAL)
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
void bitmap_free(const long unsigned int *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062b1c8)
Location: lib/bitmap.c:1184
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/probe.c:pci_release_dev
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_free_bitmap
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_release
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_bitmap_free
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffff80001062b1c8-ffff80001062b1dc: bitmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bitmap_free(const long unsigned int *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c07d2500)
Location: lib/bitmap.c:1184
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/probe.c:pci_release_dev
  - drivers/input/evdev.c:evdev_release
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_bitmap_free
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
c07d2500-c07d2514: bitmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bitmap_free(const long unsigned int *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007cd800)
Location: lib/bitmap.c:1184
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/probe.c:pci_release_dev
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_release
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_bitmap_free
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
c0000000007cd800-c0000000007cd82c: bitmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bitmap_free(const long unsigned int *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffe00045bf7e)
Location: lib/bitmap.c:1184
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/probe.c:pci_release_dev
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_release
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_bitmap_free
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffe00045bf7e-ffffffe00045bf96: bitmap_free (STB_GLOBAL)
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
void bitmap_free(const long unsigned int *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8151a080)
Location: lib/bitmap.c:1184
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/probe.c:pci_release_dev
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_release
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_bitmap_free
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff8151a080-ffffffff8151a08b: bitmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bitmap_free(const long unsigned int *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8150a370)
Location: lib/bitmap.c:1184
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/irq/irq_sim.c:irq_sim_fini
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/probe.c:pci_release_dev
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_release
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_bitmap_free
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff8150a370-ffffffff8150a37b: bitmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bitmap_free(const long unsigned int *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81516110)
Location: lib/bitmap.c:1184
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/probe.c:pci_release_dev
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_release
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_bitmap_free
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81516110-ffffffff8151611b: bitmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bitmap_free(const long unsigned int *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152f8a0)
Location: lib/bitmap.c:1184
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - kernel/sysctl.c:proc_do_large_bitmap
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shutdown
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/probe.c:pci_release_dev
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_release
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_bitmap_free
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff8152f8a0-ffffffff8152f8ab: bitmap_free (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bitmap *bitmap</code> ➡️ <code>const long unsigned int *bitmap</code>
</li>
</ul>
</details>
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
