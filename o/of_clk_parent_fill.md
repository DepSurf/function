# Function: <code>of_clk_parent_fill</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:849
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
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:861
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
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:871
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
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:888
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
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:945
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
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:981
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
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:1098
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
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:1100
Inline: True
```
</details>
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
int of_clk_parent_fill(struct device_node *np, const char **parents, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107bf080)
Location: drivers/clk/clk.c:4728
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clk_probe
  - drivers/clk/sunxi/clk-a10-mod1.c:sun4i_mod1_clk_setup
  - drivers/clk/sunxi/clk-a20-gmac.c:sun7i_a20_gmac_clk_setup
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_init
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_setup
  - drivers/clk/sunxi/clk-sun8i-mbus.c:sun8i_a23_mbus_setup
  - drivers/clk/sunxi/clk-sun9i-cpus.c:sun9i_a80_cpus_setup
  - drivers/clk/versatile/clk-sp810.c:clk_sp810_of_setup
```
**Symbols:**

```
ffff8000107bf080-ffff8000107bf118: of_clk_parent_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_clk_parent_fill(struct device_node *np, const char **parents, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08eb6ac)
Location: drivers/clk/clk.c:4728
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/clk/ti/dpll.c:of_ti_dpll_setup
  - drivers/clk/ti/composite.c:ti_clk_add_component
  - drivers/clk/ti/mux.c:of_mux_clk_setup
  - drivers/clk/ti/apll.c:of_dra7_apll_setup
  - drivers/clk/ti/fapll.c:ti_fapll_setup
  - drivers/clk/ti/adpll.c:ti_adpll_probe
  - drivers/clk/versatile/clk-sp810.c:clk_sp810_of_setup
  - drivers/net/ethernet/ti/cpts.c:cpts_create
```
**Symbols:**

```
c08eb6ac-c08eb714: of_clk_parent_fill (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_clk_parent_fill(struct device_node *np, const char **parents, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050e36e)
Location: drivers/clk/clk.c:4728
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffe00050e36e-ffffffe00050e3d2: of_clk_parent_fill (STB_GLOBAL)
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
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:1100
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
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:1100
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
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:1100
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
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:1100
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
