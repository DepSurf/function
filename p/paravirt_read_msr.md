# Function: <code>paravirt_read_msr</code>

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
In arch/x86/events/core.c (ffffffff8100651b)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_disable_all
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
In arch/x86/events/amd/ibs.c (ffffffff81009119)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/msr.c (ffffffff81f5dbfa)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_init
  - arch/x86/events/msr.c:msr_event_del
```
```
In arch/x86/events/intel/core.c (ffffffff8107c6b3)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100d55f)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:__rmid_read
  - arch/x86/events/intel/cqm.c:update_sample
```
```
In arch/x86/events/intel/cstate.c (ffffffff8100ee4a)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/events/intel/cstate.c:cstate_pmu_event_update
  - arch/x86/events/intel/cstate.c:cstate_probe_msr
```
```
In arch/x86/events/intel/ds.c (ffffffff8101072c)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81010e4a)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101129a)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_disable
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
```
```
In arch/x86/events/intel/p4.c (ffffffff810126e0)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/intel/p6.c (ffffffff8101308a)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff810133cc)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/events/intel/rapl.c (ffffffff8101491d)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/events/intel/rapl.c:rapl_event_update
  - arch/x86/events/intel/rapl.c:__rapl_pmu_event_start
  - arch/x86/events/intel/rapl.c:rapl_pmu_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff810167dd)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81017186)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81019479)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
```
```
In arch/x86/xen/enlighten.c (ffffffff81f60b72)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
```
```
In arch/x86/realmode/init.c (ffffffff81f65685)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:setup_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff8102d24d)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:do_arch_prctl
  - arch/x86/kernel/process_64.c:do_arch_prctl
```
```
In arch/x86/kernel/tsc.c (ffffffff81f69208)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff81038692)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:try_msr_calibrate_tsc
  - arch/x86/kernel/tsc_msr.c:try_msr_calibrate_tsc
  - arch/x86/kernel/tsc_msr.c:try_msr_calibrate_tsc
```
```
In arch/x86/kernel/process.c (ffffffff81038ec6)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:amd_e400_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103dc2c)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040134)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:__print_cpu_msr
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81041eb7)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81042642)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104348a)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044750)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_generic
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81047020)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81047b71)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049554)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff81f6b3a7)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104b9a6)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff81f6c4e6)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d127)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8104f266)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:read_hv_clock
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8104fb57)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8107cea7)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f72003)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81f72dd0)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810585af)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81058fdd)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810595d1)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059a61)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
```
```
In arch/x86/kernel/crash.c (ffffffff8105d743)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8105f0c0)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810633e2)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff81068325)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
```
```
In arch/x86/mm/pat.c (ffffffff8106fe09)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff8141b2ef)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff8141ba56)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_set_bit
  - arch/x86/lib/msr.c:msr_clear_bit
```
```
In drivers/idle/intel_idle.c (ffffffff8147913a)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:auto_demotion_disable
  - drivers/idle/intel_idle.c:c1e_promotion_disable
```
```
In drivers/acpi/processor_throttling.c (ffffffff814ae050)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/acpi/processor_perflib.c (ffffffff814aedab)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8153ddf1)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff816b6347)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff816b7181)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff816b9996)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:atom_get_min_pstate
  - drivers/cpufreq/intel_pstate.c:atom_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate
  - drivers/cpufreq/intel_pstate.c:atom_get_vid
  - drivers/cpufreq/intel_pstate.c:atom_get_vid
  - drivers/cpufreq/intel_pstate.c:core_get_min_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate
  - drivers/cpufreq/intel_pstate.c:airmont_get_scaling
  - drivers/cpufreq/intel_pstate.c:silvermont_get_scaling
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:show_no_turbo
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_timer_func
  - drivers/cpufreq/intel_pstate.c:intel_pstate_timer_func
  - drivers/cpufreq/intel_pstate.c:intel_hwp_timer_func
  - drivers/cpufreq/intel_pstate.c:intel_hwp_timer_func
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81fb8e0c)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
```
In arch/x86/pci/amd_bus.c (ffffffff816fadca)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:enable_pci_io_ecs
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
```
In arch/x86/power/cpu.c (ffffffff816faf88)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/events/core.c (ffffffff81007199)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/ibs.c (ffffffff81f8591c)
Location: arch/x86/include/asm/paravirt.h:122
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
In arch/x86/events/msr.c (ffffffff81009fd6)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81f861b9)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100d875)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:update_sample
  - arch/x86/events/intel/cqm.c:__rmid_read
```
```
In arch/x86/events/intel/ds.c (ffffffff810101c3)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81010a19)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff810115ce)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_disable
```
```
In arch/x86/events/intel/p4.c (ffffffff81f875f9)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff81012a7a)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff81012ced)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015a76)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810164db)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810188e6)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/realmode/init.c (ffffffff81f8d3d1)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff8102cce1)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl
  - arch/x86/kernel/process_64.c:do_arch_prctl
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff81037974)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
```
```
In arch/x86/kernel/process.c (ffffffff81037f23)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:amd_e400_idle
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103da69)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040b16)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810421f7)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81042542)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104342a)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810466c8)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81047b73)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81047ef4)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049b18)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff81f936cb)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104bb06)
Location: arch/x86/include/asm/paravirt.h:122
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
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff81f94d00)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d282)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81f95c36)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:read_hv_clock
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81f998c9)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105948e)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059841)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059ce1)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
```
```
In arch/x86/kernel/crash.c (ffffffff8105d81f)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8105f4d7)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8106303f)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff810682af)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
```
```
In arch/x86/mm/pat.c (ffffffff8106fb83)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff814634bc)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff814c75fa)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:c1e_promotion_disable
  - drivers/idle/intel_idle.c:auto_demotion_disable
```
```
In drivers/acpi/processor_perflib.c (ffffffff814fe868)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81717666)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81718ecc)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8171c191)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
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
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
```
```
In arch/x86/pci/amd_bus.c (ffffffff8175fc5a)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:enable_pci_io_ecs
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
```
In arch/x86/power/cpu.c (ffffffff817601ac)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/events/core.c (ffffffff81007199)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/ibs.c (ffffffff81fc0d56)
Location: arch/x86/include/asm/paravirt.h:113
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
In arch/x86/events/msr.c (ffffffff8100a016)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81fc161c)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100d935)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:update_sample
  - arch/x86/events/intel/cqm.c:__rmid_read
```
```
In arch/x86/events/intel/ds.c (ffffffff81010383)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81010bc9)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff810116fe)
Location: arch/x86/include/asm/paravirt.h:113
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
```
```
In arch/x86/events/intel/p4.c (ffffffff81fc2a71)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff81012b6a)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff81012ddd)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015c46)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810166eb)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81018ab6)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102bc36)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_is_hypercall_page_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:read_hv_clock_msr
  - arch/x86/hyperv/hv_init.c:read_hv_clock_tsc
```
```
In arch/x86/realmode/init.c (ffffffff81fc87e5)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff8102cbc9)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl
  - arch/x86/kernel/process_64.c:do_arch_prctl
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/tsc.c (ffffffff81fcc4e9)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff81037718)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
```
```
In arch/x86/kernel/process.c (ffffffff81fcc8e5)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103d359)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104055a)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81041c87)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81042032)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81042f1a)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81fce024)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81048268)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81049793)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81049bc4)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104bf18)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff81fcecd7)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104df56)
Location: arch/x86/include/asm/paravirt.h:113
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
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff81fd030c)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104f889)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81fd10e3)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055567)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81fd4d9f)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105c21e)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c5f1)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105caa1)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
```
```
In arch/x86/kernel/crash.c (ffffffff8106089c)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81062573)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8106652f)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8106beff)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
```
```
In arch/x86/mm/pat.c (ffffffff810737b3)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
```
```
In arch/x86/lib/msr-smp.c (ffffffff8148275c)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff814e9769)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
```
In drivers/acpi/processor_perflib.c (ffffffff8152155c)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817494e6)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8174ac8c)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8174ed6f)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
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
  - drivers/cpufreq/intel_pstate.c:show_no_turbo
