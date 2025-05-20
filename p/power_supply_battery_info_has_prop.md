# Function: <code>power_supply_battery_info_has_prop</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool power_supply_battery_info_has_prop(struct power_supply_battery_info *info, enum power_supply_property psp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81d3d590)
Location: drivers/power/supply/power_supply_core.c:864
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:power_supply_battery_info_get_prop
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_attr_is_visible
```
**Symbols:**

```
ffffffff81d3d590-ffffffff81d3d752: power_supply_battery_info_has_prop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool power_supply_battery_info_has_prop(struct power_supply_battery_info *info, enum power_supply_property psp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81df3ee0)
Location: drivers/power/supply/power_supply_core.c:863
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:power_supply_battery_info_get_prop
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_attr_is_visible
```
**Symbols:**

```
ffffffff81df3ee0-ffffffff81df40a2: power_supply_battery_info_has_prop (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
