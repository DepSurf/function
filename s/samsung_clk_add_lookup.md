# Function: <code>samsung_clk_add_lookup</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void samsung_clk_add_lookup(struct samsung_clk_provider *ctx, struct clk_hw *clk_hw, unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/samsung/clk.c (c1584924)
Location: drivers/clk/samsung/clk.c:89
Inline: True
Inline callers:
  - drivers/clk/samsung/clk.c:samsung_clk_register_gate
  - drivers/clk/samsung/clk.c:samsung_clk_register_div
  - drivers/clk/samsung/clk.c:samsung_clk_register_mux
  - drivers/clk/samsung/clk.c:samsung_clk_register_fixed_factor
  - drivers/clk/samsung/clk.c:samsung_clk_register_fixed_rate
Direct callers:
  - drivers/clk/samsung/clk-pll.c:samsung_clk_register_pll
  - drivers/clk/samsung/clk-cpu.c:exynos_register_cpu_clock
  - drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_subcmus_init
```
**Symbols:**

```
c0909aa8-c0909acc: samsung_clk_add_lookup (STB_GLOBAL)
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
