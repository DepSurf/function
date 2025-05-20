# Function: <code>rcar_gen3_cpg_init</code>

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
int rcar_gen3_cpg_init(const struct rcar_gen3_cpg_pll_config *config, unsigned int clk_extalr, u32 mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/renesas/rcar-gen3-cpg.c (ffff8000114883a0)
Location: drivers/clk/renesas/rcar-gen3-cpg.c:709
Inline: False
Direct callers:
  - drivers/clk/renesas/r8a774a1-cpg-mssr.c:r8a774a1_cpg_mssr_init
  - drivers/clk/renesas/r8a774c0-cpg-mssr.c:r8a774c0_cpg_mssr_init
  - drivers/clk/renesas/r8a7795-cpg-mssr.c:r8a7795_cpg_mssr_init
  - drivers/clk/renesas/r8a7796-cpg-mssr.c:r8a7796_cpg_mssr_init
  - drivers/clk/renesas/r8a77965-cpg-mssr.c:r8a77965_cpg_mssr_init
  - drivers/clk/renesas/r8a77970-cpg-mssr.c:r8a77970_cpg_mssr_init
  - drivers/clk/renesas/r8a77980-cpg-mssr.c:r8a77980_cpg_mssr_init
  - drivers/clk/renesas/r8a77990-cpg-mssr.c:r8a77990_cpg_mssr_init
  - drivers/clk/renesas/r8a77995-cpg-mssr.c:r8a77995_cpg_mssr_init
```
**Symbols:**

```
ffff8000114883a0-ffff800011488438: rcar_gen3_cpg_init (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
