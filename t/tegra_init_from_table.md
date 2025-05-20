# Function: <code>tegra_init_from_table</code>

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
<summary>In <code>armhf</code>: ✅</summary>

```c
void tegra_init_from_table(struct tegra_clk_init_table *tbl, struct clk **clks, int clk_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/tegra/clk.c (c1585fd8)
Location: drivers/clk/tegra/clk.c:238
Inline: False
Direct callers:
  - drivers/clk/tegra/clk-tegra20.c:tegra20_clock_apply_init_table
  - drivers/clk/tegra/clk-tegra30.c:tegra30_clock_apply_init_table
  - drivers/clk/tegra/clk-tegra114.c:tegra114_clock_apply_init_table
  - drivers/clk/tegra/clk-tegra124.c:tegra132_clock_apply_init_table
  - drivers/clk/tegra/clk-tegra124.c:tegra132_clock_apply_init_table
  - drivers/clk/tegra/clk-tegra124.c:tegra124_clock_apply_init_table
  - drivers/clk/tegra/clk-tegra124.c:tegra124_clock_apply_init_table
```
**Symbols:**

```
c1585fd8-c15861a8: tegra_init_from_table (STB_GLOBAL)
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
