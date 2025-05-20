# Function: <code>__static_call_update</code>

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
void __static_call_update(struct static_call_key *key, void *tramp, void *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call.c (ffffffff81239820)
Location: kernel/static_call.c:123
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - kernel/tracepoint.c:tracepoint_remove_func
  - kernel/tracepoint.c:tracepoint_add_func
```
**Symbols:**

```
ffffffff81239820-ffffffff81239a20: __static_call_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __static_call_update(struct static_call_key *key, void *tramp, void *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call.c (ffffffff8123e010)
Location: kernel/static_call.c:123
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/xen/time.c:xen_init_time_common
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/paravirt.c:paravirt_set_sched_clock
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/tracepoint.c:tracepoint_add_func
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - drivers/xen/time.c:xen_time_setup_guest
```
**Symbols:**

```
ffffffff8123e010-ffffffff8123e210: __static_call_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __static_call_update(struct static_call_key *key, void *tramp, void *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/static_call.c (0)
Location: kernel/static_call.c:123
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/xen/time.c:xen_init_time_common
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/paravirt.c:paravirt_set_sched_clock
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/tracepoint.c:tracepoint_add_func
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - drivers/xen/time.c:xen_time_setup_guest
```
**Symbols:**

```
ffffffff81cb987a-ffffffff81cb98a9: __static_call_update.cold (STB_LOCAL)
ffffffff81278ad0-ffffffff81278ce6: __static_call_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __static_call_update(struct static_call_key *key, void *tramp, void *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/static_call_inline.c (0)
Location: kernel/static_call_inline.c:123
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/brs.c:amd_brs_lopwr_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/xen/time.c:xen_init_time_common
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/paravirt.c:paravirt_set_sched_clock
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/events/core.c:perf_unregister_guest_info_callbacks
  - kernel/events/core.c:perf_unregister_guest_info_callbacks
  - kernel/events/core.c:perf_unregister_guest_info_callbacks
  - kernel/events/core.c:perf_register_guest_info_callbacks
  - kernel/events/core.c:perf_register_guest_info_callbacks
  - kernel/events/core.c:perf_register_guest_info_callbacks
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/cpufreq/amd-pstate.c:amd_pstate_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_init
```
**Symbols:**

```
ffffffff81e6ae53-ffffffff81e6ae82: __static_call_update.cold (STB_LOCAL)
ffffffff812cb920-ffffffff812cbb60: __static_call_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __static_call_update(struct static_call_key *key, void *tramp, void *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/static_call_inline.c (0)
Location: kernel/static_call_inline.c:134
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/brs.c:amd_brs_lopwr_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/paravirt.c:paravirt_set_sched_clock
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/sched/core.c:sched_dynamic_update
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/events/core.c:perf_unregister_guest_info_callbacks
  - kernel/events/core.c:perf_unregister_guest_info_callbacks
  - kernel/events/core.c:perf_unregister_guest_info_callbacks
  - kernel/events/core.c:perf_register_guest_info_callbacks
  - kernel/events/core.c:perf_register_guest_info_callbacks
  - kernel/events/core.c:perf_register_guest_info_callbacks
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/cpufreq/amd-pstate.c:amd_pstate_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_init
```
**Symbols:**

```
ffffffff82061dc5-ffffffff82061de0: __static_call_update.cold (STB_LOCAL)
ffffffff813332b0-ffffffff813334e6: __static_call_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __static_call_update(struct static_call_key *key, void *tramp, void *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/static_call_inline.c (0)
Location: kernel/static_call_inline.c:134
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/brs.c:amd_brs_lopwr_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/kernel/process.c:idle_setup
  - arch/x86/kernel/process.c:select_idle_routine
  - arch/x86/kernel/process.c:select_idle_routine
  - arch/x86/kernel/process.c:select_idle_routine
  - arch/x86/kernel/process.c:select_idle_routine
  - arch/x86/kernel/process.c:xen_set_default_idle
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/paravirt.c:paravirt_set_sched_clock
  - kernel/sched/core.c:sched_dynamic_klp_enable
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/events/core.c:perf_unregister_guest_info_callbacks
  - kernel/events/core.c:perf_unregister_guest_info_callbacks
  - kernel/events/core.c:perf_unregister_guest_info_callbacks
  - kernel/events/core.c:perf_register_guest_info_callbacks
  - kernel/events/core.c:perf_register_guest_info_callbacks
  - kernel/events/core.c:perf_register_guest_info_callbacks
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/cpufreq/amd-pstate.c:amd_pstate_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_init
```
**Symbols:**

```
ffffffff820e1541-ffffffff820e155c: __static_call_update.cold (STB_LOCAL)
ffffffff81363f80-ffffffff813641b1: __static_call_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __static_call_update(struct static_call_key *key, void *tramp, void *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/static_call_inline.c (0)
Location: kernel/static_call_inline.c:134
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/core.c:x86_pmu_static_call_update
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/core.c:amd_core_pmu_init
  - arch/x86/events/amd/brs.c:amd_brs_lopwr_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/kernel/process.c:idle_setup
  - arch/x86/kernel/process.c:select_idle_routine
  - arch/x86/kernel/process.c:select_idle_routine
  - arch/x86/kernel/process.c:select_idle_routine
  - arch/x86/kernel/process.c:select_idle_routine
  - arch/x86/kernel/process.c:xen_set_default_idle
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/acpi/boot.c:acpi_parse_mp_wake
  - arch/x86/kernel/apic/init.c:update_static_calls
  - arch/x86/kernel/apic/init.c:update_static_calls
  - arch/x86/kernel/apic/init.c:update_static_calls
  - arch/x86/kernel/apic/init.c:update_static_calls
  - arch/x86/kernel/apic/init.c:update_static_calls
  - arch/x86/kernel/apic/init.c:update_static_calls
  - arch/x86/kernel/apic/init.c:update_static_calls
  - arch/x86/kernel/apic/init.c:update_static_calls
  - arch/x86/kernel/apic/init.c:update_static_calls
  - arch/x86/kernel/apic/init.c:update_static_calls
  - arch/x86/kernel/apic/init.c:update_static_calls
  - arch/x86/kernel/apic/init.c:update_static_calls
  - arch/x86/kernel/apic/init.c:update_static_calls
  - arch/x86/kernel/apic/init.c:update_static_calls
  - arch/x86/kernel/apic/init.c:update_static_calls
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/paravirt.c:paravirt_set_sched_clock
  - arch/x86/kernel/sev.c:snp_set_wakeup_secondary_cpu
  - kernel/sched/core.c:sched_dynamic_klp_enable
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/sched/core.c:__sched_dynamic_update
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/events/core.c:perf_unregister_guest_info_callbacks
  - kernel/events/core.c:perf_unregister_guest_info_callbacks
  - kernel/events/core.c:perf_unregister_guest_info_callbacks
  - kernel/events/core.c:perf_register_guest_info_callbacks
  - kernel/events/core.c:perf_register_guest_info_callbacks
  - kernel/events/core.c:perf_register_guest_info_callbacks
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - security/keys/trusted-keys/trusted_core.c:init_trusted
  - drivers/xen/time.c:xen_time_setup_guest
  - drivers/cpufreq/amd-pstate.c:amd_pstate_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_init
```
**Symbols:**

```
ffffffff821bdf50-ffffffff821bdf6b: __static_call_update.cold (STB_LOCAL)
ffffffff8138ce50-ffffffff8138d081: __static_call_update (STB_GLOBAL)
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
