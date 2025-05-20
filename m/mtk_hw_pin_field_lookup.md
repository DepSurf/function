# Function: <code>mtk_hw_pin_field_lookup</code>

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
In drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c (ffff8000106bab58)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:65
Inline: True
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_get_value
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value
```
**Symbols:**

```
ffff8000106bab58-ffff8000106bad24: mtk_hw_pin_field_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mtk_hw_pin_field_lookup(struct mtk_pinctrl *hw, const struct mtk_pin_desc *desc, int field, struct mtk_pin_field *pfd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c (c085b7f0)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:65
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_get_value
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value
```
**Symbols:**

```
c085b7f0-c085b9c0: mtk_hw_pin_field_lookup (STB_LOCAL)
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
