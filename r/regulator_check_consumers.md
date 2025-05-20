# Function: <code>regulator_check_consumers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814d7ce0)
Location: drivers/regulator/core.c:244
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff814d7ce0-ffffffff814d7d6a: regulator_check_consumers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81528c20)
Location: drivers/regulator/core.c:242
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff81528c20-ffffffff81528caa: regulator_check_consumers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81555180)
Location: drivers/regulator/core.c:242
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff81555180-ffffffff8155520a: regulator_check_consumers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81569a30)
Location: drivers/regulator/core.c:242
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff81569a30-ffffffff81569abb: regulator_check_consumers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815cdc10)
Location: drivers/regulator/core.c:242
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff815cdc10-ffffffff815cdc9b: regulator_check_consumers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:291
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff81606260-ffffffff816062c3: regulator_check_consumers (STB_LOCAL)
ffffffff8160c506-ffffffff8160c546: regulator_check_consumers.cold.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:475
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
ffffffff81621270-ffffffff816212d3: regulator_check_consumers (STB_LOCAL)
ffffffff81628a84-ffffffff81628ac4: regulator_check_consumers.cold.47 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:457
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
ffffffff8165cdab-ffffffff8165cdc7: regulator_check_consumers.cold (STB_LOCAL)
ffffffff816588d0-ffffffff8165895e: regulator_check_consumers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:461
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
ffffffff8167f6d2-ffffffff8167f6ee: regulator_check_consumers.cold (STB_LOCAL)
ffffffff8167c8d0-ffffffff8167c95e: regulator_check_consumers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:464
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
```
**Symbols:**

```
ffffffff817306d8-ffffffff817306ff: regulator_check_consumers.cold (STB_LOCAL)
ffffffff8172da00-ffffffff8172da75: regulator_check_consumers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:463
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
```
**Symbols:**

```
ffffffff81c06bd7-ffffffff81c06bfe: regulator_check_consumers.cold (STB_LOCAL)
ffffffff8174a610-ffffffff8174a685: regulator_check_consumers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:463
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
```
**Symbols:**

```
ffffffff81bf8872-ffffffff81bf8899: regulator_check_consumers.cold (STB_LOCAL)
ffffffff8172de70-ffffffff8172dee7: regulator_check_consumers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:453
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
```
**Symbols:**

```
ffffffff81cf7a7c-ffffffff81cf7aa3: regulator_check_consumers.cold (STB_LOCAL)
ffffffff817ada10-ffffffff817adac5: regulator_check_consumers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:454
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
```
**Symbols:**

```
ffffffff81ebfc4f-ffffffff81ebfc75: regulator_check_consumers.cold (STB_LOCAL)
ffffffff818e8910-ffffffff818e89d7: regulator_check_consumers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3eb20)
Location: drivers/regulator/core.c:454
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
```
**Symbols:**

```
ffffffff81a3eb20-ffffffff81a3ec23: regulator_check_consumers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a88640)
Location: drivers/regulator/core.c:520
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
```
**Symbols:**

```
ffffffff81a88640-ffffffff81a88743: regulator_check_consumers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81adad30)
Location: drivers/regulator/core.c:522
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
```
**Symbols:**

```
ffffffff81adad30-ffffffff81adae33: regulator_check_consumers (STB_GLOBAL)
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
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff8000108464c0)
Location: drivers/regulator/core.c:461
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
ffff8000108464c0-ffff8000108465ac: regulator_check_consumers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094fb90)
Location: drivers/regulator/core.c:461
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
c094fb90-c094fc54: regulator_check_consumers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e2260)
Location: drivers/regulator/core.c:461
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
c0000000008e2260-c0000000008e2360: regulator_check_consumers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000526a6a)
Location: drivers/regulator/core.c:461
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
ffffffe000526a6a-ffffffe000526b1e: regulator_check_consumers (STB_GLOBAL)
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
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:461
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
ffffffff816450eb-ffffffff81645107: regulator_check_consumers.cold (STB_LOCAL)
ffffffff816421b0-ffffffff8164223e: regulator_check_consumers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:461
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
ffffffff816255b2-ffffffff816255ce: regulator_check_consumers.cold (STB_LOCAL)
ffffffff816227b0-ffffffff8162283e: regulator_check_consumers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:461
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
ffffffff81673512-ffffffff8167352e: regulator_check_consumers.cold (STB_LOCAL)
ffffffff81670710-ffffffff8167079e: regulator_check_consumers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int regulator_check_consumers(struct regulator_dev *rdev, int *min_uV, int *max_uV, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:461
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
ffffffff8168db72-ffffffff8168db8e: regulator_check_consumers.cold (STB_LOCAL)
ffffffff8168ad70-ffffffff8168adfe: regulator_check_consumers (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>suspend_state_t state</code>
</li>
</ul>
</details>
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
