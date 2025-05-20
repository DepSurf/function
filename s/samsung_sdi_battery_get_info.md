# Function: <code>samsung_sdi_battery_get_info</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int samsung_sdi_battery_get_info(struct device *dev, const char *compatible, struct power_supply_battery_info **info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/samsung-sdi-battery.c (0)
Location: drivers/power/supply/samsung-sdi-battery.c:898
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
**Symbols:**

```
ffffffff81ef22c0-ffffffff81ef2303: samsung_sdi_battery_get_info.cold (STB_LOCAL)
ffffffff81b426f0-ffffffff81b4277a: samsung_sdi_battery_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int samsung_sdi_battery_get_info(struct device *dev, const char *compatible, struct power_supply_battery_info **info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/samsung-sdi-battery.c (ffffffff81cd8e50)
Location: drivers/power/supply/samsung-sdi-battery.c:898
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
**Symbols:**

```
ffffffff81cd8e50-ffffffff81cd8f38: samsung_sdi_battery_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int samsung_sdi_battery_get_info(struct device *dev, const char *compatible, struct power_supply_battery_info **info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/samsung-sdi-battery.c (ffffffff81d410c0)
Location: drivers/power/supply/samsung-sdi-battery.c:898
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
**Symbols:**

```
ffffffff81d410c0-ffffffff81d411a8: samsung_sdi_battery_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int samsung_sdi_battery_get_info(struct device *dev, const char *compatible, struct power_supply_battery_info **info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/samsung-sdi-battery.c (ffffffff81df7a70)
Location: drivers/power/supply/samsung-sdi-battery.c:898
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
**Symbols:**

```
ffffffff81df7a70-ffffffff81df7b58: samsung_sdi_battery_get_info (STB_GLOBAL)
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