```
```
In arch/x86/pci/amd_bus.c (ffffffff8178c19a)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
```
In arch/x86/power/cpu.c (ffffffff8178d1ac)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/events/core.c (ffffffff81006eaa)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/ibs.c (ffffffff820a103e)
Location: arch/x86/include/asm/paravirt.h:113
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
In arch/x86/events/msr.c (ffffffff8100a4c6)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff820a19ce)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e983)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff8100f212)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff8100fd5b)
Location: arch/x86/include/asm/paravirt.h:113
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
```
```
In arch/x86/events/intel/p4.c (ffffffff820a2cf0)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff810110fa)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff8101138d)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/events/intel/uncore.c (ffffffff810140f6)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81014c6b)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81016fa6)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81029e76)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_is_hypercall_page_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:read_hv_clock_msr
```
```
In arch/x86/realmode/init.c (ffffffff820a8ed5)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff8102adc9)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/tsc.c (ffffffff820acc6d)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff8103583d)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
```
```
In arch/x86/kernel/process.c (ffffffff820ad0bf)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103b3a9)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103e4ed)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8103eeca)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8103fd8c)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81040172)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81040fed)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff820ae79e)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff810440e9)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81047b49)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81049133)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104950b)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104b588)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff820af6fc)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104dec6)
Location: arch/x86/include/asm/paravirt.h:113
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
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff820b0d7b)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104f7c9)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105093f)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff820b1c2c)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81054e87)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff820b5a52)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105b91e)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105bd21)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c1e1)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read
```
```
In arch/x86/kernel/crash.c (ffffffff8105f8c9)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8106151d)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8106583f)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8106b30f)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
```
```
In arch/x86/mm/pat.c (ffffffff81072d63)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
```
```
In kernel/kexec_core.c (ffffffff8111e745)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
  - kernel/kexec_core.c:crash_save_cpu
```
```
In arch/x86/lib/msr-smp.c (ffffffff8148be8c)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff814f5389)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
```
In drivers/acpi/processor_perflib.c (ffffffff81532f15)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81767b66)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817692bc)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8176d32b)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_pid
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_pid
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
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
```
```
In arch/x86/pci/amd_bus.c (ffffffff817ab13a)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
```
In arch/x86/power/cpu.c (ffffffff817ab31c)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/events/core.c (ffffffff810072d1)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/ibs.c (ffffffff826a7133)
Location: arch/x86/include/asm/paravirt.h:109
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
In arch/x86/events/msr.c (ffffffff8100a9a6)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff826a7b0c)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f133)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff8100f9b2)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff810104eb)
Location: arch/x86/include/asm/paravirt.h:109
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
```
```
In arch/x86/events/intel/p4.c (ffffffff826a8fe4)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff81011a2a)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff81011acd)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014926)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101697b)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81019d46)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/xen/suspend.c (ffffffff8101c1d9)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102a006)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_is_hypercall_page_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:read_hv_clock_msr
```
```
In arch/x86/realmode/init.c (ffffffff826af590)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff8102bb09)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/tsc.c (ffffffff826b34db)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff81037b5d)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
```
```
In arch/x86/kernel/process.c (ffffffff826b392e)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103ddc9)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81041072)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81041ea2)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81043101)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81043532)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104444b)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff826b4ff9)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff810478b9)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104b5d1)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104cb73)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104cf57)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104ef98)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff826b5f31)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81051836)
Location: arch/x86/include/asm/paravirt.h:109
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
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff826b758a)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810533f9)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105447e)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff826b8494)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81058c7a)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff826bc3ad)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105fa2e)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105fd91)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81060231)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read
```
```
In arch/x86/kernel/crash.c (ffffffff8106390d)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8106521d)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81069a0f)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8106fc0f)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
```
```
In arch/x86/mm/pat.c (ffffffff810786e3)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
```
```
In kernel/kexec_core.c (ffffffff81129ea5)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
  - kernel/kexec_core.c:crash_save_cpu
```
```
In arch/x86/lib/msr-smp.c (ffffffff814c7f7c)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff81535c09)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
```
In drivers/acpi/processor_perflib.c (ffffffff81594572)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817dda46)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817df09f)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:pending_bit_stuck
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff817e30eb)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
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
```
```
In arch/x86/pci/amd_bus.c (ffffffff8182262a)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
```
In arch/x86/power/cpu.c (ffffffff818227e0)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
```
```
In arch/x86/lib/insn-eval.c (ffffffff819835c1)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
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
In arch/x86/events/core.c (ffffffff810079e1)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/ibs.c (ffffffff826d02bf)
Location: arch/x86/include/asm/paravirt.h:109
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
In arch/x86/events/msr.c (ffffffff8100b0fa)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff826d0cc4)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fa83)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81010329)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff81010f41)
Location: arch/x86/include/asm/paravirt.h:109
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
```
```
In arch/x86/events/intel/p4.c (ffffffff826d216d)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff810123f5)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff826d251e)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015465)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101759b)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81018151)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/xen/suspend.c (ffffffff8101cbe9)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102af5d)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:read_hv_clock_msr
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102bb15)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_read
```
```
In arch/x86/realmode/init.c (ffffffff826d8c99)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff8102cb4f)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/tsc.c (ffffffff826dccbf)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff81038c18)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
```
```
In arch/x86/kernel/process.c (ffffffff826dd112)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103f369)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810429e2)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff826de557)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81043db2)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81044f29)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104561c)
Location: arch/x86/include/asm/paravirt.h:109
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
In arch/x86/kernel/cpu/centaur.c (ffffffff810465b5)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff826dec98)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81049ed9)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104df16)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104f813)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81050cf7)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81051cb9)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff826dfc85)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81054565)
Location: arch/x86/include/asm/paravirt.h:109
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
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff826e129d)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810560a9)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057268)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff826e21ac)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8105bb78)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff826e615b)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81062b3e)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81062ea0)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81063310)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read
```
```
In arch/x86/kernel/crash.c (ffffffff8106657a)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81067de6)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8106c5ff)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff81072a7e)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
```
```
In arch/x86/mm/pat.c (ffffffff8107b346)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
```
```
In kernel/kexec_core.c (ffffffff81137ee0)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
  - kernel/kexec_core.c:crash_save_cpu
```
```
In arch/x86/lib/msr-smp.c (ffffffff814f8efc)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff8271ce0a)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
```
In drivers/acpi/processor_perflib.c (ffffffff815cb9a2)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818266d5)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81827c9f)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:pending_bit_stuck
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff82735553)
Location: arch/x86/include/asm/paravirt.h:109
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
```
```
In arch/x86/pci/amd_bus.c (ffffffff8186c915)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
```
In arch/x86/power/cpu.c (ffffffff8186ca54)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
```
```
In arch/x86/lib/insn-eval.c (ffffffff819dfb7d)
Location: arch/x86/include/asm/paravirt.h:109
Inline: True
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
In arch/x86/events/core.c (ffffffff810078c1)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/ibs.c (ffffffff8288637e)
Location: arch/x86/include/asm/paravirt.h:171
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
In arch/x86/events/msr.c (ffffffff8100b05a)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff82886e95)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/events/intel/ds.c (ffffffff81010053)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81010909)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff810115a1)
Location: arch/x86/include/asm/paravirt.h:171
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
In arch/x86/events/intel/p4.c (ffffffff8288847d)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff81012a75)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff8288882e)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015b75)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81017d1b)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81018921)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/xen/suspend.c (ffffffff8101c479)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102b68d)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:read_hv_clock_msr
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102cae5)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_read
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff8102d194)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff8288f07d)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff8102e173)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/tsc.c (ffffffff82893102)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff81039e98)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
```
```
In arch/x86/kernel/process.c (ffffffff8289355a)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff81040969)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81043fff)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff828949c0)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff810457b2)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104693b)
Location: arch/x86/include/asm/paravirt.h:171
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
In arch/x86/kernel/cpu/amd.c (ffffffff8104706c)
Location: arch/x86/include/asm/paravirt.h:171
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8104854b)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81048835)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104b606)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104ced3)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8104d457)
Location: arch/x86/include/asm/paravirt.h:171
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
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8104f339)
Location: arch/x86/include/asm/paravirt.h:171
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
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff82895c3d)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81051c05)
Location: arch/x86/include/asm/paravirt.h:171
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
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff8289725f)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810537a9)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054828)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82898248)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105a259)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82898afa)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81061808)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8289cc9e)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106883e)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068ba0)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81069010)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read
```
```
In arch/x86/kernel/crash.c (ffffffff8106c5d9)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8106dca6)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81072495)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff81078ace)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
```
```
In arch/x86/mm/pat.c (ffffffff81081c86)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
```
```
In kernel/kexec_core.c (ffffffff81143700)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
  - kernel/kexec_core.c:crash_save_cpu
```
```
In arch/x86/lib/msr-smp.c (ffffffff8150d79c)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff828d4e20)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
```
In drivers/acpi/processor_perflib.c (ffffffff815e4f82)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818525c5)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81853b9f)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:pending_bit_stuck
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff828ef47f)
Location: arch/x86/include/asm/paravirt.h:171
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
```
```
In arch/x86/pci/amd_bus.c (ffffffff8188c925)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
```
In arch/x86/power/cpu.c (ffffffff8188ca64)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a1aa3d)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
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
In arch/x86/events/core.c (ffffffff81007ba5)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81008c26)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
```
```
In arch/x86/events/amd/ibs.c (ffffffff8289d2c3)
Location: arch/x86/include/asm/paravirt.h:171
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
In arch/x86/events/msr.c (ffffffff8100b52a)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8289dd80)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/events/intel/ds.c (ffffffff8101118e)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81011ac9)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff810129f7)
Location: arch/x86/include/asm/paravirt.h:171
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
In arch/x86/events/intel/p4.c (ffffffff8289f5ee)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff81013e15)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff8289f9a8)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017135)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101930b)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81019d36)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c931)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/xen/suspend.c (ffffffff8101dfd9)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102d41d)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102e845)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_read
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff8102ef72)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff828a65bf)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff8102fec4)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/tsc.c (ffffffff828aa78f)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff8103c459)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
```
```
In arch/x86/kernel/process.c (ffffffff828aabcf)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff81043019)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104658c)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff828ac451)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81047f82)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff828acb90)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104934b)
Location: arch/x86/include/asm/paravirt.h:171
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
In arch/x86/kernel/cpu/intel_epb.c (ffffffff81049b25)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_save
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81049cc4)
Location: arch/x86/include/asm/paravirt.h:171
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b406)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104b5f5)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104b915)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e547)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fe03)
Location: arch/x86/include/asm/paravirt.h:171
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810503a6)
Location: arch/x86/include/asm/paravirt.h:171
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052459)
Location: arch/x86/include/asm/paravirt.h:171
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
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff828ad7da)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81054d25)
Location: arch/x86/include/asm/paravirt.h:171
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
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828aee0a)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105694b)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057a70)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828afe17)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105d529)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b06fd)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81064f08)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b4f87)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106c05c)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c3b0)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106c830)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read
```
```
In arch/x86/kernel/crash.c (ffffffff810705d9)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81071ccf)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81075fa5)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8107c63e)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
```
```
In arch/x86/mm/pat.c (ffffffff81085926)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
```
```
In kernel/kexec_core.c (ffffffff8114ea46)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
  - kernel/kexec_core.c:crash_save_cpu
```
```
In arch/x86/lib/msr-smp.c (ffffffff8153be4c)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff815b3a60)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff81616b6d)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81895b55)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8189715f)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/powernow-k8.c:pending_bit_stuck
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8290a98d)
Location: arch/x86/include/asm/paravirt.h:171
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
In drivers/clocksource/hyperv_timer.c (ffffffff8290fbaf)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc
```
```
In arch/x86/pci/amd_bus.c (ffffffff818d7265)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
```
In arch/x86/power/cpu.c (ffffffff818d73d4)
Location: arch/x86/include/asm/paravirt.h:171
Inline: True
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a8a773)
Location: arch/x86/include/asm/paravirt.h:171
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
In arch/x86/events/core.c (ffffffff81007dce)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81008f46)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
```
```
In arch/x86/events/amd/ibs.c (ffffffff828a0332)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/events/msr.c (ffffffff8100b93a)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff828a0dfa)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/events/intel/ds.c (ffffffff8101186e)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81012289)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff810131a7)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/events/intel/p4.c (ffffffff828a26c0)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff810145c5)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff828a2a7a)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017ae5)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019c8b)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a6b6)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101d2b1)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/xen/suspend.c (ffffffff8101e959)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102dd2d)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f155)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_read
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff8102f8d2)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff828a95fe)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff81030824)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/tsc.c (ffffffff828ad7ff)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff8103cc19)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
```
```
In arch/x86/kernel/process.c (ffffffff828adc3f)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff81043779)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046cec)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff828af5c3)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81048832)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff828afd9b)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049c1b)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/kernel/cpu/tsx.c (ffffffff8104a2b5)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104a4b5)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_save
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a654)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bde3)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104bfb5)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c2d5)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104eee7)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81050793)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81050d16)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052d49)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff828b0b1e)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055605)
Location: arch/x86/include/asm/paravirt.h:159
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
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828b214f)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810571fb)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058340)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828b3150)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105ddd9)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b3b45)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065578)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b83e4)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106cc0c)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106cf60)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106dab0)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106df80)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read
```
```
In arch/x86/kernel/crash.c (ffffffff810715d9)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81072cff)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81076f75)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8107d72e)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
```
```
In arch/x86/mm/pat.c (ffffffff81086616)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
```
```
In kernel/kexec_core.c (ffffffff8115a756)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
  - kernel/kexec_core.c:crash_save_cpu
