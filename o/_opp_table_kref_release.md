# Function: <code>_opp_table_kref_release</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d3c48)
Location: drivers/opp/core.c:862
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
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
In drivers/opp/core.c (ffffffff8181c968)
Location: drivers/opp/core.c:869
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
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
In drivers/opp/core.c (ffffffff81848484)
Location: drivers/opp/core.c:920
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
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
In drivers/opp/core.c (ffffffff8188b4d4)
Location: drivers/opp/core.c:994
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
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
In drivers/opp/core.c (ffffffff818bd5b4)
Location: drivers/opp/core.c:1043
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void _opp_table_kref_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8198dc20)
Location: drivers/opp/core.c:1126
Inline: False
Direct callers:
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
  - drivers/opp/core.c:dev_pm_opp_put_supported_hw
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
```
**Symbols:**

```
ffffffff8198dc20-ffffffff8198dd6a: _opp_table_kref_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void _opp_table_kref_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff819919e0)
Location: drivers/opp/core.c:1207
Inline: False
Direct callers:
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
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
```
**Symbols:**

```
ffffffff819919e0-ffffffff81991b2a: _opp_table_kref_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void _opp_table_kref_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81976040)
Location: drivers/opp/core.c:1361
Inline: False
Direct callers:
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
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
```
**Symbols:**

```
ffffffff81976040-ffffffff81976204: _opp_table_kref_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void _opp_table_kref_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1371
Inline: False
Direct callers:
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
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
```
**Symbols:**

```
ffffffff81a1ede0-ffffffff81a1efae: _opp_table_kref_release (STB_LOCAL)
ffffffff81d2b1b7-ffffffff81d2b1d2: _opp_table_kref_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void _opp_table_kref_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1516
Inline: False
Direct callers:
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
  - drivers/opp/core.c:dev_pm_opp_find_bw_floor
  - drivers/opp/core.c:dev_pm_opp_find_bw_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
```
**Symbols:**

```
ffffffff81b87800-ffffffff81b879ce: _opp_table_kref_release (STB_LOCAL)
ffffffff81ef73a0-ffffffff81ef73bb: _opp_table_kref_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void _opp_table_kref_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1488
Inline: False
Direct callers:
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
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_find_key
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
```
**Symbols:**

```
ffffffff81d27310-ffffffff81d274de: _opp_table_kref_release (STB_LOCAL)
ffffffff820a8a18-ffffffff820a8a33: _opp_table_kref_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void _opp_table_kref_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d904c0)
Location: drivers/opp/core.c:1504
Inline: False
Direct callers:
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
```
**Symbols:**

```
ffffffff81d904c0-ffffffff81d90675: _opp_table_kref_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void _opp_table_kref_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e47b20)
Location: drivers/opp/core.c:1615
Inline: False
Direct callers:
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
```
**Symbols:**

```
ffffffff81e47b20-ffffffff81e47cd5: _opp_table_kref_release (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b182c8)
Location: drivers/opp/core.c:1043
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf327c)
Location: drivers/opp/core.c:1043
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c098b0)
Location: drivers/opp/core.c:1043
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000700f32)
Location: drivers/opp/core.c:1043
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
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
In drivers/opp/core.c (ffffffff81861cd4)
Location: drivers/opp/core.c:1043
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
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
In drivers/opp/core.c (ffffffff8182a984)
Location: drivers/opp/core.c:1043
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
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
In drivers/opp/core.c (ffffffff818b2a64)
Location: drivers/opp/core.c:1043
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
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
In drivers/opp/core.c (ffffffff818ced14)
Location: drivers/opp/core.c:1043
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
