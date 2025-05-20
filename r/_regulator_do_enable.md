# Function: <code>_regulator_do_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814d99a0)
Location: drivers/regulator/core.c:2022
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:_regulator_suspend_finish
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff814d99a0-ffffffff814d9cae: _regulator_do_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81529f30)
Location: drivers/regulator/core.c:2074
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_suspend_finish
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81529f30-ffffffff8152a235: _regulator_do_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81556530)
Location: drivers/regulator/core.c:2075
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_suspend_finish
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81556530-ffffffff81556835: _regulator_do_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156aa40)
Location: drivers/regulator/core.c:2085
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_suspend_finish
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8156aa40-ffffffff8156ad40: _regulator_do_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815cec30)
Location: drivers/regulator/core.c:2085
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_suspend_finish
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff815cec30-ffffffff815cef3f: _regulator_do_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2142
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81606d50-ffffffff81607007: _regulator_do_enable (STB_LOCAL)
ffffffff8160c57f-ffffffff8160c5be: _regulator_do_enable.cold.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2382
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81622120-ffffffff816223d7: _regulator_do_enable (STB_LOCAL)
ffffffff81628c83-ffffffff81628cc2: _regulator_do_enable.cold.52 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2337
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81655af0-ffffffff81655db2: _regulator_do_enable (STB_LOCAL)
ffffffff8165cca7-ffffffff8165ccc6: _regulator_do_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2345
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81678020-ffffffff816782e2: _regulator_do_enable (STB_LOCAL)
ffffffff8167f3d7-ffffffff8167f3f6: _regulator_do_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2376
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8172ad50-ffffffff8172b003: _regulator_do_enable (STB_LOCAL)
ffffffff8173018b-ffffffff817301ad: _regulator_do_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2471
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff817478c0-ffffffff81747c01: _regulator_do_enable (STB_LOCAL)
ffffffff81c06689-ffffffff81c066d2: _regulator_do_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2482
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8172b140-ffffffff8172b498: _regulator_do_enable (STB_LOCAL)
ffffffff81bf831d-ffffffff81bf835e: _regulator_do_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2582
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff817ab030-ffffffff817ab38b: _regulator_do_enable (STB_LOCAL)
ffffffff81cf76da-ffffffff81cf771b: _regulator_do_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2629
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff818e5c90-ffffffff818e6030: _regulator_do_enable (STB_LOCAL)
ffffffff81ebf8ad-ffffffff81ebf8ee: _regulator_do_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3e560)
Location: drivers/regulator/core.c:2656
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81a3e560-ffffffff81a3e9db: _regulator_do_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a88090)
Location: drivers/regulator/core.c:2722
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81a88090-ffffffff81a884f7: _regulator_do_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ada780)
Location: drivers/regulator/core.c:2724
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81ada780-ffffffff81adabe7: _regulator_do_enable (STB_LOCAL)
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
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010844c20)
Location: drivers/regulator/core.c:2345
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffff800010844c20-ffff800010844f3c: _regulator_do_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094a408)
Location: drivers/regulator/core.c:2345
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
c094a408-c094a770: _regulator_do_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008db160)
Location: drivers/regulator/core.c:2345
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
c0000000008db160-c0000000008db55c: _regulator_do_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000522e4a)
Location: drivers/regulator/core.c:2345
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffe000522e4a-ffffffe0005230e8: _regulator_do_enable (STB_LOCAL)
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
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2345
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8163dd10-ffffffff8163dfd2: _regulator_do_enable (STB_LOCAL)
ffffffff81644e37-ffffffff81644e56: _regulator_do_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2345
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8161df00-ffffffff8161e1c2: _regulator_do_enable (STB_LOCAL)
ffffffff816252b7-ffffffff816252d6: _regulator_do_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2345
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8166be60-ffffffff8166c122: _regulator_do_enable (STB_LOCAL)
ffffffff81673217-ffffffff81673236: _regulator_do_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int _regulator_do_enable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2345
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81686420-ffffffff81686729: _regulator_do_enable (STB_LOCAL)
ffffffff8168d877-ffffffff8168d896: _regulator_do_enable.cold (STB_LOCAL)
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
