# Function: <code>__hwmon_device_register</code>

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
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81714859)
Location: drivers/hwmon/hwmon.c:539
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
Direct callers:
  - drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_groups
  - drivers/hwmon/hwmon.c:hwmon_device_register
  - drivers/hwmon/hwmon.c:hwmon_device_register_with_info
```
**Symbols:**

```
ffffffff81713f10-ffffffff817145f7: __hwmon_device_register.part.4 (STB_LOCAL)
ffffffff81714600-ffffffff81714677: __hwmon_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8172c3b0)
Location: drivers/hwmon/hwmon.c:539
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
  - drivers/hwmon/hwmon.c:hwmon_device_register_with_info
```
**Symbols:**

```
ffffffff8172c3b0-ffffffff8172cb15: __hwmon_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8179db80)
Location: drivers/hwmon/hwmon.c:546
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
  - drivers/hwmon/hwmon.c:hwmon_device_register_with_info
```
**Symbols:**

```
ffffffff8179db80-ffffffff8179e2de: __hwmon_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff817e50f0)
Location: drivers/hwmon/hwmon.c:546
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
ffffffff817e50f0-ffffffff817e585b: __hwmon_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81810b80)
Location: drivers/hwmon/hwmon.c:564
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
ffffffff81810b80-ffffffff81811305: __hwmon_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:564
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
ffffffff81852fe0-ffffffff81853325: __hwmon_device_register (STB_LOCAL)
ffffffff81853935-ffffffff8185394c: __hwmon_device_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:580
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
ffffffff81884aa0-ffffffff81884d9d: __hwmon_device_register (STB_LOCAL)
ffffffff81885392-ffffffff818853aa: __hwmon_device_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:685
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
ffffffff81953a10-ffffffff81953c79: __hwmon_device_register (STB_LOCAL)
ffffffff81953e52-ffffffff81953e6a: __hwmon_device_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:695
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
ffffffff81958830-ffffffff81958a99: __hwmon_device_register (STB_LOCAL)
ffffffff81c25991-ffffffff81c259a9: __hwmon_device_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:695
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
ffffffff8193c180-ffffffff8193c510: __hwmon_device_register (STB_LOCAL)
ffffffff81c17b1c-ffffffff81c17b35: __hwmon_device_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:733
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
ffffffff819e0a00-ffffffff819e0d9d: __hwmon_device_register (STB_LOCAL)
ffffffff81d26c38-ffffffff81d26c51: __hwmon_device_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:752
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
ffffffff81b45640-ffffffff81b45aaf: __hwmon_device_register (STB_LOCAL)
ffffffff81ef2a74-ffffffff81ef2a8d: __hwmon_device_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81cdc810)
Location: drivers/hwmon/hwmon.c:753
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
ffffffff81cdc810-ffffffff81cdcc8b: __hwmon_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81d44ce0)
Location: drivers/hwmon/hwmon.c:757
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
ffffffff81d44ce0-ffffffff81d45171: __hwmon_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81dfb840)
Location: drivers/hwmon/hwmon.c:757
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
ffffffff81dfb840-ffffffff81dfbb90: __hwmon_device_register (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffff800010ad1770)
Location: drivers/hwmon/hwmon.c:580
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
ffff800010ad1770-ffff800010ad1b08: __hwmon_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (c0bb24e4)
Location: drivers/hwmon/hwmon.c:580
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
c0bb24e4-c0bb2884: __hwmon_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (c000000000bb6330)
Location: drivers/hwmon/hwmon.c:580
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
c000000000bb6330-c000000000bb6834: __hwmon_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffe0006ce136)
Location: drivers/hwmon/hwmon.c:580
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
ffffffe0006ce136-ffffffe0006ce440: __hwmon_device_register (STB_LOCAL)
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
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:580
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
ffffffff8182a920-ffffffff8182ac1d: __hwmon_device_register (STB_LOCAL)
ffffffff8182b212-ffffffff8182b22a: __hwmon_device_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:580
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
ffffffff817f1fb0-ffffffff817f22ad: __hwmon_device_register (STB_LOCAL)
ffffffff817f28a2-ffffffff817f28ba: __hwmon_device_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:580
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
ffffffff81879f50-ffffffff8187a24d: __hwmon_device_register (STB_LOCAL)
ffffffff8187a842-ffffffff8187a85a: __hwmon_device_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct device *__hwmon_device_register(struct device *dev, const char *name, void *drvdata, const struct hwmon_chip_info *chip, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:580
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
ffffffff81895950-ffffffff81895c4d: __hwmon_device_register (STB_LOCAL)
ffffffff81896242-ffffffff8189625a: __hwmon_device_register.cold (STB_LOCAL)
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
