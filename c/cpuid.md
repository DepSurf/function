# Function: <code>cpuid</code>

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
Location: arch/x86/include/asm/processor.h:502
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff81f5d9a4)
Location: arch/x86/include/asm/processor.h:502
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/core.c (ffffffff81f5e015)
Location: arch/x86/include/asm/processor.h:502
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/xen/enlighten.c (ffffffff8101bc9f)
Location: arch/x86/include/asm/processor.h:502
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_read_msr_safe
  - arch/x86/xen/enlighten.c:xen_start_kernel
```
```
In arch/x86/xen/pmu.c (ffffffff81026662)
Location: arch/x86/include/asm/processor.h:502
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/kernel/tsc.c (ffffffff81f691b4)
Location: arch/x86/include/asm/processor.h:502
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103ef8a)
Location: arch/x86/include/asm/processor.h:502
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8103fe66)
Location: arch/x86/include/asm/processor.h:502
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810404a2)
Location: arch/x86/include/asm/processor.h:502
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
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810419af)
Location: arch/x86/include/asm/processor.h:502
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104276c)
Location: arch/x86/include/asm/processor.h:502
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
Location: arch/x86/include/asm/processor.h:502
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044bfe)
Location: arch/x86/include/asm/processor.h:502
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff81f6b290)
Location: arch/x86/include/asm/processor.h:502
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d0b0)
Location: arch/x86/include/asm/processor.h:502
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e134)
Location: arch/x86/include/asm/processor.h:502
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81f6d65a)
Location: arch/x86/include/asm/processor.h:502
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81f6d7b8)
Location: arch/x86/include/asm/processor.h:502
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8104ffbd)
Location: arch/x86/include/asm/processor.h:502
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81050168)
Location: arch/x86/include/asm/processor.h:502
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/crash.c (ffffffff8105d62d)
Location: arch/x86/include/asm/processor.h:502
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
In arch/x86/kernel/amd_nb.c (ffffffff810632da)
Location: arch/x86/include/asm/processor.h:502
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81063d27)
Location: arch/x86/include/asm/processor.h:502
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/idle/intel_idle.c (ffffffff81fa0328)
Location: arch/x86/include/asm/processor.h:502
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff814ce8de)
Location: arch/x86/include/asm/processor.h:502
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81fa5631)
Location: arch/x86/include/asm/processor.h:502
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff814ff8d1)
Location: arch/x86/include/asm/processor.h:502
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff816b6f2d)
Location: arch/x86/include/asm/processor.h:502
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In arch/x86/pci/xen.c (ffffffff81fb9046)
Location: arch/x86/include/asm/processor.h:502
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
In arch/x86/events/amd/uncore.c (ffffffff810086d2)
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff81f858a3)
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/core.c (ffffffff81f85ed8)
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff81f879d9)
Location: arch/x86/include/asm/processor.h:513
Inline: True
```
```
In arch/x86/xen/enlighten.c (ffffffff81f88664)
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/enlighten.c:xen_read_msr_safe
```
```
In arch/x86/xen/pmu.c (ffffffff81025b01)
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/kernel/tsc.c (ffffffff81f910c2)
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f8aa)
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8103fcc9)
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810409e7)
Location: arch/x86/include/asm/processor.h:513
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
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810418df)
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81042e7d)
Location: arch/x86/include/asm/processor.h:513
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
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044fd1)
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff81f935ad)
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d0e9)
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e2c4)
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81f95a14)
Location: arch/x86/include/asm/processor.h:513
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81f95b77)
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8105012d)
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff810504cc)
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/crash.c (ffffffff8105d728)
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81062f4d)
Location: arch/x86/include/asm/processor.h:513
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81063b9c)
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In drivers/idle/intel_idle.c (ffffffff81fcbb51)
Location: arch/x86/include/asm/processor.h:513
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8151f4ce)
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81550514)
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81719cf4)
Location: arch/x86/include/asm/processor.h:513
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff81fe6c1d)
Location: arch/x86/include/asm/processor.h:513
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
In arch/x86/events/amd/uncore.c (ffffffff81008712)
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff81fc0cdd)
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/core.c (ffffffff81fc1317)
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff81fc2e53)
Location: arch/x86/include/asm/processor.h:555
Inline: True
```
```
In arch/x86/xen/enlighten.c (ffffffff81fc3a41)
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/enlighten.c:xen_read_msr_safe
```
```
In arch/x86/xen/pmu.c (ffffffff81026233)
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/kernel/tsc.c (ffffffff81fcc4b2)
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f2fa)
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8103f799)
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104042b)
Location: arch/x86/include/asm/processor.h:555
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
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104132f)
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104295f)
Location: arch/x86/include/asm/processor.h:555
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
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046b81)
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff81fcebb9)
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104f829)
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050944)
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81fd0dce)
Location: arch/x86/include/asm/processor.h:555
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81fd0f31)
Location: arch/x86/include/asm/processor.h:555
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
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81052d3c)
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/crash.c (ffffffff810607a5)
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8106643b)
Location: arch/x86/include/asm/processor.h:555
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8106704c)
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In drivers/idle/intel_idle.c (ffffffff82008b8c)
Location: arch/x86/include/asm/processor.h:555
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8154b987)
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157cd94)
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8174bab4)
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff82025461)
Location: arch/x86/include/asm/processor.h:555
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
In arch/x86/events/amd/uncore.c (ffffffff810083c2)
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff820a0fc3)
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/core.c (ffffffff820a16c4)
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff820a30ce)
Location: arch/x86/include/asm/processor.h:566
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101ba16)
Location: arch/x86/include/asm/processor.h:566
Inline: True
```
```
In arch/x86/xen/pmu.c (ffffffff8101cb6e)
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff820a5d04)
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff820a75eb)
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff820acc36)
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103d22c)
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8103d688)
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103e3c0)
Location: arch/x86/include/asm/processor.h:566
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
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8103fd4a)
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81040a4e)
Location: arch/x86/include/asm/processor.h:566
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
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046674)
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff820af5de)
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff820b1277)
Location: arch/x86/include/asm/processor.h:566
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104f769)
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050844)
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff820b1916)
Location: arch/x86/include/asm/processor.h:566
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff820b1a6a)
Location: arch/x86/include/asm/processor.h:566
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
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8105284c)
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81053125)
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8105f825)
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8106574c)
Location: arch/x86/include/asm/processor.h:566
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8106631c)
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In drivers/idle/intel_idle.c (ffffffff820e9e7a)
Location: arch/x86/include/asm/processor.h:566
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8155fc9c)
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81591001)
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8176a23f)
Location: arch/x86/include/asm/processor.h:566
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff8210894e)
Location: arch/x86/include/asm/processor.h:566
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
In arch/x86/events/amd/uncore.c (ffffffff81008716)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a015)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff826a7801)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff826a93b8)
Location: arch/x86/include/asm/processor.h:588
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101c706)
Location: arch/x86/include/asm/processor.h:588
Inline: True
```
```
In arch/x86/xen/pmu.c (ffffffff8101d81e)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826ac3f9)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff826add9b)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff826b34a4)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103fdb5)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81040228)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81041a35)
Location: arch/x86/include/asm/processor.h:588
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
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81043352)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81043b66)
Location: arch/x86/include/asm/processor.h:588
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
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104a094)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff81050bc9)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff826b7a89)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053399)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054e04)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff826b8167)
Location: arch/x86/include/asm/processor.h:588
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff826b841c)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8105616d)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8105655a)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81056e58)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81063858)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8106991c)
Location: arch/x86/include/asm/processor.h:588
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8106a51c)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In drivers/idle/intel_idle.c (ffffffff826f2d20)
Location: arch/x86/include/asm/processor.h:588
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff815ba77f)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815c3f3c)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f4f9a)
Location: arch/x86/include/asm/processor.h:588
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817e060a)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff827122a6)
Location: arch/x86/include/asm/processor.h:588
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
In arch/x86/events/amd/uncore.c (ffffffff81008eda)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a6dc)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff826d09a2)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff826d253d)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff826d33ff)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/pmu.c (ffffffff8101e22e)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826d510f)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff826d7141)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff826dcc88)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81041559)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81041a55)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81043318)
Location: arch/x86/include/asm/processor.h:604
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
  - arch/x86/kernel/cpu/common.c:detect_ht_early
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810450d6)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81045eb2)
Location: arch/x86/include/asm/processor.h:604
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
In arch/x86/kernel/cpu/centaur.c (ffffffff8104657b)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104c765)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810537d7)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff826e179b)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105607e)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057b1b)
Location: arch/x86/include/asm/processor.h:604
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff826e1e53)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff826e210c)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81059020)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81059785)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81059ccf)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81066509)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8106c52f)
Location: arch/x86/include/asm/processor.h:604
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8106d417)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff8106e8ba)
Location: arch/x86/include/asm/processor.h:604
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff8271cca0)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/xen/grant-table.c (ffffffff815f23f5)
Location: arch/x86/include/asm/processor.h:604
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815fc5a1)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162ec43)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81828c85)
Location: arch/x86/include/asm/processor.h:604
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff8273c552)
Location: arch/x86/include/asm/processor.h:604
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
In arch/x86/events/amd/uncore.c (ffffffff81008dfa)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a64c)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff82886b22)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff8288884d)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff82889323)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/pmu.c (ffffffff8101dab8)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8288b12f)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff8288d1da)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff8288e853)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff828930cc)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81042c19)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81043075)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81044998)
Location: arch/x86/include/asm/processor.h:599
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
  - arch/x86/kernel/cpu/common.c:detect_ht_early
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81046aea)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810478d6)
Location: arch/x86/include/asm/processor.h:599
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
In arch/x86/kernel/cpu/hygon.c (ffffffff810484af)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff810487fb)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81049e55)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81050e57)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8289775d)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105377e)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810554bb)
Location: arch/x86/include/asm/processor.h:599
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff8289878c)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82898a5a)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8105ec70)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8105f02d)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8105f94f)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8106c519)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81072378)
Location: arch/x86/include/asm/processor.h:599
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810735e7)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810748da)
Location: arch/x86/include/asm/processor.h:599
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff828d4cc0)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/xen/grant-table.c (ffffffff8160d8e5)
Location: arch/x86/include/asm/processor.h:599
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81617651)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164c23a)
Location: arch/x86/include/asm/processor.h:599
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81854d15)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff828f656d)
Location: arch/x86/include/asm/processor.h:599
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
In arch/x86/events/amd/uncore.c (ffffffff8100928a)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100aadc)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff8289da13)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff8289f9c7)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a06a4)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/pmu.c (ffffffff8101f65a)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a2570)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a4666)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff828a5df1)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff828aa758)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045126)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81045408)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046f19)
Location: arch/x86/include/asm/processor.h:589
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
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810495e1)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a63f)
Location: arch/x86/include/asm/processor.h:589
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b24f)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104b5bb)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104b8db)
Location: arch/x86/include/asm/processor.h:589
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
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81053f27)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828af32a)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105691e)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810586eb)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828b0368)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b065e)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff828b086f)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81062060)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8106283a)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81062dbe)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81070519)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81075e89)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81077157)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810784e6)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
```
```
In drivers/idle/intel_idle.c (ffffffff828ef0a7)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/xen/grant-table.c (ffffffff81641370)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8164b2fd)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81681025)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818977ba)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff82911faa)
Location: arch/x86/include/asm/processor.h:589
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
In arch/x86/events/amd/uncore.c (ffffffff8100968a)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100aef8)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff828a0a82)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff828a2a99)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a3794)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/pmu.c (ffffffff8101ffba)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a5624)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a76f6)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff828a8df9)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff828ad7c8)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045876)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81045b58)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810476a9)
Location: arch/x86/include/asm/processor.h:589
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
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049fce)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104afda)
Location: arch/x86/include/asm/processor.h:589
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bc4f)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104bf7b)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c29b)
Location: arch/x86/include/asm/processor.h:589
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
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81054817)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828b2663)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810571ce)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058fbb)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828b3723)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b3aa6)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff828b3cbc)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810629c0)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff810630aa)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8106347e)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bace5)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
```
```
In arch/x86/kernel/crash.c (ffffffff81071519)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81076e59)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81077757)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81079536)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
```
```
In drivers/idle/intel_idle.c (ffffffff828f823b)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/xen/grant-table.c (ffffffff81663d30)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8166d78d)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a36d5)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818c97ca)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff8291bd43)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
  - arch/x86/pci/xen.c:xen_msi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff8100ad38)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100c178)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff82cc6cce)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff82cc8a7a)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff82cc92e0)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff82cc9ac6)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/pmu.c (ffffffff81021f56)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_arch_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82ccbac5)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff82ccdad4)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff82cce764)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff82cd2845)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:detect_art
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81049699)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81049978)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104b409)
Location: arch/x86/include/asm/processor.h:623
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
  - arch/x86/kernel/cpu/common.c:detect_ht_early
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104e4f7)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104ee50)
Location: arch/x86/include/asm/processor.h:623
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
In arch/x86/kernel/cpu/hygon.c (ffffffff810503b2)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:hygon_get_topology
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81050a09)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81050d29)
Location: arch/x86/include/asm/processor.h:623
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
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810598f2)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff82cd780f)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105c47e)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105dcbb)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105f048)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff82cd8783)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82cd8b1f)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff82cd8d66)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810688f0)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81068f61)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:emergency_vmx_disable_all
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81069281)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074c74)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:set_x2apic_bits
```
```
In arch/x86/kernel/crash.c (ffffffff81078623)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8107e180)
Location: arch/x86/include/asm/processor.h:623
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107eab5)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810807ab)
Location: arch/x86/include/asm/processor.h:623
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff82d0f258)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:sklh_idle_state_table_update
```
```
In drivers/xen/grant-table.c (ffffffff81712f1d)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_need_v2
  - drivers/xen/grant-table.c:gnttab_need_v2
  - drivers/xen/grant-table.c:gnttab_need_v2
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171c167)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xen_strict_xenbus_quirk
  - drivers/xen/xenbus/xenbus_xs.c:xen_strict_xenbus_quirk
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81755c3a)
Location: arch/x86/include/asm/processor.h:623
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199c9d8)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff82d31aa9)
Location: arch/x86/include/asm/processor.h:623
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
  - arch/x86/pci/xen.c:xen_msi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff81009cc8)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff81bd206d)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff82fb26eb)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/lbr.c (ffffffff82fb42d1)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/pt.c (ffffffff82fb4891)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff82fb5131)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff82fb592b)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/pmu.c (ffffffff81022636)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_arch_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82fb7933)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff82fb9904)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff82fba5c0)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff82fbe68c)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:detect_art
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048b3b)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81048df8)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104aad9)
Location: arch/x86/include/asm/processor.h:606
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
  - arch/x86/kernel/cpu/common.c:detect_ht_early
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104da37)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104e110)
Location: arch/x86/include/asm/processor.h:606
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8104f482)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:hygon_get_topology
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104fb69)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104fe89)
Location: arch/x86/include/asm/processor.h:606
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
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81bd5bab)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff82fc37e2)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105acee)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105c35b)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d588)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff82fc4b55)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82fc4f3d)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff82fc5184)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106a590)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8106abb2)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:emergency_vmx_disable_all
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8106aea1)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81bd7675)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:set_x2apic_bits
```
```
In arch/x86/kernel/crash.c (ffffffff81078628)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8107de40)
Location: arch/x86/include/asm/processor.h:606
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e6e5)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810803c1)
Location: arch/x86/include/asm/processor.h:606
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff82ffcce9)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:sklh_idle_state_table_update
```
```
In drivers/xen/grant-table.c (ffffffff8172fd1d)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_need_v2
  - drivers/xen/grant-table.c:gnttab_need_v2
  - drivers/xen/grant-table.c:gnttab_need_v2
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81739117)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xen_strict_xenbus_quirk
  - drivers/xen/xenbus/xenbus_xs.c:xen_strict_xenbus_quirk
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81770eaa)
Location: arch/x86/include/asm/processor.h:606
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199fa68)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff83020ae4)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
  - arch/x86/pci/xen.c:xen_hvm_msi_init
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
In arch/x86/events/amd/uncore.c (ffffffff8100a6aa)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff81bc40fd)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff831bc83b)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/lbr.c (ffffffff831be848)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/pt.c (ffffffff831bee05)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff831bf8b4)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff831c0136)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/pmu.c (ffffffff81025055)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff831c1ec9)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff831c3fc4)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff831c4b45)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/hyperv/hv_init.c (ffffffff831c5023)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tsc.c (ffffffff831c9050)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104a40b)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8104a6c8)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104c3b9)
Location: arch/x86/include/asm/processor.h:588
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
  - arch/x86/kernel/cpu/common.c:detect_ht_early
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104f7a1)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81050ae4)
Location: arch/x86/include/asm/processor.h:588
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
In arch/x86/kernel/cpu/hygon.c (ffffffff81051201)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81051719)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff810518ed)
Location: arch/x86/include/asm/processor.h:588
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
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81bc7f5f)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff831cddc4)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105b69e)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105cc6b)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105deb8)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff831cf338)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff831cf800)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff831cfaa6)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106b050)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8106b822)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8106bc91)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d7bc9)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
```
```
In arch/x86/kernel/crash.c (ffffffff810794e8)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8107ef60)
Location: arch/x86/include/asm/processor.h:588
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f755)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81081261)
Location: arch/x86/include/asm/processor.h:588
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff83207b0b)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/xen/grant-table.c (ffffffff81713db5)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171e4a0)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8175496a)
Location: arch/x86/include/asm/processor.h:588
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff819844a8)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff8322bcb2)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
  - arch/x86/pci/xen.c:xen_hvm_msi_init
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
In arch/x86/events/amd/ibs.c (ffffffff81c954d0)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff8329cbc3)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/lbr.c (ffffffff8329eca6)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/pt.c (ffffffff8329f274)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8329fe4a)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff832a0904)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/pmu.c (ffffffff81029510)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff832a2917)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff832a4b24)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff832a579e)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/hyperv/hv_init.c (ffffffff832a5d53)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tsc.c (ffffffff832aa311)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81050f8b)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff810515ca)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81053669)
Location: arch/x86/include/asm/processor.h:600
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
  - arch/x86/kernel/cpu/common.c:detect_ht_early
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81057981)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81058e1b)
Location: arch/x86/include/asm/processor.h:600
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
In arch/x86/kernel/cpu/hygon.c (ffffffff810596c8)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81059ca9)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81059e7d)
Location: arch/x86/include/asm/processor.h:600
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
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81c9bc71)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff832aff27)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81064c9b)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8106630b)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81067658)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff832b16f0)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff832b1c72)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff832b1f35)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81075ac4)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8107631f)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81076771)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832baa8e)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
```
```
In arch/x86/kernel/crash.c (ffffffff81087548)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/hpet.c (ffffffff832bd687)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8108dbf0)
Location: arch/x86/include/asm/processor.h:600
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e515)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81090211)
Location: arch/x86/include/asm/processor.h:600
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff832efb6c)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/xen/grant-table.c (ffffffff817907e5)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8179d250)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d802a)
Location: arch/x86/include/asm/processor.h:600
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81a2db12)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff833164d7)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
  - arch/x86/pci/xen.c:xen_hvm_msi_init
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
In arch/x86/events/amd/core.c (ffffffff8344a92f)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_core_pmu_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff81e44805)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff8344b6ba)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/lbr.c (ffffffff8344d9db)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/pt.c (ffffffff8344e075)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8344eca5)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8344f8e8)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
  - arch/x86/xen/enlighten_hvm.c:cpuid_eax
