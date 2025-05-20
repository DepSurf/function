# Function: <code>mtk_rmw</code>

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
void mtk_rmw(struct mtk_pinctrl *pctl, u8 i, u32 reg, u32 mask, u32 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c (ffff8000106bad28)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:55
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value
```
**Symbols:**

```
ffff8000106bad28-ffff8000106bad88: mtk_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void mtk_rmw(struct mtk_pinctrl *pctl, u8 i, u32 reg, u32 mask, u32 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c (c085ba78)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:55
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-mt7623.c:mt7623_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-mt7623.c:mt7623_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-mt7623.c:mt7623_pinctrl_probe
```
**Symbols:**

```
c085b9c0-c085b9f8: mtk_rmw (STB_GLOBAL)
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
