# Function: <code>regulator_check_voltage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814d94d0)
Location: drivers/regulator/core.c:213
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff814d94d0-ffffffff814d95c8: regulator_check_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152b760)
Location: drivers/regulator/core.c:215
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff8152b760-ffffffff8152b865: regulator_check_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81557d60)
Location: drivers/regulator/core.c:215
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff81557d60-ffffffff81557e65: regulator_check_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156bfb0)
Location: drivers/regulator/core.c:215
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff8156bfb0-ffffffff8156c0a6: regulator_check_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d0200)
Location: drivers/regulator/core.c:215
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff815d0200-ffffffff815d02f6: regulator_check_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:258
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff81607b00-ffffffff81607b66: regulator_check_voltage (STB_LOCAL)
ffffffff8160c6b2-ffffffff8160c755: regulator_check_voltage.cold.49 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:442
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff816232f0-ffffffff81623356: regulator_check_voltage (STB_LOCAL)
ffffffff81628db6-ffffffff81628e59: regulator_check_voltage.cold.55 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:424
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff8165cd8f-ffffffff8165cdab: regulator_check_voltage.cold (STB_LOCAL)
ffffffff816587e0-ffffffff816588cd: regulator_check_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:428
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff8167f6b6-ffffffff8167f6d2: regulator_check_voltage.cold (STB_LOCAL)
ffffffff8167c7e0-ffffffff8167c8cd: regulator_check_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:431
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff8173067b-ffffffff817306d8: regulator_check_voltage.cold (STB_LOCAL)
ffffffff8172d980-ffffffff8172d9ff: regulator_check_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:430
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff81c06b7a-ffffffff81c06bd7: regulator_check_voltage.cold (STB_LOCAL)
ffffffff8174a590-ffffffff8174a60f: regulator_check_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:430
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff81bf8815-ffffffff81bf8872: regulator_check_voltage.cold (STB_LOCAL)
ffffffff8172ddf0-ffffffff8172de6f: regulator_check_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:420
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff81cf7a1f-ffffffff81cf7a7c: regulator_check_voltage.cold (STB_LOCAL)
ffffffff817ad990-ffffffff817ada0f: regulator_check_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:421
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff81ebfbf2-ffffffff81ebfc4f: regulator_check_voltage.cold (STB_LOCAL)
ffffffff818e8880-ffffffff818e890a: regulator_check_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3e9f0)
Location: drivers/regulator/core.c:421
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff81a3e9f0-ffffffff81a3eb09: regulator_check_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a88510)
Location: drivers/regulator/core.c:487
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff81a88510-ffffffff81a88629: regulator_check_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81adac00)
Location: drivers/regulator/core.c:489
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff81adac00-ffffffff81adad19: regulator_check_voltage (STB_GLOBAL)
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
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010846398)
Location: drivers/regulator/core.c:428
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffff800010846398-ffff8000108464bc: regulator_check_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094fa64)
Location: drivers/regulator/core.c:428
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
c094fa64-c094fb90: regulator_check_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e20e0)
Location: drivers/regulator/core.c:428
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
c0000000008e20e0-c0000000008e2260: regulator_check_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe00052698c)
Location: drivers/regulator/core.c:428
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffe00052698c-ffffffe000526a6a: regulator_check_voltage (STB_GLOBAL)
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
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:428
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff816450cf-ffffffff816450eb: regulator_check_voltage.cold (STB_LOCAL)
ffffffff816420c0-ffffffff816421ad: regulator_check_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:428
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff81625596-ffffffff816255b2: regulator_check_voltage.cold (STB_LOCAL)
ffffffff816226c0-ffffffff816227ad: regulator_check_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:428
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff816734f6-ffffffff81673512: regulator_check_voltage.cold (STB_LOCAL)
ffffffff81670620-ffffffff8167070d: regulator_check_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int regulator_check_voltage(struct regulator_dev *rdev, int *min_uV, int *max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:428
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff8168db56-ffffffff8168db72: regulator_check_voltage.cold (STB_LOCAL)
ffffffff8168ac80-ffffffff8168ad6d: regulator_check_voltage (STB_GLOBAL)
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
