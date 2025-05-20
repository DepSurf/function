# Function: <code>imx_obtain_fixed_clk_hw</code>

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
struct clk_hw *imx_obtain_fixed_clk_hw(struct device_node *np, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/imx/clk.c (ffff800011485a10)
Location: drivers/clk/imx/clk.c:97
Inline: False
```
**Symbols:**

```
ffff800011485a10-ffff800011485a58: imx_obtain_fixed_clk_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk_hw *imx_obtain_fixed_clk_hw(struct device_node *np, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/imx/clk.c (c1557f7c)
Location: drivers/clk/imx/clk.c:97
Inline: False
Direct callers:
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_scg1_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_scg1_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_scg1_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_scg1_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_scg1_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_scg1_init
```
**Symbols:**

```
c1557f7c-c1557fac: imx_obtain_fixed_clk_hw (STB_GLOBAL)
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
