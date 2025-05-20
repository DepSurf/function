# Function: <code>regulator_is_supported_voltage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814db6b0)
Location: drivers/regulator/core.c:2628
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff814db6b0-ffffffff814db781: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152cbb0)
Location: drivers/regulator/core.c:2644
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff8152cbb0-ffffffff8152cc98: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81559210)
Location: drivers/regulator/core.c:2645
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff81559210-ffffffff815592f8: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156cc80)
Location: drivers/regulator/core.c:2657
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff8156cc80-ffffffff8156cd66: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d0ef0)
Location: drivers/regulator/core.c:2665
Inline: True
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff815d0ef0-ffffffff815d0fd6: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2722
Inline: True
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff8160c8c6-ffffffff8160c8db: regulator_is_supported_voltage.cold.55 (STB_LOCAL)
ffffffff81609450-ffffffff81609529: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff816260bf)
Location: drivers/regulator/core.c:3045
Inline: True
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff81629104-ffffffff81629119: regulator_is_supported_voltage.cold.62 (STB_LOCAL)
ffffffff81626030-ffffffff81626109: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81659ce0)
Location: drivers/regulator/core.c:3000
Inline: True
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff81659ce0-ffffffff81659db5: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8167c6d0)
Location: drivers/regulator/core.c:3008
Inline: True
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff8167c6d0-ffffffff8167c7a5: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3039
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff8173048f-ffffffff817304af: regulator_is_supported_voltage.cold (STB_LOCAL)
ffffffff8172c800-ffffffff8172c99a: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3169
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff81c069b9-ffffffff81c069d9: regulator_is_supported_voltage.cold (STB_LOCAL)
ffffffff81749890-ffffffff81749a2a: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3167
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff81bf8651-ffffffff81bf8671: regulator_is_supported_voltage.cold (STB_LOCAL)
ffffffff8172d140-ffffffff8172d2da: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3267
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff81cf77d4-ffffffff81cf77f4: regulator_is_supported_voltage.cold (STB_LOCAL)
ffffffff817abe00-ffffffff817abf9a: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3314
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff81ebf9a5-ffffffff81ebf9c5: regulator_is_supported_voltage.cold (STB_LOCAL)
ffffffff818e6b90-ffffffff818e6d4a: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3d8b0)
Location: drivers/regulator/core.c:3346
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff81a3d8b0-ffffffff81a3da93: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a87a20)
Location: drivers/regulator/core.c:3412
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff81a87a20-ffffffff81a87c0c: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ada110)
Location: drivers/regulator/core.c:3418
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff81ada110-ffffffff81ada2fc: regulator_is_supported_voltage (STB_GLOBAL)
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
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010846238)
Location: drivers/regulator/core.c:3008
Inline: True
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffff800010846238-ffff800010846350: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094f924)
Location: drivers/regulator/core.c:3008
Inline: True
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
```
**Symbols:**

```
c094f924-c094fa28: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e1ec0)
Location: drivers/regulator/core.c:3008
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
c0000000008e1ec0-c0000000008e20a0: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe00052688c)
Location: drivers/regulator/core.c:3008
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffe00052688c-ffffffe00052694e: regulator_is_supported_voltage (STB_GLOBAL)
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
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81641fb0)
Location: drivers/regulator/core.c:3008
Inline: True
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff81641fb0-ffffffff81642085: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816225b0)
Location: drivers/regulator/core.c:3008
Inline: True
Direct callers:
  - drivers/opp/core.c:_opp_add
```
**Symbols:**

```
ffffffff816225b0-ffffffff81622685: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81670510)
Location: drivers/regulator/core.c:3008
Inline: True
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff81670510-ffffffff816705e5: regulator_is_supported_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int regulator_is_supported_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8168ab70)
Location: drivers/regulator/core.c:3008
Inline: True
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff8168ab70-ffffffff8168ac45: regulator_is_supported_voltage (STB_GLOBAL)
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
