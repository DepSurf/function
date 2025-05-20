# Function: <code>meson_parm_read</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/meson/clk-cpu-dyndiv.c (ffff8000107e6194)
Location: drivers/clk/meson/parm.h:30
Inline: True
Inline callers:
  - drivers/clk/meson/clk-cpu-dyndiv.c:meson_clk_cpu_dyndiv_recalc_rate
```
```
In drivers/clk/meson/clk-dualdiv.c (ffff8000107e64b8)
Location: drivers/clk/meson/parm.h:30
Inline: True
Inline callers:
  - drivers/clk/meson/clk-dualdiv.c:meson_clk_dualdiv_recalc_rate
  - drivers/clk/meson/clk-dualdiv.c:meson_clk_dualdiv_recalc_rate
  - drivers/clk/meson/clk-dualdiv.c:meson_clk_dualdiv_recalc_rate
  - drivers/clk/meson/clk-dualdiv.c:meson_clk_dualdiv_recalc_rate
  - drivers/clk/meson/clk-dualdiv.c:meson_clk_dualdiv_recalc_rate
```
```
In drivers/clk/meson/clk-mpll.c (ffff8000107e6bac)
Location: drivers/clk/meson/parm.h:30
Inline: True
Inline callers:
  - drivers/clk/meson/clk-mpll.c:mpll_recalc_rate
  - drivers/clk/meson/clk-mpll.c:mpll_recalc_rate
```
```
In drivers/clk/meson/clk-pll.c (ffff8000107e7a14)
Location: drivers/clk/meson/parm.h:30
Inline: True
Inline callers:
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_set_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_enable
  - drivers/clk/meson/clk-pll.c:meson_clk_pcie_pll_enable
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_is_enabled
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_is_enabled
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_is_enabled
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_recalc_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_recalc_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_recalc_rate
```
```
In drivers/clk/meson/vid-pll-div.c (ffff8000107e815c)
Location: drivers/clk/meson/parm.h:30
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/meson/clk-mpll.c (c0901c48)
Location: drivers/clk/meson/parm.h:30
Inline: True
Inline callers:
  - drivers/clk/meson/clk-mpll.c:mpll_recalc_rate
  - drivers/clk/meson/clk-mpll.c:mpll_recalc_rate
```
```
In drivers/clk/meson/clk-pll.c (c0902b8c)
Location: drivers/clk/meson/parm.h:30
Inline: True
Inline callers:
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_set_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_enable
  - drivers/clk/meson/clk-pll.c:meson_clk_pcie_pll_enable
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_is_enabled
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_is_enabled
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_is_enabled
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_recalc_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_recalc_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_recalc_rate
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
