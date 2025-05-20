# Function: <code>power_supply_get_maintenance_charging_setting</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct power_supply_maintenance_charge_table *power_supply_get_maintenance_charging_setting(struct power_supply_battery_info *info, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81b3f3e0)
Location: drivers/power/supply/power_supply_core.c:935
Inline: False
```
**Symbols:**

```
ffffffff81b3f3e0-ffffffff81b3f417: power_supply_get_maintenance_charging_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct power_supply_maintenance_charge_table *power_supply_get_maintenance_charging_setting(struct power_supply_battery_info *info, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81cd58d0)
Location: drivers/power/supply/power_supply_core.c:939
Inline: False
```
**Symbols:**

```
ffffffff81cd58d0-ffffffff81cd5907: power_supply_get_maintenance_charging_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct power_supply_maintenance_charge_table *power_supply_get_maintenance_charging_setting(struct power_supply_battery_info *info, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81d3d940)
Location: drivers/power/supply/power_supply_core.c:1073
Inline: False
```
**Symbols:**

```
ffffffff81d3d940-ffffffff81d3d977: power_supply_get_maintenance_charging_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct power_supply_maintenance_charge_table *power_supply_get_maintenance_charging_setting(struct power_supply_battery_info *info, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81df4290)
Location: drivers/power/supply/power_supply_core.c:1072
Inline: False
```
**Symbols:**

```
ffffffff81df4290-ffffffff81df42c7: power_supply_get_maintenance_charging_setting (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
