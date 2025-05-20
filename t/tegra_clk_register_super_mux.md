# Function: <code>tegra_clk_register_super_mux</code>

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
struct clk *tegra_clk_register_super_mux(const char *name, const char **parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 clk_super_flags, u8 width, u8 pllx_index, u8 div2_index, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/tegra/clk-super.c (c0912934)
Location: drivers/clk/tegra/clk-super.c:159
Inline: False
Direct callers:
  - drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init
  - drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init
  - drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init
  - drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init
  - drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init
  - drivers/clk/tegra/clk-tegra20.c:tegra20_clock_init
  - drivers/clk/tegra/clk-tegra20.c:tegra20_clock_init
  - drivers/clk/tegra/clk-tegra30.c:tegra30_super_clk_init
  - drivers/clk/tegra/clk-tegra30.c:tegra30_super_clk_init
  - drivers/clk/tegra/clk-tegra30.c:tegra30_super_clk_init
```
**Symbols:**

```
c0912934-c0912a50: tegra_clk_register_super_mux (STB_GLOBAL)
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
