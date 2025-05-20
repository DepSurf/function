# Function: <code>__thermal_zone_device_update</code>

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
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81ce0dd3)
Location: drivers/thermal/thermal_core.c:409
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff81cdf2c0-ffffffff81cdf497: __thermal_zone_device_update.part.0 (STB_LOCAL)
ffffffff820a7a4e-ffffffff820a7a62: __thermal_zone_device_update.part.0.cold (STB_LOCAL)
ffffffff81ce11a0-ffffffff81ce11cf: __thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d49061)
Location: drivers/thermal/thermal_core.c:404
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_trip.c:thermal_zone_set_trip
```
**Symbols:**

```
ffffffff81d47360-ffffffff81d476a2: __thermal_zone_device_update.part.0 (STB_LOCAL)
ffffffff82128e41-ffffffff82128e55: __thermal_zone_device_update.part.0.cold (STB_LOCAL)
ffffffff81d49410-ffffffff81d4943f: __thermal_zone_device_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __thermal_zone_device_update(struct thermal_zone_device *tz, enum thermal_notify_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81dfe46f)
Location: drivers/thermal/thermal_core.c:459
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_resume
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_resume
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_sysfs.c:emul_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_trip.c:thermal_zone_trip_updated
```
**Symbols:**

```
ffffffff81dfd990-ffffffff81dfdcbd: __thermal_zone_device_update.part.0 (STB_LOCAL)
ffffffff8220a851-ffffffff8220a866: __thermal_zone_device_update.cold (STB_LOCAL)
ffffffff81e001f0-ffffffff81e0024e: __thermal_zone_device_update (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
