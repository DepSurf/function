# Function: <code>paravirt_write_msr</code>

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
In arch/x86/entry/vdso/vma.c (ffffffff81003edd)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/events/core.c (ffffffff81006564)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_event
```
```
In arch/x86/events/amd/core.c (ffffffff81007948)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:x86_pmu_disable_event
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008339)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_start
```
```
In arch/x86/events/amd/ibs.c (ffffffff81008f9e)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100a778)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:__intel_pmu_enable_all
  - arch/x86/events/intel/core.c:__intel_pmu_disable_all
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100d536)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:__rmid_read
  - arch/x86/events/intel/cqm.c:update_sample
  - arch/x86/events/intel/cqm.c:intel_cqm_event_start
  - arch/x86/events/intel/cqm.c:intel_cqm_event_stop
```
```
In arch/x86/events/intel/ds.c (ffffffff8101075e)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
```
```
In arch/x86/events/intel/knc.c (ffffffff81010e70)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/lbr.c (ffffffff810112c0)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_disable
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
```
```
In arch/x86/events/intel/p4.c (ffffffff81012311)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/intel/p6.c (ffffffff810130b0)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
```
```
In arch/x86/events/intel/pt.c (ffffffff810132e7)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81017116)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
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
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81018b96)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81019489)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event
  - arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event
  - arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event
  - arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event
  - arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event
  - arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
```
```
In arch/x86/xen/enlighten.c (ffffffff81f60e86)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff8102d5e8)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:do_arch_prctl
  - arch/x86/kernel/process_64.c:do_arch_prctl
```
```
In arch/x86/kernel/process.c (ffffffff81039396)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103dc90)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104041a)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:load_percpu_segment
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81041ffc)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81042f75)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81043499)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81043606)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_error_reporting
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_generic
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_generic
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_generic
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104703e)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81047bf7)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049543)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104bfed)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d22e)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8104fc22)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81052c4a)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059561)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810599f1)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/crash.c (ffffffff8105d732)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8105f0d4)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/kvm.c (ffffffff81063b46)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff81068643)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/pat.c (ffffffff8106fd87)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff8141b34b)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff8141bab9)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_set_bit
  - arch/x86/lib/msr.c:msr_clear_bit
```
```
In drivers/idle/intel_idle.c (ffffffff81479174)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:auto_demotion_disable
  - drivers/idle/intel_idle.c:c1e_promotion_disable
```
```
In drivers/acpi/processor_throttling.c (ffffffff814ad919)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff816b6355)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff816b72a8)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
```
```
In arch/x86/pci/amd_bus.c (ffffffff816fadff)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:enable_pci_io_ecs
```
```
In arch/x86/power/cpu.c (ffffffff816fb083)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003e6f)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/events/core.c (ffffffff810070b4)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81007b98)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:x86_pmu_disable_event
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008869)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_start
```
```
In arch/x86/events/amd/ibs.c (ffffffff810099bf)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff8107e0eb)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:__intel_pmu_disable_all
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100d9cb)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_start
  - arch/x86/events/intel/cqm.c:update_sample
  - arch/x86/events/intel/cqm.c:__rmid_read
