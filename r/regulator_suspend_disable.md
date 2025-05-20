# Function: <code>regulator_suspend_disable</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int regulator_suspend_disable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81609d70)
Location: drivers/regulator/core.c:3162
Inline: True
```
**Symbols:**

```
ffffffff81609d70-ffffffff81609e12: regulator_suspend_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int regulator_suspend_disable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816231c0)
Location: drivers/regulator/core.c:3769
Inline: True
```
**Symbols:**

```
ffffffff816231c0-ffffffff81623262: regulator_suspend_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int regulator_suspend_disable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816552e0)
Location: drivers/regulator/core.c:3789
Inline: True
```
**Symbols:**

```
ffffffff816552e0-ffffffff81655387: regulator_suspend_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int regulator_suspend_disable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81677810)
Location: drivers/regulator/core.c:3798
Inline: True
```
**Symbols:**

```
ffffffff81677810-ffffffff816778b7: regulator_suspend_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int regulator_suspend_disable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81728830)
Location: drivers/regulator/core.c:3838
Inline: True
```
**Symbols:**

```
ffffffff81728830-ffffffff817288db: regulator_suspend_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int regulator_suspend_disable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817453e0)
Location: drivers/regulator/core.c:3968
Inline: True
```
**Symbols:**

```
ffffffff817453e0-ffffffff8174548b: regulator_suspend_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int regulator_suspend_disable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81728d80)
Location: drivers/regulator/core.c:3966
Inline: True
```
**Symbols:**

```
ffffffff81728d80-ffffffff81728e25: regulator_suspend_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_suspend_disable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff817a80bf)
Location: drivers/regulator/core.c:4066
Inline: True
```
**Symbols:**

```
ffffffff81cf7537-ffffffff81cf754c: regulator_suspend_disable.cold (STB_LOCAL)
ffffffff817a8050-ffffffff817a814c: regulator_suspend_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_suspend_disable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff818e29bb)
Location: drivers/regulator/core.c:4108
Inline: True
```
**Symbols:**

```
ffffffff81ebf713-ffffffff81ebf728: regulator_suspend_disable.cold (STB_LOCAL)
ffffffff818e2940-ffffffff818e2a39: regulator_suspend_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_suspend_disable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a37a4b)
Location: drivers/regulator/core.c:4138
Inline: True
```
**Symbols:**

```
ffffffff82094ad5-ffffffff82094aea: regulator_suspend_disable.cold (STB_LOCAL)
ffffffff81a379d0-ffffffff81a37ac9: regulator_suspend_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_suspend_disable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a81622)
Location: drivers/regulator/core.c:4204
Inline: True
```
**Symbols:**

```
ffffffff821158f9-ffffffff8211590e: regulator_suspend_disable.cold (STB_LOCAL)
ffffffff81a815a0-ffffffff81a81699: regulator_suspend_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_suspend_disable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad3bd2)
Location: drivers/regulator/core.c:4210
Inline: True
```
**Symbols:**

```
ffffffff821f35b0-ffffffff821f35c5: regulator_suspend_disable.cold (STB_LOCAL)
ffffffff81ad3b50-ffffffff81ad3c49: regulator_suspend_disable (STB_GLOBAL)
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
int regulator_suspend_disable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010840980)
Location: drivers/regulator/core.c:3798
Inline: True
```
**Symbols:**

```
ffff800010840980-ffff800010840a58: regulator_suspend_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int regulator_suspend_disable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0949f24)
Location: drivers/regulator/core.c:3798
Inline: True
```
**Symbols:**

```
c0949f24-c0949ff4: regulator_suspend_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int regulator_suspend_disable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008da830)
Location: drivers/regulator/core.c:3798
Inline: True
```
**Symbols:**

```
c0000000008da830-c0000000008da918: regulator_suspend_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int regulator_suspend_disable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe00052270a)
Location: drivers/regulator/core.c:3798
Inline: True
```
**Symbols:**

```
ffffffe00052270a-ffffffe0005227a8: regulator_suspend_disable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int regulator_suspend_disable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8163d500)
Location: drivers/regulator/core.c:3798
Inline: True
```
**Symbols:**

```
ffffffff8163d500-ffffffff8163d5a7: regulator_suspend_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int regulator_suspend_disable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8161d6f0)
Location: drivers/regulator/core.c:3798
Inline: True
```
**Symbols:**

```
ffffffff8161d6f0-ffffffff8161d797: regulator_suspend_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int regulator_suspend_disable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8166b650)
Location: drivers/regulator/core.c:3798
Inline: True
```
**Symbols:**

```
ffffffff8166b650-ffffffff8166b6f7: regulator_suspend_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int regulator_suspend_disable(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81685c10)
Location: drivers/regulator/core.c:3798
Inline: True
```
**Symbols:**

```
ffffffff81685c10-ffffffff81685cb7: regulator_suspend_disable (STB_GLOBAL)
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
