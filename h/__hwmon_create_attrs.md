# Function: <code>__hwmon_create_attrs</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81713ffa)
Location: drivers/hwmon/hwmon.c:511
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8172c4a2)
Location: drivers/hwmon/hwmon.c:511
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8179dc6f)
Location: drivers/hwmon/hwmon.c:518
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:518
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:536
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81852b30)
Location: drivers/hwmon/hwmon.c:536
Inline: True
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81852b30-ffffffff81852ee1: __hwmon_create_attrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81884710)
Location: drivers/hwmon/hwmon.c:551
Inline: True
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81884710-ffffffff81884a9d: __hwmon_create_attrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct attribute **__hwmon_create_attrs(const void *drvdata, const struct hwmon_chip_info *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff819538e0)
Location: drivers/hwmon/hwmon.c:656
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff819538e0-ffffffff81953a05: __hwmon_create_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct attribute **__hwmon_create_attrs(const void *drvdata, const struct hwmon_chip_info *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81958700)
Location: drivers/hwmon/hwmon.c:666
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81958700-ffffffff81958825: __hwmon_create_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:666
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:704
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:723
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:724
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:728
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct attribute **__hwmon_create_attrs(const void *drvdata, const struct hwmon_chip_info *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:728
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81dfb3b0-ffffffff81dfb825: __hwmon_create_attrs (STB_LOCAL)
ffffffff8220a78d-ffffffff8220a7d3: __hwmon_create_attrs.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (ffff800010ad13e8)
Location: drivers/hwmon/hwmon.c:551
Inline: True
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffff800010ad13e8-ffff800010ad1770: __hwmon_create_attrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct attribute **__hwmon_create_attrs(const void *drvdata, const struct hwmon_chip_info *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (c0bb213c)
Location: drivers/hwmon/hwmon.c:551
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
c0bb213c-c0bb24e4: __hwmon_create_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (c000000000bb5e40)
Location: drivers/hwmon/hwmon.c:551
Inline: True
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
c000000000bb5e40-c000000000bb6328: __hwmon_create_attrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffe0006cddee)
Location: drivers/hwmon/hwmon.c:551
Inline: True
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffe0006cddee-ffffffe0006ce136: __hwmon_create_attrs.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8182a590)
Location: drivers/hwmon/hwmon.c:551
Inline: True
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff8182a590-ffffffff8182a91d: __hwmon_create_attrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff817f1c20)
Location: drivers/hwmon/hwmon.c:551
Inline: True
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff817f1c20-ffffffff817f1fad: __hwmon_create_attrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81879bc0)
Location: drivers/hwmon/hwmon.c:551
Inline: True
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81879bc0-ffffffff81879f4d: __hwmon_create_attrs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff818955c0)
Location: drivers/hwmon/hwmon.c:551
Inline: True
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff818955c0-ffffffff8189594d: __hwmon_create_attrs.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
