# Function: <code>regulator_lock</code>

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
In drivers/regulator/core.c (ffffffff82724fcf)
Location: drivers/regulator/core.c:175
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
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void regulator_lock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff828dd191)
Location: drivers/regulator/core.c:210
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
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
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
```
**Symbols:**

```
ffffffff81624380-ffffffff8162441e: regulator_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void regulator_lock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff828f79f5)
Location: drivers/regulator/core.c:192
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
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
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
```
**Symbols:**

```
ffffffff81657040-ffffffff816570de: regulator_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void regulator_lock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81678b17)
Location: drivers/regulator/core.c:192
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
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
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
```
**Symbols:**

```
ffffffff8167a940-ffffffff8167a9de: regulator_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void regulator_lock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172c9fa)
Location: drivers/regulator/core.c:192
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
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
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_opmode_show
  - drivers/regulator/core.c:regulator_uA_show
  - drivers/regulator/core.c:regulator_uV_show
```
**Symbols:**

```
ffffffff817295b0-ffffffff8172964e: regulator_lock (STB_GLOBAL)
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
In drivers/regulator/core.c (ffffffff81749a8a)
Location: drivers/regulator/core.c:193
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
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
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_opmode_show
  - drivers/regulator/core.c:regulator_uA_show
  - drivers/regulator/core.c:regulator_uV_show
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
In drivers/regulator/core.c (ffffffff8172d32f)
Location: drivers/regulator/core.c:193
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
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
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_opmode_show
  - drivers/regulator/core.c:regulator_uA_show
  - drivers/regulator/core.c:regulator_uV_show
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
In drivers/regulator/core.c (ffffffff817ab3d4)
Location: drivers/regulator/core.c:183
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
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
In drivers/regulator/core.c (ffffffff818e607e)
Location: drivers/regulator/core.c:184
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
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
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:requested_microamps_show
  - drivers/regulator/core.c:state_show
  - drivers/regulator/core.c:opmode_show
  - drivers/regulator/core.c:microamps_show
  - drivers/regulator/core.c:microvolts_show
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
In drivers/regulator/core.c (ffffffff81a3b537)
Location: drivers/regulator/core.c:184
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
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
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:requested_microamps_show
  - drivers/regulator/core.c:state_show
  - drivers/regulator/core.c:opmode_show
  - drivers/regulator/core.c:microamps_show
  - drivers/regulator/core.c:microvolts_show
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
In drivers/regulator/core.c (ffffffff81a85747)
Location: drivers/regulator/core.c:184
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
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
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:requested_microamps_show
  - drivers/regulator/core.c:state_show
  - drivers/regulator/core.c:opmode_show
  - drivers/regulator/core.c:microamps_show
  - drivers/regulator/core.c:microvolts_show
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
In drivers/regulator/core.c (ffffffff81ad7f07)
Location: drivers/regulator/core.c:186
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
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
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:requested_microamps_show
  - drivers/regulator/core.c:state_show
  - drivers/regulator/core.c:opmode_show
  - drivers/regulator/core.c:microamps_show
  - drivers/regulator/core.c:microvolts_show
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
void regulator_lock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010844478)
Location: drivers/regulator/core.c:192
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
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
```
**Symbols:**

```
ffff800010842d10-ffff800010842df0: regulator_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void regulator_lock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094c620)
Location: drivers/regulator/core.c:192
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
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
```
**Symbols:**

```
c094d8dc-c094d998: regulator_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void regulator_lock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008dd894)
Location: drivers/regulator/core.c:192
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
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
```
**Symbols:**

```
c0000000008def40-c0000000008df054: regulator_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void regulator_lock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe00052449c)
Location: drivers/regulator/core.c:192
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
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
```
**Symbols:**

```
ffffffe000524e7a-ffffffe000524f24: regulator_lock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void regulator_lock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8163e617)
Location: drivers/regulator/core.c:192
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
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
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
```
**Symbols:**

```
ffffffff81640440-ffffffff816404de: regulator_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void regulator_lock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8161e9f7)
Location: drivers/regulator/core.c:192
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
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
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
```
**Symbols:**

```
ffffffff81620820-ffffffff816208be: regulator_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void regulator_lock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8166c957)
Location: drivers/regulator/core.c:192
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
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
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
```
**Symbols:**

```
ffffffff8166e780-ffffffff8166e81e: regulator_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void regulator_lock(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81686f87)
Location: drivers/regulator/core.c:192
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
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
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
```
**Symbols:**

```
ffffffff81688de0-ffffffff81688e7e: regulator_lock (STB_GLOBAL)
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