```
```
In arch/x86/events/intel/ds.c (ffffffff810107a7)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81010a40)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff810114c1)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_disable
```
```
In arch/x86/events/intel/p4.c (ffffffff810121b1)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff81012a89)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff810132f7)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_stop
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81016c98)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
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
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81017f96)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a994)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/process_64.c (ffffffff8102c6e1)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff8103839f)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103dab0)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81041093)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:load_percpu_segment
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81041fd0)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81043292)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81043436)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81043746)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_error_reporting
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81047b82)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81047e9b)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049c29)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d258)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81052e3e)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810597d1)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059d42)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_dest
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write
```
```
In arch/x86/kernel/crash.c (ffffffff8105d80e)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8105f4e6)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/kvm.c (ffffffff81063c0c)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff81068339)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/pat.c (ffffffff8106fb9b)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff8146350b)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff814c7609)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:c1e_promotion_disable
  - drivers/idle/intel_idle.c:auto_demotion_disable
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81717686)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81718f2d)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8171c303)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
```
In arch/x86/pci/amd_bus.c (ffffffff8175fc70)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:enable_pci_io_ecs
```
```
In arch/x86/power/cpu.c (ffffffff817602e3)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003e5f)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/events/core.c (ffffffff810070b4)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81007ba8)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:x86_pmu_disable_event
```
```
In arch/x86/events/amd/uncore.c (ffffffff810088a9)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_start
```
```
In arch/x86/events/amd/ibs.c (ffffffff810099ff)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff8108268b)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:__intel_pmu_disable_all
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100da8b)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_start
  - arch/x86/events/intel/cqm.c:update_sample
  - arch/x86/events/intel/cqm.c:__rmid_read
```
```
In arch/x86/events/intel/ds.c (ffffffff81010957)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81010bf0)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff81011693)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
```
In arch/x86/events/intel/p4.c (ffffffff810122e1)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff81012b79)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff81013477)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_stop
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81016ea8)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
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
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff810181a6)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101966d)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
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
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102bb56)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/process_64.c (ffffffff8102c599)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff81037e48)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103d398)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040ae0)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:load_percpu_segment
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104178f)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81042d82)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81042f26)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff8104332b)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:clear_closid
  - arch/x86/kernel/cpu/intel_rdt.c:rdt_cbm_update
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81043f59)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_update_closid
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81047fe6)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_error_reporting
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff810497a2)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81049b60)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104c029)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810502ff)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810559e9)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81055b2e)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c5d0)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105cb02)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_dest
```
```
In arch/x86/kernel/crash.c (ffffffff8106088b)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81062582)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/kvm.c (ffffffff810670c3)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8106bf89)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/pat.c (ffffffff810737cb)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff814827ab)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff814e9779)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81749506)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8174aced)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8174ecb5)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate
```
```
In arch/x86/pci/amd_bus.c (ffffffff8178c1b0)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff8178d2e3)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003cef)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/events/core.c (ffffffff81006dc5)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff810078f8)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:x86_pmu_disable_event
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008619)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_start
```
```
In arch/x86/events/amd/ibs.c (ffffffff810094d2)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff8100ca9c)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:__intel_pmu_disable_all
```
```
In arch/x86/events/intel/ds.c (ffffffff8100ef97)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff8100f23d)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff8100fcd4)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
```
In arch/x86/events/intel/p4.c (ffffffff810108cd)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff81011109)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff810119a1)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_stop
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81015428)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
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
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff810166a6)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81017abd)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
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
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81029d96)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/process_64.c (ffffffff8102a7be)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff81035fd6)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_cpuid_faulting
```
```
In arch/x86/kernel/step.c (ffffffff8103b3d1)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103ea71)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:load_percpu_segment
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8103ff21)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81040e72)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81040ff9)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81041083)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:cat_wrmsr
  - arch/x86/kernel/cpu/intel_rdt.c:mba_wrmsr
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81041af2)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:__intel_rdt_sched_in
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff810440d6)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81047893)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_error_reporting
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81049142)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81049562)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104b6a7)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104fb67)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810552de)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105563e)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105bd00)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c242)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_dest
```
```
In arch/x86/kernel/crash.c (ffffffff8105f8b8)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8106152c)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/kvm.c (ffffffff81066393)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8106b395)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/pat.c (ffffffff81072d7b)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff8148bedb)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff814f5399)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81767b86)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8176931d)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8176ba07)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate
```
```
In arch/x86/pci/amd_bus.c (ffffffff817ab150)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff817ab460)
Location: arch/x86/include/asm/paravirt.h:118
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003f3f)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/events/core.c (ffffffff810071e8)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81007d78)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:x86_pmu_disable_event
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008f19)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_start
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009c02)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff8100c3da)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:__intel_pmu_disable_all
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f73c)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff8100f9dd)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff81010472)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
```
In arch/x86/events/intel/p4.c (ffffffff81010ede)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff81011a39)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff810120e6)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_stop
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81016cae)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
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
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81016f26)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81019a9d)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
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
```
```
In arch/x86/xen/suspend.c (ffffffff8101c24c)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_vcpu_notify_restore
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102a0c6)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/process_64.c (ffffffff8102b51a)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff81038855)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:enable_cpuid
```
```
In arch/x86/kernel/step.c (ffffffff8103de08)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81041750)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:load_percpu_segment
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81043283)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810442d2)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81044457)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff810448d3)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:cat_wrmsr
  - arch/x86/kernel/cpu/intel_rdt.c:mba_wrmsr
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81044f4a)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:__intel_rdt_sched_in
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff810478a6)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104b359)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_error_reporting
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104cb82)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104cfb1)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104f0bd)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053fbf)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810590ae)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810597d1)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81060085)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810606d0)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/crash.c (ffffffff810638fc)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8106522c)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/kvm.c (ffffffff8106a593)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8106fc95)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/pat.c (ffffffff810786fb)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff814c7fcb)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff81535c19)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817dda66)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817df0c6)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff817e29bd)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate
```
```
In arch/x86/pci/amd_bus.c (ffffffff81822640)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff81822960)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff8100476c)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/events/core.c (ffffffff8100795b)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81008508)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:x86_pmu_disable_event
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009529)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_start
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a0db)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff8100cb17)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:__intel_pmu_disable_all
```
```
In arch/x86/events/intel/ds.c (ffffffff810100bc)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81010350)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff81010eb5)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
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
```
```
In arch/x86/events/intel/p4.c (ffffffff8101192e)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff81012409)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff81012876)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_stop
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81017817)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
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
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81017a85)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a1fd)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
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
```
```
In arch/x86/xen/suspend.c (ffffffff8101cc5c)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_vcpu_notify_restore
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102ab85)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102bb35)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_write
```
```
In arch/x86/kernel/process_64.c (ffffffff8102c53a)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff81039d1c)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculative_store_bypass_update
  - arch/x86/kernel/process.c:speculative_store_bypass_update
  - arch/x86/kernel/process.c:speculative_store_bypass_update
  - arch/x86/kernel/process.c:speculative_store_bypass_update
  - arch/x86/kernel/process.c:speculative_store_bypass_update
  - arch/x86/kernel/process.c:enable_cpuid
```
```
In arch/x86/kernel/step.c (ffffffff8103f3a8)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81043049)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:load_percpu_segment
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81043a00)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104505e)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81046462)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104670e)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81046b76)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:cat_wrmsr
  - arch/x86/kernel/cpu/intel_rdt.c:mba_wrmsr
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810473a5)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:l2_qos_cfg_update
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:l3_qos_cfg_update
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:__intel_rdt_sched_in
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff8104a6f4)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104dc9f)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_error_reporting
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104f822)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81050d30)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81051dc1)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056c1f)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8105c034)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105ca81)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106307a)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106379d)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/crash.c (ffffffff81066569)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81067df5)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/kvm.c (ffffffff8106d1f8)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff81072b12)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/pat.c (ffffffff8107b35b)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff814f8f3b)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff8271d060)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818266f5)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81827cc6)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8182bbbd)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
```
```
In arch/x86/pci/amd_bus.c (ffffffff8186c935)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff8186cb99)
Location: arch/x86/include/asm/paravirt.h:114
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100783b)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff810083e8)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:x86_pmu_disable_event
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009439)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_start
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a00b)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff8100cc0a)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
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
  - arch/x86/events/intel/core.c:__intel_pmu_disable_all
```
```
In arch/x86/events/intel/ds.c (ffffffff8101069c)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81010930)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff81011515)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
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
```
```
In arch/x86/events/intel/p4.c (ffffffff81011fae)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff81012a89)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff81012f76)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_stop
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81017f8f)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
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
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81018275)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101abed)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
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
```
```
In arch/x86/xen/suspend.c (ffffffff8101c4ec)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_vcpu_notify_restore
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102b475)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102cb05)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_write
```
```
In arch/x86/kernel/process_64.c (ffffffff8102dd60)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff8103b26c)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/step.c (ffffffff810409a8)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810445ab)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:load_percpu_segment
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810452e0)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap
  - arch/x86/kernel/cpu/bugs.c:update_stibp_msr
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81046a72)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81047ee2)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104898e)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104b38f)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104cee2)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8104d496)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8104f441)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810542af)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81055b76)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810563b5)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105aa74)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105ca1c)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81061caa)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81062711)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068e5a)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106949d)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/crash.c (ffffffff8106c5c8)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8106dcb5)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/kvm.c (ffffffff810733c8)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81073874)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff81078b62)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/pat.c (ffffffff81081c9b)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff8150d7db)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff828d5073)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818525e5)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81853bc6)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81857bad)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
```
```
In arch/x86/pci/amd_bus.c (ffffffff8188c945)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff8188cba9)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007b27)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81008c61)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100992f)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_start
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a4fc)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff8100d44a)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
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
  - arch/x86/events/intel/core.c:__intel_pmu_disable_all
