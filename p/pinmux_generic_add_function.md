# Function: <code>pinmux_generic_add_function</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int pinmux_generic_add_function(struct pinctrl_dev *pctldev, const char *name, const char **groups, const unsigned int num_groups, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffff80001068f368)
Location: drivers/pinctrl/pinmux.c:771
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_bits_in_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
```
**Symbols:**

```
ffff80001068f368-ffff80001068f430: pinmux_generic_add_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pinmux_generic_add_function(struct pinctrl_dev *pctldev, const char *name, const char **groups, const unsigned int num_groups, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (c08311fc)
Location: drivers/pinctrl/pinmux.c:771
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-rza1.c:rza1_dt_node_to_map
  - drivers/pinctrl/pinctrl-rza2.c:rza2_dt_node_to_map
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
```
**Symbols:**

```
c08311fc-c0831294: pinmux_generic_add_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pinmux_generic_add_function(struct pinctrl_dev *pctldev, const char *name, const char **groups, const unsigned int num_groups, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (c00000000082a790)
Location: drivers/pinctrl/pinmux.c:771
Inline: True
```
**Symbols:**

```
c00000000082a790-c00000000082a880: pinmux_generic_add_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pinmux_generic_add_function(struct pinctrl_dev *pctldev, const char *name, const char **groups, const unsigned int num_groups, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffe00049b170)
Location: drivers/pinctrl/pinmux.c:771
Inline: True
```
**Symbols:**

```
ffffffe00049b170-ffffffe00049b20e: pinmux_generic_add_function (STB_GLOBAL)
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
