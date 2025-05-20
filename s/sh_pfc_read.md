# Function: <code>sh_pfc_read</code>

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
u32 sh_pfc_read(struct sh_pfc *pfc, u32 reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/sh-pfc/core.c (ffff8000106afce8)
Location: drivers/pinctrl/sh-pfc/core.c:172
Inline: False
Direct callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_save_reg
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get
  - drivers/pinctrl/sh-pfc/pfc-r8a7796.c:r8a7796_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7796.c:r8a7796_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7796.c:r8a7796_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7796.c:r8a7796_pinmux_get_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7796.c:r8a7796_pinmux_get_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a77990.c:r8a77990_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a77990.c:r8a77990_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a77990.c:r8a77990_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a77990.c:r8a77990_pinmux_get_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a77990.c:r8a77990_pinmux_get_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7795.c:r8a7795_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7795.c:r8a7795_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7795.c:r8a7795_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7795.c:r8a7795_pinmux_get_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7795.c:r8a7795_pinmux_get_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7795-es1.c:r8a7795es1_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7795-es1.c:r8a7795es1_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7795-es1.c:r8a7795es1_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7795-es1.c:r8a7795es1_pinmux_get_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7795-es1.c:r8a7795es1_pinmux_get_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a77965.c:r8a77965_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a77965.c:r8a77965_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a77965.c:r8a77965_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a77965.c:r8a77965_pinmux_get_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a77965.c:r8a77965_pinmux_get_bias
```
**Symbols:**

```
ffff8000106afce8-ffff8000106afd28: sh_pfc_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u32 sh_pfc_read(struct sh_pfc *pfc, u32 reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/sh-pfc/core.c (c0853528)
Location: drivers/pinctrl/sh-pfc/core.c:172
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_save_reg
Direct callers:
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get
```
**Symbols:**

```
c085368c-c08536b0: sh_pfc_read (STB_GLOBAL)
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
