# Function: <code>rockchip_rk3066_pll_get_params</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/rockchip/clk-pll.c (ffff8000107ecff0)
Location: drivers/clk/rockchip/clk-pll.c:367
Inline: True
Direct callers:
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_init
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_set_params
```
**Symbols:**

```
ffff8000107ecff0-ffff8000107ed068: rockchip_rk3066_pll_get_params.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rockchip_rk3066_pll_get_params(struct rockchip_clk_pll *pll, struct rockchip_pll_rate_table *rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/rockchip/clk-pll.c (c09063ec)
Location: drivers/clk/rockchip/clk-pll.c:367
Inline: False
Direct callers:
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_init
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_recalc_rate
```
**Symbols:**

```
c09063ec-c090644c: rockchip_rk3066_pll_get_params (STB_LOCAL)
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
