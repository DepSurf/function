# Function: <code>mtk_pconf_group_get</code>

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
int mtk_pconf_group_get(struct pinctrl_dev *pctldev, unsigned int group, long unsigned int *config);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (ffff8000106b8990)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:373
Inline: False
```
```
In drivers/pinctrl/mediatek/pinctrl-paris.c (ffff8000106bbd00)
Location: drivers/pinctrl/mediatek/pinctrl-paris.c:646
Inline: False
```
**Symbols:**

```
ffff8000106b8990-ffff8000106b89e8: mtk_pconf_group_get (STB_LOCAL)
ffff8000106bbd00-ffff8000106bbd58: mtk_pconf_group_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mtk_pconf_group_get(struct pinctrl_dev *pctldev, unsigned int group, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (c08597a0)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:373
Inline: False
```
**Symbols:**

```
c08597a0-c08597dc: mtk_pconf_group_get (STB_LOCAL)
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
