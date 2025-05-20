# Function: <code>power_supply_get_by_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/power_supply_core.c (ffffffff8167ee50)
Location: drivers/power/power_supply_core.c:376
Inline: False
Direct callers:
  - drivers/power/charger-manager.c:is_full_charged
  - drivers/power/charger-manager.c:charger_get_property
  - drivers/power/charger-manager.c:charger_get_property
  - drivers/power/charger-manager.c:charger_get_property
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8167ee50-ffffffff8167ee8a: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/power_supply_core.c (ffffffff816dfb60)
Location: drivers/power/power_supply_core.c:376
Inline: False
Direct callers:
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_get_property
  - drivers/power/charger-manager.c:charger_get_property
  - drivers/power/charger-manager.c:charger_get_property
  - drivers/power/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffff816dfb60-ffffffff816dfb9a: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff8170ffd0)
Location: drivers/power/supply/power_supply_core.c:376
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffff8170ffd0-ffffffff8171000a: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81728380)
Location: drivers/power/supply/power_supply_core.c:409
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffff81728380-ffffffff817283ba: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81799a90)
Location: drivers/power/supply/power_supply_core.c:447
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffff81799a90-ffffffff81799aca: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff817e0d90)
Location: drivers/power/supply/power_supply_core.c:454
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffff817e0d90-ffffffff817e0dca: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff8180c3d0)
Location: drivers/power/supply/power_supply_core.c:454
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffff8180c3d0-ffffffff8180c406: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff8184e050)
Location: drivers/power/supply/power_supply_core.c:451
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffff8184e050-ffffffff8184e083: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff8187fa90)
Location: drivers/power/supply/power_supply_core.c:451
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffff8187fa90-ffffffff8187fac3: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff8194e380)
Location: drivers/power/supply/power_supply_core.c:451
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:cm_get_battery_temperature
  - drivers/power/supply/charger-manager.c:fullbatt_vchk
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_ext_pwr_online
  - drivers/power/supply/charger-manager.c:is_batt_present
  - drivers/power/supply/charger-manager.c:is_batt_present
```
**Symbols:**

```
ffffffff8194e380-ffffffff8194e3b3: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81953d60)
Location: drivers/power/supply/power_supply_core.c:451
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:cm_get_battery_temperature
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:is_ext_pwr_online
  - drivers/power/supply/charger-manager.c:is_batt_present
  - drivers/power/supply/charger-manager.c:is_batt_present
```
**Symbols:**

```
ffffffff81953d60-ffffffff81953d93: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81937bf0)
Location: drivers/power/supply/power_supply_core.c:451
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:cm_get_battery_temperature
  - drivers/power/supply/charger-manager.c:is_ext_pwr_online
  - drivers/power/supply/charger-manager.c:is_batt_present
  - drivers/power/supply/charger-manager.c:is_batt_present
```
**Symbols:**

```
ffffffff81937bf0-ffffffff81937c23: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff819dbec0)
Location: drivers/power/supply/power_supply_core.c:451
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:cm_get_battery_temperature
  - drivers/power/supply/charger-manager.c:is_ext_pwr_online
  - drivers/power/supply/charger-manager.c:is_batt_present
  - drivers/power/supply/charger-manager.c:is_batt_present
```
**Symbols:**

```
ffffffff819dbec0-ffffffff819dbef3: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81b3f9c0)
Location: drivers/power/supply/power_supply_core.c:455
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:cm_get_battery_temperature
  - drivers/power/supply/charger-manager.c:is_charging
  - drivers/power/supply/charger-manager.c:is_ext_pwr_online
  - drivers/power/supply/charger-manager.c:is_batt_present
  - drivers/power/supply/charger-manager.c:is_batt_present
```
**Symbols:**

```
ffffffff81b3f9c0-ffffffff81b3f9ff: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81cd5f20)
Location: drivers/power/supply/power_supply_core.c:455
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:cm_get_battery_temperature
  - drivers/power/supply/charger-manager.c:is_charging
  - drivers/power/supply/charger-manager.c:is_ext_pwr_online
  - drivers/power/supply/charger-manager.c:is_batt_present
  - drivers/power/supply/charger-manager.c:is_batt_present
```
**Symbols:**

```
ffffffff81cd5f20-ffffffff81cd5f5f: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81d3df20)
Location: drivers/power/supply/power_supply_core.c:459
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:cm_get_battery_temperature
  - drivers/power/supply/charger-manager.c:is_charging
  - drivers/power/supply/charger-manager.c:is_ext_pwr_online
  - drivers/power/supply/charger-manager.c:is_batt_present
  - drivers/power/supply/charger-manager.c:is_batt_present
```
**Symbols:**

```
ffffffff81d3df20-ffffffff81d3df5f: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81df4870)
Location: drivers/power/supply/power_supply_core.c:458
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:cm_get_battery_temperature
  - drivers/power/supply/charger-manager.c:is_charging
  - drivers/power/supply/charger-manager.c:is_ext_pwr_online
  - drivers/power/supply/charger-manager.c:is_batt_present
  - drivers/power/supply/charger-manager.c:is_batt_present
```
**Symbols:**

```
ffffffff81df4870-ffffffff81df48af: power_supply_get_by_name (STB_GLOBAL)
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
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffff800010acc558)
Location: drivers/power/supply/power_supply_core.c:451
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffff800010acc558-ffff800010acc5c4: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (c0babe10)
Location: drivers/power/supply/power_supply_core.c:451
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:cm_get_battery_temperature
  - drivers/power/supply/charger-manager.c:is_full_charged
  - drivers/power/supply/charger-manager.c:get_batt_uV
  - drivers/power/supply/charger-manager.c:is_ext_pwr_online
```
**Symbols:**

```
c0babe10-c0babe70: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (c000000000bacea0)
Location: drivers/power/supply/power_supply_core.c:451
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
c000000000bacea0-c000000000bacf0c: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffe0006c8832)
Location: drivers/power/supply/power_supply_core.c:451
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffe0006c8832-ffffffe0006c887c: power_supply_get_by_name (STB_GLOBAL)
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
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81828000)
Location: drivers/power/supply/power_supply_core.c:451
Inline: False
```
**Symbols:**

```
ffffffff81828000-ffffffff81828033: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff817ef690)
Location: drivers/power/supply/power_supply_core.c:451
Inline: False
```
**Symbols:**

```
ffffffff817ef690-ffffffff817ef6c3: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81874f40)
Location: drivers/power/supply/power_supply_core.c:451
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffff81874f40-ffffffff81874f73: power_supply_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct power_supply *power_supply_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff818908f0)
Location: drivers/power/supply/power_supply_core.c:451
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:charger_get_property
  - drivers/power/supply/charger-manager.c:is_full_charged
```
**Symbols:**

```
ffffffff818908f0-ffffffff81890923: power_supply_get_by_name (STB_GLOBAL)
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
