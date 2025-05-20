# Function: <code>sh_pfc_pin_to_bias_reg</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
const struct pinmux_bias_reg *sh_pfc_pin_to_bias_reg(const struct sh_pfc *pfc, unsigned int pin, unsigned int *bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/sh-pfc/core.c (ffff8000106b01e0)
Location: drivers/pinctrl/sh-pfc/core.c:387
Inline: False
Direct callers:
  - drivers/pinctrl/sh-pfc/pfc-r8a7796.c:r8a7796_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7796.c:r8a7796_pinmux_get_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a77990.c:r8a77990_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a77990.c:r8a77990_pinmux_get_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7795.c:r8a7795_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7795.c:r8a7795_pinmux_get_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7795-es1.c:r8a7795es1_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7795-es1.c:r8a7795es1_pinmux_get_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a77965.c:r8a77965_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a77965.c:r8a77965_pinmux_get_bias
```
**Symbols:**

```
ffff8000106b01e0-ffff8000106b02b0: sh_pfc_pin_to_bias_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct pinmux_bias_reg *sh_pfc_pin_to_bias_reg(const struct sh_pfc *pfc, unsigned int pin, unsigned int *bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/sh-pfc/core.c (c0853ac0)
Location: drivers/pinctrl/sh-pfc/core.c:387
Inline: False
Direct callers:
  - drivers/pinctrl/sh-pfc/pfc-r8a7778.c:r8a7778_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7778.c:r8a7778_pinmux_get_bias
```
**Symbols:**

```
c0853ac0-c0853b94: sh_pfc_pin_to_bias_reg (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
