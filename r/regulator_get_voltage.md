# Function: <code>regulator_get_voltage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814d8230)
Location: drivers/regulator/core.c:3132
Inline: False
Direct callers:
  - drivers/regulator/core.c:drms_uA_update
```
**Symbols:**

```
ffffffff814d8230-ffffffff814d8297: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81529180)
Location: drivers/regulator/core.c:3165
Inline: False
```
**Symbols:**

```
ffffffff81529180-ffffffff815291f2: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81555630)
Location: drivers/regulator/core.c:3198
Inline: False
```
**Symbols:**

```
ffffffff81555630-ffffffff815556a2: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81569c50)
Location: drivers/regulator/core.c:3221
Inline: False
```
**Symbols:**

```
ffffffff81569c50-ffffffff81569cc4: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815cde30)
Location: drivers/regulator/core.c:3229
Inline: False
```
**Symbols:**

```
ffffffff815cde30-ffffffff815cdea4: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81608e50)
Location: drivers/regulator/core.c:3403
Inline: False
```
**Symbols:**

```
ffffffff81608e50-ffffffff81608ea5: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81624100)
Location: drivers/regulator/core.c:4011
Inline: False
```
**Symbols:**

```
ffffffff81624100-ffffffff81624167: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81659c70)
Location: drivers/regulator/core.c:4031
Inline: False
Direct callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff81659c70-ffffffff81659cdb: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8167a3c0)
Location: drivers/regulator/core.c:4041
Inline: False
Direct callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff8167a3c0-ffffffff8167a42b: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172c848)
Location: drivers/regulator/core.c:4081
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:drms_uA_update
Direct callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff8172b330-ffffffff8172b397: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817498d8)
Location: drivers/regulator/core.c:4219
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:drms_uA_update
Direct callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff81747f40-ffffffff81747fa7: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172d188)
Location: drivers/regulator/core.c:4221
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:drms_uA_update
Direct callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff8172b690-ffffffff8172b6f7: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817abe48)
Location: drivers/regulator/core.c:4344
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:drms_uA_update
Direct callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff817abd90-ffffffff817abdf7: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff818e6bdc)
Location: drivers/regulator/core.c:4389
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:drms_uA_update
Direct callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff818e6b00-ffffffff818e6b87: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3d8fc)
Location: drivers/regulator/core.c:4419
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
Direct callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff81a3c5a0-ffffffff81a3c627: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a87a6c)
Location: drivers/regulator/core.c:4485
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
Direct callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff81a86730-ffffffff81a867b7: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ada15c)
Location: drivers/regulator/core.c:4491
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
Direct callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff81ad8e40-ffffffff81ad8ec7: regulator_get_voltage (STB_GLOBAL)
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
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff8000108426e0)
Location: drivers/regulator/core.c:4041
Inline: False
Direct callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_request
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffff8000108426e0-ffff800010842754: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094d258)
Location: drivers/regulator/core.c:4041
Inline: False
Direct callers:
  - drivers/cpufreq/omap-cpufreq.c:omap_target
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - sound/soc/codecs/sgtl5000.c:sgtl5000_probe
  - sound/soc/codecs/sgtl5000.c:sgtl5000_probe
  - sound/soc/codecs/sgtl5000.c:sgtl5000_probe
```
**Symbols:**

```
c094d258-c094d2d8: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008de6e0)
Location: drivers/regulator/core.c:4041
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
c0000000008de6e0-c0000000008de76c: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe0005249d0)
Location: drivers/regulator/core.c:4041
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffe0005249d0-ffffffe000524a1a: regulator_get_voltage (STB_GLOBAL)
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
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8163fec0)
Location: drivers/regulator/core.c:4041
Inline: False
Direct callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff8163fec0-ffffffff8163ff2b: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816202a0)
Location: drivers/regulator/core.c:4041
Inline: False
```
**Symbols:**

```
ffffffff816202a0-ffffffff8162030b: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8166e200)
Location: drivers/regulator/core.c:4041
Inline: False
Direct callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff8166e200-ffffffff8166e26b: regulator_get_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int regulator_get_voltage(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81688860)
Location: drivers/regulator/core.c:4041
Inline: False
Direct callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff81688860-ffffffff816888cb: regulator_get_voltage (STB_GLOBAL)
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
