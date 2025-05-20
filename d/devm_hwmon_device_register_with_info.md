# Function: <code>devm_hwmon_device_register_with_info</code>

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
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff817146e0)
Location: drivers/hwmon/hwmon.c:777
Inline: False
```
**Symbols:**

```
ffffffff817146e0-ffffffff8171478b: devm_hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8172cc20)
Location: drivers/hwmon/hwmon.c:785
Inline: True
```
**Symbols:**

```
ffffffff8172cc20-ffffffff8172ccdc: devm_hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8179e3e0)
Location: drivers/hwmon/hwmon.c:798
Inline: True
```
**Symbols:**

```
ffffffff8179e3e0-ffffffff8179e49c: devm_hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff817e5960)
Location: drivers/hwmon/hwmon.c:801
Inline: True
```
**Symbols:**

```
ffffffff817e5960-ffffffff817e5a08: devm_hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81811410)
Location: drivers/hwmon/hwmon.c:819
Inline: True
```
**Symbols:**

```
ffffffff81811410-ffffffff818114b8: devm_hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81853430)
Location: drivers/hwmon/hwmon.c:825
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81853430-ffffffff818534dd: devm_hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81884ea0)
Location: drivers/hwmon/hwmon.c:839
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81884ea0-ffffffff81884f4d: devm_hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81953d80)
Location: drivers/hwmon/hwmon.c:930
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81953d80-ffffffff81953e2d: devm_hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81958ba0)
Location: drivers/hwmon/hwmon.c:940
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81958ba0-ffffffff81958c4d: devm_hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8193c610)
Location: drivers/hwmon/hwmon.c:940
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff8193c610-ffffffff8193c6ba: devm_hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff819e0ea0)
Location: drivers/hwmon/hwmon.c:980
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff819e0ea0-ffffffff819e0f51: devm_hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81b45c20)
Location: drivers/hwmon/hwmon.c:1035
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81b45c20-ffffffff81b45ce7: devm_hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81cdce30)
Location: drivers/hwmon/hwmon.c:1036
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81cdce30-ffffffff81cdcef7: devm_hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81d45320)
Location: drivers/hwmon/hwmon.c:1043
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81d45320-ffffffff81d453e7: devm_hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **extra_groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81dfbd30)
Location: drivers/hwmon/hwmon.c:1043
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81dfbd30-ffffffff81dfbdf7: devm_hwmon_device_register_with_info (STB_GLOBAL)
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
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffff800010ad1c90)
Location: drivers/hwmon/hwmon.c:839
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffff800010ad1c90-ffff800010ad1d60: devm_hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (c0bb29a8)
Location: drivers/hwmon/hwmon.c:839
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
c0bb29a8-c0bb2a50: devm_hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (c000000000bb69a0)
Location: drivers/hwmon/hwmon.c:839
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
c000000000bb69a0-c000000000bb6a98: devm_hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffe0006ce540)
Location: drivers/hwmon/hwmon.c:839
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffe0006ce540-ffffffe0006ce5dc: devm_hwmon_device_register_with_info (STB_GLOBAL)
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
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8182ad20)
Location: drivers/hwmon/hwmon.c:839
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff8182ad20-ffffffff8182adcd: devm_hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff817f23b0)
Location: drivers/hwmon/hwmon.c:839
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff817f23b0-ffffffff817f245d: devm_hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8187a350)
Location: drivers/hwmon/hwmon.c:839
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff8187a350-ffffffff8187a3fd: devm_hwmon_device_register_with_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct device *devm_hwmon_device_register_with_info(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81895d50)
Location: drivers/hwmon/hwmon.c:839
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81895d50-ffffffff81895dfd: devm_hwmon_device_register_with_info (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct attribute_group **extra_groups</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct attribute_group **groups</code>
</li>
</ul>
</details>
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
