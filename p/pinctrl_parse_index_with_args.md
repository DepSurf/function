# Function: <code>pinctrl_parse_index_with_args</code>

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
int pinctrl_parse_index_with_args(const struct device_node *np, const char *list_name, int index, struct of_phandle_args *out_args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/devicetree.c (ffff800010690b80)
Location: drivers/pinctrl/devicetree.c:409
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_bits_in_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
```
**Symbols:**

```
ffff800010690b80-ffff800010690ca0: pinctrl_parse_index_with_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pinctrl_parse_index_with_args(const struct device_node *np, const char *list_name, int index, struct of_phandle_args *out_args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/devicetree.c (c08327a4)
Location: drivers/pinctrl/devicetree.c:409
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_dt_node_to_map
```
**Symbols:**

```
c08327a4-c08328a0: pinctrl_parse_index_with_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pinctrl_parse_index_with_args(const struct device_node *np, const char *list_name, int index, struct of_phandle_args *out_args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/devicetree.c (c00000000082c6d0)
Location: drivers/pinctrl/devicetree.c:409
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
```
**Symbols:**

```
c00000000082c6d0-c00000000082c858: pinctrl_parse_index_with_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pinctrl_parse_index_with_args(const struct device_node *np, const char *list_name, int index, struct of_phandle_args *out_args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/devicetree.c (ffffffe00049c524)
Location: drivers/pinctrl/devicetree.c:409
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
```
**Symbols:**

```
ffffffe00049c524-ffffffe00049c616: pinctrl_parse_index_with_args (STB_GLOBAL)
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
