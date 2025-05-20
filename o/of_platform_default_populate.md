# Function: <code>of_platform_default_populate</code>

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
int of_platform_default_populate(struct device_node *root, const struct of_dev_auxdata *lookup, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (ffff8000114aa404)
Location: drivers/of/platform.c:497
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_default_populate_init
Direct callers:
  - drivers/bus/imx-weim.c:weim_parse_dt
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
```
**Symbols:**

```
ffff800010b6df28-ffff800010b6df78: of_platform_default_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int of_platform_default_populate(struct device_node *root, const struct of_dev_auxdata *lookup, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (c15ae924)
Location: drivers/of/platform.c:497
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_default_populate_init
Direct callers:
  - arch/arm/mach-imx/mach-imx6q.c:imx6q_init_machine
  - arch/arm/mach-imx/mach-imx6sl.c:imx6sl_init_machine
  - arch/arm/mach-imx/mach-imx6sx.c:imx6sx_init_machine
  - arch/arm/mach-imx/mach-imx6ul.c:imx6ul_init_machine
  - arch/arm/mach-imx/mach-imx7ulp.c:imx7ulp_init_machine
  - arch/arm/mach-tegra/tegra.c:tegra_dt_init
  - drivers/bus/imx-weim.c:weim_parse_dt
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/uniphier-system-bus.c:uniphier_system_bus_probe
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe
  - drivers/memory/omap-gpmc.c:gpmc_probe_generic_child
```
**Symbols:**

```
c0c50dc4-c0c50df0: of_platform_default_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_platform_default_populate(struct device_node *root, const struct of_dev_auxdata *lookup, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (c000000000c48780)
Location: drivers/of/platform.c:497
Inline: False
```
**Symbols:**

```
c000000000c48780-c000000000c487a8: of_platform_default_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int of_platform_default_populate(struct device_node *root, const struct of_dev_auxdata *lookup, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (ffffffe00003a7da)
Location: drivers/of/platform.c:497
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_default_populate_init
```
**Symbols:**

```
ffffffe0007228e0-ffffffe000722922: of_platform_default_populate (STB_GLOBAL)
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
