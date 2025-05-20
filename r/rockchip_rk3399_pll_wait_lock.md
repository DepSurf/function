# Function: <code>rockchip_rk3399_pll_wait_lock</code>

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
In drivers/clk/rockchip/clk-pll.c (ffff8000107ece60)
Location: drivers/clk/rockchip/clk-pll.c:585
Inline: True
Direct callers:
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_enable
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_set_params
```
**Symbols:**

```
ffff8000107ece60-ffff8000107ececc: rockchip_rk3399_pll_wait_lock.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/rockchip/clk-pll.c (c0907594)
Location: drivers/clk/rockchip/clk-pll.c:585
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_enable
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_enable
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_set_params
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
