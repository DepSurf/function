# Function: <code>_regulator_get_error_flags</code>

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
In drivers/regulator/core.c (ffffffff815556c5)
Location: drivers/regulator/core.c:3363
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_error_flags
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
In drivers/regulator/core.c (ffffffff81569ce5)
Location: drivers/regulator/core.c:3386
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_error_flags
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
In drivers/regulator/core.c (ffffffff815cdec5)
Location: drivers/regulator/core.c:3394
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_error_flags
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
In drivers/regulator/core.c (ffffffff81608b27)
Location: drivers/regulator/core.c:3568
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_error_flags
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
In drivers/regulator/core.c (ffffffff81624435)
Location: drivers/regulator/core.c:4179
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_error_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816570f6)
Location: drivers/regulator/core.c:4199
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_error_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8167a9f6)
Location: drivers/regulator/core.c:4209
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_error_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817298e6)
Location: drivers/regulator/core.c:4249
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_error_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817463f6)
Location: drivers/regulator/core.c:4387
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_error_flags
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
In drivers/regulator/core.c (ffffffff81729e06)
Location: drivers/regulator/core.c:4389
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_error_flags
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
In drivers/regulator/core.c (ffffffff817aab69)
Location: drivers/regulator/core.c:4524
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_error_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _regulator_get_error_flags(struct regulator_dev *rdev, unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4569
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:over_temp_warn_show
  - drivers/regulator/core.c:over_voltage_warn_show
  - drivers/regulator/core.c:over_current_warn_show
  - drivers/regulator/core.c:under_voltage_warn_show
  - drivers/regulator/core.c:over_temp_show
  - drivers/regulator/core.c:fail_show
  - drivers/regulator/core.c:regulation_out_show
  - drivers/regulator/core.c:over_current_show
  - drivers/regulator/core.c:under_voltage_show
```
**Symbols:**

```
ffffffff818e4910-ffffffff818e4aae: _regulator_get_error_flags (STB_LOCAL)
ffffffff81ebf824-ffffffff81ebf84e: _regulator_get_error_flags.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int _regulator_get_error_flags(struct regulator_dev *rdev, unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4599
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:over_temp_warn_show
  - drivers/regulator/core.c:over_voltage_warn_show
  - drivers/regulator/core.c:over_current_warn_show
  - drivers/regulator/core.c:under_voltage_warn_show
  - drivers/regulator/core.c:over_temp_show
  - drivers/regulator/core.c:fail_show
  - drivers/regulator/core.c:regulation_out_show
  - drivers/regulator/core.c:over_current_show
  - drivers/regulator/core.c:under_voltage_show
```
**Symbols:**

```
ffffffff81a394e0-ffffffff81a3967e: _regulator_get_error_flags (STB_LOCAL)
ffffffff82094aea-ffffffff82094b14: _regulator_get_error_flags.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int _regulator_get_error_flags(struct regulator_dev *rdev, unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4665
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:over_temp_warn_show
  - drivers/regulator/core.c:over_voltage_warn_show
  - drivers/regulator/core.c:over_current_warn_show
  - drivers/regulator/core.c:under_voltage_warn_show
  - drivers/regulator/core.c:over_temp_show
  - drivers/regulator/core.c:fail_show
  - drivers/regulator/core.c:regulation_out_show
  - drivers/regulator/core.c:over_current_show
  - drivers/regulator/core.c:under_voltage_show
```
**Symbols:**

```
ffffffff81a830c0-ffffffff81a8325e: _regulator_get_error_flags (STB_LOCAL)
ffffffff8211590e-ffffffff82115938: _regulator_get_error_flags.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int _regulator_get_error_flags(struct regulator_dev *rdev, unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4671
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:over_temp_warn_show
  - drivers/regulator/core.c:over_voltage_warn_show
  - drivers/regulator/core.c:over_current_warn_show
  - drivers/regulator/core.c:under_voltage_warn_show
  - drivers/regulator/core.c:over_temp_show
  - drivers/regulator/core.c:fail_show
  - drivers/regulator/core.c:regulation_out_show
  - drivers/regulator/core.c:over_current_show
  - drivers/regulator/core.c:under_voltage_show
```
**Symbols:**

```
ffffffff81ad5870-ffffffff81ad5a0e: _regulator_get_error_flags (STB_LOCAL)
ffffffff821f35c5-ffffffff821f35ef: _regulator_get_error_flags.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010842e20)
Location: drivers/regulator/core.c:4209
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_error_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094d9b0)
Location: drivers/regulator/core.c:4209
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_error_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008df0a0)
Location: drivers/regulator/core.c:4209
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_error_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000524f42)
Location: drivers/regulator/core.c:4209
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_error_flags
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816404f6)
Location: drivers/regulator/core.c:4209
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_error_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816208d6)
Location: drivers/regulator/core.c:4209
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_error_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8166e836)
Location: drivers/regulator/core.c:4209
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_error_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81688e96)
Location: drivers/regulator/core.c:4209
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_error_flags
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
