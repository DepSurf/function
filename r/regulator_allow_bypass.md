# Function: <code>regulator_allow_bypass</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814d8330)
Location: drivers/regulator/core.c:3348
Inline: False
```
**Symbols:**

```
ffffffff814d8330-ffffffff814d8437: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152b1d0)
Location: drivers/regulator/core.c:3381
Inline: False
```
**Symbols:**

```
ffffffff8152b1d0-ffffffff8152b2f4: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815577d0)
Location: drivers/regulator/core.c:3447
Inline: False
```
**Symbols:**

```
ffffffff815577d0-ffffffff815578f4: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156be80)
Location: drivers/regulator/core.c:3470
Inline: False
```
**Symbols:**

```
ffffffff8156be80-ffffffff8156bfa5: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d00c0)
Location: drivers/regulator/core.c:3478
Inline: False
```
**Symbols:**

```
ffffffff815d00c0-ffffffff815d01f5: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3652
Inline: False
```
**Symbols:**

```
ffffffff8160c7c6-ffffffff8160c7db: regulator_allow_bypass.cold.52 (STB_LOCAL)
ffffffff81608ba0-ffffffff81608ce3: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4277
Inline: False
```
**Symbols:**

```
ffffffff816290ef-ffffffff81629104: regulator_allow_bypass.cold.61 (STB_LOCAL)
ffffffff81625d00-ffffffff81625e9d: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81658330)
Location: drivers/regulator/core.c:4297
Inline: False
```
**Symbols:**

```
ffffffff81658330-ffffffff816584e8: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8167c250)
Location: drivers/regulator/core.c:4307
Inline: False
```
**Symbols:**

```
ffffffff8167c250-ffffffff8167c408: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4347
Inline: False
```
**Symbols:**

```
ffffffff8173062c-ffffffff81730648: regulator_allow_bypass.cold (STB_LOCAL)
ffffffff8172d1b0-ffffffff8172d4cb: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4485
Inline: False
```
**Symbols:**

```
ffffffff81c06b5e-ffffffff81c06b7a: regulator_allow_bypass.cold (STB_LOCAL)
ffffffff8174a2a0-ffffffff8174a586: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4487
Inline: False
```
**Symbols:**

```
ffffffff81bf87f9-ffffffff81bf8815: regulator_allow_bypass.cold (STB_LOCAL)
ffffffff8172db10-ffffffff8172ddef: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4624
Inline: False
```
**Symbols:**

```
ffffffff81cf77b8-ffffffff81cf77d4: regulator_allow_bypass.cold (STB_LOCAL)
ffffffff817ab6f0-ffffffff817aba28: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4669
Inline: False
```
**Symbols:**

```
ffffffff81ebf989-ffffffff81ebf9a5: regulator_allow_bypass.cold (STB_LOCAL)
ffffffff818e63c0-ffffffff818e6744: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3b130)
Location: drivers/regulator/core.c:4699
Inline: False
```
**Symbols:**

```
ffffffff81a3b130-ffffffff81a3b4e0: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a84fb0)
Location: drivers/regulator/core.c:4765
Inline: False
```
**Symbols:**

```
ffffffff81a84fb0-ffffffff81a85360: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad7790)
Location: drivers/regulator/core.c:4771
Inline: False
```
**Symbols:**

```
ffffffff81ad7790-ffffffff81ad7b40: regulator_allow_bypass (STB_GLOBAL)
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
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010845d60)
Location: drivers/regulator/core.c:4307
Inline: False
```
**Symbols:**

```
ffff800010845d60-ffff800010845f28: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094f4b0)
Location: drivers/regulator/core.c:4307
Inline: False
Direct callers:
  - sound/soc/soc-dapm.c:snd_soc_dapm_new_control_unlocked
```
**Symbols:**

```
c094f4b0-c094f67c: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e17d0)
Location: drivers/regulator/core.c:4307
Inline: False
```
**Symbols:**

```
c0000000008e17d0-c0000000008e1a40: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe0005264bc)
Location: drivers/regulator/core.c:4307
Inline: False
```
**Symbols:**

```
ffffffe0005264bc-ffffffe000526634: regulator_allow_bypass (STB_GLOBAL)
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
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81641b30)
Location: drivers/regulator/core.c:4307
Inline: False
```
**Symbols:**

```
ffffffff81641b30-ffffffff81641ce8: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81622130)
Location: drivers/regulator/core.c:4307
Inline: False
```
**Symbols:**

```
ffffffff81622130-ffffffff816222e8: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81670090)
Location: drivers/regulator/core.c:4307
Inline: False
```
**Symbols:**

```
ffffffff81670090-ffffffff81670248: regulator_allow_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int regulator_allow_bypass(struct regulator *regulator, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8168a6f0)
Location: drivers/regulator/core.c:4307
Inline: False
```
**Symbols:**

```
ffffffff8168a6f0-ffffffff8168a8a8: regulator_allow_bypass (STB_GLOBAL)
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
