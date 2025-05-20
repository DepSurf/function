# Function: <code>hwmon_notify_event</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hwmon_notify_event(struct device *dev, enum hwmon_sensor_types type, u32 attr, int channel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81952b40)
Location: drivers/hwmon/hwmon.c:577
Inline: False
```
**Symbols:**

```
ffffffff81952b40-ffffffff81952bdf: hwmon_notify_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hwmon_notify_event(struct device *dev, enum hwmon_sensor_types type, u32 attr, int channel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff819579c0)
Location: drivers/hwmon/hwmon.c:587
Inline: False
```
**Symbols:**

```
ffffffff819579c0-ffffffff81957a5f: hwmon_notify_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hwmon_notify_event(struct device *dev, enum hwmon_sensor_types type, u32 attr, int channel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8193b600)
Location: drivers/hwmon/hwmon.c:587
Inline: False
```
**Symbols:**

```
ffffffff8193b600-ffffffff8193b69f: hwmon_notify_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hwmon_notify_event(struct device *dev, enum hwmon_sensor_types type, u32 attr, int channel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff819dfdd0)
Location: drivers/hwmon/hwmon.c:625
Inline: False
```
**Symbols:**

```
ffffffff819dfdd0-ffffffff819dfecb: hwmon_notify_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hwmon_notify_event(struct device *dev, enum hwmon_sensor_types type, u32 attr, int channel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81b446f0)
Location: drivers/hwmon/hwmon.c:641
Inline: False
```
**Symbols:**

```
ffffffff81b446f0-ffffffff81b44881: hwmon_notify_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hwmon_notify_event(struct device *dev, enum hwmon_sensor_types type, u32 attr, int channel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81cdb790)
Location: drivers/hwmon/hwmon.c:642
Inline: False
```
**Symbols:**

```
ffffffff81cdb790-ffffffff81cdb921: hwmon_notify_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hwmon_notify_event(struct device *dev, enum hwmon_sensor_types type, u32 attr, int channel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81d43af0)
Location: drivers/hwmon/hwmon.c:646
Inline: False
```
**Symbols:**

```
ffffffff81d43af0-ffffffff81d43c81: hwmon_notify_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hwmon_notify_event(struct device *dev, enum hwmon_sensor_types type, u32 attr, int channel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81dfa4c0)
Location: drivers/hwmon/hwmon.c:646
Inline: False
```
**Symbols:**

```
ffffffff81dfa4c0-ffffffff81dfa651: hwmon_notify_event (STB_GLOBAL)
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
