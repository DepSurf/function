# Function: <code>of_cpu_device_node_get</code>

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
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct device_node *of_cpu_device_node_get(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (ffff800010b1b618)
Location: include/linux/of_device.h:49
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq-dt-platdev.c (ffff8000114a1ee4)
Location: include/linux/of_device.h:49
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init
```
```
In drivers/cpuidle/dt_idle_states.c (ffff800010b2a28c)
Location: include/linux/of_device.h:49
Inline: True
Inline callers:
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
```
```
In drivers/cpuidle/cpuidle-psci.c (ffff800010b2a79c)
Location: include/linux/of_device.h:49
Inline: True
Direct callers:
  - drivers/cpuidle/cpuidle-psci.c:psci_idle_init
  - drivers/cpuidle/cpuidle-psci.c:psci_idle_init
```
```
In drivers/of/base.c (ffff800010b6c310)
Location: include/linux/of_device.h:49
Inline: True
Inline callers:
  - drivers/of/base.c:of_find_last_cache_level
  - drivers/of/base.c:of_find_last_cache_level
  - drivers/of/base.c:of_cpu_node_to_id
  - drivers/of/base.c:of_cpu_node_to_id
```
**Symbols:**

```
ffff800010b2a79c-ffff800010b2a7d8: of_cpu_device_node_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct device_node *of_cpu_device_node_get(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/cpuidle.c (c15057fc)
Location: include/linux/of_device.h:49
Inline: True
Inline callers:
  - arch/arm/kernel/cpuidle.c:arm_cpuidle_init
```
```
In drivers/soc/qcom/spm.c (c0938020)
Location: include/linux/of_device.h:49
Inline: True
Inline callers:
  - drivers/soc/qcom/spm.c:spm_dev_probe
```
```
In drivers/opp/of.c (c0bf5ce0)
Location: include/linux/of_device.h:49
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq-dt-platdev.c (c15a3f04)
Location: include/linux/of_device.h:49
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init
```
```
In drivers/cpufreq/tegra124-cpufreq.c (c0c00dec)
Location: include/linux/of_device.h:49
Inline: True
Inline callers:
  - drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe
```
```
In drivers/cpuidle/dt_idle_states.c (c0c05850)
Location: include/linux/of_device.h:49
Inline: True
Inline callers:
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
```
```
In drivers/cpuidle/cpuidle-psci.c (c0c0600c)
Location: include/linux/of_device.h:49
Inline: True
Direct callers:
  - drivers/cpuidle/cpuidle-psci.c:psci_idle_init
  - drivers/cpuidle/cpuidle-psci.c:psci_idle_init
```
```
In drivers/of/base.c (c0c4f57c)
Location: include/linux/of_device.h:49
Inline: True
Inline callers:
  - drivers/of/base.c:of_find_last_cache_level
  - drivers/of/base.c:of_find_last_cache_level
  - drivers/of/base.c:of_cpu_node_to_id
  - drivers/of/base.c:of_cpu_node_to_id
```
**Symbols:**

```
c0c0600c-c0c06040: of_cpu_device_node_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (c000000000c0d5cc)
Location: include/linux/of_device.h:49
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
```
```
In drivers/of/base.c (c000000000c46958)
Location: include/linux/of_device.h:49
Inline: True
Inline callers:
  - drivers/of/base.c:of_find_last_cache_level
  - drivers/of/base.c:of_find_last_cache_level
  - drivers/of/base.c:of_cpu_node_to_id
  - drivers/of/base.c:of_cpu_node_to_id
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/cacheinfo.c (ffffffe0000b75a2)
Location: include/linux/of_device.h:49
Inline: True
Inline callers:
  - arch/riscv/kernel/cacheinfo.c:_populate_cache_leaves
  - arch/riscv/kernel/cacheinfo.c:_populate_cache_leaves
  - arch/riscv/kernel/cacheinfo.c:_init_cache_level
  - arch/riscv/kernel/cacheinfo.c:_init_cache_level
```
```
In drivers/opp/of.c (ffffffe00070371e)
Location: include/linux/of_device.h:49
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
```
```
In drivers/of/base.c (ffffffe000721504)
Location: include/linux/of_device.h:49
Inline: True
Inline callers:
  - drivers/of/base.c:of_find_last_cache_level
  - drivers/of/base.c:of_find_last_cache_level
  - drivers/of/base.c:of_cpu_node_to_id
  - drivers/of/base.c:of_cpu_node_to_id
```
</details>
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
<b>Arch</b>
<ul>
</ul>
