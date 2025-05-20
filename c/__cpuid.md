# Function: <code>__cpuid</code>

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
In arch/x86/events/amd/uncore.c (ffffffff81008492)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff81f5d9a4)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/core.c (ffffffff81f5e023)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff81f5fa45)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
```
```
In arch/x86/xen/enlighten.c (ffffffff8101bcad)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_read_msr_safe
  - arch/x86/xen/enlighten.c:xen_start_kernel
```
```
In arch/x86/xen/pmu.c (ffffffff81026670)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/kernel/tsc.c (ffffffff81f691b4)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8107cd49)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103ea30)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8103fe0d)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8103ff3b)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810404a2)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:cpu_detect
  - arch/x86/kernel/cpu/common.c:cpu_detect
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810419bd)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104277a)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff810433ae)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044c0c)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff81f6b290)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d0b0)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e134)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81f6d65a)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81f6d7b8)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8104ffbd)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81050168)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/crash.c (ffffffff8105d62d)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810632e8)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81063d31)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/idle/intel_idle.c (ffffffff81fa0328)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff814ce8e9)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81fa563f)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff814ff8dc)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff816b6f2d)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In arch/x86/pci/xen.c (ffffffff81fb9046)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/events/amd/uncore.c (ffffffff8100874c)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff81f858a3)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/core.c (ffffffff81f85ee6)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff81f879e7)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
```
```
In arch/x86/xen/enlighten.c (ffffffff81f88664)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/enlighten.c:xen_read_msr_safe
```
```
In arch/x86/xen/pmu.c (ffffffff81025b0f)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/kernel/tsc.c (ffffffff81f910c2)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81f91c79)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f8b8)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8103fc6d)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8103fd9b)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810409f5)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810418ed)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81042e8b)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104334e)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044fd1)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff81f935ad)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d0e9)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e2c4)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81f95a14)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81f95b77)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8105012d)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff810504da)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/crash.c (ffffffff8105d736)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81062f5b)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81063ba3)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In drivers/idle/intel_idle.c (ffffffff81fcbb51)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8151f4d9)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8155051f)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81719d02)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff81fe6c1d)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/events/amd/uncore.c (ffffffff8100878c)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff81fc0cdd)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/core.c (ffffffff81fc1325)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff81fc2e61)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
```
```
In arch/x86/xen/enlighten.c (ffffffff81fc3a41)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/enlighten.c:xen_read_msr_safe
```
```
In arch/x86/xen/pmu.c (ffffffff81026241)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/kernel/tsc.c (ffffffff81fcc4b2)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81fccf29)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f308)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8103f73d)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8103f86b)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040439)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104133d)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104296d)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81042e3e)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81082f35)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:rdt_get_config
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046b81)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff81fcebb9)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104f829)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050944)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81fd0dce)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81fd0f31)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810529fd)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81052d4a)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/crash.c (ffffffff810607b3)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81066449)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81067053)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In drivers/idle/intel_idle.c (ffffffff82008b8c)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8154b992)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157cd9f)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8174bac2)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff82025461)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/events/amd/uncore.c (ffffffff8100843c)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff820a0fc3)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/core.c (ffffffff820a16d2)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff820a30dc)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101ba16)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
```
```
In arch/x86/xen/pmu.c (ffffffff8101cb7c)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff820a5d04)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff820a75eb)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff820acc36)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff820ad6a8)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103d23a)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8103d631)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8103d75b)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103e3ce)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8103fd58)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81040a5c)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81040f19)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81041a0c)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046674)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff820af5de)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff820b1285)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104f769)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050844)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff820b1916)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff820b1a6a)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8105251d)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8105285a)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81053133)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8105f833)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8106575a)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81066323)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In drivers/idle/intel_idle.c (ffffffff820e9e7a)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8155fca7)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8159100c)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8176a24d)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff8210894e)
Location: arch/x86/include/asm/paravirt.h:25
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/events/amd/uncore.c (ffffffff810087bb)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a015)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff826a780f)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff826a93c6)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101c706)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
```
```
In arch/x86/xen/pmu.c (ffffffff8101d82c)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826ac3f9)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff826add9b)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff826b34a4)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff826b3f03)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103fdc3)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff810401d1)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff810402fb)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81041a35)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81043360)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81043b66)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81044379)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81044e5c)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104a094)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff81050bc9)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff826b7a97)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053399)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054e04)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff826b8167)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff826b842c)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8105616d)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8105655a)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81056e66)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81063866)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8106992a)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8106a523)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In drivers/idle/intel_idle.c (ffffffff826f2d20)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff815ba78a)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815c3f47)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f4fa5)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817e0618)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff827122a6)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/events/amd/uncore.c (ffffffff81008eec)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a6ee)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff826d09bc)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff826d2553)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff826d3410)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/pmu.c (ffffffff8101e244)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826d5122)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff826d7155)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff826dccab)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff826dd6e1)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104156f)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81041aa0)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff81041bf9)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81043344)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:get_cpu_address_sizes
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_ht_early
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810450ec)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff826deae3)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81045ecb)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81046591)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff826deebe)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init
  - arch/x86/kernel/cpu/intel_rdt.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104c765)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810537e9)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff826e17b1)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056090)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057b29)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff826e1e69)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff826e2113)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8105902e)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8105979b)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81059cd6)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8106651f)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8106c545)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8106d42e)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff8106e8cf)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff8271ccc1)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/xen/grant-table.c (ffffffff815f240a)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815fc5b4)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162ec59)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81828c9b)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff8273c565)
