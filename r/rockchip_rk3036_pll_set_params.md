# Function: <code>rockchip_rk3036_pll_set_params</code>

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
int rockchip_rk3036_pll_set_params(struct rockchip_clk_pll *pll, const struct rockchip_pll_rate_table *rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/rockchip/clk-pll.c (ffff8000107edc80)
Location: drivers/clk/rockchip/clk-pll.c:178
Inline: False
Direct callers:
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_init
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_set_rate
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_set_params
```
**Symbols:**

```
ffff8000107edc80-ffff8000107ede14: rockchip_rk3036_pll_set_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rockchip_rk3036_pll_set_params(struct rockchip_clk_pll *pll, const struct rockchip_pll_rate_table *rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/rockchip/clk-pll.c (c0906f68)
Location: drivers/clk/rockchip/clk-pll.c:178
Inline: False
Direct callers:
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_init
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_set_params
```
**Symbols:**

```
c0906f68-c0907104: rockchip_rk3036_pll_set_params (STB_LOCAL)
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
