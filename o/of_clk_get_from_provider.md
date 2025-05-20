# Function: <code>of_clk_get_from_provider</code>

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
struct clk *of_clk_get_from_provider(struct of_phandle_args *clkspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107bed28)
Location: drivers/clk/clk.c:4583
Inline: False
Direct callers:
  - drivers/clk/clk.c:of_clk_get_parent_name
  - drivers/clk/imx/clk.c:imx_obtain_fixed_clock_from_dt
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_attach_dev
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_attach_dev
```
**Symbols:**

```
ffff8000107bed28-ffff8000107bed84: of_clk_get_from_provider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk *of_clk_get_from_provider(struct of_phandle_args *clkspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08eb3b0)
Location: drivers/clk/clk.c:4583
Inline: False
Direct callers:
  - drivers/clk/clk.c:of_clk_get_parent_name
  - drivers/clk/imx/clk.c:imx_obtain_fixed_clock_from_dt
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_attach_dev
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_attach_dev
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_attach_dev
  - drivers/clk/ti/clk.c:ti_clk_add_aliases
  - drivers/clk/ti/clk.c:ti_dt_clocks_register
  - drivers/clk/ti/clk-dra7-atl.c:of_dra7_atl_clk_probe
```
**Symbols:**

```
c08eb3b0-c08eb404: of_clk_get_from_provider (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct clk *of_clk_get_from_provider(struct of_phandle_args *clkspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050e09e)
Location: drivers/clk/clk.c:4583
Inline: False
Direct callers:
  - drivers/clk/clk.c:of_clk_get_parent_name
```
**Symbols:**

```
ffffffe00050e09e-ffffffe00050e0ea: of_clk_get_from_provider (STB_GLOBAL)
```
</details>
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
