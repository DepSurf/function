# Function: <code>do_trace_write_msr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void do_trace_write_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81463bc0)
Location: arch/x86/lib/msr.c:116
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_write_msr_safe
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
  - arch/x86/kernel/paravirt.c:native_write_msr_safe
```
**Symbols:**

```
ffffffff81463bc0-ffffffff81463c27: do_trace_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void do_trace_write_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81482e60)
Location: arch/x86/lib/msr.c:116
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_write_msr_safe
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
  - arch/x86/kernel/paravirt.c:native_write_msr_safe
```
**Symbols:**

```
ffffffff81482e60-ffffffff81482ec7: do_trace_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void do_trace_write_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8148c5c0)
Location: arch/x86/lib/msr.c:116
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
  - arch/x86/kernel/paravirt.c:native_write_msr_safe
```
**Symbols:**

```
ffffffff8148c5c0-ffffffff8148c627: do_trace_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void do_trace_write_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff814c86b0)
Location: arch/x86/lib/msr.c:117
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
  - arch/x86/kernel/paravirt.c:native_write_msr_safe
```
**Symbols:**

```
ffffffff814c86b0-ffffffff814c8720: do_trace_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void do_trace_write_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff814f9650)
Location: arch/x86/lib/msr.c:117
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
  - arch/x86/kernel/paravirt.c:native_write_msr_safe
```
**Symbols:**

```
ffffffff814f9650-ffffffff814f96c0: do_trace_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void do_trace_write_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8150def0)
Location: arch/x86/lib/msr.c:117
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/paravirt.c:native_write_msr_safe
```
**Symbols:**

```
ffffffff8150def0-ffffffff8150df60: do_trace_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void do_trace_write_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8153c560)
Location: arch/x86/lib/msr.c:117
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/paravirt.c:native_write_msr_safe
```
**Symbols:**

```
ffffffff8153c560-ffffffff8153c5c9: do_trace_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void do_trace_write_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8155d370)
Location: arch/x86/lib/msr.c:117
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/paravirt.c:native_write_msr_safe
```
**Symbols:**

```
ffffffff8155d370-ffffffff8155d3d9: do_trace_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void do_trace_write_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff815e7130)
Location: arch/x86/lib/msr.c:117
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/paravirt.c:native_write_msr_safe
```
**Symbols:**

```
ffffffff815e7130-ffffffff815e7199: do_trace_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void do_trace_write_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8160c310)
Location: arch/x86/lib/msr.c:117
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/paravirt.c:native_write_msr_safe
```
**Symbols:**

```
ffffffff8160c310-ffffffff8160c355: do_trace_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void do_trace_write_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff815ef680)
Location: arch/x86/lib/msr.c:117
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
  - arch/x86/kernel/kvmclock.c:kvmclock_disable
  - arch/x86/kernel/paravirt.c:native_write_msr_safe
```
**Symbols:**

```
ffffffff815ef680-ffffffff815ef6c5: do_trace_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void do_trace_write_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8165c790)
Location: arch/x86/lib/msr.c:117
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
  - arch/x86/kernel/kvmclock.c:kvmclock_disable
  - arch/x86/kernel/paravirt.c:native_write_msr_safe
```
**Symbols:**

```
ffffffff8165c790-ffffffff8165c7d2: do_trace_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void do_trace_write_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81775640)
Location: arch/x86/lib/msr.c:117
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
  - arch/x86/kernel/kvmclock.c:kvmclock_disable
  - arch/x86/kernel/paravirt.c:native_write_msr_safe
```
**Symbols:**

```
ffffffff81775640-ffffffff817756d0: do_trace_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_trace_write_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff818a6280)
Location: arch/x86/lib/msr.c:117
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/enlighten_pv.c:xen_do_write_msr
  - arch/x86/xen/enlighten_pv.c:xen_do_write_msr
  - arch/x86/kernel/kvmclock.c:kvmclock_disable
  - arch/x86/kernel/paravirt.c:native_write_msr_safe
```
**Symbols:**

```
ffffffff818a6280-ffffffff818a6310: do_trace_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_trace_write_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff818e90b0)
Location: arch/x86/lib/msr.c:123
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/enlighten_pv.c:xen_do_write_msr
  - arch/x86/xen/enlighten_pv.c:xen_do_write_msr
  - arch/x86/kernel/kvmclock.c:kvmclock_disable
  - arch/x86/kernel/paravirt.c:native_write_msr_safe
```
**Symbols:**

```
ffffffff818e90b0-ffffffff818e9140: do_trace_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_trace_write_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81930550)
Location: arch/x86/lib/msr.c:123
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/enlighten_pv.c:xen_do_write_msr
  - arch/x86/xen/enlighten_pv.c:xen_do_write_msr
  - arch/x86/kernel/kvmclock.c:kvmclock_disable
  - arch/x86/kernel/paravirt.c:native_write_msr_safe
```
**Symbols:**

```
ffffffff81930550-ffffffff819305e0: do_trace_write_msr (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void do_trace_write_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81555960)
Location: arch/x86/lib/msr.c:117
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/paravirt.c:native_write_msr_safe
```
**Symbols:**

```
ffffffff81555960-ffffffff815559c9: do_trace_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void do_trace_write_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff815462d4)
Location: arch/x86/lib/msr.c:117
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:__intel_pmu_disable_all
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_stop
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event
  - arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event
  - arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event
  - arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event
  - arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event
  - arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_write
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:load_percpu_segment
  - arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap
  - arch/x86/kernel/cpu/bugs.c:update_stibp_msr
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/centaur.c:native_write_msr
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/kprobes/core.c:resume_execution
  - arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot
  - drivers/clocksource/hyperv_timer.c:hv_ce_shutdown
  - drivers/clocksource/hyperv_timer.c:hv_ce_shutdown
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event
  - drivers/hv/vmbus_drv.c:vmbus_isr
  - drivers/hv/vmbus_drv.c:vmbus_on_msg_dpc
  - drivers/hv/hv.c:hv_synic_disable_regs
  - drivers/hv/hv.c:hv_synic_disable_regs
  - drivers/hv/hv.c:hv_synic_disable_regs
  - drivers/hv/hv.c:hv_synic_disable_regs
  - drivers/hv/hv.c:hv_synic_enable_regs
  - drivers/hv/hv.c:hv_synic_enable_regs
  - drivers/hv/hv.c:hv_synic_enable_regs
  - drivers/hv/hv.c:hv_synic_enable_regs
  - drivers/hv/channel_mgmt.c:vmbus_initiate_unload
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff81545f60-ffffffff81545fc9: do_trace_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void do_trace_write_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff815516a0)
Location: arch/x86/lib/msr.c:117
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/paravirt.c:native_write_msr_safe
```
**Symbols:**

```
ffffffff815516a0-ffffffff81551709: do_trace_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void do_trace_write_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8156b730)
Location: arch/x86/lib/msr.c:117
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:pmu_msr_write
  - arch/x86/xen/enlighten_pv.c:xen_write_msr_safe
  - arch/x86/kernel/kvmclock.c:kvm_shutdown
  - arch/x86/kernel/kvmclock.c:kvm_crash_shutdown
  - arch/x86/kernel/paravirt.c:native_write_msr_safe
```
**Symbols:**

```
ffffffff8156b730-ffffffff8156b7b0: do_trace_write_msr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