Location: arch/x86/include/asm/paravirt.h:26
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/events/amd/uncore.c (ffffffff81008e0c)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a65e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff82886b3c)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff82888863)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff82889334)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/pmu.c (ffffffff8101dace)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8288b142)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff8288d1ed)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff8288e866)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff828930ee)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff82893b29)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81042c2f)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff810430c0)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff81043219)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810449c4)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:get_cpu_address_sizes
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_ht_early
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81046b00)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff8289518f)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810478ef)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810484c5)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81048811)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81049e55)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81050e69)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff82897773)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053790)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810554c9)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82897f82)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828987a2)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82898a61)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8105ec7e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8105f03b)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8105f956)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8106c52f)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8107238e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810735fe)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810748ef)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff828d4ce1)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/xen/grant-table.c (ffffffff8160d8fa)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81617665)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164c24e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81854d2b)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff828f6580)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/events/amd/uncore.c (ffffffff8100929c)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100aaee)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff8289da2d)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff8289f9dd)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a06b5)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/pmu.c (ffffffff8101f670)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a2584)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a4679)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff828a5e04)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff828aa778)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828ab374)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104513c)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8104541b)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8104566e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046f45)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:get_cpu_address_sizes
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810495f7)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff828acc7e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a658)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b265)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104b5d1)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104b8f1)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cfa5)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81053f39)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828af340)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056930)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810586f9)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828afb5e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828b037e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b0665)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff828b0883)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106206e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81062850)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81062dbe)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8107052f)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81075e9f)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107716e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810784fa)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
```
```
In drivers/idle/intel_idle.c (ffffffff828ef0c4)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/xen/grant-table.c (ffffffff81641385)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8164b311)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8168103a)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818977d0)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff82911fbd)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/events/amd/uncore.c (ffffffff8100969c)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100af0a)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff828a0a9c)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff828a2aaf)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a37a5)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/pmu.c (ffffffff8101ffd0)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a5638)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a7709)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff828a8e0c)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff828ad7e8)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828ae1ad)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104588c)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81045b6b)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff81045dbe)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810476d5)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:get_cpu_address_sizes
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049fe4)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff828afe89)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104aff0)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bc65)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104bf91)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c2b1)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d945)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81054829)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828b2679)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810571e0)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058fc9)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828b2e97)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828b3739)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b3aad)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff828b3cd0)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810629ce)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff810630c0)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8106347e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bacfb)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
```
```
In arch/x86/kernel/crash.c (ffffffff8107152f)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81076e6f)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107776e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff8107954a)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
```
```
In drivers/idle/intel_idle.c (ffffffff828f8258)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/xen/grant-table.c (ffffffff81663d45)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8166d7a1)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a36ea)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818c97e0)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff8291bd56)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
  - arch/x86/pci/xen.c:xen_msi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void __cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff8100ad4a)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100c18a)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff82cc6ce4)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff81017c9b)
