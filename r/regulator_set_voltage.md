# Function: <code>regulator_set_voltage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814db630)
Location: drivers/regulator/core.c:2951
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
```
**Symbols:**

```
ffffffff814db630-ffffffff814db6a5: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152bf10)
Location: drivers/regulator/core.c:2967
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8152bf10-ffffffff8152bf8d: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81558550)
Location: drivers/regulator/core.c:3003
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81558550-ffffffff815585cd: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156cc00)
Location: drivers/regulator/core.c:3026
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8156cc00-ffffffff8156cc7f: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d0e70)
Location: drivers/regulator/core.c:3034
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff815d0e70-ffffffff815d0eef: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81609070)
Location: drivers/regulator/core.c:3123
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81609070-ffffffff816090d6: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81626980)
Location: drivers/regulator/core.c:3729
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
  - drivers/mmc/core/core.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81626980-ffffffff816269f8: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81659ae0)
Location: drivers/regulator/core.c:3749
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81659ae0-ffffffff81659b5c: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8167eac0)
Location: drivers/regulator/core.c:3758
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8167eac0-ffffffff8167eb3c: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172fdc0)
Location: drivers/regulator/core.c:3798
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8172fdc0-ffffffff8172fe38: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8174ca90)
Location: drivers/regulator/core.c:3928
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8174ca90-ffffffff8174cb08: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81730330)
Location: drivers/regulator/core.c:3926
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81730330-ffffffff817303a8: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817b0150)
Location: drivers/regulator/core.c:4026
Inline: False
Direct callers:
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff817b0150-ffffffff817b01c8: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff818eb590)
Location: drivers/regulator/core.c:4068
Inline: False
Direct callers:
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff818eb590-ffffffff818eb62c: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a42390)
Location: drivers/regulator/core.c:4098
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_config_regulator_single
  - drivers/opp/core.c:_opp_config_regulator_single
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81a42390-ffffffff81a4242c: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a8c480)
Location: drivers/regulator/core.c:4164
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_config_regulator_single
  - drivers/opp/core.c:_opp_config_regulator_single
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81a8c480-ffffffff81a8c51c: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81adec80)
Location: drivers/regulator/core.c:4170
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_config_regulator_single
  - drivers/opp/core.c:_opp_config_regulator_single
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81adec80-ffffffff81aded1c: regulator_set_voltage (STB_GLOBAL)
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
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010848950)
Location: drivers/regulator/core.c:3758
Inline: False
Direct callers:
  - drivers/soc/imx/gpcv2.c:imx_pgc_domain_probe
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
  - drivers/mmc/host/mmci.c:mmci_sig_volt_switch
  - drivers/mmc/host/mmci.c:mmci_sig_volt_switch
  - drivers/mmc/host/mmci.c:mmci_sig_volt_switch
```
**Symbols:**

```
ffff800010848950-ffff8000108489e0: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c095215c)
Location: drivers/regulator/core.c:3758
Inline: False
Direct callers:
  - drivers/soc/imx/gpcv2.c:imx_pgc_domain_probe
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/opp/ti-opp-supply.c:_opp_set_voltage
  - drivers/opp/ti-opp-supply.c:_opp_set_voltage
  - drivers/cpufreq/omap-cpufreq.c:omap_target
  - drivers/cpufreq/omap-cpufreq.c:omap_target
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
  - drivers/mmc/host/mmci.c:mmci_sig_volt_switch
  - drivers/mmc/host/mmci.c:mmci_sig_volt_switch
  - drivers/mmc/host/mmci.c:mmci_sig_volt_switch
```
**Symbols:**

```
c095215c-c09521f0: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e5820)
Location: drivers/regulator/core.c:3758
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
c0000000008e5820-c0000000008e58c8: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000528b9a)
Location: drivers/regulator/core.c:3758
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffe000528b9a-ffffffe000528bf6: regulator_set_voltage (STB_GLOBAL)
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
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81644520)
Location: drivers/regulator/core.c:3758
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81644520-ffffffff8164459c: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816249a0)
Location: drivers/regulator/core.c:3758
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/opp/core.c:_set_opp_voltage
```
**Symbols:**

```
ffffffff816249a0-ffffffff81624a1c: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81672900)
Location: drivers/regulator/core.c:3758
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff81672900-ffffffff8167297c: regulator_set_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int regulator_set_voltage(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8168cf60)
Location: drivers/regulator/core.c:3758
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/opp/core.c:_set_opp_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
  - drivers/mmc/core/regulator.c:mmc_regulator_set_ocr
```
**Symbols:**

```
ffffffff8168cf60-ffffffff8168cfdc: regulator_set_voltage (STB_GLOBAL)
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
