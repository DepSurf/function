# Function: <code>of_node_full_name</code>

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
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:396
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:420
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:540
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:558
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:563
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fe50c)
Location: include/linux/of.h:566
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:566
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81109cdc)
Location: include/linux/of.h:585
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:585
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
In kernel/irq/irqdomain.c (ffffffff811133b4)
Location: include/linux/of.h:585
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:585
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111f54f)
Location: include/linux/of.h:585
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:585
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112ba8e)
Location: include/linux/of.h:587
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:587
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
In kernel/irq/irqdomain.c (ffffffff81be1c34)
Location: include/linux/of.h:589
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
  - kernel/irq/irqdomain.c:irq_domain_associate_many
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
In kernel/irq/irqdomain.c (ffffffff81bd3ceb)
Location: include/linux/of.h:604
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
  - kernel/irq/irqdomain.c:irq_domain_associate_many
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
In kernel/irq/irqdomain.c (ffffffff81cadcfb)
Location: include/linux/of.h:604
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81e5e1eb)
Location: include/linux/of.h:472
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
```
In drivers/opp/debugfs.c (ffffffff81b8c37b)
Location: include/linux/of.h:472
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811a07b1)
Location: include/linux/of.h:470
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
```
In drivers/opp/debugfs.c (ffffffff81d2bc82)
Location: include/linux/of.h:470
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b2623)
Location: include/linux/of.h:482
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
```
In drivers/misc/sram.c (0)
Location: include/linux/of.h:482
Inline: True
```
```
In drivers/opp/debugfs.c (ffffffff81d94f13)
Location: include/linux/of.h:482
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c2413)
Location: include/linux/of.h:481
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
```
In drivers/misc/sram.c (0)
Location: include/linux/of.h:481
Inline: True
```
```
In drivers/opp/debugfs.c (ffffffff81e4ca23)
Location: include/linux/of.h:481
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In kernel/irq/irqdomain.c (ffff800010184f60)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
```
In drivers/irqchip/irq-sunxi-nmi.c (ffff800011471234)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_irq_init
```
```
In drivers/pinctrl/sprd/pinctrl-sprd.c (ffff8000106b2d48)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_dt_node_to_map
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_dt_node_to_map
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_dt_node_to_map
```
```
In drivers/gpio/gpiolib-of.c (ffff8000106c7cd8)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
```
```
In drivers/video/fbdev/amba-clcd.c (ffff80001075c16c)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_probe
```
```
In drivers/clk/sunxi/clk-a10-codec.c (ffff80001148bdf8)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-a10-codec.c:sun4i_codec_clk_setup
```
```
In drivers/clk/sunxi/clk-a10-mod1.c (ffff80001148c058)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-a10-mod1.c:sun4i_mod1_clk_setup
```
```
In drivers/clk/sunxi/clk-a10-pll2.c (ffff80001148c204)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-a10-pll2.c:sun4i_pll2_setup
```
```
In drivers/clk/sunxi/clk-a10-ve.c (ffff80001148c5f4)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-a10-ve.c:sun4i_ve_clk_setup
```
```
In drivers/clk/sunxi/clk-mod0.c (ffff80001148ca98)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-mod0.c:sunxi_mmc_setup
  - drivers/clk/sunxi/clk-mod0.c:sun9i_a80_mod0_setup
```
```
In drivers/clk/sunxi/clk-simple-gates.c (ffff80001148cdd8)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-simple-gates.c:sunxi_simple_gates_setup
```
```
In drivers/clk/sunxi/clk-sun4i-display.c (ffff80001148d150)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_init
```
```
In drivers/clk/sunxi/clk-sun4i-pll3.c (ffff80001148d500)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun4i-pll3.c:sun4i_a10_pll3_setup
```
```
In drivers/clk/sunxi/clk-sun4i-tcon-ch1.c (ffff80001148d6e8)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_setup
```
```
In drivers/clk/sunxi/clk-sun8i-bus-gates.c (ffff80001148d8a0)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun8i-bus-gates.c:sun8i_h3_bus_gates_init
```
```
In drivers/clk/sunxi/clk-sun8i-mbus.c (ffff80001148dbb4)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun8i-mbus.c:sun8i_a23_mbus_setup
```
```
In drivers/clk/sunxi/clk-sun9i-core.c (ffff80001148df30)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-core.c:sun9i_a80_apb1_setup
  - drivers/clk/sunxi/clk-sun9i-core.c:sun9i_a80_apb0_setup
  - drivers/clk/sunxi/clk-sun9i-core.c:sun9i_a80_ahb_setup
  - drivers/clk/sunxi/clk-sun9i-core.c:sun9i_a80_gt_setup
  - drivers/clk/sunxi/clk-sun9i-core.c:sun9i_a80_pll4_setup
```
```
In drivers/clk/sunxi/clk-usb.c (ffff80001148e08c)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_clk_setup
```
```
In drivers/clk/sunxi/clk-sun8i-apb0.c (ffff80001148e4f8)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun8i-apb0.c:sun8i_a23_apb0_of_clk_init_driver
```
```
In drivers/clk/sunxi/clk-sun9i-cpus.c (ffff8000107f4050)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-cpus.c:sun9i_a80_cpus_setup
```
```
In drivers/clk/sunxi-ng/ccu-sun50i-h6-r.c (ffff80001148e6a0)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu-sun50i-h6-r.c:sun50i_h6_r_ccu_setup
```
```
In drivers/clk/sunxi-ng/ccu-sun8i-h3.c (ffff80001148e740)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu-sun8i-h3.c:sunxi_h3_h5_ccu_init
```
```
In drivers/clk/sunxi-ng/ccu-sun8i-r.c (ffff80001148e888)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu-sun8i-r.c:sunxi_r_ccu_init
```
```
In drivers/mfd/syscon.c (ffff80001094e8a0)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:of_syscon_register
```
```
In drivers/rtc/rtc-sun6i.c (ffff80001149e164)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_clk_init
```
```
In drivers/of/irq.c (ffff800010b751c0)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/of/irq.c:of_irq_to_resource
```
```
In drivers/mailbox/zynqmp-ipi-mailbox.c (ffff800010b7d314)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe
```
```
In lib/vsprintf.c (ffff800010d95804)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
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
In arch/arm/mach-mvebu/platsmp.c (c03319a4)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/platsmp.c:mv98dx3236_boot_secondary
```
```
In kernel/irq/irqdomain.c (c03d40e0)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
```
In drivers/gpio/gpiolib-of.c (c0865510)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
```
```
In drivers/video/fbdev/amba-clcd.c (c08df10c)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_probe
```
```
In drivers/mfd/syscon.c (c0a38724)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:of_syscon_register
```
```
In drivers/of/irq.c (c0c57678)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/of/irq.c:of_irq_to_resource
```
```
In lib/vsprintf.c (c0e92a3c)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
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
In kernel/irq/irqdomain.c (c0000000001df444)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
```
In drivers/gpio/gpiolib-of.c (c000000000844af0)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
```
```
In drivers/mfd/syscon.c (c0000000009fb1d8)
Location: include/linux/of.h:259
Inline: True
```
```
In drivers/of/irq.c (c000000000c52650)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/of/irq.c:of_irq_to_resource
```
```
In lib/vsprintf.c (c000000000edad30)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
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
In kernel/irq/irqdomain.c (ffffffe00011bc4e)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
```
In drivers/gpio/gpiolib-of.c (ffffffe0004ab5b4)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
```
```
In drivers/mfd/syscon.c (ffffffe0005bf634)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:of_syscon_register
```
```
In drivers/of/irq.c (ffffffe0007289fa)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - drivers/of/irq.c:of_irq_to_resource
```
```
In lib/vsprintf.c (ffffffe0008bf4f0)
Location: include/linux/of.h:259
Inline: True
Inline callers:
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81117b2f)
Location: include/linux/of.h:585
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:585
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8110881f)
Location: include/linux/of.h:585
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:585
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81115a1f)
Location: include/linux/of.h:585
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:585
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112104f)
Location: include/linux/of.h:585
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:585
Inline: True
```
</details>
</li>
</ul>

## Differences
