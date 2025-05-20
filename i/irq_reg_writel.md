# Function: <code>irq_reg_writel</code>

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
In kernel/irq/generic-chip.c (ffffffff810df072)
Location: include/linux/irq.h:919
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg_and_ack
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg_and_ack
  - kernel/irq/generic-chip.c:irq_gc_eoi
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
In kernel/irq/generic-chip.c (ffffffff810e55d0)
Location: include/linux/irq.h:958
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg_and_ack
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
In kernel/irq/generic-chip.c (ffffffff810ebee0)
Location: include/linux/irq.h:983
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg_and_ack
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
In kernel/irq/generic-chip.c (ffffffff810eb780)
Location: include/linux/irq.h:1096
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg_and_ack
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
In kernel/irq/generic-chip.c (ffffffff810f3cf0)
Location: include/linux/irq.h:1125
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
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
In kernel/irq/generic-chip.c (ffffffff810fc0e0)
Location: include/linux/irq.h:1127
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
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
In kernel/irq/generic-chip.c (ffffffff811078b0)
Location: include/linux/irq.h:1129
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
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
In kernel/irq/generic-chip.c (ffffffff81110e6b)
Location: include/linux/irq.h:1142
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
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
In kernel/irq/generic-chip.c (ffffffff8111d0cb)
Location: include/linux/irq.h:1160
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
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
In kernel/irq/generic-chip.c (ffffffff811293f8)
Location: include/linux/irq.h:1190
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
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
In kernel/irq/generic-chip.c (ffffffff81124cc8)
Location: include/linux/irq.h:1195
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
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
In kernel/irq/generic-chip.c (ffffffff81125088)
Location: include/linux/irq.h:1197
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
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
In kernel/irq/generic-chip.c (ffffffff81145728)
Location: include/linux/irq.h:1199
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
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
In kernel/irq/generic-chip.c (ffffffff81169827)
Location: include/linux/irq.h:1203
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
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
In kernel/irq/generic-chip.c (ffffffff8119e187)
Location: include/linux/irq.h:1220
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
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
In kernel/irq/generic-chip.c (ffffffff811b0027)
Location: include/linux/irq.h:1233
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
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
In kernel/irq/generic-chip.c (ffffffff811bfd57)
Location: include/linux/irq.h:1215
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
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
In kernel/irq/generic-chip.c (ffff800010181e60)
Location: include/linux/irq.h:1160
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
```
```
In drivers/irqchip/irq-sunxi-nmi.c (ffff800011471310)
Location: include/linux/irq.h:1160
Inline: True
Inline callers:
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_irq_init
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_irq_init
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_set_type
```
```
In drivers/irqchip/irq-brcmstb-l2.c (ffff800010677570)
Location: include/linux/irq.h:1160
Inline: True
Inline callers:
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_resume
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_resume
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_resume
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_suspend
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_suspend
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_mask_and_ack
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_mask_and_ack
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff80001069829c)
Location: include/linux/irq.h:1160
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_resume
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_suspend
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
In kernel/irq/generic-chip.c (c03d173c)
Location: include/linux/irq.h:1160
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
```
```
In drivers/pinctrl/pinctrl-rockchip.c (c083b0e8)
Location: include/linux/irq.h:1160
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_resume
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (c0000000001dd1f8)
Location: include/linux/irq.h:1160
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffe000119c08)
Location: include/linux/irq.h:1160
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
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
In kernel/irq/generic-chip.c (ffffffff811156ab)
Location: include/linux/irq.h:1160
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
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
In kernel/irq/generic-chip.c (ffffffff811063bb)
Location: include/linux/irq.h:1160
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
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
In kernel/irq/generic-chip.c (ffffffff8111359b)
Location: include/linux/irq.h:1160
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
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
In kernel/irq/generic-chip.c (ffffffff8111ebeb)
Location: include/linux/irq.h:1160
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
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