```
```
In arch/x86/events/intel/ds.c (ffffffff81011827)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81011af1)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff81012973)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
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
```
```
In arch/x86/events/intel/p4.c (ffffffff81013321)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff81013e29)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff81014323)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_stop
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019575)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
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
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81019855)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c75d)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
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
```
```
In arch/x86/xen/suspend.c (ffffffff8101e04c)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_vcpu_notify_restore
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102d1e5)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102e887)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_write
```
```
In arch/x86/kernel/process_64.c (ffffffff8102fadf)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff8103d840)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/step.c (ffffffff8104305e)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046b62)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:load_percpu_segment
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047dd0)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap
  - arch/x86/kernel/cpu/bugs.c:update_stibp_msr
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff81048375)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline
  - arch/x86/kernel/cpu/umwait.c:umwait_update_control_msr
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810495ca)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff81049b42)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104ac56)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104b74e)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104ba54)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e28a)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fe12)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810503e5)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052564)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810574d2)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058de6)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ac95)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105dd6e)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fd8c)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810652b5)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81065da1)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c688)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106cced)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/crash.c (ffffffff810705c8)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81071cde)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/kvm.c (ffffffff81076f58)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810773ee)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8107c6d2)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/pat.c (ffffffff8108593a)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff8153be8b)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff815b3a6f)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81895b75)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81897186)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8189af65)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff8290fbc4)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot
  - drivers/clocksource/hyperv_timer.c:hv_ce_shutdown
  - drivers/clocksource/hyperv_timer.c:hv_ce_shutdown
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event
```
```
In arch/x86/pci/amd_bus.c (ffffffff818d7285)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff818d768b)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007d09)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
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
```
```
In arch/x86/events/amd/core.c (ffffffff81008f83)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009d1f)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_start
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100aabc)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff8100d97a)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
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
```
```
In arch/x86/events/intel/ds.c (ffffffff81012027)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff810122b1)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff81013123)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
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
```
```
In arch/x86/events/intel/p4.c (ffffffff81013ad1)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff810145d9)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff810148d3)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_stop
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019ef5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
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
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a1d5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101d0dd)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
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
```
```
In arch/x86/xen/suspend.c (ffffffff8101e9cc)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_vcpu_notify_restore
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102daf5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f197)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_write
```
```
In arch/x86/kernel/process_64.c (ffffffff8103043f)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff8103e000)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/step.c (ffffffff810437be)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810472e2)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:load_percpu_segment
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048620)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap
  - arch/x86/kernel/cpu/bugs.c:update_stibp_msr
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff81048c45)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline
  - arch/x86/kernel/cpu/umwait.c:umwait_update_control_msr
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049eb9)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff8104a2c9)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104a4d2)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b656)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104c10e)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c414)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ec2a)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810507a2)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81050d55)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052e54)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057da0)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810596b6)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059dd5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e62e)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106063c)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065925)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810663d1)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106d5dd)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106de50)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e44d)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/crash.c (ffffffff810715c8)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81072d0e)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/kvm.c (ffffffff810773a5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8107847e)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8107d7c2)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/pat.c (ffffffff8108662a)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff8155cc9b)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff815d4caf)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818c7b85)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818c9196)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818cd115)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff829198e3)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot
  - drivers/clocksource/hyperv_timer.c:hv_ce_shutdown
  - drivers/clocksource/hyperv_timer.c:hv_ce_shutdown
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event
```
```
In arch/x86/pci/amd_bus.c (ffffffff81909605)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff819096f9)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void paravirt_write_msr(unsigned int msr, unsigned int low, unsigned int high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008d64)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
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
```
```
In arch/x86/events/amd/core.c (ffffffff8100a673)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100aeef)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_start
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100bd32)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff8100ea6d)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_tfa_commit_scheduling
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
  - arch/x86/events/intel/core.c:intel_pmu_disable_all
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81013497)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81013721)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff810149e3)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset
```
```
In arch/x86/events/intel/p4.c (ffffffff810150f3)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff81015c89)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff810166f0)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101b855)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
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
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101bf45)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ee4d)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
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
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8101f7ae)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
```
In arch/x86/xen/suspend.c (ffffffff81020eec)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_vcpu_notify_restore
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102fc75)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_suspend
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81031ce7)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_write
```
```
In arch/x86/kernel/process_64.c (ffffffff81032c73)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__resctrl_sched_in
```
```
In arch/x86/kernel/process.c (ffffffff810410d0)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
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
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:enable_cpuid
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043822)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate
```
```
In arch/x86/kernel/step.c (ffffffff810471d8)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104b37b)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:load_percpu_segment
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104c290)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap
  - arch/x86/kernel/cpu/bugs.c:update_stibp_msr
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff8104cf51)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff8104d6d8)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104e608)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:switch_to_sld
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
  - arch/x86/kernel/cpu/intel.c:init_intel_misc_features
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff8104e8d9)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104ea72)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104fe87)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff810507b0)
Location: arch/x86/include/asm/paravirt.h:170
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81050a60)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052e6d)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_clear_state
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81054e42)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81056122)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81057f30)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105cf69)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105e82c)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810603f5)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81063853)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106634c)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82cd8c26)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106bf58)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
Direct callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106cd54)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8107470d)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075300)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8107592d)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/crash.c (ffffffff810786ca)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8107a252)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/kvm.c (ffffffff8107edd5)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8107f7ae)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff81083fe8)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/pat/memtype.c (ffffffff8108fdaa)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff815e66bb)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff8167e9a1)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_init
  - drivers/idle/intel_idle.c:intel_idle_cpu_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199a715)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199c4b3)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:170
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a0bdd)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff819c325d)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_tsc_clocksource
```
```
In arch/x86/pci/amd_bus.c (ffffffff81bb9f08)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff81bba2ab)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
**Symbols:**

```
ffffffff8100cd70-ffffffff8100cd83: paravirt_write_msr (STB_LOCAL)
ffffffff8102f9e0-ffffffff8102f9f3: paravirt_write_msr (STB_LOCAL)
ffffffff8104b880-ffffffff8104b893: paravirt_write_msr (STB_LOCAL)
ffffffff810507b0-ffffffff810507c3: paravirt_write_msr (STB_LOCAL)
ffffffff81050a60-ffffffff81050a76: paravirt_write_msr.constprop.0 (STB_LOCAL)
ffffffff8106bc10-ffffffff8106bc26: paravirt_write_msr.constprop.0 (STB_LOCAL)
ffffffff8107e6a0-ffffffff8107e6b3: paravirt_write_msr (STB_LOCAL)
ffffffff8107f5b0-ffffffff8107f5c3: paravirt_write_msr (STB_LOCAL)
ffffffff8167e880-ffffffff8167e893: paravirt_write_msr (STB_LOCAL)
ffffffff819c2df0-ffffffff819c2e03: paravirt_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void paravirt_write_msr(unsigned int msr, unsigned int low, unsigned int high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007e14)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
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
```
```
In arch/x86/events/amd/core.c (ffffffff810094f3)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009e7f)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_start
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100aced)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff8100d71d)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:icl_update_topdown_event
  - arch/x86/events/intel/core.c:icl_update_topdown_event
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_fixed
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_tfa_commit_scheduling
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
  - arch/x86/events/intel/core.c:intel_pmu_disable_all
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81013047)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff810132d1)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff81013f84)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_32
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_disable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_disable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
```
```
In arch/x86/events/intel/p4.c (ffffffff81015593)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff81016129)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff81016b90)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101bd55)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
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
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101c435)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101f5ad)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
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
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8102024e)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
```
In arch/x86/xen/suspend.c (ffffffff8102175c)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_vcpu_notify_restore
```
```
In arch/x86/hyperv/hv_init.c (ffffffff810308a5)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_suspend
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810329c7)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_write
```
```
In arch/x86/kernel/process_64.c (ffffffff8103397a)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__resctrl_sched_in
```
```
In arch/x86/kernel/traps.c (ffffffff81c35e63)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/process.c (ffffffff81041030)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104414c)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:update_pasid
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/step.c (ffffffff81046a28)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104aa4d)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:load_percpu_segment
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b7b0)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap
  - arch/x86/kernel/cpu/bugs.c:update_stibp_msr
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff8104c3b1)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff8104cb93)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104db48)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:switch_to_sld
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
  - arch/x86/kernel/cpu/intel.c:init_intel_misc_features
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff8104dbe9)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104dd82)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104f0f7)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104f900)
Location: arch/x86/include/asm/paravirt.h:168
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104fbc0)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051fbd)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81053dd2)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81055022)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81056cb0)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105b7c9)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105cd4c)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e585)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81061c70)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810645f8)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8106709b)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82fc5044)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106d838)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
Direct callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106e4f4)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8107518d)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075963)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075f6d)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/crash.c (ffffffff810786cf)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81079ac6)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/kvm.c (ffffffff8107ea05)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8107f40e)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff81bd8765)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/pat/memtype.c (ffffffff8108faaa)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff8160b80b)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff8169d6a1)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_init
  - drivers/idle/intel_idle.c:intel_idle_cpu_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199d875)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199f543)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:168
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a3ad5)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_hwp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff8301a9c0)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event
```
```
In arch/x86/pci/amd_bus.c (ffffffff81bce778)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff81bceb1b)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
```
**Symbols:**

