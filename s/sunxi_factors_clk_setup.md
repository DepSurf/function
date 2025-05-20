# Function: <code>sunxi_factors_clk_setup</code>

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
struct clk *sunxi_factors_clk_setup(struct device_node *node, const struct factors_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/sunxi/clk-sunxi.c (ffff80001148b1c4)
Location: drivers/clk/sunxi/clk-sunxi.c:556
Inline: False
Direct callers:
  - drivers/clk/sunxi/clk-sunxi.c:sun6i_display_setup
  - drivers/clk/sunxi/clk-sunxi.c:sunxi_divs_clk_setup
  - drivers/clk/sunxi/clk-sunxi.c:sun7i_out_clk_setup
  - drivers/clk/sunxi/clk-sunxi.c:sun4i_apb1_clk_setup
  - drivers/clk/sunxi/clk-sunxi.c:sun6i_ahb1_clk_setup
  - drivers/clk/sunxi/clk-sunxi.c:sun5i_ahb_clk_setup
  - drivers/clk/sunxi/clk-sunxi.c:sun7i_pll4_clk_setup
  - drivers/clk/sunxi/clk-sunxi.c:sun8i_pll1_clk_setup
  - drivers/clk/sunxi/clk-sunxi.c:sun6i_pll1_clk_setup
  - drivers/clk/sunxi/clk-sunxi.c:sun4i_pll1_clk_setup
```
**Symbols:**

```
ffff80001148b1c4-ffff80001148b23c: sunxi_factors_clk_setup (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
