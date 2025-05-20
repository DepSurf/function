# Function: <code>thermal_zone_device_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816852b0)
Location: drivers/thermal/thermal_core.c:560
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_core.c:emul_temp_store
  - drivers/thermal/thermal_core.c:passive_store
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_check
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_core.c:emul_temp_store
  - drivers/thermal/thermal_core.c:passive_store
```
**Symbols:**

```
ffffffff816852b0-ffffffff8168542c: thermal_zone_device_update.part.23 (STB_LOCAL)
ffffffff81685430-ffffffff81685459: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816e6910)
Location: drivers/thermal/thermal_core.c:560
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:emul_temp_store
  - drivers/thermal/thermal_core.c:passive_store
  - drivers/thermal/thermal_core.c:trip_point_temp_store
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_check
  - drivers/thermal/thermal_core.c:emul_temp_store
  - drivers/thermal/thermal_core.c:passive_store
  - drivers/thermal/thermal_core.c:trip_point_temp_store
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
```
**Symbols:**

```
ffffffff816e66a0-ffffffff816e680c: thermal_zone_device_update.part.22 (STB_LOCAL)
ffffffff816e6810-ffffffff816e6839: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81715e25)
Location: drivers/thermal/thermal_core.c:408
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff81715c60-ffffffff81715de3: thermal_zone_device_update.part.24 (STB_LOCAL)
ffffffff81715df0-ffffffff81715e19: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8172d995)
Location: drivers/thermal/thermal_core.c:467
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff8172d7d0-ffffffff8172d955: thermal_zone_device_update.part.22 (STB_LOCAL)
ffffffff8172d960-ffffffff8172d98a: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8179eff5)
Location: drivers/thermal/thermal_core.c:467
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff8179ee30-ffffffff8179efb8: thermal_zone_device_update.part.18 (STB_LOCAL)
ffffffff8179efc0-ffffffff8179efea: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817e7ae6)
Location: drivers/thermal/thermal_core.c:464
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff817e63f0-ffffffff817e6586: thermal_zone_device_update.part.19 (STB_LOCAL)
ffffffff817e6590-ffffffff817e65b9: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81813389)
Location: drivers/thermal/thermal_core.c:468
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff81812870-ffffffff81812a06: thermal_zone_device_update.part.20 (STB_LOCAL)
ffffffff81812a10-ffffffff81812a39: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff818554c3)
Location: drivers/thermal/thermal_core.c:474
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff818547b0-ffffffff81854939: thermal_zone_device_update.part.0 (STB_LOCAL)
ffffffff81856e71-ffffffff81856e89: thermal_zone_device_update.part.0.cold (STB_LOCAL)
ffffffff81854940-ffffffff81854969: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81887dd1)
Location: drivers/thermal/thermal_core.c:474
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff81886210-ffffffff81886399: thermal_zone_device_update.part.0 (STB_LOCAL)
ffffffff818888c1-ffffffff818888d9: thermal_zone_device_update.part.0.cold (STB_LOCAL)
ffffffff818863a0-ffffffff818863c9: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81956cbc)
Location: drivers/thermal/thermal_core.c:462
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:thermal_set_mode
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff819553b0-ffffffff81955416: thermal_zone_device_update.part.0 (STB_LOCAL)
ffffffff81955420-ffffffff81955449: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8195a440)
Location: drivers/thermal/thermal_core.c:549
Inline: True
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff8195a440-ffffffff8195a4fe: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8193fc54)
Location: drivers/thermal/thermal_core.c:538
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff8193db60-ffffffff8193def7: thermal_zone_device_update.part.0 (STB_LOCAL)
ffffffff81c17c45-ffffffff81c17c5c: thermal_zone_device_update.part.0.cold (STB_LOCAL)
ffffffff8193df00-ffffffff8193df58: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819e4594)
Location: drivers/thermal/thermal_core.c:485
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff819e2410-ffffffff819e27b3: thermal_zone_device_update.part.0 (STB_LOCAL)
ffffffff81d26d87-ffffffff81d26db2: thermal_zone_device_update.part.0.cold (STB_LOCAL)
ffffffff819e27c0-ffffffff819e2818: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81b4973d)
Location: drivers/thermal/thermal_core.c:487
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff81b47e20-ffffffff81b47f98: thermal_zone_device_update.part.0 (STB_LOCAL)
ffffffff81ef2c0b-ffffffff81ef2c37: thermal_zone_device_update.part.0.cold (STB_LOCAL)
ffffffff81b47fa0-ffffffff81b48002: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81ce0dc3)
Location: drivers/thermal/thermal_core.c:494
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
```
**Symbols:**

```
ffffffff81cdf610-ffffffff81cdf667: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d49051)
Location: drivers/thermal/thermal_core.c:489
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
```
**Symbols:**

```
ffffffff81d47820-ffffffff81d47877: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81dfecd5)
Location: drivers/thermal/thermal_core.c:538
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
```
**Symbols:**

```
ffffffff8220a7fd-ffffffff8220a812: thermal_zone_device_update.cold (STB_LOCAL)
ffffffff81dfe710-ffffffff81dfe793: thermal_zone_device_update (STB_GLOBAL)
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
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffff800010ad5864)
Location: drivers/thermal/thermal_core.c:474
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/of-thermal.c:of_thermal_set_mode
  - drivers/thermal/armada_thermal.c:armada_overheat_isr_thread
  - drivers/thermal/armada_thermal.c:armada_overheat_isr_thread
