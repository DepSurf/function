# Function: <code>rcar_gen2_cpg_init</code>

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
int rcar_gen2_cpg_init(const struct rcar_gen2_cpg_pll_config *config, unsigned int pll0_div, u32 mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/renesas/rcar-gen2-cpg.c (c15811f8)
Location: drivers/clk/renesas/rcar-gen2-cpg.c:375
Inline: False
Direct callers:
  - drivers/clk/renesas/r8a7743-cpg-mssr.c:r8a7743_cpg_mssr_init
  - drivers/clk/renesas/r8a7745-cpg-mssr.c:r8a7745_cpg_mssr_init
  - drivers/clk/renesas/r8a77470-cpg-mssr.c:r8a77470_cpg_mssr_init
  - drivers/clk/renesas/r8a7790-cpg-mssr.c:r8a7790_cpg_mssr_init
  - drivers/clk/renesas/r8a7791-cpg-mssr.c:r8a7791_cpg_mssr_init
  - drivers/clk/renesas/r8a7792-cpg-mssr.c:r8a7792_cpg_mssr_init
  - drivers/clk/renesas/r8a7794-cpg-mssr.c:r8a7794_cpg_mssr_init
```
**Symbols:**

```
c15811f8-c158128c: rcar_gen2_cpg_init (STB_GLOBAL)
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
