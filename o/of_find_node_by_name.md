# Function: <code>of_find_node_by_name</code>

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
In drivers/mfd/twl4030-audio.c (0)
Location: include/linux/of.h:401
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
In drivers/mfd/twl4030-audio.c (0)
Location: include/linux/of.h:425
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
In drivers/mfd/twl4030-audio.c (0)
Location: include/linux/of.h:545
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
In drivers/mfd/twl4030-audio.c (0)
Location: include/linux/of.h:563
Inline: True
```
</details>
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
struct device_node *of_find_node_by_name(struct device_node *from, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b699a0)
Location: drivers/of/base.c:997
Inline: False
Direct callers:
  - drivers/thermal/of-thermal.c:of_parse_thermal_zones
  - drivers/thermal/of-thermal.c:thermal_zone_of_sensor_register
  - drivers/firmware/arm_sdei.c:sdei_init
```
**Symbols:**

```
ffff800010b699a0-ffff800010b69af4: of_find_node_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device_node *of_find_node_by_name(struct device_node *from, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4ce24)
Location: drivers/of/base.c:997
Inline: False
Direct callers:
  - arch/arm/mach-mvebu/pm-board.c:mvebu_armada_pm_init
  - arch/arm/mach-omap2/omap_hwmod_3xxx_data.c:omap3xxx_hwmod_init
  - drivers/clk/mvebu/common.c:kirkwood_fix_sscg_deviation
  - drivers/clk/ti/clk.c:ti_dt_clocks_register
  - drivers/clk/ti/clk-814x.c:dm814x_adpll_early_init
  - drivers/thermal/of-thermal.c:of_parse_thermal_zones
  - drivers/thermal/of-thermal.c:thermal_zone_of_sensor_register
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
```
**Symbols:**

```
c0c4ce24-c0c4cf00: of_find_node_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device_node *of_find_node_by_name(struct device_node *from, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c42310)
Location: drivers/of/base.c:997
Inline: False
Direct callers:
  - arch/powerpc/kernel/setup-common.c:check_legacy_ioport
  - arch/powerpc/kernel/rtas.c:rtas_initialize
  - arch/powerpc/kernel/rtas-proc.c:proc_rtas_init
  - arch/powerpc/platforms/powernv/setup.c:pnv_setup_arch
  - arch/powerpc/platforms/pseries/vio.c:vio_cmo_num_OF_devs
  - drivers/thermal/of-thermal.c:of_parse_thermal_zones
  - drivers/thermal/of-thermal.c:thermal_zone_of_sensor_register
```
**Symbols:**

```
c000000000c42310-c000000000c42464: of_find_node_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device_node *of_find_node_by_name(struct device_node *from, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe00071f0c0)
Location: drivers/of/base.c:997
Inline: False
Direct callers:
  - drivers/thermal/of-thermal.c:of_parse_thermal_zones
  - drivers/thermal/of-thermal.c:thermal_zone_of_sensor_register
```
**Symbols:**

```
ffffffe00071f0c0-ffffffe00071f184: of_find_node_by_name (STB_GLOBAL)
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