Location: arch/x86/include/asm/paravirt.h:94
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff82cc92f6)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8102126a)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/pmu.c (ffffffff81021f6c)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_arch_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810256e8)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff8102af8a)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff82cce777)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff8103f542)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
Direct callers:
  - arch/x86/kernel/tsc.c:detect_art
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104412b)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned
  - arch/x86/kernel/fpu/xstate.c:setup_xstate_features
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810496af)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8104998b)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff81049bb9)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104b435)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_ht_early
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104e50d)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff82cd52ad)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104ee5e)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810503cb)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:hygon_get_topology
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81050a1f)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81050d3f)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81bbe290)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81059904)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff82cd7825)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105c490)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105dcc9)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105f0af)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81067841)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81067b22)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff82cd8d7a)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810688fe)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81068f77)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:emergency_vmx_disable_all
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81069297)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074c1a)
Location: arch/x86/include/asm/paravirt.h:94
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:set_x2apic_bits
  - arch/x86/kernel/apic/x2apic_uv_x.c:set_x2apic_bits
  - arch/x86/kernel/apic/x2apic_uv_x.c:set_x2apic_bits
```
```
In arch/x86/kernel/crash.c (ffffffff81078639)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8107e196)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107eacc)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810807bf)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff8167ea7b)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:sklh_idle_state_table_update
```
```
In drivers/xen/grant-table.c (ffffffff81712f32)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_need_v2
  - drivers/xen/grant-table.c:gnttab_need_v2
  - drivers/xen/grant-table.c:gnttab_need_v2
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171c17c)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xen_strict_xenbus_quirk
  - drivers/xen/xenbus/xenbus_xs.c:xen_strict_xenbus_quirk
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81755c4f)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199c9ee)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff81bb6bd2)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Direct callers:
  - arch/x86/pci/xen.c:xen_msi_init
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff81017c9b-ffffffff81017ca8: __cpuid (STB_LOCAL)
ffffffff8102126a-ffffffff81021277: __cpuid.constprop.0 (STB_LOCAL)
ffffffff810256e8-ffffffff810256f5: __cpuid.constprop.0 (STB_LOCAL)
ffffffff8102af8a-ffffffff8102af97: __cpuid.constprop.0 (STB_LOCAL)
ffffffff8103eb50-ffffffff8103eb5d: __cpuid.constprop.0 (STB_LOCAL)
ffffffff8104412b-ffffffff81044138: __cpuid.constprop.0 (STB_LOCAL)
ffffffff8105e4b0-ffffffff8105e4bd: __cpuid (STB_LOCAL)
ffffffff81067841-ffffffff8106784e: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81067b22-ffffffff81067b2f: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81074c1a-ffffffff81074c27: __cpuid (STB_LOCAL)
ffffffff8167ea7b-ffffffff8167ea88: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81bb6bd2-ffffffff81bb6bdf: __cpuid.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void __cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff81009cda)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff81bd207f)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff82fb2701)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/lbr.c (ffffffff82fb42d1)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/pt.c (ffffffff81bd22ce)
Location: arch/x86/include/asm/paravirt.h:94
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff82fb5147)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff81bd28b1)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/pmu.c (ffffffff8102264c)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_arch_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81bd2bb1)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff81bd2cc2)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff82fba5d3)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff8103f602)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
Direct callers:
  - arch/x86/kernel/tsc.c:detect_art
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810437d8)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:get_xsaves_size
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned
  - arch/x86/kernel/fpu/xstate.c:setup_xstate_features
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048b51)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81048e0b)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff81049039)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104ab05)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_ht_early
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104da4d)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff82fc1265)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104e11e)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104f49b)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:hygon_get_topology
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104fb7f)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104fe9f)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c36bd0)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81bd5bbd)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff82fc37f8)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105ad00)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105c369)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d5ef)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81bd654c)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff82fc4509)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81bd655f)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81bd656c)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff82fc5198)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106a59e)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8106abc8)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:emergency_vmx_disable_all
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8106aeb7)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81bd75ae)
Location: arch/x86/include/asm/paravirt.h:94
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:set_x2apic_bits
  - arch/x86/kernel/apic/x2apic_uv_x.c:set_x2apic_bits
  - arch/x86/kernel/apic/x2apic_uv_x.c:set_x2apic_bits
