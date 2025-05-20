# Function: <code>sysfs_emit_at</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sysfs_emit_at(char *buf, int at, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813e34b0)
Location: fs/sysfs/file.c:749
Inline: False
Direct callers:
  - mm/shmem.c:shmem_enabled_show
  - mm/shmem.c:shmem_enabled_show
  - mm/shmem.c:shmem_enabled_show
  - mm/hugetlb.c:hugetlb_report_node_meminfo
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - drivers/base/core.c:uevent_show
  - drivers/base/cpu.c:print_cpu_modalias
  - drivers/base/cpu.c:print_cpu_modalias
  - drivers/base/cpu.c:print_cpu_modalias
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/node.c:node_read_distance
  - drivers/base/node.c:node_read_distance
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff813e34b0-ffffffff813e3553: sysfs_emit_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sysfs_emit_at(char *buf, int at, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813ea0f0)
Location: fs/sysfs/file.c:760
Inline: False
Direct callers:
  - mm/shmem.c:shmem_enabled_show
  - mm/shmem.c:shmem_enabled_show
  - mm/shmem.c:shmem_enabled_show
  - mm/hugetlb.c:hugetlb_report_node_meminfo
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - mm/slub.c:list_locations
  - drivers/pci/pci-sysfs.c:resource_show
  - drivers/base/core.c:uevent_show
  - drivers/base/cpu.c:print_cpu_modalias
  - drivers/base/cpu.c:print_cpu_modalias
  - drivers/base/cpu.c:print_cpu_modalias
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/node.c:node_read_distance
  - drivers/base/node.c:node_read_distance
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff813ea0f0-ffffffff813ea18f: sysfs_emit_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sysfs_emit_at(char *buf, int at, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8143be70)
Location: fs/sysfs/file.c:760
Inline: False
Direct callers:
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - mm/shmem.c:shmem_enabled_show
  - mm/shmem.c:shmem_enabled_show
  - mm/shmem.c:shmem_enabled_show
  - mm/hugetlb.c:hugetlb_report_node_meminfo
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - drivers/pci/pci.c:reset_method_show
  - drivers/pci/pci.c:reset_method_show
  - drivers/pci/pci-sysfs.c:resource_show
  - drivers/pci/pcie/aer.c:aer_dev_nonfatal_show
  - drivers/pci/pcie/aer.c:aer_dev_nonfatal_show
  - drivers/pci/pcie/aer.c:aer_dev_nonfatal_show
  - drivers/pci/pcie/aer.c:aer_dev_fatal_show
  - drivers/pci/pcie/aer.c:aer_dev_fatal_show
  - drivers/pci/pcie/aer.c:aer_dev_fatal_show
  - drivers/pci/pcie/aer.c:aer_dev_correctable_show
  - drivers/pci/pcie/aer.c:aer_dev_correctable_show
  - drivers/pci/pcie/aer.c:aer_dev_correctable_show
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/base/core.c:uevent_show
  - drivers/base/cpu.c:print_cpu_modalias
  - drivers/base/cpu.c:print_cpu_modalias
  - drivers/base/cpu.c:print_cpu_modalias
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/node.c:node_read_distance
  - drivers/base/node.c:node_read_distance
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_available_governors_get
```
**Symbols:**

```
ffffffff8143be70-ffffffff8143bf0f: sysfs_emit_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sysfs_emit_at(char *buf, int at, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff814b7310)
Location: fs/sysfs/file.c:757
Inline: False
Direct callers:
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - mm/shmem.c:shmem_enabled_show
  - mm/shmem.c:shmem_enabled_show
  - mm/hugetlb.c:hugetlb_report_node_meminfo
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - drivers/pci/pci.c:reset_method_show
  - drivers/pci/pci.c:reset_method_show
  - drivers/pci/pci-sysfs.c:resource_show
  - drivers/pci/pcie/aer.c:aer_dev_nonfatal_show
  - drivers/pci/pcie/aer.c:aer_dev_nonfatal_show
  - drivers/pci/pcie/aer.c:aer_dev_nonfatal_show
  - drivers/pci/pcie/aer.c:aer_dev_fatal_show
  - drivers/pci/pcie/aer.c:aer_dev_fatal_show
  - drivers/pci/pcie/aer.c:aer_dev_fatal_show
  - drivers/pci/pcie/aer.c:aer_dev_correctable_show
  - drivers/pci/pcie/aer.c:aer_dev_correctable_show
  - drivers/pci/pcie/aer.c:aer_dev_correctable_show
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/base/core.c:uevent_show
  - drivers/base/cpu.c:print_cpu_modalias
  - drivers/base/cpu.c:print_cpu_modalias
  - drivers/base/cpu.c:print_cpu_modalias
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/node.c:node_read_distance
  - drivers/base/node.c:node_read_distance
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_show
  - drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_show
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_available_governors_get
```
**Symbols:**

```
ffffffff814b7310-ffffffff814b73db: sysfs_emit_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sysfs_emit_at(char *buf, int at, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8154e660)
Location: fs/sysfs/file.c:757
Inline: False
Direct callers:
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - mm/shmem.c:shmem_enabled_show
  - mm/shmem.c:shmem_enabled_show
  - mm/hugetlb.c:hugetlb_report_node_meminfo
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - drivers/pci/pci.c:reset_method_show
  - drivers/pci/pci.c:reset_method_show
  - drivers/pci/pci-sysfs.c:resource_show
  - drivers/pci/pcie/aer.c:aer_dev_nonfatal_show
  - drivers/pci/pcie/aer.c:aer_dev_nonfatal_show
  - drivers/pci/pcie/aer.c:aer_dev_nonfatal_show
  - drivers/pci/pcie/aer.c:aer_dev_fatal_show
  - drivers/pci/pcie/aer.c:aer_dev_fatal_show
  - drivers/pci/pcie/aer.c:aer_dev_fatal_show
  - drivers/pci/pcie/aer.c:aer_dev_correctable_show
  - drivers/pci/pcie/aer.c:aer_dev_correctable_show
  - drivers/pci/pcie/aer.c:aer_dev_correctable_show
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/acpi/fan_attr.c:show_state
  - drivers/acpi/fan_attr.c:show_state
  - drivers/acpi/fan_attr.c:show_state
  - drivers/acpi/fan_attr.c:show_state
  - drivers/acpi/fan_attr.c:show_state
  - drivers/acpi/fan_attr.c:show_state
  - drivers/acpi/fan_attr.c:show_state
  - drivers/acpi/fan_attr.c:show_state
  - drivers/virtio/virtio.c:features_show
  - drivers/virtio/virtio.c:features_show
  - drivers/base/core.c:uevent_show
  - drivers/base/cpu.c:print_cpu_modalias
  - drivers/base/cpu.c:print_cpu_modalias
  - drivers/base/cpu.c:print_cpu_modalias
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/node.c:node_read_distance
  - drivers/base/node.c:node_read_distance
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_show
  - drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_show
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_available_governors_get
  - drivers/cpufreq/cpufreq_stats.c:show_trans_table
  - drivers/cpufreq/cpufreq_stats.c:show_trans_table
  - drivers/cpufreq/cpufreq_stats.c:show_trans_table
  - drivers/cpufreq/cpufreq_stats.c:show_trans_table
  - drivers/cpufreq/cpufreq_stats.c:show_trans_table
  - drivers/cpufreq/cpufreq_stats.c:show_trans_table
  - drivers/cpufreq/cpufreq_stats.c:show_trans_table
