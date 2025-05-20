# Function: <code>rockchip_clk_register_cpuclk</code>

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
struct clk *rockchip_clk_register_cpuclk(const char *name, const const char * *parent_names, u8 num_parents, const struct rockchip_cpuclk_reg_data *reg_data, const struct rockchip_cpuclk_rate_table *rates, int nrates, void *reg_base, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/rockchip/clk-cpu.c (ffff8000107ee9f8)
Location: drivers/clk/rockchip/clk-cpu.c:246
Inline: False
Direct callers:
  - drivers/clk/rockchip/clk.c:rockchip_clk_register_armclk
```
**Symbols:**

```
ffff8000107ee9f8-ffff8000107eec88: rockchip_clk_register_cpuclk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk *rockchip_clk_register_cpuclk(const char *name, const const char * *parent_names, u8 num_parents, const struct rockchip_cpuclk_reg_data *reg_data, const struct rockchip_cpuclk_rate_table *rates, int nrates, void *reg_base, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/rockchip/clk-cpu.c (c0908184)
Location: drivers/clk/rockchip/clk-cpu.c:246
Inline: False
Direct callers:
  - drivers/clk/rockchip/clk.c:rockchip_clk_register_armclk
```
**Symbols:**

```
c0908184-c0908424: rockchip_clk_register_cpuclk (STB_GLOBAL)
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