```
```
In arch/x86/xen/pmu.c (ffffffff8102de7b)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83451cb1)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff83453ce7)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff834547e2)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83454e54)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tsc.c (ffffffff83459af2)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/process.c (ffffffff81051d7f)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8105c4c1)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8105cbba)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105e365)
Location: arch/x86/include/asm/processor.h:600
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
  - arch/x86/kernel/cpu/common.c:detect_ht_early
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81063c87)
Location: arch/x86/include/asm/processor.h:600
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
In arch/x86/kernel/cpu/amd.c (ffffffff81064917)
Location: arch/x86/include/asm/processor.h:600
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8106601b)
Location: arch/x86/include/asm/processor.h:600
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
In arch/x86/kernel/cpu/centaur.c (ffffffff81066436)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8106666b)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810688db)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81e4b0e5)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff83460fac)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81071682)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8107308a)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81074396)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff83462945)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff83462ef0)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff83463234)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81084832)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81085088)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81085366)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346c5a6)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
```
```
In arch/x86/kernel/crash.c (ffffffff810976a2)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/hpet.c (ffffffff8346f07f)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81e4e6d1)
Location: arch/x86/include/asm/processor.h:600
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8109f3b0)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810a1120)
Location: arch/x86/include/asm/processor.h:600
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff834a7cc0)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/xen/grant-table.c (ffffffff818c8a91)
Location: arch/x86/include/asm/processor.h:600
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff818d692b)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81916297)
Location: arch/x86/include/asm/processor.h:600
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81b52a4b)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81b99493)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff834d0e64)
Location: arch/x86/include/asm/processor.h:600
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
  - arch/x86/pci/xen.c:xen_hvm_msi_init
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
In arch/x86/events/amd/core.c (ffffffff83e6524a)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_core_pmu_init
```
```
In arch/x86/events/amd/lbr.c (ffffffff83e6562d)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff83e65a50)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/core.c (ffffffff83e664cb)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/lbr.c (ffffffff83e68e06)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/pt.c (ffffffff83e696fb)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff83e6a545)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff83e6b916)
Location: arch/x86/include/asm/cpuid.h:72
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
In arch/x86/xen/pmu.c (ffffffff8103524b)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83e6e989)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff83e71497)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff83e722b6)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83e72a1c)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tsc.c (ffffffff83e79613)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/process.c (ffffffff8105f5c1)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:select_idle_routine
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106a4c1)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8106af3a)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106c92b)
Location: arch/x86/include/asm/cpuid.h:72
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
  - arch/x86/kernel/cpu/common.c:detect_ht_early
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81072de7)
Location: arch/x86/include/asm/cpuid.h:72
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
In arch/x86/kernel/cpu/amd.c (ffffffff81073b97)
Location: arch/x86/include/asm/cpuid.h:72
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8107536b)
Location: arch/x86/include/asm/cpuid.h:72
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
In arch/x86/kernel/cpu/centaur.c (ffffffff81075756)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8107594b)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107839b)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff83e7fc83)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff83e82e1a)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81081f42)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810830de)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810845c6)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff83e84e74)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff83e8529d)
Location: arch/x86/include/asm/cpuid.h:72
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
In arch/x86/kernel/cpu/acrn.c (ffffffff83e85c5f)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
  - arch/x86/kernel/cpu/acrn.c:acrn_get_tsc_khz
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81097732)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81097e77)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e90ffb)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
```
```
In arch/x86/kernel/hpet.c (ffffffff83e9528c)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_is_pc10_damaged
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810b5a6c)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810b6a10)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810b9030)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff83edeeb8)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/xen/grant-table.c (ffffffff81a19879)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/events/events_base.c (ffffffff83eea8c7)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a28e97)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a719c9)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff83efebe2)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_parse_features
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81d3a3b6)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff83f15004)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
  - arch/x86/pci/xen.c:xen_hvm_msi_init
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
In arch/x86/events/amd/core.c (ffffffff836858ca)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_core_pmu_init
```
```
In arch/x86/events/amd/lbr.c (ffffffff83685cad)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff836860d0)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/core.c (ffffffff83686b3b)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/events/intel/lbr.c (ffffffff836897a6)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/pt.c (ffffffff8368a08b)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8368aed5)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init
```
```
In arch/x86/xen/time.c (ffffffff8368b703)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8368c3b6)
Location: arch/x86/include/asm/cpuid.h:72
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
In arch/x86/xen/pmu.c (ffffffff810351cb)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8368f309)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data
  - arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff836922ec)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff836931c6)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8369393c)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tsc.c (ffffffff8369bc1e)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/process.c (ffffffff81060d1a)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:select_idle_routine
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106badf)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8106c8aa)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106e307)
Location: arch/x86/include/asm/cpuid.h:72
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
  - arch/x86/kernel/cpu/common.c:detect_ht_early
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810749c7)
Location: arch/x86/include/asm/cpuid.h:72
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
In arch/x86/kernel/cpu/amd.c (ffffffff81075a47)
Location: arch/x86/include/asm/cpuid.h:72
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
In arch/x86/kernel/cpu/hygon.c (ffffffff810774db)
Location: arch/x86/include/asm/cpuid.h:72
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
In arch/x86/kernel/cpu/centaur.c (ffffffff810778c6)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81077abb)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107a64b)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff836a619f)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81084482)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81084f1e)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81086b76)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff836a83b4)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff836a87dd)
Location: arch/x86/include/asm/cpuid.h:72
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
In arch/x86/kernel/cpu/acrn.c (ffffffff836a919f)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
  - arch/x86/kernel/cpu/acrn.c:acrn_get_tsc_khz
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8109a7f2)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8109af17)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b49cb)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
```
```
In arch/x86/kernel/hpet.c (ffffffff836b8dec)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_is_pc10_damaged
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810b8b62)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810b9b50)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810bc200)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff83704938)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/xen/grant-table.c (ffffffff81a628f9)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/events/events_base.c (ffffffff837102b7)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a72597)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abc279)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff83724a52)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_parse_features
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81da4e46)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff8373b784)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
  - arch/x86/pci/xen.c:xen_hvm_msi_init
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
In arch/x86/events/amd/core.c (ffffffff838b4a5a)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_core_pmu_init
```
```
In arch/x86/events/amd/lbr.c (ffffffff838b4e3d)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff838b5260)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/core.c (ffffffff838b5d4b)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/events/intel/lbr.c (ffffffff838b92d6)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/pt.c (ffffffff838b9c49)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff838baa95)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init
```
```
In arch/x86/xen/time.c (ffffffff838bb2c3)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff838bbf76)
Location: arch/x86/include/asm/cpuid.h:72
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
In arch/x86/xen/pmu.c (ffffffff8103b3cb)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff838bf169)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data
  - arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff838c1dfc)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff838c2d36)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/hyperv/hv_init.c (ffffffff838c331f)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tsc.c (ffffffff838cb6f8)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:detect_art
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/process.c (ffffffff81067dc6)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:select_idle_routine
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81072f53)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
  - arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81073afa)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810755d0)
