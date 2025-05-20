# Function: <code>pinconf_generic_dt_node_to_map_group</code>

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
<summary>In <code>arm64</code>: Duplicate ⚠️</summary>

```c
int pinconf_generic_dt_node_to_map_group(struct pinctrl_dev *pctldev, struct device_node *np_config, struct pinctrl_map **map, unsigned int *num_maps);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffff800010692a90)
Location: include/linux/pinctrl/pinconf-generic.h:194
Inline: False
```
```
In drivers/pinctrl/mvebu/pinctrl-armada-37xx.c (ffff8000106abd98)
Location: include/linux/pinctrl/pinconf-generic.h:194
Inline: False
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106acef0)
Location: include/linux/pinctrl/pinconf-generic.h:194
Inline: False
```
**Symbols:**

```
ffff800010692a90-ffff800010692aa8: pinconf_generic_dt_node_to_map_group (STB_LOCAL)
ffff8000106abd98-ffff8000106abdb0: pinconf_generic_dt_node_to_map_group (STB_LOCAL)
ffff8000106acef0-ffff8000106acf08: pinconf_generic_dt_node_to_map_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate ⚠️</summary>

```c
int pinconf_generic_dt_node_to_map_group(struct pinctrl_dev *pctldev, struct device_node *np_config, struct pinctrl_map **map, unsigned int *num_maps);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (c08353e8)
Location: include/linux/pinctrl/pinconf-generic.h:194
Inline: False
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (c084ea50)
Location: include/linux/pinctrl/pinconf-generic.h:194
Inline: False
```
**Symbols:**

```
c08353e8-c083540c: pinconf_generic_dt_node_to_map_group (STB_LOCAL)
c084ea50-c084ea74: pinconf_generic_dt_node_to_map_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pinconf_generic_dt_node_to_map_group(struct pinctrl_dev *pctldev, struct device_node *np_config, struct pinctrl_map **map, unsigned int *num_maps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (c00000000082f2b0)
Location: include/linux/pinctrl/pinconf-generic.h:194
Inline: False
```
**Symbols:**

```
c00000000082f2b0-c00000000082f2e0: pinconf_generic_dt_node_to_map_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pinconf_generic_dt_node_to_map_group(struct pinctrl_dev *pctldev, struct device_node *np_config, struct pinctrl_map **map, unsigned int *num_maps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffe00049ecb6)
Location: include/linux/pinctrl/pinconf-generic.h:194
Inline: False
```
**Symbols:**

```
ffffffe00049ecb6-ffffffe00049ecd0: pinconf_generic_dt_node_to_map_group (STB_LOCAL)
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
