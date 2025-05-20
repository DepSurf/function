# Function: <code>pinconf_generic_dt_subnode_to_map</code>

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
int pinconf_generic_dt_subnode_to_map(struct pinctrl_dev *pctldev, struct device_node *np, struct pinctrl_map **map, unsigned int *reserved_maps, unsigned int *num_maps, enum pinctrl_map_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf-generic.c (ffff8000106918f8)
Location: drivers/pinctrl/pinconf-generic.c:290
Inline: False
Direct callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_node_to_map
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_node_to_map
```
**Symbols:**

```
ffff8000106918f8-ffff800010691b48: pinconf_generic_dt_subnode_to_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pinconf_generic_dt_subnode_to_map(struct pinctrl_dev *pctldev, struct device_node *np, struct pinctrl_map **map, unsigned int *reserved_maps, unsigned int *num_maps, enum pinctrl_map_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf-generic.c (c083343c)
Location: drivers/pinctrl/pinconf-generic.c:290
Inline: False
Direct callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_node_to_map
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_node_to_map
```
**Symbols:**

```
c083343c-c08336c4: pinconf_generic_dt_subnode_to_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pinconf_generic_dt_subnode_to_map(struct pinctrl_dev *pctldev, struct device_node *np, struct pinctrl_map **map, unsigned int *reserved_maps, unsigned int *num_maps, enum pinctrl_map_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf-generic.c (c00000000082db10)
Location: drivers/pinctrl/pinconf-generic.c:290
Inline: False
Direct callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_node_to_map
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_node_to_map
```
**Symbols:**

```
c00000000082db10-c00000000082de50: pinconf_generic_dt_subnode_to_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pinconf_generic_dt_subnode_to_map(struct pinctrl_dev *pctldev, struct device_node *np, struct pinctrl_map **map, unsigned int *reserved_maps, unsigned int *num_maps, enum pinctrl_map_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf-generic.c (ffffffe00049d010)
Location: drivers/pinctrl/pinconf-generic.c:290
Inline: False
Direct callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_node_to_map
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_node_to_map
```
**Symbols:**

```
ffffffe00049d010-ffffffe00049d20c: pinconf_generic_dt_subnode_to_map (STB_GLOBAL)
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
