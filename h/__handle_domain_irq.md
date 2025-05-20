# Function: <code>__handle_domain_irq</code>

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
int __handle_domain_irq(struct irq_domain *domain, unsigned int hwirq, bool lookup, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffff800010177bd0)
Location: kernel/irq/irqdesc.c:659
Inline: False
Direct callers:
  - drivers/irqchip/irq-bcm2835.c:bcm2835_handle_irq
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_handle_irq
  - drivers/irqchip/irq-sun4i.c:sun4i_handle_irq
  - drivers/irqchip/irq-gic.c:gic_handle_irq
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
```
**Symbols:**

```
ffff800010177bd0-ffff800010177c90: __handle_domain_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __handle_domain_irq(struct irq_domain *domain, unsigned int hwirq, bool lookup, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c03c95a0)
Location: kernel/irq/irqdesc.c:659
Inline: False
Direct callers:
  - arch/arm/kernel/irq.c:asm_do_IRQ
  - arch/arm/mach-imx/tzic.c:tzic_handle_irq
  - drivers/irqchip/irq-hip04.c:hip04_handle_irq
  - drivers/irqchip/irq-orion.c:orion_handle_irq
  - drivers/irqchip/irq-omap-intc.c:omap_intc_handle_irq
  - drivers/irqchip/irq-gic.c:gic_handle_irq
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_handle_irq
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_handle_msi_irq
  - drivers/irqchip/irq-rda-intc.c:rda_handle_irq
  - drivers/irqchip/irq-aspeed-vic.c:avic_handle_irq
```
**Symbols:**

```
c03c95a0-c03c9660: __handle_domain_irq (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