```
```
In arch/x86/kernel/crash.c (ffffffff8107863e)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8107de56)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e6fc)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810803d6)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81c005cf)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:sklh_idle_state_table_update
```
```
In drivers/xen/grant-table.c (ffffffff8172fd32)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_need_v2
  - drivers/xen/grant-table.c:gnttab_need_v2
  - drivers/xen/grant-table.c:gnttab_need_v2
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8173912c)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xen_strict_xenbus_quirk
  - drivers/xen/xenbus/xenbus_xs.c:xen_strict_xenbus_quirk
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81770ebf)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199fa7e)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff81c34283)
Location: arch/x86/include/asm/paravirt.h:94
Inline: True
Direct callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
  - arch/x86/pci/xen.c:xen_hvm_msi_init
```
**Symbols:**

```
ffffffff81bd22ce-ffffffff81bd22db: __cpuid (STB_LOCAL)
ffffffff81bd28b1-ffffffff81bd28be: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81bd2bb1-ffffffff81bd2bbe: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81bd2cc2-ffffffff81bd2ccf: __cpuid.constprop.0 (STB_LOCAL)
ffffffff8103ec00-ffffffff8103ec0d: __cpuid.constprop.0 (STB_LOCAL)
ffffffff810434e0-ffffffff810434ed: __cpuid.constprop.0 (STB_LOCAL)
ffffffff8105c9f0-ffffffff8105c9fd: __cpuid (STB_LOCAL)
ffffffff81bd654c-ffffffff81bd6559: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81bd655f-ffffffff81bd656c: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81bd656c-ffffffff81bd6579: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81bd75ae-ffffffff81bd75bb: __cpuid (STB_LOCAL)
ffffffff81c005cf-ffffffff81c005dc: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81c34283-ffffffff81c34290: __cpuid.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void __cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff8100a6bc)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff81bc410f)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff831bc851)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/lbr.c (ffffffff831be848)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/pt.c (ffffffff81bc45c2)
Location: arch/x86/include/asm/paravirt.h:107
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff831bf8ca)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff81bc4a4f)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/pmu.c (ffffffff8102506b)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81bc4d49)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff81bc5011)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff831c4b58)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/hyperv/hv_init.c (ffffffff831c5041)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tsc.c (ffffffff831c9070)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81045028)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:get_xsaves_size
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104a421)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8104a6db)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8104a909)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104c3e5)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:generic_identify
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_ht_early
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104f7b7)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff831cb950)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81050afa)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81051217)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8105172f)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81051903)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c29080)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81bc7f71)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff831cddda)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105b6b0)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105cc79)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105df1f)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81bc87fe)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff831cec77)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81bc8811)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81bc881e)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff831cfaba)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106b05e)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8106b838)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8106bca7)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81bc974c)
Location: arch/x86/include/asm/paravirt.h:107
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
```
```
In arch/x86/kernel/crash.c (ffffffff810794fe)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8107ef76)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f76c)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81081276)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81bf20ba)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/xen/grant-table.c (ffffffff81713dcb)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171e4b5)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8175497f)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff819844be)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff81c265f9)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Direct callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
  - arch/x86/pci/xen.c:xen_hvm_msi_init
