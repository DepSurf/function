# Function: <code>imx_check_clk_hws</code>

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
void imx_check_clk_hws(struct clk_hw **clks, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/imx/clk.c (ffff8000107d1db8)
Location: drivers/clk/imx/clk.c:45
Inline: False
```
**Symbols:**

```
ffff8000107d1db8-ffff8000107d1e28: imx_check_clk_hws (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void imx_check_clk_hws(struct clk_hw **clks, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/imx/clk.c (c08f9794)
Location: drivers/clk/imx/clk.c:45
Inline: False
Direct callers:
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_smc1_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_pcc3_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_pcc2_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_scg1_init
```
**Symbols:**

```
c08f9794-c08f97f0: imx_check_clk_hws (STB_GLOBAL)
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
