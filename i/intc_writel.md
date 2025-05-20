# Function: <code>intc_writel</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-omap-intc.c (c154a9d8)
Location: drivers/irqchip/irq-omap-intc.c:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-omap-intc.c:intc_of_init
  - drivers/irqchip/irq-omap-intc.c:omap_intc_handle_irq
  - drivers/irqchip/irq-omap-intc.c:omap3_intc_suspend
  - drivers/irqchip/irq-omap-intc.c:omap_irq_soft_reset
  - drivers/irqchip/irq-omap-intc.c:omap_irq_soft_reset
  - drivers/irqchip/irq-omap-intc.c:omap_mask_ack_irq
  - drivers/irqchip/irq-omap-intc.c:omap3_intc_resume_idle
  - drivers/irqchip/irq-omap-intc.c:omap3_intc_resume_idle
  - drivers/irqchip/irq-omap-intc.c:omap3_intc_prepare_idle
  - drivers/irqchip/irq-omap-intc.c:omap3_intc_prepare_idle
  - drivers/irqchip/irq-omap-intc.c:omap_intc_restore_context
  - drivers/irqchip/irq-omap-intc.c:omap_intc_restore_context
  - drivers/irqchip/irq-omap-intc.c:omap_intc_restore_context
  - drivers/irqchip/irq-omap-intc.c:omap_intc_restore_context
  - drivers/irqchip/irq-omap-intc.c:omap_intc_restore_context
  - drivers/irqchip/irq-omap-intc.c:omap_intc_restore_context
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