```
**Symbols:**

```
ffffffff81bc45c2-ffffffff81bc45cf: __cpuid (STB_LOCAL)
ffffffff81bc4a4f-ffffffff81bc4a5c: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81bc4d49-ffffffff81bc4d56: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81bc5011-ffffffff81bc501e: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81044de0-ffffffff81044ded: __cpuid.constprop.0 (STB_LOCAL)
ffffffff8105d350-ffffffff8105d35d: __cpuid (STB_LOCAL)
ffffffff81bc87fe-ffffffff81bc880b: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81bc8811-ffffffff81bc881e: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81bc881e-ffffffff81bc882b: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81bc974c-ffffffff81bc9759: __cpuid (STB_LOCAL)
ffffffff81bf20ba-ffffffff81bf20c7: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81c265f9-ffffffff81c26606: __cpuid.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void __cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81c954e2)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff8329cbd9)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/lbr.c (ffffffff8329eca6)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/pt.c (ffffffff81c963ba)
Location: arch/x86/include/asm/paravirt.h:107
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8329fe60)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff81c970e4)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/pmu.c (ffffffff81029526)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81c97525)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff81c97b04)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff832a57b2)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/hyperv/hv_init.c (ffffffff832a5d71)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tsc.c (ffffffff832aa331)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104b5c8)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:get_xsaves_size
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81050fa1)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff810515dd)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff81051829)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81053695)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_ht_early
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81057997)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff832ad152)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81058e31)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810596de)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81059cbf)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81059e93)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81d47816)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81c9bc83)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff832aff3d)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81064ca2)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8106631a)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810676bf)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81c9cddd)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff832b0f2e)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81c9cf41)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c9d00e)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff832b1f49)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81075ad2)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81076335)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81076787)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81c9e2be)
Location: arch/x86/include/asm/paravirt.h:107
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
```
```
In arch/x86/kernel/crash.c (ffffffff8108755e)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/hpet.c (ffffffff832bd69d)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8108dc06)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e52c)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81090226)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81cee9f8)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/xen/grant-table.c (ffffffff817907fb)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8179d265)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d803f)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81a2db28)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff81d443ec)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Direct callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
  - arch/x86/pci/xen.c:xen_hvm_msi_init
```
**Symbols:**

```
ffffffff81c963ba-ffffffff81c963c7: __cpuid (STB_LOCAL)
ffffffff81c970e4-ffffffff81c970f1: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81c97525-ffffffff81c97532: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81c97b04-ffffffff81c97b11: __cpuid.constprop.0 (STB_LOCAL)
ffffffff8104b1b0-ffffffff8104b1bd: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81066a50-ffffffff81066a5d: __cpuid (STB_LOCAL)
ffffffff81c9cddd-ffffffff81c9cdea: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81c9cf41-ffffffff81c9cf4e: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81c9d00e-ffffffff81c9d01b: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81c9e2be-ffffffff81c9e2cb: __cpuid (STB_LOCAL)
ffffffff81cee9f8-ffffffff81ceea05: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81d443ec-ffffffff81d443f9: __cpuid.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void __cpuid(unsigned int *eax, unsigned int *ebx, unsigned int *ecx, unsigned int *edx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff83449ec9)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_early_init
```
```
In arch/x86/events/amd/core.c (ffffffff8344a936)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_core_pmu_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff81e44805)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff8344b6ba)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/lbr.c (ffffffff8344d9e2)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/pt.c (ffffffff81e45681)
Location: arch/x86/include/asm/paravirt.h:113
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8344ecbe)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff81e464f7)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:cpuid_eax
```
```
In arch/x86/xen/pmu.c (ffffffff8102de91)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81e46973)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff81e46eb2)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff834547f1)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83454e66)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tsc.c (ffffffff83459b0b)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/process.c (ffffffff81051d95)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81056156)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:get_compacted_size
  - arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct
  - arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct
  - arch/x86/kernel/fpu/xstate.c:__xstate_dump_leaves
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8105c4d7)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8105cbc4)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8105cec2)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105e37b)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
  - arch/x86/kernel/cpu/common.c:get_cpu_address_sizes
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_ht_early
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81063c9d)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff8345dfa7)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81064926)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd
  - arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd
  - arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd
  - arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8106602a)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon
  - arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon
  - arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8106644c)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81066681)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810688e9)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81e4b0e5)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff83460fac)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81071690)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810730a0)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810743f7)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81e4c13c)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff834620ac)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81e4c2e6)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81e4c3b8)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff83463242)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81084840)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81085088)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8108537c)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81e4d767)
