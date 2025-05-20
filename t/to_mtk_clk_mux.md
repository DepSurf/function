# Function: <code>to_mtk_clk_mux</code>

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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/mediatek/clk-mux.c (ffff8000107e362c)
Location: drivers/clk/mediatek/clk-mux.c:15
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_setclr_lock
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_lock
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_get_parent
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_is_enabled
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_disable_setclr
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_enable_setclr
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_disable
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_enable
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
In drivers/clk/mediatek/clk-mux.c (c0900720)
Location: drivers/clk/mediatek/clk-mux.c:15
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_setclr_lock
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_lock
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_get_parent
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_is_enabled
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_disable_setclr
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_enable_setclr
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_disable
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_enable
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
