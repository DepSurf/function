# Function: <code>regulator_bulk_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814dc900)
Location: drivers/regulator/core.c:3444
Inline: False
```
**Symbols:**

```
ffffffff814dc900-ffffffff814dc9df: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152e500)
Location: drivers/regulator/core.c:3476
Inline: False
```
**Symbols:**

```
ffffffff8152e500-ffffffff8152e5d9: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8155a1d0)
Location: drivers/regulator/core.c:3542
Inline: False
```
**Symbols:**

```
ffffffff8155a1d0-ffffffff8155a2a7: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815700d0)
Location: drivers/regulator/core.c:3565
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff815700d0-ffffffff815701c4: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d4360)
Location: drivers/regulator/core.c:3573
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff815d4360-ffffffff815d4454: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8160c280)
Location: drivers/regulator/core.c:3747
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff8160c280-ffffffff8160c374: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81628920)
Location: drivers/regulator/core.c:4372
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff81628920-ffffffff81628a14: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4392
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff8165d0ea-ffffffff8165d104: regulator_bulk_get.cold (STB_LOCAL)
ffffffff8165ac70-ffffffff8165ad78: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4402
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff8167facc-ffffffff8167fae6: regulator_bulk_get.cold (STB_LOCAL)
ffffffff8167f140-ffffffff8167f248: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4451
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff81730926-ffffffff81730940: regulator_bulk_get.cold (STB_LOCAL)
ffffffff8172ec60-ffffffff8172ed98: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4589
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff81c06e89-ffffffff81c06ea4: regulator_bulk_get.cold (STB_LOCAL)
ffffffff8174b900-ffffffff8174ba09: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4591
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff81bf8b24-ffffffff81bf8b3f: regulator_bulk_get.cold (STB_LOCAL)
ffffffff8172f010-ffffffff8172f12a: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4728
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff81cf7d52-ffffffff81cf7d6d: regulator_bulk_get.cold (STB_LOCAL)
ffffffff817aecd0-ffffffff817aede7: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4773
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff81ec01c9-ffffffff81ec01e3: regulator_bulk_get.cold (STB_LOCAL)
ffffffff818ea680-ffffffff818ea7ba: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a42df0)
Location: drivers/regulator/core.c:4842
Inline: False
```
**Symbols:**

```
ffffffff81a42df0-ffffffff81a42e0e: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a8cf00)
Location: drivers/regulator/core.c:4908
Inline: False
```
**Symbols:**

```
ffffffff81a8cf00-ffffffff81a8cf1e: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81adf700)
Location: drivers/regulator/core.c:4930
Inline: False
```
**Symbols:**

```
ffffffff81adf700-ffffffff81adf71e: regulator_bulk_get (STB_GLOBAL)
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
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff8000108490f8)
Location: drivers/regulator/core.c:4402
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
ffff8000108490f8-ffff800010849244: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c09528c4)
Location: drivers/regulator/core.c:4402
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe
```
**Symbols:**

```
c09528c4-c09529e0: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e6250)
Location: drivers/regulator/core.c:4402
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
c0000000008e6250-c0000000008e6420: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000529188)
Location: drivers/regulator/core.c:4402
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
ffffffe000529188-ffffffe00052929a: regulator_bulk_get (STB_GLOBAL)
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
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4402
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff8164554c-ffffffff81645566: regulator_bulk_get.cold (STB_LOCAL)
ffffffff81644ba0-ffffffff81644ca8: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4402
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff816259ac-ffffffff816259c6: regulator_bulk_get.cold (STB_LOCAL)
ffffffff81625020-ffffffff81625128: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4402
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff8167390c-ffffffff81673926: regulator_bulk_get.cold (STB_LOCAL)
ffffffff81672f80-ffffffff81673088: regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4402
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff8168df6c-ffffffff8168df86: regulator_bulk_get.cold (STB_LOCAL)
ffffffff8168d5e0-ffffffff8168d6e8: regulator_bulk_get (STB_GLOBAL)
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
