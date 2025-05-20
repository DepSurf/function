# Function: <code>power_supply_get_property</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/power_supply_core.c (ffffffff8167eae0)
Location: drivers/power/power_supply_core.c:490
Inline: False
Direct callers:
  - drivers/power/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/charger-manager.c:is_full_charged
  - drivers/power/charger-manager.c:is_full_charged
  - drivers/power/charger-manager.c:charger_get_property
  - drivers/power/charger-manager.c:charger_get_property
  - drivers/power/charger-manager.c:charger_get_property
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8167eae0-ffffffff8167eb01: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/power_supply_core.c (ffffffff816dffa4)
Location: drivers/power/power_supply_core.c:490
Inline: True
Inline callers:
  - drivers/power/power_supply_core.c:ps_get_cur_chrage_cntl_limit
  - drivers/power/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/power_supply_core.c:ps_get_cur_chrage_cntl_limit
  - drivers/power/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/power_supply_core.c:power_supply_read_temp
  - drivers/power/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_get_property
  - drivers/power/charger-manager.c:charger_get_property
  - drivers/power/charger-manager.c:charger_get_property
  - drivers/power/charger-manager.c:is_full_charged
  - drivers/power/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffff816dfeb0-ffffffff816dfec1: power_supply_get_property.part.5 (STB_LOCAL)
ffffffff816dfed0-ffffffff816dfefa: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81710414)
Location: drivers/power/supply/power_supply_core.c:490
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_chrage_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_chrage_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffff81710320-ffffffff81710331: power_supply_get_property.part.5 (STB_LOCAL)
ffffffff81710340-ffffffff8171036a: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81728104)
Location: drivers/power/supply/power_supply_core.c:579
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_chrage_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffff81727fd0-ffffffff81727ffb: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81799764)
Location: drivers/power/supply/power_supply_core.c:617
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_chrage_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffff81799620-ffffffff81799651: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff817e11c4)
Location: drivers/power/supply/power_supply_core.c:624
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_chrage_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_chrage_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffff817e10d0-ffffffff817e10e7: power_supply_get_property.part.10 (STB_LOCAL)
ffffffff817e10f0-ffffffff817e111a: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff8180c8b4)
Location: drivers/power/supply/power_supply_core.c:762
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_chrage_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_chrage_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffff8180c7c0-ffffffff8180c7d7: power_supply_get_property.part.14 (STB_LOCAL)
ffffffff8180c7e0-ffffffff8180c80a: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff8184e554)
Location: drivers/power/supply/power_supply_core.c:772
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffff8184e460-ffffffff8184e477: power_supply_get_property.part.0 (STB_LOCAL)
ffffffff8184e480-ffffffff8184e4aa: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff8187ff94)
Location: drivers/power/supply/power_supply_core.c:772
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffff8187fea0-ffffffff8187feb7: power_supply_get_property.part.0 (STB_LOCAL)
ffffffff8187fec0-ffffffff8187feea: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff8194ef94)
Location: drivers/power/supply/power_supply_core.c:845
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_gen_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:cm_init_thermal_data
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:cm_get_battery_temperature
  - drivers/power/supply/charger-manager.c:fullbatt_vchk
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_ext_pwr_online
  - drivers/power/supply/charger-manager.c:is_batt_present
  - drivers/power/supply/charger-manager.c:is_batt_present
```
**Symbols:**

```
ffffffff8194e670-ffffffff8194e6a1: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81954974)
Location: drivers/power/supply/power_supply_core.c:864
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_gen_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:cm_init_thermal_data
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:cm_get_battery_temperature
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_ext_pwr_online
  - drivers/power/supply/charger-manager.c:is_batt_present
  - drivers/power/supply/charger-manager.c:is_batt_present
```
**Symbols:**

```
ffffffff819541c0-ffffffff819541f1: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81938864)
Location: drivers/power/supply/power_supply_core.c:864
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:cm_get_battery_temperature
  - drivers/power/supply/charger-manager.c:is_ext_pwr_online
  - drivers/power/supply/charger-manager.c:is_batt_present
  - drivers/power/supply/charger-manager.c:is_batt_present
```
**Symbols:**

```
ffffffff81937fb0-ffffffff81937fe1: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff819dcd44)
Location: drivers/power/supply/power_supply_core.c:887
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:cm_get_battery_temperature
  - drivers/power/supply/charger-manager.c:is_ext_pwr_online
  - drivers/power/supply/charger-manager.c:is_batt_present
  - drivers/power/supply/charger-manager.c:is_batt_present
```
**Symbols:**

```
ffffffff81d2632c-ffffffff81d26340: power_supply_get_property.cold (STB_LOCAL)
ffffffff819dc3f0-ffffffff819dc43a: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81b4114c)
Location: drivers/power/supply/power_supply_core.c:1045
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:cm_get_battery_temperature
  - drivers/power/supply/charger-manager.c:is_charging
  - drivers/power/supply/charger-manager.c:is_charging
  - drivers/power/supply/charger-manager.c:is_ext_pwr_online
  - drivers/power/supply/charger-manager.c:is_batt_present
  - drivers/power/supply/charger-manager.c:is_batt_present
