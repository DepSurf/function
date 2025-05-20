# Function: <code>regulator_count_voltages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814d72d0)
Location: drivers/regulator/core.c:2503
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_count_voltages
```
**Symbols:**

```
ffffffff814d72d0-ffffffff814d7301: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81528030)
Location: drivers/regulator/core.c:2519
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_count_voltages
```
**Symbols:**

```
ffffffff81528030-ffffffff81528061: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815545a0)
Location: drivers/regulator/core.c:2520
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_count_voltages
```
**Symbols:**

```
ffffffff815545a0-ffffffff815545d1: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81569110)
Location: drivers/regulator/core.c:2532
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_count_voltages
```
**Symbols:**

```
ffffffff81569110-ffffffff81569150: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815cd2c0)
Location: drivers/regulator/core.c:2540
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_count_voltages
```
**Symbols:**

```
ffffffff815cd2c0-ffffffff815cd300: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816059f0)
Location: drivers/regulator/core.c:2597
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_count_voltages
```
**Symbols:**

```
ffffffff816059f0-ffffffff81605a2a: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81620ad0)
Location: drivers/regulator/core.c:2920
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_count_voltages
```
**Symbols:**

```
ffffffff81620ad0-ffffffff81620b0a: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816540c0)
Location: drivers/regulator/core.c:2875
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_count_voltages
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff816540c0-ffffffff816540fa: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81676660)
Location: drivers/regulator/core.c:2883
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_count_voltages
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff81676660-ffffffff8167669a: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172c8ce)
Location: drivers/regulator/core.c:2914
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
Direct callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff817291f0-ffffffff817292f9: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8174995e)
Location: drivers/regulator/core.c:3042
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
Direct callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff81745da0-ffffffff81745ea9: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172d20e)
Location: drivers/regulator/core.c:3040
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
Direct callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff817297b0-ffffffff817298b9: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817abece)
Location: drivers/regulator/core.c:3140
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
Direct callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff817a8b50-ffffffff817a8c59: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff818e6c81)
Location: drivers/regulator/core.c:3187
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
Direct callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff818e3190-ffffffff818e32b5: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3d9a1)
Location: drivers/regulator/core.c:3219
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
Direct callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff81a38320-ffffffff81a38445: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a87b11)
Location: drivers/regulator/core.c:3285
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
Direct callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff81a81ef0-ffffffff81a82015: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ada201)
Location: drivers/regulator/core.c:3291
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
Direct callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff81ad44d0-ffffffff81ad45f5: regulator_count_voltages (STB_GLOBAL)
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
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff80001083f300)
Location: drivers/regulator/core.c:2883
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_count_voltages
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffff80001083f300-ffff80001083f350: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0948b68)
Location: drivers/regulator/core.c:2883
Inline: False
Direct callers:
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/regulator/core.c:regulator_count_voltages
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
c0948b68-c0948bb8: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008d84b0)
Location: drivers/regulator/core.c:2883
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
Direct callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
c0000000008d84b0-c0000000008d8508: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000521050)
Location: drivers/regulator/core.c:2883
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_count_voltages
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffe000521050-ffffffe00052109e: regulator_count_voltages (STB_GLOBAL)
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
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8163c350)
Location: drivers/regulator/core.c:2883
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_count_voltages
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff8163c350-ffffffff8163c38a: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8161c540)
Location: drivers/regulator/core.c:2883
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_count_voltages
```
**Symbols:**

```
ffffffff8161c540-ffffffff8161c57a: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8166a4a0)
Location: drivers/regulator/core.c:2883
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_count_voltages
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff8166a4a0-ffffffff8166a4da: regulator_count_voltages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int regulator_count_voltages(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81684a60)
Location: drivers/regulator/core.c:2883
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_count_voltages
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff81684a60-ffffffff81684a9a: regulator_count_voltages (STB_GLOBAL)
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
