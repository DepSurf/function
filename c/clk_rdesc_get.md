# Function: <code>clk_rdesc_get</code>

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
In drivers/clk/renesas/r9a06g032-clocks.c (ffff8000107ea870)
Location: drivers/clk/renesas/r9a06g032-clocks.c:331
Inline: True
Direct callers:
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_dualgate_is_enabled
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_dualgate_is_enabled
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_dualgate_setenable
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_mux_get_parent
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_is_enabled
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_is_enabled
```
**Symbols:**

```
ffff8000107ea870-ffff8000107ea8c8: clk_rdesc_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/renesas/r9a06g032-clocks.c (c0903f74)
Location: drivers/clk/renesas/r9a06g032-clocks.c:331
Inline: True
Inline callers:
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_dualgate_is_enabled
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_dualgate_is_enabled
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_dualgate_setenable
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_mux_get_parent
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_is_enabled
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_is_enabled
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
