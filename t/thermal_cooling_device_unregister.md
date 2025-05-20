# Function: <code>thermal_cooling_device_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81685680)
Location: drivers/thermal/thermal_core.c:1564
Inline: True
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/power/power_supply_core.c:power_supply_unregister
  - drivers/power/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81685680-ffffffff81685863: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816e6b60)
Location: drivers/thermal/thermal_core.c:1570
Inline: True
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/power_supply_core.c:power_supply_unregister
  - drivers/power/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff816e6b60-ffffffff816e6d43: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81715ff0)
Location: drivers/thermal/thermal_core.c:1031
Inline: True
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81715ff0-ffffffff81716195: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8172da60)
Location: drivers/thermal/thermal_core.c:1069
Inline: True
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff8172da60-ffffffff8172dbf3: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8179f090)
Location: drivers/thermal/thermal_core.c:1065
Inline: True
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff8179f090-ffffffff8179f226: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817e6670)
Location: drivers/thermal/thermal_core.c:1062
Inline: True
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
**Symbols:**

```
ffffffff817e6670-ffffffff817e6809: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81812bd0)
Location: drivers/thermal/thermal_core.c:1066
Inline: True
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
**Symbols:**

```
ffffffff81812bd0-ffffffff81812d74: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81854b50)
Location: drivers/thermal/thermal_core.c:1121
Inline: True
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_cooling_device_release
```
**Symbols:**

```
ffffffff81854b50-ffffffff81854cf2: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff818865b0)
Location: drivers/thermal/thermal_core.c:1121
Inline: True
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_cooling_device_release
```
**Symbols:**

```
ffffffff818865b0-ffffffff81886752: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81954650)
Location: drivers/thermal/thermal_core.c:1109
Inline: True
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_pss_perf_init
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_release
```
**Symbols:**

```
ffffffff81954650-ffffffff819547e1: thermal_cooling_device_unregister.part.0 (STB_LOCAL)
ffffffff819547f0-ffffffff8195486a: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81959f40)
Location: drivers/thermal/thermal_core.c:1177
Inline: True
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_pss_perf_init
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_release
```
**Symbols:**

```
ffffffff81959f40-ffffffff8195a0d1: thermal_cooling_device_unregister.part.0 (STB_LOCAL)
ffffffff8195a0e0-ffffffff8195a15a: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8193d070)
Location: drivers/thermal/thermal_core.c:1117
Inline: True
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_release
```
**Symbols:**

```
ffffffff8193d070-ffffffff8193d26b: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819e197a)
Location: drivers/thermal/thermal_core.c:1069
Inline: True
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_release
```
**Symbols:**

```
ffffffff81d26cdb-ffffffff81d26d04: thermal_cooling_device_unregister.cold (STB_LOCAL)
ffffffff819e1910-ffffffff819e1b17: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81b46b00)
Location: drivers/thermal/thermal_core.c:1072
Inline: True
Direct callers:
  - drivers/acpi/fan_core.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_release
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_unregister
```
**Symbols:**

```
ffffffff81ef2b44-ffffffff81ef2b6d: thermal_cooling_device_unregister.cold (STB_LOCAL)
ffffffff81b46a70-ffffffff81b46c9b: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81cde190)
Location: drivers/thermal/thermal_core.c:1072
Inline: True
Direct callers:
  - drivers/acpi/fan_core.c:acpi_fan_remove
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_exit
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_init
  - drivers/thermal/thermal_core.c:thermal_cooling_device_release
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_unregister
```
**Symbols:**

```
ffffffff820a7a0c-ffffffff820a7a35: thermal_cooling_device_unregister.cold (STB_LOCAL)
ffffffff81cde100-ffffffff81cde32b: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d466a0)
Location: drivers/thermal/thermal_core.c:1098
Inline: True
Direct callers:
  - drivers/acpi/fan_core.c:acpi_fan_remove
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_exit
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_init
  - drivers/thermal/thermal_core.c:thermal_cooling_device_release
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_unregister
```
**Symbols:**

```
ffffffff81d466a0-ffffffff81d467ca: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81dfd0d0)
Location: drivers/thermal/thermal_core.c:1167
Inline: True
Direct callers:
  - drivers/acpi/fan_core.c:acpi_fan_remove
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_exit
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_init
  - drivers/thermal/thermal_core.c:thermal_cooling_device_release
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_unregister
```
**Symbols:**

```
ffffffff81dfd0d0-ffffffff81dfd1fa: thermal_cooling_device_unregister (STB_GLOBAL)
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
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffff800010ad3400)
Location: drivers/thermal/thermal_core.c:1121
Inline: True
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_cooling_device_release
```
**Symbols:**

```
ffff800010ad3400-ffff800010ad3594: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c0bb3e80)
Location: drivers/thermal/thermal_core.c:1121
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_cooling_device_release
```
**Symbols:**

```
c0bb3e80-c0bb4000: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c000000000bb8450)
Location: drivers/thermal/thermal_core.c:1121
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_cooling_device_release
```
**Symbols:**

```
c000000000bb8450-c000000000bb86b8: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffe0006cfa68)
Location: drivers/thermal/thermal_core.c:1121
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_cooling_device_release
```
**Symbols:**

```
ffffffe0006cfa68-ffffffe0006cfbd2: thermal_cooling_device_unregister (STB_GLOBAL)
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
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8182c430)
Location: drivers/thermal/thermal_core.c:1121
Inline: True
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_cooling_device_release
```
**Symbols:**

```
ffffffff8182c430-ffffffff8182c5d2: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817f3ac0)
Location: drivers/thermal/thermal_core.c:1121
Inline: True
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_cooling_device_release
```
**Symbols:**

```
ffffffff817f3ac0-ffffffff817f3c62: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8187ba60)
Location: drivers/thermal/thermal_core.c:1121
Inline: True
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_cooling_device_release
```
**Symbols:**

```
ffffffff8187ba60-ffffffff8187bc02: thermal_cooling_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void thermal_cooling_device_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81897490)
Location: drivers/thermal/thermal_core.c:1121
Inline: True
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_cooling_device_release
```
**Symbols:**

```
ffffffff81897490-ffffffff81897632: thermal_cooling_device_unregister (STB_GLOBAL)
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
