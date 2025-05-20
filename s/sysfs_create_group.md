# Function: <code>sysfs_create_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8128d8a0)
Location: fs/sysfs/group.c:153
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_create_groups
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_add_dev
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_add
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module.c:load_module
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_add
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/xen-selfballoon.c:register_xen_selfballooning
  - drivers/char/tpm/tpm-sysfs.c:tpm_sysfs_add_device
  - drivers/base/transport_class.c:transport_add_class_device
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/topology.c:topology_cpu_callback
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:lo_ioctl
  - drivers/misc/bmp085.c:bmp085_probe
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:md_run
  - drivers/cpufreq/cpufreq_stats.c:__cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
```
**Symbols:**

```
ffffffff8128d8a0-ffffffff8128d8b5: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff812bb006)
Location: fs/sysfs/group.c:153
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_create_groups
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_add_dev
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_add
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module.c:load_module
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_add
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/xen-selfballoon.c:register_xen_selfballooning
  - drivers/base/transport_class.c:transport_add_class_device
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/topology.c:topology_cpu_callback
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:lo_ioctl
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff812baf00-ffffffff812baf15: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff812d0736)
Location: fs/sysfs/group.c:153
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_create_groups
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_add
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module.c:load_module
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_add
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/xen-selfballoon.c:register_xen_selfballooning
  - drivers/base/transport_class.c:transport_add_class_device
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:lo_ioctl
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff812d0630-ffffffff812d0645: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff812ddcb0)
Location: fs/sysfs/group.c:153
Inline: True
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_add
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module.c:load_module
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/xen-selfballoon.c:register_xen_selfballooning
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:lo_ioctl
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff812ddcb0-ffffffff812ddcc5: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813025f0)
Location: fs/sysfs/group.c:153
Inline: True
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_add
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:cgroup_sysfs_init
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_add
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/xen-selfballoon.c:register_xen_selfballooning
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:lo_ioctl
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff813025f0-ffffffff81302605: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81330490)
Location: fs/sysfs/group.c:157
Inline: True
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_add
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/cgroup/cgroup.c:cgroup_sysfs_init
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/ksm.c:ksm_init
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/xen-selfballoon.c:register_xen_selfballooning
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:lo_ioctl
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81330490-ffffffff813304a5: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81347860)
Location: fs/sysfs/group.c:171
Inline: True
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_add
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/cgroup/cgroup.c:cgroup_sysfs_init
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/ksm.c:ksm_init
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/xen-selfballoon.c:register_xen_selfballooning
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:lo_ioctl
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81347860-ffffffff81347875: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8136fc60)
Location: fs/sysfs/group.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_add
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/cgroup/cgroup.c:cgroup_sysfs_init
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/ksm.c:ksm_init
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - block/blk-sysfs.c:blk_register_queue
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_set_fd
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff8136fc60-ffffffff8136fc75: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81387fd0)
Location: fs/sysfs/group.c:172
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_add
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/cgroup/cgroup.c:cgroup_sysfs_init
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/ksm.c:ksm_init
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - block/blk-sysfs.c:blk_register_queue
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_set_fd
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81387fd0-ffffffff81387fe5: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813d2b80)
Location: fs/sysfs/group.c:172
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_node
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_add_dev
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_add
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/params.c:kernel_add_sysfs_param
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module.c:add_sect_attrs
  - kernel/cgroup/cgroup.c:cgroup_sysfs_init
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/ksm.c:ksm_init
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - block/blk-sysfs.c:blk_register_queue
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/attribute_container.c:attribute_container_add_attrs
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_configure
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff813d2b80-ffffffff813d2b95: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813e48e0)
Location: fs/sysfs/group.c:172
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_node
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_add_dev
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_add
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/params.c:kernel_add_sysfs_param
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module.c:add_sect_attrs
  - kernel/cgroup/cgroup.c:cgroup_sysfs_init
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/ksm.c:ksm_init
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - block/blk-sysfs.c:blk_register_queue
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/attribute_container.c:attribute_container_add_attrs
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_configure
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff813e48e0-ffffffff813e48f5: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813eb4e0)
Location: fs/sysfs/group.c:172
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_add
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module.c:add_sect_attrs
  - kernel/cgroup/cgroup.c:cgroup_sysfs_init
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/ksm.c:ksm_init
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - block/blk-sysfs.c:blk_register_queue
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/attribute_container.c:attribute_container_add_attrs
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_configure
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff813eb4e0-ffffffff813eb4f5: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8143d270)
Location: fs/sysfs/group.c:172
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_add
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module.c:add_sect_attrs
  - kernel/cgroup/cgroup.c:cgroup_sysfs_init
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/mempolicy.c:numa_init_sysfs
  - mm/ksm.c:ksm_init
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - block/blk-sysfs.c:blk_register_queue
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/attribute_container.c:attribute_container_add_attrs
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_configure
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_add_dev
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff8143d270-ffffffff8143d285: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff814b8a70)
Location: fs/sysfs/group.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_add
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module/sysfs.c:add_sect_attrs
  - kernel/cgroup/cgroup.c:cgroup_sysfs_init
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/ksm.c:ksm_init
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/migrate.c:numa_init_sysfs
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - block/blk-sysfs.c:blk_register_queue
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/attribute_container.c:attribute_container_add_attrs
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_configure
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_add_dev
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff814b8a70-ffffffff814b8a8f: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff815500e0)
Location: fs/sysfs/group.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:setup_online_cpu
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module/sysfs.c:add_sect_attrs
  - kernel/cgroup/cgroup.c:cgroup_sysfs_init
  - mm/vmscan.c:init_lru_gen
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/ksm.c:ksm_init
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/memory-tiers.c:numa_init_sysfs
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/attribute_container.c:attribute_container_add_attrs
  - drivers/base/transport_class.c:transport_add_class_device
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_configure
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_add_dev
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff815500e0-ffffffff815500ff: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81587de0)
Location: fs/sysfs/group.c:175
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:setup_online_cpu
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module/sysfs.c:add_sect_attrs
  - kernel/cgroup/cgroup.c:cgroup_sysfs_init
  - mm/vmscan.c:init_lru_gen
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/ksm.c:ksm_init
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/memory-tiers.c:numa_init_sysfs
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/attribute_container.c:attribute_container_add_attrs
  - drivers/base/transport_class.c:transport_add_class_device
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_configure
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
  - drivers/usb/host/xhci-dbgcap.c:xhci_alloc_dbc
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_add_dev
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/amd-pstate.c:amd_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81587de0-ffffffff81587dff: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff815c09a0)
Location: fs/sysfs/group.c:175
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module/sysfs.c:add_sect_attrs
  - kernel/cgroup/cgroup.c:cgroup_sysfs_init
  - mm/vmscan.c:init_lru_gen
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/ksm.c:ksm_init
  - mm/memory-tiers.c:numa_init_sysfs
  - mm/huge_memory.c:hugepage_init_sysfs
  - mm/huge_memory.c:hugepage_init_sysfs
  - mm/huge_memory.c:hugepage_init_sysfs
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/acpi_fpdt.c:fpdt_process_subtable
  - drivers/acpi/acpi_fpdt.c:fpdt_process_subtable
  - drivers/acpi/acpi_fpdt.c:fpdt_process_subtable
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/attribute_container.c:attribute_container_add_attrs
  - drivers/base/transport_class.c:transport_add_class_device
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_configure
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_add_dev
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/amd-pstate.c:amd_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff815c09a0-ffffffff815c09bf: sysfs_create_group (STB_GLOBAL)
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
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffff800010458198)
Location: fs/sysfs/group.c:172
Inline: False
Direct callers:
  - arch/arm64/kernel/cpuinfo.c:cpuid_cpu_online
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/cgroup/cgroup.c:cgroup_sysfs_init
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/ksm.c:ksm_init
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - block/blk-sysfs.c:blk_register_queue
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_set_fd
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/meson/meson_sm.c:meson_sm_probe
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffff800010458198-ffff8000104581d0: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (c0619d64)
Location: fs/sysfs/group.c:172
Inline: False
Direct callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/cgroup/cgroup.c:cgroup_sysfs_init
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/swap_state.c:swap_init_sysfs
  - mm/ksm.c:ksm_init
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - block/blk-sysfs.c:blk_register_queue
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_set_fd
  - drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