```
```
In arch/x86/lib/msr-smp.c (ffffffff8155cc5c)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff815d4ca0)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff816380cd)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818c7b65)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818c916f)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/powernow-k8.c:pending_bit_stuck
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff82914384)
Location: arch/x86/include/asm/paravirt.h:159
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
In drivers/clocksource/hyperv_timer.c (ffffffff829198c4)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
```
```
In arch/x86/pci/amd_bus.c (ffffffff819095e5)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
```
In arch/x86/power/cpu.c (ffffffff81909a64)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
```
```
In arch/x86/lib/insn-eval.c (ffffffff81ac1a33)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u64 paravirt_read_msr(unsigned int msr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff810082cc)
Location: arch/x86/include/asm/paravirt.h:165
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
In arch/x86/events/amd/core.c (ffffffff8100a086)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100b745)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/msr.c (ffffffff8100cc76)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100ea5e)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81012cce)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff810136f9)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff81014d0c)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
```
```
In arch/x86/events/intel/p4.c (ffffffff81014fb5)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
Direct callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/intel/p6.c (ffffffff81015c75)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff810164e4)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
Direct callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff81019695)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101b4cb)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101c146)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101f0c6)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8101f7bf)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
```
In arch/x86/xen/suspend.c (ffffffff81020f05)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102ff97)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_suspend
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81031c75)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_read
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81032003)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff82ccecab)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:setup_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff81032c59)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/tsc.c (ffffffff82cd287a)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:detect_art
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff8103fa89)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
```
```
In arch/x86/kernel/process.c (ffffffff8104088d)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
Direct callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
```
```
In arch/x86/kernel/step.c (ffffffff81047199)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a98a)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:generic_identify
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b870)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8104c8d2)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff82cd5026)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff8104d4bb)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104ddf9)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:detect_tme
  - arch/x86/kernel/cpu/intel.c:early_init_intel
Direct callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_setup
  - arch/x86/kernel/cpu/intel.c:cpu_set_core_cap_bits
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff8104e8c5)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104ea55)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_save
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104f564)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt
  - arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81050695)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:hygon_get_topology
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff810507a0)
Location: arch/x86/include/asm/paravirt.h:165
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81050a80)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81053720)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_cap_init
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81054e33)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810560f0)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81057d59)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work
  - arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff82cd5b46)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:set_num_var_ranges
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105a8f5)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_var_ranges
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_var_ranges
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
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff8105b2fb)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105c4ab)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105de1e)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82cd7f76)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:__check_quirks_intel
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810639d9)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81067ae5)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106b75f)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:arch_scale_freq_tick
  - arch/x86/kernel/smpboot.c:arch_scale_freq_tick
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106bec6)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106cd35)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81073f00)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074730)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075150)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075950)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read
```
```
In arch/x86/kernel/crash.c (ffffffff810786db)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8107a243)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8107e2a5)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff81083f4f)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
```
```
In arch/x86/mm/pat/memtype.c (ffffffff8108fd96)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:init_cache_modes
```
```
In kernel/kexec_core.c (ffffffff8116b526)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
  - kernel/kexec_core.c:crash_save_cpu
```
```
In arch/x86/lib/msr-smp.c (ffffffff815e667c)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
```
```
In arch/x86/lib/insn-eval.c (ffffffff815fdfad)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
```
```
In drivers/idle/intel_idle.c (ffffffff8167e982)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_init
  - drivers/idle/intel_idle.c:intel_idle_cpu_init
Direct callers:
  - drivers/idle/intel_idle.c:sklh_idle_state_table_update
  - drivers/idle/intel_idle.c:sklh_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
```
```
In drivers/acpi/processor_perflib.c (ffffffff816e4d64)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199a735)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199c455)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:165
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a0b57)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
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
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff819c3105)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_tsc_clocksource
```
```
In arch/x86/pci/amd_bus.c (ffffffff81bb9ee5)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff81bba194)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
```
**Symbols:**

```
ffffffff81006540-ffffffff8100654f: paravirt_read_msr (STB_LOCAL)
ffffffff8100cd60-ffffffff8100cd6f: paravirt_read_msr (STB_LOCAL)
ffffffff81014e30-ffffffff81014e3f: paravirt_read_msr (STB_LOCAL)
ffffffff81017ca8-ffffffff81017cb7: paravirt_read_msr (STB_LOCAL)
ffffffff8102f9d0-ffffffff8102f9df: paravirt_read_msr (STB_LOCAL)
ffffffff81032060-ffffffff8103206f: paravirt_read_msr (STB_LOCAL)
ffffffff8103fef0-ffffffff8103feff: paravirt_read_msr (STB_LOCAL)
ffffffff8104b870-ffffffff8104b87f: paravirt_read_msr (STB_LOCAL)
ffffffff8104d7a0-ffffffff8104d7af: paravirt_read_msr (STB_LOCAL)
ffffffff810507a0-ffffffff810507af: paravirt_read_msr (STB_LOCAL)
ffffffff81050a80-ffffffff81050a92: paravirt_read_msr.constprop.0 (STB_LOCAL)
ffffffff8105a570-ffffffff8105a57f: paravirt_read_msr (STB_LOCAL)
ffffffff8105b2fb-ffffffff8105b30d: paravirt_read_msr.constprop.0 (STB_LOCAL)
ffffffff81067850-ffffffff8106785f: paravirt_read_msr (STB_LOCAL)
ffffffff8106c360-ffffffff8106c36f: paravirt_read_msr (STB_LOCAL)
ffffffff8167e870-ffffffff8167e87f: paravirt_read_msr (STB_LOCAL)
ffffffff8199dca0-ffffffff8199dcaf: paravirt_read_msr (STB_LOCAL)
ffffffff819c2de0-ffffffff819c2def: paravirt_read_msr (STB_LOCAL)
ffffffff81bb9ed0-ffffffff81bb9edf: paravirt_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u64 paravirt_read_msr(unsigned int msr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100737c)
Location: arch/x86/include/asm/paravirt.h:163
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
In arch/x86/events/amd/core.c (ffffffff81008f06)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
```
```
In arch/x86/events/amd/ibs.c (ffffffff82fb200f)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/msr.c (ffffffff8100bbc6)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100d70e)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_pmu_disable_fixed
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff8101286e)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff810132a9)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101517b)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_disable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
```
```
In arch/x86/events/intel/p4.c (ffffffff81015455)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
Direct callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/intel/p6.c (ffffffff81016115)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff81016984)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
Direct callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff81019cd5)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101b9cb)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101c6b6)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_cpu_init
  - arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ef76)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8102025f)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
