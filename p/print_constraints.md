# Function: <code>print_constraints</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void print_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814d8f20)
Location: drivers/regulator/core.c:831
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff814d8f20-ffffffff814d934c: print_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void print_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152b300)
Location: drivers/regulator/core.c:804
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8152b300-ffffffff8152b75c: print_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void print_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81557900)
Location: drivers/regulator/core.c:805
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81557900-ffffffff81557d5c: print_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void print_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156c2c0)
Location: drivers/regulator/core.c:805
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8156c2c0-ffffffff8156c720: print_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void print_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d0520)
Location: drivers/regulator/core.c:805
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff815d0520-ffffffff815d0980: print_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void print_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:858
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81608240-ffffffff81608650: print_constraints (STB_LOCAL)
ffffffff8160c77c-ffffffff8160c7c6: print_constraints.cold.51 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void print_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1051
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff816248e0-ffffffff81624cf0: print_constraints (STB_LOCAL)
ffffffff81628fd7-ffffffff81629021: print_constraints.cold.58 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void print_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8165b450)
Location: drivers/regulator/core.c:1033
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8165b450-ffffffff8165b88b: print_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void print_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8167acc0)
Location: drivers/regulator/core.c:1039
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8167acc0-ffffffff8167b0fb: print_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void print_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1042
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8172d4d0-ffffffff8172d977: print_constraints (STB_LOCAL)
ffffffff81730648-ffffffff8173067b: print_constraints.cold (STB_LOCAL)
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
In drivers/regulator/core.c (ffffffff8174be6f)
Location: drivers/regulator/core.c:1136
Inline: True
Inline callers:
  - drivers/regulator/core.c:set_machine_constraints
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
In drivers/regulator/core.c (ffffffff8172f5a6)
Location: drivers/regulator/core.c:1138
Inline: True
Inline callers:
  - drivers/regulator/core.c:set_machine_constraints
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
In drivers/regulator/core.c (ffffffff817af2b8)
Location: drivers/regulator/core.c:1118
Inline: True
Inline callers:
  - drivers/regulator/core.c:set_machine_constraints
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
In drivers/regulator/core.c (ffffffff818e9d76)
Location: drivers/regulator/core.c:1143
Inline: True
Inline callers:
  - drivers/regulator/core.c:set_machine_constraints
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
In drivers/regulator/core.c (ffffffff81a40c36)
Location: drivers/regulator/core.c:1161
Inline: True
Inline callers:
  - drivers/regulator/core.c:set_machine_constraints
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
In drivers/regulator/core.c (ffffffff81a8aca8)
Location: drivers/regulator/core.c:1227
Inline: True
Inline callers:
  - drivers/regulator/core.c:set_machine_constraints
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
In drivers/regulator/core.c (ffffffff81add389)
Location: drivers/regulator/core.c:1229
Inline: True
Inline callers:
  - drivers/regulator/core.c:set_machine_constraints
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
void print_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010843138)
Location: drivers/regulator/core.c:1039
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffff800010843138-ffff80001084353c: print_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void print_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094de24)
Location: drivers/regulator/core.c:1039
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
c094de24-c094e234: print_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void print_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008df740)
Location: drivers/regulator/core.c:1039
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
c0000000008df740-c0000000008dfc28: print_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void print_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe00052512e)
Location: drivers/regulator/core.c:1039
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffe00052512e-ffffffe000525474: print_constraints (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void print_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81640850)
Location: drivers/regulator/core.c:1039
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81640850-ffffffff81640c8b: print_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void print_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81620ba0)
Location: drivers/regulator/core.c:1039
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81620ba0-ffffffff81620fdb: print_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void print_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8166eb00)
Location: drivers/regulator/core.c:1039
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8166eb00-ffffffff8166ef3b: print_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void print_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81689160)
Location: drivers/regulator/core.c:1039
Inline: False
Direct callers:
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81689160-ffffffff8168959b: print_constraints (STB_LOCAL)
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
