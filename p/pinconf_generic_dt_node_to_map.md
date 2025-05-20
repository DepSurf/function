# Function: <code>pinconf_generic_dt_node_to_map</code>

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
int pinconf_generic_dt_node_to_map(struct pinctrl_dev *pctldev, struct device_node *np_config, struct pinctrl_map **map, unsigned int *num_maps, enum pinctrl_map_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf-generic.c (ffff800010691b48)
Location: drivers/pinctrl/pinconf-generic.c:374
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:pinconf_generic_dt_node_to_map_pin
  - drivers/pinctrl/pinctrl-amd.c:pinconf_generic_dt_node_to_map_group
  - drivers/pinctrl/pinctrl-bm1880.c:pinconf_generic_dt_node_to_map_all
  - drivers/pinctrl/meson/pinctrl-meson.c:pinconf_generic_dt_node_to_map_all
  - drivers/pinctrl/pinctrl-palmas.c:pinconf_generic_dt_node_to_map_pin
  - drivers/pinctrl/pinctrl-sx150x.c:pinconf_generic_dt_node_to_map_pin
  - drivers/pinctrl/pinctrl-ocelot.c:pinconf_generic_dt_node_to_map_pin
  - drivers/pinctrl/actions/pinctrl-owl.c:pinconf_generic_dt_node_to_map_all
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pctl_dt_node_to_map
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:pinconf_generic_dt_node_to_map_pin
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:pinconf_generic_dt_node_to_map_pin
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:pinconf_generic_dt_node_to_map_group
  - drivers/pinctrl/qcom/pinctrl-msm.c:pinconf_generic_dt_node_to_map_group
  - drivers/pinctrl/mediatek/pinctrl-moore.c:pinconf_generic_dt_node_to_map_all
```
**Symbols:**

```
ffff800010691b48-ffff800010691c58: pinconf_generic_dt_node_to_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pinconf_generic_dt_node_to_map(struct pinctrl_dev *pctldev, struct device_node *np_config, struct pinctrl_map **map, unsigned int *num_maps, enum pinctrl_map_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf-generic.c (c08336c4)
Location: drivers/pinctrl/pinconf-generic.c:374
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:pinconf_generic_dt_node_to_map_pin
  - drivers/pinctrl/pinctrl-amd.c:pinconf_generic_dt_node_to_map_group
  - drivers/pinctrl/meson/pinctrl-meson.c:pinconf_generic_dt_node_to_map_all
  - drivers/pinctrl/pinctrl-palmas.c:pinconf_generic_dt_node_to_map_pin
  - drivers/pinctrl/pinctrl-sx150x.c:pinconf_generic_dt_node_to_map_pin
  - drivers/pinctrl/pinctrl-ocelot.c:pinconf_generic_dt_node_to_map_pin
  - drivers/pinctrl/actions/pinctrl-owl.c:pinconf_generic_dt_node_to_map_all
  - drivers/pinctrl/aspeed/pinctrl-aspeed-g6.c:pinconf_generic_dt_node_to_map_all
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_dt_node_to_map
  - drivers/pinctrl/qcom/pinctrl-msm.c:pinconf_generic_dt_node_to_map_group
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:pinconf_generic_dt_node_to_map_all
  - drivers/pinctrl/mediatek/pinctrl-moore.c:pinconf_generic_dt_node_to_map_all
  - drivers/soc/tegra/pmc.c:pinconf_generic_dt_node_to_map_pin
  - drivers/rtc/rtc-omap.c:pinconf_generic_dt_node_to_map_pin
```
**Symbols:**

```
c08336c4-c08337a8: pinconf_generic_dt_node_to_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pinconf_generic_dt_node_to_map(struct pinctrl_dev *pctldev, struct device_node *np_config, struct pinctrl_map **map, unsigned int *num_maps, enum pinctrl_map_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf-generic.c (c00000000082de50)
Location: drivers/pinctrl/pinconf-generic.c:374
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:pinconf_generic_dt_node_to_map_pin
  - drivers/pinctrl/pinctrl-amd.c:pinconf_generic_dt_node_to_map_group
  - drivers/pinctrl/pinctrl-palmas.c:pinconf_generic_dt_node_to_map_pin
  - drivers/pinctrl/pinctrl-sx150x.c:pinconf_generic_dt_node_to_map_pin
  - drivers/pinctrl/pinctrl-ocelot.c:pinconf_generic_dt_node_to_map_pin
```
**Symbols:**

```
c00000000082de50-c00000000082dfb0: pinconf_generic_dt_node_to_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pinconf_generic_dt_node_to_map(struct pinctrl_dev *pctldev, struct device_node *np_config, struct pinctrl_map **map, unsigned int *num_maps, enum pinctrl_map_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf-generic.c (ffffffe00049d20c)
Location: drivers/pinctrl/pinconf-generic.c:374
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:pinconf_generic_dt_node_to_map_pin
  - drivers/pinctrl/pinctrl-amd.c:pinconf_generic_dt_node_to_map_group
  - drivers/pinctrl/pinctrl-palmas.c:pinconf_generic_dt_node_to_map_pin
  - drivers/pinctrl/pinctrl-sx150x.c:pinconf_generic_dt_node_to_map_pin
  - drivers/pinctrl/pinctrl-ocelot.c:pinconf_generic_dt_node_to_map_pin
```
**Symbols:**

```
ffffffe00049d20c-ffffffe00049d2c2: pinconf_generic_dt_node_to_map (STB_GLOBAL)
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
