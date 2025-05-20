# Function: <code>of_get_cpu_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (0)
Location: include/linux/of.h:562
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (0)
Location: include/linux/of.h:586
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (0)
Location: include/linux/of.h:706
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (0)
Location: include/linux/of.h:732
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (0)
Location: include/linux/of.h:729
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (0)
Location: include/linux/of.h:738
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (0)
Location: include/linux/of.h:757
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (0)
Location: include/linux/of.h:757
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (0)
Location: include/linux/of.h:757
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (0)
Location: include/linux/of.h:759
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (0)
Location: include/linux/of.h:766
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (0)
Location: include/linux/of.h:781
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (0)
Location: include/linux/of.h:781
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (0)
Location: include/linux/of.h:623
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (0)
Location: include/linux/of.h:621
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (0)
Location: include/linux/of.h:633
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (0)
Location: include/linux/of.h:632
Inline: True
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
struct device_node *of_get_cpu_node(int cpu, unsigned int *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b6b138)
Location: drivers/of/base.c:442
Inline: False
Direct callers:
  - arch/arm64/kernel/cpu_ops.c:cpu_read_ops
  - arch/arm64/kernel/smp_spin_table.c:smp_spin_table_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection
  - drivers/soc/bcm/brcmstb/biuctrl.c:brcmstb_biuctrl_init
  - drivers/base/cpu.c:register_cpu
  - drivers/thermal/cpu_cooling.c:of_cpufreq_cooling_register
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
  - drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/of/base.c:of_find_last_cache_level
  - drivers/of/base.c:of_cpu_node_to_id
```
**Symbols:**

```
ffff800010b6b138-ffff800010b6b1a0: of_get_cpu_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device_node *of_get_cpu_node(int cpu, unsigned int *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4e544)
Location: drivers/of/base.c:442
Inline: False
Direct callers:
  - arch/arm/kernel/cpuidle.c:arm_cpuidle_init
  - arch/arm/kernel/topology.c:init_cpu_topology
  - arch/arm/mach-meson/platsmp.c:meson_smp_get_core_reset
  - arch/arm/mach-mvebu/platsmp.c:get_cpu_clk
  - arch/arm/mach-qcom/platsmp.c:kpssv2_release_secondary
  - arch/arm/mach-qcom/platsmp.c:kpssv1_release_secondary
  - arch/arm/mach-rockchip/platsmp.c:pmu_set_power_domain
  - arch/arm/mach-vexpress/platsmp.c:vexpress_smp_init_ops
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection
  - drivers/bus/arm-cci.c:cci_probe_ports
  - drivers/soc/qcom/spm.c:spm_dev_probe
  - drivers/soc/renesas/r9a06g032-smp.c:r9a06g032_smp_prepare_cpus
  - drivers/base/cpu.c:register_cpu
  - drivers/thermal/cpu_cooling.c:of_cpufreq_cooling_register
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
  - drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init
  - drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/of/base.c:of_find_last_cache_level
  - drivers/of/base.c:of_cpu_node_to_id
```
**Symbols:**

```
c0c4e544-c0c4e5a0: of_get_cpu_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device_node *of_get_cpu_node(int cpu, unsigned int *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c44c70)
Location: drivers/of/base.c:442
Inline: False
Direct callers:
  - arch/powerpc/kernel/sysfs.c:register_cpu_online
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_offline
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online
  - arch/powerpc/kernel/prom.c:cpu_to_chip_id
  - arch/powerpc/kernel/mce.c:init_debug_trig_function
  - arch/powerpc/kernel/smp.c:cpu_to_l2cache
  - arch/powerpc/kernel/smp.c:cpu_to_core_id
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/mm/numa.c:parse_numa_properties
  - arch/powerpc/mm/numa.c:numa_setup_cpu
  - arch/powerpc/sysdev/xics/xics-common.c:xics_update_irq_servers
  - arch/powerpc/sysdev/xive/common.c:xive_prepare_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/thermal/cpu_cooling.c:of_cpufreq_cooling_register
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
  - drivers/of/base.c:of_find_last_cache_level
  - drivers/of/base.c:of_cpu_node_to_id
```
**Symbols:**

```
c000000000c44c70-c000000000c44d04: of_get_cpu_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device_node *of_get_cpu_node(int cpu, unsigned int *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe0007206c2)
Location: drivers/of/base.c:442
Inline: False
Direct callers:
  - arch/riscv/kernel/cpu.c:c_show
  - arch/riscv/kernel/cacheinfo.c:_populate_cache_leaves
  - arch/riscv/kernel/cacheinfo.c:_init_cache_level
  - drivers/base/cpu.c:register_cpu
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
  - drivers/of/base.c:of_find_last_cache_level
  - drivers/of/base.c:of_cpu_node_to_id
```
**Symbols:**

```
ffffffe0007206c2-ffffffe000720712: of_get_cpu_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (0)
Location: include/linux/of.h:757
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (0)
Location: include/linux/of.h:757
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (0)
Location: include/linux/of.h:757
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (0)
Location: include/linux/of.h:757
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
