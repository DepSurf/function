# Function: <code>mtk_pctrl_init</code>

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
int mtk_pctrl_init(struct platform_device *pdev, const struct mtk_pinctrl_devdata *data, struct regmap *regmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (ffff8000106b9680)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:1016
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-mt2712.c:mt2712_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-mt8173.c:mt8173_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-mt8516.c:mt8516_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-mt6397.c:mt6397_pinctrl_probe
```
**Symbols:**

```
ffff8000106b9680-ffff8000106b9b78: mtk_pctrl_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mtk_pctrl_init(struct platform_device *pdev, const struct mtk_pinctrl_devdata *data, struct regmap *regmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (c085a2d0)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:1016
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-mt2701.c:mt2701_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-mt8135.c:mt8135_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-mt8127.c:mt8127_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-mt6397.c:mt6397_pinctrl_probe
```
**Symbols:**

```
c085a2d0-c085a800: mtk_pctrl_init (STB_GLOBAL)
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
