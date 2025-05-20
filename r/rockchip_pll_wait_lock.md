# Function: <code>rockchip_pll_wait_lock</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int rockchip_pll_wait_lock(struct rockchip_clk_pll *pll);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/rockchip/clk-pll.c (ffff8000107eccf0)
Location: drivers/clk/rockchip/clk-pll.c:85
Inline: True
Direct callers:
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_enable
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_enable
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_set_params
```
**Symbols:**

```
ffff8000107eccf0-ffff8000107ecdcc: rockchip_pll_wait_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int rockchip_pll_wait_lock(struct rockchip_clk_pll *pll);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/rockchip/clk-pll.c (c0906ac0)
Location: drivers/clk/rockchip/clk-pll.c:85
Inline: True
Direct callers:
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_enable
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_enable
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_set_params
```
**Symbols:**

```
c0906ac0-c0906b94: rockchip_pll_wait_lock (STB_LOCAL)
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
