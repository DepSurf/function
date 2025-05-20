# Function: <code>clk_pll_recalc_rate</code>

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
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
long unsigned int clk_pll_recalc_rate(struct clk_hw *hw, long unsigned int parent_rate);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/imx/clk-frac-pll.c (ffff8000107d39f0)
Location: drivers/clk/imx/clk-frac-pll.c:95
Inline: False
```
```
In drivers/clk/socfpga/clk-pll-s10.c (ffff8000107f0890)
Location: drivers/clk/socfpga/clk-pll-s10.c:30
Inline: False
```
**Symbols:**

```
ffff8000107d39f0-ffff8000107d3a58: clk_pll_recalc_rate (STB_LOCAL)
ffff8000107f0890-ffff8000107f0900: clk_pll_recalc_rate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
long unsigned int clk_pll_recalc_rate(struct clk_hw *hwclk, long unsigned int parent_rate);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-highbank.c (c08f4424)
Location: drivers/clk/clk-highbank.c:93
Inline: False
```
```
In drivers/clk/imx/clk-frac-pll.c (c08fad18)
Location: drivers/clk/imx/clk-frac-pll.c:95
Inline: False
```
```
In drivers/clk/tegra/clk-pll.c (c0910fa0)
Location: drivers/clk/tegra/clk-pll.c:840
Inline: False
```
**Symbols:**

```
c08f4424-c08f4460: clk_pll_recalc_rate (STB_LOCAL)
c08fad18-c08fadb8: clk_pll_recalc_rate (STB_LOCAL)
c0910fa0-c0911184: clk_pll_recalc_rate (STB_LOCAL)
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
