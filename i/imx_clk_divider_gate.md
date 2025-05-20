# Function: <code>imx_clk_divider_gate</code>

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
struct clk_hw *imx_clk_divider_gate(const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/imx/clk-divider-gate.c (ffff8000107d30f8)
Location: drivers/clk/imx/clk-divider-gate.c:176
Inline: False
```
**Symbols:**

```
ffff8000107d30f8-ffff8000107d3254: imx_clk_divider_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk_hw *imx_clk_divider_gate(const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/imx/clk-divider-gate.c (c08fa6a8)
Location: drivers/clk/imx/clk-divider-gate.c:176
Inline: False
Direct callers:
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_scg1_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_scg1_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_scg1_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_scg1_init
```
**Symbols:**

```
c08fa6a8-c08fa7f4: imx_clk_divider_gate (STB_GLOBAL)
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
