# Function: <code>regulator_set_voltage_rdev</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81626476)
Location: drivers/regulator/core.c:3373
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_balance_voltage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int regulator_set_voltage_rdev(struct regulator_dev *rdev, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3388
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
ffffffff8165cdf1-ffffffff8165ce28: regulator_set_voltage_rdev.cold (STB_LOCAL)
ffffffff816593c0-ffffffff816595eb: regulator_set_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int regulator_set_voltage_rdev(struct regulator_dev *rdev, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3396
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
ffffffff8167f9be-ffffffff8167f9f5: regulator_set_voltage_rdev.cold (STB_LOCAL)
ffffffff8167e890-ffffffff8167eabb: regulator_set_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regulator_set_voltage_rdev(struct regulator_dev *rdev, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3427
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_do_balance_voltage
```
**Symbols:**

```
ffffffff81730bdb-ffffffff81730c39: regulator_set_voltage_rdev.cold (STB_LOCAL)
ffffffff8172fb70-ffffffff8172fdb1: regulator_set_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regulator_set_voltage_rdev(struct regulator_dev *rdev, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3557
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_do_balance_voltage
```
**Symbols:**

```
ffffffff81c07184-ffffffff81c071e4: regulator_set_voltage_rdev.cold (STB_LOCAL)
ffffffff8174c840-ffffffff8174ca81: regulator_set_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int regulator_set_voltage_rdev(struct regulator_dev *rdev, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3555
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_do_balance_voltage
```
**Symbols:**

```
ffffffff81bf8e31-ffffffff81bf8e91: regulator_set_voltage_rdev.cold (STB_LOCAL)
ffffffff817300e0-ffffffff81730323: regulator_set_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regulator_set_voltage_rdev(struct regulator_dev *rdev, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3655
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_do_balance_voltage
```
**Symbols:**

```
ffffffff81cf81b3-ffffffff81cf8213: regulator_set_voltage_rdev.cold (STB_LOCAL)
ffffffff817aff00-ffffffff817b0143: regulator_set_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regulator_set_voltage_rdev(struct regulator_dev *rdev, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3697
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_do_balance_voltage
```
**Symbols:**

```
ffffffff81ec0296-ffffffff81ec02eb: regulator_set_voltage_rdev.cold (STB_LOCAL)
ffffffff818eb370-ffffffff818eb58c: regulator_set_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regulator_set_voltage_rdev(struct regulator_dev *rdev, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a420f0)
Location: drivers/regulator/core.c:3727
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_do_balance_voltage
```
**Symbols:**

```
ffffffff81a420f0-ffffffff81a42376: regulator_set_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regulator_set_voltage_rdev(struct regulator_dev *rdev, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a8c1f0)
Location: drivers/regulator/core.c:3793
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_do_balance_voltage
```
**Symbols:**

```
ffffffff81a8c1f0-ffffffff81a8c46f: regulator_set_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regulator_set_voltage_rdev(struct regulator_dev *rdev, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ade9f0)
Location: drivers/regulator/core.c:3799
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_do_balance_voltage
```
**Symbols:**

```
ffffffff81ade9f0-ffffffff81adec6f: regulator_set_voltage_rdev (STB_GLOBAL)
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
int regulator_set_voltage_rdev(struct regulator_dev *rdev, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010848720)
Location: drivers/regulator/core.c:3396
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
ffff800010848720-ffff80001084894c: regulator_set_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_set_voltage_rdev(struct regulator_dev *rdev, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0951f10)
Location: drivers/regulator/core.c:3396
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
c0951f10-c095215c: regulator_set_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regulator_set_voltage_rdev(struct regulator_dev *rdev, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e54b0)
Location: drivers/regulator/core.c:3396
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
c0000000008e54b0-c0000000008e5814: regulator_set_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_set_voltage_rdev(struct regulator_dev *rdev, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe0005289b8)
Location: drivers/regulator/core.c:3396
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
ffffffe0005289b8-ffffffe000528b9a: regulator_set_voltage_rdev (STB_GLOBAL)
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
int regulator_set_voltage_rdev(struct regulator_dev *rdev, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3396
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
ffffffff8164543e-ffffffff81645475: regulator_set_voltage_rdev.cold (STB_LOCAL)
ffffffff816442f0-ffffffff8164451b: regulator_set_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int regulator_set_voltage_rdev(struct regulator_dev *rdev, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3396
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
ffffffff8162589e-ffffffff816258d5: regulator_set_voltage_rdev.cold (STB_LOCAL)
ffffffff81624770-ffffffff8162499b: regulator_set_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int regulator_set_voltage_rdev(struct regulator_dev *rdev, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3396
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
ffffffff816737fe-ffffffff81673835: regulator_set_voltage_rdev.cold (STB_LOCAL)
ffffffff816726d0-ffffffff816728fb: regulator_set_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int regulator_set_voltage_rdev(struct regulator_dev *rdev, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3396
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
ffffffff8168de5e-ffffffff8168de95: regulator_set_voltage_rdev.cold (STB_LOCAL)
ffffffff8168cd30-ffffffff8168cf5b: regulator_set_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
