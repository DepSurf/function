# Function: <code>mtk_clk_register_plls</code>

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
void mtk_clk_register_plls(struct device_node *node, const struct mtk_pll_data *plls, int num_plls, struct clk_onecell_data *clk_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/mediatek/clk-pll.c (ffff8000107e26a8)
Location: drivers/clk/mediatek/clk-pll.c:344
Inline: False
Direct callers:
  - drivers/clk/mediatek/clk-mt6779.c:clk_mt6779_apmixed_probe
  - drivers/clk/mediatek/clk-mt6797.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt2712.c:clk_mt2712_apmixed_probe
  - drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt8183.c:clk_mt8183_apmixed_probe
  - drivers/clk/mediatek/clk-mt8516.c:mtk_apmixedsys_init
```
**Symbols:**

```
ffff8000107e26a8-ffff8000107e28b0: mtk_clk_register_plls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mtk_clk_register_plls(struct device_node *node, const struct mtk_pll_data *plls, int num_plls, struct clk_onecell_data *clk_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/mediatek/clk-pll.c (c08ff8cc)
Location: drivers/clk/mediatek/clk-pll.c:344
Inline: False
Direct callers:
  - drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt8135.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt8516.c:mtk_apmixedsys_init
```
**Symbols:**

```
c08ff8cc-c08ffadc: mtk_clk_register_plls (STB_GLOBAL)
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
