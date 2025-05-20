# Function: <code>rockchip_clk_register_armclk</code>

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
void rockchip_clk_register_armclk(struct rockchip_clk_provider *ctx, unsigned int lookup_id, const char *name, const const char * *parent_names, u8 num_parents, const struct rockchip_cpuclk_reg_data *reg_data, const struct rockchip_cpuclk_rate_table *rates, int nrates);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/rockchip/clk.c (ffff800011489cc0)
Location: drivers/clk/rockchip/clk.c:570
Inline: False
Direct callers:
  - drivers/clk/rockchip/clk-px30.c:px30_clk_init
  - drivers/clk/rockchip/clk-rv1108.c:rv1108_clk_init
  - drivers/clk/rockchip/clk-rk3036.c:rk3036_clk_init
  - drivers/clk/rockchip/clk-rk3128.c:rk3128_common_clk_init
  - drivers/clk/rockchip/clk-rk3188.c:rk3188a_clk_init
  - drivers/clk/rockchip/clk-rk3188.c:rk3066a_clk_init
  - drivers/clk/rockchip/clk-rk3228.c:rk3228_clk_init
  - drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_init
  - drivers/clk/rockchip/clk-rk3308.c:rk3308_clk_init
  - drivers/clk/rockchip/clk-rk3328.c:rk3328_clk_init
  - drivers/clk/rockchip/clk-rk3368.c:rk3368_clk_init
  - drivers/clk/rockchip/clk-rk3368.c:rk3368_clk_init
  - drivers/clk/rockchip/clk-rk3399.c:rk3399_clk_init
  - drivers/clk/rockchip/clk-rk3399.c:rk3399_clk_init
```
**Symbols:**

```
ffff800011489cc0-ffff800011489d78: rockchip_clk_register_armclk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rockchip_clk_register_armclk(struct rockchip_clk_provider *ctx, unsigned int lookup_id, const char *name, const const char * *parent_names, u8 num_parents, const struct rockchip_cpuclk_reg_data *reg_data, const struct rockchip_cpuclk_rate_table *rates, int nrates);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/rockchip/clk.c (c1582f40)
Location: drivers/clk/rockchip/clk.c:570
Inline: False
Direct callers:
  - drivers/clk/rockchip/clk-px30.c:px30_clk_init
  - drivers/clk/rockchip/clk-rv1108.c:rv1108_clk_init
  - drivers/clk/rockchip/clk-rk3036.c:rk3036_clk_init
  - drivers/clk/rockchip/clk-rk3128.c:rk3128_common_clk_init
  - drivers/clk/rockchip/clk-rk3188.c:rk3188a_clk_init
  - drivers/clk/rockchip/clk-rk3188.c:rk3066a_clk_init
  - drivers/clk/rockchip/clk-rk3228.c:rk3228_clk_init
  - drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_init
  - drivers/clk/rockchip/clk-rk3308.c:rk3308_clk_init
  - drivers/clk/rockchip/clk-rk3328.c:rk3328_clk_init
  - drivers/clk/rockchip/clk-rk3368.c:rk3368_clk_init
  - drivers/clk/rockchip/clk-rk3368.c:rk3368_clk_init
  - drivers/clk/rockchip/clk-rk3399.c:rk3399_clk_init
  - drivers/clk/rockchip/clk-rk3399.c:rk3399_clk_init
```
**Symbols:**

```
c1582f40-c1582fd8: rockchip_clk_register_armclk (STB_GLOBAL)
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