```
ffffffff8100bcc0-ffffffff8100bcd3: paravirt_write_msr (STB_LOCAL)
ffffffff81030610-ffffffff81030623: paravirt_write_msr (STB_LOCAL)
ffffffff810434c0-ffffffff810434d3: paravirt_write_msr.constprop.0 (STB_LOCAL)
ffffffff8104adc0-ffffffff8104add3: paravirt_write_msr (STB_LOCAL)
ffffffff8104f900-ffffffff8104f913: paravirt_write_msr (STB_LOCAL)
ffffffff8104fbc0-ffffffff8104fbd6: paravirt_write_msr.constprop.0 (STB_LOCAL)
ffffffff8106d4f0-ffffffff8106d506: paravirt_write_msr.constprop.0 (STB_LOCAL)
ffffffff8107e250-ffffffff8107e263: paravirt_write_msr (STB_LOCAL)
ffffffff8107f210-ffffffff8107f223: paravirt_write_msr (STB_LOCAL)
ffffffff8169d580-ffffffff8169d593: paravirt_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void paravirt_write_msr(unsigned int msr, unsigned int low, unsigned int high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008cbc)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:perf_clear_dirty_counters
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
```
```
In arch/x86/events/amd/core.c (ffffffff81009ec1)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100aa0f)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_start
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100b680)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff8100e9eb)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_tfa_commit_scheduling
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_disable_all
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81014257)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff810144f5)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff81015dc2)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_32
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
```
```
In arch/x86/events/intel/p4.c (ffffffff81016822)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff81017419)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff81017e6d)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_start
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101d105)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
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
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101d825)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81020add)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
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
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81021955)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_init_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810225ce)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
```
In arch/x86/xen/suspend.c (ffffffff81023adc)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_vcpu_notify_restore
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81031318)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_suspend
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81033e27)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_write
```
```
In arch/x86/kernel/process_64.c (ffffffff810354a8)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
```
```
In arch/x86/kernel/traps.c (ffffffff81c282f7)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/process.c (ffffffff81042a20)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81045109)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/step.c (ffffffff810482a8)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104c2f2)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:load_percpu_segment
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104d460)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap
  - arch/x86/kernel/cpu/bugs.c:update_stibp_msr
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff8104def1)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff8104e6a7)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff831cb710)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_setup
  - arch/x86/kernel/cpu/intel.c:switch_to_sld
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff8104f879)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104fa12)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81050cf7)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff810514b0)
Location: arch/x86/include/asm/paravirt.h:185
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81051770)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105399f)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810556a2)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810565b2)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105c179)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d6ac)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ef75)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062440)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81064b98)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810693dc)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff831cf944)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106e2b1)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
Direct callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106efe4)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075c2d)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81076403)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810769fd)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/crash.c (ffffffff81079586)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f885)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8108052e)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff81bca609)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810905aa)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff815eeaeb)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff81680442)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81947664)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81982415)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8198491d)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:185
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81988714)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff832259f1)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event
```
```
In arch/x86/pci/amd_bus.c (ffffffff81bc2128)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff81bc24cb)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
```
**Symbols:**

```
ffffffff8100c650-ffffffff8100c663: paravirt_write_msr (STB_LOCAL)
ffffffff81031100-ffffffff81031113: paravirt_write_msr (STB_LOCAL)
ffffffff81044dc0-ffffffff81044dd6: paravirt_write_msr.constprop.0 (STB_LOCAL)
ffffffff8104c6a0-ffffffff8104c6b3: paravirt_write_msr (STB_LOCAL)
ffffffff810514b0-ffffffff810514c3: paravirt_write_msr (STB_LOCAL)
ffffffff81051770-ffffffff81051786: paravirt_write_msr.constprop.0 (STB_LOCAL)
ffffffff8106df60-ffffffff8106df76: paravirt_write_msr.constprop.0 (STB_LOCAL)
ffffffff8107f370-ffffffff8107f383: paravirt_write_msr (STB_LOCAL)
ffffffff81080370-ffffffff81080383: paravirt_write_msr (STB_LOCAL)
ffffffff81680300-ffffffff81680313: paravirt_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void paravirt_write_msr(unsigned int msr, unsigned int low, unsigned int high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81009b38)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:perf_clear_dirty_counters
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
```
```
In arch/x86/events/amd/core.c (ffffffff8100afd1)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100bb75)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff8100f452)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_tfa_commit_scheduling
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_disable_all
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff810155b7)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81015875)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff81017432)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_32
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
```
```
In arch/x86/events/intel/p4.c (ffffffff810182f1)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff810191c9)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff8101abf7)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_start
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81020205)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
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
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81020925)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81024626)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_enable_event
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
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff810256b5)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_init_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8102642e)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
```
In arch/x86/xen/suspend.c (ffffffff81027d7c)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_vcpu_notify_restore
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81036a18)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_suspend
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81038b17)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_write
```
```
In arch/x86/kernel/process_64.c (ffffffff8103a788)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
```
```
In arch/x86/kernel/traps.c (ffffffff81d46467)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/process.c (ffffffff81048d90)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104b631)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/step.c (ffffffff8104ebb8)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81053486)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
  - arch/x86/kernel/cpu/common.c:load_percpu_segment
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81054bc0)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap
  - arch/x86/kernel/cpu/bugs.c:update_stibp_msr
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff810556f1)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff81056097)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff832acfb8)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_setup
  - arch/x86/kernel/cpu/intel.c:switch_to_sld
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff81057a59)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff81057c72)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81059117)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81059a40)
Location: arch/x86/include/asm/paravirt.h:185
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81059d00)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105c29e)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105e042)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105f1c2)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81065913)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81066dbd)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810688a6)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106c2a2)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106ec48)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81073a8c)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff832b1db4)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81079b7a)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
Direct callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8107a98c)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810831ad)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81083a53)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810841cd)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/crash.c (ffffffff810875e6)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e665)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8108f45e)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff81c9fa68)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/tlb.c (ffffffff8109b335)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/pat/memtype.c (ffffffff8109ffba)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff8165bbdf)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff816f51e5)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff819ec513)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81a2b8a5)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81a2e01a)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:185
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81a327b1)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff8330fbcb)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event
```
```
In arch/x86/pci/amd_bus.c (ffffffff81c92738)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff81c92b59)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
```
**Symbols:**

