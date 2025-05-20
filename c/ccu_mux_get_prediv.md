# Function: <code>ccu_mux_get_prediv</code>

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
In drivers/clk/sunxi-ng/ccu_mux.c (ffff8000107f5fac)
Location: drivers/clk/sunxi-ng/ccu_mux.c:15
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_recalc_rate
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_helper_determine_rate
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_helper_determine_rate
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_helper_determine_rate
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_helper_determine_rate
Direct callers:
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_recalc_rate
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_helper_determine_rate
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_helper_determine_rate
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_helper_determine_rate
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_helper_determine_rate
```
**Symbols:**

```
ffff8000107f5e70-ffff8000107f5f90: ccu_mux_get_prediv.part.0 (STB_LOCAL)
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