```
**Symbols:**

```
ffffffff81ef2175-ffffffff81ef2189: power_supply_get_property.cold (STB_LOCAL)
ffffffff81b40460-ffffffff81b404be: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81cd7804)
Location: drivers/power/supply/power_supply_core.c:1049
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:cm_get_battery_temperature
  - drivers/power/supply/charger-manager.c:is_charging
  - drivers/power/supply/charger-manager.c:is_charging
  - drivers/power/supply/charger-manager.c:is_ext_pwr_online
  - drivers/power/supply/charger-manager.c:is_batt_present
  - drivers/power/supply/charger-manager.c:is_batt_present
```
**Symbols:**

```
ffffffff820a784e-ffffffff820a7862: power_supply_get_property.cold (STB_LOCAL)
ffffffff81cd6a70-ffffffff81cd6ace: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81d3eaa0)
Location: drivers/power/supply/power_supply_core.c:1199
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
  - drivers/power/supply/power_supply_core.c:__power_supply_get_supplier_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:cm_get_battery_temperature
  - drivers/power/supply/charger-manager.c:is_charging
  - drivers/power/supply/charger-manager.c:is_charging
  - drivers/power/supply/charger-manager.c:is_ext_pwr_online
  - drivers/power/supply/charger-manager.c:is_batt_present
  - drivers/power/supply/charger-manager.c:is_batt_present
```
**Symbols:**

```
ffffffff82128c49-ffffffff82128c5d: power_supply_get_property.cold (STB_LOCAL)
ffffffff81d3ea80-ffffffff81d3eb5d: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81df53f0)
Location: drivers/power/supply/power_supply_core.c:1198
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
  - drivers/power/supply/power_supply_core.c:__power_supply_get_supplier_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:cm_get_battery_temperature
  - drivers/power/supply/charger-manager.c:is_charging
  - drivers/power/supply/charger-manager.c:is_charging
  - drivers/power/supply/charger-manager.c:is_ext_pwr_online
  - drivers/power/supply/charger-manager.c:is_batt_present
  - drivers/power/supply/charger-manager.c:is_batt_present
```
**Symbols:**

```
ffffffff8220a5db-ffffffff8220a5ef: power_supply_get_property.cold (STB_LOCAL)
ffffffff81df53d0-ffffffff81df54ad: power_supply_get_property (STB_GLOBAL)
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
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffff800010acb92c)
Location: drivers/power/supply/power_supply_core.c:772
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffff800010acb798-ffff800010acb7e4: power_supply_get_property.part.0 (STB_LOCAL)
ffff800010acb7e8-ffff800010acb85c: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (c0bac95c)
Location: drivers/power/supply/power_supply_core.c:772
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:cm_get_battery_temperature
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:get_batt_uV
  - drivers/power/supply/charger-manager.c:is_ext_pwr_online
```
**Symbols:**

```
c0bac838-c0bac85c: power_supply_get_property.part.0 (STB_LOCAL)
c0bac85c-c0bac898: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (c000000000badf24)
Location: drivers/power/supply/power_supply_core.c:772
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
c000000000badda0-c000000000badde4: power_supply_get_property.part.0 (STB_LOCAL)
c000000000baddf0-c000000000bade28: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffe0006c934e)
Location: drivers/power/supply/power_supply_core.c:772
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffe0006c9238-ffffffe0006c9270: power_supply_get_property.part.0 (STB_LOCAL)
ffffffe0006c9270-ffffffe0006c92cc: power_supply_get_property (STB_GLOBAL)
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
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81828504)
Location: drivers/power/supply/power_supply_core.c:772
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read
```
**Symbols:**

```
ffffffff81828410-ffffffff81828427: power_supply_get_property.part.0 (STB_LOCAL)
ffffffff81828430-ffffffff8182845a: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff817efb94)
Location: drivers/power/supply/power_supply_core.c:772
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read
```
**Symbols:**

```
ffffffff817efaa0-ffffffff817efab7: power_supply_get_property.part.0 (STB_LOCAL)
ffffffff817efac0-ffffffff817efaea: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81875444)
Location: drivers/power/supply/power_supply_core.c:772
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffff81875350-ffffffff81875367: power_supply_get_property.part.0 (STB_LOCAL)
ffffffff81875370-ffffffff8187539a: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int power_supply_get_property(struct power_supply *psy, enum power_supply_property psp, union power_supply_propval *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81890de4)
Location: drivers/power/supply/power_supply_core.c:772
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
Direct callers:
  - drivers/power/supply/power_supply_core.c:ps_get_cur_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:ps_get_max_charge_cntl_limit
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_hwmon.c:power_supply_hwmon_read
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffff81890cf0-ffffffff81890d07: power_supply_get_property.part.0 (STB_LOCAL)
ffffffff81890d10-ffffffff81890d3a: power_supply_get_property (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
