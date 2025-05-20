# Function: <code>set_machine_constraints</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev, const struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814dca20)
Location: drivers/regulator/core.c:1043
Inline: False
```
**Symbols:**

```
ffffffff814dca20-ffffffff814dd295: set_machine_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev, const struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152d000)
Location: drivers/regulator/core.c:1036
Inline: False
```
**Symbols:**

```
ffffffff8152d000-ffffffff8152d950: set_machine_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev, const struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8155a2f0)
Location: drivers/regulator/core.c:1037
Inline: False
```
**Symbols:**

```
ffffffff8155a2f0-ffffffff8155ac40: set_machine_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev, const struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156e610)
Location: drivers/regulator/core.c:1037
Inline: False
```
**Symbols:**

```
ffffffff8156e610-ffffffff8156ef3d: set_machine_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev, const struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d28a0)
Location: drivers/regulator/core.c:1037
Inline: False
```
**Symbols:**

```
ffffffff815d28a0-ffffffff815d31ea: set_machine_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev, const struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1102
Inline: False
```
**Symbols:**

```
ffffffff8160ac00-ffffffff8160b100: set_machine_constraints (STB_LOCAL)
ffffffff8160cdb6-ffffffff8160d277: set_machine_constraints.cold.66 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev, const struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1295
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff81627450-ffffffff816279b6: set_machine_constraints (STB_LOCAL)
ffffffff816293c2-ffffffff81629880: set_machine_constraints.cold.71 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev, const struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1277
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff8165b890-ffffffff8165bd81: set_machine_constraints (STB_LOCAL)
ffffffff8165d26a-ffffffff8165d368: set_machine_constraints.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev, const struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1283
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff8167d6d0-ffffffff8167dbca: set_machine_constraints (STB_LOCAL)
ffffffff8167f82d-ffffffff8167f92b: set_machine_constraints.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev, const struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1290
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff8172ef80-ffffffff8172f2fd: set_machine_constraints (STB_LOCAL)
ffffffff81730992-ffffffff81730b36: set_machine_constraints.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1325
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff8174bbf0-ffffffff8174bf2e: set_machine_constraints (STB_LOCAL)
ffffffff81c06ef5-ffffffff81c070e3: set_machine_constraints.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1328
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff8172f310-ffffffff8172f6b4: set_machine_constraints (STB_LOCAL)
ffffffff81bf8b90-ffffffff81bf8d7e: set_machine_constraints.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1354
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff817aefd0-ffffffff817af4a6: set_machine_constraints (STB_LOCAL)
ffffffff81cf7dbe-ffffffff81cf8100: set_machine_constraints.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1380
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff818e9a40-ffffffff818e9fd8: set_machine_constraints (STB_LOCAL)
ffffffff81ebfd67-ffffffff81ec00a8: set_machine_constraints.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a407e0)
Location: drivers/regulator/core.c:1398
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff81a407e0-ffffffff81a4138f: set_machine_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a8a890)
Location: drivers/regulator/core.c:1464
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff81a8a890-ffffffff81a8b457: set_machine_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81adcfe0)
Location: drivers/regulator/core.c:1466
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff81adcfe0-ffffffff81addba5: set_machine_constraints (STB_LOCAL)
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
int set_machine_constraints(struct regulator_dev *rdev, const struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff8000108473f8)
Location: drivers/regulator/core.c:1283
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffff8000108473f8-ffff800010847940: set_machine_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev, const struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0950bbc)
Location: drivers/regulator/core.c:1283
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
c0950bbc-c095118c: set_machine_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev, const struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e3770)
Location: drivers/regulator/core.c:1283
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
c0000000008e3770-c0000000008e3e74: set_machine_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev, const struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000527774)
Location: drivers/regulator/core.c:1283
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffe000527774-ffffffe000527d16: set_machine_constraints (STB_LOCAL)
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
int set_machine_constraints(struct regulator_dev *rdev, const struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1283
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff81642fb0-ffffffff81643629: set_machine_constraints (STB_LOCAL)
ffffffff81645246-ffffffff816453ab: set_machine_constraints.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev, const struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1283
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff816235b0-ffffffff81623aaa: set_machine_constraints (STB_LOCAL)
ffffffff8162570d-ffffffff8162580b: set_machine_constraints.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev, const struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1283
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff81671510-ffffffff81671a0a: set_machine_constraints (STB_LOCAL)
ffffffff8167366d-ffffffff8167376b: set_machine_constraints.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int set_machine_constraints(struct regulator_dev *rdev, const struct regulation_constraints *constraints);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:1283
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff8168bb70-ffffffff8168c06a: set_machine_constraints (STB_LOCAL)
ffffffff8168dccd-ffffffff8168ddcb: set_machine_constraints.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct regulation_constraints *constraints</code>
</li>
</ul>
</details>
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