```
In arch/x86/xen/suspend.c (ffffffff81021775)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81030bc7)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_suspend
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81032955)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_read
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81032c63)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff82fbab40)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:setup_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff8103320f)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_fsbase_read_task
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81c35e53)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/tsc.c (ffffffff82fbe6c1)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:detect_art
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff8103f919)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
```
```
In arch/x86/kernel/process.c (ffffffff810407dd)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
Direct callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
```
```
In arch/x86/kernel/step.c (ffffffff810469e9)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81049e3a)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:generic_identify
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104adb0)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8104bda2)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff82fc0fcc)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff8104c93b)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104d329)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:detect_tme
  - arch/x86/kernel/cpu/intel.c:early_init_intel
Direct callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_setup
  - arch/x86/kernel/cpu/intel.c:cpu_set_core_cap_bits
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff8104dbd5)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104dd65)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_save
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104e844)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt
  - arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104f875)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:hygon_get_topology
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104f8f0)
Location: arch/x86/include/asm/paravirt.h:163
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104fbe0)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052840)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_cap_init
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81053dc3)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81054ff0)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81056ad9)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work
  - arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff82fc1b09)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:set_num_var_ranges
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81059455)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_var_ranges
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_var_ranges
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
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff81bd5e7e)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105ad1b)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105c3fe)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82fc3ed5)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:__check_quirks_intel
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81061df9)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810698e5)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106d40f)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:arch_scale_freq_tick
  - arch/x86/kernel/smpboot.c:arch_scale_freq_tick
  - arch/x86/kernel/smpboot.c:init_counter_refs
  - arch/x86/kernel/smpboot.c:init_counter_refs
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106d7a6)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106e4d5)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81074a60)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810751b0)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075780)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075f90)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read
```
```
In arch/x86/kernel/crash.c (ffffffff810786e0)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81079ab6)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8107df65)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8108549f)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
```
```
In arch/x86/mm/pat/memtype.c (ffffffff8108fa96)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:init_cache_modes
```
```
In kernel/kexec_core.c (ffffffff81167ce2)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
```
In arch/x86/lib/msr-smp.c (ffffffff8160b7cc)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
```
```
In arch/x86/lib/insn-eval.c (ffffffff81622e9d)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
```
```
In drivers/idle/intel_idle.c (ffffffff8169d682)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_init
  - drivers/idle/intel_idle.c:intel_idle_cpu_init
Direct callers:
  - drivers/idle/intel_idle.c:sklh_idle_state_table_update
  - drivers/idle/intel_idle.c:sklh_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
```
```
In drivers/acpi/processor_perflib.c (ffffffff817027d4)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199d895)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199f4f5)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:163
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a3924)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
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
  - drivers/cpufreq/intel_pstate.c:show_energy_efficiency
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:show_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff8301a9a1)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
```
```
In arch/x86/pci/amd_bus.c (ffffffff81bce755)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff81bcea09)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
```
**Symbols:**

```
ffffffff810056b0-ffffffff810056bf: paravirt_read_msr (STB_LOCAL)
ffffffff8100bcb0-ffffffff8100bcbf: paravirt_read_msr (STB_LOCAL)
ffffffff810152d0-ffffffff810152df: paravirt_read_msr (STB_LOCAL)
ffffffff81bd22db-ffffffff81bd22ea: paravirt_read_msr (STB_LOCAL)
ffffffff81030600-ffffffff8103060f: paravirt_read_msr (STB_LOCAL)
ffffffff81032cc0-ffffffff81032ccf: paravirt_read_msr (STB_LOCAL)
ffffffff8103fe30-ffffffff8103fe3f: paravirt_read_msr (STB_LOCAL)
ffffffff8104adb0-ffffffff8104adbf: paravirt_read_msr (STB_LOCAL)
ffffffff8104ccd0-ffffffff8104ccdf: paravirt_read_msr (STB_LOCAL)
ffffffff8104f8f0-ffffffff8104f8ff: paravirt_read_msr (STB_LOCAL)
ffffffff8104fbe0-ffffffff8104fbf2: paravirt_read_msr.constprop.0 (STB_LOCAL)
ffffffff810590d0-ffffffff810590df: paravirt_read_msr (STB_LOCAL)
ffffffff81bd5e7e-ffffffff81bd5e90: paravirt_read_msr.constprop.0 (STB_LOCAL)
ffffffff81069600-ffffffff8106960f: paravirt_read_msr (STB_LOCAL)
ffffffff8106daf0-ffffffff8106daff: paravirt_read_msr (STB_LOCAL)
ffffffff8169d570-ffffffff8169d57f: paravirt_read_msr (STB_LOCAL)
ffffffff819a0890-ffffffff819a089f: paravirt_read_msr (STB_LOCAL)
ffffffff81bce740-ffffffff81bce74f: paravirt_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u64 paravirt_read_msr(unsigned int msr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007afc)
Location: arch/x86/include/asm/paravirt.h:180
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
In arch/x86/events/amd/core.c (ffffffff810098a6)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100ae25)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/msr.c (ffffffff8100c556)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100ebcb)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81013a5e)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff810144b9)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff810163f5)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
```
```
In arch/x86/events/intel/p4.c (ffffffff810166d1)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
Direct callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/intel/p6.c (ffffffff81017405)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff81017c64)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
Direct callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101b055)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101cd7b)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101db85)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_cpu_init
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_cpu_init
  - arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81020d56)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810225df)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
```
In arch/x86/xen/suspend.c (ffffffff81023b1c)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff810316e7)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_suspend
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81033db5)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_read
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff8103477b)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff831c53e1)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:setup_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff81034d51)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsbase_read_task
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81c282e7)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/tsc.c (ffffffff831c9087)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff810412b7)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
```
```
In arch/x86/kernel/process.c (ffffffff810421cd)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
Direct callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
```
```
In arch/x86/kernel/step.c (ffffffff81048269)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104b6ea)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:generic_identify
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104c690)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8104d8d2)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff831cb5e7)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff8104e44b)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104eea8)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:detect_tme
  - arch/x86/kernel/cpu/intel.c:early_init_intel
Direct callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_setup
  - arch/x86/kernel/cpu/intel.c:split_lock_setup
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff8104f865)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104f9f5)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_save
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810502d4)
Location: arch/x86/include/asm/paravirt.h:180
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
In arch/x86/kernel/cpu/hygon.c (ffffffff810511bd)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff810514a0)
Location: arch/x86/include/asm/paravirt.h:180
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81051790)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81054052)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81055693)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81056580)
Location: arch/x86/include/asm/paravirt.h:180
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
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff831cc253)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81059da5)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff81bc822a)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105b6cb)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105cd0e)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff831ce7d8)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810625b9)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8106a335)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106de7f)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:arch_scale_freq_tick
  - arch/x86/kernel/smpboot.c:arch_scale_freq_tick
  - arch/x86/kernel/smpboot.c:init_counter_refs
  - arch/x86/kernel/smpboot.c:init_counter_refs
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106e216)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106efc5)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81075870)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075c50)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81076220)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81076a20)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read
```
```
In arch/x86/kernel/crash.c (ffffffff81079597)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8107f085)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8108619f)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
```
```
In arch/x86/mm/pat/memtype.c (ffffffff81090596)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:init_cache_modes
```
```
In kernel/kexec_core.c (ffffffff81168a72)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
```
In arch/x86/lib/msr-smp.c (ffffffff815eeaac)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
```
```
In arch/x86/lib/insn-eval.c (ffffffff8160662d)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
```
```
In drivers/idle/intel_idle.c (ffffffff81680433)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
```
In drivers/acpi/processor_perflib.c (ffffffff816e4269)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81947499)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81982435)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff819848c7)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:180
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81988569)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
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
  - drivers/cpufreq/intel_pstate.c:show_energy_efficiency
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:show_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff832259d2)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
```
```
In arch/x86/pci/amd_bus.c (ffffffff81bc2105)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff81bc23b9)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
```
**Symbols:**