```
**Symbols:**

```
ffffffff8154e660-ffffffff8154e72b: sysfs_emit_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sysfs_emit_at(char *buf, int at, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81586320)
Location: fs/sysfs/file.c:757
Inline: False
Direct callers:
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - mm/shmem.c:shmem_enabled_show
  - mm/shmem.c:shmem_enabled_show
  - mm/shmem.c:shmem_enabled_show
  - mm/dmapool.c:pools_show
  - mm/hugetlb.c:hugetlb_report_node_meminfo
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - drivers/pci/pci.c:reset_method_show
  - drivers/pci/pci.c:reset_method_show
  - drivers/pci/pci-sysfs.c:resource_show
  - drivers/pci/pcie/aer.c:aer_dev_nonfatal_show
  - drivers/pci/pcie/aer.c:aer_dev_nonfatal_show
  - drivers/pci/pcie/aer.c:aer_dev_nonfatal_show
  - drivers/pci/pcie/aer.c:aer_dev_fatal_show
  - drivers/pci/pcie/aer.c:aer_dev_fatal_show
  - drivers/pci/pcie/aer.c:aer_dev_fatal_show
  - drivers/pci/pcie/aer.c:aer_dev_correctable_show
  - drivers/pci/pcie/aer.c:aer_dev_correctable_show
  - drivers/pci/pcie/aer.c:aer_dev_correctable_show
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/acpi/fan_attr.c:show_state
  - drivers/acpi/fan_attr.c:show_state
  - drivers/acpi/fan_attr.c:show_state
  - drivers/acpi/fan_attr.c:show_state
  - drivers/acpi/fan_attr.c:show_state
  - drivers/acpi/fan_attr.c:show_state
  - drivers/acpi/fan_attr.c:show_state
  - drivers/acpi/fan_attr.c:show_state
  - drivers/virtio/virtio.c:features_show
  - drivers/virtio/virtio.c:features_show
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
  - drivers/base/core.c:uevent_show
  - drivers/base/cpu.c:print_cpu_modalias
  - drivers/base/cpu.c:print_cpu_modalias
  - drivers/base/cpu.c:print_cpu_modalias
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/node.c:node_read_distance
  - drivers/base/node.c:node_read_distance
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_show
  - drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_show
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/thermal/thermal_core.c:thermal_build_list_of_policies
  - drivers/thermal/thermal_core.c:thermal_build_list_of_policies
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_available_governors_get
  - drivers/cpufreq/cpufreq_stats.c:show_trans_table
  - drivers/cpufreq/cpufreq_stats.c:show_trans_table
  - drivers/cpufreq/cpufreq_stats.c:show_trans_table
  - drivers/cpufreq/cpufreq_stats.c:show_trans_table
  - drivers/cpufreq/cpufreq_stats.c:show_trans_table
  - drivers/cpufreq/cpufreq_stats.c:show_trans_table
  - drivers/cpufreq/cpufreq_stats.c:show_trans_table
  - drivers/cpufreq/amd-pstate.c:show_energy_performance_available_preferences
  - drivers/cpufreq/amd-pstate.c:show_energy_performance_available_preferences
  - drivers/extcon/extcon.c:state_show
