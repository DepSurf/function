# Function: <code>dev_pm_opp_put</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/pm_opp.h:199
Inline: True
```
```
In drivers/devfreq/governor_passive.c (0)
Location: include/linux/pm_opp.h:199
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dev_pm_opp_put(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d3d30)
Location: drivers/opp/core.c:921
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff817d3d30-ffffffff817d3db6: dev_pm_opp_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dev_pm_opp_put(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181cb20)
Location: drivers/opp/core.c:928
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff8181cb20-ffffffff8181cba6: dev_pm_opp_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dev_pm_opp_put(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818486e0)
Location: drivers/opp/core.c:1027
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_remove_all_static
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff818486e0-ffffffff81848722: dev_pm_opp_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dev_pm_opp_put(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8188b750)
Location: drivers/opp/core.c:1101
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_remove_all_static
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff8188b750-ffffffff8188b792: dev_pm_opp_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dev_pm_opp_put(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818bd820)
Location: drivers/opp/core.c:1150
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_remove_all_static
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff818bd820-ffffffff818bd862: dev_pm_opp_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81990fdd)
Location: drivers/opp/core.c:1213
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:set_freq_table
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff8198dfa0-ffffffff8198e01f: dev_pm_opp_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff819931cd)
Location: drivers/opp/core.c:1282
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:set_freq_table
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff81991b60-ffffffff81991bdf: dev_pm_opp_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81977ab9)
Location: drivers/opp/core.c:1439
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff81975fc0-ffffffff8197603f: dev_pm_opp_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81a209b9)
Location: drivers/opp/core.c:1449
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff81a1ed60-ffffffff81a1eddf: dev_pm_opp_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81b895fb)
Location: drivers/opp/core.c:1594
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp
  - drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp
```
**Symbols:**

```
ffffffff81b87770-ffffffff81b877f8: dev_pm_opp_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d28e0b)
Location: drivers/opp/core.c:1566
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp
  - drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp
```
**Symbols:**

```
ffffffff81d27270-ffffffff81d272f8: dev_pm_opp_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d91fab)
Location: drivers/opp/core.c:1574
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp
  - drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp
```
**Symbols:**

```
ffffffff81d90420-ffffffff81d904a8: dev_pm_opp_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e498db)
Location: drivers/opp/core.c:1684
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
Direct callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_gen_tables
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp
  - drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp
```
**Symbols:**

```
ffffffff81e47a80-ffffffff81e47b08: dev_pm_opp_put (STB_GLOBAL)
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
void dev_pm_opp_put(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b185b0)
Location: drivers/opp/core.c:1150
Inline: False
Direct callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_remove_all_static
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/opp/of.c:of_get_required_opp_performance_state
  - drivers/opp/of.c:_of_opp_free_required_opps
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffff800010b185b0-ffff800010b18604: dev_pm_opp_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dev_pm_opp_put(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf3550)
Location: drivers/opp/core.c:1150
Inline: False
Direct callers:
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-dfll.c:dfll_calculate_rate_request
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:get_voltage
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_remove_all_static
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/opp/of.c:of_get_required_opp_performance_state
  - drivers/opp/of.c:_of_opp_free_required_opps
  - drivers/cpufreq/omap-cpufreq.c:omap_target
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:find_available_max_freq
  - drivers/devfreq/devfreq.c:find_available_min_freq
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
  - drivers/devfreq/exynos-bus.c:exynos_bus_target
```
**Symbols:**

```
c0bf3550-c0bf359c: dev_pm_opp_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dev_pm_opp_put(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c09c40)
Location: drivers/opp/core.c:1150
Inline: False
Direct callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:get_voltage
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_remove_all_static
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/opp/of.c:of_get_required_opp_performance_state
  - drivers/opp/of.c:_of_opp_free_required_opps
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:find_available_max_freq
  - drivers/devfreq/devfreq.c:find_available_min_freq
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
c000000000c09c40-c000000000c09cb8: dev_pm_opp_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dev_pm_opp_put(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000701174)
Location: drivers/opp/core.c:1150
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:get_voltage
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_remove_all_static
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/of.c:of_get_required_opp_performance_state
  - drivers/opp/of.c:_of_opp_free_required_opps
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:find_available_max_freq
  - drivers/devfreq/devfreq.c:find_available_min_freq
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffe000701174-ffffffe0007011c8: dev_pm_opp_put (STB_GLOBAL)
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
void dev_pm_opp_put(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81861f40)
Location: drivers/opp/core.c:1150
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_remove_all_static
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff81861f40-ffffffff81861f82: dev_pm_opp_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dev_pm_opp_put(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182abf0)
Location: drivers/opp/core.c:1150
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_remove_all_static
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff8182abf0-ffffffff8182ac32: dev_pm_opp_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dev_pm_opp_put(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b2cd0)
Location: drivers/opp/core.c:1150
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_remove_all_static
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff818b2cd0-ffffffff818b2d12: dev_pm_opp_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dev_pm_opp_put(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818cef80)
Location: drivers/opp/core.c:1150
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_set_cur_state
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_remove_all_static
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/cpu.c:dev_pm_opp_init_cpufreq_table
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff818cef80-ffffffff818cefc2: dev_pm_opp_put (STB_GLOBAL)
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
