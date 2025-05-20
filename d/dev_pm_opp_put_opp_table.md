# Function: <code>dev_pm_opp_put_opp_table</code>

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
void dev_pm_opp_put_opp_table(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d3c20)
Location: drivers/opp/core.c:886
Inline: False
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_clock_latency
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
```
**Symbols:**

```
ffffffff817d3c20-ffffffff817d3cec: dev_pm_opp_put_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181c940)
Location: drivers/opp/core.c:893
Inline: False
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_put_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_put
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_clock_latency
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
```
**Symbols:**

```
ffffffff8181c940-ffffffff8181ca15: dev_pm_opp_put_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81848450)
Location: drivers/opp/core.c:979
Inline: False
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_put_genpd_virt_dev
  - drivers/opp/core.c:dev_pm_opp_set_genpd_virt_dev
  - drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_put_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_clock_latency
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
```
**Symbols:**

```
ffffffff81848450-ffffffff8184857b: dev_pm_opp_put_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1053
Inline: False
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_put_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_clock_latency
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
```
**Symbols:**

```
ffffffff8188d524-ffffffff8188d537: dev_pm_opp_put_opp_table.cold (STB_LOCAL)
ffffffff8188b4a0-ffffffff8188b5b5: dev_pm_opp_put_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818bd580)
Location: drivers/opp/core.c:1102
Inline: False
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_put_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_clock_latency
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
```
**Symbols:**

```
ffffffff818bd580-ffffffff818bd69c: dev_pm_opp_put_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81991111)
Location: drivers/opp/core.c:1165
Inline: True
Inline callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_put_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
```
**Symbols:**

```
ffffffff8198df70-ffffffff8198dfa0: dev_pm_opp_put_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81992d06)
Location: drivers/opp/core.c:1247
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_put_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_bw
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
```
**Symbols:**

```
ffffffff81991b30-ffffffff81991b60: dev_pm_opp_put_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81976e6e)
Location: drivers/opp/core.c:1404
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:devm_pm_opp_register_set_opp_helper
  - drivers/opp/core.c:devm_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:devm_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
**Symbols:**

```
ffffffff81976210-ffffffff81976240: dev_pm_opp_put_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81a1fc5c)
Location: drivers/opp/core.c:1414
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:devm_pm_opp_register_set_opp_helper
  - drivers/opp/core.c:devm_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:devm_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
**Symbols:**

```
ffffffff81a1efb0-ffffffff81a1efe0: dev_pm_opp_put_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81b887ed)
Location: drivers/opp/core.c:1559
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:devm_pm_opp_register_set_opp_helper
  - drivers/opp/core.c:devm_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:devm_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_bw_floor
  - drivers/opp/core.c:dev_pm_opp_find_bw_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/devfreq/devfreq.c:devfreq_dev_release
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff81b879d0-ffffffff81b87a09: dev_pm_opp_put_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d2853d)
Location: drivers/opp/core.c:1531
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:_opp_clear_config
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_find_key
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/devfreq/devfreq.c:devfreq_dev_release
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff81d274f0-ffffffff81d27529: dev_pm_opp_put_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d916da)
Location: drivers/opp/core.c:1539
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:_opp_clear_config
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_find_key
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/devfreq/devfreq.c:devfreq_dev_release
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff81d90690-ffffffff81d906c9: dev_pm_opp_put_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e4934c)
Location: drivers/opp/core.c:1649
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add_dynamic
  - drivers/opp/core.c:_opp_clear_config
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_find_key
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/devfreq/devfreq.c:devfreq_dev_release
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff81e47cf0-ffffffff81e47d29: dev_pm_opp_put_opp_table (STB_GLOBAL)
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
void dev_pm_opp_put_opp_table(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b18278)
Location: drivers/opp/core.c:1102
Inline: False
Direct callers:
  - drivers/base/power/domain.c:of_genpd_del_provider
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper
  - drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_put_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_clock_latency
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/of.c:of_get_required_opp_performance_state
  - drivers/opp/of.c:dev_pm_opp_of_add_table_indexed
  - drivers/opp/of.c:dev_pm_opp_of_add_table
```
**Symbols:**

```
ffff800010b18278-ffff800010b183b4: dev_pm_opp_put_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf3250)
Location: drivers/opp/core.c:1102
Inline: False
Direct callers:
  - drivers/base/power/domain.c:of_genpd_del_provider
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_put_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_clock_latency
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/of.c:of_get_required_opp_performance_state
  - drivers/opp/of.c:dev_pm_opp_of_add_table_indexed
  - drivers/opp/of.c:dev_pm_opp_of_add_table
  - drivers/opp/of.c:_opp_table_free_required_tables
```
**Symbols:**

```
c0bf3250-c0bf336c: dev_pm_opp_put_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c09840)
Location: drivers/opp/core.c:1102
Inline: False
Direct callers:
  - drivers/base/power/domain.c:of_genpd_del_provider
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_put_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_clock_latency
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/of.c:of_get_required_opp_performance_state
  - drivers/opp/of.c:dev_pm_opp_of_add_table_indexed
  - drivers/opp/of.c:dev_pm_opp_of_add_table
  - drivers/opp/of.c:_opp_table_free_required_tables
```
**Symbols:**

```
c000000000c09840-c000000000c09a14: dev_pm_opp_put_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000700ee8)
Location: drivers/opp/core.c:1102
Inline: False
Direct callers:
  - drivers/base/power/domain.c:of_genpd_del_provider
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_put_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_clock_latency
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/of.c:of_get_required_opp_performance_state
  - drivers/opp/of.c:dev_pm_opp_of_add_table_indexed
  - drivers/opp/of.c:dev_pm_opp_of_add_table
  - drivers/opp/of.c:_opp_table_free_required_tables
```
**Symbols:**

```
ffffffe000700ee8-ffffffe000700ff4: dev_pm_opp_put_opp_table (STB_GLOBAL)
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
void dev_pm_opp_put_opp_table(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81861ca0)
Location: drivers/opp/core.c:1102
Inline: False
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_put_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_clock_latency
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
```
**Symbols:**

```
ffffffff81861ca0-ffffffff81861dbc: dev_pm_opp_put_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182a950)
Location: drivers/opp/core.c:1102
Inline: False
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_put_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_clock_latency
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
```
**Symbols:**

```
ffffffff8182a950-ffffffff8182aa6c: dev_pm_opp_put_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b2a30)
Location: drivers/opp/core.c:1102
Inline: False
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_put_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_clock_latency
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
```
**Symbols:**

```
ffffffff818b2a30-ffffffff818b2b4c: dev_pm_opp_put_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dev_pm_opp_put_opp_table(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818cece0)
Location: drivers/opp/core.c:1102
Inline: False
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_unregister_set_opp_helper
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_regulators
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_put_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_put_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_clock_latency
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
```
**Symbols:**

```
ffffffff818cece0-ffffffff818cedfc: dev_pm_opp_put_opp_table (STB_GLOBAL)
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
