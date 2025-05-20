# Function: <code>do_trace_read_msr</code>

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
void do_trace_read_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81463c30)
Location: arch/x86/lib/msr.c:123
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_read_msr_safe
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:check_current_patch_level
  - arch/x86/kernel/paravirt.c:native_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr
```
**Symbols:**

```
ffffffff81463c30-ffffffff81463c97: do_trace_read_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81482ed0)
Location: arch/x86/lib/msr.c:123
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_read_msr_safe
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/amd.c:check_current_patch_level
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
  - arch/x86/kernel/paravirt.c:native_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr
```
**Symbols:**

```
ffffffff81482ed0-ffffffff81482f37: do_trace_read_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8148c630)
Location: arch/x86/lib/msr.c:123
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr
```
**Symbols:**

```
ffffffff8148c630-ffffffff8148c697: do_trace_read_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff814c8720)
Location: arch/x86/lib/msr.c:124
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr
```
**Symbols:**

```
ffffffff814c8720-ffffffff814c8790: do_trace_read_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff814f96c0)
Location: arch/x86/lib/msr.c:124
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr
```
**Symbols:**

```
ffffffff814f96c0-ffffffff814f9730: do_trace_read_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8150df60)
Location: arch/x86/lib/msr.c:124
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr
```
**Symbols:**

```
ffffffff8150df60-ffffffff8150dfd0: do_trace_read_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8153c5d0)
Location: arch/x86/lib/msr.c:124
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr
```
**Symbols:**

```
ffffffff8153c5d0-ffffffff8153c639: do_trace_read_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8155d3e0)
Location: arch/x86/lib/msr.c:124
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr
```
**Symbols:**

```
ffffffff8155d3e0-ffffffff8155d449: do_trace_read_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff815e70c0)
Location: arch/x86/lib/msr.c:124
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr
```
**Symbols:**

```
ffffffff815e70c0-ffffffff815e7129: do_trace_read_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8160c2c0)
Location: arch/x86/lib/msr.c:124
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr
```
**Symbols:**

```
ffffffff8160c2c0-ffffffff8160c305: do_trace_read_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff815ef630)
Location: arch/x86/lib/msr.c:124
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr
```
**Symbols:**

```
ffffffff815ef630-ffffffff815ef675: do_trace_read_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8165c740)
Location: arch/x86/lib/msr.c:124
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr
```
**Symbols:**

```
ffffffff8165c740-ffffffff8165c782: do_trace_read_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81775910)
Location: arch/x86/lib/msr.c:124
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr
```
**Symbols:**

```
ffffffff81775910-ffffffff817759a0: do_trace_read_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff818a65d0)
Location: arch/x86/lib/msr.c:124
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/enlighten_pv.c:xen_do_read_msr
  - arch/x86/xen/enlighten_pv.c:xen_do_read_msr
  - arch/x86/kernel/paravirt.c:native_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr
```
**Symbols:**

```
ffffffff818a65d0-ffffffff818a6660: do_trace_read_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff818e9440)
Location: arch/x86/lib/msr.c:130
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/enlighten_pv.c:xen_do_read_msr
  - arch/x86/xen/enlighten_pv.c:xen_do_read_msr
  - arch/x86/kernel/paravirt.c:native_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr
```
**Symbols:**

```
ffffffff818e9440-ffffffff818e94d0: do_trace_read_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff819308e0)
Location: arch/x86/lib/msr.c:130
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/enlighten_pv.c:xen_do_read_msr
  - arch/x86/xen/enlighten_pv.c:xen_do_read_msr
  - arch/x86/hyperv/ivm.c:hv_snp_boot_ap
  - arch/x86/kernel/paravirt.c:native_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr
```
**Symbols:**

```
ffffffff819308e0-ffffffff81930970: do_trace_read_msr (STB_GLOBAL)
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
void do_trace_read_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff815559d0)
Location: arch/x86/lib/msr.c:124
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr
```
**Symbols:**

```
ffffffff815559d0-ffffffff81555a39: do_trace_read_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff815462cd)
Location: arch/x86/lib/msr.c:124
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
Direct callers:
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:native_read_msr_safe
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:clear_APIC_ibs
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/msr.c:msr_event_start
  - arch/x86/events/msr.c:msr_event_update
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:native_read_msr_safe
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_read
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/step.c:set_task_blockstep
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/vector.c:print_local_APIC
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/kprobes/core.c:resume_execution
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
  - kernel/kexec_core.c:crash_save_cpu
  - kernel/kexec_core.c:crash_save_cpu
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/edac/mce_amd.c:amd_decode_mce
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical
  - drivers/cpufreq/intel_pstate.c:core_get_min_pstate
  - drivers/cpufreq/intel_pstate.c:atom_get_vid
  - drivers/cpufreq/intel_pstate.c:atom_get_vid
  - drivers/cpufreq/intel_pstate.c:airmont_get_scaling
  - drivers/cpufreq/intel_pstate.c:silvermont_get_scaling
  - drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate
  - drivers/cpufreq/intel_pstate.c:atom_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:atom_get_min_pstate
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:show_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show
  - drivers/hv/vmbus_drv.c:hv_acpi_init
  - drivers/hv/hv.c:hv_synic_disable_regs
  - drivers/hv/hv.c:hv_synic_disable_regs
  - drivers/hv/hv.c:hv_synic_disable_regs
  - drivers/hv/hv.c:hv_synic_disable_regs
  - drivers/hv/hv.c:hv_synic_enable_regs
  - drivers/hv/hv.c:hv_synic_enable_regs
  - drivers/hv/hv.c:hv_synic_enable_regs
  - drivers/hv/hv.c:hv_synic_enable_regs
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
```
**Symbols:**

```
ffffffff81545ef0-ffffffff81545f59: do_trace_read_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81551710)
Location: arch/x86/lib/msr.c:124
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr
```
**Symbols:**

```
ffffffff81551710-ffffffff81551779: do_trace_read_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8156b7b0)
Location: arch/x86/lib/msr.c:124
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:xen_read_pmc
  - arch/x86/xen/pmu.c:pmu_msr_read
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr_safe
  - arch/x86/kernel/paravirt.c:native_read_msr
```
**Symbols:**

```
ffffffff8156b7b0-ffffffff8156b830: do_trace_read_msr (STB_GLOBAL)
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
