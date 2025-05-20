# Function: <code>sysfs_remove_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8128d8e0)
Location: fs/sysfs/group.c:226
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_cpu_callback
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:free_module
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - fs/sysfs/group.c:sysfs_create_groups
  - fs/sysfs/group.c:sysfs_remove_groups
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_exit
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_exit
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_exit
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_exit
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/tpm/tpm-sysfs.c:tpm_sysfs_del_device
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_cpu_callback
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:loop_clr_fd
  - drivers/misc/bmp085.c:bmp085_remove
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:__cpufreq_stats_free_table
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
```
**Symbols:**

```
ffffffff8128d8e0-ffffffff8128d96d: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff812baf40)
Location: fs/sysfs/group.c:226
Inline: True
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_cpu_callback
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_teardown
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - fs/sysfs/group.c:sysfs_remove_groups
  - fs/sysfs/group.c:sysfs_create_groups
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_cpu_callback
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:loop_clr_fd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff812baf40-ffffffff812bafcd: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff812d0670)
Location: fs/sysfs/group.c:226
Inline: True
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_teardown
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - fs/sysfs/group.c:sysfs_remove_groups
  - fs/sysfs/group.c:sysfs_create_groups
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:loop_clr_fd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff812d0670-ffffffff812d06fe: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff812ddcf0)
Location: fs/sysfs/group.c:226
Inline: True
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_teardown
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:loop_clr_fd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff812ddcf0-ffffffff812ddd74: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81302630)
Location: fs/sysfs/group.c:226
Inline: True
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_teardown
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:loop_clr_fd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81302630-ffffffff813026b9: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813304d0)
Location: fs/sysfs/group.c:230
Inline: True
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_teardown
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:loop_clr_fd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff813304d0-ffffffff81330554: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813478a0)
Location: fs/sysfs/group.c:245
Inline: True
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_teardown
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff813478a0-ffffffff81347924: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8136fca0)
Location: fs/sysfs/group.c:269
Inline: True
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_teardown
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff8136fca0-ffffffff8136fd20: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81388010)
Location: fs/sysfs/group.c:270
Inline: True
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_teardown
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81388010-ffffffff81388090: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813d2710)
Location: fs/sysfs/group.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_add_dev
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/params.c:kernel_add_sysfs_param
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_teardown
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff813d2710-ffffffff813d278b: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813e4470)
Location: fs/sysfs/group.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_add_dev
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/params.c:kernel_add_sysfs_param
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_teardown
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_remove
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff813e4470-ffffffff813e44eb: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813eb070)
Location: fs/sysfs/group.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_teardown
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_offline
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff813eb070-ffffffff813eb0eb: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8143ce00)
Location: fs/sysfs/group.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_teardown
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_offline
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_add_dev
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff8143ce00-ffffffff8143ce7b: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff814b85d0)
Location: fs/sysfs/group.c:269
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - fs/sysfs/group.c:internal_create_groups
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_offline
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_add_dev
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff814b85d0-ffffffff814b8659: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8154fc00)
Location: fs/sysfs/group.c:269
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_down_prep
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - fs/sysfs/group.c:internal_create_groups
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/ecryptfs/main.c:ecryptfs_init
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_offline
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_add_dev
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff8154fc00-ffffffff8154fc89: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff815878d0)
Location: fs/sysfs/group.c:273
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_down_prep
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - fs/sysfs/group.c:internal_create_groups
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/ecryptfs/main.c:ecryptfs_init
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_remove
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_offline
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_add_dev
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff815878d0-ffffffff81587959: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff815c0490)
Location: fs/sysfs/group.c:273
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_down_prep
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/huge_memory.c:hugepage_exit_sysfs
  - mm/huge_memory.c:hugepage_exit_sysfs
  - mm/huge_memory.c:hugepage_init_sysfs
  - fs/sysfs/group.c:internal_create_groups
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/ecryptfs/main.c:ecryptfs_init
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/acpi/acpi_fpdt.c:fpdt_process_subtable
  - drivers/acpi/acpi_fpdt.c:fpdt_process_subtable
  - drivers/acpi/acpi_fpdt.c:fpdt_process_subtable
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_offline
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_add_dev
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff815c0490-ffffffff815c0519: sysfs_remove_group (STB_GLOBAL)
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
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffff800010458208)
Location: fs/sysfs/group.c:270
Inline: True
Direct callers:
  - arch/arm64/kernel/cpuinfo.c:cpuid_cpu_offline
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:free_module
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffff800010458208-ffff8000104582a4: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (c061a318)
Location: fs/sysfs/group.c:270
Inline: True
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:free_module
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/mtd/mtd_blkdevs.c:del_mtd_blktrans_dev
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
c061a318-c061a3c4: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (c000000000572b40)
Location: fs/sysfs/group.c:270
Inline: True
Direct callers:
  - arch/powerpc/kernel/sysfs.c:cpu_remove_dev_attr_group
  - arch/powerpc/platforms/powernv/opal-flash.c:opal_flash_update_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_teardown
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
c000000000572b40-c000000000572c20: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffe0002e9388)
Location: fs/sysfs/group.c:270
Inline: True
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:free_module
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffe0002e9388-ffffffe0002e941e: sysfs_remove_group (STB_GLOBAL)
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
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813805f0)
Location: fs/sysfs/group.c:270
Inline: True
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_teardown
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff813805f0-ffffffff81380670: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81371080)
Location: fs/sysfs/group.c:270
Inline: True
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_teardown
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/hv/vmbus_drv.c:vmbus_remove_channel_attr_group
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81371080-ffffffff81371100: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8137e0c0)
Location: fs/sysfs/group.c:270
Inline: True
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_teardown
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff8137e0c0-ffffffff8137e140: sysfs_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81391cc0)
Location: fs/sysfs/group.c:270
Inline: True
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_remove
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_teardown
  - kernel/trace/blktrace.c:blk_trace_remove_sysfs
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/pci/pci-label.c:pci_remove_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/acpi/sysfs.c:interrupt_stats_exit
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/char/virtio_console.c:unplug_port
  - drivers/base/core.c:devm_attr_group_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/base/transport_class.c:transport_remove_classdev
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81391cc0-ffffffff81391d40: sysfs_remove_group (STB_GLOBAL)
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
