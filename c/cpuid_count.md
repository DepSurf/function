# Function: <code>cpuid_count</code>

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
In arch/x86/events/amd/uncore.c (ffffffff8100850c)
Location: arch/x86/include/asm/processor.h:512
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/intel/pt.c (ffffffff81f5fa31)
Location: arch/x86/include/asm/processor.h:512
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8107cd3f)
Location: arch/x86/include/asm/processor.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103ea2c)
Location: arch/x86/include/asm/processor.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8103fe0d)
Location: arch/x86/include/asm/processor.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8103ff3b)
Location: arch/x86/include/asm/processor.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040826)
Location: arch/x86/include/asm/processor.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81042431)
Location: arch/x86/include/asm/processor.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
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
Location: arch/x86/include/asm/processor.h:523
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/intel/pt.c (ffffffff81f87a34)
Location: arch/x86/include/asm/processor.h:523
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81f91c6b)
Location: arch/x86/include/asm/processor.h:523
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103ec80)
Location: arch/x86/include/asm/processor.h:523
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8103fc6d)
Location: arch/x86/include/asm/processor.h:523
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8103fd9b)
Location: arch/x86/include/asm/processor.h:523
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040732)
Location: arch/x86/include/asm/processor.h:523
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81042334)
Location: arch/x86/include/asm/processor.h:523
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
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
Location: arch/x86/include/asm/processor.h:565
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/intel/pt.c (ffffffff81fc2eae)
Location: arch/x86/include/asm/processor.h:565
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81fccf1b)
Location: arch/x86/include/asm/processor.h:565
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103e610)
Location: arch/x86/include/asm/processor.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8103f73d)
Location: arch/x86/include/asm/processor.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8103f86b)
Location: arch/x86/include/asm/processor.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104017c)
Location: arch/x86/include/asm/processor.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81041e1b)
Location: arch/x86/include/asm/processor.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81082f35)
Location: arch/x86/include/asm/processor.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:rdt_get_config
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
Location: arch/x86/include/asm/processor.h:576
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/intel/pt.c (ffffffff820a314d)
Location: arch/x86/include/asm/processor.h:576
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff820ad69a)
Location: arch/x86/include/asm/processor.h:576
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103c5e0)
Location: arch/x86/include/asm/processor.h:576
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8103d631)
Location: arch/x86/include/asm/processor.h:576
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8103d75b)
Location: arch/x86/include/asm/processor.h:576
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103e0ec)
Location: arch/x86/include/asm/processor.h:576
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8103ffdb)
Location: arch/x86/include/asm/processor.h:576
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81041a0c)
Location: arch/x86/include/asm/processor.h:576
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:rdt_get_cache_alloc_cfg
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
In arch/x86/events/amd/uncore.c (ffffffff810087a6)
Location: arch/x86/include/asm/processor.h:598
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting
```
```
In arch/x86/events/intel/pt.c (ffffffff826a9437)
Location: arch/x86/include/asm/processor.h:598
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff826b3ef5)
Location: arch/x86/include/asm/processor.h:598
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f1f0)
Location: arch/x86/include/asm/processor.h:598
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff810401d1)
Location: arch/x86/include/asm/processor.h:598
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff810402fb)
Location: arch/x86/include/asm/processor.h:598
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040c62)
Location: arch/x86/include/asm/processor.h:598
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810433a7)
Location: arch/x86/include/asm/processor.h:598
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81044e5c)
Location: arch/x86/include/asm/processor.h:598
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:rdt_get_cache_alloc_cfg
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
In arch/x86/events/intel/pt.c (ffffffff826d25bc)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff826dd6cb)
Location: arch/x86/include/asm/processor.h:614
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81041149)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81041a8f)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff81041bd5)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81042502)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff826deacf)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff826deea8)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init
  - arch/x86/kernel/cpu/intel_rdt.c:rdt_get_cache_alloc_cfg
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
In arch/x86/events/intel/pt.c (ffffffff828888cc)
Location: arch/x86/include/asm/processor.h:609
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff82893b13)
Location: arch/x86/include/asm/processor.h:609
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81042759)
Location: arch/x86/include/asm/processor.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff810430af)
Location: arch/x86/include/asm/processor.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff810431f5)
Location: arch/x86/include/asm/processor.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81043b22)
Location: arch/x86/include/asm/processor.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff8289517b)
Location: arch/x86/include/asm/processor.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82897f6c)
Location: arch/x86/include/asm/processor.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
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
In arch/x86/events/intel/pt.c (ffffffff8289fa46)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828ab35e)
Location: arch/x86/include/asm/processor.h:599
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044bc5)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81045441)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8104565c)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81045fab)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff828acc6b)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828afb48)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
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
In arch/x86/events/intel/pt.c (ffffffff828a2b18)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828ae197)
Location: arch/x86/include/asm/processor.h:599
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045315)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81045b91)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff81045dac)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104670b)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff828afe76)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828b2e81)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bad21)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
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
In arch/x86/events/intel/pt.c (ffffffff82cc8af5)
Location: arch/x86/include/asm/processor.h:633
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff82cd35dc)
Location: arch/x86/include/asm/processor.h:633
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81049135)
Location: arch/x86/include/asm/processor.h:633
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff810499b1)
Location: arch/x86/include/asm/processor.h:633
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff81049b9b)
Location: arch/x86/include/asm/processor.h:633
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a76d)
Location: arch/x86/include/asm/processor.h:633
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff82cd529a)
Location: arch/x86/include/asm/processor.h:633
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105f098)
Location: arch/x86/include/asm/processor.h:633
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074c9e)
Location: arch/x86/include/asm/processor.h:633
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:set_x2apic_bits
  - arch/x86/kernel/apic/x2apic_uv_x.c:set_x2apic_bits
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
In arch/x86/events/intel/pt.c (ffffffff82fb490c)
Location: arch/x86/include/asm/processor.h:616
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff82fbf3aa)
Location: arch/x86/include/asm/processor.h:616
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:get_xsaves_size
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned
  - arch/x86/kernel/fpu/xstate.c:setup_xstate_features
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810485f6)
Location: arch/x86/include/asm/processor.h:616
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81048e31)
Location: arch/x86/include/asm/processor.h:616
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8104901b)
Location: arch/x86/include/asm/processor.h:616
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81049c1d)
Location: arch/x86/include/asm/processor.h:616
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff82fc1252)
Location: arch/x86/include/asm/processor.h:616
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d5d8)
Location: arch/x86/include/asm/processor.h:616
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff82fc43bb)
Location: arch/x86/include/asm/processor.h:616
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff82fc44f7)
Location: arch/x86/include/asm/processor.h:616
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81bd769f)
Location: arch/x86/include/asm/processor.h:616
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:set_x2apic_bits
  - arch/x86/kernel/apic/x2apic_uv_x.c:set_x2apic_bits
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
In arch/x86/events/intel/pt.c (ffffffff831bee7d)
Location: arch/x86/include/asm/processor.h:598
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff831c9914)
Location: arch/x86/include/asm/processor.h:598
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:get_xsaves_size
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81049ec6)
Location: arch/x86/include/asm/processor.h:598
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8104a701)
Location: arch/x86/include/asm/processor.h:598
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8104a8eb)
Location: arch/x86/include/asm/processor.h:598
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104b46b)
Location: arch/x86/include/asm/processor.h:598
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff831cb93d)
Location: arch/x86/include/asm/processor.h:598
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105df08)
Location: arch/x86/include/asm/processor.h:598
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff831cea8c)
Location: arch/x86/include/asm/processor.h:598
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff831cec66)
Location: arch/x86/include/asm/processor.h:598
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d7c03)
Location: arch/x86/include/asm/processor.h:598
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
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
In arch/x86/events/intel/pt.c (ffffffff8329f2ec)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff832aac60)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:get_xsaves_size
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81050933)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81051603)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8105180b)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810525c0)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff832ad13f)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810676a8)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff832b0d32)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff832b0f1c)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832baac8)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
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
In arch/x86/coco/tdx/tdx.c (ffffffff83449ec9)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_early_init
```
```
In arch/x86/events/intel/pt.c (ffffffff8344e0dc)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8345a9de)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:get_compacted_size
  - arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct
  - arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct
  - arch/x86/kernel/fpu/xstate.c:__xstate_dump_leaves
  - arch/x86/kernel/fpu/xstate.c:xfeature_size
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8105bdd6)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8105cbe3)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8105ceb0)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105dfa2)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff8345df96)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810743e6)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff83461eb3)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8346209a)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346c5e0)
Location: arch/x86/include/asm/processor.h:610
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
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
In arch/x86/coco/tdx/tdx.c (ffffffff83e643fc)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_early_init
```
```
In arch/x86/events/intel/pt.c (ffffffff83e695b2)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff83e7ad2d)
Location: arch/x86/include/asm/cpuid.h:82
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81069d96)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8106af63)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8106b262)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106c534)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff83e7efb0)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81084616)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff83e840dd)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff83e8427d)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e9101f)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
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
In arch/x86/coco/tdx/tdx.c (ffffffff83684a2c)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_early_init
```
```
In arch/x86/events/intel/core.c (ffffffff8101330a)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/events/intel/pt.c (ffffffff83689f42)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/xen/time.c (ffffffff8368b740)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8369d38d)
Location: arch/x86/include/asm/cpuid.h:82
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106b6b6)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff8106c8d3)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8106cbe2)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106dec7)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff836a1d00)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81086bc6)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
  - arch/x86/kernel/cpu/resctrl/core.c:__rdt_get_mem_config_amd
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff836a762d)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff836a77cd)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b49ef)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
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
In arch/x86/coco/tdx/tdx.c (ffffffff838b3c38)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_early_init
```
```
In arch/x86/events/intel/core.c (ffffffff8101a6d9)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/events/intel/pt.c (ffffffff838b9aa2)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/xen/time.c (ffffffff838bb300)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff838ccf4d)
Location: arch/x86/include/asm/cpuid.h:82
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81072b4a)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81073b23)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff81073dff)
Location: arch/x86/include/asm/cpuid.h:82
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
In arch/x86/kernel/cpu/common.c (ffffffff81075147)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff838d1e00)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108dae6)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff838d7b6d)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff838d7d0d)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e537f)
Location: arch/x86/include/asm/cpuid.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
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
In arch/x86/events/intel/pt.c (ffffffff82890b18)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8289c1b6)
Location: arch/x86/include/asm/processor.h:599
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045495)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81045d11)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff81045f2c)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104688b)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff8289de95)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828a0ea0)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
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
In arch/x86/events/intel/pt.c (ffffffff8288ea01)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8289443e)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct
  - arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81034d46)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_hygon_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff810350ef)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8103522c)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81035a46)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff8289609e)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82898e7f)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
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
In arch/x86/events/intel/pt.c (ffffffff828a3b18)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828af179)
Location: arch/x86/include/asm/processor.h:599
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810452d5)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81045b51)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff81045d6c)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810466cb)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff828b0e58)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828b3e63)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
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
In arch/x86/events/intel/pt.c (ffffffff828a3b2c)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828af1a7)
Location: arch/x86/include/asm/processor.h:599
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810466d5)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
```
In arch/x86/kernel/cpu/scattered.c (ffffffff81046f51)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features
```
```
In arch/x86/kernel/cpu/topology.c (ffffffff8104716c)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology
  - arch/x86/kernel/cpu/topology.c:detect_extended_topology_early
  - arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047acb)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:detect_num_cpu_cores
```
```
In arch/x86/kernel/cpu/intel_pconfig.c (ffffffff828b0e86)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828b3e91)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bbd4e)
Location: arch/x86/include/asm/processor.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
```
</details>
</li>
</ul>

## Differences
