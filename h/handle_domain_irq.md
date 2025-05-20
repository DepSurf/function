# Function: <code>handle_domain_irq</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-bcm2835.c (ffff80001008167c)
Location: include/linux/irqdesc.h:171
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm2835.c:bcm2835_handle_irq
```
```
In drivers/irqchip/irq-bcm2836.c (ffff8000100816f4)
Location: include/linux/irqdesc.h:171
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_handle_irq
```
```
In drivers/irqchip/irq-sun4i.c (ffff8000100817c0)
Location: include/linux/irqdesc.h:171
Inline: True
Inline callers:
  - drivers/irqchip/irq-sun4i.c:sun4i_handle_irq
```
```
In drivers/irqchip/irq-gic.c (ffff800010081880)
Location: include/linux/irqdesc.h:171
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_handle_irq
```
```
In drivers/irqchip/irq-gic-v3.c (ffff8000100819b4)
Location: include/linux/irqdesc.h:171
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
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
In arch/arm/mach-imx/tzic.c (c0302328)
Location: include/linux/irqdesc.h:171
Inline: True
Inline callers:
  - arch/arm/mach-imx/tzic.c:tzic_handle_irq
```
```
In drivers/irqchip/irq-hip04.c (c0302398)
Location: include/linux/irqdesc.h:171
Inline: True
Inline callers:
  - drivers/irqchip/irq-hip04.c:hip04_handle_irq
```
```
In drivers/irqchip/irq-orion.c (c030243c)
Location: include/linux/irqdesc.h:171
Inline: True
Inline callers:
  - drivers/irqchip/irq-orion.c:orion_handle_irq
```
```
In drivers/irqchip/irq-omap-intc.c (c03024ac)
Location: include/linux/irqdesc.h:171
Inline: True
Inline callers:
  - drivers/irqchip/irq-omap-intc.c:omap_intc_handle_irq
```
```
In drivers/irqchip/irq-gic.c (c0302564)
Location: include/linux/irqdesc.h:171
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_handle_irq
```
```
In drivers/irqchip/irq-gic-v3.c (c0302608)
Location: include/linux/irqdesc.h:171
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
```
```
In drivers/irqchip/irq-armada-370-xp.c (c0302740)
Location: include/linux/irqdesc.h:171
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_handle_irq
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_handle_msi_irq
```
```
In drivers/irqchip/irq-rda-intc.c (c0302800)
Location: include/linux/irqdesc.h:171
Inline: True
Inline callers:
  - drivers/irqchip/irq-rda-intc.c:rda_handle_irq
```
```
In drivers/irqchip/irq-aspeed-vic.c (c0302878)
Location: include/linux/irqdesc.h:171
Inline: True
Inline callers:
  - drivers/irqchip/irq-aspeed-vic.c:avic_handle_irq
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
