# Function: <code>pinconf_generic_dt_node_to_map_all</code>

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
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pinconf_generic_dt_node_to_map_all(struct pinctrl_dev *pctldev, struct device_node *np_config, struct pinctrl_map **map, unsigned int *num_maps);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-bm1880.c (ffff800010694da8)
Location: include/linux/pinctrl/pinconf-generic.h:210
Inline: False
```
```
In drivers/pinctrl/meson/pinctrl-meson.c (ffff800010695780)
Location: include/linux/pinctrl/pinconf-generic.h:210
Inline: False
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (ffff8000106a04d0)
Location: include/linux/pinctrl/pinconf-generic.h:210
Inline: False
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (ffff8000106a2df0)
Location: include/linux/pinctrl/pinconf-generic.h:210
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pctl_dt_node_to_map
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (ffff8000106ba3e0)
Location: include/linux/pinctrl/pinconf-generic.h:210
Inline: False
```
**Symbols:**

```
ffff800010694da8-ffff800010694dc0: pinconf_generic_dt_node_to_map_all (STB_LOCAL)
ffff800010695780-ffff800010695798: pinconf_generic_dt_node_to_map_all (STB_LOCAL)
ffff8000106a04d0-ffff8000106a04e8: pinconf_generic_dt_node_to_map_all (STB_LOCAL)
ffff8000106ba3e0-ffff8000106ba3f8: pinconf_generic_dt_node_to_map_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate ⚠️</summary>

```c
int pinconf_generic_dt_node_to_map_all(struct pinctrl_dev *pctldev, struct device_node *np_config, struct pinctrl_map **map, unsigned int *num_maps);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/meson/pinctrl-meson.c (c0835d4c)
Location: include/linux/pinctrl/pinconf-generic.h:210
Inline: False
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (c0845af8)
Location: include/linux/pinctrl/pinconf-generic.h:210
Inline: False
```
```
In drivers/pinctrl/aspeed/pinctrl-aspeed-g6.c (c08478e8)
Location: include/linux/pinctrl/pinconf-generic.h:210
Inline: False
```
```
In drivers/pinctrl/uniphier/pinctrl-uniphier-core.c (c0857a14)
Location: include/linux/pinctrl/pinconf-generic.h:210
Inline: False
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (c085b0ec)
Location: include/linux/pinctrl/pinconf-generic.h:210
Inline: False
```
**Symbols:**

```
c0835d4c-c0835d70: pinconf_generic_dt_node_to_map_all (STB_LOCAL)
c0845af8-c0845b1c: pinconf_generic_dt_node_to_map_all (STB_LOCAL)
c08478e8-c084790c: pinconf_generic_dt_node_to_map_all (STB_LOCAL)
c0857a14-c0857a38: pinconf_generic_dt_node_to_map_all (STB_LOCAL)
c085b0ec-c085b110: pinconf_generic_dt_node_to_map_all (STB_LOCAL)
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
