# Function: <code>imx_pinctrl_probe</code>

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
int imx_pinctrl_probe(struct platform_device *pdev, const struct imx_pinctrl_soc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/freescale/pinctrl-imx.c (ffff8000106a93b8)
Location: drivers/pinctrl/freescale/pinctrl-imx.c:787
Inline: False
Direct callers:
  - drivers/pinctrl/freescale/pinctrl-imx8mm.c:imx8mm_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx8mn.c:imx8mn_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx8mq.c:imx8mq_pinctrl_probe
```
**Symbols:**

```
ffff8000106a93b8-ffff8000106a9960: imx_pinctrl_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int imx_pinctrl_probe(struct platform_device *pdev, const struct imx_pinctrl_soc_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/freescale/pinctrl-imx.c (c08493dc)
Location: drivers/pinctrl/freescale/pinctrl-imx.c:787
Inline: False
Direct callers:
  - drivers/pinctrl/freescale/pinctrl-imx50.c:imx50_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx51.c:imx51_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx6q.c:imx6q_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx6dl.c:imx6dl_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx6sl.c:imx6sl_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx6sll.c:imx6sll_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx6sx.c:imx6sx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx6ul.c:imx6ul_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx7d.c:imx7d_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx7ulp.c:imx7ulp_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-vf610.c:vf610_pinctrl_probe
```
**Symbols:**

```
c08493dc-c08499c4: imx_pinctrl_probe (STB_GLOBAL)
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
