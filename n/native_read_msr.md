# Function: <code>native_read_msr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d51f)
Location: arch/x86/include/asm/msr.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e33e)
Location: arch/x86/include/asm/msr.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_ucode_in_initrd
  - arch/x86/kernel/cpu/microcode/amd.c:apply_ucode_in_initrd
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr(unsigned int msr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104dd35)
Location: arch/x86/include/asm/msr.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e484)
Location: arch/x86/include/asm/msr.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:check_current_patch_level
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064750)
Location: arch/x86/include/asm/msr.h:83
Inline: False
```
**Symbols:**

```
ffffffff81064750-ffffffff81064784: native_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr(unsigned int msr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81041a33)
Location: arch/x86/include/asm/msr.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105032a)
Location: arch/x86/include/asm/msr.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810510b6)
Location: arch/x86/include/asm/msr.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:check_current_patch_level
  - arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd
```
```
In arch/x86/kernel/paravirt.c (ffffffff81067c30)
Location: arch/x86/include/asm/msr.h:83
Inline: False
```
**Symbols:**

```
ffffffff81067c30-ffffffff81067c64: native_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long long unsigned int native_read_msr(unsigned int msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81066f10)
Location: arch/x86/include/asm/msr.h:110
Inline: False
```
**Symbols:**

```
ffffffff81066f10-ffffffff81066f3d: native_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long long unsigned int native_read_msr(unsigned int msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106b040)
Location: arch/x86/include/asm/msr.h:111
Inline: False
```
**Symbols:**

```
ffffffff8106b040-ffffffff8106b06e: native_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long long unsigned int native_read_msr(unsigned int msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106dcd0)
Location: arch/x86/include/asm/msr.h:125
Inline: False
```
**Symbols:**

```
ffffffff8106dcd0-ffffffff8106dcfe: native_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long long unsigned int native_read_msr(unsigned int msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81073d40)
Location: arch/x86/include/asm/msr.h:125
Inline: False
```
**Symbols:**

```
ffffffff81073d40-ffffffff81073d6e: native_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long long unsigned int native_read_msr(unsigned int msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810778c0)
Location: arch/x86/include/asm/msr.h:125
Inline: False
```
**Symbols:**

```
ffffffff810778c0-ffffffff810778f1: native_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long long unsigned int native_read_msr(unsigned int msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81078930)
Location: arch/x86/include/asm/msr.h:125
Inline: False
```
**Symbols:**

```
ffffffff81078930-ffffffff81078961: native_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long long unsigned int native_read_msr(unsigned int msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107fd40)
Location: arch/x86/include/asm/msr.h:125
Inline: False
```
**Symbols:**

```
ffffffff8107fd40-ffffffff8107fd75: native_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long long unsigned int native_read_msr(unsigned int msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107f960)
Location: arch/x86/include/asm/msr.h:123
Inline: False
```
**Symbols:**

```
ffffffff8107f960-ffffffff8107f995: native_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long long unsigned int native_read_msr(unsigned int msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810809e0)
Location: arch/x86/include/asm/msr.h:123
Inline: False
```
**Symbols:**

```
ffffffff810809e0-ffffffff81080a15: native_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long long unsigned int native_read_msr(unsigned int msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8108f930)
Location: arch/x86/include/asm/msr.h:123
Inline: False
```
**Symbols:**

```
ffffffff8108f930-ffffffff8108f962: native_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long long unsigned int native_read_msr(unsigned int msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810a06b0)
Location: arch/x86/include/asm/msr.h:114
Inline: False
```
**Symbols:**

```
ffffffff810a06b0-ffffffff810a06f9: native_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr(unsigned int msr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81034a9f)
Location: arch/x86/include/asm/msr.h:114
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103707f)
Location: arch/x86/include/asm/msr.h:114
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_do_read_msr
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b8310)
Location: arch/x86/include/asm/msr.h:114
Inline: False
```
**Symbols:**

```
ffffffff810b8310-ffffffff810b8359: native_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr(unsigned int msr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81034a1f)
Location: arch/x86/include/asm/msr.h:114
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81036fcf)
Location: arch/x86/include/asm/msr.h:114
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_do_read_msr
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bb4a0)
Location: arch/x86/include/asm/msr.h:114
Inline: False
```
**Symbols:**

```
ffffffff810bb4a0-ffffffff810bb4e9: native_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long long unsigned int native_read_msr(unsigned int msr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8103ac1f)
Location: arch/x86/include/asm/msr.h:114
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_msr_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103d24f)
Location: arch/x86/include/asm/msr.h:114
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_do_read_msr
```
```
In arch/x86/hyperv/ivm.c (ffffffff8104f3e3)
Location: arch/x86/include/asm/msr.h:114
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_snp_boot_ap
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c28b0)
Location: arch/x86/include/asm/msr.h:114
Inline: False
```
**Symbols:**

```
ffffffff810c28b0-ffffffff810c28f9: native_read_msr (STB_LOCAL)
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
long long unsigned int native_read_msr(unsigned int msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077930)
Location: arch/x86/include/asm/msr.h:125
Inline: False
```
**Symbols:**

```
ffffffff81077930-ffffffff81077961: native_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long long unsigned int native_read_msr(unsigned int msr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005980)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_disable_all
Direct callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
```
```
In arch/x86/events/amd/core.c (ffffffff8100775b)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
```
```
In arch/x86/events/amd/ibs.c (ffffffff8288c27f)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:clear_APIC_ibs
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/msr.c (ffffffff8100a29a)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_start
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100c27b)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff8101063e)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81011159)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff81012289)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
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
```
```
In arch/x86/events/intel/p4.c (ffffffff81012b6c)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
Direct callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/intel/p6.c (ffffffff810138f5)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff81014de5)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016f22)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810191c0)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81019df6)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101bc20)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8101d1e5)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8101f175)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_read
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff8101f3f9)
Location: arch/x86/include/asm/msr.h:125
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff8288f927)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff8101f440)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/tsc.c (ffffffff82893aab)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff8102c3ed)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
```
```
In arch/x86/kernel/process.c (ffffffff8102cfe3)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
Direct callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
```
```
In arch/x86/kernel/step.c (ffffffff81032f15)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81035edf)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff828957d1)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81037d55)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff82895fcb)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8103949b)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff81039885)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff81039b78)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8103a172)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8103b13b)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8103b610)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
Direct callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8103b92a)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
Direct callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103e539)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103ff86)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81041094)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81042899)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff82896d0f)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810454c5)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff81045faa)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81046f9c)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81048cd8)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8289933f)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104dd2b)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81051bb5)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055379)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81056235)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105c9e3)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105cfa0)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d810)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read
```
```
In arch/x86/kernel/crash.c (ffffffff810605c5)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81061d0f)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81065f27)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8106be6f)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
```
```
In arch/x86/mm/pat.c (ffffffff810742ee)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
```
```
In kernel/kexec_core.c (ffffffff8114605a)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
  - kernel/kexec_core.c:crash_save_cpu