```
ffffffff81005610-ffffffff8100561f: paravirt_read_msr (STB_LOCAL)
ffffffff8100c640-ffffffff8100c64f: paravirt_read_msr (STB_LOCAL)
ffffffff81016540-ffffffff8101654f: paravirt_read_msr (STB_LOCAL)
ffffffff81bc45cf-ffffffff81bc45de: paravirt_read_msr (STB_LOCAL)
ffffffff810310f0-ffffffff810310ff: paravirt_read_msr (STB_LOCAL)
ffffffff810347d0-ffffffff810347df: paravirt_read_msr (STB_LOCAL)
ffffffff810417d0-ffffffff810417df: paravirt_read_msr (STB_LOCAL)
ffffffff8104c690-ffffffff8104c69f: paravirt_read_msr (STB_LOCAL)
ffffffff8104e870-ffffffff8104e87f: paravirt_read_msr (STB_LOCAL)
ffffffff810514a0-ffffffff810514af: paravirt_read_msr (STB_LOCAL)
ffffffff81051790-ffffffff810517a2: paravirt_read_msr.constprop.0 (STB_LOCAL)
ffffffff81059a20-ffffffff81059a2f: paravirt_read_msr (STB_LOCAL)
ffffffff81bc822a-ffffffff81bc823c: paravirt_read_msr.constprop.0 (STB_LOCAL)
ffffffff8106a090-ffffffff8106a09f: paravirt_read_msr (STB_LOCAL)
ffffffff8106e560-ffffffff8106e56f: paravirt_read_msr (STB_LOCAL)
ffffffff816802f0-ffffffff816802ff: paravirt_read_msr (STB_LOCAL)
ffffffff819854f0-ffffffff819854ff: paravirt_read_msr (STB_LOCAL)
ffffffff81bc20f0-ffffffff81bc20ff: paravirt_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u64 paravirt_read_msr(unsigned int msr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100850d)
Location: arch/x86/include/asm/paravirt.h:180
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
In arch/x86/events/amd/core.c (ffffffff8100a87a)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100b5a5)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/msr.c (ffffffff8100ca86)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100f663)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81014d7e)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81015839)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff81017e55)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
```
```
In arch/x86/events/intel/p4.c (ffffffff8101818b)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
Direct callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/intel/p6.c (ffffffff810191b5)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff8101a9d5)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
Direct callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101d985)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101fe53)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81020c85)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_cpu_init
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_cpu_init
  - arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81023c56)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8102643f)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
```
In arch/x86/xen/suspend.c (ffffffff81027dbc)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81036987)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_suspend
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81038aa5)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_read
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81039a1b)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff832a60b7)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:setup_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff8103a071)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsbase_read_task
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81d46457)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/tsc.c (ffffffff832aa348)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff8104750a)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
```
```
In arch/x86/kernel/process.c (ffffffff8104851d)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
Direct callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
```
```
In arch/x86/kernel/step.c (ffffffff8104eb79)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81052f62)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81053980)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81055032)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff832acd25)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff81055e3b)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81056f98)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:detect_tme
  - arch/x86/kernel/cpu/intel.c:early_init_intel
Direct callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_setup
  - arch/x86/kernel/cpu/intel.c:split_lock_setup
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff81057a45)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff81057c55)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_save
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810585c4)
Location: arch/x86/include/asm/paravirt.h:180
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8105964a)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81059a30)
Location: arch/x86/include/asm/paravirt.h:180
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81059d20)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105c914)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105e033)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105f190)
Location: arch/x86/include/asm/paravirt.h:180
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
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff832adaf3)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810631b5)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff81c9c0a5)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81064cbc)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810663df)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff832b07a3)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:check_quirks
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106c429)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81074ab5)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/smpboot.c (ffffffff8107969f)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:arch_scale_freq_tick
  - arch/x86/kernel/smpboot.c:arch_scale_freq_tick
  - arch/x86/kernel/smpboot.c:init_counter_refs
  - arch/x86/kernel/smpboot.c:init_counter_refs
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81079ab6)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81079eb0)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81082d90)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810831d0)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81083820)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810841f0)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read
```
```
In arch/x86/kernel/crash.c (ffffffff810875f7)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/hpet.c (ffffffff832bd6c0)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8108dd15)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8109537f)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
```
```
In arch/x86/mm/pat/memtype.c (ffffffff8109ffa6)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:init_cache_modes
```
```
In kernel/kexec_core.c (ffffffff8118e7b1)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
```
In arch/x86/lib/msr-smp.c (ffffffff8165bb6f)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
```
```
In arch/x86/lib/insn-eval.c (ffffffff8167506d)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
```
```
In drivers/idle/intel_idle.c (ffffffff816f51d6)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
```
In drivers/acpi/processor_perflib.c (ffffffff8175cf09)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff819ec2fd)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81a2b8e5)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81a2dfc7)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:180
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81a325f9)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
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
  - drivers/cpufreq/intel_pstate.c:show_energy_efficiency
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:show_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff8330fbac)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
```
```
In drivers/hv/hv_common.c (ffffffff81a61095)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:__hv_read_ref_counter
  - drivers/hv/hv_common.c:hv_common_cpu_init
```
```
In arch/x86/pci/amd_bus.c (ffffffff81c92715)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff81c92a25)
Location: arch/x86/include/asm/paravirt.h:180
Inline: True
```
**Symbols:**

```
ffffffff81005c50-ffffffff81005c5f: paravirt_read_msr (STB_LOCAL)
ffffffff8100cb70-ffffffff8100cb7f: paravirt_read_msr (STB_LOCAL)
ffffffff81017fc0-ffffffff81017fcf: paravirt_read_msr (STB_LOCAL)
ffffffff81c963c7-ffffffff81c963d6: paravirt_read_msr (STB_LOCAL)
ffffffff81036390-ffffffff8103639f: paravirt_read_msr (STB_LOCAL)
ffffffff81039ad0-ffffffff81039adf: paravirt_read_msr (STB_LOCAL)
ffffffff81047a70-ffffffff81047a7f: paravirt_read_msr (STB_LOCAL)
ffffffff81053980-ffffffff8105398f: paravirt_read_msr (STB_LOCAL)
ffffffff81056290-ffffffff8105629f: paravirt_read_msr (STB_LOCAL)
ffffffff81059a30-ffffffff81059a3f: paravirt_read_msr (STB_LOCAL)
ffffffff81059d20-ffffffff81059d32: paravirt_read_msr.constprop.0 (STB_LOCAL)
ffffffff81062cd0-ffffffff81062cdf: paravirt_read_msr (STB_LOCAL)
ffffffff81c9c0a5-ffffffff81c9c0b7: paravirt_read_msr.constprop.0 (STB_LOCAL)
ffffffff810748b0-ffffffff810748bf: paravirt_read_msr (STB_LOCAL)
ffffffff81079eb0-ffffffff81079ebf: paravirt_read_msr (STB_LOCAL)
ffffffff816f5060-ffffffff816f506f: paravirt_read_msr (STB_LOCAL)
ffffffff81a2f000-ffffffff81a2f00f: paravirt_read_msr (STB_LOCAL)
ffffffff81c92700-ffffffff81c9270f: paravirt_read_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u64 paravirt_read_msr(unsigned int msr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007b09)
Location: arch/x86/include/asm/paravirt.h:186
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
In arch/x86/events/amd/core.c (ffffffff8100aeee)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_test_overflow_status
  - arch/x86/events/amd/core.c:amd_pmu_test_overflow_topbit
```
```
In arch/x86/events/amd/brs.c (ffffffff8100b448)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/amd/brs.c:perf_amd_brs_lopwr_cb
  - arch/x86/events/amd/brs.c:amd_pmu_brs_sched_task
  - arch/x86/events/amd/brs.c:amd_brs_drain
  - arch/x86/events/amd/brs.c:amd_brs_drain
  - arch/x86/events/amd/brs.c:amd_brs_drain
  - arch/x86/events/amd/brs.c:amd_brs_disable
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100c035)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/msr.c (ffffffff8100d886)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81010bbe)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81016bae)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81017906)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff81019ea8)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
```
```
In arch/x86/events/intel/p4.c (ffffffff8101a2db)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
Direct callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/intel/p6.c (ffffffff8101b3f5)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff8101d1c5)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
Direct callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff81020385)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81022d27)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81024195)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_cpu_init
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_cpu_init
  - arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81028a96)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8102a537)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