```
ffffffff8100cb80-ffffffff8100cb93: paravirt_write_msr (STB_LOCAL)
ffffffff810363a0-ffffffff810363b3: paravirt_write_msr (STB_LOCAL)
ffffffff8104b190-ffffffff8104b1a6: paravirt_write_msr.constprop.0 (STB_LOCAL)
ffffffff81053990-ffffffff810539a3: paravirt_write_msr (STB_LOCAL)
ffffffff81059a40-ffffffff81059a53: paravirt_write_msr (STB_LOCAL)
ffffffff81059d00-ffffffff81059d16: paravirt_write_msr.constprop.0 (STB_LOCAL)
ffffffff81079780-ffffffff81079796: paravirt_write_msr.constprop.0 (STB_LOCAL)
ffffffff8108e0a0-ffffffff8108e0b3: paravirt_write_msr (STB_LOCAL)
ffffffff8108f200-ffffffff8108f213: paravirt_write_msr (STB_LOCAL)
ffffffff816f5070-ffffffff816f5083: paravirt_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void paravirt_write_msr(unsigned int msr, unsigned int low, unsigned int high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81009267)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:perf_clear_dirty_counters
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
```
```
In arch/x86/events/amd/core.c (ffffffff8100ab89)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
```
```
In arch/x86/events/amd/brs.c (ffffffff8100b468)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/amd/brs.c:perf_amd_brs_lopwr_cb
  - arch/x86/events/amd/brs.c:amd_pmu_brs_sched_task
  - arch/x86/events/amd/brs.c:amd_brs_disable
  - arch/x86/events/amd/brs.c:amd_brs_enable_all
  - arch/x86/events/amd/brs.c:amd_brs_reset
  - arch/x86/events/amd/brs.c:amd_brs_reset
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100c792)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff81010982)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
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
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack
  - arch/x86/events/intel/core.c:intel_pmu_disable_all
Direct callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff810175e1)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81017943)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff810197b6)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_32
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
```
```
In arch/x86/events/intel/p4.c (ffffffff8101a456)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff8101b408)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff8101d469)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_start
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81023185)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
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
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81023bc5)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81028656)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_enable_event
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
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81029615)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_init_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8102a526)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
```
In arch/x86/xen/suspend.c (ffffffff8102c250)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_vcpu_notify_restore
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8103ca88)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_suspend
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103f7c7)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_write
```
```
In arch/x86/kernel/process_64.c (ffffffff81041889)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
```
```
In arch/x86/kernel/traps.c (ffffffff81042a5d)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_xfd_event
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_general_protection
```
```
In arch/x86/kernel/process.c (ffffffff8105187b)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
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
  - arch/x86/kernel/process.c:enable_cpuid
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81053b07)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054aa3)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81055fc2)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/step.c (ffffffff81059ddf)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105ef0b)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
  - arch/x86/kernel/cpu/common.c:load_percpu_segment
  - arch/x86/kernel/cpu/common.c:cet_disable
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8105f3f6)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:write_spec_ctrl_current
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff810616d1)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff8106209c)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8345dd80)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_setup
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
  - arch/x86/kernel/cpu/intel.c:splitlock_cpu_offline
  - arch/x86/kernel/cpu/intel.c:__split_lock_reenable
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff81063eb5)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff81064121)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81065747)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81066150)
Location: arch/x86/include/asm/paravirt.h:191
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81066480)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81068771)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8106a781)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106ba03)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810723b1)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81073b10)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81075956)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8107962e)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107c3f7)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81082055)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff83463083)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810889a3)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
Direct callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81089a0d)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8109302d)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81093a33)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8109429d)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/crash.c (ffffffff81097751)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff8109f455)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_init_platform
  - arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810a00ed)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff81e4f2cb)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/tlb.c (ffffffff810ae7f1)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810b3eb1)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff81774a7f)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff81821b19)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_ibrs
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81b523cc)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81b52ad1)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81b95de5)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81b96e42)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81b984ee)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:191
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9ecf8)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff834c9a01)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event
```
```
In arch/x86/pci/amd_bus.c (ffffffff81e41ecf)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff81e424c9)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
```
**Symbols:**

```
ffffffff8100da20-ffffffff8100da4c: paravirt_write_msr (STB_LOCAL)
ffffffff8103c200-ffffffff8103c22c: paravirt_write_msr (STB_LOCAL)
ffffffff81055380-ffffffff810553ac: paravirt_write_msr (STB_LOCAL)
ffffffff81066150-ffffffff8106617c: paravirt_write_msr (STB_LOCAL)
ffffffff81066480-ffffffff810664af: paravirt_write_msr.constprop.0 (STB_LOCAL)
ffffffff81088500-ffffffff8108852f: paravirt_write_msr.constprop.0 (STB_LOCAL)
ffffffff8109e840-ffffffff8109e86c: paravirt_write_msr (STB_LOCAL)
ffffffff81821990-ffffffff818219bc: paravirt_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void paravirt_write_msr(unsigned int msr, unsigned int low, unsigned int high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100a6b6)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff8100ca99)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
```
```
In arch/x86/events/amd/lbr.c (ffffffff8100dc17)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_reset
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_reset
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_reset
```
```
In arch/x86/events/amd/brs.c (ffffffff8100dce8)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/amd/brs.c:perf_amd_brs_lopwr_cb
  - arch/x86/events/amd/brs.c:amd_pmu_brs_sched_task
  - arch/x86/events/amd/brs.c:amd_brs_disable
  - arch/x86/events/amd/brs.c:amd_brs_enable_all
  - arch/x86/events/amd/brs.c:amd_brs_reset
  - arch/x86/events/amd/brs.c:amd_brs_reset
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100f7d3)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff81014fb2)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
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
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack
  - arch/x86/events/intel/core.c:intel_pmu_disable_all
