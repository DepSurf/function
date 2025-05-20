# Function: <code>pinconf_generic_dt_node_to_map_pin</code>

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
int pinconf_generic_dt_node_to_map_pin(struct pinctrl_dev *pctldev, struct device_node *np_config, struct pinctrl_map **map, unsigned int *num_maps);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-as3722.c (ffff8000106925f8)
Location: include/linux/pinctrl/pinconf-generic.h:202
Inline: False
```
```
In drivers/pinctrl/pinctrl-palmas.c (ffff800010697088)
Location: include/linux/pinctrl/pinconf-generic.h:202
Inline: False
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffff80001069e538)
Location: include/linux/pinctrl/pinconf-generic.h:202
Inline: False
```
```
In drivers/pinctrl/pinctrl-ocelot.c (ffff80001069f898)
Location: include/linux/pinctrl/pinconf-generic.h:202
Inline: False
```
```
In drivers/pinctrl/bcm/pinctrl-iproc-gpio.c (ffff8000106a4958)
Location: include/linux/pinctrl/pinconf-generic.h:202
Inline: False
```
```
In drivers/pinctrl/bcm/pinctrl-ns2-mux.c (ffff8000106a6520)
Location: include/linux/pinctrl/pinconf-generic.h:202
Inline: False
```
**Symbols:**

```
ffff8000106925f8-ffff800010692610: pinconf_generic_dt_node_to_map_pin (STB_LOCAL)
ffff800010697088-ffff8000106970a0: pinconf_generic_dt_node_to_map_pin (STB_LOCAL)
ffff80001069e538-ffff80001069e550: pinconf_generic_dt_node_to_map_pin (STB_LOCAL)
ffff80001069f898-ffff80001069f8b0: pinconf_generic_dt_node_to_map_pin (STB_LOCAL)
ffff8000106a4958-ffff8000106a4970: pinconf_generic_dt_node_to_map_pin (STB_LOCAL)
ffff8000106a6520-ffff8000106a6538: pinconf_generic_dt_node_to_map_pin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate ⚠️</summary>

```c
int pinconf_generic_dt_node_to_map_pin(struct pinctrl_dev *pctldev, struct device_node *np_config, struct pinctrl_map **map, unsigned int *num_maps);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-as3722.c (c083401c)
Location: include/linux/pinctrl/pinconf-generic.h:202
Inline: False
```
```
In drivers/pinctrl/pinctrl-palmas.c (c0837354)
Location: include/linux/pinctrl/pinconf-generic.h:202
Inline: False
```
```
In drivers/pinctrl/pinctrl-sx150x.c (c08417b0)
Location: include/linux/pinctrl/pinconf-generic.h:202
Inline: False
```
```
In drivers/pinctrl/pinctrl-ocelot.c (c08444c8)
Location: include/linux/pinctrl/pinconf-generic.h:202
Inline: False
```
```
In drivers/soc/tegra/pmc.c (c093b3b8)
Location: include/linux/pinctrl/pinconf-generic.h:202
Inline: False
```
```
In drivers/rtc/rtc-omap.c (c0b8c600)
Location: include/linux/pinctrl/pinconf-generic.h:202
Inline: False
```
**Symbols:**

```
c083401c-c0834040: pinconf_generic_dt_node_to_map_pin (STB_LOCAL)
c0837354-c0837378: pinconf_generic_dt_node_to_map_pin (STB_LOCAL)
c08417b0-c08417d4: pinconf_generic_dt_node_to_map_pin (STB_LOCAL)
c08444c8-c08444ec: pinconf_generic_dt_node_to_map_pin (STB_LOCAL)
c093b3b8-c093b3dc: pinconf_generic_dt_node_to_map_pin (STB_LOCAL)
c0b8c600-c0b8c624: pinconf_generic_dt_node_to_map_pin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate ⚠️</summary>

```c
int pinconf_generic_dt_node_to_map_pin(struct pinctrl_dev *pctldev, struct device_node *np_config, struct pinctrl_map **map, unsigned int *num_maps);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-as3722.c (c00000000082ecc0)
Location: include/linux/pinctrl/pinconf-generic.h:202
Inline: False
```
```
In drivers/pinctrl/pinctrl-palmas.c (c000000000832210)
Location: include/linux/pinctrl/pinconf-generic.h:202
Inline: False
```
```
In drivers/pinctrl/pinctrl-sx150x.c (c000000000837170)
Location: include/linux/pinctrl/pinconf-generic.h:202
Inline: False
```
```
In drivers/pinctrl/pinctrl-ocelot.c (c000000000837f80)
Location: include/linux/pinctrl/pinconf-generic.h:202
Inline: False
```
**Symbols:**

```
c00000000082ecc0-c00000000082ecf0: pinconf_generic_dt_node_to_map_pin (STB_LOCAL)
c000000000832210-c000000000832240: pinconf_generic_dt_node_to_map_pin (STB_LOCAL)
c000000000837170-c0000000008371a0: pinconf_generic_dt_node_to_map_pin (STB_LOCAL)
c000000000837f80-c000000000837fb0: pinconf_generic_dt_node_to_map_pin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate ⚠️</summary>

```c
int pinconf_generic_dt_node_to_map_pin(struct pinctrl_dev *pctldev, struct device_node *np_config, struct pinctrl_map **map, unsigned int *num_maps);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-as3722.c (ffffffe00049db16)
Location: include/linux/pinctrl/pinconf-generic.h:202
Inline: False
```
```
In drivers/pinctrl/pinctrl-palmas.c (ffffffe00049fa34)
Location: include/linux/pinctrl/pinconf-generic.h:202
Inline: False
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffe0004a2bf2)
Location: include/linux/pinctrl/pinconf-generic.h:202
Inline: False
```
```
In drivers/pinctrl/pinctrl-ocelot.c (ffffffe0004a355e)
Location: include/linux/pinctrl/pinconf-generic.h:202
Inline: False
```
**Symbols:**

```
ffffffe00049db16-ffffffe00049db30: pinconf_generic_dt_node_to_map_pin (STB_LOCAL)
ffffffe00049fa34-ffffffe00049fa4e: pinconf_generic_dt_node_to_map_pin (STB_LOCAL)
ffffffe0004a2bf2-ffffffe0004a2c0c: pinconf_generic_dt_node_to_map_pin (STB_LOCAL)
ffffffe0004a355e-ffffffe0004a3578: pinconf_generic_dt_node_to_map_pin (STB_LOCAL)
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