Location: arch/x86/include/asm/paravirt.h:113
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
```
```
In arch/x86/kernel/crash.c (ffffffff810976b8)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/hpet.c (ffffffff8346f093)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81e4e6d1)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8109f3c2)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810a1135)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81eb610a)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/xen/grant-table.c (ffffffff818c8aa7)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff818d6940)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff819162ab)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81b52a61)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81b994a9)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff81f11273)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Direct callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
  - arch/x86/pci/xen.c:xen_hvm_msi_init
```
**Symbols:**

```
ffffffff81e45681-ffffffff81e456a7: __cpuid (STB_LOCAL)
ffffffff81e464f7-ffffffff81e4651d: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81e46973-ffffffff81e46999: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81e46eb2-ffffffff81e46ed8: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81055350-ffffffff81055376: __cpuid (STB_LOCAL)
ffffffff81073620-ffffffff81073646: __cpuid (STB_LOCAL)
ffffffff81e4c13c-ffffffff81e4c162: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81e4c2e6-ffffffff81e4c30c: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81e4c3b8-ffffffff81e4c3de: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81e4d767-ffffffff81e4d78d: __cpuid (STB_LOCAL)
ffffffff81eb610a-ffffffff81eb6130: __cpuid.constprop.0 (STB_LOCAL)
ffffffff81f11273-ffffffff81f11299: __cpuid.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff83e64403)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_early_init
```
```
In arch/x86/events/amd/core.c (ffffffff83e65260)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_core_pmu_init
```
```
In arch/x86/events/amd/lbr.c (ffffffff83e65643)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff83e65a64)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/core.c (ffffffff83e664cb)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/lbr.c (ffffffff83e68e1c)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/pt.c (ffffffff83e69711)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff83e6a560)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff83e6b92b)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id
  - arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/pmu.c (ffffffff81035261)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83e6e99e)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff83e714ac)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff83e722ca)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83e72a2a)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tsc.c (ffffffff83e79636)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/process.c (ffffffff8105f5c8)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:select_idle_routine
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff83e7ad3c)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct
  - arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct
  - arch/x86/kernel/fpu/xstate.c:__xstate_dump_leaves
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106a4d7)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8106af44)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8106b275)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106c941)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
  - arch/x86/kernel/cpu/common.c:get_cpu_address_sizes
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_ht_early
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81072dfd)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff83e7efbe)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81073ba6)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd
  - arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd
  - arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd
  - arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107537a)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon
  - arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon
  - arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8107576c)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81075961)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810783a9)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff83e7fc91)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff83e82e30)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81081f50)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810830f4)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81084627)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff83e84101)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff83e8428f)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff83e84e83)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff83e852ab)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff83e85c74)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
  - arch/x86/kernel/cpu/acrn.c:acrn_get_tsc_khz
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81097740)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81097e8d)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e9100f)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
```
```
In arch/x86/kernel/hpet.c (ffffffff83e952a2)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_is_pc10_damaged
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810b5a82)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810b6a22)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810b9045)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff83edeed5)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/xen/grant-table.c (ffffffff81a1988e)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/events/events_base.c (ffffffff83eea8dc)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a28eac)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a719dd)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff83efebf8)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_parse_features
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81d3a3cc)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff83f15019)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
  - arch/x86/pci/xen.c:xen_hvm_msi_init
