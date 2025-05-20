# Function: <code>kstrtoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814022b0)
Location: lib/kstrtox.c:249
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoint_from_user
Direct callers:
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/mm/tlb.c:tlbflush_write_file
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/reboot.c:reboot_setup
  - kernel/sched/core.c:setup_relax_domain_level
  - kernel/cgroup.c:__cgroup_procs_write
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_adj_write
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_store
  - drivers/base/power/sysfs.c:pm_qos_remote_wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/thermal/thermal_core.c:thermal_cooling_device_weight_store
  - drivers/thermal/thermal_core.c:offset_store
  - drivers/thermal/thermal_core.c:slope_store
  - drivers/thermal/thermal_core.c:integral_cutoff_store
  - drivers/thermal/thermal_core.c:k_d_store
  - drivers/thermal/thermal_core.c:k_i_store
  - drivers/thermal/thermal_core.c:k_pu_store
  - drivers/thermal/thermal_core.c:k_po_store
  - drivers/thermal/thermal_core.c:trip_point_hyst_store
```
**Symbols:**

```
ffffffff814022b0-ffffffff81402308: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81449f1d)
Location: lib/kstrtox.c:249
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoint_from_user
Direct callers:
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/mm/tlb.c:tlbflush_write_file
  - kernel/cpu.c:write_cpuhp_target
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/reboot.c:reboot_setup
  - kernel/sched/core.c:setup_relax_domain_level
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/base/power/sysfs.c:pm_qos_remote_wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_store
  - drivers/thermal/thermal_core.c:thermal_cooling_device_weight_store
  - drivers/thermal/thermal_core.c:offset_store
  - drivers/thermal/thermal_core.c:slope_store
  - drivers/thermal/thermal_core.c:integral_cutoff_store
  - drivers/thermal/thermal_core.c:k_d_store
  - drivers/thermal/thermal_core.c:k_i_store
  - drivers/thermal/thermal_core.c:k_pu_store
  - drivers/thermal/thermal_core.c:k_po_store
  - drivers/thermal/thermal_core.c:emul_temp_store
  - drivers/thermal/thermal_core.c:trip_point_hyst_store
  - drivers/thermal/thermal_core.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff81449e60-ffffffff81449eb8: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814688dd)
