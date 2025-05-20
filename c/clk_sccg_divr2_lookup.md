# Function: <code>clk_sccg_divr2_lookup</code>

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
int clk_sccg_divr2_lookup(struct clk_sccg_pll_setup *setup, struct clk_sccg_pll_setup *temp_setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/imx/clk-sccg-pll.c (ffff8000107d5f18)
Location: drivers/clk/imx/clk-sccg-pll.c:173
Inline: False
Direct callers:
  - drivers/clk/imx/clk-sccg-pll.c:__clk_sccg_pll_determine_rate
  - drivers/clk/imx/clk-sccg-pll.c:__clk_sccg_pll_determine_rate
```
**Symbols:**

```
ffff8000107d5f18-ffff8000107d60bc: clk_sccg_divr2_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int clk_sccg_divr2_lookup(struct clk_sccg_pll_setup *setup, struct clk_sccg_pll_setup *temp_setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/imx/clk-sccg-pll.c (c08fd548)
Location: drivers/clk/imx/clk-sccg-pll.c:173
Inline: False
Direct callers:
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_determine_rate
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_divf1_lookup
```
**Symbols:**

```
c08fd548-c08fd658: clk_sccg_divr2_lookup (STB_LOCAL)
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
