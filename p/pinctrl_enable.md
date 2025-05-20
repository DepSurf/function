# Function: <code>pinctrl_enable</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8148fd50)
Location: drivers/pinctrl/core.c:2048
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register
```
**Symbols:**

```
ffffffff8148fd50-ffffffff8148ffe1: pinctrl_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814cbf00)
Location: drivers/pinctrl/core.c:2057
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff814cbf00-ffffffff814cc1a5: pinctrl_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:2006
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff814fd905-ffffffff814fd953: pinctrl_enable.cold.22 (STB_LOCAL)
ffffffff814fce80-ffffffff814fd15d: pinctrl_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81511969)
Location: drivers/pinctrl/core.c:2034
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff81512375-ffffffff815123c3: pinctrl_enable.cold.21 (STB_LOCAL)
ffffffff815118e0-ffffffff81511bbd: pinctrl_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:2023
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff815409e1-ffffffff81540a8d: pinctrl_enable.cold (STB_LOCAL)
ffffffff8153fed0-ffffffff8154017f: pinctrl_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:2050
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff8156185b-ffffffff8156190a: pinctrl_enable.cold (STB_LOCAL)
ffffffff81560d90-ffffffff81561033: pinctrl_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:2047
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff81603f45-ffffffff81603f65: pinctrl_enable.cold (STB_LOCAL)
ffffffff81603820-ffffffff81603887: pinctrl_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:2070
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff81bf516a-ffffffff81bf518a: pinctrl_enable.cold (STB_LOCAL)
ffffffff81628730-ffffffff81628797: pinctrl_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:2095
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff81be6fe1-ffffffff81be7001: pinctrl_enable.cold (STB_LOCAL)
ffffffff8160c210-ffffffff8160c277: pinctrl_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:2095
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff81ce04f3-ffffffff81ce0527: pinctrl_enable.cold (STB_LOCAL)
ffffffff8167af10-ffffffff8167af77: pinctrl_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:2095
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff81ea6c3e-ffffffff81ea6c70: pinctrl_enable.cold (STB_LOCAL)
ffffffff81796610-ffffffff8179667d: pinctrl_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818abd90)
Location: drivers/pinctrl/core.c:2094
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff818abd90-ffffffff818abe38: pinctrl_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818eecd0)
Location: drivers/pinctrl/core.c:2103
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff818eecd0-ffffffff818eed78: pinctrl_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81936490)
Location: drivers/pinctrl/core.c:2117
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_register
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff81936490-ffffffff81936538: pinctrl_enable (STB_GLOBAL)
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
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffff80001068d8c8)
Location: drivers/pinctrl/core.c:2050
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_register_pinctrl
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_paris_pinctrl_probe
```
**Symbols:**

```
ffff80001068d8c8-ffff80001068dbe0: pinctrl_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c082f920)
Location: drivers/pinctrl/core.c:2050
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pinctrl_probe
  - drivers/pinctrl/pinctrl-rza2.c:rza2_pinctrl_probe
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_register_pinctrl
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_probe
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
```
**Symbols:**

```
c082f920-c082fc64: pinctrl_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c000000000827930)
Location: drivers/pinctrl/core.c:2050
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
c000000000827930-c000000000827e94: pinctrl_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffe000499a7c)
Location: drivers/pinctrl/core.c:2050
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffe000499a7c-ffffffe000499d5e: pinctrl_enable (STB_GLOBAL)
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
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:2050
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register
```
**Symbols:**

```
ffffffff81559e4b-ffffffff81559efa: pinctrl_enable.cold (STB_LOCAL)
ffffffff81559380-ffffffff81559623: pinctrl_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:2050
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register
```
**Symbols:**

```
ffffffff8154a30b-ffffffff8154a3ba: pinctrl_enable.cold (STB_LOCAL)
ffffffff81549840-ffffffff81549ae3: pinctrl_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:2050
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff81555b8b-ffffffff81555c3a: pinctrl_enable.cold (STB_LOCAL)
ffffffff815550c0-ffffffff81555363: pinctrl_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pinctrl_enable(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:2050
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff8156fa1b-ffffffff8156faca: pinctrl_enable.cold (STB_LOCAL)
ffffffff8156ef50-ffffffff8156f1f3: pinctrl_enable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
