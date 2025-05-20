# Function: <code>devm_thermal_zone_of_sensor_register</code>

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
In <code>6.5</code>: Absent ⚠️
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
struct thermal_zone_device *devm_thermal_zone_of_sensor_register(struct device *dev, int sensor_id, void *data, const struct thermal_zone_of_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/of-thermal.c (ffff800010ad9b18)
Location: drivers/thermal/of-thermal.c:617
Inline: False
Direct callers:
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
```
**Symbols:**

```
ffff800010ad9b18-ffff800010ad9bc0: devm_thermal_zone_of_sensor_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct thermal_zone_device *devm_thermal_zone_of_sensor_register(struct device *dev, int sensor_id, void *data, const struct thermal_zone_of_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/of-thermal.c (c0bb9d9c)
Location: drivers/thermal/of-thermal.c:617
Inline: False
Direct callers:
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
```
**Symbols:**

```
c0bb9d9c-c0bb9e2c: devm_thermal_zone_of_sensor_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct thermal_zone_device *devm_thermal_zone_of_sensor_register(struct device *dev, int sensor_id, void *data, const struct thermal_zone_of_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/of-thermal.c (c000000000bc1180)
Location: drivers/thermal/of-thermal.c:617
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
c000000000bc1180-c000000000bc1268: devm_thermal_zone_of_sensor_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct thermal_zone_device *devm_thermal_zone_of_sensor_register(struct device *dev, int sensor_id, void *data, const struct thermal_zone_of_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/of-thermal.c (ffffffe0006d4144)
Location: drivers/thermal/of-thermal.c:617
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffe0006d4144-ffffffe0006d41d2: devm_thermal_zone_of_sensor_register (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
