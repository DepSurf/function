# Function: <code>get_cpu_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff8154e7c0)
Location: drivers/base/cpu.c:382
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_is_hotpluggable
Direct callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_cpu_callback
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/topology.c:topology_cpu_callback
  - drivers/base/topology.c:topology_cpu_callback
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
```
**Symbols:**

```
ffffffff8154e7c0-ffffffff8154e7fd: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff815a0605)
Location: drivers/base/cpu.c:382
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_is_hotpluggable
Direct callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_cpu_callback
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/topology.c:topology_cpu_callback
  - drivers/base/topology.c:topology_cpu_callback
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
```
**Symbols:**

```
ffffffff815a05c0-ffffffff815a05f6: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff815cec45)
Location: drivers/base/cpu.c:383
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_is_hotpluggable
Direct callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
```
**Symbols:**

```
ffffffff815cec00-ffffffff815cec36: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff815e36b5)
Location: drivers/base/cpu.c:385
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_is_hotpluggable
Direct callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff815e3670-ffffffff815e36a6: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff8164a865)
Location: drivers/base/cpu.c:395
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_is_hotpluggable
Direct callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff8164a820-ffffffff8164a859: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff81686090)
Location: drivers/base/cpu.c:398
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/cpu.c:cpu_is_hotpluggable
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
```
**Symbols:**

```
ffffffff81686090-ffffffff816860ca: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff816a5d30)
Location: drivers/base/cpu.c:398
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/cpu.c:cpu_is_hotpluggable
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
```
**Symbols:**

```
ffffffff816a5d30-ffffffff816a5d6a: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff816dee10)
Location: drivers/base/cpu.c:398
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_online
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/cpu.c:cpu_is_hotpluggable
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
```
**Symbols:**

```
ffffffff816dee10-ffffffff816dee46: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff81703060)
Location: drivers/base/cpu.c:398
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_online
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/cpu.c:cpu_is_hotpluggable
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
```
**Symbols:**

```
ffffffff81703060-ffffffff81703096: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff817bd775)
Location: drivers/base/cpu.c:393
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_is_hotpluggable
  - drivers/base/cpu.c:cpu_is_hotpluggable
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_online
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_cstates_constrain
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_init
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
```
**Symbols:**

```
ffffffff817bd680-ffffffff817bd6b6: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff817d24e5)
Location: drivers/base/cpu.c:391
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_is_hotpluggable
  - drivers/base/cpu.c:cpu_is_hotpluggable
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_online
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_cstates_constrain
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_create_pd
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_init
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
```
**Symbols:**

```
ffffffff817d23f0-ffffffff817d2426: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff817b5f05)
Location: drivers/base/cpu.c:391
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_is_hotpluggable
  - drivers/base/cpu.c:cpu_is_hotpluggable
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_create_pd
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_offline
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
```
**Symbols:**

```
ffffffff817b5e10-ffffffff817b5e46: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff8183f425)
Location: drivers/base/cpu.c:391
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_is_hotpluggable
  - drivers/base/cpu.c:cpu_is_hotpluggable
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_create_pd
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_offline
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
```
**Symbols:**

```
ffffffff8183f310-ffffffff8183f36c: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff819824f5)
Location: drivers/base/cpu.c:391
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_is_hotpluggable
  - drivers/base/cpu.c:cpu_is_hotpluggable
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_create_pd
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:register_cpu_under_node
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_offline
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
```
**Symbols:**

```
ffffffff81981ef0-ffffffff81981f64: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff81af0355)
Location: drivers/base/cpu.c:391
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_is_hotpluggable
  - drivers/base/cpu.c:cpu_is_hotpluggable
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_online
  - arch/x86/kernel/cpu/microcode/core.c:setup_online_cpu
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_down_prep
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_create_pd
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:register_cpu_under_node
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_offline
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
```
**Symbols:**

```
ffffffff81aefc60-ffffffff81aefcd4: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff81b3e4b5)
Location: drivers/base/cpu.c:391
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_is_hotpluggable
  - drivers/base/cpu.c:cpu_is_hotpluggable
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_online
  - arch/x86/kernel/cpu/microcode/core.c:setup_online_cpu
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_down_prep
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_create_pd
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:register_cpu_under_node
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_offline
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
```
**Symbols:**

```
ffffffff81b3e040-ffffffff81b3e0b4: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff81b96145)
Location: drivers/base/cpu.c:420
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_is_hotpluggable
  - drivers/base/cpu.c:cpu_is_hotpluggable
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_down_prep
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:add_cpu
  - kernel/cpu.c:remove_cpu
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_create_pd
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/pmdomain/core.c:genpd_add_device
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:register_cpu_under_node
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_offline
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
```
**Symbols:**

```
ffffffff81b95c70-ffffffff81b95ce4: get_cpu_device (STB_GLOBAL)
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
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffff8000108eedf0)
Location: drivers/base/cpu.c:398
Inline: True
Direct callers:
  - arch/arm64/kernel/cpuinfo.c:cpuid_cpu_offline
  - arch/arm64/kernel/cpuinfo.c:cpuid_cpu_online
  - kernel/cpu.c:cpuhp_sysfs_init
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/cpu.c:cpu_is_hotpluggable
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/arch_topology.c:register_cpu_capacity_sysctl
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_register_em
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
  - drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/of/base.c:of_find_last_cache_level
  - drivers/of/base.c:of_cpu_node_to_id
