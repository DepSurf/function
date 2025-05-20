# Function: <code>_regulator_do_set_voltage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814dac00)
Location: drivers/regulator/core.c:2730
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff814dac00-ffffffff814db0be: _regulator_do_set_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152a820)
Location: drivers/regulator/core.c:2746
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8152a820-ffffffff8152acdd: _regulator_do_set_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81556e30)
Location: drivers/regulator/core.c:2765
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81556e30-ffffffff815572dc: _regulator_do_set_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156b4e0)
Location: drivers/regulator/core.c:2785
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8156b4e0-ffffffff8156b9ae: _regulator_do_set_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815cf6e0)
Location: drivers/regulator/core.c:2793
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff815cf6e0-ffffffff815cfbd2: _regulator_do_set_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2850
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff816075e0-ffffffff81607a7f: _regulator_do_set_voltage (STB_LOCAL)
ffffffff8160c5be-ffffffff8160c5fa: _regulator_do_set_voltage.cold.47 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3178
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81622d20-ffffffff816231bf: _regulator_do_set_voltage (STB_LOCAL)
ffffffff81628cc2-ffffffff81628cfe: _regulator_do_set_voltage.cold.53 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3193
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffff81658ba0-ffffffff81659133: _regulator_do_set_voltage (STB_LOCAL)
ffffffff8165cddd-ffffffff8165cdf1: _regulator_do_set_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3201
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffff81678e30-ffffffff816793c3: _regulator_do_set_voltage (STB_LOCAL)
ffffffff8167f4e7-ffffffff8167f4fb: _regulator_do_set_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3232
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
```
**Symbols:**

```
ffffffff8172b8b0-ffffffff8172bd3a: _regulator_do_set_voltage (STB_LOCAL)
ffffffff817301ce-ffffffff817301ed: _regulator_do_set_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3362
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
```
**Symbols:**

```
ffffffff817489a0-ffffffff81748ddd: _regulator_do_set_voltage (STB_LOCAL)
ffffffff81c066f3-ffffffff81c06712: _regulator_do_set_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3360
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
```
**Symbols:**

```
ffffffff8172c0f0-ffffffff8172c678: _regulator_do_set_voltage (STB_LOCAL)
ffffffff81bf837f-ffffffff81bf839e: _regulator_do_set_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3460
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
```
**Symbols:**

```
ffffffff817acb30-ffffffff817ad0be: _regulator_do_set_voltage (STB_LOCAL)
ffffffff81cf78e1-ffffffff81cf7900: _regulator_do_set_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3507
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
```
**Symbols:**

```
ffffffff818e79a0-ffffffff818e7f61: _regulator_do_set_voltage (STB_LOCAL)
ffffffff81ebfaa6-ffffffff81ebfacf: _regulator_do_set_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3c730)
Location: drivers/regulator/core.c:3537
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
```
**Symbols:**

```
ffffffff81a3c730-ffffffff81a3cd33: _regulator_do_set_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a868c0)
Location: drivers/regulator/core.c:3603
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
```
**Symbols:**

```
ffffffff81a868c0-ffffffff81a86ec3: _regulator_do_set_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad8fc0)
Location: drivers/regulator/core.c:3609
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
```
**Symbols:**

```
ffffffff81ad8fc0-ffffffff81ad95b9: _regulator_do_set_voltage (STB_LOCAL)
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
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff8000108450c0)
Location: drivers/regulator/core.c:3201
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffff8000108450c0-ffff800010845648: _regulator_do_set_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094b0ac)
Location: drivers/regulator/core.c:3201
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
```
**Symbols:**

```
c094b0ac-c094b6c8: _regulator_do_set_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008dc220)
Location: drivers/regulator/core.c:3201
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
c0000000008dc220-c0000000008dc94c: _regulator_do_set_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe00052365e)
Location: drivers/regulator/core.c:3201
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffe00052365e-ffffffe000523a96: _regulator_do_set_voltage (STB_LOCAL)
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
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3201
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffff8163e930-ffffffff8163eec3: _regulator_do_set_voltage (STB_LOCAL)
ffffffff81644f00-ffffffff81644f14: _regulator_do_set_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3201
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffff8161ed10-ffffffff8161f2a3: _regulator_do_set_voltage (STB_LOCAL)
ffffffff816253c7-ffffffff816253db: _regulator_do_set_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3201
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffff8166cc70-ffffffff8166d203: _regulator_do_set_voltage (STB_LOCAL)
ffffffff81673327-ffffffff8167333b: _regulator_do_set_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int _regulator_do_set_voltage(struct regulator_dev *rdev, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3201
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffff816872a0-ffffffff81687865: _regulator_do_set_voltage (STB_LOCAL)
ffffffff8168d987-ffffffff8168d99b: _regulator_do_set_voltage.cold (STB_LOCAL)
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