```
In arch/x86/xen/suspend.c (ffffffff8102c2b6)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8103c309)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_is_hyperv_initialized
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_suspend
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103f725)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_read
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff8104091c)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff83455208)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:setup_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff810410a7)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsbase_read_task
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81042a26)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_xfd_event
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/tsc.c (ffffffff83459b26)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff81050370)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
```
```
In arch/x86/kernel/process.c (ffffffff8105185a)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
Direct callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81052d0c)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_sync_guest_vmexit_xfd_state
```
```
In arch/x86/kernel/step.c (ffffffff81059d88)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105e9cf)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81e4a02f)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff810610a2)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
  - arch/x86/kernel/cpu/aperfmperf.c:init_counter_refs
  - arch/x86/kernel/cpu/aperfmperf.c:init_counter_refs
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff8345da8e)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff81061e3b)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81063305)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:detect_tme
  - arch/x86/kernel/cpu/intel.c:early_init_intel
Direct callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_setup
  - arch/x86/kernel/cpu/intel.c:split_lock_setup
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff81063ea7)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff81064105)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_save
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81064da3)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81065d1e)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81066120)
Location: arch/x86/include/asm/paravirt.h:186
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff810664b0)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8106907b)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8106a773)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106b9d1)
Location: arch/x86/include/asm/paravirt.h:186
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
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8345e9c8)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8106fd85)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff81e4b4c2)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810716ad)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81073151)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff834618a7)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:check_quirks
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81079808)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810833d5)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810888de)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810899d5)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81092aba)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81093060)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810937c0)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810942d0)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read
```
```
In arch/x86/kernel/crash.c (ffffffff81097761)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/hpet.c (ffffffff8346f0b5)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8109e465)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/kvm.c (ffffffff8109fb73)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_suspend
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff810a7739)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810b3e99)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_init
Direct callers:
  - arch/x86/mm/pat/memtype.c:init_cache_modes
```
```
In kernel/kexec_core.c (ffffffff811bde27)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
```
In arch/x86/lib/msr-smp.c (ffffffff817749ff)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
```
```
In arch/x86/lib/insn-eval.c (ffffffff8178f99c)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81821b0b)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
```
In drivers/acpi/processor_perflib.c (ffffffff81890ac1)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81b522ed)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81b52b51)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81b95e25)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81b9733d)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_sample
  - drivers/cpufreq/amd-pstate.c:amd_pstate_sample
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81b9981f)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:186
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9eb45)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
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
  - drivers/cpufreq/intel_pstate.c:show_energy_efficiency
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:show_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff834c99e3)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
```
```
In drivers/hv/hv_common.c (ffffffff81bd1735)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:__hv_read_ref_counter
  - drivers/hv/hv_common.c:hv_common_cpu_init
```
```
In arch/x86/pci/amd_bus.c (ffffffff81e41e95)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff81e42374)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
```
**Symbols:**