Location: lib/kstrtox.c:245
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoint_from_user
Direct callers:
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/mm/tlb.c:tlbflush_write_file
  - kernel/cpu.c:write_cpuhp_target
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/reboot.c:reboot_setup
  - kernel/sched/core.c:setup_relax_domain_level
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_delay_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/base/power/sysfs.c:pm_qos_remote_wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_store
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff81468820-ffffffff81468878: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8146dfc6)
Location: lib/kstrtox.c:247
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoint_from_user
Direct callers:
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/mm/tlb.c:tlbflush_write_file
  - kernel/cpu.c:write_cpuhp_target
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/reboot.c:reboot_setup
  - kernel/sched/topology.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_delay_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/power/sysfs.c:pm_qos_remote_wakeup_store
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_store
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff8146df10-ffffffff8146df6a: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8149a2f6)
Location: lib/kstrtox.c:248
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoint_from_user
Direct callers:
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/mm/tlb.c:tlbflush_write_file
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/reboot.c:reboot_setup
  - kernel/sched/topology.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_delay_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_store
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff8149a240-ffffffff8149a29a: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814cf5b6)
Location: lib/kstrtox.c:248
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoint_from_user
Direct callers:
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/mm/tlb.c:tlbflush_write_file
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/reboot.c:reboot_setup
  - kernel/sched/topology.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_delay_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/acpi/tables.c:acpi_parse_apic_instance
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/thermal/thermal_sysfs.c:weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff814cf4f0-ffffffff814cf54a: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814e3ec6)
Location: lib/kstrtox.c:248
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoint_from_user
Direct callers:
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/tlb.c:tlbflush_write_file
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/reboot.c:reboot_setup
  - kernel/sched/topology.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - mm/memcontrol.c:memory_oom_group_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_delay_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/acpi/tables.c:acpi_parse_apic_instance
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/dd.c:deferred_probe_timeout_setup
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/thermal/thermal_sysfs.c:weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff814e3e00-ffffffff814e3e5a: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815102a6)
Location: lib/kstrtox.c:248
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoint_from_user
Direct callers:
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/tlb.c:tlbflush_write_file
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/reboot.c:reboot_setup
  - kernel/sched/topology.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - mm/memcontrol.c:memory_oom_group_write
  - fs/fs_parser.c:fs_parse
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_delay_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/acpi/tables.c:acpi_parse_apic_instance
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/dd.c:deferred_probe_timeout_setup
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/thermal/thermal_sysfs.c:weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff815101e0-ffffffff8151023a: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8152e1a6)
Location: lib/kstrtox.c:248
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoint_from_user
Direct callers:
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/tlb.c:tlbflush_write_file
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/reboot.c:reboot_setup
  - kernel/sched/topology.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - mm/memcontrol.c:memory_oom_group_write
  - fs/fs_parser.c:fs_parse
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_delay_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/acpi/tables.c:acpi_parse_apic_instance
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/dd.c:deferred_probe_timeout_setup
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/thermal/thermal_sysfs.c:weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff8152e0e0-ffffffff8152e13a: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81591f46)
Location: lib/kstrtox.c:248
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoint_from_user
Direct callers:
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/tlb.c:tlbflush_write_file
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/reboot.c:reboot_setup
  - kernel/sched/fair.c:setup_sched_thermal_decay_shift
  - kernel/sched/topology.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - mm/memcontrol.c:memory_oom_group_write
  - fs/fs_parser.c:fs_param_is_s32
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_delay_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/acpi/tables.c:acpi_parse_apic_instance
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/dd.c:deferred_probe_timeout_setup
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/thermal/thermal_sysfs.c:weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff815923c0-ffffffff8159244d: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815aea86)
Location: lib/kstrtox.c:244
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoint_from_user
Direct callers:
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/tlb.c:tlbflush_write_file
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/sched/fair.c:setup_sched_thermal_decay_shift
  - kernel/sched/topology.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - mm/memcontrol.c:memory_oom_group_write
  - fs/fs_parser.c:fs_param_is_s32
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_delay_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/acpi/tables.c:acpi_parse_apic_instance
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/dd.c:deferred_probe_timeout_setup
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/dax/bus.c:create_store
  - drivers/scsi/sd.c:max_retries_store
  - drivers/thermal/thermal_sysfs.c:weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff815aef00-ffffffff815aef8d: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815b9586)
Location: lib/kstrtox.c:251
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoint_from_user
Direct callers:
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/tlb.c:tlbflush_write_file
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/sched/fair.c:setup_sched_thermal_decay_shift
  - kernel/sched/topology.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - mm/memcontrol.c:memory_oom_group_write
  - fs/fs_parser.c:fs_param_is_s32
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_delay_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/acpi/tables.c:acpi_parse_apic_instance
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/dd.c:deferred_probe_timeout_setup
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/dax/bus.c:create_store
  - drivers/scsi/sd.c:max_retries_store
  - drivers/thermal/thermal_sysfs.c:weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff815b9a00-ffffffff815b9a8d: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8161fe6c)
Location: lib/kstrtox.c:252
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoint_from_user
Direct callers:
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/tlb.c:tlbflush_write_file
  - kernel/cpu.c:fail_store
  - kernel/cpu.c:target_store
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/sched/fair.c:setup_sched_thermal_decay_shift
  - kernel/sched/topology.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - mm/memcontrol.c:memory_oom_group_write
  - fs/fs_parser.c:fs_param_is_s32
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_delay_store
  - block/mq-deadline.c:deadline_fifo_batch_store
  - block/mq-deadline.c:deadline_async_depth_store
  - block/mq-deadline.c:deadline_front_merges_store
  - block/mq-deadline.c:deadline_writes_starved_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/acpi/tables.c:acpi_parse_apic_instance
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/dd.c:deferred_probe_timeout_setup
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/dax/bus.c:create_store
  - drivers/scsi/sd.c:max_retries_store
  - drivers/thermal/thermal_sysfs.c:weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff81620350-ffffffff816203dd: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff816ee2c0)