```
**Symbols:**

```
ffff8000108eedf0-ffff8000108eee78: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (c09dc7f8)
Location: drivers/base/cpu.c:398
Inline: True
Direct callers:
  - arch/arm/kernel/cpuidle.c:arm_cpuidle_init
  - arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus
  - arch/arm/common/bL_switcher.c:bL_switcher_restore_cpus
  - arch/arm/mach-rockchip/platsmp.c:pmu_set_power_domain
  - arch/arm/mach-vexpress/spc.c:ve_spc_clk_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - drivers/clk/tegra/clk-tegra124-dfll-fcpu.c:tegra124_dfll_fcpu_probe
  - drivers/soc/qcom/spm.c:spm_dev_probe
  - drivers/soc/qcom/spm.c:qcom_cpuidle_init
  - drivers/base/cpu.c:cpu_is_hotpluggable
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/arch_topology.c:register_cpu_capacity_sysctl
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_register_em
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
  - drivers/opp/ti-opp-supply.c:ti_opp_supply_probe
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
  - drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init
  - drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init
  - drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe
  - drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe
  - drivers/cpufreq/ti-cpufreq.c:ti_cpufreq_probe
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/of/base.c:of_find_last_cache_level
  - drivers/of/base.c:of_cpu_node_to_id
```
**Symbols:**

```
c09dc7f8-c09dc870: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (c000000000987c00)
Location: drivers/base/cpu.c:398
Inline: True
Direct callers:
  - arch/powerpc/kernel/sysfs.c:cpu_remove_dev_attr_group
  - arch/powerpc/kernel/sysfs.c:cpu_remove_dev_attr
  - arch/powerpc/kernel/sysfs.c:cpu_add_dev_attr_group
  - arch/powerpc/kernel/sysfs.c:cpu_add_dev_attr
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online
  - arch/powerpc/kernel/rtas.c:rtas_cpu_state_change_mask
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_readd
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_remove
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_online_cpu
  - kernel/cpu.c:cpuhp_sysfs_init
  - drivers/base/cpu.c:cpu_is_hotpluggable
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_register_em
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/of/base.c:of_find_last_cache_level
  - drivers/of/base.c:of_cpu_node_to_id
```
**Symbols:**

```
c000000000987c00-c000000000987c88: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffe00058185a)
Location: drivers/base/cpu.c:398
Inline: True
Direct callers:
  - arch/riscv/kernel/cacheinfo.c:_populate_cache_leaves
  - arch/riscv/kernel/cacheinfo.c:_init_cache_level
  - drivers/base/cpu.c:cpu_is_hotpluggable
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/arch_topology.c:register_cpu_capacity_sysctl
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_register_em
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
  - drivers/of/base.c:of_find_last_cache_level
  - drivers/of/base.c:of_cpu_node_to_id
```
**Symbols:**

```
ffffffe00058185a-ffffffe0005818d4: get_cpu_device (STB_GLOBAL)
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
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff816c87b0)
Location: drivers/base/cpu.c:398
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_online
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/cpu.c:cpu_is_hotpluggable
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
```
**Symbols:**

```
ffffffff816c87b0-ffffffff816c87e6: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff816a3ae0)
Location: drivers/base/cpu.c:398
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_online
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/base/cpu.c:cpu_is_hotpluggable
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
```
**Symbols:**

```
ffffffff816a3ae0-ffffffff816a3b16: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff816f6d20)
Location: drivers/base/cpu.c:398
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_online
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/cpu.c:cpu_is_hotpluggable
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
```
**Symbols:**

```
ffffffff816f6d20-ffffffff816f6d56: get_cpu_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct device *get_cpu_device(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff817115c0)
Location: drivers/base/cpu.c:398
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_online
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_online
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
  - drivers/base/cpu.c:cpu_is_hotpluggable
  - drivers/base/topology.c:topology_remove_dev
  - drivers/base/topology.c:topology_add_dev
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
```
**Symbols:**

```
ffffffff817115c0-ffffffff817115f6: get_cpu_device (STB_GLOBAL)
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