```
**Symbols:**

```
ffffffff8105e110-ffffffff8105e136: __cpuid.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff83684a33)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_early_init
```
```
In arch/x86/events/amd/core.c (ffffffff836858e0)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_core_pmu_init
```
```
In arch/x86/events/amd/lbr.c (ffffffff83685cc3)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff836860e4)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/core.c (ffffffff83686b3b)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:init_hybrid_pmu
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/events/intel/lbr.c (ffffffff836897bc)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/pt.c (ffffffff8368a0a1)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8368aef0)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init
```
```
In arch/x86/xen/time.c (ffffffff8368b718)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8368c3cb)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id
  - arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/pmu.c (ffffffff810351e1)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8368f31e)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data
  - arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff83692306)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff836931da)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8369394a)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tsc.c (ffffffff8369bc41)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/process.c (ffffffff81060d21)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:select_idle_routine
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8369d39c)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct
  - arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct
  - arch/x86/kernel/fpu/xstate.c:__xstate_dump_leaves
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106baf5)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8106c8b4)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8106cbf5)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106e31d)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:get_cpu_address_sizes
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_ht_early
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810749dd)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff836a1d0e)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81075a56)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd
  - arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd
  - arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd
  - arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810774ea)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon
  - arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon
  - arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff810778dc)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81077ad1)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107a659)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff836a61b5)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81084490)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81084f34)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81086bd7)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
  - arch/x86/kernel/cpu/resctrl/core.c:__rdt_get_mem_config_amd
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff836a7651)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff836a77df)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff836a83c3)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff836a87eb)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff836a91b4)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
  - arch/x86/kernel/cpu/acrn.c:acrn_get_tsc_khz
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8109a800)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8109af2d)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b49df)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
```
```
In arch/x86/kernel/hpet.c (ffffffff836b8e02)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_is_pc10_damaged
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810b8b78)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810b9b62)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810bc215)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff83704955)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/xen/grant-table.c (ffffffff81a6290e)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/events/events_base.c (ffffffff837102cc)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a725ac)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abc28d)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff83724a68)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_parse_features
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81da4e5c)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff8373b799)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
  - arch/x86/pci/xen.c:xen_hvm_msi_init
```
**Symbols:**

```
ffffffff8105f7c0-ffffffff8105f7e6: __cpuid.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff838b3c38)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_early_init
```
```
In arch/x86/events/amd/core.c (ffffffff838b4a70)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_core_pmu_init
```
```
In arch/x86/events/amd/lbr.c (ffffffff838b4e53)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff838b5274)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/core.c (ffffffff838b5d4b)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:init_hybrid_pmu
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/events/intel/lbr.c (ffffffff838b92ec)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/pt.c (ffffffff838b9c5f)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff838baab0)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init
```
```
In arch/x86/xen/time.c (ffffffff838bb2d8)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff838bbf8b)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id
  - arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/pmu.c (ffffffff8103b3e1)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff838bf17e)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data
  - arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff838c1e16)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff838c2d4a)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/hyperv/hv_init.c (ffffffff838c332d)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tsc.c (ffffffff838cb718)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:detect_art
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/process.c (ffffffff81067dcd)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:select_idle_routine
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff838ccf5c)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct
  - arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct
  - arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct
  - arch/x86/kernel/fpu/xstate.c:__xstate_dump_leaves
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81072f69)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81073b04)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff81073e15)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810755e6)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:get_cpu_address_sizes
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_ht_early
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8107bead)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff838d1e0e)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107ce66)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd
  - arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd
  - arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd
  - arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107ea6a)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon
  - arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon
  - arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8107ee5c)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8107efb1)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81081b89)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8108b920)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:intel_collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c1c4)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108daf7)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff838d7b91)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff838d7d1f)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff838d8903)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff838d8dab)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff838d9814)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
  - arch/x86/kernel/cpu/acrn.c:acrn_get_tsc_khz
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810a2030)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e536f)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
```
```
In arch/x86/kernel/hpet.c (ffffffff838e9716)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:mwait_pc10_supported
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810bffb8)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810c1202)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810c3395)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff83937e65)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/xen/grant-table.c (ffffffff81ab586e)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/events/events_base.c (ffffffff83943c4c)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81ac470c)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0efdd)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff839588d8)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_parse_features
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5cdec)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff83970124)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
  - arch/x86/pci/xen.c:xen_hvm_msi_init
