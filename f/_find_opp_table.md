# Function: <code>_find_opp_table</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *_find_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d41a0)
Location: drivers/opp/core.c:76
Inline: True
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_clock_latency
  - drivers/opp/core.c:dev_pm_opp_get_regulator
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
```
**Symbols:**

```
ffffffff817d41a0-ffffffff817d4204: _find_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *_find_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181cf10)
Location: drivers/opp/core.c:74
Inline: True
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_clock_latency
  - drivers/opp/core.c:dev_pm_opp_get_regulator
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
```
**Symbols:**

```
ffffffff8181cf10-ffffffff8181cf70: _find_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *_find_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81848c50)
Location: drivers/opp/core.c:79
Inline: True
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
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
ffffffff81848c50-ffffffff81848cb0: _find_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct opp_table *_find_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff8188d5fe)
Location: drivers/opp/core.c:76
Inline: True
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
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
ffffffff8188d5fe-ffffffff8188d61d: _find_opp_table.cold (STB_LOCAL)
ffffffff8188bb20-ffffffff8188bb6e: _find_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct opp_table *_find_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff818bf7ec)
Location: drivers/opp/core.c:76
Inline: True
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
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
ffffffff818bf7ec-ffffffff818bf80b: _find_opp_table.cold (STB_LOCAL)
ffffffff818bdc00-ffffffff818bdc4e: _find_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct opp_table *_find_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81991095)
Location: drivers/opp/core.c:76
Inline: True
Inline callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
```
**Symbols:**

```
ffffffff81991734-ffffffff81991753: _find_opp_table.cold (STB_LOCAL)
ffffffff8198fd60-ffffffff8198fdb0: _find_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct opp_table *_find_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81992c75)
Location: drivers/opp/core.c:76
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_bw
  - drivers/opp/core.c:dev_pm_opp_set_bw
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
```
**Symbols:**

```
ffffffff81c294f2-ffffffff81c29511: _find_opp_table.cold (STB_LOCAL)
ffffffff81993d00-ffffffff81993d50: _find_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct opp_table *_find_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81976dd5)
Location: drivers/opp/core.c:80
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
```
**Symbols:**

```
ffffffff81c1b546-ffffffff81c1b565: _find_opp_table.cold (STB_LOCAL)
ffffffff81978020-ffffffff81978070: _find_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct opp_table *_find_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81a1fbb5)
Location: drivers/opp/core.c:80
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
```
**Symbols:**

```
ffffffff81d2b703-ffffffff81d2b722: _find_opp_table.cold (STB_LOCAL)
ffffffff81a20f70-ffffffff81a20fc0: _find_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct opp_table *_find_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81b88745)
Location: drivers/opp/core.c:80
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_bw_floor
  - drivers/opp/core.c:dev_pm_opp_find_bw_floor
  - drivers/opp/core.c:dev_pm_opp_find_bw_ceil
  - drivers/opp/core.c:dev_pm_opp_find_bw_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
```
**Symbols:**

```
ffffffff81ef7921-ffffffff81ef7940: _find_opp_table.cold (STB_LOCAL)
ffffffff81b89ea0-ffffffff81b89ef7: _find_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *_find_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d28495)
Location: drivers/opp/core.c:84
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_find_key
  - drivers/opp/core.c:_find_key
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
```
**Symbols:**

```
ffffffff81d294e0-ffffffff81d2955a: _find_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *_find_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d91635)
Location: drivers/opp/core.c:81
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_find_key
  - drivers/opp/core.c:_find_key
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
```
**Symbols:**

```
ffffffff81d92680-ffffffff81d926fa: _find_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *_find_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e492c5)
Location: drivers/opp/core.c:81
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_find_key
  - drivers/opp/core.c:_find_key
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
Direct callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
```
**Symbols:**

```
ffffffff81e49fb0-ffffffff81e4a02a: _find_opp_table (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *_find_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b18918)
Location: drivers/opp/core.c:76
Inline: True
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
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
ffff800010b18918-ffff800010b18994: _find_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *_find_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf383c)
Location: drivers/opp/core.c:76
Inline: True
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
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
c0bf383c-c0bf38a4: _find_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *_find_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0a130)
Location: drivers/opp/core.c:76
Inline: True
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
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
c000000000c0a130-c000000000c0a1d0: _find_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *_find_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe0007014ce)
Location: drivers/opp/core.c:76
Inline: True
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
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
ffffffe0007014ce-ffffffe000701540: _find_opp_table (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct opp_table *_find_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81863f0c)
Location: drivers/opp/core.c:76
Inline: True
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
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
ffffffff81863f0c-ffffffff81863f2b: _find_opp_table.cold (STB_LOCAL)
ffffffff81862320-ffffffff8186236e: _find_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct opp_table *_find_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff8182cbbc)
Location: drivers/opp/core.c:76
Inline: True
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
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
ffffffff8182cbbc-ffffffff8182cbdb: _find_opp_table.cold (STB_LOCAL)
ffffffff8182afd0-ffffffff8182b01e: _find_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct opp_table *_find_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff818b4c9c)
Location: drivers/opp/core.c:76
Inline: True
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
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
ffffffff818b4c9c-ffffffff818b4cbb: _find_opp_table.cold (STB_LOCAL)
ffffffff818b30b0-ffffffff818b30fe: _find_opp_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct opp_table *_find_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff818d0f4c)
Location: drivers/opp/core.c:76
Inline: True
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
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
ffffffff818d0f4c-ffffffff818d0f6b: _find_opp_table.cold (STB_LOCAL)
ffffffff818cf360-ffffffff818cf3ae: _find_opp_table (STB_GLOBAL)
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
