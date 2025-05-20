# Function: <code>pinctrl_generic_add_group</code>

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
int pinctrl_generic_add_group(struct pinctrl_dev *pctldev, const char *name, int *pins, int num_pins, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffff80001068c9d8)
Location: drivers/pinctrl/core.c:625
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_bits_in_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
```
**Symbols:**

```
ffff80001068c9d8-ffff80001068cad4: pinctrl_generic_add_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_generic_add_group(struct pinctrl_dev *pctldev, const char *name, int *pins, int num_pins, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c082eabc)
Location: drivers/pinctrl/core.c:625
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-rza1.c:rza1_dt_node_to_map
  - drivers/pinctrl/pinctrl-rza2.c:rza2_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_dt_node_to_map
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
```
**Symbols:**

```
c082eabc-c082eb94: pinctrl_generic_add_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_generic_add_group(struct pinctrl_dev *pctldev, const char *name, int *pins, int num_pins, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c000000000825a60)
Location: drivers/pinctrl/core.c:625
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
```
**Symbols:**

```
c000000000825a60-c000000000825d74: pinctrl_generic_add_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_generic_add_group(struct pinctrl_dev *pctldev, const char *name, int *pins, int num_pins, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffe000498c84)
Location: drivers/pinctrl/core.c:625
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
```
**Symbols:**

```
ffffffe000498c84-ffffffe000498d4c: pinctrl_generic_add_group (STB_GLOBAL)
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
