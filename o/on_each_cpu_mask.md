# Function: <code>on_each_cpu_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void on_each_cpu_mask(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81103f10)
Location: kernel/smp.c:622
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_count
  - arch/x86/events/intel/cqm.c:intel_cqm_event_count
  - arch/x86/events/intel/cqm.c:intel_cqm_event_init
  - arch/x86/events/intel/cqm.c:intel_cqm_event_init
  - arch/x86/events/intel/cqm.c:intel_cqm_event_init
  - arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid
  - arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid
  - arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid
  - arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid
  - arch/x86/events/intel/cqm.c:intel_cqm_event_destroy
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/smp.c:on_each_cpu_cond
  - mm/page_alloc.c:drain_all_pages
  - drivers/cpuidle/driver.c:cpuidle_register_driver
  - drivers/cpuidle/driver.c:cpuidle_unregister_driver
  - net/core/flow.c:flow_cache_flush
  - net/core/flow.c:flow_cache_flush
```
**Symbols:**

```
ffffffff81103f10-ffffffff81103f6f: on_each_cpu_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void on_each_cpu_mask(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8110b320)
Location: kernel/smp.c:607
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_init
  - arch/x86/events/intel/cqm.c:intel_cqm_event_init
  - arch/x86/events/intel/cqm.c:intel_cqm_event_init
  - arch/x86/events/intel/cqm.c:intel_cqm_event_destroy
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
  - arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid
  - arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/smp.c:on_each_cpu_cond
  - mm/page_alloc.c:drain_all_pages
  - drivers/cpuidle/driver.c:cpuidle_unregister_driver
  - drivers/cpuidle/driver.c:cpuidle_register_driver
  - net/core/flow.c:flow_cache_flush
```
**Symbols:**

```
ffffffff8110b320-ffffffff8110b37b: on_each_cpu_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void on_each_cpu_mask(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81112cb0)
Location: kernel/smp.c:614
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_init
  - arch/x86/events/intel/cqm.c:intel_cqm_event_init
  - arch/x86/events/intel/cqm.c:intel_cqm_event_init
  - arch/x86/events/intel/cqm.c:intel_cqm_event_destroy
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
  - arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid
  - arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/smp.c:on_each_cpu_cond
  - mm/page_alloc.c:drain_all_pages
  - drivers/cpuidle/driver.c:cpuidle_unregister_driver
  - drivers/cpuidle/driver.c:cpuidle_register_driver
  - net/core/flow.c:flow_cache_flush
```
**Symbols:**

```
ffffffff81112cb0-ffffffff81112d0b: on_each_cpu_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void on_each_cpu_mask(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811141c0)
Location: kernel/smp.c:625
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/smp.c:on_each_cpu_cond
  - drivers/cpuidle/driver.c:cpuidle_unregister_driver
  - drivers/cpuidle/driver.c:cpuidle_register_driver
  - net/core/flow.c:flow_cache_flush
```
**Symbols:**

```
ffffffff811141c0-ffffffff8111421b: on_each_cpu_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void on_each_cpu_mask(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8111f730)
Location: kernel/smp.c:627
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/smp.c:on_each_cpu_cond
  - drivers/cpuidle/driver.c:cpuidle_unregister_driver
  - drivers/cpuidle/driver.c:cpuidle_register_driver
```
**Symbols:**

```
ffffffff8111f730-ffffffff8111f78d: on_each_cpu_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void on_each_cpu_mask(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8112ca60)
Location: kernel/smp.c:629
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/smp.c:on_each_cpu_cond
  - drivers/cpuidle/driver.c:cpuidle_unregister_driver
  - drivers/cpuidle/driver.c:cpuidle_register_driver
```
**Symbols:**

```
ffffffff8112ca60-ffffffff8112cac6: on_each_cpu_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void on_each_cpu_mask(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81138330)
Location: kernel/smp.c:627
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/smp.c:on_each_cpu_cond_mask
  - drivers/cpuidle/driver.c:cpuidle_unregister_driver
  - drivers/cpuidle/driver.c:cpuidle_register_driver
```
**Symbols:**

```
ffffffff81138330-ffffffff81138396: on_each_cpu_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void on_each_cpu_mask(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811434f0)
Location: kernel/smp.c:640
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/smp.c:on_each_cpu_cond_mask
  - drivers/cpuidle/driver.c:cpuidle_unregister_driver
  - drivers/cpuidle/driver.c:cpuidle_register_driver
```
**Symbols:**

```
ffffffff811434f0-ffffffff81143557: on_each_cpu_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void on_each_cpu_mask(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8114f030)
Location: kernel/smp.c:640
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/smp.c:on_each_cpu_cond_mask
```
**Symbols:**

```
ffffffff8114f030-ffffffff8114f097: on_each_cpu_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void on_each_cpu_mask(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115f940)
Location: kernel/smp.c:723
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
**Symbols:**

```
ffffffff8115f940-ffffffff8115f9aa: on_each_cpu_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void on_each_cpu_mask(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115b8e0)
Location: kernel/smp.c:860
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - kernel/sched/membarrier.c:membarrier_private_expedited
```
**Symbols:**

