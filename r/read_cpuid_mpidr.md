# Function: <code>read_cpuid_mpidr</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/setup.c (ffff800011433f88)
Location: arch/arm64/include/asm/cputype.h:190
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:smp_setup_processor_id
```
```
In arch/arm64/kernel/smp.c (ffff80001009c200)
Location: arch/arm64/include/asm/cputype.h:190
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:secondary_start_kernel
```
```
In arch/arm64/kernel/topology.c (ffff800011435e1c)
Location: arch/arm64/include/asm/cputype.h:190
Inline: True
Inline callers:
  - arch/arm64/kernel/topology.c:parse_acpi_topology
  - arch/arm64/kernel/topology.c:store_cpu_topology
```
```
In virt/kvm/arm/arm.c (ffff8000100c594c)
Location: arch/arm64/include/asm/cputype.h:190
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (ffff800010b96a14)
Location: arch/arm64/include/asm/cputype.h:190
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_online_cpu
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_online_cpu
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b99888)
Location: arch/arm64/include/asm/cputype.h:190
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2cache_pmu_online_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/setup.c (c1504428)
Location: arch/arm/include/asm/cputype.h:256
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:smp_setup_processor_id
```
```
In arch/arm/kernel/devtree.c (c150619c)
Location: arch/arm/include/asm/cputype.h:256
Inline: True
Inline callers:
  - arch/arm/kernel/devtree.c:arm_dt_init_cpu_maps
```
```
In arch/arm/kernel/topology.c (c0319a54)
Location: arch/arm/include/asm/cputype.h:256
Inline: True
Inline callers:
  - arch/arm/kernel/topology.c:store_cpu_topology
```
```
In arch/arm/common/mcpm_entry.c (c150baa0)
Location: arch/arm/include/asm/cputype.h:256
Inline: True
Inline callers:
  - arch/arm/common/mcpm_entry.c:nocache_trampoline
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_powered_up
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_suspend
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_sync_init
```
```
In arch/arm/common/mcpm_platsmp.c (c032621c)
Location: arch/arm/include/asm/cputype.h:256
Inline: True
Inline callers:
  - arch/arm/common/mcpm_platsmp.c:mcpm_cpu_die
```
```
In arch/arm/mach-exynos/suspend.c (c032dafc)
Location: arch/arm/include/asm/cputype.h:256
Inline: True
Inline callers:
  - arch/arm/mach-exynos/suspend.c:exynos5420_cpu_suspend
```
```
In arch/arm/mach-exynos/mcpm-exynos.c (c032eb00)
Location: arch/arm/include/asm/cputype.h:256
Inline: True
Inline callers:
  - arch/arm/mach-exynos/mcpm-exynos.c:exynos_cluster_cache_disable
```
```
In arch/arm/mach-hisi/platmcpm.c (c150cee0)
Location: arch/arm/include/asm/cputype.h:256
Inline: True
Inline callers:
  - arch/arm/mach-hisi/platmcpm.c:hip04_smp_init
```
```
In arch/arm/mach-milbeaut/platsmp.c (c0334d44)
Location: arch/arm/include/asm/cputype.h:256
Inline: True
```
```
In arch/arm/mach-shmobile/pm-rcar-gen2.c (c151a408)
Location: arch/arm/include/asm/cputype.h:256
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
```
```
In arch/arm/mach-vexpress/dcscb.c (c034cd44)
Location: arch/arm/include/asm/cputype.h:256
Inline: True
Inline callers:
  - arch/arm/mach-vexpress/dcscb.c:dcscb_cluster_cache_disable
```
```
In arch/arm/mach-vexpress/tc2_pm.c (c151b398)
Location: arch/arm/include/asm/cputype.h:256
Inline: True
Inline callers:
  - arch/arm/mach-vexpress/tc2_pm.c:tc2_pm_init
  - arch/arm/mach-vexpress/tc2_pm.c:tc2_pm_cluster_cache_disable
```
```
In drivers/soc/samsung/exynos5420-pmu.c (c093a0ac)
Location: arch/arm/include/asm/cputype.h:256
Inline: True
Inline callers:
  - drivers/soc/samsung/exynos5420-pmu.c:exynos5420_powerdown_conf
```
```
In drivers/cpuidle/cpuidle-big_little.c (c0c05d28)
Location: arch/arm/include/asm/cputype.h:256
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-big_little.c:bl_powerdown_finisher
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
