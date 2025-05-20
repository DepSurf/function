# Function: <code>of_prop_next_string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/of.h:637
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/of.h:682
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/of.h:802
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/of.h:828
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/of.h:881
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/of.h:899
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/of.h:930
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/of.h:930
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/of.h:930
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/of.h:938
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/of.h:950
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/of.h:965
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/of.h:970
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/of.h:792
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/of.h:790
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/of.h:823
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/of.h:822
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
const char *of_prop_next_string(struct property *prop, const char *cur);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffff800010b6ec68)
Location: drivers/of/property.c:506
Inline: False
Direct callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_subnode_to_map
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_subnode_to_map
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_dt_node_to_map
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_dt_node_to_map
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_dt_node_to_map
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_dt_node_to_map
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pctrl_dt_node_to_map
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pctrl_dt_node_to_map
  - drivers/of/base.c:__of_device_is_compatible
  - drivers/of/base.c:__of_device_is_compatible
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_get_modalias
  - drivers/of/device.c:of_device_get_modalias
  - drivers/of/device.c:of_device_get_modalias
  - drivers/of/of_mdio.c:of_get_phy_id
  - drivers/of/of_mdio.c:of_get_phy_id
  - drivers/mailbox/mailbox.c:mbox_request_channel_byname
  - drivers/mailbox/mailbox.c:mbox_request_channel_byname
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
```
**Symbols:**

```
ffff800010b6ec68-ffff800010b6ecd4: of_prop_next_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *of_prop_next_string(struct property *prop, const char *cur);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c0c51a54)
Location: drivers/of/property.c:506
Inline: False
Direct callers:
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_parse_module_range
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_parse_module_range
  - arch/arm/mach-omap2/omap_device.c:omap_device_build
  - arch/arm/mach-omap2/omap_device.c:omap_device_build
  - drivers/bus/ti-sysc.c:sysc_get_clocks
  - drivers/bus/ti-sysc.c:sysc_get_clocks
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_subnode_to_map
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_subnode_to_map
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_dt_node_to_map
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_dt_node_to_map
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_dt_node_to_map
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_dt_node_to_map
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_dt_node_to_map
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_dt_node_to_map
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_dt_node_to_map
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_dt_node_to_map
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map
  - drivers/mtd/mtdpart.c:parse_mtd_partitions
  - drivers/mtd/mtdpart.c:parse_mtd_partitions
  - drivers/of/base.c:__of_device_is_compatible
  - drivers/of/base.c:__of_device_is_compatible
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_get_modalias
  - drivers/of/device.c:of_device_get_modalias
  - drivers/of/of_mdio.c:of_get_phy_id
  - drivers/of/of_mdio.c:of_get_phy_id
  - drivers/mailbox/mailbox.c:mbox_request_channel_byname
  - drivers/mailbox/mailbox.c:mbox_request_channel_byname
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
```
**Symbols:**

```
c0c51a54-c0c51ab4: of_prop_next_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *of_prop_next_string(struct property *prop, const char *cur);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c000000000c49bd0)
Location: drivers/of/property.c:506
Inline: False
Direct callers:
  - arch/powerpc/kernel/mce.c:init_debug_trig_function
  - arch/powerpc/kernel/mce.c:init_debug_trig_function
  - arch/powerpc/kernel/mce.c:init_debug_trig_function
  - arch/powerpc/platforms/pseries/of_helpers.c:of_read_drc_info_cell
  - arch/powerpc/platforms/pseries/of_helpers.c:of_read_drc_info_cell
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_subnode_to_map
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_subnode_to_map
  - drivers/of/base.c:__of_device_is_compatible
  - drivers/of/base.c:__of_device_is_compatible
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_get_modalias
  - drivers/of/device.c:of_device_get_modalias
  - drivers/of/device.c:of_device_get_modalias
  - drivers/of/of_mdio.c:of_get_phy_id
  - drivers/of/of_mdio.c:of_get_phy_id
  - drivers/mailbox/mailbox.c:mbox_request_channel_byname
  - drivers/mailbox/mailbox.c:mbox_request_channel_byname
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
```
**Symbols:**

```
c000000000c49bd0-c000000000c49c78: of_prop_next_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *of_prop_next_string(struct property *prop, const char *cur);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffffffe0007232b2)
Location: drivers/of/property.c:506
Inline: False
Direct callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_subnode_to_map
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_subnode_to_map
  - drivers/of/base.c:__of_device_is_compatible
  - drivers/of/base.c:__of_device_is_compatible
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_get_modalias
  - drivers/of/device.c:of_device_get_modalias
  - drivers/of/device.c:of_device_get_modalias
  - drivers/of/of_mdio.c:of_get_phy_id
  - drivers/of/of_mdio.c:of_get_phy_id
  - drivers/mailbox/mailbox.c:mbox_request_channel_byname
  - drivers/mailbox/mailbox.c:mbox_request_channel_byname
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
```
**Symbols:**

```
ffffffe0007232b2-ffffffe000723314: of_prop_next_string (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/of.h:930
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/of.h:930
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/of.h:930
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/of.h:930
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
