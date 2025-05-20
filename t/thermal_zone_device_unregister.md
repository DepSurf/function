# Function: <code>thermal_zone_device_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81684930)
Location: drivers/thermal/thermal_core.c:1962
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/power/power_supply_core.c:power_supply_unregister
  - drivers/power/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81684930-ffffffff81684c22: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816e5eb0)
Location: drivers/thermal/thermal_core.c:1970
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/power/power_supply_core.c:power_supply_unregister
  - drivers/power/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff816e5eb0-ffffffff816e61a2: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817157e0)
Location: drivers/thermal/thermal_core.c:1268
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff817157e0-ffffffff817159cc: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8172dc00)
Location: drivers/thermal/thermal_core.c:1307
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff8172dc00-ffffffff8172ddd7: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8179f230)
Location: drivers/thermal/thermal_core.c:1306
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff8179f230-ffffffff8179f40d: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817e6810)
Location: drivers/thermal/thermal_core.c:1304
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
**Symbols:**

```
ffffffff817e6810-ffffffff817e69e8: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81812d80)
Location: drivers/thermal/thermal_core.c:1309
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
**Symbols:**

```
ffffffff81812d80-ffffffff81812f58: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81854d20)
Location: drivers/thermal/thermal_core.c:1364
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
**Symbols:**

```
ffffffff81854d20-ffffffff81854ef6: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81886780)
Location: drivers/thermal/thermal_core.c:1374
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
**Symbols:**

```
ffffffff81886780-ffffffff81886956: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819562f0)
Location: drivers/thermal/thermal_core.c:1362
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff819562f0-ffffffff81956525: thermal_zone_device_unregister.part.0 (STB_LOCAL)
ffffffff81956530-ffffffff81956546: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8195c230)
Location: drivers/thermal/thermal_core.c:1433
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:psy_register_thermal
```
**Symbols:**

```
ffffffff8195c230-ffffffff8195c472: thermal_zone_device_unregister.part.0 (STB_LOCAL)
ffffffff8195c480-ffffffff8195c496: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8193f170)
Location: drivers/thermal/thermal_core.c:1375
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff8193f170-ffffffff8193f3b2: thermal_zone_device_unregister.part.0 (STB_LOCAL)
ffffffff8193f3c0-ffffffff8193f3d6: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819e3ca0)
Location: drivers/thermal/thermal_core.c:1330
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff819e3a50-ffffffff819e3c9f: thermal_zone_device_unregister.part.0 (STB_LOCAL)
ffffffff81d26e12-ffffffff81d26e3b: thermal_zone_device_unregister.part.0.cold (STB_LOCAL)
ffffffff819e3ca0-ffffffff819e3cb6: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81b48dd0)
Location: drivers/thermal/thermal_core.c:1333
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81b48b50-ffffffff81b48dcd: thermal_zone_device_unregister.part.0 (STB_LOCAL)
ffffffff81ef2c67-ffffffff81ef2c90: thermal_zone_device_unregister.part.0.cold (STB_LOCAL)
ffffffff81b48dd0-ffffffff81b48df2: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81ce03b0)
Location: drivers/thermal/thermal_core.c:1367
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81ce00f0-ffffffff81ce039d: thermal_zone_device_unregister.part.0 (STB_LOCAL)
ffffffff820a7a62-ffffffff820a7a8b: thermal_zone_device_unregister.part.0.cold (STB_LOCAL)
ffffffff81ce03b0-ffffffff81ce03d2: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d48340)
Location: drivers/thermal/thermal_core.c:1411
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81d48340-ffffffff81d48512: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81dff7a0)
Location: drivers/thermal/thermal_core.c:1476
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81dff7a0-ffffffff81dff96c: thermal_zone_device_unregister (STB_GLOBAL)
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
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffff800010ad35c8)
Location: drivers/thermal/thermal_core.c:1374
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/of-thermal.c:of_thermal_destroy_zones
  - drivers/thermal/armada_thermal.c:armada_thermal_exit
```
**Symbols:**

```
ffff800010ad35c8-ffff800010ad3788: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c0bb4020)
Location: drivers/thermal/thermal_core.c:1374
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/of-thermal.c:of_thermal_destroy_zones
  - drivers/thermal/armada_thermal.c:armada_thermal_exit
```
**Symbols:**

```
c0bb4020-c0bb41d4: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c000000000bb86e0)
Location: drivers/thermal/thermal_core.c:1374
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/of-thermal.c:of_thermal_destroy_zones
```
**Symbols:**

```
c000000000bb86e0-c000000000bb89a8: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffe0006cfbfc)
Location: drivers/thermal/thermal_core.c:1374
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/of-thermal.c:of_thermal_destroy_zones
```
**Symbols:**

```
ffffffe0006cfbfc-ffffffe0006cfd80: thermal_zone_device_unregister (STB_GLOBAL)
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
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8182c600)
Location: drivers/thermal/thermal_core.c:1374
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
**Symbols:**

```
ffffffff8182c600-ffffffff8182c7d6: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817f3c90)
Location: drivers/thermal/thermal_core.c:1374
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
**Symbols:**

```
ffffffff817f3c90-ffffffff817f3e66: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8187bc30)
Location: drivers/thermal/thermal_core.c:1374
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
**Symbols:**

```
ffffffff8187bc30-ffffffff8187be06: thermal_zone_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void thermal_zone_device_unregister(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81897660)
Location: drivers/thermal/thermal_core.c:1374
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
**Symbols:**

```
ffffffff81897660-ffffffff81897836: thermal_zone_device_unregister (STB_GLOBAL)
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
