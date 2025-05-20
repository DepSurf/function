# Function: <code>thermal_cooling_device_trip_point_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t thermal_cooling_device_trip_point_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81685650)
Location: drivers/thermal/thermal_core.c:1176
Inline: True
```
**Symbols:**

```
ffffffff81685650-ffffffff81685680: thermal_cooling_device_trip_point_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t thermal_cooling_device_trip_point_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816e6b30)
Location: drivers/thermal/thermal_core.c:1182
Inline: True
```
**Symbols:**

```
ffffffff816e6b30-ffffffff816e6b60: thermal_cooling_device_trip_point_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t thermal_cooling_device_trip_point_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff81719b90)
Location: drivers/thermal/thermal_sysfs.c:730
Inline: False
```
**Symbols:**

```
ffffffff81719b90-ffffffff81719bc0: thermal_cooling_device_trip_point_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t thermal_cooling_device_trip_point_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff81731e40)
Location: drivers/thermal/thermal_sysfs.c:730
Inline: False
```
**Symbols:**

```
ffffffff81731e40-ffffffff81731e70: thermal_cooling_device_trip_point_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t thermal_cooling_device_trip_point_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff817a2f60)
Location: drivers/thermal/thermal_sysfs.c:758
Inline: False
```
**Symbols:**

```
ffffffff817a2f60-ffffffff817a2f90: thermal_cooling_device_trip_point_show (STB_GLOBAL)
```
</details>
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
</ul>
