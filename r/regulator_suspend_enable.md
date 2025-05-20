# Function: <code>regulator_suspend_enable</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regulator_suspend_enable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81605ad0)
Location: drivers/regulator/core.c:3155
Inline: False
```
**Symbols:**

```
ffffffff81605ad0-ffffffff81605b21: regulator_suspend_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regulator_suspend_enable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81620bb0)
Location: drivers/regulator/core.c:3762
Inline: False
```
**Symbols:**

```
ffffffff81620bb0-ffffffff81620c01: regulator_suspend_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int regulator_suspend_enable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816541a0)
Location: drivers/regulator/core.c:3782
Inline: False
```
**Symbols:**

```
ffffffff816541a0-ffffffff81654207: regulator_suspend_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int regulator_suspend_enable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81676740)
Location: drivers/regulator/core.c:3791
Inline: False
```
**Symbols:**

```
ffffffff81676740-ffffffff816767a7: regulator_suspend_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int regulator_suspend_enable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81728620)
Location: drivers/regulator/core.c:3831
Inline: False
```
**Symbols:**

```
ffffffff81728620-ffffffff81728687: regulator_suspend_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int regulator_suspend_enable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817451d0)
Location: drivers/regulator/core.c:3961
Inline: False
```
**Symbols:**

```
ffffffff817451d0-ffffffff81745237: regulator_suspend_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int regulator_suspend_enable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81728b70)
Location: drivers/regulator/core.c:3959
Inline: False
```
**Symbols:**

```
ffffffff81728b70-ffffffff81728bd7: regulator_suspend_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regulator_suspend_enable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4059
Inline: False
```
**Symbols:**

```
ffffffff81cf7506-ffffffff81cf751b: regulator_suspend_enable.cold (STB_LOCAL)
ffffffff817a7dc0-ffffffff817a7e35: regulator_suspend_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regulator_suspend_enable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4101
Inline: False
```
**Symbols:**

```
ffffffff81ebf6d6-ffffffff81ebf6eb: regulator_suspend_enable.cold (STB_LOCAL)
ffffffff818e2680-ffffffff818e2705: regulator_suspend_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int regulator_suspend_enable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4131
Inline: False
```
**Symbols:**

```
ffffffff82094ac0-ffffffff82094ad5: regulator_suspend_enable.cold (STB_LOCAL)
ffffffff81a37740-ffffffff81a377c5: regulator_suspend_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int regulator_suspend_enable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4197
Inline: False
```
**Symbols:**

```
ffffffff821158e4-ffffffff821158f9: regulator_suspend_enable.cold (STB_LOCAL)
ffffffff81a81320-ffffffff81a8139a: regulator_suspend_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int regulator_suspend_enable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4203
Inline: False
```
**Symbols:**

```
ffffffff821f359b-ffffffff821f35b0: regulator_suspend_enable.cold (STB_LOCAL)
ffffffff81ad38d0-ffffffff81ad394a: regulator_suspend_enable (STB_GLOBAL)
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
int regulator_suspend_enable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff80001083f458)
Location: drivers/regulator/core.c:3791
Inline: False
```
**Symbols:**

```
ffff80001083f458-ffff80001083f4e8: regulator_suspend_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_suspend_enable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0948c7c)
Location: drivers/regulator/core.c:3791
Inline: False
```
**Symbols:**

```
c0948c7c-c0948cf8: regulator_suspend_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regulator_suspend_enable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008d8600)
Location: drivers/regulator/core.c:3791
Inline: False
```
**Symbols:**

```
c0000000008d8600-c0000000008d8690: regulator_suspend_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_suspend_enable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe00052116e)
Location: drivers/regulator/core.c:3791
Inline: False
```
**Symbols:**

```
ffffffe00052116e-ffffffe0005211de: regulator_suspend_enable (STB_GLOBAL)
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
int regulator_suspend_enable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8163c430)
Location: drivers/regulator/core.c:3791
Inline: False
```
**Symbols:**

```
ffffffff8163c430-ffffffff8163c497: regulator_suspend_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int regulator_suspend_enable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8161c620)
Location: drivers/regulator/core.c:3791
Inline: False
```
**Symbols:**

```
ffffffff8161c620-ffffffff8161c687: regulator_suspend_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int regulator_suspend_enable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8166a580)
Location: drivers/regulator/core.c:3791
Inline: False
```
**Symbols:**

```
ffffffff8166a580-ffffffff8166a5e7: regulator_suspend_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int regulator_suspend_enable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81684b40)
Location: drivers/regulator/core.c:3791
Inline: False
```
**Symbols:**

```
ffffffff81684b40-ffffffff81684ba7: regulator_suspend_enable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
