# Function: <code>pinctrl_find_cells_size</code>

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
In drivers/pinctrl/devicetree.c (ffff800010690ad8)
Location: drivers/pinctrl/devicetree.c:290
Inline: True
Direct callers:
  - drivers/pinctrl/devicetree.c:pinctrl_parse_index_with_args
  - drivers/pinctrl/devicetree.c:pinctrl_count_index_with_args
```
**Symbols:**

```
ffff800010690ad8-ffff800010690b7c: pinctrl_find_cells_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pinctrl_find_cells_size(const struct device_node *np);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/devicetree.c (c08326f4)
Location: drivers/pinctrl/devicetree.c:290
Inline: False
Direct callers:
  - drivers/pinctrl/devicetree.c:pinctrl_parse_index_with_args
  - drivers/pinctrl/devicetree.c:pinctrl_count_index_with_args
```
**Symbols:**

```
c08326f4-c08327a4: pinctrl_find_cells_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/devicetree.c (c00000000082c600)
Location: drivers/pinctrl/devicetree.c:290
Inline: True
Direct callers:
  - drivers/pinctrl/devicetree.c:pinctrl_parse_index_with_args
  - drivers/pinctrl/devicetree.c:pinctrl_count_index_with_args
```
**Symbols:**

```
c00000000082c600-c00000000082c6c4: pinctrl_find_cells_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/devicetree.c (ffffffe00049c4be)
Location: drivers/pinctrl/devicetree.c:290
Inline: True
Direct callers:
  - drivers/pinctrl/devicetree.c:pinctrl_parse_index_with_args
  - drivers/pinctrl/devicetree.c:pinctrl_count_index_with_args
```
**Symbols:**

```
ffffffe00049c4be-ffffffe00049c524: pinctrl_find_cells_size.isra.0 (STB_LOCAL)
```
</details>
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