```
```
In arch/x86/lib/msr-smp.c (ffffffff81545590)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff815b1c24)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff815f2369)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81835945)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81837b45)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/msr.h:125
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff828f1c81)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
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
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff828f656a)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
```
```
In drivers/hv/vmbus_drv.c (ffffffff828f6e6c)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - drivers/hv/vmbus_drv.c:hv_acpi_init
```
```
In drivers/hv/hv.c (ffffffff8184fb55)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - drivers/hv/hv.c:hv_synic_disable_regs
  - drivers/hv/hv.c:hv_synic_disable_regs
  - drivers/hv/hv.c:hv_synic_disable_regs
  - drivers/hv/hv.c:hv_synic_disable_regs
  - drivers/hv/hv.c:hv_synic_enable_regs
  - drivers/hv/hv.c:hv_synic_enable_regs
  - drivers/hv/hv.c:hv_synic_enable_regs
  - drivers/hv/hv.c:hv_synic_enable_regs
```
```
In arch/x86/pci/amd_bus.c (ffffffff818633f5)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
Direct callers:
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
```
In arch/x86/power/cpu.c (ffffffff8186359e)
Location: arch/x86/include/asm/msr.h:125
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a1d934)
Location: arch/x86/include/asm/msr.h:125
Inline: True
```
**Symbols:**

```
ffffffff810041b0-ffffffff810041e1: native_read_msr (STB_LOCAL)
ffffffff8100aec0-ffffffff8100aef1: native_read_msr (STB_LOCAL)
ffffffff81012a80-ffffffff81012ab1: native_read_msr (STB_LOCAL)
ffffffff8101573b-ffffffff81015767: native_read_msr (STB_LOCAL)
ffffffff8101d030-ffffffff8101d061: native_read_msr (STB_LOCAL)
ffffffff8101f440-ffffffff8101f471: native_read_msr (STB_LOCAL)
ffffffff8102c880-ffffffff8102c8b1: native_read_msr (STB_LOCAL)
ffffffff81035500-ffffffff81035531: native_read_msr (STB_LOCAL)
ffffffff8103b4d0-ffffffff8103b501: native_read_msr (STB_LOCAL)
ffffffff8103b7e0-ffffffff8103b811: native_read_msr (STB_LOCAL)
ffffffff81045280-ffffffff810452b1: native_read_msr (STB_LOCAL)
ffffffff81045faa-ffffffff81045fde: native_read_msr.constprop.0 (STB_LOCAL)
ffffffff81051b30-ffffffff81051b61: native_read_msr (STB_LOCAL)
ffffffff81055a10-ffffffff81055a41: native_read_msr (STB_LOCAL)
ffffffff815b1a90-ffffffff815b1ac1: native_read_msr (STB_LOCAL)
ffffffff818633b0-ffffffff818633e1: native_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long long unsigned int native_read_msr(unsigned int msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810778e0)
Location: arch/x86/include/asm/msr.h:125
Inline: False
```
**Symbols:**

```
ffffffff810778e0-ffffffff81077911: native_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long long unsigned int native_read_msr(unsigned int msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81079980)
Location: arch/x86/include/asm/msr.h:125
Inline: False
```
**Symbols:**

```
ffffffff81079980-ffffffff810799b1: native_read_msr (STB_LOCAL)
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