```
**Symbols:**

```
ffffffff81066920-ffffffff81066946: __cpuid.constprop.0 (STB_LOCAL)
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
In arch/x86/events/amd/uncore.c (ffffffff8100969c)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100af0a)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff8288ea9c)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff82890aaf)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828917c6)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/pmu.c (ffffffff81020130)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82893641)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff82895719)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff82896e1c)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff8289b807)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8289c1cc)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045a0c)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81045ceb)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff81045f3e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047845)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:get_cpu_address_sizes
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104a154)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff8289dea8)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b160)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bdd5)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104c101)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c421)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104daa5)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810543a9)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828a0698)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056d60)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058b49)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828a0eb6)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828a1758)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828a1acc)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff828a1cef)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810624be)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81062bb0)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81062f6e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8107052f)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81075e6f)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107676e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff8107854a)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
```
```
In drivers/idle/intel_idle.c (ffffffff828e0fc4)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/xen/grant-table.c (ffffffff81629bb5)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81633611)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8166914a)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8186df00)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff82900a5a)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/events/amd/uncore.c (ffffffff8100965c)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100aeca)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff828a1a9c)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff828a3aaf)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a47a5)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/pmu.c (ffffffff8101ff90)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a6638)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a8709)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff828a9e0c)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff828ae7ca)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828af18f)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104584c)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81045b2b)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff81045d7e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047685)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:get_cpu_address_sizes
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049f94)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff828b0e6b)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104afa0)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bc15)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104bf41)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c261)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d8f5)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810547d9)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828b365b)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057190)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058f79)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828b3e79)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828b471b)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b4a8f)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106296e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81063060)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8106341e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8107052f)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81075e1f)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107671e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810784fa)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
```
```
In drivers/idle/intel_idle.c (ffffffff828f3e54)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/xen/grant-table.c (ffffffff81657b85)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff816615e1)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8169752a)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818bec90)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff82916061)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/events/amd/uncore.c (ffffffff810097bc)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100b08e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff828a1ab0)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff828a3ac3)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a4779)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/pmu.c (ffffffff810201e0)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a660c)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a8719)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff828a9e1c)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff828ae7f8)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828af1bd)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81046c4c)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81046f2b)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8104717e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81048a95)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:get_cpu_address_sizes
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104b3a4)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff828b0e99)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104c3b0)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104d025)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104d351)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104d671)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ed35)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81055c59)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828b3689)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81058630)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105a419)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828b3ea7)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828b473c)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b4ab0)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff828b4cd3)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81063f2e)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81064620)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff810649de)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bbd28)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
```
```
In arch/x86/kernel/crash.c (ffffffff81072549)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81077e7f)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810788ee)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff8107a5fa)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
```
```
In drivers/idle/intel_idle.c (ffffffff828f92ac)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/xen/grant-table.c (ffffffff81672185)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8167bbb1)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b1bea)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818dafa0)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff8291cdb8)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
  - arch/x86/pci/xen.c:xen_msi_init
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
