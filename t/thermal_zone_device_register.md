# Function: <code>thermal_zone_device_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81687870)
Location: drivers/thermal/thermal_core.c:1795
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/power/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81687870-ffffffff816881de: thermal_zone_device_register.part.28 (STB_LOCAL)
ffffffff816881e0-ffffffff81688294: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816e8530)
Location: drivers/thermal/thermal_core.c:1803
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/power/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff816e8530-ffffffff816e8eb0: thermal_zone_device_register.part.27 (STB_LOCAL)
ffffffff816e8eb0-ffffffff816e8f64: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81716c80)
Location: drivers/thermal/thermal_core.c:1143
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81716c80-ffffffff817172ae: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8172e610)
Location: drivers/thermal/thermal_core.c:1181
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff8172e610-ffffffff8172ebf9: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8179fc50)
Location: drivers/thermal/thermal_core.c:1177
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff8179fc50-ffffffff817a0237: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817e7210)
Location: drivers/thermal/thermal_core.c:1175
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff817e7210-ffffffff817e7812: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81813490)
Location: drivers/thermal/thermal_core.c:1180
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff81813490-ffffffff81813a95: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81856830)
Location: drivers/thermal/thermal_core.c:1235
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff81856260-ffffffff81856822: thermal_zone_device_register.part.0 (STB_LOCAL)
ffffffff81856ed3-ffffffff81856ef2: thermal_zone_device_register.part.0.cold (STB_LOCAL)
ffffffff81856830-ffffffff8185685d: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:1235
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff81888923-ffffffff818889aa: thermal_zone_device_register.cold (STB_LOCAL)
ffffffff818878c0-ffffffff81887ea9: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:1223
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81957364-ffffffff819573cc: thermal_zone_device_register.cold (STB_LOCAL)
ffffffff819568a0-ffffffff81956d06: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:1291
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/power/supply/power_supply_core.c:psy_register_thermal
```
**Symbols:**

```
ffffffff81c25ae5-ffffffff81c25b4d: thermal_zone_device_register.cold (STB_LOCAL)
ffffffff8195a9e0-ffffffff8195aee9: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:1232
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81c17cbc-ffffffff81c17d24: thermal_zone_device_register.cold (STB_LOCAL)
ffffffff8193f790-ffffffff8193fcc8: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:1184
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81d26e3b-ffffffff81d26eb7: thermal_zone_device_register.cold (STB_LOCAL)
ffffffff819e4080-ffffffff819e45f0: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:1187
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81ef2c90-ffffffff81ef2cee: thermal_zone_device_register.cold (STB_LOCAL)
ffffffff81b49250-ffffffff81b497a8: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int ntrips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81ce0e30)
Location: drivers/thermal/thermal_core.c:1352
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81ce0e30-ffffffff81ce0e68: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int ntrips, int mask, void *devdata, struct thermal_zone_device_ops *ops, const struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d490c0)
Location: drivers/thermal/thermal_core.c:1372
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81d490c0-ffffffff81d490f8: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffff800010ad53c0)
Location: drivers/thermal/thermal_core.c:1235
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/thermal/of-thermal.c:of_parse_thermal_zones
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
```
**Symbols:**

```
ffff800010ad53c0-ffff800010ad59ec: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c0bb4674)
Location: drivers/thermal/thermal_core.c:1235
Inline: False
Direct callers:
  - drivers/thermal/of-thermal.c:of_parse_thermal_zones
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
```
**Symbols:**

```
c0bb4674-c0bb4cb0: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c000000000bbb170)
Location: drivers/thermal/thermal_core.c:1235
Inline: False
Direct callers:
  - drivers/thermal/of-thermal.c:of_parse_thermal_zones
```
**Symbols:**

```
c000000000bbb170-c000000000bbb944: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffe0006d04f4)
Location: drivers/thermal/thermal_core.c:1235
Inline: False
Direct callers:
  - drivers/thermal/of-thermal.c:of_parse_thermal_zones
```
**Symbols:**

```
ffffffe0006d04f4-ffffffe0006d09f6: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:1235
Inline: False
```
**Symbols:**

```
ffffffff8182e7a3-ffffffff8182e82a: thermal_zone_device_register.cold (STB_LOCAL)
ffffffff8182d740-ffffffff8182dd29: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:1235
Inline: False
```
**Symbols:**

```
ffffffff817f5e33-ffffffff817f5eba: thermal_zone_device_register.cold (STB_LOCAL)
ffffffff817f4dd0-ffffffff817f53b9: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:1235
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff8187ddd3-ffffffff8187de5a: thermal_zone_device_register.cold (STB_LOCAL)
ffffffff8187cd70-ffffffff8187d359: thermal_zone_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_device_register(const char *type, int trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:1235
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
**Symbols:**

```
ffffffff81899803-ffffffff8189988a: thermal_zone_device_register.cold (STB_LOCAL)
ffffffff818987a0-ffffffff81898d89: thermal_zone_device_register (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int ntrips</code>
</li>
<li>
<b>Param removed. </b>
<code>int trips</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct thermal_zone_params *tzp</code> ➡️ <code>const struct thermal_zone_params *tzp</code>
</li>
</ul>
</details>
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