```
```
In arch/x86/events/intel/ds.c (ffffffff8101b7d1)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff8101bbe3)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101d791)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_32
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
```
```
In arch/x86/events/intel/p4.c (ffffffff8101e569)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_set_period
```
```
In arch/x86/events/intel/p6.c (ffffffff8101f638)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff81021879)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_start
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81027ea5)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
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
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81028a55)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:mtl_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102e7f6)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_enable_event
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
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81030045)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_init_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81031116)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
```
In arch/x86/xen/suspend.c (ffffffff810331c0)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_vcpu_notify_restore
```
```
In arch/x86/hyperv/hv_init.c (ffffffff810456c5)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_suspend
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048ff7)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_write
```
```
In arch/x86/kernel/process_64.c (ffffffff8104afe9)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
```
```
In arch/x86/kernel/traps.c (ffffffff8104c46d)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_xfd_event
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_general_protection
```
```
In arch/x86/kernel/process.c (ffffffff8105eefb)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
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
  - arch/x86/kernel/process.c:enable_cpuid
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8106157f)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810625f4)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106388e)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
```
```
In arch/x86/kernel/step.c (ffffffff8106799f)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106d66b)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
  - arch/x86/kernel/cpu/common.c:switch_gdt_and_percpu_base
  - arch/x86/kernel/cpu/common.c:cet_disable
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106f21c)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap
  - arch/x86/kernel/cpu/bugs.c:update_stibp_msr
  - arch/x86/kernel/cpu/bugs.c:update_spec_ctrl_cond
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff81070101)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff81070b1c)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81071e39)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
  - arch/x86/kernel/cpu/intel.c:splitlock_cpu_offline
  - arch/x86/kernel/cpu/intel.c:__split_lock_reenable
  - arch/x86/kernel/cpu/intel.c:__split_lock_reenable_unlock
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:sld_setup
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff81073025)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable
  - arch/x86/kernel/cpu/tsx.c:tsx_clear_cpuid
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff810732c1)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81074a57)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81075647)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81075a6e)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81077ea1)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107a5e1)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107bcca)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810821b5)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81083eb0)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81085a16)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108a495)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108d6fb)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81094a65)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff83e85a8b)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/reboot.c (ffffffff81097d91)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:cpu_emergency_svm_disable
  - arch/x86/kernel/reboot.c:cpu_emergency_svm_disable
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109c910)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109d91d)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810a838d)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a9163)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a9b1d)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/kvm.c (ffffffff810b6cb5)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_init_platform
  - arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810b7b3d)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff810c0afe)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/tlb.c (ffffffff810c8ada)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810ce9ce)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_cpu_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff818a552f)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff81952819)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_ibrs
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81cea58c)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81cead14)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d36955)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81d37b82)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81d3950e)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:191
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d402c8)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff83f0b0fb)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event
```
```
In arch/x86/pci/amd_bus.c (ffffffff8201c67f)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff8201cea9)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
```
**Symbols:**

