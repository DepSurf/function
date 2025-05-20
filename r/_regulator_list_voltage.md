# Function: <code>_regulator_list_voltage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff814db210)
Location: drivers/regulator/core.c:2406
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff814db210-ffffffff814db2e5: _regulator_list_voltage.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152bb00)
Location: drivers/regulator/core.c:2450
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff8152bb00-ffffffff8152bbc9: _regulator_list_voltage.isra.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff81558100)
Location: drivers/regulator/core.c:2451
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff81558100-ffffffff815581c9: _regulator_list_voltage.isra.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156c790)
Location: drivers/regulator/core.c:2463
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff8156c790-ffffffff8156c860: _regulator_list_voltage.isra.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d09f0)
Location: drivers/regulator/core.c:2471
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff815d09f0-ffffffff815d0ac8: _regulator_list_voltage.isra.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev *rdev, unsigned int selector, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81607c50)
Location: drivers/regulator/core.c:2528
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_list_voltage
```
**Symbols:**

```
ffffffff81607c50-ffffffff81607d45: _regulator_list_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev *rdev, unsigned int selector, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81625ea0)
Location: drivers/regulator/core.c:2851
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
```
**Symbols:**

```
ffffffff81625ea0-ffffffff81626007: _regulator_list_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev *rdev, unsigned int selector, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816584f0)
Location: drivers/regulator/core.c:2806
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:_regulator_list_voltage
```
**Symbols:**

```
ffffffff816584f0-ffffffff81658661: _regulator_list_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev *rdev, unsigned int selector, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8167c410)
Location: drivers/regulator/core.c:2814
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:_regulator_list_voltage
```
**Symbols:**

```
ffffffff8167c410-ffffffff8167c581: _regulator_list_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev *rdev, unsigned int selector, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172a5c0)
Location: drivers/regulator/core.c:2845
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
```
**Symbols:**

```
ffffffff8172a5c0-ffffffff8172a738: _regulator_list_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev *rdev, unsigned int selector, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81747130)
Location: drivers/regulator/core.c:2971
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
```
**Symbols:**

```
ffffffff81747130-ffffffff81747299: _regulator_list_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev *rdev, unsigned int selector, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172aae0)
Location: drivers/regulator/core.c:2969
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
```
**Symbols:**

```
ffffffff8172aae0-ffffffff8172ac42: _regulator_list_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev *rdev, unsigned int selector, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817ab510)
Location: drivers/regulator/core.c:3069
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
```
**Symbols:**

```
ffffffff817ab510-ffffffff817ab6ce: _regulator_list_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev *rdev, unsigned int selector, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff818e61d0)
Location: drivers/regulator/core.c:3116
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
```
**Symbols:**

```
ffffffff818e61d0-ffffffff818e638f: _regulator_list_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev *rdev, unsigned int selector, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3a730)
Location: drivers/regulator/core.c:3148
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
```
**Symbols:**

```
ffffffff81a3a730-ffffffff81a3a8ef: _regulator_list_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev *rdev, unsigned int selector, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a84140)
Location: drivers/regulator/core.c:3214
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
```
**Symbols:**

```
ffffffff81a84140-ffffffff81a842ff: _regulator_list_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev *rdev, unsigned int selector, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad68f0)
Location: drivers/regulator/core.c:3220
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
```
**Symbols:**

```
ffffffff81ad68f0-ffffffff81ad6aaf: _regulator_list_voltage (STB_LOCAL)
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
int _regulator_list_voltage(struct regulator_dev *rdev, unsigned int selector, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010845f28)
Location: drivers/regulator/core.c:2814
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:_regulator_list_voltage
```
**Symbols:**

```
ffff800010845f28-ffff8000108460c8: _regulator_list_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev *rdev, unsigned int selector, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094f67c)
Location: drivers/regulator/core.c:2814
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:_regulator_list_voltage
```
**Symbols:**

```
c094f67c-c094f80c: _regulator_list_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev *rdev, unsigned int selector, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e1a40)
Location: drivers/regulator/core.c:2814
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
```
**Symbols:**

```
c0000000008e1a40-c0000000008e1c88: _regulator_list_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev *rdev, unsigned int selector, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000526634)
Location: drivers/regulator/core.c:2814
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
```
**Symbols:**

```
ffffffe000526634-ffffffe000526776: _regulator_list_voltage (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev *rdev, unsigned int selector, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81641cf0)
Location: drivers/regulator/core.c:2814
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:_regulator_list_voltage
```
**Symbols:**

```
ffffffff81641cf0-ffffffff81641e61: _regulator_list_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev *rdev, unsigned int selector, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816222f0)
Location: drivers/regulator/core.c:2814
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:_regulator_list_voltage
```
**Symbols:**

```
ffffffff816222f0-ffffffff81622461: _regulator_list_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev *rdev, unsigned int selector, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81670250)
Location: drivers/regulator/core.c:2814
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:_regulator_list_voltage
```
**Symbols:**

```
ffffffff81670250-ffffffff816703c1: _regulator_list_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int _regulator_list_voltage(struct regulator_dev *rdev, unsigned int selector, int lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8168a8b0)
Location: drivers/regulator/core.c:2814
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_time
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:_regulator_list_voltage
```
**Symbols:**

```
ffffffff8168a8b0-ffffffff8168aa21: _regulator_list_voltage (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
