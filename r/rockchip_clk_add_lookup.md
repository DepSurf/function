# Function: <code>rockchip_clk_add_lookup</code>

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
void rockchip_clk_add_lookup(struct rockchip_clk_provider *ctx, struct clk *clk, unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/rockchip/clk.c (ffff800011489d50)
Location: drivers/clk/rockchip/clk.c:406
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk.c:rockchip_clk_register_armclk
  - drivers/clk/rockchip/clk.c:rockchip_clk_register_branches
  - drivers/clk/rockchip/clk.c:rockchip_clk_register_branches
  - drivers/clk/rockchip/clk.c:rockchip_clk_register_plls
```
**Symbols:**

```
ffff8000107ecb60-ffff8000107ecba8: rockchip_clk_add_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rockchip_clk_add_lookup(struct rockchip_clk_provider *ctx, struct clk *clk, unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/rockchip/clk.c (c1582fbc)
Location: drivers/clk/rockchip/clk.c:406
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk.c:rockchip_clk_register_armclk
  - drivers/clk/rockchip/clk.c:rockchip_clk_register_branches
  - drivers/clk/rockchip/clk.c:rockchip_clk_register_branches
  - drivers/clk/rockchip/clk.c:rockchip_clk_register_plls
```
**Symbols:**

```
c09062dc-c0906304: rockchip_clk_add_lookup (STB_GLOBAL)
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
