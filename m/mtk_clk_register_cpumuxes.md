# Function: <code>mtk_clk_register_cpumuxes</code>

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
int mtk_clk_register_cpumuxes(struct device_node *node, const struct mtk_composite *clks, int num, struct clk_onecell_data *clk_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/mediatek/clk-cpumux.c (ffff8000107e2ef0)
Location: drivers/clk/mediatek/clk-cpumux.c:79
Inline: False
Direct callers:
  - drivers/clk/mediatek/clk-mt7622.c:mtk_infrasys_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_infrasys_init
```
**Symbols:**

```
ffff8000107e2ef0-ffff8000107e3084: mtk_clk_register_cpumuxes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mtk_clk_register_cpumuxes(struct device_node *node, const struct mtk_composite *clks, int num, struct clk_onecell_data *clk_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/mediatek/clk-cpumux.c (c0900090)
Location: drivers/clk/mediatek/clk-cpumux.c:79
Inline: False
Direct callers:
  - drivers/clk/mediatek/clk-mt7622.c:mtk_infrasys_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_infrasys_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_infrasys_init
```
**Symbols:**

```
c0900090-c0900208: mtk_clk_register_cpumuxes (STB_GLOBAL)
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
