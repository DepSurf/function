# Function: <code>irqchip_init</code>

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
void irqchip_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irqchip.c (ffff800011470568)
Location: drivers/irqchip/irqchip.c:27
Inline: False
Direct callers:
  - arch/arm64/kernel/irq.c:init_IRQ
```
**Symbols:**

```
ffff800011470568-ffff8000114705a8: irqchip_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void irqchip_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irqchip.c (c154967c)
Location: drivers/irqchip/irqchip.c:27
Inline: False
Direct callers:
  - arch/arm/kernel/irq.c:init_IRQ
  - arch/arm/mach-exynos/exynos.c:exynos_init_irq
  - arch/arm/mach-highbank/highbank.c:highbank_init_irq
  - arch/arm/mach-mvebu/board-v7.c:mvebu_init_irq
  - arch/arm/mach-imx/mach-imx6q.c:imx6q_init_irq
  - arch/arm/mach-imx/mach-imx6sl.c:imx6sl_init_irq
  - arch/arm/mach-imx/mach-imx6sx.c:imx6sx_init_irq
  - arch/arm/mach-imx/mach-imx6ul.c:imx6ul_init_irq
  - arch/arm/mach-imx/mach-imx7d.c:imx7d_init_irq
  - arch/arm/mach-omap2/omap4-common.c:omap_gic_of_init
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
  - arch/arm/mach-shmobile/setup-r8a7778.c:r8a7778_init_irq_dt
  - arch/arm/mach-shmobile/setup-r8a7779.c:r8a7779_init_irq_dt
  - arch/arm/mach-tegra/tegra.c:tegra_dt_init_irq
```
**Symbols:**

```
c154967c-c15496a0: irqchip_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void irqchip_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irqchip.c (c0000000013a0bcc)
Location: drivers/irqchip/irqchip.c:27
Inline: False
```
**Symbols:**

```
c0000000013a0bcc-c0000000013a0c08: irqchip_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void irqchip_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irqchip.c (ffffffe00002a8bc)
Location: drivers/irqchip/irqchip.c:27
Inline: False
Direct callers:
  - arch/riscv/kernel/irq.c:init_IRQ
```
**Symbols:**

```
ffffffe00002a8bc-ffffffe00002a8e6: irqchip_init (STB_GLOBAL)
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
