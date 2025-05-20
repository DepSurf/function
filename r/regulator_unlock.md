# Function: <code>regulator_unlock</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff827250b7)
Location: drivers/regulator/core.c:187
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:_regulator_resume_early
  - drivers/regulator/core.c:_regulator_suspend_late
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_unlock_supply
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void regulator_unlock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81621150)
Location: drivers/regulator/core.c:223
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
```
**Symbols:**

```
ffffffff81621150-ffffffff816211b2: regulator_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void regulator_unlock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81654780)
Location: drivers/regulator/core.c:205
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff81654780-ffffffff816547ef: regulator_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void regulator_unlock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81676c70)
Location: drivers/regulator/core.c:205
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff81676c70-ffffffff81676cdf: regulator_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void regulator_unlock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81727690)
Location: drivers/regulator/core.c:205
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_lock
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_opmode_show
  - drivers/regulator/core.c:regulator_opmode_show
  - drivers/regulator/core.c:regulator_uA_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
```
**Symbols:**

```
ffffffff81727690-ffffffff817276f5: regulator_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void regulator_unlock(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817444d0)
Location: drivers/regulator/core.c:205
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_lock
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:destroy_regulator
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_opmode_show
  - drivers/regulator/core.c:regulator_opmode_show
  - drivers/regulator/core.c:regulator_uA_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
```
**Symbols:**

```
ffffffff817444d0-ffffffff81744535: regulator_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void regulator_unlock(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81727e70)
Location: drivers/regulator/core.c:205
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_opmode_show
  - drivers/regulator/core.c:regulator_opmode_show
  - drivers/regulator/core.c:regulator_uA_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
```
**Symbols:**

```
ffffffff81727e70-ffffffff81727ed5: regulator_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void regulator_unlock(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817ab437)
Location: drivers/regulator/core.c:195
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_sync_voltage_rdev
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:requested_microamps_show
  - drivers/regulator/core.c:state_show
  - drivers/regulator/core.c:opmode_show
  - drivers/regulator/core.c:microamps_show
  - drivers/regulator/core.c:microvolts_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
Direct callers:
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
```
**Symbols:**

```
ffffffff817a6fc0-ffffffff817a7025: regulator_unlock (STB_LOCAL)
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
In drivers/regulator/core.c (ffffffff818e60e7)
Location: drivers/regulator/core.c:196
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:_regulator_get_error_flags
  - drivers/regulator/core.c:regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_sync_voltage_rdev
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:_regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:requested_microamps_show
  - drivers/regulator/core.c:state_show
  - drivers/regulator/core.c:opmode_show
  - drivers/regulator/core.c:microamps_show
  - drivers/regulator/core.c:microvolts_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
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
In drivers/regulator/core.c (ffffffff81a3b622)
Location: drivers/regulator/core.c:196
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:_regulator_bulk_get
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_get_error_flags
  - drivers/regulator/core.c:regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_sync_voltage_rdev
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:_regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:requested_microamps_show
  - drivers/regulator/core.c:state_show
  - drivers/regulator/core.c:opmode_show
  - drivers/regulator/core.c:microamps_show
  - drivers/regulator/core.c:microvolts_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
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
In drivers/regulator/core.c (ffffffff81a85832)
Location: drivers/regulator/core.c:196
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:_regulator_bulk_get
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_get_error_flags
  - drivers/regulator/core.c:regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_sync_voltage_rdev
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:_regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:requested_microamps_show
  - drivers/regulator/core.c:state_show
  - drivers/regulator/core.c:opmode_show
  - drivers/regulator/core.c:microamps_show
  - drivers/regulator/core.c:microvolts_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
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
In drivers/regulator/core.c (ffffffff81ad7ff2)
Location: drivers/regulator/core.c:198
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:_regulator_bulk_get
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_get_error_flags
  - drivers/regulator/core.c:regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_sync_voltage_rdev
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:_regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:requested_microamps_show
  - drivers/regulator/core.c:state_show
  - drivers/regulator/core.c:opmode_show
  - drivers/regulator/core.c:microamps_show
  - drivers/regulator/core.c:microvolts_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
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
void regulator_unlock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff80001083fa58)
Location: drivers/regulator/core.c:205
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffff80001083fa58-ffff80001083fad4: regulator_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void regulator_unlock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0949238)
Location: drivers/regulator/core.c:205
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
```
**Symbols:**

```
c0949238-c09492d0: regulator_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void regulator_unlock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008d8d90)
Location: drivers/regulator/core.c:205
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
```
**Symbols:**

```
c0000000008d8d90-c0000000008d8e54: regulator_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void regulator_unlock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe0005219dc)
Location: drivers/regulator/core.c:205
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
```
**Symbols:**

```
ffffffe0005219dc-ffffffe000521a62: regulator_unlock (STB_GLOBAL)
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
void regulator_unlock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8163c960)
Location: drivers/regulator/core.c:205
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff8163c960-ffffffff8163c9cf: regulator_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void regulator_unlock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8161cb50)
Location: drivers/regulator/core.c:205
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff8161cb50-ffffffff8161cbbf: regulator_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void regulator_unlock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8166aab0)
Location: drivers/regulator/core.c:205
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff8166aab0-ffffffff8166ab1f: regulator_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void regulator_unlock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81685070)
Location: drivers/regulator/core.c:205
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff81685070-ffffffff816850df: regulator_unlock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
