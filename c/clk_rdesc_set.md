# Function: <code>clk_rdesc_set</code>

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
In drivers/clk/renesas/r9a06g032-clocks.c (ffff8000107ea9a0)
Location: drivers/clk/renesas/r9a06g032-clocks.c:320
Inline: True
Direct callers:
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_mux_set_parent
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_set
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_set
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_set
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_set
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_set
```
**Symbols:**

```
ffff8000107ea9a0-ffff8000107eaa1c: clk_rdesc_set.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void clk_rdesc_set(struct r9a06g032_priv *clocks, u16 one, unsigned int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/renesas/r9a06g032-clocks.c (c0903ff0)
Location: drivers/clk/renesas/r9a06g032-clocks.c:320
Inline: False
Direct callers:
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_mux_set_parent
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_set
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_set
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_set
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_set
```
**Symbols:**

```
c0903ff0-c0904040: clk_rdesc_set (STB_LOCAL)
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
