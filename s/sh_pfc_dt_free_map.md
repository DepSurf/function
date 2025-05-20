# Function: <code>sh_pfc_dt_free_map</code>

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

```c
void sh_pfc_dt_free_map(struct pinctrl_dev *pctldev, struct pinctrl_map *map, unsigned int num_maps);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/sh-pfc/pinctrl.c (ffff8000106b0b60)
Location: drivers/pinctrl/sh-pfc/pinctrl.c:241
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_node_to_map
Direct callers:
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_node_to_map
```
**Symbols:**

```
ffff8000106b05d8-ffff8000106b065c: sh_pfc_dt_free_map.part.0 (STB_LOCAL)
ffff8000106b0660-ffff8000106b0698: sh_pfc_dt_free_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sh_pfc_dt_free_map(struct pinctrl_dev *pctldev, struct pinctrl_map *map, unsigned int num_maps);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/sh-pfc/pinctrl.c (c0854d88)
Location: drivers/pinctrl/sh-pfc/pinctrl.c:241
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_node_to_map
Direct callers:
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_node_to_map
```
**Symbols:**

```
c08547e4-c0854850: sh_pfc_dt_free_map.part.0 (STB_LOCAL)
c0854850-c0854878: sh_pfc_dt_free_map (STB_LOCAL)
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
