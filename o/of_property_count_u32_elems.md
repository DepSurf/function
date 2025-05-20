# Function: <code>of_property_count_u32_elems</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/of.h:1079
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/of.h:1079
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/of.h:1079
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
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/of.h:1079
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
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/of.h:1087
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
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/of.h:1104
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
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/of.h:1125
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
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/of.h:1130
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
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/of.h:1063
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
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/of.h:1062
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
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/of.h:1120
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
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/of.h:1119
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-mvebu-gicp.c (ffff800010678c28)
Location: include/linux/of.h:1079
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-gicp.c:mvebu_gicp_probe
```
```
In drivers/gpio/gpiolib-of.c (ffff8000106c867c)
Location: include/linux/of.h:1079
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/gpio/gpiolib-of.c:of_gpio_need_valid_mask
```
```
In drivers/clk/sunxi/clk-simple-gates.c (ffff80001148ce30)
Location: include/linux/of.h:1079
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-simple-gates.c:sunxi_simple_gates_setup
```
```
In drivers/clk/sunxi/clk-sun8i-bus-gates.c (ffff80001148d934)
Location: include/linux/of.h:1079
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun8i-bus-gates.c:sun8i_h3_bus_gates_init
```
```
In drivers/soc/qcom/rpmh-rsc.c (ffff80001081b370)
Location: include/linux/of.h:1079
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_probe
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acb390)
Location: include/linux/of.h:1079
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
```
In drivers/opp/of.c (ffff800010b1b7d4)
Location: include/linux/of.h:1079
Inline: True
```
```
In drivers/of/of_numa.c (ffff8000114acb74)
Location: include/linux/of.h:1079
Inline: True
Inline callers:
  - drivers/of/of_numa.c:of_numa_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-rzn1.c (c083dd10)
Location: include/linux/of.h:1079
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_count_function_groups
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_count_function_groups
```
```
In drivers/gpio/gpiolib-of.c (c0865ca8)
Location: include/linux/of.h:1079
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/gpio/gpiolib-of.c:of_gpio_need_valid_mask
```
```
In drivers/regulator/ti-abb-regulator.c (c0955aac)
Location: include/linux/of.h:1079
Inline: True
Inline callers:
  - drivers/regulator/ti-abb-regulator.c:ti_abb_init_table
```
```
In drivers/power/supply/power_supply_core.c (c0bac204)
Location: include/linux/of.h:1079
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
```
In drivers/opp/of.c (c0bf6078)
Location: include/linux/of.h:1079
Inline: True
Inline callers:
  - drivers/opp/of.c:opp_parse_supplies
  - drivers/opp/of.c:opp_parse_supplies
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/platforms/powernv/idle.c (c0000000000c8880)
Location: include/linux/of.h:1079
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/idle.c:pnv_parse_cpuidle_dt
```
```
In arch/powerpc/platforms/powernv/opal-irqchip.c (c00000000135db30)
Location: include/linux/of.h:1079
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_init
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d4d28)
Location: include/linux/of.h:1079
Inline: True
```
```
In arch/powerpc/platforms/powernv/opal-imc.c (c0000000000e01d0)
Location: include/linux/of.h:1079
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-imc.c:opal_imc_counters_probe
```
```
In drivers/gpio/gpiolib-of.c (c000000000845ed0)
Location: include/linux/of.h:1079
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/gpio/gpiolib-of.c:of_gpio_need_valid_mask
```
```
In drivers/power/supply/power_supply_core.c (c000000000bad51c)
Location: include/linux/of.h:1079
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
```
In drivers/opp/of.c (c000000000c0db24)
Location: include/linux/of.h:1079
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (ffffffe0004abe92)
Location: include/linux/of.h:1079
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/gpio/gpiolib-of.c:of_gpio_need_valid_mask
```
```
In drivers/power/supply/power_supply_core.c (ffffffe0006c8bf6)
Location: include/linux/of.h:1079
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
```
In drivers/opp/of.c (ffffffe000703a7a)
Location: include/linux/of.h:1079
Inline: True
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
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/of.h:1079
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
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/of.h:1079
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
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/of.h:1079
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
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/of.h:1079
Inline: True
```
</details>
</li>
</ul>

## Differences
