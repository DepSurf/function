# Function: <code>mtk_clk_register_fixed_clks</code>

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
void mtk_clk_register_fixed_clks(const struct mtk_fixed_clk *clks, int num, struct clk_onecell_data *clk_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/mediatek/clk-mtk.c (ffff8000107e1750)
Location: drivers/clk/mediatek/clk-mtk.c:45
Inline: False
Direct callers:
  - drivers/clk/mediatek/clk-mt6779.c:clk_mt6779_top_probe
  - drivers/clk/mediatek/clk-mt2712.c:clk_mt2712_top_probe
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt8183.c:clk_mt8183_top_probe
  - drivers/clk/mediatek/clk-mt8516.c:mtk_topckgen_init
```
**Symbols:**

```
ffff8000107e1750-ffff8000107e182c: mtk_clk_register_fixed_clks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mtk_clk_register_fixed_clks(const struct mtk_fixed_clk *clks, int num, struct clk_onecell_data *clk_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/mediatek/clk-mtk.c (c08fea08)
Location: drivers/clk/mediatek/clk-mtk.c:45
Inline: False
Direct callers:
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt8516.c:mtk_topckgen_init
```
**Symbols:**

```
c08fea08-c08feaec: mtk_clk_register_fixed_clks (STB_GLOBAL)
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