```
ffffffff81044ca0-ffffffff81044ccc: paravirt_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void paravirt_write_msr(unsigned int msr, unsigned int low, unsigned int high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81009f06)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff8100c339)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
```
```
In arch/x86/events/amd/lbr.c (ffffffff8100d3e7)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_reset
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_reset
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_reset
```
```
In arch/x86/events/amd/brs.c (ffffffff8100d91d)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/events/amd/brs.c:amd_pmu_brs_sched_task
  - arch/x86/events/amd/brs.c:amd_brs_reset
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100edc0)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff81014812)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
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
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack
  - arch/x86/events/intel/core.c:intel_pmu_disable_all
```
```
In arch/x86/events/intel/ds.c (ffffffff8101b4a1)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff8101b8b4)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101d491)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_32
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
```
```
In arch/x86/events/intel/p4.c (ffffffff8101e261)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_set_period
```
```
In arch/x86/events/intel/p6.c (ffffffff8101f348)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff810215c9)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_start
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81027ec5)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
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
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81028a85)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:mtl_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102e8f6)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_enable_event
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
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81030135)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_init_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81031127)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
```
In arch/x86/xen/suspend.c (ffffffff81033160)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_vcpu_notify_restore
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81045805)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_suspend
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81049257)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_write
```
```
In arch/x86/kernel/process_64.c (ffffffff8104b883)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
```
```
In arch/x86/kernel/traps.c (ffffffff8104ccdd)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_xfd_event
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_general_protection
```
```
In arch/x86/kernel/process.c (ffffffff810605fb)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
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
  - arch/x86/kernel/process.c:enable_cpuid
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81062e4f)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810640c0)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106578f)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
```
```
In arch/x86/kernel/step.c (ffffffff8106924f)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106efcf)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
  - arch/x86/kernel/cpu/common.c:switch_gdt_and_percpu_base
  - arch/x86/kernel/cpu/common.c:cet_disable
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81070abc)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap
  - arch/x86/kernel/cpu/bugs.c:update_stibp_msr
  - arch/x86/kernel/cpu/bugs.c:update_gds_msr
  - arch/x86/kernel/cpu/bugs.c:update_spec_ctrl_cond
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff81071d11)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff8107270d)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81073a29)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
  - arch/x86/kernel/cpu/intel.c:splitlock_cpu_offline
  - arch/x86/kernel/cpu/intel.c:__split_lock_reenable
  - arch/x86/kernel/cpu/intel.c:__split_lock_reenable_unlock
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:sld_setup
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff81074c05)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable
  - arch/x86/kernel/cpu/tsx.c:tsx_clear_cpuid
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff81074ea1)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81076a4b)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:amd_set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff810777b7)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81077bdc)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107a151)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107c891)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107dfca)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8108464f)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81086450)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088c96)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_cpu_closid_rmid
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108d505)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810905ab)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81097a05)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff836a8f8b)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/reboot.c (ffffffff8109ae31)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:cpu_emergency_svm_disable
  - arch/x86/kernel/reboot.c:cpu_emergency_svm_disable
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109f85d)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a087c)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810ab5fd)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810ac323)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810acb6d)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/kvm.c (ffffffff810b9e55)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_init_platform
  - arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810bad2d)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff810c41de)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/tlb.c (ffffffff810cc14f)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810d1f8e)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_cpu_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff818e834f)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff81998c19)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81d53184)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81d53924)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d9fd05)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81da1a32)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81da3fae)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:193
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81daae38)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state
```
```
In arch/x86/pci/amd_bus.c (ffffffff8209cd1f)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff8209d539)
Location: arch/x86/include/asm/paravirt.h:193
Inline: True
```
**Symbols:**

```
ffffffff81044de0-ffffffff81044e0c: paravirt_write_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void paravirt_write_msr(unsigned int msr, unsigned int low, unsigned int high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100f626)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_pmu_enable_event
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_enable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81011a39)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
  - arch/x86/events/amd/core.c:amd_pmu_v2_enable_event
```
```
In arch/x86/events/amd/lbr.c (ffffffff81012c27)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_reset
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_reset
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_reset
```
```
In arch/x86/events/amd/brs.c (ffffffff8101315d)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/events/amd/brs.c:amd_pmu_brs_sched_task
  - arch/x86/events/amd/brs.c:amd_brs_reset
```
```
In arch/x86/events/amd/ibs.c (ffffffff81014500)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff8101a2c2)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
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
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack
  - arch/x86/events/intel/core.c:intel_pmu_disable_all
```
```
In arch/x86/events/intel/ds.c (ffffffff81021001)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff810213e0)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff81023461)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_32
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
```
```
In arch/x86/events/intel/p4.c (ffffffff81024326)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_set_period
```
```
In arch/x86/events/intel/p6.c (ffffffff81025408)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff81027f6a)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8102e025)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
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
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8102ebe5)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:mtl_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81034fc6)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_enable_event
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
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff810363d5)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_event
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_init_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8103741c)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
```
In arch/x86/xen/suspend.c (ffffffff81039510)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_vcpu_notify_restore
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8104bed5)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_suspend
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810506b7)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_write
```
```
In arch/x86/kernel/process_64.c (ffffffff81052b01)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
```
```
In arch/x86/kernel/traps.c (ffffffff81053f5d)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_xfd_event
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_general_protection
```
```
In arch/x86/kernel/process.c (ffffffff810681a0)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
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
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:enable_cpuid
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8106a13f)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b5d8)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106cbef)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
```
```
In arch/x86/kernel/step.c (ffffffff810706bf)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8107633e)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
  - arch/x86/kernel/cpu/common.c:switch_gdt_and_percpu_base
  - arch/x86/kernel/cpu/common.c:cet_disable
  - arch/x86/kernel/cpu/common.c:cet_disable
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810783dc)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap
  - arch/x86/kernel/cpu/bugs.c:update_stibp_msr
  - arch/x86/kernel/cpu/bugs.c:bhi_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:update_gds_msr
  - arch/x86/kernel/cpu/bugs.c:update_spec_ctrl_cond
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff81079531)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_online
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff8107a00d)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8107af69)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
  - arch/x86/kernel/cpu/intel.c:splitlock_cpu_offline
  - arch/x86/kernel/cpu/intel.c:__split_lock_reenable
  - arch/x86/kernel/cpu/intel.c:__split_lock_reenable_unlock
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:sld_setup
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff8107c0d5)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable
  - arch/x86/kernel/cpu/tsx.c:tsx_clear_cpuid
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8107c371)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107e08b)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:amd_set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8107ed37)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8107f0bc)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810819d1)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81083d81)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_claim_bank
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_handle_storm
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_handle_storm
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8108547a)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108d330)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81091af1)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_cpu_closid_rmid
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81094895)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8109793b)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109ef75)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff838d9495)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a6ced)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a7fbc)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810b246d)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810b2ee3)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b3b8d)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/kvm.c (ffffffff810c16e5)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_init_platform
  - arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_offline
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810c216d)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/shstk.c (ffffffff810cad8a)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/shstk.c:shstk_prctl
  - arch/x86/kernel/shstk.c:shstk_prctl
  - arch/x86/kernel/shstk.c:wrss_control
  - arch/x86/kernel/shstk.c:restore_signal_shadow_stack
  - arch/x86/kernel/shstk.c:setup_signal_shadow_stack
  - arch/x86/kernel/shstk.c:shstk_setup
  - arch/x86/kernel/shstk.c:shstk_setup
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff810cc61e)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/tlb.c (ffffffff810d47df)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810da6ee)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_cpu_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff8192f7ef)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff819e1369)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81e09e8c)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81e0a3e9)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_do_enable
  - drivers/thermal/intel/intel_hfi.c:hfi_do_enable
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
  - drivers/thermal/intel/intel_hfi.c:hfi_disable
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e57a14)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr_each
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81e597d2)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5c03e)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:195
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e62f58)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state
```
```
In arch/x86/pci/amd_bus.c (ffffffff8217451f)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff82174d39)
Location: arch/x86/include/asm/paravirt.h:195
Inline: True
```
**Symbols:**

