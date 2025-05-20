# Function: <code>tegra_lookup_dt_id</code>

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
struct clk **tegra_lookup_dt_id(int clk_id, struct tegra_clk *tegra_clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/tegra/clk.c (c158633c)
Location: drivers/clk/tegra/clk.c:340
Inline: False
Direct callers:
  - drivers/clk/tegra/clk-tegra-audio.c:tegra_audio_clk_init
  - drivers/clk/tegra/clk-tegra-audio.c:tegra_audio_clk_init
  - drivers/clk/tegra/clk-tegra-audio.c:tegra_audio_clk_init
  - drivers/clk/tegra/clk-tegra-audio.c:tegra_audio_clk_init
  - drivers/clk/tegra/clk-tegra-periph.c:tegra_periph_clk_init
  - drivers/clk/tegra/clk-tegra-periph.c:tegra_periph_clk_init
  - drivers/clk/tegra/clk-tegra-periph.c:tegra_periph_clk_init
  - drivers/clk/tegra/clk-tegra-periph.c:tegra_periph_clk_init
  - drivers/clk/tegra/clk-tegra-periph.c:tegra_periph_clk_init
  - drivers/clk/tegra/clk-tegra-periph.c:tegra_periph_clk_init
  - drivers/clk/tegra/clk-tegra-periph.c:tegra_periph_clk_init
  - drivers/clk/tegra/clk-tegra-periph.c:tegra_periph_clk_init
  - drivers/clk/tegra/clk-tegra-periph.c:tegra_periph_clk_init
  - drivers/clk/tegra/clk-tegra-pmc.c:tegra_pmc_clk_init
  - drivers/clk/tegra/clk-tegra-pmc.c:tegra_pmc_clk_init
  - drivers/clk/tegra/clk-tegra-pmc.c:tegra_pmc_clk_init
  - drivers/clk/tegra/clk-tegra-fixed.c:tegra_fixed_clk_init
  - drivers/clk/tegra/clk-tegra-fixed.c:tegra_fixed_clk_init
  - drivers/clk/tegra/clk-tegra-fixed.c:tegra_fixed_clk_init
  - drivers/clk/tegra/clk-tegra-fixed.c:tegra_osc_clk_init
  - drivers/clk/tegra/clk-tegra-fixed.c:tegra_osc_clk_init
  - drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init
  - drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init
  - drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init
  - drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init
  - drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init
  - drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init
  - drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init
  - drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init
  - drivers/clk/tegra/clk-tegra-super-gen4.c:tegra_super_clk_init
```
**Symbols:**

```
c158633c-c1586378: tegra_lookup_dt_id (STB_GLOBAL)
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
