# Function: <code>mtk_pericfg_init</code>

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
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
int mtk_pericfg_init(struct platform_device *pdev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/mediatek/clk-mt7622.c (ffff8000107e4e60)
Location: drivers/clk/mediatek/clk-mt7622.c:692
Inline: False
```
```
In drivers/clk/mediatek/clk-mt8173.c (ffff8000114864f4)
Location: drivers/clk/mediatek/clk-mt8173.c:975
Inline: False
```
**Symbols:**

```
ffff8000107e4e60-ffff8000107e4f74: mtk_pericfg_init (STB_LOCAL)
ffff8000114864f4-ffff8000114865d8: mtk_pericfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int mtk_pericfg_init(struct platform_device *pdev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/mediatek/clk-mt7622.c (c0900b50)
Location: drivers/clk/mediatek/clk-mt7622.c:692
Inline: False
```
```
In drivers/clk/mediatek/clk-mt7629.c (c09013c0)
Location: drivers/clk/mediatek/clk-mt7629.c:623
Inline: False
```
```
In drivers/clk/mediatek/clk-mt8135.c (c157bdd0)
Location: drivers/clk/mediatek/clk-mt8135.c:565
Inline: False
```
```
In drivers/clk/mediatek/clk-mt8173.c (c157c320)
Location: drivers/clk/mediatek/clk-mt8173.c:975
Inline: False
```
**Symbols:**

```
c0900b50-c0900c50: mtk_pericfg_init (STB_LOCAL)
c09013c0-c09014a4: mtk_pericfg_init (STB_LOCAL)
c157bdd0-c157bea0: mtk_pericfg_init (STB_LOCAL)
c157c320-c157c3ec: mtk_pericfg_init (STB_LOCAL)
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
