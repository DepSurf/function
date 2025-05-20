# Function: <code>cpuid_eax</code>

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
In arch/x86/events/amd/ibs.c (ffffffff81f5d9a4)
Location: arch/x86/include/asm/processor.h:524
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f969)
Location: arch/x86/include/asm/processor.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8103fe66)
Location: arch/x86/include/asm/processor.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104092d)
Location: arch/x86/include/asm/processor.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810419af)
Location: arch/x86/include/asm/processor.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81042ac7)
Location: arch/x86/include/asm/processor.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff810433ae)
Location: arch/x86/include/asm/processor.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044f3c)
Location: arch/x86/include/asm/processor.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff81f6b290)
Location: arch/x86/include/asm/processor.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d0b0)
Location: arch/x86/include/asm/processor.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e134)
Location: arch/x86/include/asm/processor.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81f6d7b8)
Location: arch/x86/include/asm/processor.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kvm.c (ffffffff81063f77)
Location: arch/x86/include/asm/processor.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff816b6f2d)
Location: arch/x86/include/asm/processor.h:524
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In arch/x86/pci/xen.c (ffffffff81fb90ac)
Location: arch/x86/include/asm/processor.h:524
Inline: True
Inline callers:
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
In arch/x86/events/amd/ibs.c (ffffffff81f858a3)
Location: arch/x86/include/asm/processor.h:535
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f8aa)
Location: arch/x86/include/asm/processor.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8103fcc9)
Location: arch/x86/include/asm/processor.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104067a)
Location: arch/x86/include/asm/processor.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810418df)
Location: arch/x86/include/asm/processor.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81042f3f)
Location: arch/x86/include/asm/processor.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104334e)
Location: arch/x86/include/asm/processor.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044fd1)
Location: arch/x86/include/asm/processor.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff81f935ad)
Location: arch/x86/include/asm/processor.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d0e9)
Location: arch/x86/include/asm/processor.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e2c4)
Location: arch/x86/include/asm/processor.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81f95b77)
Location: arch/x86/include/asm/processor.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kvm.c (ffffffff81063b9c)
Location: arch/x86/include/asm/processor.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81719cf4)
Location: arch/x86/include/asm/processor.h:535
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff81fe6c8e)
Location: arch/x86/include/asm/processor.h:535
Inline: True
Inline callers:
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
In arch/x86/events/amd/ibs.c (ffffffff81fc0cdd)
Location: arch/x86/include/asm/processor.h:577
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f2fa)
Location: arch/x86/include/asm/processor.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8103f799)
Location: arch/x86/include/asm/processor.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040096)
Location: arch/x86/include/asm/processor.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104132f)
Location: arch/x86/include/asm/processor.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81042a7d)
Location: arch/x86/include/asm/processor.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81042e3e)
Location: arch/x86/include/asm/processor.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046b81)
Location: arch/x86/include/asm/processor.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff81fcebb9)
Location: arch/x86/include/asm/processor.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104f829)
Location: arch/x86/include/asm/processor.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050944)
Location: arch/x86/include/asm/processor.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81fd0f31)
Location: arch/x86/include/asm/processor.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kvm.c (ffffffff8106704c)
Location: arch/x86/include/asm/processor.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8174bab4)
Location: arch/x86/include/asm/processor.h:577
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff820254d2)
Location: arch/x86/include/asm/processor.h:577
Inline: True
Inline callers:
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
In arch/x86/events/amd/ibs.c (ffffffff820a0fc3)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff820a3b8b)
Location: arch/x86/include/asm/processor.h:588
Inline: True
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103d22c)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8103d688)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103e006)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8103fd4a)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81040b67)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81040f19)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046674)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff820af5de)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff820b1277)
Location: arch/x86/include/asm/processor.h:588
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104f769)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050844)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff820b1a6a)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kvm.c (ffffffff8106631c)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8176a23f)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff821089bf)
Location: arch/x86/include/asm/processor.h:588
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_eax(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100a00d)
Location: arch/x86/include/asm/processor.h:610
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff826aa28a)
Location: arch/x86/include/asm/processor.h:610
Inline: True
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103fdb5)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81040228)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81041a35)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81043352)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81043b66)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81044379)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104a094)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff81050bc1)
Location: arch/x86/include/asm/processor.h:610
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff826b7a89)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053399)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054e04)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81055496)
Location: arch/x86/include/asm/processor.h:610
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kvm.c (ffffffff8106a51c)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/xen/grant-table.c (ffffffff815ba70d)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817e060a)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff82712317)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff8100a00d-ffffffff8100a05e: cpuid_eax (STB_LOCAL)
ffffffff81050bc1-ffffffff81050c12: cpuid_eax (STB_LOCAL)
ffffffff81055496-ffffffff810554e7: cpuid_eax (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_eax(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100a6c5)
Location: arch/x86/include/asm/processor.h:626
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff826d33ff)
Location: arch/x86/include/asm/processor.h:626
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81041559)
Location: arch/x86/include/asm/processor.h:626
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81041a55)
Location: arch/x86/include/asm/processor.h:626
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81043318)
Location: arch/x86/include/asm/processor.h:626
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810450d6)
Location: arch/x86/include/asm/processor.h:626
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104613c)
Location: arch/x86/include/asm/processor.h:626
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104657b)
Location: arch/x86/include/asm/processor.h:626
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104c765)
Location: arch/x86/include/asm/processor.h:626
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810537c0)
Location: arch/x86/include/asm/processor.h:626
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff826e179b)
Location: arch/x86/include/asm/processor.h:626
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105607e)
Location: arch/x86/include/asm/processor.h:626
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057b1b)
Location: arch/x86/include/asm/processor.h:626
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8105831e)
Location: arch/x86/include/asm/processor.h:626
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kvm.c (ffffffff8106d177)
Location: arch/x86/include/asm/processor.h:626
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/xen/grant-table.c (ffffffff815f242d)
Location: arch/x86/include/asm/processor.h:626
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81828c85)
Location: arch/x86/include/asm/processor.h:626
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff8273c59e)
Location: arch/x86/include/asm/processor.h:626
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff8100a6c5-ffffffff8100a716: cpuid_eax (STB_LOCAL)
ffffffff810537c0-ffffffff81053811: cpuid_eax (STB_LOCAL)
ffffffff8105831e-ffffffff8105836f: cpuid_eax (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_eax(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100a635)
Location: arch/x86/include/asm/processor.h:621
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff82889323)
Location: arch/x86/include/asm/processor.h:621
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81042c19)
Location: arch/x86/include/asm/processor.h:621
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81043075)
Location: arch/x86/include/asm/processor.h:621
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81044998)
Location: arch/x86/include/asm/processor.h:621
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81046aea)
Location: arch/x86/include/asm/processor.h:621
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81047c31)
Location: arch/x86/include/asm/processor.h:621
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81048240)
Location: arch/x86/include/asm/processor.h:621
Inline: True
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff810487fb)
Location: arch/x86/include/asm/processor.h:621
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81049e55)
Location: arch/x86/include/asm/processor.h:621
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81050e40)
Location: arch/x86/include/asm/processor.h:621
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8289775d)
Location: arch/x86/include/asm/processor.h:621
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105377e)
Location: arch/x86/include/asm/processor.h:621
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810554bb)
Location: arch/x86/include/asm/processor.h:621
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8105df43)
Location: arch/x86/include/asm/processor.h:621
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kvm.c (ffffffff81073347)
Location: arch/x86/include/asm/processor.h:621
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/xen/grant-table.c (ffffffff8160d91d)
Location: arch/x86/include/asm/processor.h:621
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81854d15)
Location: arch/x86/include/asm/processor.h:621
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff828f65b9)
Location: arch/x86/include/asm/processor.h:621
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff8100a635-ffffffff8100a686: cpuid_eax (STB_LOCAL)
ffffffff81050e40-ffffffff81050e91: cpuid_eax (STB_LOCAL)
ffffffff8105df43-ffffffff8105df94: cpuid_eax (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_eax(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100aac5)
Location: arch/x86/include/asm/processor.h:611
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a06a4)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045126)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81045408)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046f19)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810495e1)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a8e1)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104afe0)
Location: arch/x86/include/asm/processor.h:611
Inline: True
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104b5bb)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104b8db)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cfa5)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81053f10)
Location: arch/x86/include/asm/processor.h:611
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828af32a)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105691e)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810586eb)
Location: arch/x86/include/asm/processor.h:611
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81061342)
Location: arch/x86/include/asm/processor.h:611
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kvm.c (ffffffff81076ed7)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/xen/grant-table.c (ffffffff8164130b)
Location: arch/x86/include/asm/processor.h:611
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818977ba)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff82911ff9)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff8100aac5-ffffffff8100ab16: cpuid_eax (STB_LOCAL)
ffffffff81053f10-ffffffff81053f61: cpuid_eax (STB_LOCAL)
ffffffff81061342-ffffffff81061393: cpuid_eax (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_eax(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100aee1)
Location: arch/x86/include/asm/processor.h:611
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a3794)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045876)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81045b58)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810476a9)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049fce)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b2e4)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b9e0)
Location: arch/x86/include/asm/processor.h:611
Inline: True
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104bf7b)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c29b)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d945)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81054800)
Location: arch/x86/include/asm/processor.h:611
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828b2663)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810571ce)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058fbb)
Location: arch/x86/include/asm/processor.h:611
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81061bd2)
Location: arch/x86/include/asm/processor.h:611
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kvm.c (ffffffff81077f27)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/xen/grant-table.c (ffffffff81663ccb)
Location: arch/x86/include/asm/processor.h:611
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818c97ca)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff8291bd92)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff8100aee1-ffffffff8100af32: cpuid_eax (STB_LOCAL)
ffffffff81054800-ffffffff81054851: cpuid_eax (STB_LOCAL)
ffffffff81061bd2-ffffffff81061c23: cpuid_eax (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_eax(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100c161)
Location: arch/x86/include/asm/processor.h:645
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff82cc9a60)
Location: arch/x86/include/asm/processor.h:645
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81049699)
Location: arch/x86/include/asm/processor.h:645
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81049978)
Location: arch/x86/include/asm/processor.h:645
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104b409)
Location: arch/x86/include/asm/processor.h:645
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104e4f7)
Location: arch/x86/include/asm/processor.h:645
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104ee50)
Location: arch/x86/include/asm/processor.h:645
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8105013c)
Location: arch/x86/include/asm/processor.h:645
Inline: True
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81050a09)
Location: arch/x86/include/asm/processor.h:645
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81050d29)
Location: arch/x86/include/asm/processor.h:645
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81bbe290)
Location: arch/x86/include/asm/processor.h:645
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810598db)
Location: arch/x86/include/asm/processor.h:645
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff82cd780f)
Location: arch/x86/include/asm/processor.h:645
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105c47e)
Location: arch/x86/include/asm/processor.h:645
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105dcbb)
Location: arch/x86/include/asm/processor.h:645
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81067b7e)
Location: arch/x86/include/asm/processor.h:645
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f205)
Location: arch/x86/include/asm/processor.h:645
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/xen/grant-table.c (ffffffff81712f55)
Location: arch/x86/include/asm/processor.h:645
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_need_v2
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199c9d8)
Location: arch/x86/include/asm/processor.h:645
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff82d31afb)
Location: arch/x86/include/asm/processor.h:645
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff8100c161-ffffffff8100c1b2: cpuid_eax (STB_LOCAL)
ffffffff810598db-ffffffff8105992c: cpuid_eax (STB_LOCAL)
ffffffff81067b7e-ffffffff81067bcd: cpuid_eax (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_eax(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81bd2056)
Location: arch/x86/include/asm/processor.h:628
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff82fb58c5)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048b3b)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81048df8)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104aad9)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104da37)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104e110)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104f34c)
Location: arch/x86/include/asm/processor.h:628
Inline: True
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104fb69)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104fe89)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c36bd0)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81bd5b94)
Location: arch/x86/include/asm/processor.h:628
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff82fc37e2)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105acee)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105c35b)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81bd65c8)
Location: arch/x86/include/asm/processor.h:628
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kvm.c (ffffffff8107eeb5)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/xen/grant-table.c (ffffffff8172fd55)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_need_v2
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199fa68)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff83020b36)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
```
**Symbols:**

```
ffffffff81bd2056-ffffffff81bd20a7: cpuid_eax (STB_LOCAL)
ffffffff81bd5b94-ffffffff81bd5be5: cpuid_eax (STB_LOCAL)
ffffffff81bd65c8-ffffffff81bd6617: cpuid_eax (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_eax(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81bc40e6)
Location: arch/x86/include/asm/processor.h:610
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff831c00d0)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104a40b)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8104a6c8)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104c3b9)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104f7a1)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104fbb0)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8105143e)
Location: arch/x86/include/asm/processor.h:610
Inline: True
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81051719)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff810518ed)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c29080)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81bc7f48)
Location: arch/x86/include/asm/processor.h:610
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff831cddc4)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105b69e)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105cc6b)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81bc887a)
Location: arch/x86/include/asm/processor.h:610
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kvm.c (ffffffff8107ff35)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/xen/grant-table.c (ffffffff81713dee)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff819844a8)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff8322bd04)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
```
**Symbols:**

```
ffffffff81bc40e6-ffffffff81bc4137: cpuid_eax (STB_LOCAL)
ffffffff81bc7f48-ffffffff81bc7f99: cpuid_eax (STB_LOCAL)
ffffffff81bc887a-ffffffff81bc88c9: cpuid_eax (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_eax(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81c954b9)
Location: arch/x86/include/asm/processor.h:622
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff832a0884)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81050f8b)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff810515ca)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81053669)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81057981)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81057e54)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810599ce)
Location: arch/x86/include/asm/processor.h:622
Inline: True
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81059ca9)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81059e7d)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81d47816)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81c9bc5a)
Location: arch/x86/include/asm/processor.h:622
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff832aff27)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81064c9b)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8106630b)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c9d06a)
Location: arch/x86/include/asm/processor.h:622
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id
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
In arch/x86/kernel/kvm.c (ffffffff8108ed75)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/xen/grant-table.c (ffffffff8179081e)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81a2db12)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff83316529)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
```
**Symbols:**

```
ffffffff81c954b9-ffffffff81c9550a: cpuid_eax (STB_LOCAL)
ffffffff81c9bc5a-ffffffff81c9bcab: cpuid_eax (STB_LOCAL)
ffffffff81c9d06a-ffffffff81c9d0b9: cpuid_eax (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_eax(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81e447ce)
Location: arch/x86/include/asm/processor.h:622
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff81e465c3)
Location: arch/x86/include/asm/processor.h:622
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/kernel/process.c (ffffffff81051d69)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8105c4ab)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8105cbba)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105e970)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81063c71)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810649f5)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810660a5)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81066420)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81066655)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810688db)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81e4b0ae)
Location: arch/x86/include/asm/processor.h:622
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff83460f88)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81071682)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81073083)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81e4c43f)
Location: arch/x86/include/asm/processor.h:622
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id
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
In arch/x86/kernel/kvm.c (ffffffff8109f915)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/xen/grant-table.c (ffffffff818c8acd)
Location: arch/x86/include/asm/processor.h:622
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81b9947d)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff834d0eb2)
Location: arch/x86/include/asm/processor.h:622
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
```
**Symbols:**

```
ffffffff81e447ce-ffffffff81e4483c: cpuid_eax (STB_LOCAL)
ffffffff81e465c3-ffffffff81e46624: cpuid_eax (STB_LOCAL)
ffffffff81e4b0ae-ffffffff81e4b11c: cpuid_eax (STB_LOCAL)
ffffffff81e4c43f-ffffffff81e4c4a0: cpuid_eax (STB_LOCAL)
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
In arch/x86/events/amd/ibs.c (ffffffff83e65a2c)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff83e6b821)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/kernel/process.c (ffffffff8105f439)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106a4ab)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8106af3a)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106cf8e)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:check_null_seg_clears_base
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81072dd1)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81073c75)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810753f5)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff81075740)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81075935)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107839b)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff83e7fc7c)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff83e82e04)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81081f42)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810830d7)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff83e8528f)
Location: arch/x86/include/asm/cpuid.h:94
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
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81096287)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_get_tsc_khz
```
```
In arch/x86/kernel/kvm.c (ffffffff810b71c5)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/xen/grant-table.c (ffffffff81a198b0)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/events/events_base.c (ffffffff83eea902)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81d3a3a0)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff83f1503f)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
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
In arch/x86/events/amd/ibs.c (ffffffff836860ac)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/core.c (ffffffff810132b6)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8368c2c1)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8368f69d)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data
  - arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data
