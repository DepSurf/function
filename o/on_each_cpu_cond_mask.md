# Function: <code>on_each_cpu_cond_mask</code>

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
void on_each_cpu_cond_mask(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811383a0)
Location: kernel/smp.c:670
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - kernel/smp.c:on_each_cpu_cond
```
**Symbols:**

```
ffffffff811383a0-ffffffff811384d4: on_each_cpu_cond_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81143560)
Location: kernel/smp.c:683
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - kernel/smp.c:on_each_cpu_cond
```
**Symbols:**

```
ffffffff81143560-ffffffff8114368b: on_each_cpu_cond_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8114f0a0)
Location: kernel/smp.c:683
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - kernel/smp.c:on_each_cpu_cond
```
**Symbols:**

```
ffffffff8114f0a0-ffffffff8114f1cb: on_each_cpu_cond_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(smp_cond_func_t cond_func, smp_call_func_t func, void *info, bool wait, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115f9b0)
Location: kernel/smp.c:761
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - kernel/smp.c:on_each_cpu_cond
```
**Symbols:**

```
ffffffff8115f9b0-ffffffff8115fa35: on_each_cpu_cond_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(smp_cond_func_t cond_func, smp_call_func_t func, void *info, bool wait, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115b950)
Location: kernel/smp.c:898
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - kernel/smp.c:on_each_cpu_cond
```
**Symbols:**

```
ffffffff8115b950-ffffffff8115b9d5: on_each_cpu_cond_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(smp_cond_func_t cond_func, smp_call_func_t func, void *info, bool wait, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115c9a0)
Location: kernel/smp.c:1124
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/hrtimer.c:clock_was_set_work
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - fs/buffer.c:invalidate_bh_lrus
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
  - drivers/char/agp/generic.c:global_cache_flush
```
**Symbols:**

```
ffffffff8115c9a0-ffffffff8115c9bf: on_each_cpu_cond_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(smp_cond_func_t cond_func, smp_call_func_t func, void *info, bool wait, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81181b50)
Location: kernel/smp.c:1126
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpa_flush_all
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/hrtimer.c:clock_was_set
  - fs/buffer.c:invalidate_bh_lrus
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
  - drivers/char/agp/generic.c:global_cache_flush
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81181b50-ffffffff81181b6f: on_each_cpu_cond_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(smp_cond_func_t cond_func, smp_call_func_t func, void *info, bool wait, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811b81f0)
Location: kernel/smp.c:1145
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpa_flush_all
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/hrtimer.c:clock_was_set
  - fs/buffer.c:invalidate_bh_lrus
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
  - drivers/char/agp/generic.c:global_cache_flush
```
**Symbols:**

```
ffffffff811b81f0-ffffffff811b8248: on_each_cpu_cond_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(smp_cond_func_t cond_func, smp_call_func_t func, void *info, bool wait, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811f94e0)
Location: kernel/smp.c:1146
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpa_flush_all
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
  - kernel/time/hrtimer.c:clock_was_set
  - fs/buffer.c:invalidate_bh_lrus
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
  - drivers/char/agp/generic.c:global_cache_flush
```
**Symbols:**

```
ffffffff811f94e0-ffffffff811f9538: on_each_cpu_cond_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(smp_cond_func_t cond_func, smp_call_func_t func, void *info, bool wait, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8120e360)
Location: kernel/smp.c:994
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/cpu/amd.c:amd_check_microcode
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
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
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpa_flush_all
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
  - kernel/time/hrtimer.c:clock_was_set
  - fs/buffer.c:invalidate_bh_lrus
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
  - drivers/char/agp/generic.c:global_cache_flush
```
**Symbols:**

```
ffffffff8120e360-ffffffff8120e3b8: on_each_cpu_cond_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(smp_cond_func_t cond_func, smp_call_func_t func, void *info, bool wait, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81225af0)
Location: kernel/smp.c:1014
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/cpu/amd.c:amd_check_microcode
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
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
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpa_flush_all
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_disable
  - fs/buffer.c:invalidate_bh_lrus
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
  - drivers/char/agp/generic.c:global_cache_flush
```
**Symbols:**

```
ffffffff81225af0-ffffffff81225b48: on_each_cpu_cond_mask (STB_GLOBAL)
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
void on_each_cpu_cond_mask(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffff8000101bd768)
Location: kernel/smp.c:683
Inline: False
Direct callers:
  - kernel/smp.c:on_each_cpu_cond
```
**Symbols:**

```
ffff8000101bd768-ffff8000101bd8a4: on_each_cpu_cond_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c0405a44)
Location: kernel/smp.c:683
Inline: False
Direct callers:
  - kernel/smp.c:on_each_cpu_cond
```
**Symbols:**

```
c0405a44-c0405b48: on_each_cpu_cond_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c000000000223bc0)
Location: kernel/smp.c:683
Inline: False
Direct callers:
  - kernel/smp.c:on_each_cpu_cond
```
**Symbols:**

```
c000000000223bc0-c000000000223d64: on_each_cpu_cond_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffe000140c9a)
Location: kernel/smp.c:683
Inline: False
Direct callers:
  - kernel/smp.c:on_each_cpu_cond
```
**Symbols:**

```
ffffffe000140c9a-ffffffe000140d5e: on_each_cpu_cond_mask (STB_GLOBAL)
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
void on_each_cpu_cond_mask(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811476c0)
Location: kernel/smp.c:683
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - kernel/smp.c:on_each_cpu_cond
```
**Symbols:**

```
ffffffff811476c0-ffffffff811477eb: on_each_cpu_cond_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8113a970)
Location: kernel/smp.c:683
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - kernel/smp.c:on_each_cpu_cond
```
**Symbols:**

```
ffffffff8113a970-ffffffff8113aa9b: on_each_cpu_cond_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81145570)
Location: kernel/smp.c:683
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - kernel/smp.c:on_each_cpu_cond
```
**Symbols:**

```
ffffffff81145570-ffffffff8114569b: on_each_cpu_cond_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81152170)
Location: kernel/smp.c:683
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - kernel/smp.c:on_each_cpu_cond
```
**Symbols:**

```
ffffffff81152170-ffffffff811522ad: on_each_cpu_cond_mask (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>cond_func, func, info, wait, gfp_flags, mask</code> ➡️ <code>cond_func, func, info, wait, mask</code>
</li>
<li>
<b>Param type changed. </b>
<code>bool (*cond_func)(int, void *)</code> ➡️ <code>smp_cond_func_t cond_func</code>
</li>
</ul>
</details>
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
