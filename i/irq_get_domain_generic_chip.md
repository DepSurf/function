# Function: <code>irq_get_domain_generic_chip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff810df240)
Location: kernel/irq/generic-chip.c:337
Inline: False
```
**Symbols:**

```
ffffffff810df240-ffffffff810df26b: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff810e4bb0)
Location: kernel/irq/generic-chip.c:337
Inline: False
```
**Symbols:**

```
ffffffff810e4bb0-ffffffff810e4bdb: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff810eb523)
Location: kernel/irq/generic-chip.c:351
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
**Symbols:**

```
ffffffff810eb4c0-ffffffff810eb4fe: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff810eadeb)
Location: kernel/irq/generic-chip.c:350
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
**Symbols:**

```
ffffffff810ead90-ffffffff810eadc9: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff810f333b)
Location: kernel/irq/generic-chip.c:358
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
**Symbols:**

```
ffffffff810f32e0-ffffffff810f3319: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff810fb5df)
Location: kernel/irq/generic-chip.c:359
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
**Symbols:**

```
ffffffff810fb4e0-ffffffff810fb515: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff81106d9f)
Location: kernel/irq/generic-chip.c:359
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
**Symbols:**

```
ffffffff81106ca0-ffffffff81106cda: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff81110361)
Location: kernel/irq/generic-chip.c:359
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
**Symbols:**

```
ffffffff811102e0-ffffffff8111031c: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff8111c5c1)
Location: kernel/irq/generic-chip.c:359
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
**Symbols:**

```
ffffffff8111c540-ffffffff8111c57c: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff81128f31)
Location: kernel/irq/generic-chip.c:359
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
**Symbols:**

```
ffffffff811288a0-ffffffff811288dc: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff81124801)
Location: kernel/irq/generic-chip.c:359
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
**Symbols:**

```
ffffffff811241c0-ffffffff811241fc: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff81124b61)
Location: kernel/irq/generic-chip.c:360
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
**Symbols:**

```
ffffffff81124510-ffffffff8112454c: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff811451f1)
Location: kernel/irq/generic-chip.c:363
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
**Symbols:**

```
ffffffff81144b10-ffffffff81144b4c: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff8116934f)
Location: kernel/irq/generic-chip.c:366
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
**Symbols:**

```
ffffffff81168b10-ffffffff81168b61: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff8119dc1f)
Location: kernel/irq/generic-chip.c:366
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
**Symbols:**

```
ffffffff8119d330-ffffffff8119d381: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff811afabf)
Location: kernel/irq/generic-chip.c:366
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
**Symbols:**

```
ffffffff811af1c0-ffffffff811af213: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff811bf79f)
Location: kernel/irq/generic-chip.c:370
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
**Symbols:**

```
ffffffff811bedc0-ffffffff811bee13: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffff80001018139c)
Location: kernel/irq/generic-chip.c:359
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
Direct callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_handler
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_irq_init
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
```
**Symbols:**

```
ffff800010180b98-ffff800010180bf8: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (c03d0c60)
Location: kernel/irq/generic-chip.c:359
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
Direct callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_handler
  - drivers/irqchip/irq-orion.c:orion_bridge_irq_init
  - drivers/irqchip/irq-orion.c:orion_bridge_irq_handler
  - drivers/irqchip/irq-orion.c:orion_irq_init
  - drivers/irqchip/irq-orion.c:orion_handle_irq
  - drivers/irqchip/irq-omap-intc.c:intc_of_init
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/soc/dove/pmu.c:dove_init_pmu_irq
```
**Symbols:**

```
c03d0a40-c03d0a94: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (c0000000001db970)
Location: kernel/irq/generic-chip.c:359
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
Direct callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
```
**Symbols:**

```
c0000000001db850-c0000000001db8a8: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffe000118d4a)
Location: kernel/irq/generic-chip.c:359
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
Direct callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
```
**Symbols:**

```
ffffffe000118bea-ffffffe000118c3e: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff81114ba1)
Location: kernel/irq/generic-chip.c:359
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
**Symbols:**

```
ffffffff81114b20-ffffffff81114b5c: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff811058b1)
Location: kernel/irq/generic-chip.c:359
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
**Symbols:**

```
ffffffff81105830-ffffffff8110586c: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff81112a91)
Location: kernel/irq/generic-chip.c:359
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
**Symbols:**

```
ffffffff81112a10-ffffffff81112a4c: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct irq_chip_generic *irq_get_domain_generic_chip(struct irq_domain *d, unsigned int hw_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff8111e221)
Location: kernel/irq/generic-chip.c:359
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
```
**Symbols:**

```
ffffffff8111e1a0-ffffffff8111e1dc: irq_get_domain_generic_chip (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
