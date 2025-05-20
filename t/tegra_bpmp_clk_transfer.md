# Function: <code>tegra_bpmp_clk_transfer</code>

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
int tegra_bpmp_clk_transfer(struct tegra_bpmp *bpmp, const struct tegra_bpmp_clk_message *clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/tegra/clk-bpmp.c (c0914ad8)
Location: drivers/clk/tegra/clk-bpmp.c:59
Inline: False
Direct callers:
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_init_clocks
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_clk_get_info
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_clk_set_rate
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_clk_get_parent
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_clk_set_parent
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_clk_round_rate
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_clk_recalc_rate
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_clk_is_prepared
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_clk_unprepare
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_clk_prepare
```
**Symbols:**

```
c0914ad8-c0914bc4: tegra_bpmp_clk_transfer (STB_LOCAL)
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