```
**Symbols:**

```
ffff800010ad4b10-ffff800010ad4cd8: thermal_zone_device_update.part.0 (STB_LOCAL)
ffff800010ad4cd8-ffff800010ad4d28: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (c0bb4b4c)
Location: drivers/thermal/thermal_core.c:474
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/of-thermal.c:of_thermal_set_mode
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_work
  - drivers/thermal/armada_thermal.c:armada_overheat_isr_thread
  - drivers/thermal/armada_thermal.c:armada_overheat_isr_thread
```
**Symbols:**

```
c0bb3a58-c0bb3c24: thermal_zone_device_update.part.0 (STB_LOCAL)
c0bb3c24-c0bb3c64: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (c000000000bbb7a0)
Location: drivers/thermal/thermal_core.c:474
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/of-thermal.c:of_thermal_set_mode
  - drivers/thermal/of-thermal.c:of_thermal_set_mode
```
**Symbols:**

```
c000000000bb7dc0-c000000000bb7fcc: thermal_zone_device_update.part.0 (STB_LOCAL)
c000000000bb7fd0-c000000000bb8004: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffe0006d0904)
Location: drivers/thermal/thermal_core.c:474
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/of-thermal.c:of_thermal_set_mode
```
**Symbols:**

```
ffffffe0006cf7dc-ffffffe0006cf94e: thermal_zone_device_update.part.0 (STB_LOCAL)
ffffffe0006cf94e-ffffffe0006cf992: thermal_zone_device_update (STB_GLOBAL)
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
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8182dc51)
Location: drivers/thermal/thermal_core.c:474
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff8182c090-ffffffff8182c219: thermal_zone_device_update.part.0 (STB_LOCAL)
ffffffff8182e741-ffffffff8182e759: thermal_zone_device_update.part.0.cold (STB_LOCAL)
ffffffff8182c220-ffffffff8182c249: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817f52e1)
Location: drivers/thermal/thermal_core.c:474
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff817f3720-ffffffff817f38a9: thermal_zone_device_update.part.0 (STB_LOCAL)
ffffffff817f5dd1-ffffffff817f5de9: thermal_zone_device_update.part.0.cold (STB_LOCAL)
ffffffff817f38b0-ffffffff817f38d9: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8187d281)
Location: drivers/thermal/thermal_core.c:474
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff8187b6c0-ffffffff8187b849: thermal_zone_device_update.part.0 (STB_LOCAL)
ffffffff8187dd71-ffffffff8187dd89: thermal_zone_device_update.part.0.cold (STB_LOCAL)
ffffffff8187b850-ffffffff8187b879: thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81898cb1)
Location: drivers/thermal/thermal_core.c:474
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:passive_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff818970e0-ffffffff81897274: thermal_zone_device_update.part.0 (STB_LOCAL)
ffffffff818997a1-ffffffff818997b9: thermal_zone_device_update.part.0.cold (STB_LOCAL)
ffffffff81897280-ffffffff818972a9: thermal_zone_device_update (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum thermal_notify_event event</code>
</li>
</ul>
</details>
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
