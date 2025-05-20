# Function: <code>regulator_balance_voltage</code>

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
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int regulator_balance_voltage(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3615
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff81626230-ffffffff8162688f: regulator_balance_voltage (STB_LOCAL)
ffffffff81629119-ffffffff8162916f: regulator_balance_voltage.cold.63 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int regulator_balance_voltage(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3631
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff816595f0-ffffffff81659ad2: regulator_balance_voltage (STB_LOCAL)
ffffffff8165ce28-ffffffff8165ce3c: regulator_balance_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int regulator_balance_voltage(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3640
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff8167c960-ffffffff8167ce42: regulator_balance_voltage (STB_LOCAL)
ffffffff8167f6ee-ffffffff8167f702: regulator_balance_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regulator_balance_voltage(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3754
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff8172e170-ffffffff8172e1b4: regulator_balance_voltage (STB_LOCAL)
ffffffff817306ff-ffffffff8173071b: regulator_balance_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regulator_balance_voltage(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3884
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff8174ad80-ffffffff8174adc4: regulator_balance_voltage (STB_LOCAL)
ffffffff81c06bfe-ffffffff81c06c1a: regulator_balance_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int regulator_balance_voltage(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3882
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff8172e450-ffffffff8172e494: regulator_balance_voltage (STB_LOCAL)
ffffffff81bf8899-ffffffff81bf88b5: regulator_balance_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regulator_balance_voltage(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3982
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_sync_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff817ae030-ffffffff817ae074: regulator_balance_voltage (STB_LOCAL)
ffffffff81cf7aa3-ffffffff81cf7abf: regulator_balance_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regulator_balance_voltage(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4024
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_sync_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff818e8fd0-ffffffff818e902c: regulator_balance_voltage (STB_LOCAL)
ffffffff81ebfc75-ffffffff81ebfc91: regulator_balance_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regulator_balance_voltage(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3f240)
Location: drivers/regulator/core.c:4054
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_sync_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff81a3f240-ffffffff81a3f2e1: regulator_balance_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regulator_balance_voltage(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a88d50)
Location: drivers/regulator/core.c:4120
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_sync_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff81a88d50-ffffffff81a88df1: regulator_balance_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regulator_balance_voltage(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81adb440)
Location: drivers/regulator/core.c:4126
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_sync_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff81adb440-ffffffff81adb4e1: regulator_balance_voltage (STB_LOCAL)
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
int regulator_balance_voltage(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff8000108465b0)
Location: drivers/regulator/core.c:3640
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffff8000108465b0-ffff8000108469e0: regulator_balance_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_balance_voltage(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094fc54)
Location: drivers/regulator/core.c:3640
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
c094fc54-c0950170: regulator_balance_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regulator_balance_voltage(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e2360)
Location: drivers/regulator/core.c:3640
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
c0000000008e2360-c0000000008e29cc: regulator_balance_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_balance_voltage(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000526b1e)
Location: drivers/regulator/core.c:3640
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffe000526b1e-ffffffe000526f10: regulator_balance_voltage (STB_LOCAL)
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
int regulator_balance_voltage(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3640
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff81642240-ffffffff81642722: regulator_balance_voltage (STB_LOCAL)
ffffffff81645107-ffffffff8164511b: regulator_balance_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int regulator_balance_voltage(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3640
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff81622840-ffffffff81622d22: regulator_balance_voltage (STB_LOCAL)
ffffffff816255ce-ffffffff816255e2: regulator_balance_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int regulator_balance_voltage(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3640
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff816707a0-ffffffff81670c82: regulator_balance_voltage (STB_LOCAL)
ffffffff8167352e-ffffffff81673542: regulator_balance_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int regulator_balance_voltage(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3640
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff8168ae00-ffffffff8168b2e2: regulator_balance_voltage (STB_LOCAL)
ffffffff8168db8e-ffffffff8168dba2: regulator_balance_voltage.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
