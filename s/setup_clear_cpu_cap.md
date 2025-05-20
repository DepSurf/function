# Function: <code>setup_clear_cpu_cap</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void setup_clear_cpu_cap(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81042200)
Location: arch/x86/kernel/cpu/cpuid-deps.c:118
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/hyperv/mmu.c:hyperv_setup_mmu_ops
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:setup_disable_smap
  - arch/x86/kernel/cpu/common.c:setup_disable_smep
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/apic/apic.c:setup_nolapic
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:parse_lapic
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff81042200-ffffffff81042214: setup_clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void setup_clear_cpu_cap(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff810440e0)
Location: arch/x86/kernel/cpu/cpuid-deps.c:118
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/cpu/common.c:setup_disable_smap
  - arch/x86/kernel/cpu/common.c:setup_disable_smep
  - arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup
  - arch/x86/kernel/cpu/common.c:x86_nopcid_setup
  - arch/x86/kernel/cpu/common.c:x86_mpx_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:parse_lapic
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff810440e0-ffffffff810440f4: setup_clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void setup_clear_cpu_cap(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81045ae0)
Location: arch/x86/kernel/cpu/cpuid-deps.c:118
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/cpu/common.c:setup_disable_smap
  - arch/x86/kernel/cpu/common.c:setup_disable_smep
  - arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup
  - arch/x86/kernel/cpu/common.c:x86_nopcid_setup
  - arch/x86/kernel/cpu/common.c:x86_mpx_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:parse_lapic
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff81045ae0-ffffffff81045af4: setup_clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void setup_clear_cpu_cap(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff810482f0)
Location: arch/x86/kernel/cpu/cpuid-deps.c:127
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:setup_disable_smap
  - arch/x86/kernel/cpu/common.c:setup_disable_smep
  - arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup
  - arch/x86/kernel/cpu/common.c:x86_nopcid_setup
  - arch/x86/kernel/cpu/common.c:x86_mpx_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/apic/apic.c:setup_nolapic
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:parse_lapic
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff810482f0-ffffffff81048304: setup_clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void setup_clear_cpu_cap(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048bb0)
Location: arch/x86/kernel/cpu/cpuid-deps.c:128
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/cpu/common.c:setup_disable_smap
  - arch/x86/kernel/cpu/common.c:setup_disable_smep
  - arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup
  - arch/x86/kernel/cpu/common.c:x86_nopcid_setup
  - arch/x86/kernel/cpu/common.c:x86_mpx_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/apic/apic.c:setup_nolapic
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:parse_lapic
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff81048bb0-ffffffff81048bc4: setup_clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void setup_clear_cpu_cap(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104ccd0)
Location: arch/x86/kernel/cpu/cpuid-deps.c:128
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/fpu/init.c:fpu__init_parse_early_param
  - arch/x86/kernel/fpu/init.c:fpu__init_parse_early_param
  - arch/x86/kernel/fpu/init.c:fpu__init_parse_early_param
  - arch/x86/kernel/fpu/init.c:fpu__init_parse_early_param
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:setup_disable_smap
  - arch/x86/kernel/cpu/common.c:setup_disable_smep
  - arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup
  - arch/x86/kernel/cpu/common.c:x86_nopcid_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt
  - arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt
  - arch/x86/kernel/apic/apic.c:setup_nolapic
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:parse_lapic
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff8104ccd0-ffffffff8104cce4: setup_clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void setup_clear_cpu_cap(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104c130)
Location: arch/x86/kernel/cpu/cpuid-deps.c:131
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:x86_nofsgsbase_setup
  - arch/x86/kernel/cpu/common.c:setup_disable_smap
  - arch/x86/kernel/cpu/common.c:setup_disable_smep
  - arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup
  - arch/x86/kernel/cpu/common.c:x86_nopcid_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt
  - arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt
  - arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt
  - arch/x86/kernel/apic/apic.c:setup_nolapic
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:parse_lapic
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff8104c130-ffffffff8104c144: setup_clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void setup_clear_cpu_cap(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104dc70)
Location: arch/x86/kernel/cpu/cpuid-deps.c:134
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:x86_nofsgsbase_setup
  - arch/x86/kernel/cpu/common.c:setup_disable_smap
  - arch/x86/kernel/cpu/common.c:setup_disable_smep
  - arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup
  - arch/x86/kernel/cpu/common.c:x86_nopcid_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/feat_ctl.c:nosgx
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/apic/apic.c:setup_nolapic
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:parse_lapic
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff8104dc70-ffffffff8104dc84: setup_clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void setup_clear_cpu_cap(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81055440)
Location: arch/x86/kernel/cpu/cpuid-deps.c:134
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:x86_nofsgsbase_setup
  - arch/x86/kernel/cpu/common.c:setup_disable_smap
  - arch/x86/kernel/cpu/common.c:setup_disable_smep
  - arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup
  - arch/x86/kernel/cpu/common.c:x86_nopcid_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/feat_ctl.c:nosgx
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/apic/apic.c:setup_nolapic
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:parse_lapic
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff81055440-ffffffff81055454: setup_clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void setup_clear_cpu_cap(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81061390)
Location: arch/x86/kernel/cpu/cpuid-deps.c:137
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:x86_nofsgsbase_setup
  - arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup
  - arch/x86/kernel/cpu/common.c:x86_nopcid_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/feat_ctl.c:nosgx
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/apic/apic.c:setup_nolapic
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:parse_lapic
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff81061390-ffffffff810613ac: setup_clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void setup_clear_cpu_cap(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8106fd40)
Location: arch/x86/kernel/cpu/cpuid-deps.c:138
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/xen/setup.c:xen_enable_syscall
  - arch/x86/xen/setup.c:xen_enable_sysenter
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:x86_nofsgsbase_setup
  - arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup
  - arch/x86/kernel/cpu/common.c:x86_nopcid_setup
  - arch/x86/kernel/cpu/feat_ctl.c:nosgx
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:parse_lapic
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff8106fd40-ffffffff8106fd5c: setup_clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void setup_clear_cpu_cap(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81071950)
Location: arch/x86/kernel/cpu/cpuid-deps.c:140
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/xen/setup.c:xen_enable_syscall
  - arch/x86/xen/setup.c:xen_enable_sysenter
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:x86_nofsgsbase_setup
  - arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup
  - arch/x86/kernel/cpu/common.c:x86_nopcid_setup
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/feat_ctl.c:nosgx
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_overwrite_state
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:parse_lapic
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff81071950-ffffffff8107196c: setup_clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void setup_clear_cpu_cap(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81079170)
Location: arch/x86/kernel/cpu/cpuid-deps.c:141
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/xen/setup.c:xen_enable_syscall
  - arch/x86/xen/setup.c:xen_enable_sysenter
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/common.c:x86_nofsgsbase_setup
  - arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup
  - arch/x86/kernel/cpu/common.c:x86_nopcid_setup
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/feat_ctl.c:nosgx
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_overwrite_state
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:parse_lapic
  - arch/x86/kernel/cet.c:ibt_setup
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff81079170-ffffffff8107918c: setup_clear_cpu_cap (STB_GLOBAL)
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
void setup_clear_cpu_cap(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048d20)
Location: arch/x86/kernel/cpu/cpuid-deps.c:128
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/cpu/common.c:setup_disable_smap
  - arch/x86/kernel/cpu/common.c:setup_disable_smep
  - arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup
  - arch/x86/kernel/cpu/common.c:x86_nopcid_setup
  - arch/x86/kernel/cpu/common.c:x86_mpx_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/apic/apic.c:setup_nolapic
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:parse_lapic
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff81048d20-ffffffff81048d34: setup_clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void setup_clear_cpu_cap(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff810380b0)
Location: arch/x86/kernel/cpu/cpuid-deps.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/cpu/common.c:setup_disable_smap
  - arch/x86/kernel/cpu/common.c:setup_disable_smep
  - arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup
  - arch/x86/kernel/cpu/common.c:x86_nopcid_setup
  - arch/x86/kernel/cpu/common.c:x86_mpx_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/apic/apic.c:setup_nolapic
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:parse_lapic
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff810380b0-ffffffff810380c4: setup_clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void setup_clear_cpu_cap(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048b60)
Location: arch/x86/kernel/cpu/cpuid-deps.c:128
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/cpu/common.c:setup_disable_smap
  - arch/x86/kernel/cpu/common.c:setup_disable_smep
  - arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup
  - arch/x86/kernel/cpu/common.c:x86_nopcid_setup
  - arch/x86/kernel/cpu/common.c:x86_mpx_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/apic/apic.c:setup_nolapic
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:parse_lapic
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff81048b60-ffffffff81048b74: setup_clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void setup_clear_cpu_cap(unsigned int feature);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81049f70)
Location: arch/x86/kernel/cpu/cpuid-deps.c:128
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:setup_noclflush
  - arch/x86/kernel/cpu/common.c:early_cpu_init
  - arch/x86/kernel/cpu/common.c:setup_disable_smap
  - arch/x86/kernel/cpu/common.c:setup_disable_smep
  - arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup
  - arch/x86/kernel/cpu/common.c:x86_nopcid_setup
  - arch/x86/kernel/cpu/common.c:x86_mpx_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/apic/apic.c:setup_nolapic
  - arch/x86/kernel/apic/apic.c:init_apic_mappings
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:parse_lapic
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff81049f70-ffffffff81049f84: setup_clear_cpu_cap (STB_GLOBAL)
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
