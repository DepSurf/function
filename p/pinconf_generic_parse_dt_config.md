# Function: <code>pinconf_generic_parse_dt_config</code>

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
int pinconf_generic_parse_dt_config(struct device_node *np, struct pinctrl_dev *pctldev, long unsigned int **configs, unsigned int *nconfigs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf-generic.c (ffff800010691778)
Location: drivers/pinctrl/pinconf-generic.c:238
Inline: False
Direct callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_subnode_to_map
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_functions
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_dt_node_to_map
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_dt_node_to_map
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pctrl_dt_node_to_map
```
**Symbols:**

```
ffff800010691778-ffff8000106918f4: pinconf_generic_parse_dt_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pinconf_generic_parse_dt_config(struct device_node *np, struct pinctrl_dev *pctldev, long unsigned int **configs, unsigned int *nconfigs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf-generic.c (c08332bc)
Location: drivers/pinctrl/pinconf-generic.c:238
Inline: False
Direct callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_subnode_to_map
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_dt
  - drivers/pinctrl/pinctrl-rza1.c:rza1_parse_pinmux_node
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_dt_node_to_map_one
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_dt_node_to_map
```
**Symbols:**

```
c08332bc-c083343c: pinconf_generic_parse_dt_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pinconf_generic_parse_dt_config(struct device_node *np, struct pinctrl_dev *pctldev, long unsigned int **configs, unsigned int *nconfigs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf-generic.c (c00000000082d920)
Location: drivers/pinctrl/pinconf-generic.c:238
Inline: False
Direct callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_subnode_to_map
```
**Symbols:**

```
c00000000082d920-c00000000082db04: pinconf_generic_parse_dt_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pinconf_generic_parse_dt_config(struct device_node *np, struct pinctrl_dev *pctldev, long unsigned int **configs, unsigned int *nconfigs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf-generic.c (ffffffe00049cef2)
Location: drivers/pinctrl/pinconf-generic.c:238
Inline: False
Direct callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_subnode_to_map
```
**Symbols:**

```
ffffffe00049cef2-ffffffe00049d010: pinconf_generic_parse_dt_config (STB_GLOBAL)
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
