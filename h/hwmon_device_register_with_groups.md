# Function: <code>hwmon_device_register_with_groups</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81682cb0)
Location: drivers/hwmon/hwmon.c:96
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
Direct callers:
  - drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_groups
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
ffffffff81682cb0-ffffffff81682db2: hwmon_device_register_with_groups.part.2 (STB_LOCAL)
ffffffff81682dc0-ffffffff81682e33: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff816e3c06)
Location: drivers/hwmon/hwmon.c:96
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_device_register
Direct callers:
  - drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_groups
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
ffffffff816e39c0-ffffffff816e3ac2: hwmon_device_register_with_groups.part.2 (STB_LOCAL)
ffffffff816e3ad0-ffffffff816e3b43: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff817147e9)
Location: drivers/hwmon/hwmon.c:650
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_groups
  - drivers/hwmon/hwmon.c:hwmon_device_register
```
**Symbols:**

```
ffffffff81714680-ffffffff81714695: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8172cb7c)
Location: drivers/hwmon/hwmon.c:652
Inline: True
```
**Symbols:**

```
ffffffff8172cd10-ffffffff8172cd32: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8179e33c)
Location: drivers/hwmon/hwmon.c:665
Inline: True
```
**Symbols:**

```
ffffffff8179e4d0-ffffffff8179e4f2: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff817e58b5)
Location: drivers/hwmon/hwmon.c:665
Inline: True
```
**Symbols:**

```
ffffffff817e5a40-ffffffff817e5a62: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81811365)
Location: drivers/hwmon/hwmon.c:683
Inline: True
```
**Symbols:**

```
ffffffff818114f0-ffffffff81811512: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81853382)
Location: drivers/hwmon/hwmon.c:689
Inline: True
```
**Symbols:**

```
ffffffff818534e0-ffffffff81853502: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81884df2)
Location: drivers/hwmon/hwmon.c:703
Inline: True
```
**Symbols:**

```
ffffffff81884f50-ffffffff81884f72: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81953cd2)
Location: drivers/hwmon/hwmon.c:794
Inline: True
```
**Symbols:**

```
ffffffff81953e30-ffffffff81953e52: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81958af2)
Location: drivers/hwmon/hwmon.c:804
Inline: True
```
**Symbols:**

```
ffffffff81958c50-ffffffff81958c72: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8193c562)
Location: drivers/hwmon/hwmon.c:804
Inline: True
```
**Symbols:**

```
ffffffff8193c6c0-ffffffff8193c6e2: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff819e0df9)
Location: drivers/hwmon/hwmon.c:844
Inline: True
```
**Symbols:**

```
ffffffff819e0f60-ffffffff819e0f82: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81b45b08)
Location: drivers/hwmon/hwmon.c:876
Inline: True
```
**Symbols:**

```
ffffffff81b45d40-ffffffff81b45d80: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81cdccf8)
Location: drivers/hwmon/hwmon.c:877
Inline: True
```
**Symbols:**

```
ffffffff81cdcfc0-ffffffff81cdd000: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81d451e8)
Location: drivers/hwmon/hwmon.c:884
Inline: True
```
**Symbols:**

```
ffffffff81d454b0-ffffffff81d454f0: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81dfbbf8)
Location: drivers/hwmon/hwmon.c:884
Inline: True
```
**Symbols:**

```
ffffffff81dfbec0-ffffffff81dfbf00: hwmon_device_register_with_groups (STB_GLOBAL)
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
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffff800010ad1b58)
Location: drivers/hwmon/hwmon.c:703
Inline: True
```
**Symbols:**

```
ffff800010ad1d60-ffff800010ad1db8: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (c0bb28d4)
Location: drivers/hwmon/hwmon.c:703
Inline: True
```
**Symbols:**

```
c0bb2a50-c0bb2a88: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (c000000000bb68ac)
Location: drivers/hwmon/hwmon.c:703
Inline: True
```
**Symbols:**

```
c000000000bb6aa0-c000000000bb6ad8: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffe0006ce484)
Location: drivers/hwmon/hwmon.c:703
Inline: True
```
**Symbols:**

```
ffffffe0006ce5dc-ffffffe0006ce624: hwmon_device_register_with_groups (STB_GLOBAL)
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
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8182ac72)
Location: drivers/hwmon/hwmon.c:703
Inline: True
```
**Symbols:**

```
ffffffff8182add0-ffffffff8182adf2: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff817f2302)
Location: drivers/hwmon/hwmon.c:703
Inline: True
```
**Symbols:**

```
ffffffff817f2460-ffffffff817f2482: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8187a2a2)
Location: drivers/hwmon/hwmon.c:703
Inline: True
```
**Symbols:**

```
ffffffff8187a400-ffffffff8187a422: hwmon_device_register_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_with_groups(struct device *dev, const char *name, void *drvdata, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81895ca2)
Location: drivers/hwmon/hwmon.c:703
Inline: True
```
**Symbols:**

```
ffffffff81895e00-ffffffff81895e22: hwmon_device_register_with_groups (STB_GLOBAL)
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