```
ffffffff8104b310-ffffffff8104b33c: paravirt_write_msr (STB_LOCAL)
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007d09)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
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
```
```
In arch/x86/events/amd/core.c (ffffffff81008f83)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009d1f)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_start
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100aabc)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff8100d97a)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
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
```
```
In arch/x86/events/intel/ds.c (ffffffff81012027)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff810122b1)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff81013123)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
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
```
```
In arch/x86/events/intel/p4.c (ffffffff81013ad1)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff810145d9)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff810148d3)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_stop
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019ef5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
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
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a1d5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101d0dd)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
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
```
```
In arch/x86/xen/suspend.c (ffffffff8101eafc)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_vcpu_notify_restore
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102dc55)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f2f7)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_write
```
```
In arch/x86/kernel/process_64.c (ffffffff8103059f)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff8103e180)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/step.c (ffffffff8104393e)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047462)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:load_percpu_segment
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048790)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap
  - arch/x86/kernel/cpu/bugs.c:update_stibp_msr
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff81048db5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline
  - arch/x86/kernel/cpu/umwait.c:umwait_update_control_msr
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104a029)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff8104a439)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104a642)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b7c6)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104c27e)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c584)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ed8a)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810508a2)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81050e55)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052f54)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057920)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059236)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059955)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e1ae)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810601bc)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065415)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81065ec1)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cdf0)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d3ed)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/crash.c (ffffffff810705c8)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81071d0e)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/kvm.c (ffffffff810763a5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8107747e)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8107c7c2)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/pat.c (ffffffff8108562a)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff8155528b)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff815c89ff)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8186c2a5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8186d8b6)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81870d15)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff828fea4f)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot
  - drivers/clocksource/hyperv_timer.c:hv_ce_shutdown
  - drivers/clocksource/hyperv_timer.c:hv_ce_shutdown
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event
```
```
In arch/x86/pci/amd_bus.c (ffffffff818a89c5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff818a8ab9)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007cc9)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
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
```
```
In arch/x86/events/amd/core.c (ffffffff81008f43)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009cdf)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_start
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100aa7c)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff8100d93a)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
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
```
```
In arch/x86/events/intel/ds.c (ffffffff81011fe7)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81012271)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff810130e3)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
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
```
```
In arch/x86/events/intel/p4.c (ffffffff81013a91)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff81014599)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff81014893)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_stop
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019eb5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
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
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a195)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101d09d)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
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
```
```
In arch/x86/xen/suspend.c (ffffffff8101e98c)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_vcpu_notify_restore
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102dab5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f157)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_write
```
```
In arch/x86/kernel/process_64.c (ffffffff810303ff)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff8103dfc0)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/step.c (ffffffff8104377e)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810472a2)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:load_percpu_segment
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810485d0)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap
  - arch/x86/kernel/cpu/bugs.c:update_stibp_msr
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff81048bf5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline
  - arch/x86/kernel/cpu/umwait.c:umwait_update_control_msr
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049e69)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff8104a279)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104a482)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b606)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104c0be)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c3c4)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ebda)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81050752)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81050d05)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052e04)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057d50)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059666)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059d85)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e5de)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810605ec)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810658c5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066371)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106d2a0)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d89d)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/crash.c (ffffffff810705c8)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81071cbe)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/kvm.c (ffffffff81076355)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8107742e)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8107c772)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/pat.c (ffffffff810855da)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff81550fcb)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff815c8f8f)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818bd035)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818be646)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818c25c5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff82913c7e)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot
  - drivers/clocksource/hyperv_timer.c:hv_ce_shutdown
  - drivers/clocksource/hyperv_timer.c:hv_ce_shutdown
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event
```
```
In arch/x86/pci/amd_bus.c (ffffffff818fa025)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff818fa119)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007e29)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
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
```
```
In arch/x86/events/amd/core.c (ffffffff810090a3)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009e3f)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_start
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100aa0c)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_start
```
```
In arch/x86/events/intel/core.c (ffffffff8100db0a)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:core_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
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
```
```
In arch/x86/events/intel/ds.c (ffffffff81012207)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:perf_restore_debug_store
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81012491)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff81013303)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
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
```
```
In arch/x86/events/intel/p4.c (ffffffff81013cb1)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff810147d9)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff81014ad3)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_config_stop
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
  - arch/x86/events/intel/pt.c:pt_config
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101a0f5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event
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
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a3d5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101d2ed)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
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
```
```
In arch/x86/xen/suspend.c (ffffffff8101ebdc)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_vcpu_notify_restore
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102e8a5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102ff97)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_write
```
```
In arch/x86/kernel/process_64.c (ffffffff81031298)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff8103f137)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
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
```
```
In arch/x86/kernel/step.c (ffffffff81044b7e)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810486a2)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:load_percpu_segment
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810499e0)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap
  - arch/x86/kernel/cpu/bugs.c:update_stibp_msr
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff8104a005)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline
  - arch/x86/kernel/cpu/umwait.c:umwait_update_control_msr
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104b279)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff8104b689)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104b892)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104ca16)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:set_dr_addr_mask
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104d4ce)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104d7d4)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105001a)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81051b92)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81052145)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81054284)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810591f0)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105ab06)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b225)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105fb1e)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81061b4c)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81066ea5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81067951)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106ecad)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f520)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106fb1d)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write
```
```
In arch/x86/kernel/crash.c (ffffffff810725e2)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81073d3e)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/kvm.c (ffffffff810783a5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810794fe)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8107e872)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/pat.c (ffffffff8108772a)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff8156ae0b)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff815e2def)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818d9325)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818da956)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:write_new_vid
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818de8d5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff8291a945)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot
  - drivers/clocksource/hyperv_timer.c:hv_ce_shutdown
  - drivers/clocksource/hyperv_timer.c:hv_ce_shutdown
  - drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event
```
```
In arch/x86/pci/amd_bus.c (ffffffff8191b185)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff8191b279)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