```
**Symbols:**

```
ffffffff81586320-ffffffff815863eb: sysfs_emit_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sysfs_emit_at(char *buf, int at, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff815bee00)
Location: fs/sysfs/file.c:770
Inline: False
Direct callers:
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - mm/shmem.c:shmem_enabled_show
  - mm/shmem.c:shmem_enabled_show
  - mm/shmem.c:shmem_enabled_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/dmapool.c:pools_show
  - mm/hugetlb.c:hugetlb_report_node_meminfo
  - drivers/pci/pci.c:reset_method_show
  - drivers/pci/pci.c:reset_method_show
  - drivers/pci/pci-sysfs.c:resource_show
  - drivers/pci/pcie/aer.c:aer_dev_nonfatal_show
  - drivers/pci/pcie/aer.c:aer_dev_nonfatal_show
  - drivers/pci/pcie/aer.c:aer_dev_nonfatal_show
  - drivers/pci/pcie/aer.c:aer_dev_fatal_show
  - drivers/pci/pcie/aer.c:aer_dev_fatal_show
  - drivers/pci/pcie/aer.c:aer_dev_fatal_show
  - drivers/pci/pcie/aer.c:aer_dev_correctable_show
  - drivers/pci/pcie/aer.c:aer_dev_correctable_show
  - drivers/pci/pcie/aer.c:aer_dev_correctable_show
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/acpi/fan_attr.c:show_state
  - drivers/acpi/fan_attr.c:show_state
  - drivers/acpi/fan_attr.c:show_state
  - drivers/acpi/fan_attr.c:show_state
  - drivers/acpi/fan_attr.c:show_state
  - drivers/acpi/fan_attr.c:show_state
  - drivers/acpi/fan_attr.c:show_state
  - drivers/acpi/fan_attr.c:show_state
  - drivers/virtio/virtio.c:features_show
  - drivers/virtio/virtio.c:features_show
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
  - drivers/base/core.c:uevent_show
  - drivers/base/cpu.c:print_cpu_modalias
  - drivers/base/cpu.c:print_cpu_modalias
  - drivers/base/cpu.c:print_cpu_modalias
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/base/node.c:node_read_distance
  - drivers/base/node.c:node_read_distance
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/input/vivaldi-fmap.c:vivaldi_function_row_physmap_show
  - drivers/input/vivaldi-fmap.c:vivaldi_function_row_physmap_show
  - drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_show
  - drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_show
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/thermal/thermal_core.c:thermal_build_list_of_policies
  - drivers/thermal/thermal_core.c:thermal_build_list_of_policies
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_available_governors_get
  - drivers/cpufreq/cpufreq_stats.c:show_trans_table
  - drivers/cpufreq/cpufreq_stats.c:show_trans_table
  - drivers/cpufreq/cpufreq_stats.c:show_trans_table
  - drivers/cpufreq/cpufreq_stats.c:show_trans_table
  - drivers/cpufreq/cpufreq_stats.c:show_trans_table
  - drivers/cpufreq/cpufreq_stats.c:show_trans_table
  - drivers/cpufreq/cpufreq_stats.c:show_trans_table
  - drivers/devfreq/devfreq.c:trans_stat_show
  - drivers/devfreq/devfreq.c:trans_stat_show
  - drivers/devfreq/devfreq.c:trans_stat_show
  - drivers/devfreq/devfreq.c:trans_stat_show
  - drivers/devfreq/devfreq.c:trans_stat_show
  - drivers/devfreq/devfreq.c:trans_stat_show
  - drivers/devfreq/devfreq.c:trans_stat_show
  - drivers/devfreq/devfreq.c:trans_stat_show
  - drivers/devfreq/devfreq.c:trans_stat_show
  - drivers/devfreq/devfreq.c:trans_stat_show
  - drivers/extcon/extcon.c:state_show
```
**Symbols:**

```
ffffffff815bee00-ffffffff815beecb: sysfs_emit_at (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
