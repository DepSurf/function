# Function: <code>imx_pinctrl_parse_functions</code>

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
int imx_pinctrl_parse_functions(struct device_node *np, struct imx_pinctrl *ipctl, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/freescale/pinctrl-imx.c (ffff8000106a8678)
Location: drivers/pinctrl/freescale/pinctrl-imx.c:642
Inline: False
Direct callers:
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
```
**Symbols:**

```
ffff8000106a8678-ffff8000106a8cf8: imx_pinctrl_parse_functions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int imx_pinctrl_parse_functions(struct device_node *np, struct imx_pinctrl *ipctl, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/freescale/pinctrl-imx.c (c0848ce8)
Location: drivers/pinctrl/freescale/pinctrl-imx.c:642
Inline: False
Direct callers:
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
```
**Symbols:**

```
c0848ce8-c08493dc: imx_pinctrl_parse_functions (STB_LOCAL)
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
