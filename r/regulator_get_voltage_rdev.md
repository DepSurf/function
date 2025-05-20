# Function: <code>regulator_get_voltage_rdev</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff81658a14)
Location: drivers/regulator/core.c:3979
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:regulator_uV_show
```
**Symbols:**

```
ffffffff8165cdc7-ffffffff8165cddd: regulator_get_voltage_rdev.cold (STB_LOCAL)
ffffffff81658990-ffffffff81658ad3: regulator_get_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff81678ca4)
Location: drivers/regulator/core.c:3988
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:regulator_uV_show
```
**Symbols:**

```
ffffffff8167f4d1-ffffffff8167f4e7: regulator_get_voltage_rdev.cold (STB_LOCAL)
ffffffff81678c20-ffffffff81678d63: regulator_get_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4028
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:regulator_uV_show
```
**Symbols:**

```
ffffffff817301ad-ffffffff817301ce: regulator_get_voltage_rdev.cold (STB_LOCAL)
ffffffff8172b010-ffffffff8172b127: regulator_get_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4164
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:regulator_uV_show
```
**Symbols:**

```
ffffffff81c066d2-ffffffff81c066f3: regulator_get_voltage_rdev.cold (STB_LOCAL)
ffffffff81747c10-ffffffff81747d3b: regulator_get_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4166
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:regulator_uV_show
```
**Symbols:**

```
ffffffff81bf835e-ffffffff81bf837f: regulator_get_voltage_rdev.cold (STB_LOCAL)
ffffffff8172b4a0-ffffffff8172b5cb: regulator_get_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4289
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:microvolts_show
```
**Symbols:**

```
ffffffff81cf746d-ffffffff81cf74a2: regulator_get_voltage_rdev.cold (STB_LOCAL)
ffffffff817a79a0-ffffffff817a7adb: regulator_get_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4334
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:microvolts_show
```
**Symbols:**

```
ffffffff81ebf641-ffffffff81ebf672: regulator_get_voltage_rdev.cold (STB_LOCAL)
ffffffff818e21f0-ffffffff818e2340: regulator_get_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4364
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:microvolts_show
```
**Symbols:**

```
ffffffff82094b29-ffffffff82094b3e: regulator_get_voltage_rdev.cold (STB_LOCAL)
ffffffff81a3c400-ffffffff81a3c581: regulator_get_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4430
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:microvolts_show
```
**Symbols:**

```
ffffffff8211594d-ffffffff82115962: regulator_get_voltage_rdev.cold (STB_LOCAL)
ffffffff81a85f60-ffffffff81a860e1: regulator_get_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4436
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_get_voltage_rdev
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_get_optimal_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:drms_uA_update
  - drivers/regulator/core.c:microvolts_show
```
**Symbols:**

```
ffffffff821f3604-ffffffff821f3619: regulator_get_voltage_rdev.cold (STB_LOCAL)
ffffffff81ad8720-ffffffff81ad88a1: regulator_get_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010841810)
Location: drivers/regulator/core.c:3988
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:regulator_uV_show
```
**Symbols:**

```
ffff800010841810-ffff80001084196c: regulator_get_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094ae58)
Location: drivers/regulator/core.c:3988
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:machine_constraints_voltage
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:regulator_uV_show
```
**Symbols:**

```
c094ae58-c094afe4: regulator_get_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008dbf30)
Location: drivers/regulator/core.c:3988
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:regulator_uV_show
```
**Symbols:**

```
c0000000008dbf30-c0000000008dc11c: regulator_get_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe0005234ea)
Location: drivers/regulator/core.c:3988
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:regulator_uV_show
```
**Symbols:**

```
ffffffe0005234ea-ffffffe0005235ce: regulator_get_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff8163e7a4)
Location: drivers/regulator/core.c:3988
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:regulator_uV_show
```
**Symbols:**

```
ffffffff81644eea-ffffffff81644f00: regulator_get_voltage_rdev.cold (STB_LOCAL)
ffffffff8163e720-ffffffff8163e863: regulator_get_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff8161eb84)
Location: drivers/regulator/core.c:3988
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:regulator_uV_show
```
**Symbols:**

```
ffffffff816253b1-ffffffff816253c7: regulator_get_voltage_rdev.cold (STB_LOCAL)
ffffffff8161eb00-ffffffff8161ec43: regulator_get_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff8166cae4)
Location: drivers/regulator/core.c:3988
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:regulator_uV_show
```
**Symbols:**

```
ffffffff81673311-ffffffff81673327: regulator_get_voltage_rdev.cold (STB_LOCAL)
ffffffff8166ca60-ffffffff8166cba3: regulator_get_voltage_rdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_get_voltage_rdev(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff81687114)
Location: drivers/regulator/core.c:3988
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_call_set_voltage_sel
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:regulator_uV_show
```
**Symbols:**

```
ffffffff8168d971-ffffffff8168d987: regulator_get_voltage_rdev.cold (STB_LOCAL)
ffffffff81687090-ffffffff816871d3: regulator_get_voltage_rdev (STB_GLOBAL)
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
