# Function: <code>irq_gc_unlock</code>

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
In kernel/irq/generic-chip.c (ffffffff810df082)
Location: include/linux/irq.h:910
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg_and_ack
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_set_wake
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
In kernel/irq/generic-chip.c (ffffffff810e5637)
Location: include/linux/irq.h:939
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg_and_ack
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
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
In kernel/irq/generic-chip.c (ffffffff810ebf47)
Location: include/linux/irq.h:964
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg_and_ack
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
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
In kernel/irq/generic-chip.c (ffffffff810eb7e2)
Location: include/linux/irq.h:1077
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg_and_ack
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
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
In kernel/irq/generic-chip.c (ffffffff810f3d52)
Location: include/linux/irq.h:1106
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
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
In kernel/irq/generic-chip.c (ffffffff810fc146)
Location: include/linux/irq.h:1108
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
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
In kernel/irq/generic-chip.c (ffffffff81107916)
Location: include/linux/irq.h:1110
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
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
In kernel/irq/generic-chip.c (ffffffff81110ed7)
Location: include/linux/irq.h:1123
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
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
In kernel/irq/generic-chip.c (ffffffff8111d137)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
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
In kernel/irq/generic-chip.c (ffffffff81129469)
Location: include/linux/irq.h:1171
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
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
In kernel/irq/generic-chip.c (ffffffff81124d39)
Location: include/linux/irq.h:1176
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
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
In kernel/irq/generic-chip.c (ffffffff81124cc9)
Location: include/linux/irq.h:1178
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
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
In kernel/irq/generic-chip.c (ffffffff81145369)
Location: include/linux/irq.h:1180
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
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
In kernel/irq/generic-chip.c (ffffffff81168998)
Location: include/linux/irq.h:1184
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
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
In kernel/irq/generic-chip.c (ffffffff8119d188)
Location: include/linux/irq.h:1201
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
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
In kernel/irq/generic-chip.c (ffffffff811af018)
Location: include/linux/irq.h:1214
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
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
In kernel/irq/generic-chip.c (ffffffff811bec18)
Location: include/linux/irq.h:1196
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
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
In kernel/irq/generic-chip.c (ffff800010181f54)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
```
```
In drivers/irqchip/irq-al-fic.c (ffff80001066a76c)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (ffff80001066b0fc)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_resume
```
```
In drivers/irqchip/irq-sunxi-nmi.c (ffff80001066b5ec)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_set_type
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_set_type
```
```
In drivers/irqchip/irq-brcmstb-l2.c (ffff8000106778dc)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_mask_and_ack
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff80001069b358)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
```
```
In drivers/gpio/gpio-mvebu.c (ffff8000106d16d4)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_level_irq_unmask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_level_irq_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_edge_irq_unmask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_edge_irq_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_ack
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
In kernel/irq/generic-chip.c (c03d17d0)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
```
```
In drivers/irqchip/irq-al-fic.c (c0812e68)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (c0814498)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_resume
```
```
In drivers/pinctrl/pinctrl-rockchip.c (c0838e88)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
```
```
In drivers/gpio/gpio-mvebu.c (c086ac8c)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_level_irq_unmask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_level_irq_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_edge_irq_unmask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_edge_irq_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_ack
```
```
In drivers/soc/dove/pmu.c (c0933ec4)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - drivers/soc/dove/pmu.c:pmu_irq_handler
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
In kernel/irq/generic-chip.c (c0000000001dd338)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
```
```
In drivers/irqchip/irq-al-fic.c (c000000000820610)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type
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
In kernel/irq/generic-chip.c (ffffffe000119cf4)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
```
```
In drivers/irqchip/irq-al-fic.c (ffffffe00049532e)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type
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
In kernel/irq/generic-chip.c (ffffffff81115717)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
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
In kernel/irq/generic-chip.c (ffffffff81106427)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
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
In kernel/irq/generic-chip.c (ffffffff81113607)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
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
In kernel/irq/generic-chip.c (ffffffff8111ec67)
Location: include/linux/irq.h:1141
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
```
</details>
</li>
</ul>

## Differences
