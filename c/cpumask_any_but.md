# Function: <code>cpumask_any_but</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff813e92c0)
Location: lib/cpumask.c:34
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:flush_tlb_current_task
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:flush_tlb_page
  - mm/rmap.c:try_to_unmap_flush
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff813e92c0-ffffffff813e92fb: cpumask_any_but (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8142f3f0)
Location: lib/cpumask.c:34
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/mm/tlb.c:flush_tlb_page
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:flush_tlb_current_task
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_flush
```
**Symbols:**

```
ffffffff8142f3f0-ffffffff8142f42f: cpumask_any_but (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8144b570)
Location: lib/cpumask.c:34
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/mm/tlb.c:flush_tlb_page
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:flush_tlb_current_task
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_flush
```
**Symbols:**

```
ffffffff8144b570-ffffffff8144b5b4: cpumask_any_but (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff818ebbb0)
Location: lib/cpumask.c:34
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff818ebbb0-ffffffff818ebbf2: cpumask_any_but (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81971b90)
Location: lib/cpumask.c:51
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff81971b90-ffffffff81971bd2: cpumask_any_but (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff819cdf20)
Location: lib/cpumask.c:52
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff819cdf20-ffffffff819cdf62: cpumask_any_but (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a073e0)
Location: lib/cpumask.c:52
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff81a073e0-ffffffff81a07422: cpumask_any_but (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a76d50)
Location: lib/cpumask.c:53
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff81a76d50-ffffffff81a76d8c: cpumask_any_but (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81aae160)
Location: lib/cpumask.c:53
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff81aae160-ffffffff81aae19c: cpumask_any_but (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff815e7e20)
Location: lib/cpumask.c:53
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff815e7e20-ffffffff815e7e5c: cpumask_any_but (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8160cf80)
Location: lib/cpumask.c:53
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff8160cf80-ffffffff8160cfbc: cpumask_any_but (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff815f07d0)
Location: lib/cpumask.c:53
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff815f07d0-ffffffff815f0814: cpumask_any_but (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8165d8b0)
Location: lib/cpumask.c:53
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff8165d8b0-ffffffff8165d8f4: cpumask_any_but (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81776f20)
Location: lib/cpumask.c:53
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
  - mm/rmap.c:try_to_unmap_one
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
**Symbols:**

```
ffffffff81776f20-ffffffff81776f78: cpumask_any_but (STB_GLOBAL)
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
In arch/x86/events/intel/uncore.c (ffffffff81023aa6)
Location: include/linux/cpumask.h:339
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81045588)
Location: include/linux/cpumask.h:339
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/cpumask.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109c46d)
Location: include/linux/cpumask.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
```
```
In arch/x86/mm/tlb.c (ffffffff810c990c)
Location: include/linux/cpumask.h:339
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In kernel/irq/cpuhotplug.c (ffffffff811a29ac)
Location: include/linux/cpumask.h:339
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In mm/rmap.c (ffffffff813d88df)
Location: include/linux/cpumask.h:339
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81b54190)
Location: include/linux/cpumask.h:339
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
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
In arch/x86/events/intel/uncore.c (ffffffff810237d8)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/hyperv/hv_init.c (ffffffff810456c8)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
```
```
In arch/x86/kernel/tsc.c (ffffffff8105ebe6)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109f5ad)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
```
```
In arch/x86/mm/tlb.c (ffffffff810ccf87)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_down_maps_locked
```
```
In kernel/irq/cpuhotplug.c (ffffffff811b48ac)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In mm/rmap.c (ffffffff8140ac7a)
Location: include/linux/cpumask.h:379
Inline: True
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1af65)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81ba76e8)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
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
In arch/x86/events/intel/uncore.c (ffffffff81029907)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8104bd98)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
```
```
In arch/x86/kernel/tsc.c (ffffffff81065c96)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a6a3d)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
```
```
In arch/x86/mm/tlb.c (ffffffff810d5657)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In kernel/irq/cpuhotplug.c (ffffffff811c472c)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In mm/rmap.c (ffffffff8143a4bf)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b70a95)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81bfb998)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffff800010d844a8)
Location: lib/cpumask.c:53
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - drivers/soc/fsl/qbman/bman_portal.c:bman_offline_cpu
  - drivers/soc/fsl/qbman/qman_portal.c:qman_offline_cpu
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_offline_cpu
  - drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_offline_cpu
  - drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu
```
**Symbols:**

```
ffff800010d844a8-ffff800010d84508: cpumask_any_but (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (c0e7f9d4)
Location: lib/cpumask.c:53
Inline: False
Direct callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_offline_cpu
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_offline_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
c0e7f9d4-c0e7fa28: cpumask_any_but (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (c000000000ec3680)
Location: lib/cpumask.c:53
Inline: False
Direct callers:
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_offline
  - arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_offline
```
**Symbols:**

```
c000000000ec3680-c000000000ec3710: cpumask_any_but (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffe0008ae9ee)
Location: lib/cpumask.c:53
Inline: False
```
**Symbols:**

```
ffffffe0008ae9ee-ffffffe0008aea38: cpumask_any_but (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a4cfb0)
Location: lib/cpumask.c:53
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff81a4cfb0-ffffffff81a4cfec: cpumask_any_but (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a0a0e0)
Location: lib/cpumask.c:53
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff81a0a0e0-ffffffff81a0a11c: cpumask_any_but (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81ab93a0)
Location: lib/cpumask.c:53
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff81ab93a0-ffffffff81ab93dc: cpumask_any_but (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cpumask_any_but(const struct cpumask *mask, unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81ac57f0)
Location: lib/cpumask.c:53
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff81ac57f0-ffffffff81ac582c: cpumask_any_but (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
