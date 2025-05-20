# Function: <code>regulator_get_optimal_voltage</code>

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
In drivers/regulator/core.c (ffffffff816262ce)
Location: drivers/regulator/core.c:3473
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_balance_voltage
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
In drivers/regulator/core.c (ffffffff81659716)
Location: drivers/regulator/core.c:3488
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_balance_voltage
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
In drivers/regulator/core.c (ffffffff8167ca86)
Location: drivers/regulator/core.c:3497
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_balance_voltage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int regulator_get_optimal_voltage(struct regulator_dev *rdev, int *current_uV, int *min_uV, int *max_uV, suspend_state_t state, int n_coupled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172da80)
Location: drivers/regulator/core.c:3528
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_do_balance_voltage
```
**Symbols:**

```
ffffffff8172da80-ffffffff8172de5a: regulator_get_optimal_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int regulator_get_optimal_voltage(struct regulator_dev *rdev, int *current_uV, int *min_uV, int *max_uV, suspend_state_t state, int n_coupled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8174a690)
Location: drivers/regulator/core.c:3658
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_do_balance_voltage
```
**Symbols:**

```
ffffffff8174a690-ffffffff8174aa6a: regulator_get_optimal_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172def0)
Location: drivers/regulator/core.c:3656
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_do_balance_voltage
```
**Symbols:**

```
ffffffff8172def0-ffffffff8172e2c4: regulator_get_optimal_voltage.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff817adad0)
Location: drivers/regulator/core.c:3756
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_do_balance_voltage
```
**Symbols:**

```
ffffffff817adad0-ffffffff817adead: regulator_get_optimal_voltage.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int regulator_get_optimal_voltage(struct regulator_dev *rdev, int *current_uV, int *min_uV, int *max_uV, suspend_state_t state, int n_coupled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff818e89e0)
Location: drivers/regulator/core.c:3798
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_do_balance_voltage
```
**Symbols:**

```
ffffffff818e89e0-ffffffff818e8e02: regulator_get_optimal_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regulator_get_optimal_voltage(struct regulator_dev *rdev, int *current_uV, int *min_uV, int *max_uV, suspend_state_t state, int n_coupled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3ec40)
Location: drivers/regulator/core.c:3828
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_do_balance_voltage
```
**Symbols:**

```
ffffffff81a3ec40-ffffffff81a3f062: regulator_get_optimal_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regulator_get_optimal_voltage(struct regulator_dev *rdev, int *current_uV, int *min_uV, int *max_uV, suspend_state_t state, int n_coupled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a88760)
Location: drivers/regulator/core.c:3894
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_do_balance_voltage
```
**Symbols:**

```
ffffffff81a88760-ffffffff81a88b52: regulator_get_optimal_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regulator_get_optimal_voltage(struct regulator_dev *rdev, int *current_uV, int *min_uV, int *max_uV, suspend_state_t state, int n_coupled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81adae50)
Location: drivers/regulator/core.c:3900
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_do_balance_voltage
```
**Symbols:**

```
ffffffff81adae50-ffffffff81adb242: regulator_get_optimal_voltage (STB_LOCAL)
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
In drivers/regulator/core.c (ffff80001084668c)
Location: drivers/regulator/core.c:3497
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_balance_voltage
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
In drivers/regulator/core.c (c094fe3c)
Location: drivers/regulator/core.c:3497
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_balance_voltage
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
In drivers/regulator/core.c (c0000000008e24bc)
Location: drivers/regulator/core.c:3497
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_balance_voltage
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
In drivers/regulator/core.c (ffffffe000526b9c)
Location: drivers/regulator/core.c:3497
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_balance_voltage
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
In drivers/regulator/core.c (ffffffff81642366)
Location: drivers/regulator/core.c:3497
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_balance_voltage
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
In drivers/regulator/core.c (ffffffff81622966)
Location: drivers/regulator/core.c:3497
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_balance_voltage
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
In drivers/regulator/core.c (ffffffff816708c6)
Location: drivers/regulator/core.c:3497
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_balance_voltage
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
In drivers/regulator/core.c (ffffffff8168af26)
Location: drivers/regulator/core.c:3497
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_balance_voltage
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