```
```
In arch/x86/kernel/process.c (ffffffff81060b53)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106bac9)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8106c8aa)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106dd4a)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810749b1)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81075b25)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81077567)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff810778b0)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff81077aa5)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107a64b)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff836a6189)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81084482)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81084f17)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff836a87cf)
Location: arch/x86/include/asm/cpuid.h:94
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
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff810993a7)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_get_tsc_khz
```
```
In arch/x86/kernel/kvm.c (ffffffff810ba3b5)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/xen/grant-table.c (ffffffff81a62930)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/events/events_base.c (ffffffff837102f2)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81da4e30)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff8373b7bf)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
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
In arch/x86/events/amd/ibs.c (ffffffff838b523c)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/core.c (ffffffff8101a647)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff838bbe81)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff838bf38d)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data
  - arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data
```
```
In arch/x86/kernel/process.c (ffffffff81067c03)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81072f3d)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81073afa)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81074fca)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8107be81)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107cf35)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107eae7)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8107ee30)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_c3
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8107ef85)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81081b7b)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8108b904)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:intel_collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c1a7)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff838d8d8f)
Location: arch/x86/include/asm/cpuid.h:94
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
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff810a09f7)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_get_tsc_khz
```
```
In arch/x86/kernel/kvm.c (ffffffff810c17f5)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/xen/grant-table.c (ffffffff81ab5890)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/events/events_base.c (ffffffff83943c72)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5cdc0)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff8397014a)
Location: arch/x86/include/asm/cpuid.h:94
Inline: True
Inline callers:
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_eax(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100aee1)
Location: arch/x86/include/asm/processor.h:611
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828917b5)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810459f6)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81045cd8)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047819)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104a13e)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b454)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bb50)
Location: arch/x86/include/asm/processor.h:611
Inline: True
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104c0eb)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c40b)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104daa5)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81054380)
Location: arch/x86/include/asm/processor.h:611
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828a0682)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056d4e)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058b3b)
Location: arch/x86/include/asm/processor.h:611
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81061752)
Location: arch/x86/include/asm/processor.h:611
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kvm.c (ffffffff81076f27)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/xen/grant-table.c (ffffffff81629b3b)
Location: arch/x86/include/asm/processor.h:611
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8186deea)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff82900a96)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff8100aee1-ffffffff8100af32: cpuid_eax (STB_LOCAL)
ffffffff81054380-ffffffff810543d1: cpuid_eax (STB_LOCAL)
ffffffff81061752-ffffffff810617a3: cpuid_eax (STB_LOCAL)
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
In arch/x86/events/amd/ibs.c (ffffffff8288c249)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81034d9f)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff810350d1)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81036b51)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8103884f)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8103a8c4)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8103ad98)
Location: arch/x86/include/asm/processor.h:611
Inline: True
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8103b56e)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8103b882)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103cf21)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff82896c57)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff82898605)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81046f48)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81048419)
Location: arch/x86/include/asm/processor.h:611
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82899b1a)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kvm.c (ffffffff828a1dd2)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8183716d)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_eax(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100aea1)
Location: arch/x86/include/asm/processor.h:611
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a4794)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045836)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81045b18)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047659)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049f7e)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b294)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b990)
Location: arch/x86/include/asm/processor.h:611
Inline: True
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104bf2b)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104c24b)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d8f5)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810547b0)
Location: arch/x86/include/asm/processor.h:611
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828b3645)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105717e)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058f6b)
Location: arch/x86/include/asm/processor.h:611
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81061b82)
Location: arch/x86/include/asm/processor.h:611
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kvm.c (ffffffff81076ed7)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/xen/grant-table.c (ffffffff81657b0b)
Location: arch/x86/include/asm/processor.h:611
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818bec7a)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff8291609d)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff8100aea1-ffffffff8100aef2: cpuid_eax (STB_LOCAL)
ffffffff810547b0-ffffffff81054801: cpuid_eax (STB_LOCAL)
ffffffff81061b82-ffffffff81061bd3: cpuid_eax (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
unsigned int cpuid_eax(unsigned int op);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100b065)
Location: arch/x86/include/asm/processor.h:611
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a4768)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81046c36)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81046f18)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81048a69)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:microcode_check
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104b38e)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104c6a4)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104cda0)
Location: arch/x86/include/asm/processor.h:611
Inline: True
```
```
In arch/x86/kernel/cpu/centaur.c (ffffffff8104d33b)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/centaur.c:init_centaur
  - arch/x86/kernel/cpu/centaur.c:init_centaur
```
```
In arch/x86/kernel/cpu/zhaoxin.c (ffffffff8104d65b)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
  - arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ed35)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81055c30)
Location: arch/x86/include/asm/processor.h:611
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828b3673)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105861e)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105a40b)
Location: arch/x86/include/asm/processor.h:611
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81063132)
Location: arch/x86/include/asm/processor.h:611
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kvm.c (ffffffff81078f47)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
```
In drivers/xen/grant-table.c (ffffffff8167210b)
Location: arch/x86/include/asm/processor.h:611
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818daf8a)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
  - drivers/cpufreq/powernow-k8.c:check_supported_cpu
```
```
In arch/x86/pci/xen.c (ffffffff8291cdf4)
Location: arch/x86/include/asm/processor.h:611
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff8100b065-ffffffff8100b0b6: cpuid_eax (STB_LOCAL)
ffffffff81055c30-ffffffff81055c81: cpuid_eax (STB_LOCAL)
ffffffff81063132-ffffffff81063183: cpuid_eax (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
