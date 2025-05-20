# Function: <code>mtk_pctrl_spec_pull_set_samereg</code>

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
int mtk_pctrl_spec_pull_set_samereg(struct regmap *regmap, const struct mtk_pin_spec_pupd_set_samereg *pupd_infos, unsigned int info_num, unsigned int pin, unsigned char align, bool isup, unsigned int r1r0);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (ffff8000106b9520)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:225
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-mt2712.c:mt2712_spec_pull_set
  - drivers/pinctrl/mediatek/pinctrl-mt8173.c:mt8173_spec_pull_set
  - drivers/pinctrl/mediatek/pinctrl-mt8516.c:mt8516_spec_pull_set
```
**Symbols:**

```
ffff8000106b9520-ffff8000106b9680: mtk_pctrl_spec_pull_set_samereg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mtk_pctrl_spec_pull_set_samereg(struct regmap *regmap, const struct mtk_pin_spec_pupd_set_samereg *pupd_infos, unsigned int info_num, unsigned int pin, unsigned char align, bool isup, unsigned int r1r0);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (c085a1c0)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:225
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-mt2701.c:mt2701_spec_pull_set
  - drivers/pinctrl/mediatek/pinctrl-mt8127.c:mt8127_spec_pull_set
```
**Symbols:**

```
c085a1c0-c085a2d0: mtk_pctrl_spec_pull_set_samereg (STB_GLOBAL)
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
