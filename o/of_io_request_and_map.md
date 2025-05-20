# Function: <code>of_io_request_and_map</code>

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
void *of_io_request_and_map(struct device_node *np, int index, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffff800010b73dd0)
Location: drivers/of/address.c:880
Inline: False
Direct callers:
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_irq_init
  - drivers/irqchip/irq-mvebu-odmi.c:mvebu_odmi_init
  - drivers/clk/sunxi/clk-a10-codec.c:sun4i_codec_clk_setup
  - drivers/clk/sunxi/clk-a10-mod1.c:sun4i_mod1_clk_setup
  - drivers/clk/sunxi/clk-a10-pll2.c:sun4i_pll2_setup
  - drivers/clk/sunxi/clk-a10-ve.c:sun4i_ve_clk_setup
  - drivers/clk/sunxi/clk-mod0.c:sunxi_mmc_setup
  - drivers/clk/sunxi/clk-mod0.c:sun9i_a80_mod0_setup
  - drivers/clk/sunxi/clk-simple-gates.c:sunxi_simple_gates_setup
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_init
  - drivers/clk/sunxi/clk-sun4i-pll3.c:sun4i_a10_pll3_setup
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_setup
  - drivers/clk/sunxi/clk-sun8i-bus-gates.c:sun8i_h3_bus_gates_init
  - drivers/clk/sunxi/clk-sun8i-mbus.c:sun8i_a23_mbus_setup
  - drivers/clk/sunxi/clk-sun9i-core.c:sun9i_a80_apb1_setup
  - drivers/clk/sunxi/clk-sun9i-core.c:sun9i_a80_apb0_setup
  - drivers/clk/sunxi/clk-sun9i-core.c:sun9i_a80_ahb_setup
  - drivers/clk/sunxi/clk-sun9i-core.c:sun9i_a80_gt_setup
  - drivers/clk/sunxi/clk-sun9i-core.c:sun9i_a80_pll4_setup
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_clk_setup
  - drivers/clk/sunxi/clk-sun8i-apb0.c:sun8i_a23_apb0_of_clk_init_driver
  - drivers/clk/sunxi/clk-sun9i-cpus.c:sun9i_a80_cpus_setup
  - drivers/clk/sunxi-ng/ccu-sun50i-h6-r.c:sun50i_h6_r_ccu_setup
  - drivers/clk/sunxi-ng/ccu-sun8i-h3.c:sunxi_h3_h5_ccu_init
  - drivers/clk/sunxi-ng/ccu-sun8i-r.c:sunxi_r_ccu_init
  - drivers/soc/actions/owl-sps.c:owl_sps_probe
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_clk_init
  - drivers/clocksource/timer-of.c:timer_of_init
  - drivers/clocksource/timer-owl.c:owl_timer_init
```
**Symbols:**

```
ffff800010b73dd0-ffff800010b73f54: of_io_request_and_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *of_io_request_and_map(struct device_node *np, int index, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c0c56540)
Location: drivers/of/address.c:880
Inline: False
Direct callers:
  - arch/arm/mach-mvebu/platsmp.c:mv98dx3236_boot_secondary
  - drivers/irqchip/irq-rda-intc.c:rda8810_intc_init
  - drivers/irqchip/irq-vf610-mscm-ir.c:vf610_mscm_ir_of_init
  - drivers/soc/actions/owl-sps.c:owl_sps_probe
  - drivers/clocksource/timer-of.c:timer_of_init
  - drivers/clocksource/timer-meson6.c:meson6_timer_init
  - drivers/clocksource/timer-owl.c:owl_timer_init
```
**Symbols:**

```
c0c56540-c0c56620: of_io_request_and_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *of_io_request_and_map(struct device_node *np, int index, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c000000000c50760)
Location: drivers/of/address.c:880
Inline: False
```
**Symbols:**

```
c000000000c50760-c000000000c508b4: of_io_request_and_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *of_io_request_and_map(struct device_node *np, int index, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffffffe000727800)
Location: drivers/of/address.c:880
Inline: False
Direct callers:
  - drivers/clocksource/timer-of.c:timer_of_init
```
**Symbols:**

```
ffffffe000727800-ffffffe0007278b2: of_io_request_and_map (STB_GLOBAL)
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
