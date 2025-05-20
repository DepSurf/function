# Function: <code>clk_pll_round_rate</code>

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
long int clk_pll_round_rate(struct clk_hw *hw, long unsigned int rate, long unsigned int *prate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/imx/clk-frac-pll.c (ffff8000107d3890)
Location: drivers/clk/imx/clk-frac-pll.c:121
Inline: False
```
**Symbols:**

```
ffff8000107d3890-ffff8000107d38f0: clk_pll_round_rate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
long int clk_pll_round_rate(struct clk_hw *hwclk, long unsigned int rate, long unsigned int *parent_rate);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-highbank.c (c08f4460)
Location: drivers/clk/clk-highbank.c:134
Inline: False
```
```
In drivers/clk/imx/clk-frac-pll.c (c08faecc)
Location: drivers/clk/imx/clk-frac-pll.c:121
Inline: False
```
```
In drivers/clk/tegra/clk-pll.c (c09105a4)
Location: drivers/clk/tegra/clk-pll.c:820
Inline: True
```
**Symbols:**

```
c08f4460-c08f44d8: clk_pll_round_rate (STB_LOCAL)
c08faecc-c08faf64: clk_pll_round_rate (STB_LOCAL)
c09105a4-c0910674: clk_pll_round_rate (STB_LOCAL)
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
