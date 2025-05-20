# Function: <code>cpg_mssr_register_mod_clk</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/renesas/renesas-cpg-mssr.c (ffff8000114886ac)
Location: drivers/clk/renesas/renesas-cpg-mssr.c:382
Inline: True
Direct callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_early_init
```
**Symbols:**

```
ffff8000114886ac-ffff8000114888b8: cpg_mssr_register_mod_clk.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpg_mssr_register_mod_clk(const struct mssr_mod_clk *mod, const struct cpg_mssr_info *info, struct cpg_mssr_priv *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/renesas/renesas-cpg-mssr.c (c15814f0)
Location: drivers/clk/renesas/renesas-cpg-mssr.c:382
Inline: False
Direct callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_early_init
```
**Symbols:**

```
c15814f0-c15816f8: cpg_mssr_register_mod_clk (STB_LOCAL)
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
