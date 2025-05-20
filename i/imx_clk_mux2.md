# Function: <code>imx_clk_mux2</code>

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
In drivers/clk/imx/clk-imx8mm.c (ffff8000107d86f8)
Location: drivers/clk/imx/clk.h:397
Inline: True
Inline callers:
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
```
```
In drivers/clk/imx/clk-imx8mn.c (ffff8000107dba3c)
Location: drivers/clk/imx/clk.h:397
Inline: True
Inline callers:
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
```
```
In drivers/clk/imx/clk-imx8mq.c (ffff8000107de528)
Location: drivers/clk/imx/clk.h:397
Inline: True
Inline callers:
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
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