```
ffffffff81004ec0-ffffffff81004ee6: paravirt_read_msr (STB_LOCAL)
ffffffff8100d9f0-ffffffff8100da16: paravirt_read_msr (STB_LOCAL)
ffffffff8101a0a0-ffffffff8101a0c6: paravirt_read_msr (STB_LOCAL)
ffffffff81e456a7-ffffffff81e456cd: paravirt_read_msr (STB_LOCAL)
ffffffff8103c1d0-ffffffff8103c1f6: paravirt_read_msr (STB_LOCAL)
ffffffff81040a20-ffffffff81040a46: paravirt_read_msr (STB_LOCAL)
ffffffff81050af0-ffffffff81050b16: paravirt_read_msr (STB_LOCAL)
ffffffff81e4a02f-ffffffff81e4a055: paravirt_read_msr (STB_LOCAL)
ffffffff810622e0-ffffffff81062306: paravirt_read_msr (STB_LOCAL)
ffffffff81066120-ffffffff81066146: paravirt_read_msr (STB_LOCAL)
ffffffff810664b0-ffffffff810664d9: paravirt_read_msr.constprop.0 (STB_LOCAL)
ffffffff8106f8c0-ffffffff8106f8e6: paravirt_read_msr (STB_LOCAL)
ffffffff81e4b4c2-ffffffff81e4b4eb: paravirt_read_msr.constprop.0 (STB_LOCAL)
ffffffff81083180-ffffffff810831a6: paravirt_read_msr (STB_LOCAL)
ffffffff81088d20-ffffffff81088d46: paravirt_read_msr (STB_LOCAL)
ffffffff810b3c50-ffffffff810b3c79: paravirt_read_msr.constprop.0 (STB_LOCAL)
ffffffff81821960-ffffffff81821986: paravirt_read_msr (STB_LOCAL)
ffffffff81b9aac0-ffffffff81b9aae6: paravirt_read_msr (STB_LOCAL)
ffffffff81e41e60-ffffffff81e41e86: paravirt_read_msr (STB_LOCAL)
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
In arch/x86/events/core.c (ffffffff81009d8e)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff8100ce59)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_test_overflow_status
  - arch/x86/events/amd/core.c:amd_pmu_test_overflow_topbit
```
```
In arch/x86/events/amd/lbr.c (ffffffff8100dbe3)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_read
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_read
```
```
In arch/x86/events/amd/brs.c (ffffffff8100dcc8)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/amd/brs.c:perf_amd_brs_lopwr_cb
  - arch/x86/events/amd/brs.c:amd_pmu_brs_sched_task
  - arch/x86/events/amd/brs.c:amd_brs_drain
  - arch/x86/events/amd/brs.c:amd_brs_drain
  - arch/x86/events/amd/brs.c:amd_brs_drain
  - arch/x86/events/amd/brs.c:amd_brs_disable
```
```
In arch/x86/events/amd/ibs.c (ffffffff83e65ac7)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
  - arch/x86/events/amd/ibs.c:setup_APIC_ibs
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/msr.c (ffffffff81010ac6)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff83e67e37)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack
```
```
In arch/x86/events/intel/ds.c (ffffffff8101ad3e)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff8101bba6)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101def8)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
```
```
In arch/x86/events/intel/p4.c (ffffffff83e69195)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff8101f625)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff810215b5)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff81024c65)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81027a07)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81029295)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:mtl_uncore_cpu_init
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_cpu_init
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_cpu_init
  - arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102f296)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81031127)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
```
In arch/x86/xen/suspend.c (ffffffff81033236)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81044e79)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_is_hyperv_initialized
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_suspend
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048f35)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_read
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81049c13)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff83e72f7b)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:setup_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff8104a7b7)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsbase_read_task
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8104c435)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_xfd_event
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/tsc.c (ffffffff83e79651)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff8105d7a0)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
```
```
In arch/x86/kernel/process.c (ffffffff83e79a2c)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810603cc)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_sync_guest_vmexit_xfd_state
```
```
In arch/x86/kernel/step.c (ffffffff81067948)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106cfcc)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff83e7e1eb)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8106f9d2)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
  - arch/x86/kernel/cpu/aperfmperf.c:init_counter_refs
  - arch/x86/kernel/cpu/aperfmperf.c:init_counter_refs
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff83e7e9a0)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff8107086b)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81072305)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:detect_tme
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:sld_setup
  - arch/x86/kernel/cpu/intel.c:sld_setup
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff81073017)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable
  - arch/x86/kernel/cpu/tsx.c:tsx_clear_cpuid
  - arch/x86/kernel/cpu/tsx.c:tsx_clear_cpuid
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff810732a5)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_save
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81074053)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107505a)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8107566c)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81075a63)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81078c1b)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107a5d3)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107bca0)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff83e7fbfb)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8107fff5)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_disable
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff83e82631)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81081fa7)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81083221)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff83e83c17)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108a4ac)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108d6db)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff83e85aef)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz
```
```
In arch/x86/kernel/reboot.c (ffffffff81097da6)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:cpu_emergency_svm_disable
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109c3fb)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff83e8d961)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810a7c3a)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810a83d0)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a8e20)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a9b60)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read
```
```
In arch/x86/kernel/hpet.c (ffffffff83e952c4)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_is_pc10_damaged
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810b5b75)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/kvm.c (ffffffff810b74d3)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_suspend
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff810c0a59)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
```
```
In arch/x86/mm/pat/memtype.c (ffffffff83e9ce13)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_bp_init
```
```
In kernel/kexec_core.c (ffffffff811ffe87)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
```
In arch/x86/lib/msr-smp.c (ffffffff818a549f)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff8195280b)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
```
```
In drivers/acpi/processor_perflib.c (ffffffff819d7bf1)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81cea4ad)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81cead94)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d369e5)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81d381ad)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_sample
  - drivers/cpufreq/amd-pstate.c:amd_pstate_sample
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81d3ac3f)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:186
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff83f03656)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
  - drivers/cpufreq/intel_pstate.c:atom_get_vid
  - drivers/cpufreq/intel_pstate.c:atom_get_vid
  - drivers/cpufreq/intel_pstate.c:airmont_get_scaling
  - drivers/cpufreq/intel_pstate.c:silvermont_get_scaling
  - drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate
  - drivers/cpufreq/intel_pstate.c:atom_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:atom_get_min_pstate
  - drivers/cpufreq/intel_pstate.c:show_energy_efficiency
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:show_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff83f0b091)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
  - drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
  - drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc
```
```
In drivers/hv/hv_common.c (ffffffff81d7d245)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:__hv_read_ref_counter
  - drivers/hv/hv_common.c:hv_common_cpu_init
```
```
In arch/x86/pci/amd_bus.c (ffffffff8201c645)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff8201cd44)
Location: arch/x86/include/asm/paravirt.h:186
Inline: True
```
```
In arch/x86/lib/insn-eval.c (ffffffff8204d50c)
Location: arch/x86/include/asm/paravirt.h:186
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
In arch/x86/events/core.c (ffffffff810095ac)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff8100c61c)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_test_overflow_status
  - arch/x86/events/amd/core.c:amd_pmu_test_overflow_topbit
```
```
In arch/x86/events/amd/lbr.c (ffffffff8100d3b3)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_read
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_read
```
```
In arch/x86/events/amd/brs.c (ffffffff8100d7d0)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/events/amd/brs.c:amd_brs_drain
  - arch/x86/events/amd/brs.c:amd_brs_drain
```
```
In arch/x86/events/amd/ibs.c (ffffffff83686147)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
  - arch/x86/events/amd/ibs.c:setup_APIC_ibs
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/msr.c (ffffffff81010186)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff836871e9)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack
```
```
In arch/x86/events/intel/ds.c (ffffffff8101a7ce)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff8101b876)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101dbf8)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
```
```
In arch/x86/events/intel/p4.c (ffffffff83689b25)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff8101f335)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff81021305)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff81024b65)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81027a27)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff810292c5)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:mtl_uncore_cpu_init
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_cpu_init
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_cpu_init
  - arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102f9b8)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8103115d)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
```
In arch/x86/xen/suspend.c (ffffffff810331d6)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81044fb9)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_is_hyperv_initialized
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_suspend
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81049195)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_read
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81049e43)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff83693f2b)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:setup_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff8104aff7)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsbase_read_task
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8104cca5)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_xfd_event
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/tsc.c (ffffffff8369bc5c)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff8105edf0)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
```
```
In arch/x86/kernel/process.c (ffffffff8369c14e)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81061b5c)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_sync_guest_vmexit_xfd_state
```
```
In arch/x86/kernel/step.c (ffffffff810691f8)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106e92e)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810703a0)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:update_gds_msr
  - arch/x86/kernel/cpu/bugs.c:update_gds_msr
  - arch/x86/kernel/cpu/bugs.c:update_gds_msr
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff810715d2)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
  - arch/x86/kernel/cpu/aperfmperf.c:init_counter_refs
  - arch/x86/kernel/cpu/aperfmperf.c:init_counter_refs
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff836a16fb)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff8107246b)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81073ee5)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:detect_tme
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:sld_setup
  - arch/x86/kernel/cpu/intel.c:sld_setup
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff81074bf7)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable
  - arch/x86/kernel/cpu/tsx.c:tsx_clear_cpuid
  - arch/x86/kernel/cpu/tsx.c:tsx_clear_cpuid
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff81074e85)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_save
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81076142)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810771ca)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff810777dc)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81077bd1)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107aecb)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107c883)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107dfa0)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff836a2a1c)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81082385)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_disable
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff836a5944)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810844e7)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81085061)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff836a6f30)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810879f0)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108d51c)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8109058b)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff836a904f)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_non_nested_register
```
```
In arch/x86/kernel/reboot.c (ffffffff8109ae46)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:cpu_emergency_svm_disable
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109f53b)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff836b1201)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810aaeaa)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810ab640)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810ac040)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810acbb0)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read
```
```
In arch/x86/kernel/hpet.c (ffffffff836b8e22)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_is_pc10_damaged
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810b8c75)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/kvm.c (ffffffff810ba6c3)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_suspend
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff810c4139)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
```
```
In arch/x86/mm/pat/memtype.c (ffffffff836c0933)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_bp_init
```
```
In kernel/kexec_core.c (ffffffff812152e7)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
```
In arch/x86/lib/msr-smp.c (ffffffff818e82bf)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff81998c0b)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a1f5f1)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81d52fe1)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81d539a4)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d9fd95)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81da25ad)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_sample
  - drivers/cpufreq/amd-pstate.c:amd_pstate_sample
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81da573f)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:188
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff837295c6)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
  - drivers/cpufreq/intel_pstate.c:atom_get_vid
  - drivers/cpufreq/intel_pstate.c:atom_get_vid
  - drivers/cpufreq/intel_pstate.c:airmont_get_scaling
  - drivers/cpufreq/intel_pstate.c:silvermont_get_scaling
  - drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate
  - drivers/cpufreq/intel_pstate.c:atom_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:atom_get_min_pstate
  - drivers/cpufreq/intel_pstate.c:show_energy_efficiency
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:show_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state
```
```
In arch/x86/pci/amd_bus.c (ffffffff8209cce5)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff8209d3d4)
Location: arch/x86/include/asm/paravirt.h:188
Inline: True
```
```
In arch/x86/lib/insn-eval.c (ffffffff820cbe8a)
Location: arch/x86/include/asm/paravirt.h:188
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
In arch/x86/events/core.c (ffffffff8100eccc)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81011dfc)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_test_overflow_status
  - arch/x86/events/amd/core.c:amd_pmu_test_overflow_topbit
```
```
In arch/x86/events/amd/lbr.c (ffffffff81012bf3)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_read
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_read
```
```
In arch/x86/events/amd/brs.c (ffffffff81013010)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/events/amd/brs.c:amd_brs_drain
  - arch/x86/events/amd/brs.c:amd_brs_drain
```
```
In arch/x86/events/amd/ibs.c (ffffffff838b52d7)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
  - arch/x86/events/amd/ibs.c:setup_APIC_ibs
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/msr.c (ffffffff81015994)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff838b643c)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:init_hybrid_pmu
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack
```
```
In arch/x86/events/intel/ds.c (ffffffff8102032e)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff810213d7)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff81023cc8)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
```
```
In arch/x86/events/intel/p4.c (ffffffff838b9685)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff810253f5)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff81027495)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102acc5)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8102dc77)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8102f425)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:mtl_uncore_cpu_init
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_cpu_init
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_cpu_init
  - arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81035b34)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81037452)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
```
In arch/x86/xen/suspend.c (ffffffff81039446)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8104b85f)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_is_hyperv_initialized
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_suspend
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810505f5)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_read
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff810510a3)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff838c3e1b)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:setup_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff81052267)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsbase_read_task
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81053f25)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_xfd_event
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/tsc.c (ffffffff838cb75e)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:detect_art
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff81065ea0)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
```
```
In arch/x86/kernel/process.c (ffffffff838cbe2c)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81068c7c)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_sync_guest_vmexit_xfd_state
```
```
In arch/x86/kernel/step.c (ffffffff81070668)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81075c21)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81077c80)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:update_gds_msr
  - arch/x86/kernel/cpu/bugs.c:update_gds_msr
  - arch/x86/kernel/cpu/bugs.c:update_gds_msr
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81078f8a)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:ap_init_aperfmperf
  - arch/x86/kernel/cpu/aperfmperf.c:ap_init_aperfmperf
  - arch/x86/kernel/cpu/aperfmperf.c:bp_init_aperfmperf
  - arch/x86/kernel/cpu/aperfmperf.c:bp_init_aperfmperf
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff838d17fb)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff81079d6b)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8107b425)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:detect_tme_early
  - arch/x86/kernel/cpu/intel.c:sld_setup
  - arch/x86/kernel/cpu/intel.c:sld_setup
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff8107c0c7)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable
  - arch/x86/kernel/cpu/tsx.c:tsx_clear_cpuid
  - arch/x86/kernel/cpu/tsx.c:tsx_clear_cpuid
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8107c4e8)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107db4e)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107e784)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8107ed5c)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8107f0b1)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8108238b)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81083d73)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_claim_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_skip_bank
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_handle_storm
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_handle_storm
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81085450)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff838d2a9c)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81089e95)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_disable
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff838d59c4)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c2cd)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff838d6e0b)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:__check_quirks_intel
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108e970)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810948ac)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8109791b)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff838d9696)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_register
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a69cb)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff838e17cd)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:apic_read_boot_cpu_id
  - arch/x86/kernel/apic/apic.c:apic_read_boot_cpu_id
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810b1e6c)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810b24b0)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810b2dd0)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b3bd0)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read
```
```
In arch/x86/kernel/hpet.c (ffffffff838e9b3f)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810c00b5)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/kvm.c (ffffffff810c1b03)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_suspend
```
```
In arch/x86/kernel/cet.c (ffffffff810c9f45)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cet.c:do_user_cp_fault
```
```
In arch/x86/kernel/shstk.c (ffffffff810ca63c)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/shstk.c:wrss_control
  - arch/x86/kernel/shstk.c:restore_signal_shadow_stack
  - arch/x86/kernel/shstk.c:setup_signal_shadow_stack
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff810cc579)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
```
```
In arch/x86/mm/pat/memtype.c (ffffffff838f1453)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_bp_init
```
```
In kernel/kexec_core.c (ffffffff8122d287)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
```
```
In arch/x86/lib/msr-smp.c (ffffffff8192f75f)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff819e135b)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a6a911)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81e09d4d)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81e0a3fd)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_do_enable
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
  - drivers/thermal/intel/intel_hfi.c:hfi_disable
  - drivers/thermal/intel/intel_hfi.c:hfi_disable
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e57a02)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr_each
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81e5a67d)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_sample
  - drivers/cpufreq/amd-pstate.c:amd_pstate_sample
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5d7ff)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:190
Inline: False
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8395d556)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
  - drivers/cpufreq/intel_pstate.c:atom_get_vid
  - drivers/cpufreq/intel_pstate.c:atom_get_vid
  - drivers/cpufreq/intel_pstate.c:airmont_get_scaling
  - drivers/cpufreq/intel_pstate.c:silvermont_get_scaling
  - drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate
  - drivers/cpufreq/intel_pstate.c:atom_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:atom_get_min_pstate
  - drivers/cpufreq/intel_pstate.c:show_energy_efficiency
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:show_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state
```
```
In arch/x86/pci/amd_bus.c (ffffffff821744e5)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
```
```
In arch/x86/power/cpu.c (ffffffff82174bd4)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
```
```
In arch/x86/lib/insn-eval.c (ffffffff821a66ba)
Location: arch/x86/include/asm/paravirt.h:190
Inline: True
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
In arch/x86/events/core.c (ffffffff81007dce)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81008f46)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
```
```
In arch/x86/events/amd/ibs.c (ffffffff8288e332)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/events/msr.c (ffffffff8100b93a)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8288edfa)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/events/intel/ds.c (ffffffff8101186e)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81012289)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff810131a7)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/events/intel/p4.c (ffffffff828906c0)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff810145c5)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff82890a7a)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017ae5)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019c8b)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a6b6)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101d2b1)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/xen/suspend.c (ffffffff8101e969)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102de8d)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f2b5)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_read
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff8102fa32)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff8289760e)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff81030984)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/tsc.c (ffffffff8289b81e)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff8103cd99)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
```
```
In arch/x86/kernel/process.c (ffffffff8289bc5e)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff810438f9)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046e6c)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8289d5e2)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff810489a2)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff8289ddba)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049d8b)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/kernel/cpu/tsx.c (ffffffff8104a425)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104a625)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_save
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a7c4)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bf53)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104c125)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c445)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f047)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81050893)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81050e16)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052e49)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8289eb3d)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055185)
Location: arch/x86/include/asm/paravirt.h:159
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
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828a016e)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056d7b)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057ec0)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828a116f)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105d959)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828a1b64)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065068)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828a63eb)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106c6fc)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106ca50)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106cf20)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read
```
```
In arch/x86/kernel/crash.c (ffffffff810705d9)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81071cff)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81075f75)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8107c72e)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
```
```
In arch/x86/mm/pat.c (ffffffff81085616)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
```
```
In kernel/kexec_core.c (ffffffff81152d76)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
  - kernel/kexec_core.c:crash_save_cpu
