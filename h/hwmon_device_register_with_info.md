# Function: <code>hwmon_device_register_with_info</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff817146a0)
Location: drivers/hwmon/hwmon.c:672
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_info
```
**Symbols:**

```
ffffffff817146a0-ffffffff817146d2: hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8172cbe0)
Location: drivers/hwmon/hwmon.c:677
Inline: False
```
**Symbols:**

```
ffffffff8172cbe0-ffffffff8172cc18: hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8179e3a0)
Location: drivers/hwmon/hwmon.c:690
Inline: False
```
**Symbols:**

```
ffffffff8179e3a0-ffffffff8179e3d8: hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff817e5920)
Location: drivers/hwmon/hwmon.c:690
Inline: True
Direct callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff817e5920-ffffffff817e595c: hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff818113d0)
Location: drivers/hwmon/hwmon.c:708
Inline: True
Direct callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff818113d0-ffffffff8181140c: hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff818533e0)
Location: drivers/hwmon/hwmon.c:714
Inline: True
Direct callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff818533e0-ffffffff81853425: hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81884e50)
Location: drivers/hwmon/hwmon.c:728
Inline: True
Direct callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81884e50-ffffffff81884e95: hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81953d30)
Location: drivers/hwmon/hwmon.c:819
Inline: True
Direct callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81953d30-ffffffff81953d75: hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81958b50)
Location: drivers/hwmon/hwmon.c:829
Inline: True
Direct callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81958b50-ffffffff81958b95: hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8193c5c0)
Location: drivers/hwmon/hwmon.c:829
Inline: True
Direct callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff8193c5c0-ffffffff8193c605: hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff819e0e50)
Location: drivers/hwmon/hwmon.c:869
Inline: True
Direct callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff819e0e50-ffffffff819e0e95: hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81b45b80)
Location: drivers/hwmon/hwmon.c:902
Inline: True
```
**Symbols:**

```
ffffffff81b45b80-ffffffff81b45c15: hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81cdcd80)
Location: drivers/hwmon/hwmon.c:903
Inline: True
```
**Symbols:**

```
ffffffff81cdcd80-ffffffff81cdce15: hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81d45270)
Location: drivers/hwmon/hwmon.c:910
Inline: True
```
**Symbols:**

```
ffffffff81d45270-ffffffff81d45305: hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81dfbc80)
Location: drivers/hwmon/hwmon.c:910
Inline: True
```
**Symbols:**

```
ffffffff81dfbc80-ffffffff81dfbd15: hwmon_device_register_with_info (STB_GLOBAL)
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
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffff800010ad1be0)
Location: drivers/hwmon/hwmon.c:728
Inline: True
Direct callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffff800010ad1be0-ffff800010ad1c90: hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (c0bb2934)
Location: drivers/hwmon/hwmon.c:728
Inline: True
Direct callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
c0bb2934-c0bb29a8: hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (c000000000bb6940)
Location: drivers/hwmon/hwmon.c:728
Inline: True
Direct callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
c000000000bb6940-c000000000bb6998: hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffe0006ce4dc)
Location: drivers/hwmon/hwmon.c:728
Inline: True
Direct callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffe0006ce4dc-ffffffe0006ce540: hwmon_device_register_with_info (STB_GLOBAL)
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
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8182acd0)
Location: drivers/hwmon/hwmon.c:728
Inline: True
Direct callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff8182acd0-ffffffff8182ad15: hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff817f2360)
Location: drivers/hwmon/hwmon.c:728
Inline: True
Direct callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff817f2360-ffffffff817f23a5: hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8187a300)
Location: drivers/hwmon/hwmon.c:728
Inline: True
Direct callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff8187a300-ffffffff8187a345: hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81895d00)
Location: drivers/hwmon/hwmon.c:728
Inline: True
Direct callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81895d00-ffffffff81895d45: hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
