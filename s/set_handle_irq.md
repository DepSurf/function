# Function: <code>set_handle_irq</code>

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
int set_handle_irq(void (*handle_irq)(struct pt_regs *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffff8000114466d4)
Location: kernel/irq/handle.c:214
Inline: False
Direct callers:
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_l1_intc_of_init
  - drivers/irqchip/irq-gic.c:__gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
```
**Symbols:**

```
ffff8000114466d4-ffff800011446714: set_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int set_handle_irq(void (*handle_irq)(struct pt_regs *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (c1520d40)
Location: kernel/irq/handle.c:214
Inline: False
Direct callers:
  - arch/arm/mach-imx/tzic.c:tzic_init_dt
  - drivers/irqchip/irq-hip04.c:hip04_of_init
  - drivers/irqchip/irq-orion.c:orion_irq_init
  - drivers/irqchip/irq-omap-intc.c:intc_of_init
  - drivers/irqchip/irq-gic.c:__gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/irqchip/irq-rda-intc.c:rda8810_intc_init
  - drivers/irqchip/irq-aspeed-vic.c:avic_of_init
```
**Symbols:**

```
c1520d40-c1520d74: set_handle_irq (STB_GLOBAL)
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
int set_handle_irq(void (*handle_irq)(struct pt_regs *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffe000008200)
Location: kernel/irq/handle.c:214
Inline: False
Direct callers:
  - drivers/irqchip/irq-sifive-plic.c:plic_init
```
**Symbols:**

```
ffffffe000008200-ffffffe000008232: set_handle_irq (STB_GLOBAL)
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
