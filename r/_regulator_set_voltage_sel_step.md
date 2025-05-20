# Function: <code>_regulator_set_voltage_sel_step</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81658ceb)
Location: drivers/regulator/core.c:3107
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
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
In drivers/regulator/core.c (ffffffff81678f7b)
Location: drivers/regulator/core.c:3115
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int _regulator_set_voltage_sel_step(struct regulator_dev *rdev, int uV, int new_selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172b1f0)
Location: drivers/regulator/core.c:3146
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
**Symbols:**

```
ffffffff8172b1f0-ffffffff8172b32c: _regulator_set_voltage_sel_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int _regulator_set_voltage_sel_step(struct regulator_dev *rdev, int uV, int new_selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81747e00)
Location: drivers/regulator/core.c:3276
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
**Symbols:**

```
ffffffff81747e00-ffffffff81747f3c: _regulator_set_voltage_sel_step (STB_LOCAL)
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
In drivers/regulator/core.c (ffffffff8172c3c6)
Location: drivers/regulator/core.c:3274
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
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
In drivers/regulator/core.c (ffffffff817ace06)
Location: drivers/regulator/core.c:3374
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
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
In drivers/regulator/core.c (ffffffff818e7c5d)
Location: drivers/regulator/core.c:3421
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
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
In drivers/regulator/core.c (ffffffff81a3c9eb)
Location: drivers/regulator/core.c:3453
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
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
In drivers/regulator/core.c (ffffffff81a86b7b)
Location: drivers/regulator/core.c:3519
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad9272)
Location: drivers/regulator/core.c:3525
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
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
In drivers/regulator/core.c (ffff8000108451d8)
Location: drivers/regulator/core.c:3115
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
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
In drivers/regulator/core.c (c094b3e4)
Location: drivers/regulator/core.c:3115
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
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
In drivers/regulator/core.c (c0000000008dc3a0)
Location: drivers/regulator/core.c:3115
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
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
In drivers/regulator/core.c (ffffffe000523754)
Location: drivers/regulator/core.c:3115
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
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
In drivers/regulator/core.c (ffffffff8163ea7b)
Location: drivers/regulator/core.c:3115
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
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
In drivers/regulator/core.c (ffffffff8161ee5b)
Location: drivers/regulator/core.c:3115
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
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
In drivers/regulator/core.c (ffffffff8166cdbb)
Location: drivers/regulator/core.c:3115
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
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
In drivers/regulator/core.c (ffffffff816873eb)
Location: drivers/regulator/core.c:3115
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
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
