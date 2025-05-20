# Function: <code>regulator_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814dbd20)
Location: drivers/regulator/core.c:4005
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffff814dbd20-ffffffff814dbe06: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152cf10)
Location: drivers/regulator/core.c:4059
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffff8152cf10-ffffffff8152cff6: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81559570)
Location: drivers/regulator/core.c:4123
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffff81559570-ffffffff81559656: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156dc50)
Location: drivers/regulator/core.c:4147
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffff8156dc50-ffffffff8156dd24: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d1ee0)
Location: drivers/regulator/core.c:4155
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffff815d1ee0-ffffffff815d1fb4: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8160a020)
Location: drivers/regulator/core.c:4421
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffff8160a020-ffffffff8160a0f3: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81626ec0)
Location: drivers/regulator/core.c:5094
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffff81626ec0-ffffffff81627083: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:5204
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffff8165cf0f-ffffffff8165cf22: regulator_unregister.cold (STB_LOCAL)
ffffffff8165a4f0-ffffffff8165a5c9: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8167d230)
Location: drivers/regulator/core.c:5232
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffff8167d230-ffffffff8167d309: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172e380)
Location: drivers/regulator/core.c:5270
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffff8172e380-ffffffff8172e4e5: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8174af90)
Location: drivers/regulator/core.c:5420
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffff8174af90-ffffffff8174b0ba: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172e660)
Location: drivers/regulator/core.c:5424
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffff8172e660-ffffffff8172e7c5: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817ae240)
Location: drivers/regulator/core.c:5562
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffff817ae240-ffffffff817ae3a5: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff818e9220)
Location: drivers/regulator/core.c:5627
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffff818e9220-ffffffff818e9386: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3f560)
Location: drivers/regulator/core.c:5685
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffff81a3f560-ffffffff81a3f6ba: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a89130)
Location: drivers/regulator/core.c:5749
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffff81a89130-ffffffff81a8928a: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81adb810)
Location: drivers/regulator/core.c:5804
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffff81adb810-ffffffff81adb96a: regulator_unregister (STB_GLOBAL)
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
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010846e58)
Location: drivers/regulator/core.c:5232
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffff800010846e58-ffff800010846f34: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c09505cc)
Location: drivers/regulator/core.c:5232
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
c09505cc-c09506b4: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e2ff0)
Location: drivers/regulator/core.c:5232
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
c0000000008e2ff0-c0000000008e3128: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe0005272b4)
Location: drivers/regulator/core.c:5232
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffe0005272b4-ffffffe000527382: regulator_unregister (STB_GLOBAL)
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
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81642b10)
Location: drivers/regulator/core.c:5232
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffff81642b10-ffffffff81642be9: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81623110)
Location: drivers/regulator/core.c:5232
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffff81623110-ffffffff816231e9: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81671070)
Location: drivers/regulator/core.c:5232
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffff81671070-ffffffff81671149: regulator_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void regulator_unregister(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8168b6d0)
Location: drivers/regulator/core.c:5232
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_rdev_release
```
**Symbols:**

```
ffffffff8168b6d0-ffffffff8168b7a9: regulator_unregister (STB_GLOBAL)
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