```
ffffffff8115b8e0-ffffffff8115b94a: on_each_cpu_mask (STB_GLOBAL)
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
In arch/x86/events/core.c (ffffffff81005f78)
Location: include/linux/smp.h:90
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff8103b170)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810687d0)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
```
In arch/x86/mm/tlb.c (ffffffff8108c1e7)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
```
```
In kernel/sched/membarrier.c (ffffffff8110af19)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
```
```
In drivers/iommu/intel/svm.c (ffffffff817993ff)
Location: include/linux/smp.h:90
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81981dcd)
Location: include/linux/smp.h:90
Inline: True
```
```
In drivers/cpuidle/driver.c (ffffffff81989af8)
Location: include/linux/smp.h:90
Inline: True
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
In arch/x86/events/core.c (ffffffff81006628)
Location: include/linux/smp.h:90
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff81040ba0)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072dde)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
```
In arch/x86/mm/tlb.c (ffffffff8109b9f3)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
```
```
In kernel/sched/membarrier.c (ffffffff81129748)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
```
```
In drivers/iommu/intel/svm.c (ffffffff81821939)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81a2b0fd)
Location: include/linux/smp.h:90
Inline: True
```
```
In drivers/cpuidle/driver.c (ffffffff81a342ed)
Location: include/linux/smp.h:90
Inline: True
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
In arch/x86/events/core.c (ffffffff81005a1a)
Location: include/linux/smp.h:90
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff810484e8)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810811e6)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
```
In arch/x86/mm/tlb.c (ffffffff810aee29)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
```
```
In kernel/sched/build_utility.c (ffffffff8113de12)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81b9569d)
Location: include/linux/smp.h:90
Inline: True
```
```
In drivers/cpuidle/driver.c (ffffffff81ba09ef)
Location: include/linux/smp.h:90
Inline: True
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
In arch/x86/events/core.c (ffffffff81006f8a)
Location: include/linux/smp.h:90
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff81053248)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81091eaf)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810938b6)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
```
In arch/x86/mm/tlb.c (ffffffff810c91ad)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
```
```
In kernel/sched/build_utility.c (ffffffff8116dd20)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d35f4d)
Location: include/linux/smp.h:90
Inline: True
```
```
In drivers/cpuidle/driver.c (ffffffff81d4267f)
Location: include/linux/smp.h:90
Inline: True
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
In arch/x86/events/core.c (ffffffff8100672a)
Location: include/linux/smp.h:90
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff81054222)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089d21)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108e98e)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81094def)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096836)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
```
In arch/x86/mm/tlb.c (ffffffff810cc83d)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
```
```
In kernel/sched/build_utility.c (ffffffff8117e2e6)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d9f2c6)
Location: include/linux/smp.h:90
Inline: True
```
```
In drivers/cpuidle/driver.c (ffffffff81dac85f)
Location: include/linux/smp.h:90
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100be2a)
Location: include/linux/smp.h:90
Inline: True
```
```
In arch/x86/kernel/ldt.c (ffffffff8105b452)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81090e3a)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81095d1e)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109c2ff)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109dda6)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
```
In arch/x86/mm/tlb.c (ffffffff810d4ecd)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
```
```
In kernel/sched/build_utility.c (ffffffff8118be82)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
```
```
In kernel/trace/trace.c (ffffffff8129ef4e)
Location: include/linux/smp.h:90
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_disable
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e570d6)
Location: include/linux/smp.h:90
Inline: True
```
```
In drivers/cpuidle/driver.c (ffffffff81e648ff)
Location: include/linux/smp.h:90
Inline: True
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
void on_each_cpu_mask(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffff8000101bd6b0)
Location: kernel/smp.c:640
Inline: False
Direct callers:
  - kernel/smp.c:on_each_cpu_cond_mask
```
**Symbols:**

```
ffff8000101bd6b0-ffff8000101bd764: on_each_cpu_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void on_each_cpu_mask(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c040581c)
Location: kernel/smp.c:640
Inline: False
Direct callers:
  - arch/arm/kernel/smp_tlb.c:flush_tlb_range
  - arch/arm/kernel/smp_tlb.c:flush_tlb_page
  - arch/arm/kernel/smp_tlb.c:flush_tlb_mm
  - kernel/smp.c:on_each_cpu_cond_mask
```
**Symbols:**

```
c040581c-c040588c: on_each_cpu_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void on_each_cpu_mask(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c000000000223b10)
Location: kernel/smp.c:640
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
  - kernel/smp.c:on_each_cpu_cond_mask
```
**Symbols:**

```
c000000000223b10-c000000000223bb8: on_each_cpu_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void on_each_cpu_mask(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffe000140c24)
Location: kernel/smp.c:640
Inline: False
Direct callers:
  - kernel/smp.c:on_each_cpu_cond_mask
```
**Symbols:**

```
ffffffe000140c24-ffffffe000140c9a: on_each_cpu_mask (STB_GLOBAL)
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
void on_each_cpu_mask(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81147650)
Location: kernel/smp.c:640
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/smp.c:on_each_cpu_cond_mask
```
**Symbols:**

```
ffffffff81147650-ffffffff811476b7: on_each_cpu_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void on_each_cpu_mask(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8113a920)
Location: kernel/smp.c:640
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/smp.c:on_each_cpu_cond_mask
```
**Symbols:**

```
ffffffff8113a920-ffffffff8113a968: on_each_cpu_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void on_each_cpu_mask(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81145500)
Location: kernel/smp.c:640
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/smp.c:on_each_cpu_cond_mask
```
**Symbols:**

```
ffffffff81145500-ffffffff81145567: on_each_cpu_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void on_each_cpu_mask(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811520f0)
Location: kernel/smp.c:640
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - kernel/smp.c:on_each_cpu_cond_mask
```
**Symbols:**

```
ffffffff811520f0-ffffffff8115216e: on_each_cpu_mask (STB_GLOBAL)
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