Location: arch/x86/include/asm/cpuid.h:72
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
  - arch/x86/kernel/cpu/common.c:detect_ht_early
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8107be97)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107ce57)
Location: arch/x86/include/asm/cpuid.h:72
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8107ea5b)
Location: arch/x86/include/asm/cpuid.h:72
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
In arch/x86/kernel/cpu/centaur.c (ffffffff8107ee46)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8107ef9b)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81081b7b)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8108b912)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:intel_collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c1ae)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108da96)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff838d88f4)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff838d8d9d)
Location: arch/x86/include/asm/cpuid.h:72
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
In arch/x86/kernel/cpu/acrn.c (ffffffff838d97ff)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
  - arch/x86/kernel/cpu/acrn.c:acrn_get_tsc_khz
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810a2022)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e535b)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
```
```
In arch/x86/kernel/hpet.c (ffffffff838e9700)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:mwait_pc10_supported
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810bffa2)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810c11f0)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810c3380)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff83937e48)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/xen/grant-table.c (ffffffff81ab5859)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/events/events_base.c (ffffffff83943c37)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81ac46f7)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0efc9)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff839588c2)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_parse_features
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5cdd6)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff8397010f)
Location: arch/x86/include/asm/cpuid.h:72
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
  - arch/x86/pci/xen.c:xen_hvm_msi_init
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
In arch/x86/events/amd/uncore.c (ffffffff8100968a)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100aef8)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff8288ea82)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff82890a99)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828917b5)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/pmu.c (ffffffff8102011a)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8289362d)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff82895706)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff82896e09)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff8289b7e7)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810459f6)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81045cd8)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047819)
Location: arch/x86/include/asm/processor.h:589
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
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104a13e)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b14a)
Location: arch/x86/include/asm/processor.h:589
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bdbf)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104c0eb)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c40b)
Location: arch/x86/include/asm/processor.h:589
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
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81054397)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828a0682)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056d4e)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058b3b)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828a1742)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828a1ac5)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff828a1cdb)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810624b0)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81062b9a)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81062f6e)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81070519)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81075e59)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81076757)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81078536)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
```
```
In drivers/idle/intel_idle.c (ffffffff828e0fa7)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/xen/grant-table.c (ffffffff81629ba0)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff816335fd)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81669135)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8186deea)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff82900a47)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
  - arch/x86/pci/xen.c:xen_msi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff81007e5e)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8288c249)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/core.c (ffffffff8288c9d9)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff8288e9a6)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff8288f142)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff82893a88)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81034d9f)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff810350d1)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81036b51)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8103884f)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8103a5da)
