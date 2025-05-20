# Function: <code>machine_constraints_voltage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814dca72)
Location: drivers/regulator/core.c:901
Inline: True
Inline callers:
  - drivers/regulator/core.c:set_machine_constraints
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152d052)
Location: drivers/regulator/core.c:874
Inline: True
Inline callers:
  - drivers/regulator/core.c:set_machine_constraints
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8155a342)
Location: drivers/regulator/core.c:875
Inline: True
Inline callers:
  - drivers/regulator/core.c:set_machine_constraints
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
In drivers/regulator/core.c (ffffffff8156e662)
Location: drivers/regulator/core.c:875
Inline: True
Inline callers:
  - drivers/regulator/core.c:set_machine_constraints
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
In drivers/regulator/core.c (ffffffff815d28f2)
Location: drivers/regulator/core.c:875
Inline: True
Inline callers:
  - drivers/regulator/core.c:set_machine_constraints
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
In drivers/regulator/core.c (ffffffff8160ac4e)
Location: drivers/regulator/core.c:928
Inline: True
Inline callers:
  - drivers/regulator/core.c:set_machine_constraints
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
In drivers/regulator/core.c (ffffffff8162749e)
Location: drivers/regulator/core.c:1121
Inline: True
Inline callers:
  - drivers/regulator/core.c:set_machine_constraints
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1103
Inline: True
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8165b140-ffffffff8165b446: machine_constraints_voltage.isra.0 (STB_LOCAL)
ffffffff8165d17b-ffffffff8165d26a: machine_constraints_voltage.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1109
Inline: True
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff816797c0-ffffffff81679ac6: machine_constraints_voltage.isra.0 (STB_LOCAL)
ffffffff8167f4fb-ffffffff8167f5ea: machine_constraints_voltage.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int machine_constraints_voltage(struct regulator_dev *rdev, struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1112
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8172bd40-ffffffff8172bfdb: machine_constraints_voltage (STB_LOCAL)
ffffffff817301ed-ffffffff817302dc: machine_constraints_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int machine_constraints_voltage(struct regulator_dev *rdev, struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1148
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81748de0-ffffffff8174907b: machine_constraints_voltage (STB_LOCAL)
ffffffff81c06712-ffffffff81c06801: machine_constraints_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int machine_constraints_voltage(struct regulator_dev *rdev, struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1150
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8172c680-ffffffff8172c92c: machine_constraints_voltage (STB_LOCAL)
ffffffff81bf839e-ffffffff81bf84a1: machine_constraints_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int machine_constraints_voltage(struct regulator_dev *rdev, struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1130
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff817ad6e0-ffffffff817ad98c: machine_constraints_voltage (STB_LOCAL)
ffffffff81cf791c-ffffffff81cf7a1f: machine_constraints_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int machine_constraints_voltage(struct regulator_dev *rdev, struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1155
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff818e85c0-ffffffff818e887d: machine_constraints_voltage (STB_LOCAL)
ffffffff81ebfaeb-ffffffff81ebfbf2: machine_constraints_voltage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int machine_constraints_voltage(struct regulator_dev *rdev, struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3dab0)
Location: drivers/regulator/core.c:1173
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81a3dab0-ffffffff81a3defd: machine_constraints_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int machine_constraints_voltage(struct regulator_dev *rdev, struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a87c20)
Location: drivers/regulator/core.c:1239
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81a87c20-ffffffff81a8807c: machine_constraints_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int machine_constraints_voltage(struct regulator_dev *rdev, struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ada310)
Location: drivers/regulator/core.c:1241
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81ada310-ffffffff81ada76c: machine_constraints_voltage (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffff800010845648)
Location: drivers/regulator/core.c:1109
Inline: True
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffff800010845648-ffff800010845a1c: machine_constraints_voltage.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int machine_constraints_voltage(struct regulator_dev *rdev, struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094b6c8)
Location: drivers/regulator/core.c:1109
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
c094b6c8-c094bb00: machine_constraints_voltage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (c0000000008dcf60)
Location: drivers/regulator/core.c:1109
Inline: True
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
c0000000008dcf60-c0000000008dd4d8: machine_constraints_voltage.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffe000523e00)
Location: drivers/regulator/core.c:1109
Inline: True
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffe000523e00-ffffffe00052413a: machine_constraints_voltage.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1109
Inline: True
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8163f2c0-ffffffff8163f5c6: machine_constraints_voltage.isra.0 (STB_LOCAL)
ffffffff81644f14-ffffffff81645003: machine_constraints_voltage.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1109
Inline: True
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8161f6a0-ffffffff8161f9a6: machine_constraints_voltage.isra.0 (STB_LOCAL)
ffffffff816253db-ffffffff816254ca: machine_constraints_voltage.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1109
Inline: True
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8166d600-ffffffff8166d906: machine_constraints_voltage.isra.0 (STB_LOCAL)
ffffffff8167333b-ffffffff8167342a: machine_constraints_voltage.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1109
Inline: True
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81687c60-ffffffff81687f66: machine_constraints_voltage.isra.0 (STB_LOCAL)
ffffffff8168d99b-ffffffff8168da8a: machine_constraints_voltage.isra.0.cold (STB_LOCAL)
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
</ul>
