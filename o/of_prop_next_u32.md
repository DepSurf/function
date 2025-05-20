# Function: <code>of_prop_next_u32</code>

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
const __be32 *of_prop_next_u32(struct property *prop, const __be32 *cur, u32 *pu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffff800010b6e520)
Location: drivers/of/property.c:483
Inline: False
Direct callers:
  - drivers/bus/imx-weim.c:weim_parse_dt
  - drivers/bus/imx-weim.c:weim_parse_dt
  - drivers/bus/imx-weim.c:weim_parse_dt
  - drivers/clk/clk.c:of_clk_detect_critical
  - drivers/clk/clk.c:of_clk_detect_critical
  - drivers/clk/clk.c:of_clk_get_parent_name
  - drivers/clk/clk.c:of_clk_get_parent_name
  - drivers/clk/sunxi/clk-simple-gates.c:sunxi_simple_gates_setup
  - drivers/clk/sunxi/clk-simple-gates.c:sunxi_simple_gates_setup
  - drivers/clk/sunxi/clk-sun8i-bus-gates.c:sun8i_h3_bus_gates_init
  - drivers/clk/sunxi/clk-sun8i-bus-gates.c:sun8i_h3_bus_gates_init
  - drivers/tty/sysrq.c:sysrq_toggle_support
  - drivers/tty/sysrq.c:sysrq_toggle_support
```
**Symbols:**

```
ffff800010b6e520-ffff800010b6e59c: of_prop_next_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const __be32 *of_prop_next_u32(struct property *prop, const __be32 *cur, u32 *pu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c0c51214)
Location: drivers/of/property.c:483
Inline: False
Direct callers:
  - drivers/bus/imx-weim.c:weim_parse_dt
  - drivers/bus/imx-weim.c:weim_parse_dt
  - drivers/bus/ti-sysc.c:sysc_init_idlemode
  - drivers/bus/ti-sysc.c:sysc_init_idlemode
  - drivers/clk/clk.c:of_clk_detect_critical
  - drivers/clk/clk.c:of_clk_detect_critical
  - drivers/clk/clk.c:of_clk_get_parent_name
  - drivers/clk/clk.c:of_clk_get_parent_name
  - drivers/tty/sysrq.c:sysrq_toggle_support
  - drivers/tty/sysrq.c:sysrq_toggle_support
```
**Symbols:**

```
c0c51214-c0c51270: of_prop_next_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const __be32 *of_prop_next_u32(struct property *prop, const __be32 *cur, u32 *pu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c000000000c48e10)
Location: drivers/of/property.c:483
Inline: False
Direct callers:
  - arch/powerpc/sysdev/xive/native.c:xive_native_init
  - arch/powerpc/sysdev/xive/native.c:xive_native_init
  - arch/powerpc/sysdev/xive/spapr.c:xive_spapr_init
  - arch/powerpc/sysdev/xive/spapr.c:xive_spapr_init
  - arch/powerpc/platforms/pseries/of_helpers.c:of_read_drc_info_cell
  - arch/powerpc/platforms/pseries/of_helpers.c:of_read_drc_info_cell
  - arch/powerpc/platforms/pseries/of_helpers.c:of_read_drc_info_cell
  - arch/powerpc/platforms/pseries/of_helpers.c:of_read_drc_info_cell
  - arch/powerpc/platforms/pseries/of_helpers.c:of_read_drc_info_cell
  - drivers/tty/sysrq.c:sysrq_toggle_support
  - drivers/tty/sysrq.c:sysrq_toggle_support
```
**Symbols:**

```
c000000000c48e10-c000000000c48e70: of_prop_next_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const __be32 *of_prop_next_u32(struct property *prop, const __be32 *cur, u32 *pu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffffffe000722cbc)
Location: drivers/of/property.c:483
Inline: False
Direct callers:
  - drivers/clk/clk.c:of_clk_detect_critical
  - drivers/clk/clk.c:of_clk_detect_critical
  - drivers/clk/clk.c:of_clk_get_parent_name
  - drivers/clk/clk.c:of_clk_get_parent_name
  - drivers/tty/sysrq.c:sysrq_toggle_support
  - drivers/tty/sysrq.c:sysrq_toggle_support
```
**Symbols:**

```
ffffffe000722cbc-ffffffe000722d3e: of_prop_next_u32 (STB_GLOBAL)
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