Location: lib/kstrtox.c:259
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/tlb.c:tlbflush_write_file
  - kernel/cpu.c:fail_store
  - kernel/cpu.c:target_store
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/sched/fair.c:setup_sched_thermal_decay_shift
  - kernel/sched/build_utility.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - mm/memcontrol.c:memory_oom_group_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - block/blk-sysfs.c:queue_poll_delay_store
  - block/mq-deadline.c:deadline_fifo_batch_store
  - block/mq-deadline.c:deadline_async_depth_store
  - block/mq-deadline.c:deadline_front_merges_store
  - block/mq-deadline.c:deadline_writes_starved_store
  - block/mq-deadline.c:deadline_prio_aging_expire_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/kstrtox.c:kstrtoint_from_user
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/acpi/tables.c:acpi_parse_apic_instance
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/dd.c:deferred_probe_timeout_setup
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/block/loop.c:loop_set_hw_queue_depth
  - drivers/dax/bus.c:create_store
  - drivers/scsi/sd.c:max_retries_store
  - drivers/thermal/thermal_sysfs.c:weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/devfreq/devfreq.c:trans_stat_store
```
**Symbols:**

```
ffffffff816ee2c0-ffffffff816ee32b: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff817dedf0)
Location: lib/kstrtox.c:259
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/tlb.c:tlbflush_write_file
  - kernel/cpu.c:fail_store
  - kernel/cpu.c:target_store
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/sched/fair.c:setup_sched_thermal_decay_shift
  - kernel/sched/build_utility.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - mm/memcontrol.c:memory_oom_group_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - block/blk-sysfs.c:queue_poll_delay_store
  - block/mq-deadline.c:deadline_fifo_batch_store
  - block/mq-deadline.c:deadline_async_depth_store
  - block/mq-deadline.c:deadline_front_merges_store
  - block/mq-deadline.c:deadline_writes_starved_store
  - block/mq-deadline.c:deadline_prio_aging_expire_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/kstrtox.c:kstrtoint_from_user
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/acpi/tables.c:acpi_parse_apic_instance
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/dd.c:deferred_probe_timeout_setup
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/block/loop.c:loop_set_hw_queue_depth
  - drivers/dax/bus.c:create_store
  - drivers/scsi/sd.c:max_retries_store
  - drivers/thermal/thermal_sysfs.c:weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/devfreq/devfreq.c:trans_stat_store
```
**Symbols:**

```
ffffffff817dedf0-ffffffff817dee5b: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8181e5d0)
Location: lib/kstrtox.c:259
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/tlb.c:tlbflush_write_file
  - kernel/cpu.c:fail_store
  - kernel/cpu.c:target_store
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/sched/fair.c:setup_sched_thermal_decay_shift
  - kernel/sched/build_utility.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - mm/memcontrol.c:memory_oom_group_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - block/mq-deadline.c:deadline_fifo_batch_store
  - block/mq-deadline.c:deadline_async_depth_store
  - block/mq-deadline.c:deadline_front_merges_store
  - block/mq-deadline.c:deadline_writes_starved_store
  - block/mq-deadline.c:deadline_prio_aging_expire_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/kstrtox.c:kstrtoint_from_user
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/acpi/tables.c:acpi_parse_apic_instance
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/dd.c:deferred_probe_timeout_setup
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/block/loop.c:loop_set_hw_queue_depth
  - drivers/dax/bus.c:create_store
  - drivers/scsi/sd.c:max_retries_store
  - drivers/thermal/thermal_sysfs.c:weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/devfreq/devfreq.c:trans_stat_store
