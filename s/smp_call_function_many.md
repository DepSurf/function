# Function: <code>smp_call_function_many</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81103ba0)
Location: kernel/smp.c:404
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu
  - kernel/smp.c:on_each_cpu_mask
  - mm/rmap.c:try_to_unmap_flush
  - arch/x86/lib/msr-smp.c:__rwmsr_on_cpus
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
**Symbols:**

```
ffffffff81103ba0-ffffffff81103df2: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8110afc0)
Location: kernel/smp.c:388
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
  - arch/x86/lib/msr-smp.c:__rwmsr_on_cpus
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
**Symbols:**

```
ffffffff8110afc0-ffffffff8110b20b: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811129a0)
Location: kernel/smp.c:392
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_update_closid
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
  - arch/x86/lib/msr-smp.c:__rwmsr_on_cpus
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
**Symbols:**

```
ffffffff811129a0-ffffffff81112be5: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81113e90)
Location: kernel/smp.c:401
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:update_closid_rmid
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
  - arch/x86/lib/msr-smp.c:__rwmsr_on_cpus
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
**Symbols:**

```
ffffffff81113e90-ffffffff811140fe: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8111f420)
Location: kernel/smp.c:403
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:update_closid_rmid
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - kernel/sched/membarrier.c:SyS_membarrier
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_disable
  - arch/x86/lib/msr-smp.c:__rwmsr_on_cpus
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
**Symbols:**

```
ffffffff8111f420-ffffffff8111f66d: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8112c750)
Location: kernel/smp.c:403
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:update_closid_rmid
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_disable
  - arch/x86/lib/msr-smp.c:__rwmsr_on_cpus
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
**Symbols:**

```
ffffffff8112c750-ffffffff8112c99c: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81138020)
Location: kernel/smp.c:403
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_disable
  - arch/x86/lib/msr-smp.c:__rwmsr_on_cpus
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
**Symbols:**

```
ffffffff81138020-ffffffff8113826c: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811431c0)
Location: kernel/smp.c:412
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_disable
  - arch/x86/lib/msr-smp.c:__rwmsr_on_cpus
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
**Symbols:**

```
ffffffff811431c0-ffffffff81143427: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8114ed00)
Location: kernel/smp.c:412
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:reset_with_ipi
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
  - arch/x86/lib/msr-smp.c:__rwmsr_on_cpus
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
**Symbols:**

```
ffffffff8114ed00-ffffffff8114ef67: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115fa6f)
Location: kernel/smp.c:574
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:reset_with_ipi
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_disable
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
  - drivers/cpufreq/acpi-cpufreq.c:drv_write
```
**Symbols:**

```
ffffffff8115f8f0-ffffffff8115f906: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115ba0f)
Location: kernel/smp.c:712
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_disable
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
  - drivers/cpufreq/acpi-cpufreq.c:drv_write
```
**Symbols:**

```
ffffffff8115b890-ffffffff8115b8a6: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115c9cf)
Location: kernel/smp.c:988
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_disable
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
**Symbols:**

```
ffffffff8115c950-ffffffff8115c966: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81181b7f)
Location: kernel/smp.c:990
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/time/hrtimer.c:clock_was_set
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
**Symbols:**

```
ffffffff81181b00-ffffffff81181b16: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811b8266)
Location: kernel/smp.c:1009
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/time/hrtimer.c:clock_was_set
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
**Symbols:**

```
ffffffff811b8160-ffffffff811b8185: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811f9566)
Location: kernel/smp.c:1008
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/time/hrtimer.c:clock_was_set
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
**Symbols:**

```
ffffffff811f9430-ffffffff811f9455: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8120e3e6)
Location: kernel/smp.c:856
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/time/hrtimer.c:clock_was_set
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
**Symbols:**

```
ffffffff8120e2b0-ffffffff8120e2d5: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81225b76)
Location: kernel/smp.c:876
Inline: True
Inline callers:
  - kernel/smp.c:kick_all_cpus_sync
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/time/hrtimer.c:clock_was_set
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
**Symbols:**

```
ffffffff81225a40-ffffffff81225a65: smp_call_function_many (STB_GLOBAL)
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
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffff8000101bd220)
Location: kernel/smp.c:412
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_make_vcpus_request_mask
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_disable
```
**Symbols:**

```
ffff8000101bd220-ffff8000101bd5ac: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c0405380)
Location: kernel/smp.c:412
Inline: False
Direct callers:
  - arch/arm/kernel/smp_tlb.c:broadcast_tlb_mm_a15_erratum
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_disable
```
**Symbols:**

```
c0405380-c040575c: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c000000000223520)
Location: kernel/smp.c:412
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/pgtable.c:pmdp_invalidate
  - arch/powerpc/mm/book3s64/radix_tlb.c:exit_flush_lazy_tlbs
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
```
**Symbols:**

```
c000000000223520-c0000000002239b8: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffe000140848)
Location: kernel/smp.c:412
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
```
**Symbols:**

```
ffffffe000140848-ffffffe000140b52: smp_call_function_many (STB_GLOBAL)
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
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81147320)
Location: kernel/smp.c:412
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
  - arch/x86/lib/msr-smp.c:__rwmsr_on_cpus
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
**Symbols:**

```
ffffffff81147320-ffffffff81147587: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8113a600)
Location: kernel/smp.c:412
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
  - arch/x86/lib/msr-smp.c:__rwmsr_on_cpus
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
**Symbols:**

```
ffffffff8113a600-ffffffff8113a862: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811451d0)
Location: kernel/smp.c:412
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
  - arch/x86/lib/msr-smp.c:__rwmsr_on_cpus
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
**Symbols:**

```
ffffffff811451d0-ffffffff81145437: smp_call_function_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void smp_call_function_many(const struct cpumask *mask, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81151db0)
Location: kernel/smp.c:412
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:reset_with_ipi
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:smp_call_function
  - arch/x86/lib/msr-smp.c:__rwmsr_on_cpus
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
**Symbols:**

```
ffffffff81151db0-ffffffff81152017: smp_call_function_many (STB_GLOBAL)
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
