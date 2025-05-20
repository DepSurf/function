# Function: <code>pinctrl_generic_get_group</code>

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
struct group_desc *pinctrl_generic_get_group(struct pinctrl_dev *pctldev, unsigned int selector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffff80001068b410)
Location: drivers/pinctrl/core.c:581
Inline: False
Direct callers:
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_group_dbg_show
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_dt_node_to_map
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinmux_set_mux
```
**Symbols:**

```
ffff80001068b410-ffff80001068b444: pinctrl_generic_get_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct group_desc *pinctrl_generic_get_group(struct pinctrl_dev *pctldev, unsigned int selector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c082d7c8)
Location: drivers/pinctrl/core.c:581
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux
  - drivers/pinctrl/pinctrl-rza2.c:rza2_set_mux
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_group_dbg_show
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_dt_node_to_map
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinmux_set_mux
```
**Symbols:**

```
c082d7c8-c082d7e8: pinctrl_generic_get_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct group_desc *pinctrl_generic_get_group(struct pinctrl_dev *pctldev, unsigned int selector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c000000000823de0)
Location: drivers/pinctrl/core.c:581
Inline: False
```
**Symbols:**

```
c000000000823de0-c000000000823e18: pinctrl_generic_get_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct group_desc *pinctrl_generic_get_group(struct pinctrl_dev *pctldev, unsigned int selector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffe0004979fe)
Location: drivers/pinctrl/core.c:581
Inline: False
```
**Symbols:**

```
ffffffe0004979fe-ffffffe000497a36: pinctrl_generic_get_group (STB_GLOBAL)
```
</details>
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
