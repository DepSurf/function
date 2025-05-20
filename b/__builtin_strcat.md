# Function: <code>__builtin_strcat</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:show_valid_zones
  - drivers/base/memory.c:show_valid_zones
  - drivers/base/memory.c:show_valid_zones
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:show_valid_zones
  - drivers/base/memory.c:show_valid_zones
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:create_synth_event
  - kernel/trace/trace_events_hist.c:create_synth_event
  - kernel/trace/trace_events_hist.c:create_synth_event
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:show_valid_zones
  - drivers/base/memory.c:show_valid_zones
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:expr_field_str
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:expr_field_str
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:expr_field_str
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:expr_field_str
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:expr_field_str
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/clk/zynqmp/clkc.c:zynqmp_register_clocks
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - drivers/pinctrl/aspeed/pinctrl-aspeed.c:get_defined_attribute
  - sound/core/init.c:snd_component_add
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:expr_field_str
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - drivers/acpi/sysfs.c:acpi_table_attr_init
  - drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate
  - drivers/acpi/acpica/exnames.c:acpi_ex_name_segment
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat
  - drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
</ul>

## Differences
