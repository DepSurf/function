# Function: <code>mtk_pctrl_is_function_valid</code>

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
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (ffff8000106b8b30)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:439
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_set_mux
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_dt_node_to_map
```
```
In drivers/pinctrl/mediatek/pinctrl-paris.c (ffff8000106bc258)
Location: drivers/pinctrl/mediatek/pinctrl-paris.c:373
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pmx_set_mux
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pctrl_dt_node_to_map
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool mtk_pctrl_is_function_valid(struct mtk_pinctrl *pctl, u32 pin_num, u32 fnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (c0858e98)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:439
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_set_mux
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_dt_node_to_map
```
**Symbols:**

```
c0858e98-c0858f24: mtk_pctrl_is_function_valid (STB_LOCAL)
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