Location: arch/x86/include/asm/processor.h:589
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8103afbb)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8103b56e)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8103b882)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103cf21)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff82896c57)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff82898605)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81046f48)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81048419)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff8289991b)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82899b1a)
Location: arch/x86/include/asm/processor.h:589
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
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff82899e29)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81052915)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81052f64)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81053297)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81060523)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81065e3a)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff828a1dd2)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81067ce3)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff828d9456)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8183716d)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff8100964a)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100aeb8)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff828a1a82)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff828a3a99)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a4794)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/pmu.c (ffffffff8101ff7a)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a6624)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a86f6)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff828a9df9)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff828ae7aa)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045836)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81045b18)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047659)
Location: arch/x86/include/asm/processor.h:589
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
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049f7e)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104af8a)
Location: arch/x86/include/asm/processor.h:589
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bbff)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104bf2b)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c24b)
Location: arch/x86/include/asm/processor.h:589
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
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810547c7)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828b3645)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105717e)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058f6b)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828b4705)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b4a88)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81062960)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8106304a)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8106341e)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81070519)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81075e09)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81076707)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810784e6)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
```
```
In drivers/idle/intel_idle.c (ffffffff828f3e37)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/xen/grant-table.c (ffffffff81657b70)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff816615cd)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81697515)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818bec7a)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff8291604e)
Location: arch/x86/include/asm/processor.h:589
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
In arch/x86/events/amd/uncore.c (ffffffff810097aa)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100b07c)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:cpuid_eax
```
```
In arch/x86/events/intel/core.c (ffffffff828a1a96)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/pt.c (ffffffff828a3aad)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a4768)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/pmu.c (ffffffff810201ca)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a65f8)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a8706)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff828a9e09)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/tsc.c (ffffffff828ae7d8)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81046c36)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81046f18)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81048a69)
Location: arch/x86/include/asm/processor.h:589
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
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
  - arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104b38e)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104c39a)
Location: arch/x86/include/asm/processor.h:589
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
In arch/x86/kernel/cpu/hygon.c (ffffffff8104d00f)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104d33b)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104d65b)
Location: arch/x86/include/asm/processor.h:589
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
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81055c47)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828b3673)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105861e)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105a40b)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828b4726)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
  - arch/x86/kernel/cpu/vmware.c:vmware_platform
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b4aa9)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_edx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx
  - arch/x86/kernel/cpu/mshyperv.c:cpuid_eax
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff828b4cbf)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81063f20)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8106460a)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff810649de)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bbd12)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
```
```
In arch/x86/kernel/crash.c (ffffffff81072533)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81077e69)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810788d7)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff8107a5e6)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
```
```
In drivers/idle/intel_idle.c (ffffffff828f928f)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init
```
```
In drivers/xen/grant-table.c (ffffffff81672170)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8167bb9d)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b1bd5)
Location: arch/x86/include/asm/processor.h:589
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818daf8a)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff8291cda5)
Location: arch/x86/include/asm/processor.h:589
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
  - arch/x86/pci/xen.c:xen_msi_init
```
</details>
</li>
</ul>

## Differences