c0619d64-c0619d88: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (c000000000572b00)
Location: fs/sysfs/group.c:172
Inline: False
Direct callers:
  - arch/powerpc/kernel/sysfs.c:cpu_add_dev_attr_group
  - arch/powerpc/platforms/powernv/opal-flash.c:opal_flash_update_init
  - arch/powerpc/platforms/powernv/opal-dump.c:opal_platform_dump_init
  - arch/powerpc/platforms/powernv/opal-powercap.c:opal_powercap_init
  - arch/powerpc/platforms/powernv/opal-sensor-groups.c:opal_sensor_groups_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/cgroup/cgroup.c:cgroup_sysfs_init
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/ksm.c:ksm_init
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - block/blk-sysfs.c:blk_register_queue
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/attribute_container.c:attribute_container_add_attrs
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_set_fd
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_cpu_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
c000000000572b00-c000000000572b1c: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffe0002e9320)
Location: fs/sysfs/group.c:172
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/cgroup/cgroup.c:cgroup_sysfs_init
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/ksm.c:ksm_init
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - block/blk-sysfs.c:blk_register_queue
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_set_fd
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffe0002e9320-ffffffe0002e9354: sysfs_create_group (STB_GLOBAL)
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
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813805b0)
Location: fs/sysfs/group.c:172
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_add
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/cgroup/cgroup.c:cgroup_sysfs_init
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/ksm.c:ksm_init
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - block/blk-sysfs.c:blk_register_queue
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_set_fd
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff813805b0-ffffffff813805c5: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81371040)
Location: fs/sysfs/group.c:172
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_add
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/cgroup/cgroup.c:cgroup_sysfs_init
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/ksm.c:ksm_init
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - block/blk-sysfs.c:blk_register_queue
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_set_fd
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/hv/vmbus_drv.c:vmbus_add_channel_kobj
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81371040-ffffffff81371055: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8137e080)
Location: fs/sysfs/group.c:172
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_add
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/cgroup/cgroup.c:cgroup_sysfs_init
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/ksm.c:ksm_init
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - block/blk-sysfs.c:blk_register_queue
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_set_fd
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff8137e080-ffffffff8137e095: sysfs_create_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sysfs_create_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81391c80)
Location: fs/sysfs/group.c:172
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_add
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/hibernate.c:pm_disk_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/cgroup/cgroup.c:cgroup_sysfs_init
  - kernel/trace/blktrace.c:blk_trace_init_sysfs
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/ksm.c:ksm_init
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/page_idle.c:page_idle_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - block/blk-sysfs.c:blk_register_queue
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/pci/pci-label.c:pci_create_firmware_label_files
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_power_expose_list
  - drivers/acpi/sysfs.c:acpi_irq_stats_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/base/core.c:devm_device_add_group
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/block/loop.c:loop_set_fd
  - drivers/usb/core/sysfs.c:usb_create_sysfs_dev_files
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81391c80-ffffffff81391c95: sysfs_create_group (STB_GLOBAL)
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