```
**Symbols:**

```
ffffffff8181e5d0-ffffffff8181e63b: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81864440)
Location: lib/kstrtox.c:259
Inline: False
Direct callers:
  - init/do_mounts.c:rootwait_timeout_setup
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/tlb.c:tlbflush_write_file
  - kernel/cpu.c:control_store
  - kernel/cpu.c:fail_store
  - kernel/cpu.c:target_store
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/sched/fair.c:setup_sched_thermal_decay_shift
  - kernel/sched/build_utility.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - mm/memcontrol.c:zswap_writeback_write
  - mm/memcontrol.c:memory_oom_group_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - block/mq-deadline.c:deadline_fifo_batch_store
  - block/mq-deadline.c:deadline_async_depth_store
  - block/mq-deadline.c:deadline_front_merges_store
  - block/mq-deadline.c:deadline_writes_starved_store
  - block/mq-deadline.c:deadline_prio_aging_expire_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/kstrtox.c:kstrtoint_from_user
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/acpi/tables.c:acpi_parse_apic_instance
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/dd.c:deferred_probe_timeout_setup
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/block/loop.c:loop_set_hw_queue_depth
  - drivers/dax/bus.c:create_store
  - drivers/scsi/sd.c:max_retries_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/thermal/thermal_sysfs.c:weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/cpufreq/cpufreq.c:store_local_boost
  - drivers/devfreq/devfreq.c:trans_stat_store
```
**Symbols:**

```
ffffffff81864440-ffffffff818644ab: kstrtoint (STB_GLOBAL)
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
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffff80001063a67c)
Location: lib/kstrtox.c:248
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoint_from_user
Direct callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
  - kernel/sched/topology.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - mm/memcontrol.c:memory_oom_group_write
  - fs/fs_parser.c:fs_parse
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_delay_store
  - drivers/bus/brcmstb_gisb.c:gisb_arb_set_timeout
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/acpi/tables.c:acpi_parse_apic_instance
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/dd.c:deferred_probe_timeout_setup
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/thermal/thermal_sysfs.c:weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/of/base.c:of_alias_scan
  - drivers/of/resolver.c:of_resolve_phandles
```
**Symbols:**

```
ffff80001063a598-ffff80001063a604: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (c07e0350)
Location: lib/kstrtox.c:248
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoint_from_user
Direct callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
  - kernel/sched/topology.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - mm/memcontrol.c:memory_oom_group_write
  - fs/fs_parser.c:fs_parse
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_delay_store
  - drivers/bus/brcmstb_gisb.c:gisb_arb_set_timeout
  - drivers/pwm/sysfs.c:enable_store
  - drivers/clk/ti/clk.c:ti_dt_clocks_register
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/dd.c:deferred_probe_timeout_setup
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/thermal/thermal_sysfs.c:weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/of/base.c:of_alias_scan
  - drivers/of/resolver.c:of_resolve_phandles
```
**Symbols:**

```
c07e0214-c07e0290: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (c0000000007e14f4)
Location: lib/kstrtox.c:248
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoint_from_user
Direct callers:
  - arch/powerpc/kernel/setup_64.c:check_smt_enabled
  - arch/powerpc/kernel/fadump.c:fadump_register_store
  - arch/powerpc/kernel/fadump.c:fadump_release_memory_store
  - arch/powerpc/platforms/powernv/opal-powercap.c:powercap_store
  - arch/powerpc/platforms/powernv/opal-psr.c:psr_store
  - arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_freq_write
  - arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_write
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
  - kernel/sched/topology.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - mm/memcontrol.c:memory_oom_group_write
  - fs/fs_parser.c:fs_parse
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_delay_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/dd.c:deferred_probe_timeout_setup
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/thermal/thermal_sysfs.c:weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/of/base.c:of_alias_scan
  - drivers/of/resolver.c:of_resolve_phandles
