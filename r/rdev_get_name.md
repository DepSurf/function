# Function: <code>rdev_get_name</code>

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
In drivers/regulator/core.c (ffffffff814d7c41)
Location: drivers/regulator/core.c:120
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_set_voltage_time_sel
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_read_file
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
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
In drivers/regulator/core.c (ffffffff81fd2078)
Location: drivers/regulator/core.c:120
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_read_file
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:_regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_voltage_time_sel
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
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
In drivers/regulator/core.c (ffffffff8200fa38)
Location: drivers/regulator/core.c:120
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_read_file
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:_regulator_get_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
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
In drivers/regulator/core.c (ffffffff820f1523)
Location: drivers/regulator/core.c:120
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:_regulator_get_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
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
In drivers/regulator/core.c (ffffffff826fad1c)
Location: drivers/regulator/core.c:120
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:_regulator_get_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
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
In drivers/regulator/core.c (ffffffff82725021)
Location: drivers/regulator/core.c:113
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:_regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
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
In drivers/regulator/core.c (ffffffff828dd1e5)
Location: drivers/regulator/core.c:120
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:_regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *rdev_get_name(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff828f7a42)
Location: drivers/regulator/core.c:110
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
```
**Symbols:**

```
ffffffff81655a80-ffffffff81655a9f: rdev_get_name.part.0 (STB_LOCAL)
ffffffff816587b0-ffffffff816587d5: rdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *rdev_get_name(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff81678b83)
Location: drivers/regulator/core.c:110
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
```
**Symbols:**

```
ffffffff81677fb0-ffffffff81677fcf: rdev_get_name.part.0 (STB_LOCAL)
ffffffff8167c7b0-ffffffff8167c7d5: rdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const char *rdev_get_name(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817291bc)
Location: drivers/regulator/core.c:110
Inline: True
Inline callers:
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:name_show
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
```
**Symbols:**

```
ffffffff8172ad10-ffffffff8172ad45: rdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const char *rdev_get_name(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81745d6c)
Location: drivers/regulator/core.c:111
Inline: True
Inline callers:
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:name_show
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
```
**Symbols:**

```
ffffffff81747880-ffffffff817478b5: rdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const char *rdev_get_name(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172977c)
Location: drivers/regulator/core.c:111
Inline: True
Inline callers:
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:name_show
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
```
**Symbols:**

```
ffffffff8172b100-ffffffff8172b135: rdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const char *rdev_get_name(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817a8b1c)
Location: drivers/regulator/core.c:100
Inline: True
Inline callers:
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:name_show
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
```
**Symbols:**

```
ffffffff817a7860-ffffffff817a7895: rdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const char *rdev_get_name(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff818e5569)
Location: drivers/regulator/core.c:101
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:name_show
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:regulator_get_suspend_state_check
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
```
**Symbols:**

```
ffffffff818e2080-ffffffff818e20c5: rdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const char *rdev_get_name(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3b747)
Location: drivers/regulator/core.c:101
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_get_suspend_state_check
  - drivers/regulator/core.c:regulator_get_suspend_state_check
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
```
**Symbols:**

```
ffffffff81a37350-ffffffff81a37395: rdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const char *rdev_get_name(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a85957)
Location: drivers/regulator/core.c:101
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_get_suspend_state_check
  - drivers/regulator/core.c:regulator_get_suspend_state_check
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
```
**Symbols:**

```
ffffffff81a80b50-ffffffff81a80b95: rdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const char *rdev_get_name(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad8117)
Location: drivers/regulator/core.c:103
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:_notifier_call_chain
  - drivers/regulator/core.c:_notifier_call_chain
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/core.c:set_consumer_device_supply
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:__suspend_set_state
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_get_suspend_state_check
  - drivers/regulator/core.c:regulator_get_suspend_state_check
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
```
**Symbols:**

```
ffffffff81ad3100-ffffffff81ad3145: rdev_get_name (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *rdev_get_name(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffff800010844554)
Location: drivers/regulator/core.c:110
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
```
**Symbols:**

```
ffff800010841038-ffff800010841074: rdev_get_name.part.0 (STB_LOCAL)
ffff800010846350-ffff800010846398: rdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *rdev_get_name(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (c094c70c)
Location: drivers/regulator/core.c:110
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_init_coupling
  - drivers/regulator/core.c:regulator_init_coupling
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_init_coupling
  - drivers/regulator/core.c:regulator_init_coupling
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
```
**Symbols:**

```
c094a384-c094a3b4: rdev_get_name.part.0 (STB_LOCAL)
c094fa28-c094fa64: rdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *rdev_get_name(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (c0000000008dd924)
Location: drivers/regulator/core.c:110
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
```
**Symbols:**

```
c0000000008daf50-c0000000008daf7c: rdev_get_name.part.0 (STB_LOCAL)
c0000000008e20a0-c0000000008e20d4: rdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *rdev_get_name(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffe000524552)
Location: drivers/regulator/core.c:110
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
```
**Symbols:**

```
ffffffe000522dc6-ffffffe000522dfe: rdev_get_name.part.0 (STB_LOCAL)
ffffffe00052694e-ffffffe00052698c: rdev_get_name (STB_GLOBAL)
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
const char *rdev_get_name(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff8163e683)
Location: drivers/regulator/core.c:110
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
```
**Symbols:**

```
ffffffff8163dca0-ffffffff8163dcbf: rdev_get_name.part.0 (STB_LOCAL)
ffffffff81642090-ffffffff816420b5: rdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *rdev_get_name(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff8161ea63)
Location: drivers/regulator/core.c:110
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
```
**Symbols:**

```
ffffffff8161de90-ffffffff8161deaf: rdev_get_name.part.0 (STB_LOCAL)
ffffffff81622690-ffffffff816226b5: rdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *rdev_get_name(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff8166c9c3)
Location: drivers/regulator/core.c:110
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
```
**Symbols:**

```
ffffffff8166bdf0-ffffffff8166be0f: rdev_get_name.part.0 (STB_LOCAL)
ffffffff816705f0-ffffffff81670615: rdev_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *rdev_get_name(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff81686ff3)
Location: drivers/regulator/core.c:110
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:supply_map_show
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_register_resolve_supply
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_match
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:suspend_set_state
  - drivers/regulator/core.c:name_show
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_mode_constrain
  - drivers/regulator/core.c:regulator_check_consumers
  - drivers/regulator/core.c:regulator_check_voltage
  - drivers/regulator/core.c:regulator_check_voltage
```
**Symbols:**

```
ffffffff816863b0-ffffffff816863cf: rdev_get_name.part.0 (STB_LOCAL)
ffffffff8168ac50-ffffffff8168ac75: rdev_get_name (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