```
```
In arch/x86/lib/msr-smp.c (ffffffff8155524c)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff815c89f0)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff81607285)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8186c285)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8186d88f)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/powernow-k8.c:pending_bit_stuck
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff828f9abe)
Location: arch/x86/include/asm/paravirt.h:159
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
In drivers/clocksource/hyperv_timer.c (ffffffff828fea30)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
```
```
In arch/x86/pci/amd_bus.c (ffffffff818a89a5)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
```
In arch/x86/power/cpu.c (ffffffff818a8e24)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a60883)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/events/core.c (ffffffff81007d8e)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81008f06)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
```
```
In arch/x86/events/amd/ibs.c (ffffffff828a1332)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/events/msr.c (ffffffff8100b8fa)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff828a1dfa)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/events/intel/ds.c (ffffffff8101182e)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81012249)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff81013167)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/events/intel/p4.c (ffffffff828a36c0)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff81014585)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff828a3a7a)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017aa5)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019c4b)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a676)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101d271)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/xen/suspend.c (ffffffff8101e919)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102dced)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f115)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_read
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff8102f892)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff828aa5fe)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff810307e4)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/tsc.c (ffffffff828ae7e1)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff8103cbd9)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
```
```
In arch/x86/kernel/process.c (ffffffff828aec21)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff81043739)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046cac)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff828b05a5)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff810487e2)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff828b0d7d)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049bcb)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/kernel/cpu/tsx.c (ffffffff8104a265)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104a465)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_save
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a604)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bd93)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104bf65)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c285)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ee97)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81050743)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81050cc6)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052cf9)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff828b1b00)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810555b5)
Location: arch/x86/include/asm/paravirt.h:159
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
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828b3131)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810571ab)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810582f0)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828b4132)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105dd89)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b4b27)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065518)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b92fb)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106cbac)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cf00)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d3d0)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read
```
```
In arch/x86/kernel/crash.c (ffffffff810705d9)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81071caf)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81075f25)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8107c6de)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
```
```
In arch/x86/mm/pat.c (ffffffff810855c6)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
```
```
In kernel/kexec_core.c (ffffffff81150c26)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
  - kernel/kexec_core.c:crash_save_cpu
```
```
In arch/x86/lib/msr-smp.c (ffffffff81550f8c)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff815c8f80)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff8162c3ad)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818bd015)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818be61f)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/powernow-k8.c:pending_bit_stuck
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8290e9d0)
Location: arch/x86/include/asm/paravirt.h:159
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
In drivers/clocksource/hyperv_timer.c (ffffffff82913c5f)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
```
```
In arch/x86/pci/amd_bus.c (ffffffff818fa005)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
```
In arch/x86/power/cpu.c (ffffffff818fa484)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
```
```
In arch/x86/lib/insn-eval.c (ffffffff81accc73)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/events/core.c (ffffffff81007eee)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:x86_pmu_disable_all
```
```
In arch/x86/events/amd/core.c (ffffffff81009066)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
```
```
In arch/x86/events/amd/ibs.c (ffffffff828a133b)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/events/msr.c (ffffffff8100bada)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff828a1e0e)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/events/intel/ds.c (ffffffff81011a3e)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/events/intel/knc.c (ffffffff81012469)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_enable_all
  - arch/x86/events/intel/knc.c:knc_pmu_disable_all
```
```
In arch/x86/events/intel/lbr.c (ffffffff81013387)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/events/intel/p4.c (ffffffff828a36d4)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/intel/p6.c (ffffffff810147c5)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_all
  - arch/x86/events/intel/p6.c:p6_pmu_disable_all
```
```
In arch/x86/events/intel/pt.c (ffffffff828a3a8e)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017ce5)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_msr_read_counter
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019e8b)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a8b6)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101d4c1)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/xen/suspend.c (ffffffff8101eb69)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102eadd)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation
  - arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102ff55)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_icr_read
```
```
In arch/x86/hyperv/hv_spinlock.c (ffffffff810306e2)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff828aa60e)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/process_64.c (ffffffff81031674)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/tsc.c (ffffffff828ae80f)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/tsc_msr.c (ffffffff8103dc69)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
  - arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr
```
```
In arch/x86/kernel/process.c (ffffffff828aec4f)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_post_acpi_subsys_init
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff81044b39)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810480ac)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff828b05d3)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81049bf2)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff828b0dab)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104afdb)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/kernel/cpu/tsx.c (ffffffff8104b675)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_enable
  - arch/x86/kernel/cpu/tsx.c:tsx_disable
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104b875)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_save
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104ba14)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8104d1a3)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104d375)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104d695)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810502d7)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81051b83)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81052106)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81054179)
Location: arch/x86/include/asm/paravirt.h:159
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
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff828b1b2e)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81056a35)
Location: arch/x86/include/asm/paravirt.h:159
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
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828b315f)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105864b)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81059790)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828b4160)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105f2a9)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b4b48)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81066af8)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b93fc)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:__x2apic_enable
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106e2ac)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106e620)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f180)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106f650)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read
  - arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read
```
```
In arch/x86/kernel/crash.c (ffffffff810725f3)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81073d2f)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81077f85)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range
```
```
In arch/x86/kernel/mmconf-fam10h_64.c (ffffffff8107e7de)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
```
```
In arch/x86/mm/pat.c (ffffffff81087716)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
```
```
In kernel/kexec_core.c (ffffffff8115da46)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
  - kernel/kexec_core.c:crash_save_cpu
```
```
In arch/x86/lib/msr-smp.c (ffffffff8156adcc)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_on_cpu
```
```
In drivers/idle/intel_idle.c (ffffffff815e2de0)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff8164624d)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818d9305)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msr
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818da92f)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/powernow-k8.c:pending_bit_stuck
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff829153e6)
Location: arch/x86/include/asm/paravirt.h:159
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
In drivers/clocksource/hyperv_timer.c (ffffffff8291a926)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr
```
```
In arch/x86/pci/amd_bus.c (ffffffff8191b165)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_bus_cpu_online
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
```
In arch/x86/power/cpu.c (ffffffff8191b5e4)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
```
```
In arch/x86/lib/insn-eval.c (ffffffff81ad9183)
Location: arch/x86/include/asm/paravirt.h:159
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
</ul>