```
**Symbols:**

```
c0000000007e13d0-c0000000007e1460: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffe000466ca2)
Location: lib/kstrtox.c:248
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoint_from_user
Direct callers:
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
  - kernel/sched/topology.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - mm/memcontrol.c:memory_oom_group_write
  - fs/fs_parser.c:fs_parse
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_delay_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/dd.c:deferred_probe_timeout_setup
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/thermal/thermal_sysfs.c:weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/of/base.c:of_alias_scan
  - drivers/of/resolver.c:of_resolve_phandles
```
**Symbols:**

```
ffffffe000466c1a-ffffffe000466c56: kstrtoint (STB_GLOBAL)
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
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81526786)
Location: lib/kstrtox.c:248
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoint_from_user
Direct callers:
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/apic/io_apic.c:notimercheck
  - arch/x86/mm/tlb.c:tlbflush_write_file
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/reboot.c:reboot_setup
  - kernel/sched/topology.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - mm/memcontrol.c:memory_oom_group_write
  - fs/fs_parser.c:fs_parse
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_delay_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/acpi/tables.c:acpi_parse_apic_instance
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/dd.c:deferred_probe_timeout_setup
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/nvme/host/pci.c:io_queue_depth_set
  - drivers/thermal/thermal_sysfs.c:weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff815266c0-ffffffff8152671a: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81516a66)
Location: lib/kstrtox.c:248
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoint_from_user
Direct callers:
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/tlb.c:tlbflush_write_file
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/reboot.c:reboot_setup
  - kernel/sched/topology.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - mm/memcontrol.c:memory_oom_group_write
  - fs/fs_parser.c:fs_parse
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_delay_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/acpi/tables.c:acpi_parse_apic_instance
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/dd.c:deferred_probe_timeout_setup
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/nvme/host/pci.c:io_queue_depth_set
  - drivers/thermal/thermal_sysfs.c:weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff815169a0-ffffffff815169fa: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81522816)
Location: lib/kstrtox.c:248
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoint_from_user
Direct callers:
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/tlb.c:tlbflush_write_file
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/reboot.c:reboot_setup
  - kernel/sched/topology.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - mm/memcontrol.c:memory_oom_group_write
  - fs/fs_parser.c:fs_parse
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_delay_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/acpi/tables.c:acpi_parse_apic_instance
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/dd.c:deferred_probe_timeout_setup
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/thermal/thermal_sysfs.c:weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff81522750-ffffffff815227aa: kstrtoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int kstrtoint(const char *s, unsigned int base, int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8153c196)
Location: lib/kstrtox.c:248
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoint_from_user
Direct callers:
  - arch/x86/kernel/ksysfs.c:setup_data_data_read
  - arch/x86/kernel/ksysfs.c:type_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/tlb.c:tlbflush_write_file
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:write_cpuhp_target
  - kernel/params.c:param_set_int
  - kernel/ksysfs.c:rcu_normal_store
  - kernel/ksysfs.c:rcu_expedited_store
  - kernel/reboot.c:reboot_setup
  - kernel/sched/topology.c:setup_relax_domain_level
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - mm/ksm.c:max_page_sharing_store
  - mm/memcontrol.c:memory_oom_group_write
  - fs/fs_parser.c:fs_parse
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-sysfs.c:queue_poll_delay_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/acpi/tables.c:acpi_parse_apic_instance
  - drivers/tty/tty_io.c:tty_dev_name_to_number
  - drivers/base/dd.c:deferred_probe_timeout_setup
  - drivers/base/power/sysfs.c:pm_qos_no_power_off_store
  - drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store
  - drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store
  - drivers/thermal/thermal_sysfs.c:weight_store
  - drivers/thermal/thermal_sysfs.c:offset_store
  - drivers/thermal/thermal_sysfs.c:slope_store
  - drivers/thermal/thermal_sysfs.c:integral_cutoff_store
  - drivers/thermal/thermal_sysfs.c:k_d_store
  - drivers/thermal/thermal_sysfs.c:k_i_store
  - drivers/thermal/thermal_sysfs.c:k_pu_store
  - drivers/thermal/thermal_sysfs.c:k_po_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff8153c0d0-ffffffff8153c12a: kstrtoint (STB_GLOBAL)
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
