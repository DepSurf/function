# Function: <code>rcar_rst_read_mode_pins</code>

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
int rcar_rst_read_mode_pins(u32 *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/soc/renesas/rcar-rst.c (ffff800011490fe8)
Location: drivers/soc/renesas/rcar-rst.c:110
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
ffff800011490fe8-ffff800011491140: rcar_rst_read_mode_pins (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rcar_rst_read_mode_pins(u32 *mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/soc/renesas/rcar-rst.c (c1590a14)
Location: drivers/soc/renesas/rcar-rst.c:110
Inline: False
Direct callers:
  - drivers/clk/renesas/r8a7743-cpg-mssr.c:r8a7743_cpg_mssr_init
  - drivers/clk/renesas/r8a7745-cpg-mssr.c:r8a7745_cpg_mssr_init
  - drivers/clk/renesas/r8a77470-cpg-mssr.c:r8a77470_cpg_mssr_init
  - drivers/clk/renesas/clk-r8a7778.c:r8a7778_cpg_clocks_init
  - drivers/clk/renesas/clk-r8a7779.c:r8a7779_cpg_clocks_init
  - drivers/clk/renesas/r8a7790-cpg-mssr.c:r8a7790_cpg_mssr_init
  - drivers/clk/renesas/r8a7791-cpg-mssr.c:r8a7791_cpg_mssr_init
  - drivers/clk/renesas/r8a7792-cpg-mssr.c:r8a7792_cpg_mssr_init
  - drivers/clk/renesas/r8a7794-cpg-mssr.c:r8a7794_cpg_mssr_init
  - drivers/clk/renesas/clk-rcar-gen2.c:rcar_gen2_cpg_clocks_init
```
**Symbols:**

```
c1590a14-c1590b64: rcar_rst_read_mode_pins (STB_GLOBAL)
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
